# pico-with-pi-debug-probe-setup
Script to setup the Raspberry Pi Pico + Pi Debug Probe toolchain on Linux systems

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
\
Resources:\
https://www.hashdefineelectronics.com/compiling-and-installing-openocd-with-cmcsis-dap-support \
https://dev.to/admantium/raspberry-pico-simple-debugging-with-just-one-device-4ce7 \
https://raw.githubusercontent.com/raspberrypi/pico-setup/master/pico_setup.sh
