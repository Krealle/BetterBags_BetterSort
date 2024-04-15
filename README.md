# BetterBags - BetterSort

Plugin for the AddOn [BetterBags](https://www.curseforge.com/wow/addons/better-bags) that improves the Alphabetical sorting.

Currently the default Alphabetical sorting doesn't remove the color prefix from titles when sorting. So eg. `|cffff8000Armor - Leather` would come after `|cffa335eeArmor - Mail` due to `a` coming before `f` in the comparison:

`|cff`<code style="color : red">f</code>`f8000Armor - Leather`

`|cff`<code style="color : red">a</code>`335eeArmor - Mail`

Since `|` is a special character, the problem actually extends as far as to make the color coded titles always come last in the sorting. This is not intuitive behavior for an Alphabetical sorting. This plugin solves this by stripping color codes before sorting, to ensure proper Alphabetical order.

Without plugin:

![image](https://github.com/Krealle/BetterBags_BetterSort/assets/3404958/d850ed19-8a05-4e34-b583-e3359cefee89)

With plugin:

![image](https://github.com/Krealle/BetterBags_BetterSort/assets/3404958/92d8adba-b1f9-4eaa-8efb-e44fc7a02000)

