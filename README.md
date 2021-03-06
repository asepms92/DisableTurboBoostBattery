# DisableTurboBoostBattery

A simple kernel extension to turn off Intel's Turbo Boost when the power adapter is unplugged and, of course, to turn it back on when it is plugged in again.

Pretty much none of the code is mine:

- the actual code that disables Turbo Boost is Copyright (c) 2012 Adam Strzelecki and was taken from here: https://github.com/nanoant/DisableTurboBoost.kext/
- the code that monitors the power state is Copyright 2012 Pavel Prokofiev. All rights reserved and was taken from here: http://code.google.com/p/macosx-nosleep-extension/

Inspiration was also taken from InsomniaX: http://code.google.com/p/insomnia-kext/

A binary for OS X 10.8, 64-bit can be found [here.](http://osxlatitude.com/index.php?/topic/2263-disable-intel-turbo-boost-on-battery-power/)

### Installation

Just Downloads [Latest Release](https://github.com/asepms92/DisableTurboBoostBattery/releases) and install to /Library/Extensions or Inject by Bootloader

Open Terminal and commands:

- sudo cp -R ~/Downloads/DisableTurboBoostBattery/DisableTurboBoostBattery.kext /Library/Extensions
- then reboot

### Credits :

- Original from [nanoant](https://github.com/nanoant/DisableTurboBoost.kext)
- modified by [qwerty12](https://github.com/qwerty12/DisableTurboBoostBattery)
- acidanthera for [MacKernelSDK](https://github.com/acidanthera/MacKernelSDK)