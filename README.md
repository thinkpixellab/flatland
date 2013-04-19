# Flatland

## About

Flatland is a simple theme and accompanying color scheme for Sublime Text 2. It is mostly derived from  [Soda](https://github.com/buymeasoda/soda-theme), the right place to start for any custom theme development for Sublime. Thanks Soda!

## Design

![Screen Shot!](https://raw.github.com/thinkpixellab/flatland/master/resources/screenshot.png)


## Installation
Flatland is a Sublime package. There are two ways to install it.

### Package Control
You can install it using the excellent [Package Control][] package manager for Sublime Text 2 following these easy steps:

1. Add the https://github.com/thinkpixellab/flatland/ repository to your list of installed packages using `Package Control: Add Repository` from the Command Palette
2. Install the `flatland` package using the `Package Control: Install Package` command.

[Package Control]: http://wbond.net/sublime_packages/package_control

### Manual Installation
You can also install it manually by following these instructions:

1. [Download theme files](https://github.com/thinkpixellab/flatland/archive/master.zip)
2. Unzip the files and copy the folder newly created folder into your Sublime Text 2 Packages directory with the name `flatland`. You can find that directory by selecting "Preferences > Browse Packages ...".
3. Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "theme": "Flatland.sublime-theme",
  "color_scheme": "Packages/flatland/Color Scheme/Flatland.tmTheme"
}
```

Or for the blue variant:

```javascript
{
  "theme": "FlatlandB.sublime-theme",
  "color_scheme": "Packages/flatland/Color Scheme/Flatland.tmTheme"
}
```

If you need help locating your user preferences file, you can find it selecting "Preferences > Settings - User".

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // square file tabs instead of rounded corners
  "flatland_square_tabs": true,

  // Monokai theme (SublimeText's default) with Flatland background color
  "color_scheme": "Packages/flatland/Color Sceme/Flatland-Monokai.tmTheme"
}
```
