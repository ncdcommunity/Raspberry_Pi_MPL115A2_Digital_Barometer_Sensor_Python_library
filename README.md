[![ MPL115A2](MPL115A2_I2C.png)](https://store.ncd.io/product/mpl115a2-digital-barometer-50-to-115-kpa-i2c-mini-module/).

#  MPL115A2

Freescale’s MPL115A2 employs a MEMS pressure sensor with an I2C interface to provide accurate Pressure/Altitude and Temperature data.The sensor outputs are digitized by a high resolution 24-bit ADC. It is capable of detecting a change in only 0.05 kPa which equates to a 0.3m change in altitude.
This Device is available from www.ncd.io 

[SKU: MPL115A2]

(https://store.ncd.io/product/mpl115a2-digital-barometer-50-to-115-kpa-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MPL115A2 digital barometer sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mpl115a2-digital-barometer-50-to-115-kpa-i2c-mini-module/">MPL115A2 digital barometer sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MPL115A2.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
