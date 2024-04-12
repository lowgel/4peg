# 4peg
4peg is a bash script that makes quick and easy vp9 WebMs under 4mb.

requires ffmpeg

to use, place 4peg in usr/local/bin and deploy it from the command line

the default mode is soundless, but if you want sound, add and 's' flag, like this:

```
4peg s myvideo.mp4
```

you can use individual filenames and entire directories as argugments, like this:

```
4peg myvideo.mp4 ./videos/catvids myvideo2.mp4 myvideo3.mp4
```
WebMs will share the same name as their inputs (i.e. myvideo.mp4 -> myvideo.webm) and will output to the same directory as the input.





