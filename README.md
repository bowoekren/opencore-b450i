**System details**. 
- **Motherboard**: Gigabyte b450i Aorus
- **Processor**: Ryzen 5 3600
- **GPU**: GT 1030 

**High Sierra 10.3.6 Build 7G66**.

**Works**:
- QI/CI: [Nvidia Web Driver](https://www.tonymacx86.com/nvidia-drivers/) and change build number to `17G14042` or by updating from app store (bootflag: nvda_drv=1 shikigva=40)
- Audio: [AppleALC.kext](https://github.com/acidanthera/AppleALC) bootflag: alcid=7
- Ethernet: [SmallTreeIntel82576.kext](https://github.com/khronokernel/SmallTree-I211-AT-patch)
- Wifi (Intel 9250): [itlwm.kext](https://github.com/OpenIntelWireless/itlwm) and connect using [Heliport](https://github.com/OpenIntelWireless/HeliPort)
- USB 2.0, 3.0: mapping with [USBMap](https://github.com/corpnewt/USBMap)
- Bluetooth: Works out of the box, no kext installed.
- Power, Sleep, Awake


**Untested**:
- Facetime
- iMessage
- Microphone
