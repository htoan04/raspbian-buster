# ~/.asoundrc configuration file for alsa
arecord <test.wav> -d 5 -c4 -r 48000 -f S16_LE
aplay <test.play>
