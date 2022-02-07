# Windows Legacy Active Desktop Wallpaper Autofill Script v1
An HTML page powered by Javascript to make wallpaper autofill work on older legacy versions of Windows that support Active Desktop like Windows 2000, XP, etc.
*Only been tested on Windows 2000 Professional, but it should work on other versions that support Active Desktop.*

It's a simple little project that I made after installing Windows 2000 for the sake of nostalgia. The way Windows 2000 handled wallpapers left a lot to be desired, so this happened.

## How to use
- Place the HTML file in any folder you wish.
- Place a copy of the image file you wish to use as a wallpaper in the same folder. The size and aspect ratio does not matter.
- Copy the filename of the image file and replace **\<YOUR WALLPAPER IMAGE\>** in the HTML file.
- Change the parameters to your desired behavior.
- Set **wallpaper.html** as your wallpaper on your computer's Display Properties and enable Active Desktop if prompted to do so.
- Enjoy!

## Parameters
The default align and scaling systems will mimic the Fill setting in current versions of Windows. If you wish to change the alignment behavior, here's what each parameter do...

### verticalAlign
This setting is used when the image is scaled taller than the screen. Valid values are **top**, **bottom**, or **_center_** (default). Keep it empty (or any other value, for the matter) for default.

### horizontalAlign
This setting is used when the image is scaled wider than the screen. You may use **left**, **right**, or **_center_** (default). Just like verticalAlign, empty or any random value is considered default.

### scale
This setting is the scale factor in decimal percentage. 1 (for 100%) is the minimum value. Any value lower than 1 will be ignored.

## Future plans
I want to add a few more features but they are low in my priority list right now:
- Alignment offsets for more granular control.
- A digital clock.
