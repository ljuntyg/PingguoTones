# PingguoTones: Pinyin with Tone Marks Input Method for macOS

PingguoTones lets you write pīnyīn with tone marks on macOS. It is functionally equivalent to the paid software Pinyinput.

## Installation and use (as of macOS 26.2)

1. Clone the whole Git repository, or download it as a ZIP file. Do not manually copy the text from `pingguotones.inputplugin` as it might change the file encoding and cause the following steps to fail.
2. Double-click on the file `pingguotones.inputplugin` in Finder. If the file is prevented from opening by macOS, go to "System Settings → Privacy & Security → Security → Open Anyway".
3. Restart your computer.
4. Go to "System Settings → Keyboard → Text Input → Edit…", then press `+` in lower-left corner to add a new input method. Find "PingguoTones" and add it to your input sources (it should be listed under "Chinese, Simplified").
5. You may delete the downloaded repository. The `pingguotones.inputplugin` file was automatically copied to `~/Library/Input Methods` in step 2. 

To type "pīnyīn", switch to the PingguoTones input method and type `pin1` and space, followed by `yin1` and space.

## Uninstallation

1. Remove `pingguotones.inputplugin` from `~/Library/Input Methods`.
2. Restart your computer.

Installation process courtesy of @andrejbauer (https://gist.github.com/andrejbauer/333f81bb7394502a8539ccf93c7d703f).