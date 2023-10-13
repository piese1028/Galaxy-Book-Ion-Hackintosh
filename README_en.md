# Galaxy Book Ion Hackintosh
Samsung Galaxy Book Ion OpenCore EFI

## General
Opencore EFI file made for Samsung Galaxy Book Ion (First gen.)

File best compatible with Opencore 0.9.4

## Version Compatibility List
| Version | Compatible |
|--------------------|-----|
| macOS Big Sur | ✅ |
| macOS Monterey | ✅ |
| macOS Ventura | ✅ |
| macOS Sonoma | ✅ |

If you're using macOS prior to macOS Sonoma, please swap these files to corresponding version:
* [AirportItlwn](https://github.com/OpenIntelWireless/itlwm/releases/latest)
* [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases/latest)
* [IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases/latest)

## Tested Hardware
| Model | Info |
|---------------|----|
| Laptop        | Samsung Galaxy Book Ion |
| CPU           | Intel Core i5-10210U |
| GPU           | Intel UHD Graphics 620 |
| SSD           | Most SSDs except provided and SSDs referred [here](https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html) |

## Status
| Function | Info | Compatibility |
|--------------------|-------------|---------------|
| 🛜 WiFi             | Continuity does not function | ✅ |
| 🔵 Bluetooth        | Continuity does not function | ✅ |
| ⌨️ Keyboard         | | ✅ |
| 🖱️ Trackpad         | | ✅ |
| 💻 Lid Close Sensor | | ✅ |
| 🔋 Battery          | | ✅ |
| 📸 Webcam           | | ✅ |
| 🔊 Speaker          | Sound does not function on boot | ✅ |
| 📺 HDMI / DP Out    | Output from Type-C port does not work | ⚠️ |
| 🎙️ Mic              | | ❌ |
| ⚡ Thunderbolt       | | ❌ |
| 🧬 Fingerprint Sensor | | ❌ |
| 💤 Sleep            | | ❌ |
| 🎆 dGPU             | Nvidia, see [here](https://dortania.github.io/GPU-Buyers-Guide/#a-quick-refresher-with-nvidia-and-web-drivers) for why | ❌ |

## How-to install
1. Create installer usb following the [Opencore Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html).
2. Download the EFI and move files to the USB
3. Edit config.plist with generated value from [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS). Editing point marked with `Changehere`
4. Fix sound issue following the [Built-in Sound Fix Guide](./Audio%20patch/README_en.md).

## Release note
2023-09-30 : Added support for macOS Sonoma

## See also
- https://github.com/wei756/NT950XCR-G58A-Hackintosh
