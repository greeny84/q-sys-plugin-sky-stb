# Sky STB Plugin

Plugin set for Sky TV STB devices. 

Developed against a SkyHD box, composed of two parts.

## Control

Using a [Dusky Control unit](https://www.dusky-control.com/), which is an RS232 device, to inject IR commands via the RF2 connector.

### Features

- Control of STB using Remote button emulation

## Feedback

Via the native RS232 port (originally used for a Sky Gnome)

### Features

- Channel Entry Feedback
- Channel Number
- Channel Name
- Program Name
- Program Description

**Note:** As this port is one way only, there is no way to poll for repsonses. Under normal operation a message should be returned once per minute. If no values are present on first load, you may simply need to wait.

## Communication

These plugins use IP to connect. In order to connect to RS232 they need to run throught an RS232<->IP device such a [Brainboxes ES-457](http://www.brainboxes.com/product/es-457/2-port-rs232-poe-ethernet-to-serial-adapter).
