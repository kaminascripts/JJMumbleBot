# JJMumbleBot
[![GitHub release](https://img.shields.io/github/release/DuckBoss/JJMumbleBot.svg)](https://github.com/DuckBoss/JJMumbleBot/releases/latest)
[![Packagist](https://img.shields.io/badge/License-GPL-blue.svg)](https://github.com/DuckBoss/JJMumbleBot/blob/master/LICENSE)
[![CodeFactor](https://www.codefactor.io/repository/github/duckboss/jjmumblebot/badge)](https://www.codefactor.io/repository/github/duckboss/jjmumblebot)

A plugin-based python 3 mumble bot with extensive features.


## Features
- <b>Built-in Plugins</b> - Fast, responsive, plugin-based system for easy expandability.
  - <b>Youtube Plugin</b> - Streams youtube songs in the channel.
  - <b>Images Plugin</b> - Posts images from urls or from a local directory in the channel.
  - <b>Sound Board Plugin</b> - Sound Board that plays short wav audio clips in the channel.
  - <b>Randomizer Plugin</b> - Do custom dice rolls, coin flips, etc in the channel.
  - <b><a href="https://github.com/DuckBoss/JJMumbleBot/wiki/Quick-Start">Full list of built-in plugins</a></b>
- <b>Support for adding plugins at runtime.</b>
- <b><a href="https://github.com/DuckBoss/JJMumbleBot/wiki/Plugins">Support for custom plugins</a></b>
- <b>Event logging to keep track of bot usage and command history.</b>
- <b>Multi-Command Input</b> - Input multiple commands in a single line.
- <b>Command Aliases</b> - Register custom aliases to shorten command calls.
- <b>Custom Command Tokens</b> - Custom command recognition tokens (ex: !command, ~command, /command, etc)
- <b>Command Tick Rates</b> - Commands in the queue are processed by the tick rate assigned in the config.
- <b>Multi-Threaded Command Processing</b> - Commands in the queue are handled in multiple threads for faster processing.

### Plans For Upcoming Updates:
- [ ] <b>New Built-in Plugin: Voting System (!vote)</b> (I will probably be adding this to the <a href="https://github.com/DuckBoss/JJMumbleBot-PluginLibrary">Extra plugin library repository</a>)

## Wiki
<b> Please check out the wiki for documentation </b> <br>
<a href="https://github.com/DuckBoss/JJMumbleBot/wiki">https://github.com/DuckBoss/JJMumbleBot/wiki</a> <br>
<b> Quick Start guide: </b> <br>
<a href="https://github.com/DuckBoss/JJMumbleBot/wiki/Quick-Start">https://github.com/DuckBoss/JJMumbleBot/wiki/Quick-Start</a> <br>

## Extra Plugins:
<a href="https://github.com/DuckBoss/JJMumbleBot-PluginLibrary">https://github.com/DuckBoss/JJMumbleBot-PluginLibrary</a>

## Legacy Branches:
- <b>pre-v1.3</b> - A legacy branch for pre-v1.3. <br>
v1.3 implemented a new config system that required reconfiguring the config.ini file if a user was updating to v1.3.
- <b>pre-v1.4</b> - A legacy branch for pre-v1.4. <br>
v1.4 implemented a new and upgraded user privilege system that required how user privileges are handled and an update to the plugin template requiring the updating of all plugins.
- <b>pre-v1.5</b> - A legacy branch for pre-v1.5. <br>
v1.5 implemented a way to send commands to the bot, command queues, command tick rates, updated built-in plugins, and fixed some major bugs. <br>
#### Need a very specific version of the legacy branches? <br>Check out the full list of tags here : <a href="https://github.com/DuckBoss/JJMumbleBot/tags">Release Tags</a>
