# SFMono-Nerd-Font-Ligaturized
This repository contains pre-patched opentype versions of macOS's SFMono fonts with support for Ligatures and Nerd Fonts. 

## Showcase
<img width="1087" alt="image" src="https://user-images.githubusercontent.com/71196912/205556850-5805aad7-3500-4a98-9ef2-b0cdc6aff957.png">
<img width="1514" alt="image" src="https://user-images.githubusercontent.com/71196912/205555115-7079b836-2c7e-43d7-b81b-256cc8d12807.png">

## Installation
### Homebrew
Needs a working installation of `brew`
```sh
brew tap shaunsingh/SFMono-Nerd-Font-Ligaturized
brew install --caks font--sf-mono-nerd-font-ligaturized
```

### Manual
#### Linux
Copy all of the font files to `~/.local/share/fonts`
```sh
git clone https://github.com/shaunsingh/SFMono-Nerd-Font-Ligaturized.git && cd SFMono-Nerd-Font-Ligaturized
cp *.otf ~/.local/share/fonts
```

#### MacOS
1. Either clone or download and unzip this repository
2. Highlight and double-click to install all `.otf` files with Font Book

## Features
Contains the following Iconsets:
- fontawesome
- fontawesomeextentions
- fontlogos
- octicons
- codicons
- pomicons
- powerline (height adjusted)
- powerlineextra (height adjusted)
- material
- weather

Ligatures are from FiraCode v3.1
