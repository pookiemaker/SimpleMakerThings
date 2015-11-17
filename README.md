## SimpleMakerThings

Very Little code will be contained here. This is a collection of things I find useful

### Raspberry Pi specific 
### Run a python script at bootup
http://www.instructables.com/id/Raspberry-Pi-Launch-Python-script-on-startup/

### Run chromium in kiosk mode at bootup 
* http://blogs.wcode.org/2013/09/howto-boot-your-raspberry-pi-into-a-fullscreen-browser-kiosk/
* https://github.com/MobilityLab/TransitScreen/wiki/Raspberry-Pi
* https://www.raspberrypi.org/forums/viewtopic.php?t=8298&p=210611
* https://raspberrypi.stackexchange.com/questions/27572/how-to-auto-start-chromium-after-boot-on-the-raspberry-2-2015-01-31-debian-whee


<p>This is the one I used
* https://lokir.wordpress.com/2012/09/16/raspberry-pi-kiosk-mode-with-chromium/



###  Useful Bits
This is a list of things that I find useful. You can expect to find small sections for each of the areas. 


## Full Screen App, Rpi2 touchscreen
My next project is to make a full-screen app that boots to the app on a raspberry pi 2 with an adafruit 3.5" 320-480 TFT (https://learn.adafruit.com/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi) I am starting to look at pygame.



### pygame tutorial 
* https://pygame.org/docs/tut/newbieguide.html -- introducing pygame 
* http://blog.jacobean.net/?p=1016 -- weatherstation application
* https://stackoverflow.com/questions/24147026/display-gui-on-raspeberry-without-startx -- complex answers
* http://www.davidhunt.ie/piphone-a-raspberry-pi-based-smartphone/ PiPhone

#### Probably the most relevant
* http://jeremyblythe.blogspot.com/2014/09/raspberry-pi-pygame-ui-basics.html

## Kivy 
* https://www.youtube.com/watch?v=ZmteLworB4E youtube kivy crash course

##Processing 
* http://cagewebdev.com/index.php/raspberry-pi-running-processing-on-your-raspi/ on a RaspPi


## QR Codes
* http://blog.matael.org/writing/python-and-qrcodes/ updated and working well on raspbian


## GNU-radio 
* Looks like Jessie is supported, but wheezy is not
* http://www.rs-online.com/designspark/electronics/eng/blog/taking-the-raspberry-pi-2-for-a-test-drive-with-gnu-radio-2
* http://www.rtl-sdr.com/spektrum-new-rtl-sdr-spectrum-analyzer-software/

## Basic RaspPi info
* Wheezy and Jessie support different installed sub systems. 
* I managed to get Cirrus Logic Card operating on Wheezy, but it looks like I'll need Jessie to run GNUradio


## Hardware Random Number Generator
* http://scruss.com/blog/2013/06/07/well-that-was-unexpected-the-raspberry-pis-hardware-random-number-generator/
* http://stackoverflow.com/questions/27305636/how-to-get-pycrypto-to-use-my-random-number-and-not-its-own-when-creating-an-rsa
