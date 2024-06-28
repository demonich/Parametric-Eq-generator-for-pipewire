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

After running the script, you will discover in audio properties a new audio source: "Pipewire Equalizer". But don't switch to it!

You must click in its properties "use only this device to play sound" (in KDE Plasma)

![audio-properties-eq](https://github.com/demonich/Parametric-Eq-generator-for-pipewire/assets/74813436/1c4c548e-d22c-4dd2-989d-41b15cbf79bf)

I don't know hot to do this in Gnome, sorry...

Now, you can use your normal audio slider for volume, and eq slider for preamp 

(in short, don't make it 100%, or you will feel speakers overload, which is obviously bad for you and your equipment)
