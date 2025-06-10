Schedule I Autosplitter – BETA v0.3.6

BIG THANKS to Doublemoses fot his initial project and helping figuring stuff :)

This is an early BETA release of an autosplitter for Schedule I, currently in version v0.3.6. The script is designed to assist with speedrunning by automatically starting the timer and splitting at key milestones. While several core features are already implemented, please note that this version is still in development and may have bugs or missing functionality.

🚧 Current Limitations
Prologue auto-start is not yet implemented, but planned for a future version.

Detection for owned properties and businesses is not yet supported.

Some autosplits may still be unstable or subject to change.


✅ What Works So Far
    Automatic timer start for the main game.
    Autosplits for various game events (see below), all of which are disabled by default and can be enabled manually.Basic split logic improvements have been made compared to earlier versions.

🔧 Installation
    Download the latest .zip from the Releases section.
    Extract the file scheduleI.asl to a convenient location.
    In LiveSplit:
    Open the Layout Editor.
    Go to Control > Scriptable Auto Splitter and add it.
    Double-click the newly added element to open its settings.
    Click Browse next to Script Path and select scheduleI.asl.
    An Advanced section will appear where you can enable/disable specific autosplits.
    Make sure Compare Against is set to Real Time, not Game Time.

✂️ Available Autosplits (disabled by default)
    Split on bed during prologue
        Final split for prologue runs. Cannot trigger later in the game – safe to enable.

    Split on first cash received
        Triggers upon receiving any cash, such as from the first sale or dropbox pickup. Useful for weed%.

    Split when making money after holding meth
        Triggers once player holds meth and later gains money. Used to end meth%.

    Split on receiving OG Kush baggie

    Split on receiving pseudo during prologue

    Split on first time receiving low-quality pseudo

    Split on first time entering a vehicle

    Split on first time buying a chemistry station

    Split when combined money reaches a target value
        Default value is 2079, used to trigger end of meth%. Change it via:
            vars.moneySplitValue = 2079;

    ⚠️ SpeedGrow autosplit is deprecated: Only works with the first two inventory slots and is likely to be removed or fixed in a later version.

🐞 Known Issues
    SpeedGrow split is unreliable, only works in specific inventory slots.
    Prologue auto-start is currently non-functional.
    Property/business detection is still under development.

🚀 Future Plans
    Implement AOB scanning for better patch resistance.
    Add support for prologue auto-start, property detection, and business logic.
    Expand autosplit library based on user requests.
    Eventually refactor the entire codebase for maintainability and stability.

🗣 Feedback & Support
    Have a bug report, suggestion, or split request?
    Reach out to me on the Schedule I Speedrunning Discord: keinfabi

