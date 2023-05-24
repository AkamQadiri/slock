# Personalized Slock Fork

This repository contains a personalized fork of Slock, a simple X display locker, with patches applied to enhance its functionality and appearance.

Feel free to explore and adapt this customized Slock fork to suit your own preferences and requirements.

## Applied Patches

- `capscolor`: Changes the color of the unlock indicator when Caps Lock is active.
- `xresources`: Allows Slock to read color settings from the X resources database (xrdb).
- `dpms`: Adds DPMS (Display Power Management Signaling) support to Slock, allowing the screen to be turned off after a period of inactivity.

## Installation

1. Clone the repository to your local machine.
   ```shell
   git clone https://github.com/AkamQadiri/slock
   ```

2. Compile and install Slock by running the following command within the cloned repository:
   ```shell
   sudo make clean install
   ```
