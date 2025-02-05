# Fixing Trackpads (SSDT-GPI0/XOSI)

* [What this SSDT does](#what-this-ssdt-does)
* [Methods to make this SSDT](#methods-to-make-this-ssdt)

## What this SSDT does

A big part of fixing I2C trackpads is enabling them within ACPI. For VoodooI2C to work, GPI0 needs to be enabled, as well as the Trackpad and I2C bus. The latter two devices are commonly disabled behind an OS check for Windows which need to be patched to work with macOS as well. Often times, GPI0 is already enabled and requires no modification.

This section assumes that macOS is already installed. You may need to use a USB mouse to install macOS if your trackpad does not work yet.

## Methods to make this SSDT

For the trackpad fix, there are 3 methods to choose from:

* [Prebuilt](/Laptops/trackpad-methods/prebuilt.md)
* [SSDTTime](/Laptops/trackpad-methods/ssdttime.md)
* [Manual](/Laptops/trackpad-methods/manual.md)
