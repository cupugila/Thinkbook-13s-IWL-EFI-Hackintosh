# Thinkbook13S-IWL-EFI-OpenCore
Lenovo Thinkbook 13S OpenCore EFI for Hackintosh


Hello everyone.

So, I created this repository to share my OpenCore configuration on Lenovo Thinkbook-13S-IWL. Hopefully this will help someone who has same machine to install Hackintosh.

MacOs Version:
MacOS Big Sur

OpenCore Version: 0.6.8


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
| Trackpad | Gesture enabled. Using VoodooI2CHID. |
| Keyboard | Almost all shortcut key work |
| Internal Speaker |  |
| Internal Microphone |  |
| Headphone jack | Audio line-in not tested yet |
| USB Type-A |  |
| USB Type-C | tested with USB type C hub |
| Camera | |
| Battery Indicator | |
| Brightness | Keyboard shortcut is working |
| Wifi | using airportitlwm |
| Bluetooth | |
| HDMI | |

What's Not Working/Partially working:
| Name | Comment |
| ------ | ------ |
| Sleep | Close lid to sleep not working. You must do Sleep manually then close the lid. If the lid's open the machine will wake up after several seconds. |
| Fingerprint |  |

Bug:
- Sometimes if you enable "Turn display off after:", the display won't turn on and you need to force shutdown. Workaround, set "Turn display off after:" to never, and set screensaver instead.
![image](https://user-images.githubusercontent.com/61957197/122768522-e1010080-d2cd-11eb-8d9e-00279d337d2d.png)


Note:
- You can use [GenSMBIOS] to generate SMBIOS.
- Use [ProperTree] to edit config.plist.



Usefull Link and Credits:
- [OpenCore Install Guide]: this is starting point if you want to install Hackintosh using OpenCore.
- [Acidanthera]: for most of the kexts
- [Olarila]: If you want to download Mac Os Vanilla image without having Mac.
- [OpenIntelWireless]: for intel wifi & bluetooth kexts
- [VoodooI2C]: Trackpad kexts
- [ECEnabler]: for working battery status


[GenSMBIOS]: <https://github.com/corpnewt/GenSMBIOS>
[ProperTree]: <https://github.com/corpnewt/ProperTree> 
[OpenCore Install Guide]: <https://dortania.github.io/OpenCore-Install-Guide/>
[Olarila]: <https://www.olarila.com>
[OpenIntelWireless]: <https://github.com/OpenIntelWireless>
[Acidanthera]: <https://github.com/acidanthera>
[VoodooI2C]: <https://github.com/VoodooI2C/VoodooI2C>
[ECEnabler]: <https://github.com/1Revenger1/ECEnabler>
