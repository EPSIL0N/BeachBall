# BeachBall

Helper addon for Sandcastle Builder (http://castle.chirpingmustard.com/castle.html).

## Features

* Kitties have a timer on top of the screen, to tell you when there is a kitty.
* You can activate Autoclick on kitties, or just an auto-focus on the kitty.
* You can add autoclick on the picture (1 click for keeping ninja, or multiple click per second)
* Logicats can be solved automatically.
* Tool factory can be loaded faster.
* Caged logicat can be automated to solve every logicat one by one, the max at once for QQ, or get bonemeal.
* ~~You can put audio alerts on common events~~ Audio alerts are currently non-functional.

## How to use this script ?

Start by installing this script (http://codeRitter.github.io/BeachBall/) using one of two methods:

A. If you have Greasemonkey (for Firefox) or Tampermonkey (for Chrome), install BeachBall_Monkey_Loader.js (instuctions for using Xmonkey can be found elsewhere). The BeachBall addon will automatically load 5 seconds after loading the game page (you must reload the game page once after installing - don't forget to save).

B. If you do NOT have one of those addons, copy the contents of BeachBall_Bookmark_Loader.js into a bookmark (paste onto the link/location/destination, and not the description or name). You will need to click your bookmark once to get the BeachBall addon to load - EVERY time you reload the game page, you must reclick the bookmark loader.

Once loaded, go in the Option panel of the game, and you will find every option to enable at the bottom of the panel.

## Changelog

###Version 5.2.0.5

####New Features
* Flux Harvest will now be used to harvest flux if it is available.
* NEW: Clear log option. Clears the in-game log to reduce lag.

####Bug Fixes/Improvements
* Improvements to logicat, including max solve fix.

###Version 5.2.0

####Features
* NEW : Favorite autoclick - In the Favorite pannel, you can now assign an autoclick to any set favorite. Doing so will ask you for a timer, and may ask you to choose a button to click if there are multiples. If you proceed so, you will have a timer that you can click for activating and de-activating the timer. You can remove it completely by starting assignation of a new timer and canceling it. This can be used to trigger Question Qubes over time, or improving sand industry regularly after a molping down, reducing repetitive spaming activities in just a few clicks.
* Improving Beach Autoclick by adding an "ninja ritual" setting, that will ninja every NP, gathering goats.
* NEW : Rift Autoclick - 2 settings. "Gather Flux Cristals" will use rifts after they close until you have no more Time Lord rift available, and waiting for the NPB to have been ninja'd. "ONG" will use rifts to create a maximum of ONGs. It will always wait for the game to have sand (for building from blackprints) and will wait for the NPB to have been ninjad.



###Version 5.1.4.0 - .2

####Bug Fixes
* Fixed Logicat countdown and clicker not working with Redacted object rewrited in 3.33331
* Fixed option menu rewriten in same update
* .1 : Fixed Logicat bug with audio alert
* .2 : Fixed display problem with classic layout

###Version 5.1.3

####Bug Fixes
* Fixed Logicat solver to work with latest SCB changes.

###Version 5.1.2

####Bug Fixes
* Fixed Logicat solver to work with latest SCB changes.

###Version 5.1.1

####New Features
* Re-implementing Pure Logicat Solver

###Version 5.1

####New Features
* Logicats in a redundakitty chain are being solved.
* Caged AutoClicker can solve single puzzles (1 per 5 seconds)
* Caged AutoClicker can solve maximum puzzles (using this setting without having ZooKeeper may cause problems)
* Caged AutoClicker can trade 100+ logicats for bonemeal (must have Shadow Dragon unlocked)

###Version 5.0

####New Features
* Caged Logicat Autosolver implemented as Full Auto and re-enabled.

####Temporary Bug Fixes/Workarounds
* Logicats in a redundakitty chain are still set to auto-hide.

###Version 4.9.9

####Temporary Bug Fixes/Workarounds
* Due to massive changes in v3.292 of Sandcastle builder, several features have been disabled in this build to allow it to function until a proper patch can be issued.
* Caged Logicat AutoSolver has been Disabled
* LC Solver will now Auto-Hide Logicats if they spawn.

####Bug Fixes
* LC audio alert fixed.

###Version 4.2

####Bug Fixes
* With high logicat/AC, temporal rift is essentially permanent, preventing Keep Ninja AutoClick from processing. Caged Logicat Autoclicker will now pause to process the click (allow Temporal Rift to expire), then resume.

###Version 4.1

#### New Features
* Can now choose whether you want Monty Haul Problem AutoClicker to try and find a Goat or a Prize (and works with Beret Guy if unlocked).

####Bug Fixes
* Updated list of Redundakitty locations.

###Version 4.0.4

####Bug Fixes
* Fixed Caged Logicat Autoclicker.
* Fixed Tool Factory helper.

###Version 4.0.3

####Bug Fixes
* Removed some debugging notifications that were accidentally left in.

###Version 4.0.2

####Bug Fixes
* Caged Logicat solver is really fully working this time!

###Version 4.0.1

####Bug Fixes
* Caged Logicat solver working again with latest SCB version (v 3.261)

### Version 4.0

#### New Features
* Caged Logicat AutoClicker now implemented
* Monty Haul Problem AutoClicker: AutoBuy if available and Opens Door(s)
* Settings are now saved between sessions if HTML5 local storage is available.

#### Feature Changes
* Simplified AutoClicker and Logicat solver options.
* Redundakitty AutoClicker will no longer open menus to click them (unless the Find RK option is enabled).
* Beach AutoClicker works better (clicks evenly over time, rather than in a large clump every tick).

### Version 3.4.1

#### Bug Fixes
* Fixed to work for people who have not yet unlocked Tool Factory.

### Version 3.4

#### New Features
* Tool Factory option to load a user defined amount of glass chips into the tool factory. Click on the number of chips to change. Click Load Tool Factory to load chips.

#### Bug Fixes
* Removed Border Alerts as this is provided by the Beach Ball boost in game.
* Fixed RedundaKitty and LogiCat AutoClick to work with new layout.
* Changed the LogicCat option item name to more accurately reflect its current ability as it does not AutoClick LC's/Caged LCs, just solves them if available.

### Version 3.3

#### Bug Fixes
* Redundakitty autoclicker will now work when the redundakitty spawns in the Discoveries and Momuments/Glass Monuments tabs.
* Discovery and Monuments menus should now toggle correctly when RK Finder/AutoClicker is enabled.

### Version 3.2

#### Bug Fixes
* Fixed syntax in Bookmark loader (missing semi-colon).
* Fixed minor error in setting auto click CPS change rate dialogue.
* Fixed Beach Auto Click so it should keep going after ninja stealth streak.

### Version 3.1

#### Bug Fixes
* Beach autoclicker will no longer break ninja streak.

###Version 3.0

#### New Features
* Caged Logicat solver implemented (under the Logicat Auto Clicker option).
* Logicat only audio alert implemented.
* Beach Auto Clicker Implemented. Options are "Off", "Keep Ninja" (to only click once per ONG to maintain Ninja streak), and "On" with clicking rate from 1 to 20 CPS (clicks per second).

#### Bug Fixes
* Fixed ONG only audio alert so it actually works.

#### Behind the Scenes
* Namespaced variables/methods in a BeachBall object to prevent potential JS crossover issues. It's not pretty, but I think it works.

### Version 2.1

#### Bug Fixes
* RedundaKitty autoclicker should now properly deal with YouTube RedundaKitties
* RedundaKitty autoclicker should now properly deal with Redundant RedundaKitties
* Ninja streak autoclicker shouldn't click during a temporal rift.

### Version 2.0

#### New Features
* Menu system implemented
* Ninja streak autoclicker implemented
* RedundaKitty finder and autoclicker
* Logicat solver/autoclicker
* Ninja streak visual cues
* Redundakitty audio alerts

===

### Version 1.0
*My really rough first attempts at coding an add-on.
