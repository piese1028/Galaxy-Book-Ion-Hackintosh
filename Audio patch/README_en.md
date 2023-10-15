# Integrated Speaker/Audio jack fix
<img align="left" src="./1_en.png" alt="macOS Finder screenshot" width="275">

**Gathering Files**

<a name="download">1</a>. Download [hda folder](https://download-directory.github.io/?url=https://github.com/rainbowicenow/Galaxy-Book-Ion-Hackintosh/tree/master/Audio%20patch/hda) and [HDA fix.app](https://download-directory.github.io/?url=https://github.com/rainbowicenow/Galaxy-Book-Ion-Hackintosh/tree/master/Audio%20patch/HDA%20fix.app) then move to /Applications folder.

<a name="move">2</a>. Add HDA fix.app to Login Items at `System Settings → General → Login Items`.

<a name="restart">3</a>. Restart or start `HDA fix.app`.

<img align="left" src="./2_en.png" alt="Audio MIDI Setup screenshot" width="275">

**Change Settings**

<a name="audiomidi">4</a>. Press `⊞ Win` + `Space` to launch spotlight search, then search for `Audio MIDI Setup`.

<a name="look">5</a>. Look for integrated speaker. It may be displayed as `MacBook Pro Speakers`.

<a name="settings">6</a>. Change speaker's format to `48,000 Hz` to remove static noise from speaker.

## See also
* https://bugs.launchpad.net/ubuntu/+source/linux/+bug/1851518
* https://github.com/tkrotoff/Gigabyte-GA-Z77-DS3H-rev1.1-Hackintosh/issues/3
