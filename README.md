# YosemiteConsolasFont
Replace Helvetica Neue on your 10.10 Yosemite Mac with Consolas

I like Consolas Font so much.In my PC(ThinkPad-R400),i also replaced Windows System Font to Consolas.
So this is for you guys who like Consolas Font just like me. ; )

The idea generated with Thai Pangsakulyanont's [Yosemite System Font Patcher](https://github.com/dtinth/YosemiteSystemFontPatcher).
Thank for your effort,Thai Pangsakulyanont! And these custom fonts not crash Google Chrome, so happy! (I also customed Menlo Font,but those fonts crash Google Chrome. :( ))

### Warning: This package has not been extensively tested. It works in my system without problems, but use at your own risk.If you find any bug, please open an issue.If you have questions or suggestions, you can open an issue.

![screenshot](/ScreenShot.png)

## How to Install:
1. [Download the zipped font files](https://github.com/w4mxl/YosemiteConsolasFont/blob/master/Consolas.zip).
2. Copy the 5 font files to `~/Library/Fonts` on your Mac. *(protip: press `cmd+shift+g` while in Finder to type the path directly.)*
3. Log out and log back in to apply the changes.

## How to Uninstall:
1. Navigate to `~/Library/Fonts` on your Mac and delete the 5 files starting with `System Consolas System Font`.
2. Log out and log back in to apply the changes.

## How does it works?
These Consolas fonts have a special name table with names identical to those of the system fonts. Because the font folder /Library/Fonts takes precedence over the fonts which are in /System/Library/Fonts, these specially crafted fonts are used for the user interface instead of the real system fonts. The original system fonts are not deleted or modified in any way.
