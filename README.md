# ~/.asoundrc configuration file for alsa
1. arecord test.wav -d 5 -c4 -r 48000 -f S16_LE #record a wav file using 4 channels mic-array, rate 48kHz, 16bit signed, duration 5 seconds  
2. aplay test.play #play with default pcm  
3. aplay -D mid test.play #play with mid pcm (output sound to bluetooth speakers)  
4. sudo cp ~/asoundrc /etc/asound.conf #create permanent settings alsa  
