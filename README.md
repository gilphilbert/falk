# FALK

## Background
This repo (and the linked ones) feature a set of open-source DIY audio projects. They're all designed to be approachable and easy to build for even the newest to electronics and DIY audio. Don't be scared by what you might see - the modular nature of the builds allows you to build and test each component separatately! I've had a lot of fun building these and I've gone through lots of revisions (and money) so you don't have to!

## Devices
* PA-01 Modular Preamplifier
* DP-01 Digital Player
* [Hypnic Power Manager](#hypnic)

### [PA-01 Modular Preamplifier](tree/main/pa-01)
The PA-01 is designed as a fully-passive modular preamplifier. The result is a set of independent modules that can be used to build a preamplifier. You can also swap out parts for other off-the-shelf or DIY components from others, even going as far as to add buffers and more. It's designed around the ESP32 MCU which prrovides a full digital display, customized inputs (enable/disable/name) and WiFi support with a web-based UI.

### DP-01 Digital Player
The DP-01 is a Raspberry Pi-based audio streamer. While it's (currently) based on MPD like many other projects, DP-01 is designed for high quality audio so it doesn't support features that may degrade audio quality (software volume control, etc.). The UI matches the other FALK projects and it supports a number of different sized LCD screens, including the 8.8" 1920x480 TFTs from Wisecoco to allow yout to create distinctive builds.

### [Hypnic Power Manager](tree/main/hypnic)<a name="hypnic"></a>
The Hypnic Power Manager is a power manager board for single board computers (including, but not limited to the Raspberry Pi) that's designed to provide power control (via a power switch), power state LED connections and enough power to allow the SBC to gracefully shutdown in the event of external power loss, to prevent corruption of the SD card.
