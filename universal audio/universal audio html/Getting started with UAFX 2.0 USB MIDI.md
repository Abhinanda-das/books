---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/43191950601620-Getting-started-with-UAFX-2-0-USB-MIDI.html'
converted_at: 2026-05-31T13:44:59Z
tool: htmlq+pandoc
title: 'Getting started with UAFX 2.0 USB MIDI'
word_count: 1520
---

# Getting started with UAFX 2.0 USB MIDI


All dual-footswitch UAFX pedals are now MIDI-capable over class-compliant USB with a firmware update and <a href="https://www.uaudio.com/pages/download-uafx-pedals" rel="noopener noreferrer" target="_blank"><strong>UAFX Control</strong></a> mobile app update.\
\
UAFX 2.0 allows you to save and recall presets over MIDI program change, control tempo with MIDI Beat Clock, and gives the ability to adjust any control in the pedal using MIDI CC.\*

*\*MIDI CC parameter control is currently available as an open beta.*  \
\
Features vary slightly depending on the pedal capabilities, so be sure to reference [**the charts**](#h_01K9RFMKRA75GXDNNDFSRMSM8Z) below.

**Tip:** For operating instructions, including step-by-step procedures, see the <a href="360058187832-UAFX-Control-Manual.html" rel="noopener noreferrer" target="_blank"><strong>UAFX Control Manual</strong></a>, the <a href="43105954567956-USB-MIDI-with-UAFX-Pedals-Manual.html" rel="noopener noreferrer" target="_blank"><strong>USB MIDI with UAFX Pedals Manual</strong></a>, and the <a href="https://help.uaudio.com/hc/en-us/sections/360012250151" rel="noopener noreferrer" target="_blank"><strong>individual UAFX Manuals</strong></a> for your particular pedal. 

### Equipment Summary

**Important:** To use the new Bluetooth and USB MIDI features, you need both UAFX firmware 2.0 or newer (available in the UA Connect app) and the <a href="https://www.uaudio.com/pages/download-uafx-pedals" rel="noopener noreferrer" target="_blank"><strong>UAFX Control</strong></a> mobile app 3.0 or newer. Get these apps <a href="https://www.uaudio.com/pages/download-uafx-pedals" rel="noopener noreferrer" target="_blank"><strong>here</strong></a>.

1.  <span style="color: #434343;">One or more dual-footswitch UAFX pedals.</span>
2.  <span style="color: #434343;">A 9VDC power supply, capable of delivering 400 mA to each UAFX pedal, and power to your chosen USB host-capable MIDI interface.</span>
3.  <span style="color: #434343;">A </span>[<span style="color: #434343;">**USB Host Capable MIDI interface**</span>](#h_01K9RFMKRHXAEXSV6TS1J62ATJ)<span style="color: #434343;">.</span>
4.  <span style="color: #434343;">Appropriate USB Cabling, see our </span><a href="https://help.uaudio.com/hc/en-us/articles/43206586819092" rel="noopener noreferrer" target="_blank"><span style="color: #434343;"><strong>UAFX Cable & Power Guide</strong></span></a><span style="color: #434343;"> for more information.</span>\
    <span style="color: #434343;">(USB cables, and a hub if you’re controlling more than one pedal)</span>
5.  <span style="color: #434343;">Appropriate audio cabling.</span>\
    <span style="color: #434343;">(your usual TS - Tip Sleeve instrument jacks)</span>
6.  <span style="color: #434343;">An iOS or Android device to run the </span><a href="https://www.uaudio.com/pages/download-uafx-pedals" rel="noopener noreferrer" target="_blank"><strong>UAFX Control</strong></a><span style="color: #434343;"> mobile app, which enables access to MIDI features.</span>
7.  <span style="color: #434343;">A computer with macOS Big Sur or newer, or Windows 10 or newer, to run UA Connect for UAFX firmware updates.</span>

### UAFX MIDI-capable pedals and features:\
![](Getting%20started%20with%20UAFX%202.0%20USB%20MIDI_assets/3ef9db32d9501eaa3038f5f1e9e888187e3cba40.png)

## ![](Getting%20started%20with%20UAFX%202.0%20USB%20MIDI_assets/80e8d5424c752e5edc06b40620c7dec31987643f.png)

### USB host-capable MIDI interfaces

There are many USB Host-capable MIDI interfaces available. Such devices have a USB port on them that is specifically labeled "Host". Devices range from simpler MIDI hubs to controllers with displays, and even those with loop switchers and MIDI control for the ultimate flexibility. \
\
The <a href="https://www.morningstar.io/mc8-pro" rel="noopener noreferrer" target="_blank"><strong>MorningStar MC8 Pro</strong></a> is a popular choice for a USB host-capable MIDI interface, with a built-in USB host port, high-quality displays, footswitches, and an intuitive editor. This allows you to connect up to four UAFX pedals directly to its USB Host port, using a USB hub and USB cables. See our <a href="https://help.uaudio.com/hc/en-us/articles/43206586819092" rel="noopener noreferrer" target="_blank"><strong>UAFX MIDI cable guide</strong></a> for more information.  

A device like this allows you to send multiple MIDI commands with a single button press to as many pedals as you have connected. You can isolate the MIDI sent to individual pedals by setting them to a specific MIDI channel in <a href="https://www.uaudio.com/pages/download-uafx-pedals" rel="noopener noreferrer" target="_blank"><strong>UAFX Control</strong></a>. There are also bypass controls available, so you can activate or deactivate any of the connected pedals with a single button press.\
\
Here is a helpful video that demonstrates how to control UAFX pedals by MIDI:

<figure class="wysiwyg-media">
<div data-oembed-url="https://youtu.be/BUd8WwiLVEo">
<div class="iframe">
<div id="player">

</div>
<div class="player-unavailable">
<h1 id="ein-fehler-ist-aufgetreten." class="message">Ein Fehler ist aufgetreten.</h1>
<div class="submessage">
JavaScript kann nicht ausgeführt werden.
</div>
</div>
</div>
</div>
</figure>

Here’s an example of a typical configuration:\
![](Getting%20started%20with%20UAFX%202.0%20USB%20MIDI_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
 

This setup can be expanded with up to four UAFX pedals, using a simple USB hub. It’s possible to add a MIDI-controllable loop switcher like the <a href="https://www.morningstar.io/ml10x" rel="noopener noreferrer" target="_blank"><strong>MorningStar ML10X</strong></a>, which allows for pedal re-ordering and complex routing possibilities with many pedals.![](Getting%20started%20with%20UAFX%202.0%20USB%20MIDI_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
\
You are only limited by the number of available virtual MIDI ports on your USB MIDI host interface. You can also use more than one USB MIDI host interface for a staggering number of connections.

Here are some additional examples:

![](Getting%20started%20with%20UAFX%202.0%20USB%20MIDI_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

Here is another example with eight UAFX pedals using a <a href="https://www.cme-pro.com/h2midi-pro" rel="noopener noreferrer" target="_blank"><strong>CME H2MIDI Pro</strong></a> as the USB MIDI host interface:

![](Getting%20started%20with%20UAFX%202.0%20USB%20MIDI_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

### Bluetooth MIDI

**UAFX pedals do not feature MIDI over Bluetooth.** 

However, as an example, it is possible to add Wireless Bluetooth by using 3rd-party hardware such as the <a href="https://www.cme-pro.com/product/usb-host-midi-interface/" rel="noopener noreferrer" target="_blank"><strong>CME H4MIDI WC</strong></a> interface with the optional Bluetooth WIDI Core module.\*\
\
An H4MIDI WC can be used with up to eight UAFX pedals connected by USB, and you can then connect a Bluetooth-capable MIDI switcher, such as the <a href="https://www.morningstar.io/mc8-pro" rel="noopener noreferrer" target="_blank"><strong>MorningStar MC8,</strong></a> to the H4MIDI WC wirelessly.\
\
To add Bluetooth MIDI to a single UAFX pedal, the <a href="https://www.cme-pro.com/widi-uhost/" rel="noopener noreferrer" target="_blank"><strong>CME WIDI Uhost</strong></a> adapter would be a good choice.\
\
\****Note:** UA does not directly support third-party hardware, and any questions regarding the named products should be directed to the product manufacturer. UA can assist with any UA product questions.*

### Hardware that has been tested with UAFX 2.0 MIDI

***Note:** MIDI is a universal standard, and any device that can output MIDI can communicate with UAFX, provided you have a suitable USB Host MIDI interface such as the* <a href="https://www.cme-pro.com/h2midi-pro" rel="noopener noreferrer" target="_blank"><em><strong>CME H2MIDI Pro</strong></em></a> *for connecting your UAFX pedals.*

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table-resized" style="border-color: #2F3941;">
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; border-color: #2F3941;"><strong>Brand</strong></td>
<td style="text-align: center; border-color: #2F3941;"><strong>Product</strong></td>
<td style="text-align: center; border-color: #2F3941;"><strong>Type</strong></td>
<td style="text-align: center; border-color: #2F3941;"><strong>Supports USB Host for direct connection to UAFX pedals</strong></td>
<td style="text-align: center; border-color: #2F3941;"><strong>USB Host maximum UAFX pedals with direct connection</strong></td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">Morningstar</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.morningstar.io/mc8-pro" rel="noopener noreferrer" target="_blank"><strong>MC8 Pro</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Footswitch controller with displays</td>
<td style="text-align: center; border-color: #2F3941;">Yes </td>
<td style="text-align: center; border-color: #2F3941;">4</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">Morningstar</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.morningstar.io/mc6-pro" rel="noopener noreferrer" target="_blank"><strong>MC6 Pro</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Footswitch controller with displays</td>
<td style="text-align: center; border-color: #2F3941;">Yes</td>
<td style="text-align: center; border-color: #2F3941;">4</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">Morningstar</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.morningstar.io/mc4-pro" rel="noopener noreferrer" target="_blank"><strong>MC4 Pro</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Footswitch controller with displays</td>
<td style="text-align: center; border-color: #2F3941;">Yes</td>
<td style="text-align: center; border-color: #2F3941;">4</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">CME</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.cme-pro.com/h2midi-pro/" rel="noopener noreferrer" target="_blank"><strong>H2MIDI Pro</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">USB Host MIDI interface</td>
<td style="text-align: center; border-color: #2F3941;">Yes</td>
<td style="text-align: center; border-color: #2F3941;">8</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">CME</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.cme-pro.com/h4midi-wc-usb-host-midi-interface/" rel="noopener noreferrer" target="_blank"><strong>H4MIDI WC</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">USB Host and MIDI interface with optional WIDI Bluetooth module</td>
<td style="text-align: center; border-color: #2F3941;">Yes</td>
<td style="text-align: center; border-color: #2F3941;">8</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">Heavy Procrastination Industries</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://mortrix.io/" rel="noopener noreferrer" target="_blank"><strong>Mortrix</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Footswitch controller with touchscreen display</td>
<td style="text-align: center; border-color: #2F3941;">Yes</td>
<td style="text-align: center; border-color: #2F3941;">32</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">GigRig</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://shop.thegigrig.com/collections/g3-switching-system/products/g3s" rel="noopener noreferrer" target="_blank"><strong>G3S</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Loopswitcher with MIDI & footswitches</td>
<td style="text-align: center; border-color: #2F3941;">No</td>
<td style="text-align: center; border-color: #2F3941;">Requires USB Host MIDI Interface</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">GigRig</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://shop.thegigrig.com/products/g3s-atom" rel="noopener noreferrer" target="_blank"><strong>G3S Atom</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Loopswitcher with MIDI & footswitches</td>
<td style="text-align: center; border-color: #2F3941;">No</td>
<td style="text-align: center; border-color: #2F3941;">Requires USB Host MIDI Interface</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">Disaster Area</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.disasterareadesigns.com/shop/p/dmc-micro-gen4" rel="noopener noreferrer" target="_blank"><strong>DMC.micro Gen4</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Compact dual footswitch USB MIDI Host</td>
<td style="text-align: center; border-color: #2F3941;">Yes</td>
<td style="text-align: center; border-color: #2F3941;">4</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">Jet Pedals</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://jetpedals.com/products/unity6" rel="noopener noreferrer" target="_blank"><strong>Unity 6</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">MIDI controller with touchscreen and built in loop switcher.</td>
<td style="text-align: center; border-color: #2F3941;">No</td>
<td style="text-align: center; border-color: #2F3941;">Requires USB Host MIDI Interface</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">RJM Mastermind</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.rjmmusic.com/mastermind-pbc-6x/" rel="noopener noreferrer" target="_blank"><strong>PBC/6X</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Loopswitcher with MIDI control and programmable footswitches</td>
<td style="text-align: center; border-color: #2F3941;">No</td>
<td style="text-align: center; border-color: #2F3941;">Requires USB Host MIDI Interface</td>
</tr>
<tr>
<td style="text-align: center; border-color: #2F3941;">RJM Mastermind</td>
<td style="text-align: center; border-color: #2F3941;"><a href="https://www.rjmmusic.com/mastermind-pbc-2/" rel="noopener noreferrer" target="_blank"><strong>PBC/10</strong></a></td>
<td style="text-align: center; border-color: #2F3941;">Loopswitcher with MIDI control and programmable footswitches</td>
<td style="text-align: center; border-color: #2F3941;">No</td>
<td style="text-align: center; border-color: #2F3941;">Requires USB Host MIDI Interface</td>
</tr>
</tbody>
</table>
</figure>

### YouTube examples of UAFX Pedalboard configurations:

<figure class="wysiwyg-media">
<div data-oembed-url="https://www.youtube.com/watch?v=N7KrX1cAZ_w">
<div class="iframe">
<div id="player">

</div>
<div class="player-unavailable">
<h1 id="ein-fehler-ist-aufgetreten." class="message">Ein Fehler ist aufgetreten.</h1>
<div class="submessage">
JavaScript kann nicht ausgeführt werden.
</div>
</div>
</div>
</div>
</figure>

<figure class="wysiwyg-media">
<div data-oembed-url="https://www.youtube.com/watch?v=L3ynG3134Oo">
<div class="iframe">
<div id="player">

</div>
<div class="player-unavailable">
<h1 id="ein-fehler-ist-aufgetreten." class="message">Ein Fehler ist aufgetreten.</h1>
<div class="submessage">
JavaScript kann nicht ausgeführt werden.
</div>
</div>
</div>
</div>
</figure>

<figure class="wysiwyg-media">
<div data-oembed-url="https://youtu.be/4EfaTxSwT8g?si=bCM9fsoK7pFrQyze">
<div class="iframe">
<div id="player">

</div>
<div class="player-unavailable">
<h1 id="ein-fehler-ist-aufgetreten." class="message">Ein Fehler ist aufgetreten.</h1>
<div class="submessage">
JavaScript kann nicht ausgeführt werden.
</div>
</div>
</div>
</div>
</figure>

</div>

