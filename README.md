# How to play Singstar on your Computer:

This documentation is complemenatary to and based on [this thread](https://www.reddit.com/r/PCSX2/comments/40ryt9/how_to_play_singstar_on_pcsx2/).
I found some things hard to figure out, so I decided to make a more detailed tutorial. 
Credits go to the original author.

# Prerequisites
1) Download and install the [PS2 Emulator PCSX2](https://pcsx2.net/)
2) Download/clone [USBqemu-wheel](https://github.com/jackun/USBqemu-wheel)
3) Get the bios files from your original PS2, as described [here](https://pcsx2.net/docs/usage/setup/#how-to-dump-your-ps2-bios). 
4) Make ISO of one of your SingStar PS2 discs to PC, as described [here](https://pcsx2.net/docs/usage/setup/#dumping-ps2-discs-via-imgburn). 

Note, that downloading the bios files or ISOs from the Internet might break copyright laws!

# Setup
## Initialize
1) Copy path/to/USBqemu-wheel/dist/USBqemu-wheel.dll to path/to/PCSX2/Plugins
2) Copy the PS2-Bios files to path/to/PCSX2/bios
3) Start the Emulator (run pcsx2.exe)
4) Select the BIOS-File during the initial setup


## Emulator-Setings
1) Make sure your Singstar-Mics are connected 
2) Open Config -> Plugins/BIOS Selector
3) Select *Qemu USB Driver (Wheel)* in Plugins -> USB and hit Configure...
4) In Device type, Port 1 select *Singstar* (leave Port 2 None)
5) In Device API, Port 1 select *WASAPI*, hit Configure
6) Select Player 1 and Player 2 identical to *Microphone (USBMIC Serial#...)*


## Enable 2 channels of the Microphone:
1) In Windows open your Control Panel
2) Go to Hardware and Sound -> Sound -> Recording
3) Find the *USBMIC Serial#...* and open its Properties
4) Go to Advanced and change the Default Format to (any) 2 channel setting

# Playing Singstar
1) In the emulator, Hit System -> Boot ISO (fast)
2) Select your Singstar ISO
3) Hit F9 to deal with Graphics issues
4) Enjoy
