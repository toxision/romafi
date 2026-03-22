# romafi
Simple Rofi launcher to browse and play SomaFM radio stations using mpv

<img width="413" height="565" alt="Screenshot_2026-03-20_09-25-12" src="https://github.com/user-attachments/assets/555f035e-e5a6-4b72-9c2b-e250c758fd1e" />


## Features
- Select station via rofi
- Play in background using mpv
- Stop running stream(s)
- Refresh station list
- Selector to play a random station

## Requirements
- rofi
- mpv
- curl & jq (only to refresh station list)
- notify-send (libnotify)
- an emojifont for rendering some menu entries

## Usage
1. copy the files into $HOME/.config/rofi/
2. bind script "somafmplayer" to a keyboard shortcut or any other way you want to launch the player 😎

## Station list
Auto-generated via SomaFM API (MP3 streams)
