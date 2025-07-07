# Parametric Eq config generator for pipewire

A python script that creates a configuration file for pipewire's sink eq using configuration files intended for easyeffects from the [autoeq.app](https://autoeq.app/)

The script generates, copies and applies the configuration file for you. 

Of course, to get benefits, your system (linux-based distribution) should using Pipewire multimedia framework, instead of pulseaudio.

## Demo

https://github.com/demonich/Parametric-Eq-generator-for-pipewire/assets/74813436/23d09cb3-099c-464f-b5fb-27cb8492d89b

## How to use it

Create a folder, put the script there and config txt file from [autoeq.app](https://autoeq.app/) (in equalizer section choose 'easyeffects').

Run script (inside file manager (make it execuable in properties first) or in terminal, you choose). File picker will appear, select there your txt file, press OK.

Done.

## How to enable equalizer

As far as I know, you should manually enable it for every app that plays audio. This can be done in the sound settings (in the application volume section).

![Снимок экрана от 2024-07-07 18-28-26](https://github.com/demonich/Parametric-Eq-generator-for-pipewire/assets/74813436/c805cfd6-1a91-421c-a30e-cf496d027490) 

![Снимок экрана от 2024-07-07 18-32-13](https://github.com/demonich/Parametric-Eq-generator-for-pipewire/assets/74813436/27b80c62-8e84-45e2-8847-182a0da59044)

## Troubleshooting

### "tkinter" import failed

Install ```tk```

```
#ubuntu
sudo apt install python3-tk
```

```
#fedora
sudo dnf install python3-tkinter
```

```
#arch
sudo pacman -S tk
```
