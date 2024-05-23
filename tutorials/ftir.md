---
layout: default
---
# Breakerspace FTIR Tutorial

## Sections:

<img src="../assets/img/ftir.JPG" alt="FTIR spectrometer" style="width:40%; float:right; margin-left:10px; margin-bottom:1.4em;">
* [Overview and manuals](#overview)
* [Instrument startup](#startup)
* [Workflow](#workflow)
* [Instrument shut down](#shutdown)
* [Compatible materials](#materials)
* [Sample preparation](#sample-prep)
* [Background collection](#background)
* [Tutorial](#tutorial)
<div style="clear:both;"></div>

### <a name="overview"></a> Overview:

The Nicolet iS5 FTIR Spectrometer Fourier-transform infrared (FTIR) spectrometer provides an infrared spectrum of absorption or transmission of a solid, liquid, or gas, for identification, primarily, of organic or polymeric materials. This tutorial focuses primarily on use of the instrument with an attenuated total reflectance (ATR) accessory, which allows for easy sampling of materials in solid, semi-solid, powder, paste, and liquid forms. 

* [iS5 spectrometer user guide](https://www.dropbox.com/scl/fi/rfba0x3swuhi4affsytv6/2638_iS5-UG.pdf?rlkey=mnjpwg72rbau8dsaw8jwg9flk&dl=0)
* [iD7 ATR User Guide](https://www.dropbox.com/scl/fi/j24msyzbfpqahhk66z5y8/3021_-iD7_UG.pdf?rlkey=xf1sw5yoydqomsmcs1hxhrf5y&dl=0)
* [OMNIC software _Getting Started_ guide](https://www.dropbox.com/scl/fi/nhx1fk2ov5fpkz4og1guf/2640_OMNIC_GS.pdf?rlkey=93wld38wdscvv94o177jylilu&dl=0)
* [Complete set of manufacturer's manuals](https://www.dropbox.com/scl/fo/n0zv4090ncohz1yd53zyp/AEk8_3vo2JuCcHDSDBEEjck?rlkey=haqbguq12kbmh8fi7jmi8wzvg&dl=0)

### <a name="startup"></a> Instrument startup:

* Power on instrument, if needed
* Log on to instrument workstation using your MIT Kerberos
* Start OMNIC software
* Verify instrument connection via system status

<figure>
  <a href="../assets/img/tutorials/ftir/ftir-power.JPG" target="_parent"><img src="../assets/img/tutorials/ftir/ftir-power.JPG" alt="FTIR power." style="width:24%;"></a>
  <a href="../assets/img/tutorials/ftir/ftir-switch.JPG" target="_parent"><img src="../assets/img/tutorials/ftir/ftir-switch.JPG" alt="FTIR switch." style="width:24%;"></a>
  <a href="../assets/img/tutorials/ftir/ftir-desktop.JPG" target="_parent"><img src="../assets/img/tutorials/ftir/ftir-desktop.JPG" alt="OMNIC icon." style="width:24%;"></a>
  <a href="../assets/img/tutorials/ftir/omnic-status.PNG" target="_parent"><img src="../assets/img/tutorials/ftir/omnic-status.PNG" alt="OMNIC status." style="width:24%;"></a>
  <figcaption> Power indicator light, Power switch, OMNIC Icon, Instrument status indicator </figcaption>
</figure>

### <a name="workflow"></a> Typical workflow:

Initially, and periodically as required:
* Remove protective cover from ATR crystal plate
* Clean ATR window
* Collect background (background will need to be refreshed periodically, the interval between background collections is configurable in software options)
* Clean ATR window

For each sample:
* Collect sample
* Clean ATR window
* Save sample spectrum
* Repeat as needed

### <a name="shutdown"></a> Instrument shut down:

* Save all data (each spectrum must be indvidually selected and saved)
* Close OMNIC
* Log off workstation
* Put cover on crystal plate and clamp in place using pressure tower
* Do not switch off (the manufacturer recommends leaving the instrument powered when not in use)

### <a name="materials"></a> Compatible materials:

* Any non-hazardous solid, semi-solid, powder, paste, and liquid materials
* Solvents needed to clean a sample off the instrument must also be non-hazardous 

_**If you have any questions about whether a material is appropriate to characterize in the Breakerspace, please ask before bringing it to the lab.**_

### <a name="sample-prep"></a> Sample preparation and loading:

To maximize signal strength, it is important that the sample is in good contact with the entire ATR window. 

Solid samples should be smooth and free of contaminants on the face to be tested. The self-leveling pressure tip is typically most suitable for a solid sample. Cover the diamond window with the sample, position the pressure tower over the window, and tighten the turn the knob until the clutch slips to provide clamping pressure to the sample. Although many solid samples will not contaminate the window, it is still a good idea to wipe the window with isopropyl alcohol and a Kimwipe between samples.

To sample powders and beads/pellets it is recommend that you switch to the concave pressure tip. It is especially important that powders contact the surface of the diamond window as completely as possible, so it is helpful that they are ground as finely as possible. Plan to run powder samples multiple times to ensure you are getting a good signal. Once power or pellet samples are in place, position the pressure tower over the window, and tighten the turn the knob until the clutch slips, collect sample, and clean the window with isopropyl alcohol and a Kimwipe.

Liquid samples can be run by placing a droplet on the window. Non-volatile liquids can be run uncovered, without the use of the pressure tower. For volatile samples, there is a volatiles cover that can be placed over them to prevent evaporation. The cover should be centered over the sample and clamped down using the pressure tower with the self-leveling foot attached. 

<figure>
  <a href="../assets/img/tutorials/ftir/sample-load.GIF" target="_parent"><img src="../assets/img/tutorials/ftir/sample-load.GIF" alt="Solid sample loading." style="width:32%;"></a>
  <a href="../assets/img/tutorials/ftir/pressure-tip.GIF" target="_parent"><img src="../assets/img/tutorials/ftir/pressure-tip.GIF" alt="Swapping pressure tips." style="width:32%;"></a>
  <a href="../assets/img/tutorials/ftir/volatile-cover.GIF" target="_parent"><img src="../assets/img/tutorials/ftir/volatile-cover.GIF" alt="Volatile cover use." style="width:32%;"></a>
  <figcaption> Loading a solid sample, swapping pressure tips, use of the volatile cover </figcaption>
</figure>

### <a name="feature1"></a> Instrument feature

A key feature of this instrument is eg. focus stacking to create 3d image with height data

GIF embedded using image tag:

![GIF test](../assets/video/raman-display-flip.GIF)

### <a name="tutorial"></a> Tutorial

Take the tutorial sample in drawer and load it in to the instrument. Find feature X and measure the dimensions. Perform operation Y and catalog results. What can be concluded from this data?

Video embedded with video tag, width set to 100%:

<video width="100%" controls>
  <source src="../assets/video/raman-display-flip.MOV" type="video/mp4">
Your browser does not support the video tag.
</video>

