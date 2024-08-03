# VSCode Settings

This repository contains a custom `settings.json` files that enhance the UI of Visual Studio Code with specific fonts and other UI configurations.

## Features: `settings1.json`

- **Theme**: React Theme
- **Icon Theme**: Moxer Icons
- **Fonts**:
  - Editor: Geist Mono
  - Terminal: JetBrainsMono Nerd Font
- **UI Tweaks**:
  - Minimap disabled
  - Custom scrollbar settings
  - Custom title bar and status bar
  - Custom CSS and JS files
  - Custom Command Pallete

![Custom Home Page](settings1-1.png)

![Custom Command Pallete](settings1-2.png)

![View in a .tsx file](settings1-3.png)

## Features: `settings2.json`

- **Theme**: Aura Soft Dark (Soft Text)
- **Icon Theme**: Moxer Icons
- **Fonts**:
  - Editor: Geist Mono
  - Terminal: JetBrainsMono Nerd Font
- **UI Tweaks**:
  - Minimap disabled
  - Custom scrollbar settings
  - Custom title bar and status bar

![View in a .tsx file](settings2.png)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/marinactonci/vscode-settings.git
   ```

2. **Copy either `settings1.json` or `settings2.json`:**
   - Replace your existing `settings.json` file located in:
     ```sh
     ~/.config/Code/User/settings.json
     ```
   - Or open VSCode, go to `Preferences` > `Settings`, and choose `Open Settings (JSON)` to paste the contents.

3. In case your selected to use the `settings1.json` you'll also need to install `Custom CSS and JS Loader` extension and inside of the `settings.json` change the paths to the custom css and js files to paths the files are located in on your system. Finally, open Command Pallete and run `Enable Custom CSS and JS`.

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
