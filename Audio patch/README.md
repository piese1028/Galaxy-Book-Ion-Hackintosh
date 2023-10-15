# 내장 스피커/이어폰 잭 픽스
<img align="left" src="./1.png" alt="macOS Finder 스크린샷" width="275">

**파일 모으기**

<a name="download">1</a>. [hda 폴더](https://download-directory.github.io/?url=https://github.com/rainbowicenow/Galaxy-Book-Ion-Hackintosh/tree/master/Audio%20patch/hda)와 [HDA fix.app](https://download-directory.github.io/?url=https://github.com/rainbowicenow/Galaxy-Book-Ion-Hackintosh/tree/master/Audio%20patch/HDA%20fix.app)을 내려받아 `/Applications`에 넣어줍니다.

<a name="move">2</a>. `시스템 환경설정 → 일반 → 로그인 항목`에서 +를 눌러 `HDA fix.app`을 추가합니다.

<a name="restart">3</a>. macOS를 재시동하거나 `HDA fix.app`을 실행합니다.

<img align="left" src="./2.png" alt="오디오 MIDI 설정 스크린샷" width="275">

**설정 변경하기**

<a name="audiomidi">4</a>. `⊞ Win` + `Space` 키를 눌러 Spotlight 검색을 열고 `오디오 MIDI 설정`을 실행합니다.

<a name="look">5</a>. `내장 출력` 항목을 찾아주세요. `MacBook Pro 스피커`로 표시될 수도 있습니다.

<a name="settings">6</a>. 스피커의 포맷을 `48,000 Hz`로 변경하면 금속성 잡음이 사라집니다.

## 참고
* https://bugs.launchpad.net/ubuntu/+source/linux/+bug/1851518
* https://github.com/tkrotoff/Gigabyte-GA-Z77-DS3H-rev1.1-Hackintosh/issues/3
