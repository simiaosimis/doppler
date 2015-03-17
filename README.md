# Motion sensing using the doppler effect
[This is an implementation](http://danielrapp.github.io/doppler/) of the [SoundWave paper](http://research.microsoft.com/en-us/um/redmond/groups/cue/publications/guptasoundwavechi2012.pdf)
on the web. It enables you to detect motion using only the microphone and speakers!

# The Game

Is a survival game that uses the motion sensing to controll the player, you just need to move your hands near to the microfone of your computer/smartphone.

# Running
You can run the game with the flag --allow-file-access-from-files on chromium browser.

## Firefox?
Unfortunately this doesn't work on Firefox since it doesn't seem to support the `echoCancellation: false` parameter to navigator.getUserMedia. This means there's no way to turn off it filtering out the sounds which are coming from the computer itself (which is precisely what we want to measure).
