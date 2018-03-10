# You need to modify this or you will be banned by BattleEye
![Imgur](https://i.imgur.com/9yh84NO.png)
![Boat](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/boat.png?raw=true)
![Buggy](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/buggy.png?raw=true)
![Enemy](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/arrow.png?raw=true)
![Player](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/player.png?raw=true)
![Nade](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/grenade.png?raw=true)
![Jetski](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/jetski.png?raw=true)
![Parachute](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/parachute.png?raw=true)


* F1 -> Combat Mode 
* F2 -> Filter Throwables
* F3 -> Show / Hide Compass
* F4 -> Toggle Vehicle Names 
* F5 -> Toggle Vehicles
* F6 ->  Camera Zoom ++
* F7 -> Camera Zoom --
* F8 -> Toggle View Line

* NUM1 -> Filter Weapons
* NUM2 -> Filter Attachments
* NUM3 -> Filter Level 2 Gear
* NUM4 -> Filter Scopes           
* NUM5 -> Filter Meds
* NUM6 -> Filter Ammo
* NUM7 -> Player Information Panel
           

# Changes
* Get self player's location by parsing `CharMoveComp` RPC. So the player's direction is corrected now. 
* Get item's relative locaiton by `DroppedItemInteractionComponent`. So the item location is corrected now.
* Change `readRotator()` to `readRotationShort()` fixes empty player state.
* `DroppedItem` is shown.
* Fully parse `ATslCharacter`. So player health is shown.
* Correct player color when driving.
* `Equipped weapons` are shown.
* Clear `DroppedItem` and `DroppedItemGroup` when `picking up`.
