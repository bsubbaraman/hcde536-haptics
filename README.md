# Haptic Interactions & Hardware Prototyping

This document provides brief supplementary notes on the Hapticlabs [getting started](https://docs.hapticlabs.io/guides/getting-started/) and [mobile devices](https://docs.hapticlabs.io/mobile/) guides. If anything here conflicts with the official Hapticlabs docs, follow the official docs.

### Getting started guide notes:
- follow the getting started guide: https://docs.hapticlabs.io/guides/getting-started/
- you'll start by connecting the 'Satellite' unit to your laptop using the provided usb-c cable. you may have to update the firmware on first connection.
- the ERM and LRA look pretty similar; the ERM has a larger diameter, and the LRA is thicker
- when you connect an actuator, you select the matching actuator in the Satellite menu in the bottom right-hand pane https://docs.hapticlabs.io/settingspanel/actuator-output/
- there are few block types, including [vibration](https://docs.hapticlabs.io/settingspanel/vibration/) (green), [pulse](https://docs.hapticlabs.io/settingspanel/pulse/) (blue), and pause (red). check those links for a bit more info on how to manipulate the frequency/intensity for the former two; pause is just a duration.
- you can assign tracks to individual channels or to both https://docs.hapticlabs.io/settingspanel/track-settings/
- you can trigger tracks using the 'Set Trigger' button under 'Output Device Settings' on the right-hand pane https://docs.hapticlabs.io/settingspanel/externaltrigger/
- the satellite has two general purpose input/output (GPIO) pins. pin 1 is hardwired to the touch sensor on top of the Satellite, so you always have 1 pin available without plugging anything in. you can connect the touch and push buttons to the I/O port, which can also drive pin 1 and/or 2; the push buttons are labelled 1 and 2, and the touch button has two small toggle switches to select which pin it listens to.


### Haptics for mobile devices
- the mobile devices guide is pretty comprehensive here: https://docs.hapticlabs.io/mobile/ + https://docs.hapticlabs.io/mobile/apple/

