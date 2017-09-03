# Better Realism FreeCol Mod

Original Description from FreeCol Discussion Topic: [New Mod: Better Realism](https://sourceforge.net/p/freecol/discussion/141200/thread/4796e856/)

_See below Changelog for rule updates._

I've made a new mod, its really a ruleset & mod combo really sense it provides a new unit amongest a good number of changes. Its called Better Realism, as the name suggests I attempt to make things a bit more realistic, unit movement, and production, some description mainly.

List of some of the changes:

* Meat is used! It replaces grain for many tiles (as such is technically incompatible with markovoss mod, though shouldn't crash the game or anything, the changes that mod makes to default titles might result in some weirdness with their values).
* New Unit: Expert Hunter - Even has unique graphics (supplied by the "mod" portion sense rulesets can't really reference/use new graphics themselves sadly, otherwise this would just be a ruleset.
* Ship Speeds reversed! - Caravels are now the fastest ships, allowing for more strategic use, and more importantly its more inline as smaller ships tended to be faster.
* Custom Houses now produce 1 trade good per turn (Wanted to set it so it only produces them after you declare your indepence, but don't know how or even if you can)
* Hammer and Tool cost for things are 1/10th of vanilla and tool production has been reduced. - To have production of things on a more realistic time scale, keep in mind these are Individual cities not regions like civilization. No inbalance of course sense AI is equally benefited.
* Water title movement costs reduced to 1 for more realistic movement on water
* Land title movement costs reduced/adjusted and land unit's movement increased for a more realistic travel range given the time that passed per turn.
* Indian references have been changed to native or native american, except for a founding father which actually references it correctly. The data references of course persists to play it safe. Just a title/description thing.
* Native Converts can no found cities and no longer have most manufacturing penalities, only bell and cross penality.
* Indentured Servants and Criminals have mixed penalitys and benefits instead of a straight penalities, giving them some strategic use.

I'll leave you to discover the rest.

Enjoy!

## Contributions
Author: Brandon [masternetra](https://sourceforge.net/u/masternetra/profile/)

## Changelog

**NOTICE: The brgraphics mod MUST be enabled WITH the betterrealism ruleset. The mod provides/enables the graphics for the expert hunter.**

**Installation:** Simply extract the ruleset and mod into the freecol program folder's rule and mod folders.

Usual default freecol installs:

* Windows: C:/program files/freecol/
* Linux: /usr/share/games/freecol/
* (Don't know about mac sorry)

### Version 1.02

* Fixed the Native Converts not showing up by suppling the default brave,pioneer,etc images to graphics mod. (Had thought it would fall to default stuff but guess not).
* Fixed it so that Native Converts can actually equip now, thought I had already did that but it appears that I in fact didn't.
* Cooperation Nation-Type now starts with a Native Convert in the soldier position.
* All starting soldier positions are now equipped as dragoons.

### Version 1.01

* Cleaned up download archive of the backup files.
* Started providing BR version for specification in ruleset.
* Removed Kings Regular from train list (removed price essentially, had tested something and forgot to remove after), but still is a mercenary unit.
* Removed Secondary Production and Normal Primary Production (If town is established on a bonus that boosts the tile's primary food source then the town receives that food production as a primary production, e.g. Grain Bonus on a plain tile will enable the titles primary production of grain for that town).
* Increased free-colonist growth to 300 food.
* Replaced Ore with furs for Arctic tile.
* Added a increase of Trade Goods of 1 (per custom house theoretically) that occurs after Independence (Needs testing as its in the events and haven't been able to play into Independence yet).
* Trade Nation-Type now increases Trade Good production by 1 (For a total of 3 per custom house after independence).
* Both Grain and Meat can be found together in most titles balanced based on title e.g. Meat will still be higher in forests and grain will be minimal or near it pending title and vice versa for plains/grasslands/etc. The bonus possibilities also reflect this of course.
* Native Converts can be trained into a free-colonist/expert by a expert, while free colonists can become a Native Convert by being trained by one (In real life some frontiersmen would meet, learn, and adopt native lifestyles).
* Native Converts now use brave images where they can (handled by the graphics mod part).
* Native Converts now can equip guns,tools, etc. in addition to them being able build colonies (which they've had sense initial release).
* Building Nation-Type now produces 2 additional tools along with its hammers.
* Agriculture Nation-Type now has the meat bonus of 2 instead of Russians and additionally start with the expertHunter in the soldier role.
* Immigration Nation-Type now has the firebrand preacher in the pioneer role.
* Naval Nation-Type now starts with a frigate instead of a merchantman.

### Version 1.0.0

* Initial Release
