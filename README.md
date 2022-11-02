!!NoTaint2 Addon for World of Warcraft (Dragon Flight)
--

> Reduce the chance that 3rd-party addons taints the Blizzard Globals/UIDropDownMenu/StaticPopups. To show less ACTION_BLOCKED warnings.

There has always been "taint" issues of the Blizzard's stock UI. But It is even worse in Dragon Flight, because Blizzard's new Edit Mode layout codes combine all the interface subsystems together. Any taint somewhere can be soon spread to all UI components. The result is something like that you can't save Edit Mode Layout, or you can only click Action Buttons to cast spell but not by pressing the hot-keys.

This addon smartly cleans some known taint points, before you entering the Edit Mode, to reduce the chance such things happen.

Remember, it can not bring you a perfect world, but better than before.
