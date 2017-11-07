# FocusFrame_TargetCastbar
Copies the FocusFrame castbar to work for the default blizz TargetFrame aswell. ([#11](https://github.com/wardz/FocusFrame/issues/11))

This addon is a plugin for FocusFrame and thus requires [FocusFrame (v1.2.3+)](https://github.com/wardz/FocusFrame/) to be installed & enabled.
Install this plugin as you would with any other vanilla addon. (Remember to remove `-master` or version suffix from folder name)

PS: This plugin won't work if you have set `/foption strictaura` to enabled (default off) in FocusFrame.

## Increase combat log distance (optional)
Casts are read from the combat log with a default range of 40 yards.
You may increase this range by running the commands below. Note that this affects performance, especially if you have a lot of addons.

`/console SET CombatLogRangeFriendlyPlayers "100"`

`/console SET CombatLogRangeHostilePlayers "100"`
