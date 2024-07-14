# VSCode Settings

This repository contains a custom `settings.json` file that enhances the UI of Visual Studio Code with specific fonts and other UI configurations.

## Features

- **Theme**: Aura Soft Dark (Soft Text)
- **Icon Theme**: Moxer Icons
- **Fonts**:
  - Editor: Geist Mono
  - Terminal: JetBrainsMono Nerd Font
- **Font Size**: 14px
- **UI Tweaks**:
  - Minimap disabled
  - Custom scrollbar settings
  - Custom title bar and status bar

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/marinactonci/vscode-settings.git
   ```

2. **Copy `settings.json`:**
   - Replace your existing `settings.json` file located in:
     ```sh
     ~/.config/Code/User/settings.json
     ```
   - Or open VSCode, go to `Preferences` > `Settings`, and choose `Open Settings (JSON)` to paste the contents.
  
## Usage

After installation, restart VSCode to apply the new settings. Ensure that the fonts mentioned are installed on your system.


# MacOS Terminal 

## Install Homebrew if you haven't already:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After installing, add it to the path (replace `[username]` with your atual username):

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/[username]/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

You can cherck whether homebrew is installed by running:

```bash
brew --version
```

## iTerm2

```bash
brew install --cask iterm2
```

## Install Oh My Zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install PowerLevel10k theme for Oh My Zsh

```bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

Open the `~/.zshrc` file with your preferred editor and change the value of `ZSH_THEME`:

```bash
ZSH_THEME="powerlevel10k/powerlevel10k"
```

```bash
source ~/.zshrc
```
