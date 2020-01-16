  <img src="https://github.com/IceCruelStuff/Steadfast5/blob/master/Steadfast5.png" alt="Steadfast5 logo" title="Aimeos" align="center" />

# Steadfast5 Minecraft: Bedrock Edition Server Software

Click [here](https://github.com/Steadfast5/Steadfast5) to view other repository.

# Links
| Jenkins | TravisCI | Discord |
| :---: | :---: | :---: |
| [![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=plastic)]() | [![Travis branch](https://img.shields.io/badge/Build-Passing-orange?style=plastic)]() |

## Introduction

Steadfast5 is a project for backporting new Minecraft: Bedrock Edition changes to older PocketMine-MP versions for better stability and performance, while retaining as many features from the new PocketMine-MP versions as possible.

## Todo-List

- [x] Forms
- [x] Rcon
- [ ] Add items and blocks
- [x] addTitle function
- [ ] Api update to the latest
- [ ] And more

## Known bugs

- Players don't fall out of the world naturally, you'll want to handle PlayerMoveEvent as needed to kill them.

## Installation
### Installing on Windows
To install on Windows, please follow these instructions. 
1) Open Powershell and type in `git clone --recursive https://github.com/IceCruelStuff/Steadfast5.git` 
2) Run the `start.cmd` file located in your server folder. It will automatically download PHP. If you are running on Windows 8 and below, download the zip file from Github and extract it, then run `start.cmd`. 
3) After running `start.cmd`, you have to complete setup wizard. When you are finished all these steps, the server should start up.

### Installing on Linux/MacOS
To install on Linux/MacOS, please follow these instructions.
1) Open command line and type in `git clone --recursive https://github.com/IceCruelStuff/Steadfast5.git`. Then navigate to `Steadfast5` directory using command line. You can also download the zip file from Github and extract it.
2) Run command `./installer.sh`. If successful, this will create a `bin` folder with a special PHP build in it. After, run command `./start.sh` and the server should start up.

### Windows Installer
This is only for Windows 10. If you don't know how to do any of the steps above, then download the [`source_installer.cmd`](https://github.com/IceCruelStuff/Steadfast5/releases/download/v1.1/source_installer.cmd) from the releases and run it. You can view the script on [GitHub Gist](https://gist.github.com/IceCruelStuff/621339e30c8fb2b0d4d806265f0bbed9).
This is only the Steadfast5 source installer. Click [here](https://github.com/IceCruelStuff/Steadfast5/releases/download/v1.1/installer.cmd) to download the [`installer.cmd`](https://gist.github.com/IceCruelStuff/f52d1071c1d93b707ead302f96c9f248).
