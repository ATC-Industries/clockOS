![ClockOS](https://i.imgur.com/06UVpUX.jpg)

<h3 align="center">ClockOS</h3>
<p align="center">
  A modern LED Clock that is beautiful to own, and beautiful to give. Easily change colors to match your decor.
</p>
<p align="center">
 </a>
  <a href="https://www.kickstarter.com/projects/threetree/clockos-rgb-led-clock-arduino-programable-0">
	<img alt="Funded on Kickstarter" src="https://img.shields.io/badge/Kickstarter-Funded-2bde73.svg">
  </a>
</p>

# Contents

- [Overview](#overview)
- [Configure](#configure)
- [Connecting Clock to Computer](#connecting)
- [Loading New Programs](#loading)

# Overview

The ClockOS software can be programmed using the Arduino Development Software that can be downloaded free from the internet: http://arduino.cc/

# Configure
Once the software is downloaded the following selections are used to set the system up for programming.

The ClockOS board looks like an Arduino PRO (5V 16mhz AT168) board to the software.

# Connecting
A USB to Serial interface (not included with ClockOS) must be used to connect the ClockOS to a USB port on your computer.

FTDI makes a cable with the connector needed that will plug straight into the 6 pin connector located next to the programming buttons on the ClockOS.

Digi-Key is a distributor of these cables. 

Digi-Key part number...............P/N 768-1028-ND

Remove the screws that hold the plate over the buttons on the back of the clock.

Plug the connector from you programming system onto the 6 pin connector (green wire to the left most pin) 

The clock will power up from power on the programming port and does not need the power supply plugged in while programming.

Once the cable is connected, and the Arduino software is configured ( you must select the board and the port that the programming cable is connected to), you are ready to start programming the ClockOS.

The original program can always be reloaded to bring the ClockOS back to factory settings.

# Loading
Before a new program can be uploaded to the ClockOS the Pic microprocessor must be put in standby mode to release the RS 232 lines.

Press all 3 buttons on the ClockOS at the same time. When the PIC processor goes into standby, only 3 blue leds at the 12:00 position will be on. At this time your new software can be uploaded to the ClockOS. After uploading press Button 1 to bring the PIC processor out of standby mode.


---------------------------------------------------------------

ClockOS files from kickstarter project in 2012
[clockOS](https://www.kickstarter.com/projects/threetree/clockos-rgb-led-clock-arduino-programable-0)
kickstarter project.

no Longer Supported

