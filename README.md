# Numix Theme

A Numix theme for Sublime Text 2/3

### Numix + Monokai
![Screenshot](https://dl.dropboxusercontent.com/u/1763308/Numix/numix_monokai.png)
### Numix + Espresso
![Screenshot](https://dl.dropboxusercontent.com/u/1763308/Numix/numix_espresso.png)
### Numix Light + Monokai
![Screenshot](https://dl.dropboxusercontent.com/u/1763308/Numix/numix_light_monokai.png)
### Numix Light + Espresso
![Screenshot](https://dl.dropboxusercontent.com/u/1763308/Numix/numix_light_espresso.png)
### Numix Dark + Monokai
![Screenshot](https://dl.dropboxusercontent.com/u/1763308/Numix/numix_dark_monokai.png)


## Installation

### Package Control
If you are using ```Package Control``` you just have to search it and install it. It's listed as ```Numix Theme```.

### Git Install
You can install the theme and keep it updated by cloning the repo into your `Packages` directory.

To get to your packages directory, go into SublimeText and click on `Preferences -> Browse Packages...`.

Now open up a terminal and go into packages folder you opened and run:

`git clone https://github.com/Zetch/sublime-text-numix "Numix Theme"`

### Manual Install
* Download the [Package](https://github.com/Zetch/sublime-text-numix/archive/master.zip)
* Unzip the files and rename the folder to `Numix Theme`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory.

### Activate
Click on `Preferences -> Settings - User` and add the next line:
```
"theme": "Numix.sublime-theme"
```
or the next one for Dark version
```
"theme": "Numix Dark.sublime-theme"
```

Restart Sublime Text after this.

## Customization

### Folder icons
To view sidebar icons as folders add the next line to your preferences file on `Preferences -> Settings - User`:
```
"numix_folder_icons": true
```

### Tabs size
You can change the size of the tabs for better visibility using the following settings in your preferences file:
* Small: `"tabs_small": true`
* Medium: `"tabs_medium": true`
* Large: `"tabs_large": true`

If no one is used it defaults to medium.

### Overlay scrollbars
The theme is compatible with overlay scrollbars. To activate them add the next line to your preferences file:
```
"overlay_scroll_bars": "enabled"
```

### Color scheme
Color schemes used on the screenshots are part of [Soda Theme](https://github.com/buymeasoda/soda-theme/) project. You can download them on this [link](http://buymeasoda.github.com/soda-theme/extras/colour-schemes.zip).

## Work in progress
This is a early release o work that needs to be improving.

## Thanks
This theme is a fork of [Brogrammer theme](https://github.com/kenwheeler/brogrammer-theme).
