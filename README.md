# 4peg
4peg is a bash script that makes quick and easy vp9 WebMs under 4mb.

requires ffmpeg

to use, place 4peg in usr/local/bin and deploy it from the command line

the default mode is soundless, but if you want sound, add an 's' flag, like this:

```
4peg s myvideo.mp4
```

you can use individual filenames and entire directories as arguments, like this:

```
4peg myvideo.mp4 ./videos/catvids myvideo2.mp4 myvideo3.mp4
```
WebMs will share the same name as their inputs (i.e. myvideo.mp4 becomes myvideo.webm) and will output to the same directory as the input.

if you want to convert ALL files in the current directory, you can use a dot:
```
4peg .
```
# But what if my file is too big?
split it up using the part script. Specify the number of parts you want (if you don't specify, it defaults to 2) and add a file path, like this:
```
part 4 longvideo.mp4
```
part will only take one video at a time and does not have a soundless option. 







