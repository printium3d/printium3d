# Printium3D

## Simple 3D printing to USB
Printium3D is a simple and easy to use printing app that enables you to 3D print locally using USB cable.

## Features
- Prints directly via USB cable, no need for network/Wifi/OctoPrint/Repetier/etc.
- Simple and easy to use.
- Detailed logs and control of serial communication and USB port.

## Do I need it ?
If you want to print 3D prints via USB cable, without Wifi/OctoPrint/Repetier,
and you're disappointed with USB support and performance (or lack of) in existing apps,
then you should give this app a try.

## How to use
1. In your slicer (CURA, Slic3r, etc), export/save G-code as file
2. Open the G-code file in Printium3D, and print, that's simple.

## FAQ
* Q: Is it a slicer ?
 A: No, Printium3D only prints the G-code, via USB cable to your printer.
* Q: Why not use WiFi or network with my printer ?
 A: Not all printers support network or WiFi, and some prefer to use USB for local printers.
* Q: Does it save me from buying Raspberry Pi, and installing OctoPrint ?
 A: Yes.

## Why not use CURA for printing via USB ?

CURA stopped (un-officially?) supporting printing via USB cable, and bugs are not fixed anymore.
see comment here:
*"We do not give USB printing any priority since none of Ultimaker's printers support USB printing. It is a bug, but
don't expect it to be fixed any time soon. Sorry!"*
(src = https://github.com/Ultimaker/Cura/issues/10573 )

CURA now has many issues with with SUB printing, which makes it impossible to work with:
* Printers are not detected when connected via USB cable.
* No recovery when there's an error in USB communication.
* All operations of USB are implicit and the user doesn't know what is the status of USB connection.
* Lack of warning/error messages.

## Is it free ?
Yes.

## Installation
Printium3D comes as a "portable app", in a zip file.
Just download the zip file, and extract to any folder you wish.

## Download
https://github.com/printium3d/printium3d/release
