# RockPi4B-I2S1-Capture    

Device Tree For Using INMP441 I2S microphone with Rock Pi 4.    
Pull up SD line of the microphone to VCC with 2.2K resistor, connect other pins of microphone accordingly to the I2S1 GPIO of Rock Pi 4.    

Tested with rockpi-4b-ubuntu-focal-server-arm64-20221101-0358-gpt.img.xz image from https://github.com/radxa-build/rock-pi-4b/releases/tag/20221101-0235 (kernel 5.10) on Rock Pi 4 model B.    

Add it to /boot/hw_initfc.conf and copy to /boot/overlays/    
