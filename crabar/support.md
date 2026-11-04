---
title: crabar Support
---

# crabar Support

crabar is a Mac app that shows CPU and memory (RAM) usage in the menu bar.

## How to use

When you launch crabar, CPU and RAM icons appear in the menu bar at the top right of the screen (there is no Dock icon). Click the icons to open the menu.

- **CPU and memory details**: CPU usage and core count, memory in use and total memory
- **Refresh Interval**: Choose 1, 1.5, 2, 3, or 5 seconds. The default is 1.5 seconds.
- **Display Style**: Gauge (bar) or graph (recent usage)
- **Animation**: Turns on or off the effect where the icon's pins flow faster as usage rises.
- **Launch at Login**: When on, crabar starts automatically when you log in. Off by default.
- **Open Activity Monitor**: See which apps are using the most CPU or memory.
- **Quit**: Quits crabar.

## FAQ

**I can't see the icon in the menu bar.**
On a crowded menu bar, or on a Mac with a notch, some icons may be hidden for lack of space. Try removing other menu bar icons, or switch to an app with fewer menus.

**How is memory usage calculated?**
The same way as "Memory Used" in Activity Monitor (app memory + wired memory + compressed memory). File cache is excluded, so memory that macOS can free immediately is not counted.

**How do I quit crabar?**
Click the menu bar icon and choose Quit (or press ⌘Q while the menu is open). To keep it from starting the next time you log in, turn off Launch at Login.

**Does it drain the battery?**
crabar only reads system statistics once every few seconds, so its overhead is small. To reduce it further, choose a longer refresh interval or turn off the animation.

## Contact

Please report bugs or suggest features via [GitHub Issues](https://github.com/hoofam/docs/issues/new?title=%5Bcrabar%5D%20). Including your macOS version and Mac model helps.

[Privacy Policy](privacy)
