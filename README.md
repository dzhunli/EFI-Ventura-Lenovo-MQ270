# EFI-Ventura-Lenovo-MQ270
<br/>

:warning: **IMPORTANT**

This is not a guide, please refer to [Dortania](https://dortania.github.io/getting-started) before doing anything. I am not responsible for any damage. This OpenCore configuration is optimized for my specific hardware, so please use it only as a reference or if you happen to have the same or similar hardware.

<br/>
### BIOS setup:
- Boot / Boot Mode - UEFI
- Security / Intel Platform Trust Technology - Disabled
- Security / Intel SGX - Disabled
- Security / Secure Boot - Disabled

### EXAMPLE:
<img src="assets/about.jpg" alt="about" width="250" height="400"/>

### POST INSTALL:
- use MountEFI-update/MountEFI.command , for mount EFI folder.
- copy EFI from flash to mounted EFI.
- remove in mounted EFI/OC/ config.plist
- rename config-realese.plist to config.plist

### Authors

- [@dzhunli](https://github.com/dzhunli)


### Documentation:

[**Apple**](http://apple.com/)

[**Dortania**](https://dortania.github.io/getting-started/)
