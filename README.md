# Dosa Theme

Dark and light custom UI themes for Sublime Text `2`, `3`, `4`

## Design

![Dosa Light Theme](https://bitst0rm-pub.github.io/theme-dosa/images/dosa-light-screenshot.png)

![Dosa Dark Theme](https://bitst0rm-pub.github.io/theme-dosa/images/dosa-dark-screenshot.png)

## Installation

**Using Git:**

If you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/bitst0rm-pub/theme-dosa.git "Theme Dosa"

**Download Manually:**

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme Dosa`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Dosa Light.sublime-theme"` or `"theme": "Dosa Dark.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "Dosa Light.sublime-theme"
    }

### Sublime Text 3 and 4

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Dosa Light 3.sublime-theme"` or `"theme": "Dosa Dark 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Dosa Light 3.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Dosa Theme ships with two alternate UI tab styles.

By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

    "dosa_classic_tabs": true

![Dosa Tab Styles](http://bitst0rm-pub.github.io/theme-dosa/images/features/multiple-tab-styles.png)

### Sidebar Folder Icons

Dosa Theme has folder icons by default with Sublime Text 3.

If you'd like to use folder icons in the Sublime Text 2 sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "dosa_folder_icons": true

![Dosa Folder Icons](http://bitst0rm-pub.github.io/theme-dosa/images/features/sidebar-folder-icons.png)

### Retina Resolution UI

Dosa Theme has been designed to take advantage of retina resolution (high-dpi) displays. Both Dosa Light and Dosa Dark support retina displays.

![Dosa Retina](http://bitst0rm-pub.github.io/theme-dosa/images/features/dosa-retina.png)

### Theme Customisation

Sublime Text provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Dosa Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

This modified version of Dosa Theme was inspired by the [Elementary theme](https://github.com/piotrkubisa/sublime-elementary). In case you might want to tweak the buttons:

* Download Photoshop source [theme-dosa-btn.zip](https://bitst0rm-pub.github.io/theme-dosa/extras/theme-dosa-btn.zip)

## License

Dosa Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.
