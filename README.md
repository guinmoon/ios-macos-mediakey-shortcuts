
# Control MacOS Media Keys with Shortcuts

## Install
```
pip3 install pyobjc-framework-Quartz
git clone https://github.com/guinmoon/ios_macos_mediakey_shortcuts ~/ios_macos_mediakey_shortcuts
```

### Add Shortcuts
Play/Pause shortcut:<br>
![https://www.icloud.com/shortcuts/af41822e22a544edab5f2d9dc9d65294](dist/play.png)

## Usage:
```
python3 quartz_mediakey.py <parameter>

PARAMETERS:
-h help

-p play/pause
-n next
-r prev
-f fast
-w rewind

-u sound up
-d sound down
```