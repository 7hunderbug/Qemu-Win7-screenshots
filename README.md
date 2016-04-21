# Qemu-Win7-screenshots
Screenshots of Windows 7 guest

Reference: git commit https://github.com/qemu/qemu/commit/5f77e06baa84323e5bbc96c2c7f4fe627078b210
USB device affected: Xbox 360 Wireless Receiver for Windows (and parent ICH9 UHCI -2934)

These images show difference between running a Windows 7 guest on Qemu git master with the commit and then without the commit:

w7-devman1.png - with the commit (and bug) shows device manager just after inserting device to running VM.
w7-devman2.png - with the commit (and bug) shows device manager ~30-50  seconds after inserting the device.
w7-devman3.png - without the commit (wihtout bug) shows device manager with device attached and working as expected.

