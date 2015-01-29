##PokuBot
An open source Clash of Clans bot.

###Features
* Auto train troops(all troops)
* Auto opponent finder matching gold, elixir, dark elixir criterias
* Auto attack with different attack strategies
* Attack with Barb King/Archer Queen and use the ability.
* Or you can just use it to find opponents, be notified when there is a match, and attack manually.
* Detect empty collectors
* Disconnect detector. You cannot run game for more than 6 hours at a time, you will be disconnected after that for 5 min, it will reload you again. Or in case something goes wrong and bot dies, you will get disconnected from inactivity, and it will log you back in and start again.

###Requirements
* Windows OS
* [BlueStacks] (http://www.bluestacks.com/) [(Tutorial here)](http://cocland.com/tutorials/play-clash-clans-pc-bluestacks)
* [Java 8 JRE] (http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html)
* You must run BlueStacks window on foreground, make sure nothing gets in front of it. I will add background mode in the future.
* Bot uses down arrow key to zoom up, make sure that key zooms up for you as well.
* Do not click CTRL key when bot is running, if you make a ctrl and mouse click, you will see BlueStacks is zooming(If not you are lucky, mine does). It will interfere with bot's clicks.
* Make sure your display&pc never goes to sleep.(power settings)
* You need to have at least level 4 barracks(it should have boost and boost all options)

###Instructions
Download the latest version of PokuBot from [releases page](https://github.com/norecha/pokubot/releases) and run the .jar file.

Make sure you are running it with java 8, not with an older version of Java.
Right click to .jar file, Properties -> Open with -> Change -> Browse.
Then choose javaw.exe in your jre8 or jdk8 installation path, ex: C:\Program Files\Java\jre1.8.0_25\bin\javaw.exe

BlueStacks must run in 860x720 resolution, it will automatically set that up, but in case it fails, you have to do it manually.

After PokuBot is opened, click start to go through setup, write down your settings and hit save.
You can change the values while bot is running too, just don't forget to click save.

All settings are saved under %appdata%/PokuBot/config.properties.
In case barracks configuration went wrong and you want to reset it, you can delete this file.

###Recommended Settings
* At least 170k for resources, so you increase the chance of getting a base with full collectors.
* Auto Attack: Attack 4 Side Parallel 2 Half Wave
* Detect empty collectors: true
* Rax 1: barb
* Rax 2: barb
* Rax 3: archer
* Rax 4: archer

*If one or more of your rax are upgrading, you need to set remaining ones to "No Unit"

###Issues
Bot is still in its early stages, I have not tested with different machines. If there are bugs/suggestions, create an issue and attach the log file.

###Donate
If you like PokuBot consider a donation to support further development. Click
[here!](https://cdn.rawgit.com/norecha/pokubot/master/donate2.html)
