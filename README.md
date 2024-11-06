
This project is built using cmake. It has the following dependencies:

- libgtkmm-3.0-dev
- libgtk-3-dev


Its core job is to provide a GUI on a beaglebone-black. It has two modes:
1. daytime mode - which offers a GUI for displaying information from various plug-ins
2. nighttime mode - a completely red screen meant to be used as a night light

It's intended to be modular so that various plug-ins can be used to pull different data