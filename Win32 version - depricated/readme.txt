This is a very daft implementation of an OBD logger.

Using the ISO-9141 OBD-II protocol and a VAG COM cable
(VAG COM cable, KKL 409.1, having the FT232RL chip by FTDI)

This program was written in order to interface with
a 2005 lotus elise (with the T4 ECU). The lower OBD
modes and PIDs may also work with other cars, though.

Within the program there are some simple controls including
a check list of loggable parameters. The check box
can be switched between 'do not log', 'log' or 
'log and plot'. Some parameters cannot be plotted, though.

The program is a work in progress.

This program uses the windows API and the FTDI API
Download the FTDI drivers at:
http://www.ftdichip.com/Drivers/D2XX.htm

In order to use the pre-compiled version of Daft OBD
download the following files and place them in the same folder
on your computer:

DaftOBD.exe
libgcc_s_dw2-1.dll
libstdc++-6.dll

also download the FTDI drivers as a setup executable, unzip and
install them. This should enable the OBD program to work.