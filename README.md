# EFI-Ventura-Lenovo-MQ270


<br/>

:warning: **IMPORTANT**

This is not a guide, please refer to [Dortania](https://dortania.github.io/getting-started) before doing anything. I am not responsible for any damage. This OpenCore configuration is optimized for my specific hardware, so please use it only as a reference or if you happen to have the same or similar hardware.

<br/>

### Tested on HARDWARE:
| HARDWARE  | Description        |
|----------|--------------------|
| CPU | i5-8500T |
| GPU |  Intel® UHD Graphics 630 |
| RAM | 8GB DDR4 |
| SSD | 120GB  |
| DEVICE | Lenovo ThinkCentre M720Q USFF |

### BIOS setup:
- Boot / Boot Mode - UEFI
- Security / Intel Platform Trust Technology - Disabled
- Security / Intel SGX - Disabled
- Security / Secure Boot - Disabled

### Example:
<img src="assets/about.jpg" alt="about" width="250" height="400"/>

### POST Install guide:
- use MountEFI-update/MountEFI.command , for mount EFI folder.
- copy EFI from flash to mounted EFI.
- remove in mounted EFI/OC/ config.plist
- rename config-realese.plist to config.plist

### Additional steps:
- you can disable window animation 
```bash
defaults write -g NSAutomaticWindowAnimationsEnabled -bool false
```
- you can disable dock animations
```bash
defaults write com.apple.dock expose-animation-duration -float 0.1
killall Dock
``` 


### Documentation:

[**Apple**](http://apple.com/)

[**Dortania**](https://dortania.github.io/getting-started/)
