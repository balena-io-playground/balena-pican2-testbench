# resin-pican2-testbench

A test application for the PiCAN2-duo HAT. The 2 CAN buses are connected to each other, so that we can perform automated tests on a single device.

### Installation

You need to set the following parameters in your config.txt:

```
dtoverlay=mcp2515-can0,oscillator=16000000,interrupt=25
dtoverlay=mcp2515-can1,oscillator=16000000,interrupt=24
dtoverlay=spi-bcm2835-overlay
```
