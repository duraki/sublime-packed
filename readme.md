# Packed
  
Ultra dark user interface for Sublime Text 3.

Fully featured Sublime Text 3 color scheme and UI theme in hackish, digital 
and sick form. Inspired by Vim, Emacs, [irssi weed-theme](https://github.com/ronilaukkarinen/weed).
  
Parent hierarchy:  
  * **Icon set**: [FileIcons](https://github.com/braver/FileIcons) + custom icons
  * **Colorscheme**: [1337 Scheme](https://github.com/MarkMichos/1337-Scheme) + custom fixes
  * ---
  * [Spacefunk](https://github.com/Twiebie/ST-Spacefunk) => 
  * [Devastate](https://github.com/vlakarados/devastate) => 
  * [DevastateMini](https://github.com/shagabutdinov/sublime-devastate-mini) =>
  * **Theme**: [Packed](https://github.com/duraki/sublime-packed) => (this package)
  
Icons distributed by [braver](https://github.com/braver/FileIcons). Theme DevastateMini 
distributed by [vlakarados/devastate](https://github.com/vlakarados/devastate).
  
To clone this repository:

```bash
$ git clone git@github.com:duraki/sublime-packed.git
```
  
## Introduction
  
Since switching to ST3, I've spent time searching for config that will support  
all my requirements. I found none. Therefore, I built this for myself and now share  
it openly, so others can enjoy it too.
  
**Pros**: easy to use, extend and looks slick out-of-the box, you will feel 30x more productive  
**Cons**: might get you addicted to ST3, your friends will think you are hacking NSA  
  
New features:  
  * Unique, Vim-like user interface  
  * Max compact view, forced minimal dimensions on UI elements  
  * New color scheme, easy on your eyes  
  * Includes `*.sublime-settings` to provide custom mods  
  * Includes `tewi` (bitmap) font provided by @Confuseh (@see lucy/tewi-font#23)  
  * Includes *Extras* for featured/supported Packages (@see `/extras`)  
  * Richful syntax support for [Ruby](https://www.ruby-lang.org/) & [Crystal](http://crystal-lang.org/)  
  
Linux and OSX friendly! Tested under MacOS High Sierra, Sublime Text build 3176.
  
Donate:
  
| Service      | Wallet                                                                                                                  |
|:-------------|:------------------------------------------------------------------------------------------------------------------------|
| Bitcoin      | 14nEUXKgxovKNBwMR25UA6UQs79UFygzDG                                                                                      |
| Bitcoin Cash | qptsv80vxj9tnesvd0yuqyrnfufc9xjvusnv389ywj                                                                              |
| Ethereum     | 0xD1c72EA0b860b65c3fDfc6945ec1D2761eDa5785                                                                              |
| PayPal       | hadr.pz@gmail.com [Link](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QBAS2NTRDT6B4&source=url) |
  
## Requirements
  
This interface is supported and developed on Sublime Text 3, I will not provide 
patches to older versions! 
  
* Sublime Text 3 (tested on build 3176) 
* Package Control for quick install (else, do manual installation)
* `Tewi` font installed (included ttf in `/ttf/tewi.ttf`)
  - **MacOS / OSX**: `cp ttf/tewi.ttf ~/Library/Fonts/`
  - **GNU / Linux**: `cp ttf/tewi.ttf ~/.fonts/ && fc-cache -f`
  
## Installation

### via Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/installation) installed.
2. Choose Install Package from the Command Palette (via `Tools > Coomand Palette` from the main menu).
3. Select **`Packed`** and press <kbd>Enter</kbd>.

### or Manual Installation

1. Download or clone the desired **`sublime-packed`** repository.
2. Browse Packages from the Command Palette (via `Preferences > Browse packages` from the main menu).
3. Copy the **`sublime-packed`** file to `Packages/User/`.
  
### or Other way

The best way to use this theme professionally is to fork it, otherwise installing 
the package will not store permanent changes.
  
## Activation
  
To activate the UI, you need to configure and enable it through `User.Preferences` file.
  
Simply go to User Preferences (`"Preferences: Settings - User"` in command palette) and add:
  
    "color_scheme": "Packages/Packed/Packed.tmTheme",
    "theme": "Packed.sublime-theme",

## Configuration
  
**Note**: This step isn't necessary. Just restart your ST3 after enabling the theme to 
use and enjoy it.
  
*Custom configuration* provides additional settings for various options.
If you may want to manually configure specific theme options; simply 
copying/editing the content of `Packed.Preferences` from this repository 
to your *User* configuration file is enough.
  
Copy the content of `Packed.Preferences` to User Preferences (`"Preferences: Settings -
User"` in command palette).

## Screenshots

## LICENSE ##

Copyright (c) 2019 `duraki/sublime-packed`, MIT 

See [`LICENSE`](./LICENSE) for details.
