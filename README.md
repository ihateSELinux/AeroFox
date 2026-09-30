# AeroFox

Brings the Aero titlebar buttons from Windows Vista/7 to modern versions of Firefox, complete with hover and active effects, as well as window transparency and shiny padding!

This theme uses images extracted from the official Windows 7 msstyles theme file, so the buttons are as accurate as possible (besides the hover glow).

This is forked from [Sand216's AeroFirefox 3.0 test branch](https://github.com/Sand216/AeroFirefox/tree/3.0-test).

|Operating System|Supported?  |
|:---------------|:----------:|
|Linux with KDE Plasma      |✅          |
|Windows 10           |❌          |
|Windows 11           |❌          |
|MacOS           |❌          |

## Installation

1. Open `about:config`
2. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to true.
3. Open `about:profiles`
4. Click `Open Folder` next to the root directory of your currently selected profile.
5. Copy the `chrome` folder from this repository into your Firefox profile folder.
6. Right click the top of your Firefox window to enable the menubar
7. If on Firefox 157 or newer, enable the **Standard** Window Density in your browser appearance settings _(about:preferences#appearance)_
9. Restart Firefox, and add forced blur to _firefox_ with your preferred blur effect in Plasma desktop effects!

## Bugs
1. Text glow and hover glow get cut off by the padding
2. Find a way to make the padding round! I hear this should be possible in Firefox Nova
3. The inner window shine currently assumes a 73 pixel tall panel; it will look weird if you don't have standard window density, the menubar, **and** 100% GUI scaling in Plasma.

## Planned features
1. Old school UI buttons (eg the home button, downloads button)
2. Maybe redesign the tabs to more closely resemble old school Firefox

## Screenshot
![image](/screenshots/AeroFox.png)
