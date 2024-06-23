# tooling
List of tools that I love and use everyday

## The list

- https://github.com/rxhanson/Rectangle
- https://github.com/exelban/stats
- https://github.com/zed-industries/zed
- https://github.com/sharkdp/bat
- https://github.com/sharkdp/fd
- https://github.com/mgdm/htmlq
- https://jqlang.github.io/jq
- https://github.com/so-fancy/diff-so-fancy
- [fzf](https://github.com/junegunn/fzf)
- [fzf-z](https://github.com/andrewferrier/fzf-z)
- [fzf-tab](https://github.com/Aloxaf/fzf-tab)


### Apps

- [keepingyouawake](https://keepingyouawake.app/) - Prevents my Mac from going to sleep when I'm presenting / live streaming
- [discord](https://discord.com/) - Messaging / Community
- [vlc](https://www.videolan.org/) - I use VLC to watch videos instead of the built in QuickTime.
- [keka](https://www.keka.io/en/) - Can extract 7z / rar and other types of archives
- [kap](https://getkap.co/) - Screen recorder / gif maker
- [visual-studio-code](https://code.visualstudio.com/) - Code Editor
- [sublime-text](https://www.sublimetext.com/) - Note taking (I know there are better apps...)
- [zed](https://zed.dev/) - Another FAST text editor
- [iTerm2](https://iterm2.com/) - macOS terminal replacement
- [oh-my-zsh](https://ohmyz.sh/) - A framework for managing your Zsh configuration
- [Sloth](https://github.com/sveinbjornt/Sloth) - Mac app that shows all open files, directories, sockets, pipes and devices in use by all running processes. Nice GUI for lsof.
- [Hiddenbar](https://github.com/dwarvesf/hidden) - An ultra-light MacOS utility that helps hide menu bar icons
- Ollama
- Flameshot - Cross platform screenshot and recording tool
- font-hack-nerd-font
- font-fira-code
- tfenv
- watch
- Postman
- Ripgrep (rg)
- tldr
- wget
- neovim
- gh
- Slack
- Rectangle
- Notion
- Warp
- fzf
- Spotify
- Whatsapp
- ffmpeg
- imagemagick
- nvm
- pyenv
- Firefox
- 


## Installation

```
brew install bat fd rectangle stats htmlq jq iterm2
```

```
brew tap homebrew/cask-versions
brew install --cask zed
brew install --cask docker
brew install --cask sloth
brew install --cask hiddenbar
```

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```


## Zsh config

```
export NVM_LAZY_LOAD=true
plugins=(git z fzf-z zsh-nvm)

alias -g -- --help='--help 2>&1 | bat --language=help --style=plain'

# tomasr/molokai
export FZF_DEFAULT_OPTS='--color=bg+:#293739,bg:#1B1D1E,border:#808080,spinner:#E6DB74,hl:#7E8E91,fg:#F8F8F2,header:#7E8E91,info:#A6E22E,pointer:#A6E22E,marker:#F92672,fg+:#F8F8F2,prompt:#F92672,hl+:#F92672'
```

