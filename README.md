# pico-with-pi-debug-probe-setup
Script to setup the Raspberry Pi Pico + Pi Debug Probe toolchain on Linux systems

Prerequisites:
- Raspberry Pi Pico H
- Raspberry Pi Debug Probe
- computer with Ubuntu
- git 

To set up your Pi Pico + Pi Debug Probe toolchain on Linux download the script from this repository, set it as executable and run it:
```
wget https://raw.githubusercontent.com/LucasOpoka/pico-with-pi-debug-probe-setup/main/pico-with-pi-debug-probe-setup.sh
```
```
chmod +x pico-with-pi-debug-probe-setup.sh
```
```
. ./pico-with-pi-debug-probe-setup.sh
```
\
After the script executed navigate to your blinky directory and run the following to open the test project in VSCode:
```
code .
```
Once the CMake extansion for VSCode asks you if you want to configure the project click yes. When asked which kit to use choose GCC for arm-non-eabi.\
Afterwards power the Pico and connect the Pi Debug Probe to it through the SWD port. Then connect the Pi Debug Probe via USB to your computer. Next, click on the Run and Debug button in the right pane of VSCode and then on the green arrow in that menu to run the blinky project on the Pi Pico with debugging.
\
Resources:\
https://www.hashdefineelectronics.com/compiling-and-installing-openocd-with-cmcsis-dap-support \
https://dev.to/admantium/raspberry-pico-simple-debugging-with-just-one-device-4ce7 \
https://raw.githubusercontent.com/raspberrypi/pico-setup/master/pico_setup.sh
