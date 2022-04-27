# This is a module for  ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## Advanced WorldChat
[![core-build](https://github.com/Gozzim/mod-worldchat/actions/workflows/core-build.yml/badge.svg)](https://github.com/Gozzim/mod-worldchat)
[![CodeFactor](https://www.codefactor.io/repository/github/gozzim/mod-worldchat/badge)](https://www.codefactor.io/repository/github/gozzim/mod-worldchat)

## Description
Advanced WorldChat with detailed options to configure individually 

## Features

- Enable/Disable Chat per command
- Set Chat Name/NameColor/TextColor
- Configure Class/Race/Faction Icons to your need
- Spam Protection
- URL Filters
- Profanity Filters
- Players can join and leave the chat
- Support for custom GM ranks
- And many more options

## Commands

### Player Commands
- `.chat` or `.world` - Write a message in the WorldChat
- `.joinworld` - Join the WorldChat
- `.leaveworld` - Leave the WorldChat
- `/join <WorldChatName>` - Join the WorldChat like a normal Channel (Name configured in conf file)

### GM Commands
- `.wenable` - Enables the WorldChat
- `.wdisable` - Disables the WorldChat (GMs can still send messages)
- `.wmute` - Mute a player in the WorldChat for a certain amount of time or permanently
- `.wunmute` - Unmute a player in the WorldChat

## Installation
```
1) Simply place the module under the `modules` directory of your AzerothCore source. 
2) Import the SQL into the Database.
3) Re-run cmake and launch a clean build of AzerothCore.
```

## Edit module configuration (optional)
If you need to change the module configuration, go to your server configuration folder (where your worldserver or worldserver.exe is), copy worldchat.conf.dist to worldchat.conf and edit that new file.

## Credits
- Module for AzerothCore created by [Gozzim](https://github.com/Gozzim)
- AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/)

## License
This code and content is released under the [GNU AGPL license](https://github.com/Gozzim/mod-worldchat/blob/master/LICENSE).