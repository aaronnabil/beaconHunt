beaconHunt 
==========

beaconHunt is a Mobile App for use in Treasure or Scavenger Hunts to locate Bluetooth Low Energy devices.  This started as an exploration of the BLE technology and has evolved into an attempt to make something useful.

While any advertising BLE beacon can be used, I am using low-power modules with an Arduino Pro Mini and RF24L01+ module.

A detailed description is provided at http://hobbies.boguerat.com

CONCEPT
-------
The idea is that the game parameters are established on the SQL Server.  The players would download the app, which would retrieve the game info.  For each beacon several hint’s are given, including small picture.  When the player gets within several feet of the beacon, the item is marked as found and points are awarded based on how many hints were used.  After a set amount of time the game ends and the person/group with the most points will win.  

Folders:
--------
*	www - www folder files for use in Cordova(EVOThings BLE plugin required) or Evothings Studio.
*	ArduinoBeacon - Arduino Code for beacons.
*	PHP_MySQL - PHP Code to return game data from MySQL database and SQL to import data structure.

TODO’s:
-------
*	Upload scores at the end of the game.  Display results on website or all apps involved.
*	Allow custom games via separate app or website.  User would enter game code to retrieve.
*	And much more…

