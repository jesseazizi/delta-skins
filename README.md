# delta-skins
Controller skins for [Delta](https://github.com/rileytestut/Delta), the retro game emulator for iOS

## Installation
Download the appropriate skins and open them in the Files app to import them into Delta. For forks such as [Ignited](https://github.com/LitRitt/Ignited), you may need to utilize the Share menu to import the skins, since Delta takes priority over the `.deltaskin` file format.

## Screenshots
![](/screenshots/IMG_5218.PNG)
![](/screenshots/IMG_5219.PNG)

## Features
- Skins for NES, SNES, GBC, GBA, and DS
- Consistent visual style crafted with official fonts and glyphs designed by Apple
- Design traced over iOS' [native touchscreen controller API](https://developer.apple.com/documentation/gamecontroller/gcvirtualcontroller) for maximum comfort
- Quick access to fast-forward and menu buttons
- Individual D-pad buttons to prevent unintended diagonal inputs

## Features planned for future updates
- N64 support
- Swap button on the DS skin to change the maximized screen (will be added once Delta supports this feature)

## Notes
These skins are designed for use with standard devices (iPhone 8, SE 2nd/3rd gen., etc.) in landscape mode. Currently, there are no plans to create skins for portrait mode, iPad, or edge-to-edge devices (iPhone X onwards).

The skins with filenames ending in `_debug.deltaskin` display red squares over buttons to help determine how large the touch targets are on the iPhone display. They are not recommended for standard use and are included primarily for archival purposes.

There are two DS skins present in the compressed archive. The skin labeled `DS_skin.deltaskin` features a maximized top screen with a smaller bottom screen in the upper-right corner, and is best for games which primarily use the top screen. For games which rely heavily on the bottom screen, it is recommended that you use `DS_skin_swapped.deltaskin`, which interchanges the positions of the two screens. While I would love to implement a swap-screen button for the DS skin, Delta currently lacks the functionality to allow this. Please consider voting for this feature on [Delta's Trello page](https://trello.com/c/Ktmi75Vi).

## Credits
- **Skin Design, JSON File Programming:** Jesse Azizi
- **Fonts, Glyphs, Original Touchscreen Controller Design:** Apple Inc.
- **Special Thanks:** All Delta developers and contributors, Noah Keck
