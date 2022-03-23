<h1 align="center"> macOS on Huawei Matebook 12 2020 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Matebook%2013%202020.png" alt="Huawei Matebook 12 2020">
</p>

<h4 align="center"> OpenCore config for Hackintosh Huawei Matebook 12 2020 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.3-blue" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.7.9-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-lightgrey?logo=YouTube&logoColor=red" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>
  
## Contents
  - [Screenshots](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#screenshots-)
  - [Photos](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#photos)
  - [Original Hardware](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#whats-not-working-)
  - [What's you have to do](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#whats-you-have-to-do--)
  - [Kexts Used](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#kext-used)
  - [SSDTs Used](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#ssdt-used)
  - [Credits](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Bağış.md)
  
## Screenshots 📷
  
<p align="center">
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/macOS/macOS%20Monterey.png">
</p>

<details>
  <summary> <h3>Photos</h3> </summary>
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Matebook%20Photo.jpg" alt="Huawei Matebook 12 2020">
</details>

## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Huawei Matebook 12 2020 | ✅
CPU              | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz Comet Lake | ✅
RAM           | 8 GB 2400 MHz DDR4 | ✅
Internal Graphics Card | Intel(R) UHD Graphics 630 (1 GB) | ✅
External Graphics Card | NVIDIA GeForce MX250 (2GB) | ❌
Wi-Fi             | Intel Wireless-AC 9462 | ✅
Audio       | ?? | ✅
Camera | Azurewave ?? | ❌
Fingerprint | Unknown | ❌

## macOS Update History
  
- ✅ macOS Monterey 12.3
- ✅ macOS Big Sur 11.6.5

## What's working  💻
  
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel UHD Graphics 630              |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio             |  ✅  
Intel Wireless-AC 9462 Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅  
2 Type-C Port       |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  

## What's not working 💻
  
Type | Info | Status
:---------|:---------|:----------
Camera | Not supported in macOS | ❌ 
Fingerprint | Not supported in macOS | ❌
NVIDIA GeForce MX250 | Not supported in macOS | ❌
S3 Sleep / Wake   |  I don't have Type-C USB. If you map the USB Ports it will work. | ⚠️
S4 Hibernation / Wake   |  I don't have Type-C USB. If you map the USB Ports it will work. | ⚠️

## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
Rename config    | If you install Monterey+, you can delete BrcmBluetoothInjector.kext and AirportItlwmBigSur.kext in OC/Kexts. If you install Big Sur-, you can delete BlueToolFixup.kext and AirportItlwmMonterey in OC/Kexts. | ⚠️ 

## Kext Used 
 
Kext | Info 
:---------|:---------
[Lilu.kext](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[VerbStub.kext](https://github.com/hackintosh-stuff/ComboJack) | Fixes jack headphone audio and microphone.
[USBInjectAll](https://github.com/Sniki/OS-X-USB-Inject-All) | Kext to inject USB ports.
[VoodooI2C.kext](https://github.com/VoodooI2C/VoodooI2C) | VoodooI2C is consisting of macOS kernel extensions that add support for I2C bus devices.
[VoodooI2CHID.kext](https://github.com/VoodooI2C/VoodooI2C) | Adds support for I2C-HID devices.
[VoodooPS2Controller.kext](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel UHD 630.
[SMCBatteryManager.kext](https://github.com/acidanthera/VirtualSMC) | Battery Status Monitoring.
[SMCProcessor.kext](https://github.com/acidanthera/VirtualSMC) | Processor Temp Monitoring.
[SMCLightSensor.kext](https://github.com/acidanthera/VirtualSMC) | Light sensor for automatic brightness level.
[NullEthernet.kext](https://github.com/RehabMan/OS-X-Null-Ethernet) | This is “fake ethernet” driver to make the system still allow Mac App Store access.
[AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS.
[IntelBluetoothFirmware.kext](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | IntelBluetoothFirmware is a Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.
[IntelBluetoothInjector.kext](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | IntelBluetoothFirmware is a Kernel Extension that inject IntelBluetoothFirmware for bluetooth.
[BlueToolFixup.kext](https://github.com/acidanthera/BrcmPatchRAM) | Required for macOS 12 or newer, as in macOS 12 Apple has changed parts of the Bluetooth stack from kernel-space to user-space as detailed in here and here. Requires Lilu 1.5.4+
[NVMeFix.kext](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[CPUFriend.kext](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider.kext](https://github.com/corpnewt/CPUFriendFriend) | A CPUFriend plug-in for CPU power management.
[FeatureUnlock.kext](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[HibernationFixup.kext](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[NoTouchID.kext](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support.

## SSDT Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-AC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | [Cosmetic]
[SSDT-ALS0.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Ambient_Light_Sensor_(SSDT-ALS0)) | Enable Ambient Light Sensor (ALSD) | [Functional]
[SSDT-AWAC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-AWAC)) | Hotpatches for enabling RTC and disabling AWAC system clock at the same time. | [Functional]
[SSDT-BATT.aml](https://dortania.github.io/OpenCore-Post-Install/laptop-specific/battery.html#battery-status) | Fixes the battery status indicator. | [Functional]
[SSDT-DDGPU.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/02_Disabling_Devices/Disabling_unsupported_GPUs) | Disable incompatible external GPU. | [Functional]
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDT-FWHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS. | [Cosmetic]
[SSDT-GPI0-GPHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/OCI2C-GPIO_Patch) | The presence of a GPIO device is usually required for a I2C TrackPads to function properly. | [Functional]
[SSDT-GPRW.aml](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html#gprw-uprw-lanc-instant-wake-patch) | Fixes instant wake if either USB or power states change while sleeping. | [Functional]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-MEM2.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/SSDT-MEM2) | It makes the iGPU use MEM2 instead of TPMX. | [Cosmetic]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PMC.aml](https://github.com/corpnewt/SSDTTime) | It specifically brings back NVRAM support and requires very little configuration for the end user. | [Functional]
[SSDT-PNLF-CFL.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-PS2K.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | Enable Brightness Key Shortcuts. | [Functional]
[SSDT-PTSWAK.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | [Functional]
[SSDT-RMNE.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Ethernet_Controller_(LAN)) | Spoof fake ethernet controller with NullEthernet. | [Functional]
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | [Functional]
[SSDT-SLPB.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Sleep Button. | [Functional]
[SSDT-XSPI.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Intel_PCH_SPI_Controller_(SSDT-XSPI)) | Adds Platform Controller Hub (PCH) to IORegistry. | [Cosmetic]

## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
