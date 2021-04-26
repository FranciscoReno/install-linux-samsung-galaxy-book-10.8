# Runing Ubuntu on Samsung Galaxy Book 10.6

Sharing some experiences about running, more precisely trying to run, Linux on a Samsung Galaxy Book 10.6" x86 tablet.

## What works

Basic functionality is working :

* Keyboard
* Touchpad
* Adaptive brightness
* Touchscreen
* Screen orientation
* WiFi
* Sound via bluetooth

## Not Working :

* Webcam
* Sound via speakers and via 3.5 audio jack
* Gyroscope

## Kind of Buggy

* Screen Refresh rate
* Trackpad

## Customization of the tablet

The tablet configuration was like this :

    Samsung Galaxy Book 10.6
    Intel(R) Core(TM) m3-7Y30 CPU @ 1.00GHz
    4GB RAM
    64GB SSD
    10.6" touchscreen display
    + a cover keyboard



## Trying Linux Live

The computer came with _Windows 10 Home_ installed.

Download **Ubuntu 20.04 x86_64** and write it on an USB drive.

Here is the steps to boot from the USB drive :

* Boot the computer
* On the boot screen displaying Samsung Galaxy Book Logo press **F10**
* Choose the USB UEFI entry

Boot the usual Ubuntu live session :

* Screen is in portrait mode :
  * open a terminal
  * type "xrandr -o left"

WiFi will not work out of the box... so you need an adapter or share internet via bluetooth with a cellphone.

To get the wifi working, follow this --> https://github.com/kirvedx/atheros#atheros


You will notice that when you disconnect the cover (with the trackpad and keyboard) and then reconnect it, the trackpad will not work again untill you reboot the system or lock the screen.


I use like this and works fine ... just skip google chrome, it's very laggy. 
