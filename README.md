# Finance Dashboard

A simple html site that displays Google Spreadsheet charts.

## Setup
1. Install Raspbian (full, with desktop) on an SD card, and fire it up in a Pi.
1. Install additional packages:
   ```sh
   apt-get update
   sudo apt-get update
   sudo apt-get install chromium
   sudo apt-get install chromium-browser
   sudo apt-get install x11-xserver-utils unclutter
   ```
1. Replace `.config/lxsession/LXDE-pi/autostart` with `autostart` file from this
   repo.
1. Reboot!

## To gracefully restart the Pi
1. `pkill chromium`
1. `sudo reboot`
