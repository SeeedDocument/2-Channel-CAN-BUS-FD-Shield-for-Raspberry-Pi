---
name: 2-Channel CAN-BUS(FD) Shield for Raspberry Pi
category: 
bzurl: 
oldwikiname: 
prodimagename: 
surveyurl: 
sku: 103030296

---

![enter image description here](https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi-wiki.jpg)


CAN BUS shield for Raspberry Pi, 2 channel CAN BUS I/O, support [CAN FD](https://en.wikipedia.org/wiki/CAN_FD). CAN FD support much faster transmission speed(up to 8Mbps)
 
Also it have two On-board 120Ω terminating resistors which are controlled by the switches.

 
<p style="text-align:center"><a href="https://www.seeedstudio.com/Grove-12-Channel-Capacitive-Touch-Keypad-ATtiny1616-p-4068.html" target="_blank"><img src="https://github.com/SeeedDocument/wiki_english/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png" /></a></p>



## Features

- High-speed transfer rate: 8Mbps@10m 20AWG shielded cable / 1Mbps@40m 20AWG shielded cable
- Stable power supply, selectable Raspberry Pi power supply or DC power supply
- Compatible with Raspberry Pi 2, Raspberry Pi 3, Raspberry Pi 3 and Raspberry Pi Zero
- One-button configuration of 120Ω terminating resistor
- Support CAN FD



## Hardware Overview


<div align="center">
<figure>
  <a href="https://raw.githubusercontent.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/master/img/block.jpg" target="_blank"><img src="https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/block.jpg" alt="Raspberry Pi CAN BUS shield" title="hardware overview" />
  <figcaption><b>Figure 1</b>. <i>Hardware overview A</i></figcaption></a>
</figure>
</div>


<div align="center">
<figure>
  <a href="https://raw.githubusercontent.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/master/img/block2.jpg" target="_blank"><img src="https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/block2.jpg" alt="Raspberry Pi CAN BUS shield" title="hardware overview" />
  <figcaption><b>Figure 2</b>. <i>Hardware overview B</i></figcaption></a>
</figure>
</div>


<div align="center">
<figure>
  <a href="https://raw.githubusercontent.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/master/img/block-diagram.jpg" target="_blank"><img src="https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/block-diagram.jpg" alt="Raspberry Pi CAN BUS shield" title="hardware overview" />
  <figcaption><b>Figure 3</b>. <i>Block Diagram</i></figcaption></a>
</figure>
</div>



## Mounting Guide

<div align="center">
<figure>
  <a href="https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/setup.jpg" target="_blank"><img src="https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/setup.jpg" alt="Raspberry Pi CAN BUS shield" title="hardware overview" />
  <figcaption><b>Figure 4</b>. <i>Mounting Guide</i></figcaption></a>
</figure>
</div>


!!!Attention
       You can see that we used nylon columns during assembly to avoid short-circuiting between the metal terminals under the CAN BUS port and the HDMI interface on the Raspberry Pi. So please be sure to assemble the nylon column as shown.




## Specification

|Parameter|Value|
|---|---|
|Power Input|12V~24V DC<br>Raspberry Pi GPIO 5V|
|CAN FD Controller| [MCP2517FD](https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/res/MCP2517-datasheet.pdf) |
|CAN FD Transceiver|[MCP2557FD](https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/res/MCP2557-datasheet.pdf)|
|CAN FD Channel|2|
|Transfer Rate|8Mbps@10m 20AWG shielded cable <br> 1Mbps@40m 20AWG shielded cable|
|Communication Interface with Pi|SPI|
|Grove Interface|Grove I2C x2|







## Platforms Supported

| Arduino                                                                                             | Raspberry Pi                                                                                             | BeagleBone                                                                                      | Wio                                                                                               | LinkIt ONE                                                                                         |
|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| ![](https://raw.githubusercontent.com/SeeedDocument/wiki_english/master/docs/images/arduino_logo_n.jpg) | ![](https://raw.githubusercontent.com/SeeedDocument/wiki_english/master/docs/images/raspberry_pi_logo.jpg) | ![](https://raw.githubusercontent.com/SeeedDocument/wiki_english/master/docs/images/bbg_logo_n.jpg) | ![](https://raw.githubusercontent.com/SeeedDocument/wiki_english/master/docs/images/wio_logo_n.jpg) | ![](https://raw.githubusercontent.com/SeeedDocument/wiki_english/master/docs/images/linkit_logo_n.jpg) |






## Getting Started


### Play with Raspberry pi

**Materials required**

| Raspberry pi | 2-Channel CAN-BUS(FD) Shield for Raspberry Pi| Arduino Board |CAN-BUS Shield V2 |
|--------------|-------------|-----------------|-----|
|![enter image description here](https://github.com/SeeedDocument/wiki_english/raw/master/docs/images/rasp.jpg)|![enter image description here](https://github.com/SeeedDocument/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi/raw/master/img/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi-thumbnail.png)|![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_Light_Sensor/master/images/gs_1.jpg)|![]()
|[Get ONE Now](https://www.seeedstudio.com/Raspberry-Pi-3-Model-B-p-2625.html)|[Get ONE Now](https://www.seeedstudio.com/2-Channel-CAN-BUS-FD-Shield-for-Raspberry-Pi-p-4072.html)|[Get ONE Now](https://www.seeedstudio.com/CAN-BUS-Shield-V2.html)|




Also we need to two [male to male jumper](https://www.seeedstudio.com/Breadboard-Jumper-Wire-Pack-241mm-200mm-160mm-117m-p-234.html) and power cables to power those boards.



- **Step 1**. Plug the Grove Base Hat into Raspberry.
 
- **Step 2**. Connect the Grove 12 button Capacitive Touch Keypad to **UART** port of the Base Hat.

- **Step 3**. Power on the Raspberry Pi.


![](https://github.com/SeeedDocument/Grove-12-Channel-Capacitive-Touch-Keypad-ATtiny1616/raw/master/img/pii-connect.jpg)



#### Software


##### UART Setting

Before start, we need to configure the Raspberry Pi UART.



- Step 1. Enable Raspberry Pi3 **UART0**.

```
sudo nano /boot/config.txt
```
Then add the content `dtoverlay=pi3-disable-bt` to the end of the **config.txt**

Tap ++ctrl+x++ to quit nano, and tap ++y++ to save the modification.



- Step 2. Disable the system serivce to use the UART0.

```
sudo systemctl disable hciuart
```

!!!Note
        Pi3-disable-bt disables the Bluetooth device and restores UART0/ttyAMA0 to GPIOs 14 and 15. It is also necessary to disable the system service that initialises the modem so it doesn't use the UART: sudo systemctl disable hciuart.

- Step 3. Delete the `console=serial0,115200` in **cmdline.txt**.

```
sudo nano /boot/cmdline.txt
```

Then delete `console=serial0,115200` in this file.

!!!Note
        If you can not find `console=serial0,115200` in this txt file, just skip this step.


- Step 4. Reboot the Raspberry Pi

```
sudo reboot
```

For more detial, please check the official [Raspberry Pi UART Config](https://www.raspberrypi.org/documentation/configuration/uart.md)


##### Raspberry Pi Demo

- **Step 1**. Follow [Setting Software](http://wiki.seeedstudio.com/Grove_Base_Hat_for_Raspberry_Pi/#installation) to configure the development environment.


After the system environment is successfully configured, you can see a prompt like this:


```C++
Running setup.py install for grove.py ... done
Successfully installed grove.py-0.6
#######################################################
  Lastest Grove.py from github install complete   !!!!!
#######################################################

```

Now, tap 'ls', you can find the **grove.py** folder under the root directory.

```c++
pi@raspberrypi:~ $ ls
01_HelloRPi            Desktop    MagPi         rpi_apa102driver
01_HelloRPi.cpp        Documents  Music         Templates
4mics_hat              Downloads  ofxGPIO       Videos
apa102_led.c           env        Pictures      wiringpi_apa102
bcm2835-1.50           grove.py   Public        wiringpi_apa102.cpp
bcm2835-1.50.tar.gz    led        python_games
bcm2835-1.50.tar.gz.1  led1       respeaker

```



- **Step 3**. Excute the following commands to run the demo.

```
cd grove.py/grove
python grove_12_channel_touch_keypad.py

```


!!!Success
    Then touch the keycap, the terminal will output the corresponding key.


![](https://github.com/SeeedDocument/Grove-12-Channel-Capacitive-Touch-Keypad-ATtiny1616/raw/master/img/grove-py-result.jpg)



## Resources

- **[ZIP]** [Grove 12 Channel Capacitive Touch Keypad (ATtiny1616) Schematic file](https://github.com/SeeedDocument/Grove-12-Channel-Capacitive-Touch-Keypad-ATtiny1616/raw/master/res/Grove%20-%2012-Channel%20Capacitive%20Touch%20Keypad%20(ATtiny1616).zip)
- **[PDF]** [ATtiny1616 Datasheet](https://github.com/SeeedDocument/Grove-12-Channel-Capacitive-Touch-Keypad-ATtiny1616/raw/master/res/ATtiny1616-1617_Datasheet.pdf)



## Tech Support
Please submit any technical issue into our [forum](http://forum.seeedstudio.com/) or drop mail to techsupport@seeed.cc
