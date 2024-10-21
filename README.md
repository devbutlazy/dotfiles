
<div align="center">
<h1>LazyDev Dotfiles</h1>
</div>

<div align="center">
  <a href="#about"><kbd> <br> 🌷 About <br> </kbd></a>&ensp;&ensp;
  <a href="#setup"><kbd> <br> 🔧 Setup <br> </kbd></a>&ensp;&ensp;
  <a href="#gallery"><kbd> <br> 🖼️ Gallery <br> </kbd></a>&ensp;&ensp;
  <a href="#credits"><kbd> <br> 🎉 Credits <br> </kbd></a>&ensp;&ensp;
</div>


![image](https://github.com/user-attachments/assets/a36dc04d-9c40-4154-bfea-38b8f28f906d)


<div align="center" id="vscode">
<h1>VS Code</h1>
</div>

![image](https://github.com/user-attachments/assets/77c53c36-1045-4647-ab20-a6aabd0731dd)

# 📂 Plugins
```
Design:
- Catppuccin for VSCode - Catppuccin Mocha (VSCode Theme)
- Apc Customize UI ++ - customize VSCode explorer
- Bearded Icons (VSCode Explorer icons)
- Better Comments (Comments design with !, #, ?, etc.. prefixes)
- Markdown All in One - System Default (README.md Preview Theme)
- Bracket Pair Color DLW - code brackets colors
- Error Lens - errors directly in code

Python:
- Python (Python typehints)
- Python Debugger 
- Pylance 
- Black Formater (Python PEP-8 formatter [CTRL + ALT + F])

Automations & Help:
- Codeium (AI with autocomplete)
- GitHub Actions (View GitHub Actions in a tab)
- GitHub Pull Requests (Send pull requests easily)
- SQLite Viewer (View database files directly in VSCode)
- YAML (.yml, .yaml files typehints)
- Docker (Dockerfile and Docker-Compose typehints)

Other:
- Discord Presence (Show the coding process with details in Discord Status)
- Polacode-2022 (Beautiful screenshots [CTRL + SHITF + P -> Polacode])
```

# >_ Keybinds
```
Comment selected code: CTRL + K + C
Uncomment selected code: CTRL + K + U
Format code: SHIFT + ALT + F
Edit multiple rows: ALT + SELECT ROWS
Other: Default
```

# [settings.json](https://github.com/devbutlazy/dotfiles/tree/main/vscode/settings.json)
# [lazydev.code-profile](https://github.com/devbutlazy/dotfiles/tree/main/vscode/lazydev.code-profile)

<div align="center" id="pycharm">
<h1>Pycharm</h1>
</div>

![image](https://github.com/user-attachments/assets/84809930-f5df-4887-918f-67bd8578d71d)


# 📂 Plugins
```
Theme:
- Monokai Pro - Filter Spectrum
- Markdown Default

Automations & Help:
- Codeium (AI with autocomplete)
- Docker (Dockerfile and Docker-Compose typehints)
- YAML Default (.yml, .yaml files typehints)

Other:
- Discord Integration V2 (Show the coding process with details in Discord Status)
```

# >_ Keybinds
```
Comment selected code: CTRL + /
Uncomment selected code: CTRL + /
Format code: CTRL + ALT + L 
Edit multiple rows: ALT + SELECT ROWS
Other: Default
```

# [settings.zip](https://github.com/devbutlazy/dotfiles/tree/main/pycharm/settings.zip)

<div align="center" id="pwsh">
<h1>Terminal</h1>
</div>

![image](https://github.com/user-attachments/assets/19acc8df-46e9-4e20-8d7f-5cb7c508067d)

# ♾️ Installation

- Install [Windows Terminal](https://github.com/microsoft/terminal) (WT)
- Install [Powershell](https://learn.microsoft.com/ru-ru/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4) and configure it as default terminal in WT
- Download [my WT Settings](https://github.com/devbutlazy/dotfiles/tree/main/wt/settings.json) and replace them in `C:\Users\<Username>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json`
- Install [Scoop](https://scoop.sh/)
- Install [Oh-My-Posh](https://ohmyposh.dev/) using scoop:
```
scoop install https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/oh-my-posh.json
```
- Add oh-my-posh to environmental variables, typing to pwsh:
```
$env:Path += ";C:\Users\YOUR_USER\AppData\Local\Programs\oh-my-posh\bin"
```
- Install [JetBrains Mono Font](https://www.jetbrains.com/lp/mono/)
- Install [GNUwin32](https://gnuwin32.sourceforge.net/packages/coreutils.htm) for GNU-like commands
- Install [fastfetch](https://github.com/fastfetch-cli/fastfetch) (neofetch for windows) using scoop:
```
scoop install fastfetch
```
- Copy [my fastfetch config](https://github.com/devbutlazy/dotfiles/tree/main/wt/fastfetch) to `C:\Users\<Username>\.config\fastfetch\config.conf`
- Install eza (enhanced version of "ls" GNU command) using scoop:
```
scoop install eza
```
- Install bat (enhanced version of "cat" GNU command) using scoop:
```
scoop install bat
```
- Create a notepad (config file) in pwsh typing `notepad $profile`, and paste this:
```
Set-Alias -Name ls -Value eza
Set-Alias -Name cat -Value bat
Set-Alias -Name neofetch -Value fastfetch

oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/refs/heads/main/themes/catppuccin_mocha.omp.json' | Invoke-Expression
```

## All configs can be found [here](https://github.com/devbutlazy/dotfiles/tree/main/wt)

### [Notepad $profile (config)](https://github.com/devbutlazy/dotfiles/tree/main/wt/notepad_profile.txt)
### [Terminal settings](https://github.com/devbutlazy/dotfiles/tree/main/wt/settings.json)
### [Fastfetch (neofetch) config](https://github.com/devbutlazy/dotfiles/tree/main/wt/fastfetch)

#

```
Inspired by: https://github.com/nixxoq/dotfiles
```
