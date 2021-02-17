# swan, a self-practice OS.

Some ideas, may or may not be implemented

Scheduler:
Loterry Scheduler but with Spotify's randomness algorithm 

https://engineering.atspotify.com/2014/02/28/how-to-shuffle-songs/
(which is inpired from http://keyj.emphy.de/balanced-shuffle/)


- Everything is a file, as in Plan 9

- Arm MPU support

- Go style goroutines instead of threads

- built in CSP library for C. For Kernel if possible.


syscalls:
yield
fork
exec

possible targeted devices: 
stm32 bluepill (arm cortex-m3)

todo:

uart output []
