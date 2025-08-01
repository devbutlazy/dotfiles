
<div align="center">
<h1>LazyDev Dotfiles</h1>
</div>

<div align="center">
  <a href="#vscode"><kbd> <br> 📂 VSCode <br> </kbd></a>&ensp;&ensp;
  <a href="#pycharm"><kbd> <br> 📂 Pycharm <br> </kbd></a>&ensp;&ensp;
  <a href="#pwsh"><kbd> <br> ♾️ Terminal <br> </kbd></a>&ensp;&ensp;
</div>

<br>

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9e33ae7f-b37c-4ce0-9b64-e112cb1292e3" />


<div align="center" id="vscode">
<h1>Visual Studio Code</h1>
</div>

<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/cf99ddff-c278-4f65-b8ae-4a336e4a5821" />

# 📂 Plugins
```
UI/UX:
- Kanagawa Flavors (Wave)  
- Material Icon Theme
- Apc Customize UI ++
- Better Comments
- Markdown All in One 
- Error Lens 

Python:
- Python 
- Python Debugger 
- Pylance 
- Black Formater 

C/C++:
- C/C++
- clangd 
- CMakeTools 

Go:
- Go

Automations & Help:
- GitHub Actions 
- GitHub Pull Requests 
- GitLens
- Code runner
- Live Share
- SQLite Viewer
- YAML 
- Docker

Other:
- Discord Presence
- Polacode-2025 
```

# >_ Keybinds
```
Comment selected code: CTRL + K + C
Uncomment selected code: CTRL + K + U
Open pwsh: CTRL + SHIFT + C
Format code: SHIFT + ALT + F
Edit multiple rows: CTRL + SELECT ROWS
Other: Default ig. :/
```

## [settings.json](https://github.com/devbutlazy/dotfiles/tree/main/.config/vscode/settings.json) && [lazydev.code-profile](https://github.com/devbutlazy/dotfiles/tree/main/.config/vscode/lazydev.code-profile)

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
- Docker
- YAML Default 

Other:
- Discord Integration V2 
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

- Install [Windows Terminal](https://github.com/microsoft/terminal) (WT);
- Install [Powershell](https://learn.microsoft.com/ru-ru/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4) and configure it as default terminal in WT;
- Download [my WT Settings](https://github.com/devbutlazy/dotfiles/tree/main/.config/wt/settings.json) and replace them in yours;
- Install [Scoop](https://scoop.sh/);
- Install [Oh-My-Posh](https://ohmyposh.dev/) using scoop:
```
scoop install https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/oh-my-posh.json
```
- Add oh-my-posh to environmental variables, typing to pwsh:
```
$env:Path += ";C:\Users\YOUR_USER\AppData\Local\Programs\oh-my-posh\bin"
```
- Install [JetBrains Mono Font](https://www.jetbrains.com/lp/mono/);
- Install [GNUwin32](https://gnuwin32.sourceforge.net/packages/coreutils.htm) for GNU-like commands;
- Install [fastfetch](https://github.com/fastfetch-cli/fastfetch) (neofetch for windows) using scoop:
```
scoop install fastfetch
```
- Copy [my fastfetch config](https://github.com/devbutlazy/dotfiles/tree/main/.config/wt/fastfetch) to `C:\Users\<Username>\.config\fastfetch\config.conf`;
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
- Remove powershell greeting message by passing "--nologo" flag in startup settings
  
## All configs can be found [here](https://github.com/devbutlazy/dotfiles/tree/main/.config/wt)
