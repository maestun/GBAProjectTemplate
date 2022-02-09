# GBA Project Template for Visual Studio Code

Supports debugging with GDB; tested with the following configuration:
- macOS Big Sur (11.6.1)
- Visual Studio Code (1.64.1)
- mGBA 0.9.3
- devkitARM release 56

## Prerequisites

### Development tools

- [Install Visual Studio Code](https://github.com/microsoft/vscode)
- [Install devkitPro](https://devkitpro.org/wiki/Getting_Started)

### Install GBA emulator

- [Install mGBA](https://mgba.io/downloads.html)

### Install Visual Studio Code extensions

- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- [Native Debug](https://marketplace.visualstudio.com/items?itemName=webfreak.debug)

## Configure and run

Edit the ```.vscode/settings.json```file and change the paths to mGBA and devkitPro's GDB (if needed).

Pressing F5 should launch mGBA with an active GDB server, then start the debug session.