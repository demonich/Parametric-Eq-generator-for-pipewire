# Parametric-Eq-generator-for-pipewire
A python script that creates a configuration file for pipewire's sink eq using configuration files for easyeffects from the autoeq.app

Moreover, the script copies the configuration file where needed and applies it for you.

Of course, to get benefits your system (linux-based distribution) should using Pipewire multimedia framework, instead of pulseaudio.
## how to enable equalizer
After running the script, you will discover in audio properties a new audio source: "Pipewire Equalizer". But don't switch to it!

You must click in its properties "use only this device to play sound" (in KDE Plasma)

![audio-properties-eq](https://github.com/demonich/Parametric-Eq-generator-for-pipewire/assets/74813436/1c4c548e-d22c-4dd2-989d-41b15cbf79bf)

I don't know hot to do this in Gnome, sorry...

Now, you can use your normal audio slider for audio, and eq slider for preamp 

(in short, don't make it 100%, or you will feel speakers overload, which is obviously bad for you and your equipment)
