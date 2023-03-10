# SZ Pocket Color PCB
Introducing the SZ Pocket Color or SZ-POCO, this PCB transforms a Game Boy Color into the form-factor of a Game Boy Pocket.

![](images/sz-poco_complete.jpeg)

# Features

- 4-Layer Board with GND and PWR Planes
- Conveniently-placed solder pads for aftermarket IPS screen kit controls
- IR blasters placed in a useable position
- Option for tactile buttons on the directional pad, A/B, and start/select buttons (picture below is of an older revision)

![](images/pcb_front.JPEG)
![](images/pcb_back.JPEG)

# Disclaimer
You will need to transfer components from a working Game Boy Color for this PCB to work.  Please do not attempt this project if you are inexperienced in soldering; populating this PCB will require desoldering and micro-soldering surface mount components.  You will also need to be able to read/understand the CGB schematics and be able to self-troubleshoot any issues.  I do not take responsibility or accept blame for any damage to your Game Boy Color or for any failed attempts. 

**Note**: There are multiple revisions of the OEM CGB PCBs (CPU-01 through CPU-06).  CGB-CPU revisions 01-05 have slight differences in passive components,  but they *should* be compatible with this PCB.  **CGB-CPU revision 06 is incompatible and cannot be used with this PCB.**  

I have personally tested this PCB and successfully created a working SZ Pocket Color using components from an OEM **CGB-CPU-04**. All features have been confirmed as working with the unit that I have created. ***However, I cannot guarantee a fully working unit if you undertake this project as there are too many factors that can cause issues, so please acknowledge this disclaimer and order/use this PCB at your own risk. Unless it is a PCB design issue, I will be providing limited technical support for any issues you may have.***

# Ordering

This PCB will only be made available through my Etsy and/or Ko-fi shop; gerbers/source files will not be released.  

https://ko-fi.com/skimzor

If you have suggestions to improve or identify issues with the PCB design, please contact me on discord: *skimzor#5078*.

# Bill of Materials & Assembly

As mentioned above in the disclaimer, assembly of this PCB requires advance soldering experience and ability to self-troubleshoot any issues.

Since this PCB uses the original CGB schematics, you are able to directly transplant components from a donor console to create a working SZ Pocket Color.  Components can also be ordered through an electronic components distributor (e.g. digikey, mouser, etc.) and can be found in the Bill of Materials (BOM) unless otherwise noted as required from the donor CGB (e.g. CGB CPU, Crystal, etc.). 

**Note:** Component transfer from a donor Game Boy Color to the SZ-POCO PCB is one to one (e.g. C1 from the donor PCB goes to C1 on SZ-POCO, R3 from the donor PCB goes to R2 on SZ-POCO, etc). Please verify orientation/polarity of components before soldering.

# Additional Parts

In addition to the donor Game Boy Color, you will need the following items to make a functional handheld SZ Pocket Color

- **Game Boy Color IPS Kit:**
- **Game Boy Pocket Shell:** It is recommended to get the Funnyplyaing IPS-Ready Game Boy Pocket shell so that you do not have to 
- **Game Boy Pocket Buttons:**
- **Game Boy Pocket Membranes:**
- **Game Boy Pocket Lens:**
- **Game Boy Pocket Battery Contacts:**



# License

 [![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
 
This project/PCB is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. ***Under this license, you are not permitted to profit from or commercialize this project.***
