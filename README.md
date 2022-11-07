<h1 align="center"> macOS on Huawei Matebook 13 2020 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Matebook%2013%202020.png" alt="Huawei Matebook 13 2020">
</p>

<h4 align="center"> OpenCore config for Hackintosh Huawei Matebook 13 2020 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey%2012.6-purple" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.8.5-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
<a href="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Huawei-Matebook-13-Hackintosh" width="145"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>
<a href="https://www.buymeacoffee.com/yusufklncc">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" width="150"/> </a>
  
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
  - [Disable CFG Lock](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#how-to-disable-cfg-lock)
  - [Credits](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Bağış.md)
  
## Screenshots 📷

### CPU Usage and Temperature  
- Normal

  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Normal%20CPU%20Frequency%20and%20Temperature.png" width="300">
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Normal%20CPU%20Usage.png" width="400">
  
- Maximum

  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Max%20CPU%20Frequency%20and%20Temperature.png" width="300">
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Max%20CPU%20Usage.png" width="400">  
  
<p align="center">
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/macOS/macOS%20Monterey.png">
</p>

<details>
  <summary> <h3>Photos</h3> </summary>
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/Matebook%20Photo.jpg" alt="Huawei Matebook 13 2020">
</details>

## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Huawei Matebook 13 2020 | ✅
CPU              | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz Comet Lake | ✅
RAM           | 8 GB 2400 MHz DDR4 | ✅
Internal Graphics Card | Intel(R) UHD Graphics 630 (1 GB) | ✅
External Graphics Card | NVIDIA GeForce MX250 (2GB) | ❌
Wi-Fi             | Intel Wireless-AC 9462 | ✅
Audio       | Realtek ALC256 | ✅
Camera | Azurewave | ❌
Fingerprint | Unknown | ❌

## macOS Update History
  
- ✅ macOS Monterey 12.6  
- ✅ macOS Monterey 12.3
- ✅ macOS Big Sur 11.6.5

## What's working  💻
  
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel UHD Graphics 630              |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio Realtek ALC256            |  ✅  
Intel Wireless-AC 9462 Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅  
2 Type-C Port       |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  
S3 Sleep / Wake   |  ✅
S4 Hibernation / Wake   |  ✅

## What's not working 💻
  
Type | Info | Status
:---------|:---------|:----------
Camera | Not supported in macOS | ❌ 
Fingerprint | Not supported in macOS | ❌
NVIDIA GeForce MX250 | Not supported in macOS | ❌

## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
Disable CFG Lock | Here my guide [READ](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh#how-to-disable-cfg-lock) | ⚠️

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
[SSDT-DDGPU.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/02_Disabling_Devices/Disabling_unsupported_GPUs) | Disable incompatible external GPU. | [Functional]
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDT-FWHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS. | [Cosmetic]
[SSDT-GPI0-GPHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/OCI2C-GPIO_Patch) | The presence of a GPIO device is usually required for a I2C TrackPads to function properly. | [Functional]
[SSDT-GPRW.aml](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html#gprw-uprw-lanc-instant-wake-patch) | Fixes instant wake if either USB or power states change while sleeping. | [Functional]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-MEM2.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/SSDT-MEM2) | It makes the iGPU use MEM2 instead of TPMX. | [Functional]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PMC.aml](https://github.com/corpnewt/SSDTTime) | It specifically brings back NVRAM support and requires very little configuration for the end user. | [Functional]
[SSDT-PNLF-CFL.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-PS2K.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | Enable Brightness Key Shortcuts. | [Functional]
[SSDT-PTSWAK.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | [Functional]
[SSDT-RMNE.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Ethernet_Controller_(LAN)) | Spoof fake ethernet controller with NullEthernet. | [Functional]
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | [Functional]
[SSDT-SLPB.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Sleep Button. | [Functional]
[SSDT-UIAC.aml](https://5t33z0.gitbook.io/oc-litte-translated/oc-little/fixes/fixing-usb-issues/usb-port-mapping-via-acpi-macos-11.3+) | Mapped USB Ports. | [Functional]
[SSDT-XSPI.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Intel_PCH_SPI_Controller_(SSDT-XSPI)) | Adds Platform Controller Hub (PCH) to IORegistry. | [Cosmetic]

## ComboJack Installation

- [Download](https://github.com/Heporis/ComboJack) and open terminal, type sudo and press space, drag install.sh file and press enter.

<details>
  <summary> <h2>How to Disable CFG Lock</h2> </summary>
  
- If you got unnormal cpu boost issue or overheating issue, i recommand to do this.
  - Upgrade your bios to 1.20, could be downloaded in PC Manager on Windows.
  - Format a usb stick to FAT32.
  - Create a new folder named "EFI" in root.
  - Create a new folder named "BOOT" in /EFI/.
  - Download [cfgunlock.zip](https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/cfgunlock.zip)
  - Copy BOOTx64.efi from cfgunlock.zip to EFI/BOOT in your USB.
  - Restart and boot with this usb.
  - After you boot. Press alt and "key next to backspace" in same time.
  - Use ↑ and ↓ in your keyboard to find "CpuSetup".
  - Press enter in keyboard to enter "CpuSetup".
  - You will see this.
  
  <img src="https://github.com/yusufklncc/Huawei-Matebook-13-Hackintosh/blob/main/Images/CpuSetup.jpg" width="500">
  
  - If 0030-0E value is 01 in your computer continue. If it is 00. You don't need this.
  - Use ← → ↑ ↓ key to pick it and change to 00.
  - Press ctrl and w in same time to save setting.
  - A window says "
  - Press alt + q to quit.
- <b>DO NOT use what i uploaded for boot opencore.</b>
  - Now you can disable these quirks in confg/kernel:
    - AppleCpuPmCfgLock
    - AppleXcpmCfgLock

## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [Heporis](https://github.com/Heporis) for ComboJack.
 - [Alex James](https://github.com/al3xtjames) for NoTouchID kext.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
