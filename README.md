# VIM Emulator Config for VS Code

🎉 Welcome to my custom VIM emulator config for VS Code! 🎉

This config is designed to help you boost your productivity by providing some custom keybindings and settings to make your VIM experience smoother.

## Getting Started

### Step 1: Install the VIM Emulator Extension

First, you'll need to install the VIM Emulator extension from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim).

### Step 2: Replace Global Settings

<img src="./scrns/demo2.png" width="300"/>

Next, you'll need to replace the global `settings.json` file with the one provided in this repo. This file contains some custom settings that will optimize your VIM experience. You can do this by following these steps:

1. Open VS Code
2. Click on the "File" menu in the top left corner
3. Click on "Preferences"
4. Click on "Settings"
5. In the search bar, search for "settings.json"
6. Click on the "Edit in settings.json" button
7. Replace the contents of the file with the contents of `settings.json` from this repo
8. Save the file

### Step 3: Replace Global Keybindings

Now, you'll need to replace the global `keybindings.json` file with the one provided in this repo. This file contains some custom keybindings that will make your VIM experience even smoother. You can do this by following these steps:

1. Open VS Code
2. Click on the "File" menu in the top left corner
3. Click on "Preferences"
4. Click on "Keyboard Shortcuts"
5. In the search bar, search for "keybindings.json"
6. Click on the "Edit in keybindings.json" button
7. Replace the contents of the file with the contents of `keybindings.json` from this repo
8. Save the file

### Step 4: Make a Backup

Before you start using this config, please make a backup of your existing settings and keybindings files, in case you need to revert back to them later.

## Recommended Color Scheme

To get the best VIM experience with this config, we recommend using the "Just Black" color scheme for VS Code. You can install this color scheme by following these steps:

<img src="./scrns/demo.png"/>

1. Open VS Code
2. Click on the "Extensions" icon in the left-hand menu
3. Search for "Just Black" in the search bar
4. Click on the "Install" button next to the "Just Black" extension
5. Once installed, click on the "Color Theme" icon in the bottom left corner
6. Select "Just Black" from the list of available color schemes

#### Keyrepeat problems?

### Mac

To enable key-repeating, execute the following in your Terminal, log out and back in, and then restart VS Code:

```sh
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false              # For VS Code
defaults write com.microsoft.VSCodeInsiders ApplePressAndHoldEnabled -bool false      # For VS Code Insider
defaults write com.visualstudio.code.oss ApplePressAndHoldEnabled -bool false         # For VS Codium
defaults write com.microsoft.VSCodeExploration ApplePressAndHoldEnabled -bool false   # For VS Codium Exploration users
defaults delete -g ApplePressAndHoldEnabled                                           # If necessary, reset global default
```

We also recommend increasing Key Repeat and Delay Until Repeat settings in _System Preferences -> Keyboard_.

### Windows

Like real vim, VSCodeVim will take over your control keys. This behaviour can be adjusted with the [`useCtrlKeys`](#vscodevim-settings) and [`handleKeys`](#vscodevim-settings) settings.

## Conclusion

That's it! You should now be all set up to start using this custom VIM emulator config for VS Code. If you have any questions or issues, please feel free to [open an issue](https://github.com/your-repo-name-here/issues/new) in this repo. Happy coding! 😊
