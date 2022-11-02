# Galaxy Book Ion Hackintosh
Samsung Galaxy Book Ion OpenCore EFI
 
[English Version](./README-ENG.md)

## Overview
This is Opencore EFI available for Samsung Galaxy Book Ion 1st Generation.

Created based on Opencore 0.8.5.

## Stable Use Specifications
- Samsung Galaxy Book Ion
- Intel Core i5-10210U
- Intel UHD Graphics 620 / MX250 (External Graphics Not Available)
- Most SSDs except embedded and some SSDs ([cf.](https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html))

## How to install
1. Follow the [Opencore Guide] (https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html) to create a macOS installation USB, then insert the EFI folder into the USB.
2. Fill the MLB, ROM, SystemSerialNumber, SystemUUID blank in PlatformInfo-General in config.plist with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).
3. After installing macOS, refer to the [Built-in Sound Fix Guide](./Audio%20patch) to fix the built-in sound function.

## Change log


## References
- https://github.com/wei756/NT950XCR-G58A-Hackintosh