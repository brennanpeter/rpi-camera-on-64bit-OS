# rpi-camera-on-64bit-OS
Quick guide on how I was able to get my rpicam working on Ubuntu 20.04

```$ sudo apt install libraspberrypi-bin```

```$ vcgencmd get_camera```

```$ sudo modprobe bcm2835-v4l2```
  ( and that is v-4-L-2 NOT a 1 )

```$ vokoscreen```


The most useful thread I found was here https://www.raspberrypi.org/forums/viewtopic.php?f=43&t=285868#p1729854

Then I realized I was typing the modprobe command in wrong after reading this thread here:
https://github.com/geraldoramos/pigeon/issues/24
