# Flex PCB Ethernet Window Passthrough

![Main flex photo](photos/img.jpg)

## Overview

If you ever tried buying an off-the-shelf window passthrough flex like this one, you probably were disappointed because it only paired at 100Mbps.
This project aims to fix that issue and provide you with glorious gigabit ethernet speed - inside *and* outside.
It was mainly designed to fit in windows, but it works with linux and macos too.
You can also use it in any other tight spaces ([H.Y.C.Y.BH.?](https://www.youtube.com/watch?v=--9kqhzQ-8Q)),
or as the world's weirdest Ethernet barrel. We won't judge. 

## Building

0. Make sure your house includes windows - it would be a shame to have nowhere to install this puppy.
1. Order the [Gerber files](production/gigabit-window-flex.zip) from [JLCPCB](https://jlcpcb.com/)
   or your favorite PCB manufacturer. Use the default 0.11mm flex stackup.
2. Solder two RJ45 connectors. The pinout is very generic and most connectors will fit - like
   [this high-tech marvel of engineering](https://www.tme.eu/pl/details/rj45g/zlacza-rj/connfly/ds1134-05-s80bx/).
   Any connector should do - even something you found in the parts drawer or on some old board.
   Just make sure it's a plain connector, without any magnetics.

## Technical details

- Length: Flexible part is 265mm, but if you want you can customize it.
- Source: PCB was designed in KiCad.
- Length matching: yes (I was bored).
- Impedance matching: believe ut or not - but yes!

![impedance matching calculations](impedance.png)

## TODO

- Design a 3D printed enclosure for the connectors so they're more robust.

## Credits

- Idea: [hbrylkowski](https://github.com/hbrylkowski)
- Design: [kosma](https://github.com/kosma)
- Paying to get the shit built: [hbrylkowski](https://github.com/hbrylkowski)

## Images

![traces near plug closeup phot](photos/img_1.jpg)

![possible application photo](photos/img_2.jpg)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.
