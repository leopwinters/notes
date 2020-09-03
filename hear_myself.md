# Hear myself in Linux

For a live playback of your own microphone, played through your speakers, in Linux using pulseaudio, use:

```sh
pactl load-module module-loopback latency_msec=1
```
