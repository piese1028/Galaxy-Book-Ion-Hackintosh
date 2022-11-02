# Galaxy Book Ion Hackintosh
 Samsung Galaxy Book Ion OpenCore EFI
 
[English Version](./README-ENG.md)

## 개요
삼성 갤럭시북 이온 1세대에서 사용가능한 Opencore EFI입니다.

Opencore 0.8.5를 기반으로 제작되었습니다.

## 안정적인 사용이 가능한 사양
- Samsung Galaxy Book Ion
- Intel Core i5-10210U
- Intel UHD Graphics 620 / MX250(외장그래픽 사용 불가)
- 기본 제공 및 일부 SSD를 제외한 대부분의 SSD ([참고](https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html))

## 설치 방법
1. [Opencore Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html)를 따라 macOS 설치 USB를 만든 다음 EFI 폴더를 USB에 넣습니다.
2. config.plist내 PlatformInfo-Generic에 공백으로 되어있는 MLB, ROM, SystemSerialNumber, SystemUUID을 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)를 통해 채워주세요.
3. macOS 설치 후 [내장 사운드 픽스 가이드](./Audio%20patch)를 참고하여 내장 사운드 기능을 픽스하세요.

## 업데이트 내역


## 참고 자료
- https://github.com/wei756/NT950XCR-G58A-Hackintosh