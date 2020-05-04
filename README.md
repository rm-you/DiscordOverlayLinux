## Discord Overlay for Linux

A QT browser window to overlay Discord activity over the screen.
![Steam Big Picture](https://user-images.githubusercontent.com/535772/81019771-e0ea3b00-8e56-11ea-9afe-7b684478e1de.png)


## Dependencies

`qt5-webengine pyqt5 python-pyqtwebengine`

Ubuntu/Debian:

`sudo apt install python3-pyqt5 python3-pyqt5.qtwebengine`

## Usage

On first launch a setup-window will appear. First choose either 'OBS' or 'XSplit'. There is no functional difference.

From there choose which widget you want to use as your overlay from the top, and make any changes to the style. Press the 'Use this overlay' button

Adjust the sliders to position the window, these correspond to invisible padding around the overlay, in the current order:
- Distance from left of screen
- Distance from right of screen
- Distance from top of screen
- Distance from bottom of screen


## Known Issues
- If loaded before Discord is logged in no display will show. Quite possible that unexpected Discord crashes will cause the same issue

### Tested configurations

- Wayfire/Wayland - Works Perfectly
- Openbox/X11     - Works Perfectly
- Gnome/X11       - Works
