---
description: 12/29/2025
---

# Beta 0.5

### General

* FiveM updated to newest server version
* Windows updates done on the host server (considering a host change due to all the 1of1 DDoS issues  the last several months)
* IDs have been overhauled new system installed. New system allows for Job badges for both whitelisted and non whitelisted jobs.
* City Hall no longer allows you to buy a weapon license

{% hint style="info" %}
Throw away your old IDs, head to City Hall and grab your new ones.&#x20;

LEO you will need to reissue the Weapon License in MDT for those who already have it in order to sync the license to the new system and allow it to be purchased.
{% endhint %}

* Car registration is now granted when a car is purchased. New registration and insurance can be purchased at the new DMV near the VIP car dealership. Registration and insurance shows on the players profile in the MDT for LEO.
* F10 no longer conflicts with the other key binds for the Bug Menu. To submit a bug report from in city please use  `/bug`
* Civilian population has returned (will be turned over time to use our proper area and time based population)
* Blackmarket crypto shop has been combined with the Hackers shop into a single electronics black market
* Bee Keeping has been tuned.
* Phones now have access to lots of wallpapers using the Wallpaper app. Limited to 200 API requests per hour.
* Lots of logs have been added to discord and our Loki Logging

### Radios

<table><thead><tr><th width="128">Channel</th><th>Departments</th></tr></thead><tbody><tr><td>1</td><td>LEO Joint Comms</td></tr><tr><td>2</td><td>LSPD</td></tr><tr><td>3</td><td>LSPD</td></tr><tr><td>4</td><td>BCSO UNUSED</td></tr><tr><td>5</td><td>BCSO UNUSED</td></tr><tr><td>6</td><td>DOC UNUSED</td></tr><tr><td>7</td><td>DOJ UNUSED</td></tr><tr><td>8</td><td>EMS</td></tr><tr><td>9</td><td>SASP UNUSED</td></tr><tr><td>10</td><td>TOW (All mech shops, LEO and EMS)</td></tr></tbody></table>

{% hint style="info" %}
All channels have sub channels that are locked to the same department. So channel 2.1 is also locked to LSPD
{% endhint %}

### LEO and EMS

{% hint style="danger" %}
Offline weapon license now checks if the player has an active warrant before allowing purchasing.&#x20;
{% endhint %}

* Police Job has new rank (Sr. Officer) any current officers will need their jobs adjusted.
* EMS Body Cam access is available at the computer in the main CEO office (a second boss menu will be added here later)
* Scripts updated to support the new rank (may have missed a few)
* Panic button now on radial menu
* Updated MDT script to newest version
* Set Body Cam for PD on top floor at the PD
* Public Citation target adjusted slightly
* Police and EMS can use `/mdt_settings` to adjust their MDT settings
* Police and EMS can now keybind Bodycam, MDT and Dispatch and use them with a slash command however you do require the item from your armory for them to work.
* Buffalo should no longer be acting like an EV
* Frisking script has been updated with new custom animation
* Adjusted PD prices in LEO car shop based on last requested change
* TAV/EVAC categories added (will add some vehicles to it soon)
* Mobile fingerprint reader added to the armory. Customized to automatically insert the Fingerprint into the MDT
* New Evidence script in place this replaces previous GSR and Alcohol Kit and provides more toys. Now under the Crime Lab tab in Armory both GSR and BAC test are now in radial
* Crime Scene access is at the computer on the second floor near the pin board
* Jailing added to radial menu
* Police can issue fines in two ways (First the they can use the Citation Notepad to issue paper traffic citations, these citations integrate into the MDT and can be seen in the Players citizen profile and must be paid at the police station at the clerk at the desk. The second way is to create and incident or report, then add the criminal to the incident or report. Once added a page button appears, click the page to added charges. Once added the player can say guilty or not to each charge on the spot, the officer can reduce time or fines and then can click the fine button to issue the fine. Once issued the fines appear appears in the players billing menu (default F7 or will add to phone in time) - The fines can be seen in the PDs Billing menu (f7 under the society tab on the left.
* Police can now get a master key from the armory to gain access to prison locks
* Tested police convoy and set it up to work at the current station.
* MDT now opens the proper prison menu
* Updated the prison convoy to use the our police fleet
* Updated prison clothing for Min, Med and Max security
* EMS Roster and SOP can now be seen in the MDT
* EMS can issue health insurance using `/healthinsurance`
* Players who are auto billed and have health insurance get a 50% discount on their bill (Hospital and EMS player are paid the full amount of the bill before insurance is applied)
* Robbing has been checked and it works, player must be cuffed, ziptied or have their hands up (Hands up has 3 options X, Shift X and Ctrl X) (Conflicting hands up emote has been removed and should)

### Crime

* Meth Warehouse and tables yields has been increased significantly
* Meth processing time in warehouse reduced significantly
* Money wash no longer requires an item to start washing and earning levels
* Money wash spawns in two locations now, these make sense for Washing, the Ped can be found in an office

### Optimizations

* To help load times the inventory images have been reduced in size to be a uniform size of 128x128 allowing you to load into city faster.
* Textures on addon guns have been optimized
* Mapping fixes applied
