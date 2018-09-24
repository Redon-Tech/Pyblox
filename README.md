# Pyblox

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)]()
[![ROBLOX API Discord](https://img.shields.io/badge/discord-roblox%20api%20chat-blue.svg)](https://discord.gg/EDXNdAT)
[![Downloads](http://pepy.tech/badge/pyblox3)](http://pepy.tech/project/pyblox3)

An API wrapper for Roblox written in Python.

The purpose of this API wrapper is to expose Roblox's API for third party use and/or for individual standalone projects.
This is the first stable Python API wrapper for the Roblox API. Documentation can be found within each module. I encourage
developers to look into the codebase to better understand this wrapper and what it can truly offer. 

This edition allows for a(n) asynchronous interface which allows for non-blocking requests made within Pyblox to be possible.
This is ideal for projects that requires far less "drag" on the main thread.

If you would like to contribute, create a pull request with the changes you made. If you have a complaint, issue or problem, create an issue and I will try to answer as fast as I can. 

### Updating

The Roblox API updates whenever necessary and often the developers don't specify when or why these changes are taking place.
Due to this, this repo could break at anytime. If a break does occur, please open up an issue on this repo detailing the error.

## Installing
As of yet, to obtain this version you must do it manually below:
```
1. Download or Clone this repo
2. Place the "pyblox" folder into C:\Users\YOURUSERNAMEONWINDOWSMACHINE\AppData\Local\Programs\Python\Python35-32\Lib\site-packages
```
MacOS and Linux are supported but installation will vary.
This was developed on a windows-based machine and thus, it's recommended to use windows.

*Please note that the "Clone" method is regulary updated.*

## Examples

All examples can be found @ https://github.com/RbxAPI/Pyblox/tree/async-python3/example .
If you'd like to submit an example, you may open a pull request to this branch. 

## Requirements

- Python 3+
- ``pip requirements.txt``

*note: dependencies may have already been satisfied*

## Related Projects
https://github.com/sentanos/roblox-js
https://github.com/CrescentCode/RobloxCommunication
https://github.com/NoahCristino/robloxlib
https://github.com/winfamy/nodeblox
https://github.com/gamenew09/RobloxAPI
https://github.com/NevermoreFramework/Nevermore
