# Beta 0.2

### 10/22/2025

### Overview

This update is to fix a few bugs from the 0.1B update as well as fill in some gaps in various jobs and scripts.&#x20;

### Out Of City

* Updated the ingredient list options for Restaurants to select from. (Page is not complete but list is complete)
* Corrected several more locations where the rules didn't properly reflect Point Hope RP

### General Updates:

* Duct tape can be purchased from PDM, this will repair the players car but not fully. It will only work to get a broken engine in good enough shape to get to a mechanic shop.&#x20;
* Most food and drink can be consumed. Nutritional gains are not tuned but will always be less than food and drink from a whitelisted business.&#x20;
* Fixed offline Weapon License Ped
* There are now two types of bandages the `Cheap Bandage` that you can buy at Public Stores/Pharmacy these can be used by normal players to stop bleeding and heal a small amount. `Highgrade Bandage` are used by EMS to treat wounds of players.&#x20;
* Adrenaline is an illegal item that the player can use to revive a friend from a downed state, this can be found at black markets.

{% hint style="info" %}
The animation for Adrenaline and Makeshift Bandage will be fixed, they are currently placeholder.&#x20;
{% endhint %}

* Disabled Pure mode, will use a custom anti-cheat so we don't need the annoyance of pure mode.&#x20;

### Clothing/Character

* Generic GTA Peds removed from the character creation menu. They do not work will with custom improved bodies and faces.

### Whitelist Jobs:

* Fixed issue with Music not working properly for restaurants
* Fixed pay and added missing owner job role for several jobs imported from an old config.&#x20;
* Leapfrog Cafe job script is disabled.
* Reds now has a spawner garage with a box truck for picking up parts from Auto Stores and a Tow Truck (Towing doesn't work yet) - other Tow Truck options will be added later. (All Mech shops will get Tow trucks, we will not have a SADOT/Gov't Owned Towing players can call Mech shops for a Tow and PD can call mech shops for a Tow.&#x20;
* Added Auto Parts shops in Sandy and Paleto only accessible by Mech shops. Paleto sells Engines and EV Parts, Sandy sells everything else.&#x20;

{% hint style="warning" %}
Current engine options are generic placeholders. Soon there will be all kinds of engine swap options available for the player to select from.&#x20;

ENGINES SWAPS ARE NOT GURANTEED TO BE UPGRADES THIS WILL BE FIXED IN TIME

There will be a detailed guide about each part and what they are for and how the script works overall created.&#x20;
{% endhint %}

### Cars/Vehicles

* Fixed issue with EMS and LEO dealerships not properly displaying on the Live server.&#x20;
* LEO and EMS cars can no longer be hotwired.
* LEO can jump in and drive any PD car without keys.&#x20;
* Fixed engine sound on the new 204s Bravado Xenon, Xenon RTS and Xenon RTS widebody, tuned and added to VIP (based on the Dodge Neon and Neon SRT)

### EMS

* Added missing radial menu option for customizing vehicles and duty toggle

### Police/LEO/Prison

* Hid blips for LEO mech shops to reduce clutter
* Gunracks configured to work with all cars in the fleet.&#x20;
* Gunrack can be opened with Radial Menu (Z) or with `/cargunrack`&#x20;
* Fixed garage to allow cars to be parked

