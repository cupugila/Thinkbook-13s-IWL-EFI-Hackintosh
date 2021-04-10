# Thinkbook13S-IWL-EFI-OpenCore
Lenovo Thinkbook 13S OpenCore EFI for Hackintosh


Hello everyone.

So, I created this repository to share my OpenCore configuration on Lenovo Thinkbook-13S-IWL. Hopefully this will help someone who has same machine to install Hackintosh.

MacOs Version:
MacOS Big Sur

OpenCore Version: 0.6.7


Laptop Specifications:
| Hardware | Info |
| ------ | ------ |
| CPU | Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz |
| MEMORY | 16 GB DDR4 |
| GRAPHICS | Intel UHD Graphics 620 (Mobile) |
| DISK | SSD HFM512GDHTNG-8310A |
| SOUND | Realtek ALC257 |
| Network | Intel AC9560 |

What's Working:
| Name | Comment |
| ------ | ------ |
| Graphics Acceleration |  |
| Trackpad | Gesture enabled. Using VoodooI2CHID. Please enable Intel SGX on boot option. |
| Keyboard | You must press fn to use F1-F12 key. Shortcut key for volume up and volume down is working. |
| Internal Speaker |  |
| Internal Microphone |  |
| Headphone jack | line in not tested yet |
| USB Type-A | Type-C port not tested |
| Camera | |
| Battery Indicator | |
| Brightness | Change brightness from control center. Keyboard shortcut F11 & F12 is not working. |
| Wifi | |
| Bluetooth | |
| HDMI | |

What's Not Working/Partially working:
| Name | Comment |
| ------ | ------ |
| Sleep | Close lid to sleep not working. You must do Sleep manually then close the lid. If the lid's open the machine will wake up after several seconds. |
| Fingerprint |  |


Note:
- You can use [GenSMBIOS] to generate SMBIOS. 



Usefull Link and Credits:
- [OpenCore Install Guide]: this is starting point if you want to install Hackintosh using OpenCore.
- [Olarila]: If you want to download Mac Os Vanilla image without having Mac.


[GenSMBIOS]: <https://github.com/corpnewt/GenSMBIOS>
[OpenCore Install Guide]: <https://dortania.github.io/OpenCore-Install-Guide/>
[Olarila]: <https://www.olarila.com>
