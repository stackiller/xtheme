# X Server theme setter
This script will help you maintain a library of your favorite themes for Server X, and define them in a much easier and more practical way.

**Preview:**
Link of video.

## Script structure

  
| Files  | Description |
|--|--|
| *xtheme* | theme setter |
| *.x_theme* | X themes directory |
| *.x_theme/default.theme*  | file with the default settings to be shared between themes: font size, font type, terminal geometry, etc |
| *.x_theme/current.theme* | Currently defined theme is the same as .Xresources. |

## Installation

    $ clone https://github.com/stackiller/xtheme
    $ cd xtheme
    $ chmod +x install
    $ ./install

> Note: the executable will be copied to the .tools folder in the $HOME directory
  

## Defining themes

The **`xtheme`** command is used to list existing themes:

    $ xtheme

Now just define the desired theme using the index returned by the script:

Example:

    $ xtheme 19
Ready :D

## Download more themes
By default, the repository already comes with some predefined themes that were downloaded from the website https://terminal.sexy, if you want to download more themes, visit the website and download them, after that, move them to the **`.xthemes`** directory.

Enjoy, and good studies ;)
