# Galaxy Book Ion Hackintosh
Samsung Galaxy Book Ion OpenCore EFI

See English version [here](./README_EN.md)

## 개요
삼성 갤럭시북 이온 1세대에서 사용가능한 Opencore EFI 입니다.

Opencore 0.9.4를 기반으로 제작되었습니다.

## 작동 버전
| 버전 | 작동 여부 |
|--------------------|-----|
| macOS Big Sur | ✅ |
| macOS Monterey | ✅ |
| macOS Ventura | ✅ |
| macOS Sonoma | ✅ |

macOS Sonoma 이전 버전 사용자는 [AirportItlwn](https://github.com/OpenIntelWireless/itlwm/releases/latest), [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases/latest), [IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases/latest)을 해당 버전으로 교체 후 사용하시기 바랍니다.

## 권장 사양
| 부품 | 정보 |
|---------------|----|
| Laptop        | Samsung Galaxy Book Ion |
| CPU           | Intel Core i5-10210U |
| GPU           | Intel UHD Graphics 620 |
| SSD           | 기본 제공 및 일부 SSD를 제외한 대부분의 SSD ([참고](https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html)) |

## 기능 작동 현황
| 기능 | 설명 | 작동 여부 |
|--------------------|-------------|---------------|
| 🛜 WiFi             | Apple 연속성 기능 작동하지 않음 | ✅ |
| 🔵 Bluetooth        | Apple 연속성 기능 작동하지 않음 | ✅ |
| ⌨️ Keyboard         | | ✅ |
| 🖱️ Trackpad         | | ✅ |
| 💻 Lid Close Sensor | | ✅ |
| 🔋 Battery          | | ✅ |
| 📸 Webcam           | | ✅ |
| 🔊 Speaker          | 음질 매우 낮음, 부팅중 작동하지 않음 | ✅ |
| 📺 HDMI / DP Out    | C to HDMI로 테스트시 불가 | ⚠️ |
| 🎙️ Mic              | | ❌ |
| ⚡ Thunderbolt       | | ❌ |
| 🧬 Fingerprint Sensor | | ❌ |
| 💤 Sleep            | | ❌ |
| 🎆 dGPU             | Nvidia, 가능한 방법 없음 | ❌ |

## 설치 방법
1. [Opencore Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html)를 따라 macOS 설치 USB를 제작하세요.
2. EFI를 다운로드 한 후 USB에 넣어주세요.
3. config.plist내 Changehere이라고 되어있는 부분(MLB, ROM, SystemSerialNumber, SystemUUID)을 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)를 통해 채워주세요.
4. macOS 설치 후 [Built-in Sound Fix Guide](./Audio%20patch)를 참고하여 내장 사운드 기능을 픽스하세요.

## 업데이트 내역
2023-09-30 : macOS Sonoma 지원

## 참고 자료
- https://github.com/wei756/NT950XCR-G58A-Hackintosh
