![pic](../img/pic.png)
1. Download iterm2
2. install zsh via homebrew
3. install oh my zsh(https://github.com/robbyrussell/oh-my-zsh) for zsh config
4. Change iterm 2 settings

# iterm2 settings:
* Preferences/Profiles/Text/Font: Meslo LG S DZ Regular for Powerline
* Preferences/Profiles/Text/Font size 20pt
* Preferences/Profiles/Colors/ColorPresets/SolarizedDarcula (downloaded from here: https://github.com/mbadolato/iTerm2-Color-Schemes)

5. under .oh-my-zsh/themes, run
```c
wget https://raw.githubusercontent.com/gitskim/LinuxConfigs/master/zsh/suhyun-ohmyzsh-theme.zsh-theme
```

6. Edit the .zshrc file.
```c
ZSH_THEME="suhyun-ohmyzsh-theme"
```

7. Done!
```
source .zshrc
```


