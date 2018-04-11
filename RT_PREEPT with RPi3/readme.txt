HOW TO INSTALL (Tested in Rpi3 Model B):

* Install RPi OS from the given image (in the zip file: 2018-03-13-raspbian-stretch-lite.zip)

Download location: https://my.pcloud.com/publink/show?code=kZVRMQ7ZwNRGAAvlauFCACwbaR9LTYyIXsak


* Login to Pi

* Copy the *.deb packages from rtdebpackages.zip directory to Pi

* In Pi: Extract rtdebpackages.zip, navigate to /rtdebpackages directory and install all the deb packages

sudo dpkg -i *.deb

* (optional) add the following to /boot/config.txt 

kernel=vmlinuz-4.9.80-rt62-v7+
