---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/32321175366676-Apollo-e1x-Remote-Controllable-Unison-Preamp-Manual.html'
converted_at: 2026-05-31T13:44:51Z
tool: htmlq+pandoc
title: 'Apollo e1x Remote-Controllable Unison Preamp Manual'
word_count: 5368
---

# Apollo e1x Remote-Controllable Unison Preamp Manual


<figure class="wysiwyg-image">
![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/4cdc530b8625a9f7c327cc6d69c13b669d140c9b.png)
</figure>

<figure class="wysiwyg-image">
![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/aefe7ab35b38060e4369a08d3cf2cf4cc359277c.png)
</figure>

## Put Unison preamps on stage or in your studio with Dante

Apollo e1x lets you add remote-controllable Unison mic/line preamps to your Apollo x16D interface, putting legendary preamp sounds from API, Neve, Manley, SSL, and more on stage, at front-of-house, or in your multi-room studio using Dante® networked audio. 

Apollo e1x can be used as a remote-controllable mic/line preamp over any Dante network without an Apollo x16D interface, ideal for expanding your inputs — from additional stage rack connections to front-of-house measurement mics to a tamper-proof lectern preamp — no matter what Dante-enabled device you use.

## Key Benefits

- Expand any Dante network with remote-controlled mic/line preamps using Power over Ethernet (PoE)
- Combine with Apollo x16D interface to get the authentic Unison™ mic preamp sounds of API, Avalon, Manley, Neve, SSL, and more
- Link multiple Apollo e1x units with included coupling bracket and integrated mic‑stand mount
- Pair with Apollo e2m stereo headphone amplifier / line interface and Apollo x16D for a complete I/O solution

------------------------------------------------------------------------

## In this article

- [System Requirements](#h_01JVMMNHQVMR7WGWCYG5KNM7SB)
- [Installing Software and Registering your Hardware](#h_01JVMMNHQVX6R2M878V90JZAEV)
- [Apollo e1x Quick Start](#h_01JVMMNHQV1GMEK3661D7NS3QD)
- [Apollo e1x Features](#h_01JVMMNHQV13V03NT01PK65WW8)
- [Configuring Apollo e1x](#h_01JVMMNHQWND3WTHJSGZPM12HJ)
- [Using Apollo e1x with Apollo x16D and UAD Console](#h_01JVMMNHQWRYCWJT750M4TWCMB)
- [Network Settings](#h_01JVMMNHQXSF8XKBMBGZYWGMZB)
- [Apollo e1x Deployment Scenarios](#h_01JVMMNHQXQJ741J4V8GCJQPZK)
- [Specifications](#h_01JVMMNHQXA83ECQ0A4DWRH62W)
- [Notices](#h_01JVMMNHQX1KXA2YGBQB84SDZ7)

------------------------------------------------------------------------

# System Requirements

- Network switch with PoE (Power over Ethernet) capability, or a PoE injector
- Audio source connected with XLR or ¼" plug
- UAD Software v11.7 or newer
- UAD Console software v1.2.3 or newer
- Dante Controller software
- For UAD Unison plug-in integration, an Apollo x16D is required

------------------------------------------------------------------------

# Installing Software and Registering your Hardware

Apollo e1x uses [UAD Console](../sections/25052396869908.html) to control preamp settings. In addition, with Apollo x16D, you can use a UAD [Unison preamp plug-in](26485044036756-Unison.html) and Preamp Auto-Gain on each Apollo e1x preamp. See [this article](30921736610836-Preamp-Auto-Gain.html) for Preamp Auto-Gain considerations. 

If you have an Apollo x16D or another Apollo device, you have likely already installed UAD Software and UAD Console. If you do not have an Apollo x16D or another Apollo device, you must install UAD Software and UAD Console.

#### Install UAD Software and UAD Console

1.  [Download, install, and launch UA Connect](https://www.uaudio.com/downloads/ua-connect/). 
2.  Log in to UA Connect with your UA account credentials. If you do not have a UA account, you can create one in this step. 
3.  After logging in, click the Apollo & UAD-2 tab (under the Apollo item) to see the Apollo & UAD-2 page. 
4.  Click Download on the UAD Software Installer item to download and install UAD software. 
5.  Follow the instructions provided by the installer ([more information is available here](https://help.uaudio.com/hc/en-us/articles/360059792932-UAD-Installation-Registration-Authorization)). 

When installation is complete, UAD software and UAD Console are ready for use. 

#### Install Dante Controller software

1.  Go [here](https://www.getdante.com/products/software-essentials/dante-controller/) and click the Free Download button to download Dante Controller software.
2.  Launch the Dante installer and follow the instructions to install Dante Controller software. 

#### Register your hardware with UA Connect

1.  Open UA Connect. 
2.  Click the Apollo E Series tab (under the Apollo item). 
3.  Click Add Apollo Hardware. 
4.  On the Set Up Your Hardware screen, choose the network port your Apollo E Series device is connected to, then click Scan For Devices.
5.  When your Apollo E Series device or devices are detected, select the device to register and click Add Device.\
    **Tip:** Click Identify next to a device to flash the power LED on the device.
6.  On the next screen, click Register. 
7.  After the Apollo is registered, click Finish. 

#### Updating Apollo E Series firmware

After you register Apollo E Series hardware, the devices appear on the Apollo E Series screen in UA Connect. When a firmware update is available, the Update badge appears on the Apollo device. You can update firmware from UA Connect. 

1.  Open UA Connect. 
2.  Click the Apollo E Series tab (under the Apollo item). 
3.  Select an Apollo E Series device. 
4.  In the Firmware area, click Update, and follow the instructions to complete the firmware update.

------------------------------------------------------------------------

# Apollo e1x Quick Start

Use these instructions to quicky get started with Apollo e1x. 

## Make connections

1.  Place Apollo e1x in a suitable location, such as on a tabletop. Alternatively, you can mount Apollo e1x on a standard mic stand or clamp adaptor using the integrated ⅝" threaded socket on the bottom of the device. 
2.  Connect Apollo e1x to your Dante network.
3.  Connect your XLR or ¼" audio plug to the combo jack on Apollo e1x. 

UAD Console selects the mic or line input according to the cable that is connected. 48V phantom power and the pad settings are unavailable when using the ¼" TRS input. See [Configuring Apollo e1x](#h_01JVMMNHQWND3WTHJSGZPM12HJ) for detailed connection and setting information.

<figure class="wysiwyg-table" style="width: 50%;">
<table style="border-collapse: collapse;">
<tbody>
<tr>
<td style="width: 50%">![Apollo_e1x_Front_Mic_Input.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/f2c7a21a15dd3a185e74e848c7c3bc96ed3c3896.png)</td>
<td style="width: 50%">![Apollo_e1x_Rear_Dante_Input.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/a3aada8a970c6b3d7dd8add34ca273e17ba093a7.png)</td>
</tr>
</tbody>
</table>
</figure>

 

<figure class="wysiwyg-image">
![apollo_e1x_bottom.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/05aaee12443bd4ff506c3b3071dfee5775d7ed47.png)
</figure>

------------------------------------------------------------------------

# Apollo e1x Features

## UAD Unison plug-ins with Apollo x16D

When Apollo e1x is routed to Apollo x16D, [Unison™ plug-in capabilities are unlocked](26485044036756-Unison.html). Unison is a unique UAD plug-in technology for Apollo hardware that reconfigures Apollo's preamps to precisely emulate the sound and behavior of classic analog gear, including impedance matching and gain staging.

## Dante/AES67 compatibility

Apollo e1x can be used for analog audio input into Dante or AES67 audio networks.

**Note:** AES67 format is configured in Dante Controller, and only available at 48 kHz sample rate. 

## XLR/TRS combo input features

Connect an analog audio source to the XLR / TRS combo jack. Apollo e1x automatically calibrates as a mic or line input according to the connected source. Apollo e1x defaults to the XLR (mic) input, and switches to the line input when a ¼" plug is detected. Apollo e1x inputs include the following options and features.

- Adjustable gain (10 – 65 dB, variable with Unison plug-ins)
- Switchable high pass filter (variable with Unison plug-ins)
- Polarity invert
- 48V phantom power (XLR only)
- -20 dB input pad (XLR only, variable with Unison plug-ins)
- Default 5.4K mic impedance (variable with Unison plug-ins) 

## Ethernet connection

Connect Apollo e1x to your Dante network with a Cat5e or Cat6 Ethernet cable. A Dante network requires a Dante-capable network switch and other connected Dante devices, which combine to form a functioning audio routing system. To power Apollo e1x, your Dante network switch must provide PoE (Power over Ethernet), or power must be provided by a PoE injector. 

For network and cabling information, see [this article](https://help.uaudio.com/hc/en-us/articles/28521194236564-Apollo-x16D-Apollo-e1x-and-e2m-Dante-Network-Switch-Cable-Information). 

## Power and Connectivity Indicators (LEDs)

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/a2db88170d54723e11c25204df2db3adfb344f04.png)

The power and connectivity indicators show the status of the device and signals.

- **PoE (Blue)**: Solid = Powered, Flashing = ID mode
- **48V (Red)**: **Illuminated** = Phantom engaged (XLR input only) 
  - **Note:** Always disable before connecting or disconnecting XLR plug
- **LED Indicator:** SIG (RGB) \| **Status:** Green, amber, or red to indicate signal level
  - **Note:** Adjust levels with UAD Console gain control and input PAD

The right level indicator illuminates when signal is present at the analog input. The LED color indicates the input signal level:

- **-Inf to -53 dBFS:** OFF

- **-52 dBFS:** Dim green

- **-26 dBFS:** Solid green

- **-3 dBFS:** Amber

- **-0.3 dBFS:** Red

## Placement

- **Tabletop –** Place on a tabletop or another flat surface, using the included rubber feet
- **Mic stand –** Mount on a standard mic stand or clamp adaptor using the ⅝" threaded socket on the bottom of the device

### Combining multiple Apollo e1x hardware units

Multiple units can be attached together using the included bracket. Remove the two bottom 2 mm hex screws on each unit to be affixed, add the bracket, and then reassemble as illustrated. To prevent overheating, a maximum of eight (8) Apollo e1x units can be attached together.

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/45a1451d1fe5b68ac09f21468806e6694276036e.png)

------------------------------------------------------------------------

# Configuring Apollo e1x

## Routing with Dante Controller

Apollo e1x is a single-channel, two flow Tx (Transmitter) device. In Dante Controller you can route the audio from Apollo e1x to up to two Rx (Receiver) channels. See [Routing View](https://dev.audinate.com/GA/dante-controller/userguide/webhelp/content/routing_view.htm) in the Dante Controller User Guide for more information. 

**Tip:** We recommend that the **Use shared Dante interface** option is selected in the Configure Dante Interfaces dialog. You can open this dialog by choosing File \> Interfaces from the Dante Controller application menus. This helps to ensure that all applications are connected to the same Dante network.

In Dante Controller, Apollo e1x is identified by its Dante device name. 

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/6c1c8ca19f4f5ab344de7aee61183df378085ca1.png)

## Routing and configuration in UAD Console with an Apollo x16D

Within UAD Console you can route audio from an available Dante transmitter to an Apollo x16D Dante channel. This creates the routing in Dante Controller software. Additionally, when an Apollo e1x is routed to an Apollo x16D input, you can add a UAD Unison plug-in to the channel. 

**Note:** To use Apollo e1x preamp features with Apollo x16D, both devices need to be on the same Dante network as the UAD Console computer.

If you are not using an Apollo x16D, you can use UAD Console to configure preamp settings. See [Apollo E window in UAD Console (Apollo e1x without an Apollo x16D)](#h_01JVMMNHQW4VFXXDY980TRVZ0M).

### Routing Apollo e1x to a Dante channel on Apollo x16D

1.  In UAD Console, click the Dante Source box in the input row of an Apollo x16D Dante channel.
2.  The Input Source browser opens. Choose the input source. 

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/3f3f358bcd9316d1b5b3e04f8ce6a5bf71c8dbec.png)

**Tip:** Apollo E Series and Apollo x16D devices appear in the Input Browser with their Dante device and channel names. You can change device and channel names on the [Device Config tab in Dante Controller](https://dev.audinate.com/GA/dante-controller/userguide/webhelp/content/device_config_tab.htm) to more easily identify Dante devices. 

## The apollo \| e window in UAD Console (Apollo e1x without an Apollo x16D)

When you use Apollo e1x without an Apollo x16D, you can configure preamp settings on the Apollo E window in UAD Console.

To adjust settings for Apollo e1x devices:

- Choose View \> Device \> apollo \| e from the UAD Console menus, or 
- Choose the apollo \| e tab at the top of the UAD Console window 

The Apollo E window, where you can adjust settings for Apollo e1x devices, is displayed. See [Adjusting Apollo e1x preamp settings](#h_01JVMMNHQWN8XYN5H27NPDJJG8) for more information. Apollo e1x devices appear in alphanumeric order. 

The Unison insert does not appear when Apollo e1x is used without an Apollo x16D. You cannot edit preamp settings for an Apollo e1x that is routed to an Apollo x16D channel; in this scenario you adjust the device settings in the main UAD Console window, not in the apollo \| e window. 

**Note:** Apollo e1x devices only appear on the apollo \| e window when they are on the same network as UAD Console. You can choose a network in Settings, on the [Network](#h_01JVMMNHQXSF8XKBMBGZYWGMZB) tab. Only Apollo e1x devices, and not Apollo e2m devices, appear in the apollo \| e window.  

In the apollo \| e window, you can:

- Adjust preamp settings for an Apollo e1x device (gain, 48V phantom power, pad, polarity, and low cut).
- Mute a device: click the Mute switch.
- Identify a device: click the "eye" symbol next to an Apollo e1x device in the browser, or right-click on the scribble strip at the bottom of the preamp strip and choose Identify. This blinks the blue LED on the indicated device.
- Open Dante Controller: click the Dante Controller switch.
- Return to UAD Console: click the Apollo or Volt tabs. 
- View and reset network settings (if desired) for devices: click Network Settings.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![apollo-e-tab.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/84bfc6bf141f80f47119affa25178093711505cf.png)
</figure>

## Adjusting Apollo e1x preamp settings

Apollo e1x appears as a preamp in UAD Console, with the same preamp channel controls as other Apollo preamps. When Apollo e1x is routed to an Apollo x16D input, its Unison insert appears. 

**Note:** If the Apollo e1x channel is routed to an Apollo x16D channel, all DSP is performed on the Apollo x16D. 

## Linking Apollo e1x channels

Apollo e1x devices routed to adjacent (odd/even) Apollo x16D channels can be linked in UAD Console. See [Stereo Link Activation](25351484855828-Monitor-Mix-Controls.html#h_01HTRDPRVAMBJN5Y92D7Q600KN) for more information. 

### Adjust preamp settings for Apollo e1x

- **With Apollo x16D –** Route Apollo e1x to a Dante channel. The preamp settings then appear in the input row at the top of the channel strip. 
- **Without Apollo x16D –**  Choose View \> Device \> apollo \| e from the UAD Console menus to see your Apollo e1x devices, or click the apollo \| e tab at the top of the UAD Console window.\
   

<div>

<figure class="wysiwyg-table" style="width: 240px;">
<table>
<tbody>
<tr>
<td style="text-align: center; vertical-align: top;">![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/f41f335e795ccc974cf65a8c6e0d4d5198046610.png)</td>
<td style="text-align: center; vertical-align: top;">![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/b883ca8967698e571416e2f8d65199344e20bb83.png)</td>
</tr>
</tbody>
</table>
</figure>

</div>

*Apollo e1x routed to Apollo x16D channel in UAD Console (left) and on apollo \| e window (right)*

### Unison insert

The Unison insert appears only when Apollo e1x is routed to a Dante channel on an Apollo x16D. See [Inserting UAD-2 DSP plug-ins in UAD Console](#h_01JVMMNHQWMQW6Q62V02SWV0XK) for more information.

### Gain

You can set the input gain for Apollo e1x from 10 – 65 dB with the Gain knob. The default level is 10 dB. You can also set the gain for one or more Apollo e1x devices with [Preamp Auto-Gain](30921736610836-Preamp-Auto-Gain.html), when routed to Dante channels on Apollo x16D. 

### Pad

When an XLR plug is connected to the Apollo e1x input, press Pad to engage a -20 dB pad. Activate PAD when the input is clipping but preamp gain is at minimum. Alternately, reduce the output level (if available) of the device connected to Apollo's input.

When enabled, the PAD switch in UAD Console is yellow and the channel's microphone input signal level is attenuated by 20 dB. Pad does not apply to the ¼" TRS input.

**Note:** The pad amount may vary when used with a Unison plug-in. 

### Mic/Line

The mic/line switch is not functional with Apollo e1x. The mic or line input is automatically selected based on the connected plug. 

### 48V phantom power

When a microphone is connected via XLR, you can apply 48V phantom power by pressing this button. When enabled, the 48V button in UAD Console and the 48V indicator on Apollo e1x are illuminated red, and 48 volts of phantom power is supplied to the Apollo e1x input. Most modern condenser microphones require 48V phantom power to operate. 

**Caution:** Activate 48V only with compatible equipment such as phantom powered microphones. Incompatible equipment can be damaged by the applied voltage. Disable phantom power before you connect or disconnect a microphone. 

### Low cut filter

When enabled, the channel's input signal passes through a low cut (high pass) filter. The filter has a cutoff frequency of 75 Hz with a slope of 12 dB per octave by default (the filter frequency and slope can change when a Unison plug-in is active in the channel).

The low cut filter is applied to a mic or line source. Low cut is typically used to eliminate rumble and other unwanted low frequencies from the input signal.

### Polarity

When enabled in UAD Console, the polarity (phase) button is yellow and the input channel's signal is inverted. Polarity applies to either a Mic or Line input source.

**Tip:** Polarity inversion can help reduce phase cancellations when more than one microphone is used on a single source.

------------------------------------------------------------------------

# Using Apollo e1x with Apollo x16D and UAD Console

## Routing Apollo e1X to Apollo x16D

You can route an Apollo e1x to two separate x16D receivers. However, if using a Unison preamp plug-in, you can only route Apollo e1X to one Apollo x16D. In this scenario, to route to multiple Apollo x16D receivers, use [flex routing](25351234458260-Output-Flex-Routing.html) to route audio from the channel strip's output to another Dante channel.  

## Adjusting sample rates

When an Apollo E Series device is routed to an Apollo x16D, the sample rate is managed by UAD Console. You can switch the sample rate for all connected Apollo E Series devices by switching the sample rate in the info bar at the bottom of the UAD Console window, or in UAD Console \> Settings \> Hardware.

## Setting Dante latency in UAD Console

You can set the global Dante Latency Control setting in UAD Console \> Settings \> Hardware. The lowest latency setting supported with Apollo E Series is 1.0 ms. To use other devices at a lower latency with Apollo x16D, set the global latency setting in UAD Console to Manual, and set device latencies individually in Dante Controller. 

**Important:** If an Apollo E Series device is routed to multiple x16Ds in different Thunderbolt systems, and the Dante latency settings or sample rates in UAD Console between systems do not match, Dante latency conflicts and audio errors can occur. If you do route to multiple x16Ds, make sure the Dante latency and sample rates are set the same in all instances of UAD Console. 

### Dante latency notes

- Locked devices do not respond to Dante latency changes in UAD Console. Unlock any devices routed to Apollo x16D to change latency.
- Third-party devices do not respond to Dante latency changes in UAD Console. When using third-party devices with Apollo x16D, make sure that all non-Apollo devices match this setting. Otherwise, set the Dante Latency Control to Manual in UAD Console, and adjust latency settings in Dante Controller.
- Although Apollo x16D supports 0.25 and 0.5ms latency settings, when setting Dante latency with Apollo E Series devices routed to the x16D, you cannot set the latency below 1.0 ms. 

You can adjust the Dante Latency Control in UAD Console's Settings, on the Hardware tab.

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/1ba9be7f663ca9ae78026169f96a3ace46ae9120.png)

## Apollo latency compensation

When Apollo devices on a Dante network are configured in a system with other (non-Dante) Apollos, latency compensation is applied when:

1.  Dante Latency Control is set to any setting other than Manual, and
2.  Input Delay Compensation is set to any value other than Off. 

These settings are available in UAD Console \> Settings \> Hardware. 

When these settings are applied, the Input Delay Compensation value is adjusted for other Apollos so all Apollo signals are in sync. 

## Inserting UAD-2 DSP plug-ins in UAD Console

When you route an Apollo e1x to a Dante channel in Apollo x16D, you can insert UAD-2 DSP plug-ins in the standard and Unison inserts. UAD-2 plug-ins are powered by the Apollo x16D's DSP. 

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/657ce053b94c9d6328ad429a5f48b7e14cc1bb0c.png)

**Note:** There is no Hi-Z input on Apollo e1x. When using a Unison plug-in with a Hi-Z source, use a DI box between your instrument and Apollo e1x.

For more information on UAD plug-in inserts, see [this article](25350369296660-UAD-Plug-In-Inserts.html).

For more information on Unison, see [this article](26485044036756-Unison.html). 

## +20 or +24 dBu Headroom setting

When a TRS (line) input is connected to Apollo e1x, the +20 or +24 dBu setting is applied to the signal received by the x16D. This setting is not applied to the XLR (mic) input.

If a Unison plug-in is inserted on an Apollo e1x preamp, the headroom setting is +20 dBu regardless of the Headroom setting.

------------------------------------------------------------------------

# Network Settings

Network settings for Dante network Apollo devices are included on the Network panel.This information is informational, except for the Reset switch. You can adjust network settings for Dante devices in Dante Controller.  For more information, see [Network Panel](https://help.uaudio.com/hc/en-us/articles/28355272973460-Network-Panel). 

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/80de04242ab9f8f1021057e4aa0916fbdd5d0365.png)

------------------------------------------------------------------------

# Apollo e1x Deployment Scenarios

Apollo e1x's small form-factor and preamp capabilities make it an indispensable tool in the studio or live, especially when combined with an Apollo x16D. 

## Live sound deployment

In a live deployment, you can use Apollo e1x devices to locate physical preamp inputs conveniently, and to provide Unison plug-in capabilities to your stage setup. Combined with Apollo e2m devices, a full array of input and monitoring capabilities are available. 

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/106b588208e7322b67cffd1f009b4c0bf2c573cb.png)

## Studio deployment

In a studio deployment, you can use up to 16 Apollo e1x devices with a single Apollo x16D for all of your studio preamp needs. Combined with Apollo e2m devices for personal monitoring, you can create an efficient, personalized recording experience for each artist. 

**Note:** The number of Unison preamp plug-ins you can assign to Apollo e1x channels depends on the available DSP and the complexity of the plug-ins.

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/a9854157025a61ba63956483fee1faf6fbcffe4e.png)

------------------------------------------------------------------------

# Specifications

All specifications are typical performance unless otherwise noted. Tested with the Audio Precision APx555 Audio Analyzer under the following conditions: 48 kHz internal sample rate, 24-bit sample depth, 20 kHz measurement bandwidth, +24 dBu headroom, balanced output, and internal clock. Specifications are subject to change without notice.

## I/O Complement

- **Simultaneous Channel I/O Count (analog + digital):** 1 x 1

- **Network Audio Ports:** One

- **Analog Microphone Inputs:** One

- **Analog Line Inputs:** One

## AD/DA Conversion

- **Simultaneous A/D Conversion:** One channel

- **Available Sample Rates (kHz):** 44.1, 48, 88.2, 96

- **Bit Depth Per Sample:** 24

- **Analog to Network Latency:** Less than 0.2 ms

- **Network Latency:** 1, 2, or 5 ms (switchable)

## Analog I/O: Microphone Input

- **Frequency Response:** 20 Hz – 20 kHz, ±0.04 dB

- **Dynamic Range (A-weighted):** 120 dB

- **THD + Noise (1 kHz @ 4.4 dBu -1 dBFS):** -115 dB (0.00017%)

- **Maximum Input Level (PAD on):** 25 dBu

- **Default Input Impedance:** 5.4 K Ω (variable via Unison plug-ins)

- **Pad Attenuation:** 20 dB (variable via Unison plug-ins)

- **Gain Range:** +10 dB to +65 dB

- **Phantom Power:** +48V

- **Connector Type:** XLR Female, pin 2 positive (Combo XLR/TRS)

## Analog I/O: Line Input

- **Frequency Response:** 20 Hz – 20 kHz, ±0.08 dB

- **Dynamic Range (A-weighted):** 119 dB

- **THD + Noise (1 kHz @ 23dBu, -1 dBFS):** -112 dB (0.00025%)

- **Maximum Input Level:** 24 dBu

- **Input Impedance:** 10 K Ω

- **Gain Range:** +10 dB to + 65 dB

- **Connector Type:** 1/4" female TRS balanced (Combo XLR/TRS)

## Digital I/O

- **Network Audio Ports (100 Mbps Ethernet):** One

- **Digital Connector:** RJ45 Female, CAT 5

- **Networked Audio Format:** Dante or AES67 (48 kHz only)

## Electrical

- **Power Supply:** Power over Ethernet (PoE) 802.3af

- **Maximum Power Consumption (PoE):** 3W (typical), 4W maximum

## Environmental

- **Ambient Temperature Range:** 32º to 104º F (0º to 40º C)

## Mechanical

- **Width:** 1.46" (36.98 mm)

- **Height:** 1.62" (41.1 mm)

- **Depth (Chassis Only):** 6.25" (158.8 mm)

- **Weight (Bare Unit):** 0.5 lbs (208 grams)

- **Shipping Box (L x W x H):** 7" x 1.91" x 1.7" (77.8 mm x 48.4 mm x 43.2 mm)

- **Shipping Weight:** 0.75 pounds (0.3 kg)

## Package Contents

- Apollo e1x

- Product Safety Sheet

 

------------------------------------------------------------------------

# Notices

## Important Safety Instructions

![safety-triangle.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/3ef29c4cdcad027959b686b1643524a5e17b73e6.png)

1.  Read these safety instructions and the instruction manual of the product.Keep these safety instructions and the instruction manual of the product. Always include all instructions when providing the product to other parties.
2.  Heed all warnings.
3.  Follow all instructions.
4.  Do not use this apparatus near water.
5.  Only clean the product when it is not connected to the power supply system. Clean only with a dry cloth.
6.  Do not block any ventilation openings. Install in accordance with the manufacturer's instructions.
7.  Do not install near any heat sources such as radiators, heat registers, stoves, or other apparatus (including amplifiers) that produce heat.
8.  Only operate the product from the type of power source indicated on the power supply unit.
9.  Protect the power cord from being walked on or pinched, particularly at plugs, convenience receptacles, and the point where it enters into and/or exits from the apparatus.
10. Only use attachments/accessories specified by the manufacturer.
11. Unplug this apparatus during lightning storms or when unused for long periods of time.
12. Refer all servicing to qualified service personnel. Servicing is required when the apparatus has been damaged in any way, such as when the power supply cord or plug is damaged, liquid has been spilled into or objects have fallen into the apparatus, or when the apparatus has been exposed to rain or moisture, does not operate normally, or has been dropped.
13. **Warning:** To reduce the risk of fire or electric shock, do not expose this apparatus to rain or moisture. Objects filled with liquids, such as vases, should not be placed on this apparatus.
14. To completely disconnect this apparatus from the AC mains, disconnect the power supply cord plug from the AC receptacle.
15. The mains plug of the power supply cord shall remain readily accessible.
16. Do not attempt to open the product housing. The warranty is voided for products opened by the customer.
17. Let the product reach ambient temperature before switching it on.
18. **Caution:** High signal levels can damage your hearing and your loudspeakers. Reduce the volume on the connected audio devices before switching on the product; this will also help prevent acoustic feedback.
19. Intended use. The product is designed for indoor use. The product can be used for commercial purposes. It is considered improper use when the product is used for any application not named in the corresponding instruction manual. Universal Audio does not accept liability for damage arising from improper use or misuse of this product and its attachments/ accessories. Before putting the product into operation, please observe the respective country-specific regulations.

## Manufacturer's Declarations

### Warranty

The product is covered by a limited warranty. For the current terms of such warranty, please visit [uaudio.com/eula](http://uaudio.com/eula).

### Maintenance

![safety-triangle-bolt.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/69f69a3c91ffc3b8abc208fb136fd38741608b3a.png)

- **CAUTION:** To reduce the risk of electric shock, do not open the unit.
- This product does not contain a fuse or any other user-replaceable parts. The unit is internally calibrated at the factory. No internal user adjustments are available.

### Repair Service

If you are having trouble with your hardware, first check all system setups, connections, and operating instructions. If that doesn't help, contact our technical support team.

To learn about repair service, or to contact Customer Care, visit [help.uaudio.com](../categories/25496430020372-Hardware-Issues-Service-Repair.html).

### Notes on Disposal

In compliance with the following requirements:

#### *WEE-DIRECTIVE (2012/19/EU)*

![safety-trash.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/d7537563a76945b4fec7ebfdf69cc8c7c1bc2553.png)

The symbol of the crossed-out wheeled bin on the product, the battery/rechargeable battery (if applicable), and/or the packaging indicates that these products must not be disposed of with normal household waste, but must be disposed of separately at the end of their operational lifetime. For packaging disposal, please observe the legal regulations on waste segregation applicable in your country.

Further information on the recycling of these products can be obtained from your municipal administration or from the municipal collection points. The separate collection of waste electrical and electronic equipment, batteries/rechargeable batteries (if applicable) and packaging, is used to promote the reuse and recycling and to prevent negative effects caused by e.g., potentially hazardous substances contained in these products. Herewith, you can make an important contribution to the protection of the environment and public health.

## EU Declaration of Conformity

![safety-ce.png](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/adf01a49d95178b45eb1a44d449515815f95608c.png)

- RoHS-Directive (2015/863/EU)
- Low Voltage Directive (2014/35/EU)
- EMC Directive (2014/30/EU)
- REACH Directive (EC1907/2006)

## Class B Device Statement

### United States

NOTE: This equipment has been tested and found to comply with the limits for a Class B digital device pursuant to Part 15 of the FCC Rules. These limits are designed to provide reasonable protection against harmful interference in a residential installation. This equipment generates, uses, and can radiate radio frequency energy and, if not installed and used in accordance with the instructions, may cause harmful interference to radio communications. However, there is no guarantee that interference will not occur in a particular installation. If this equipment does cause harmful interference to radio or television reception, which can be determined by turning the equipment off and on, the user is encouraged to try and correct the interference by one or more of the following measures:

- Reorient or relocate the receiving antenna.
- Increase the separation between the equipment and the receiver.
- Connect the equipment into an outlet on a circuit different from that to which the receiver is connected.
- Consult the dealer or an experienced radio/TV technician for help.

Any modifications to the unit, unless expressly approved by Universal Audio, could void the User's authority to operate the equipment.

## Compliance

This product complied with the following requirements:

- Subpart B of Part 15 of FCC Rules for Class B digital devices (ANSI C63.4 methods)
- Innovation, Science and Economic Development Canada Interference Causing Equipment Standard ICES-003, "Information Technology Equipment (ITE) – Limits and methods of measurement", Issue 7, dated October 2020 (Class B) (ANSI C63.4 methods)
- VCCI-CISPR 32:2016 "Technical Requirements" for multimedia equipment (Class B)
- AS/NZS CISPR 32:2015 +A1 +A11 2020 "Electromagnetic compatibility of multimedia equipment – Emission requirements" (Class B)
- CISPR 32:2015 +A1:2019, "Electromagnetic compatibility of multimedia equipment – Emissions requirements" (Class B)
- EN 55032:2015 +A11 +A1:2020, "Electromagnetic compatibility of multimedia equipment – Emissions requirements" (Class B)
- BS EN 55032:2015 +A11 +A1:2020, "Electromagnetic compatibility of multimedia equipment – Emissions requirements" (Class B)
- CISPR 35:2016 "Electromagnetic compatibility of multimedia equipment – Immunity requirements.
- EN 55035:2017 + A11:2020 "Electromagnetic compatibility of multimedia equipment – Immunity requirements.
- BS EN 55035:2017 + A11:2020 "Electromagnetic compatibility of multimedia equipment – Immunity requirements.
- QCVN 118:2018/BTTTT "National technical regulation on Electromagnetic compatibility of multimedia equipment - Emission requirements" (Class B)
- KS C 9832, KS C 9835 (Class B)

## South Korea Compliance Certification

### Apollo e1x

- Applicant Name: Universal Audio, Inc.
- Equipment Name: Apollo e1x
- Registration Number: R-R-UAO-APOLLOE1X
- Manufacturer/Country of Origin: Universal Audio, Inc. / Malaysia, China, Vietnam
- Date of Registration: December 12, 2024

### Product Label

![](Apollo%20e1x%20Remote-Controllable%20Unison%20Preamp%20Manual_assets/71932a606238987d6caf81ccbfde21f21b39e325.png)

## End User License Agreement

Your rights to the Software are governed by the accompanying End User License Agreement, a copy of which can be found at [www.uaudio.com/eula](https://www.uaudio.com/eula).

## Copyrights & Trademarks

Copyright ©2025 Universal Audio, Inc. All rights reserved.

UA owns certain trademarks (or applications therefor) that are used in connection with the following UA Software Products and/or the UAD Platform (together "UA Marks"), including, without limitation:

1176, 1176 LN, 175-B, 176, APOLLO, APOLLO TWIN, ARROW, ASTRA MODULATION MACHINE, BOCK, BOCK AUDIO and BOCK AUDIO logo, CENTURY TUBE CHANNEL STRIP, CYCLOSONIC PANNER, DEL-VERB, DREAMVERB, DYTRONICS, EQP-1A, GOLDEN REVERBERATOR, GOLDEN REVERBERATOR & UA Diamond Design, GOLDEN REVERBERATOR & UA Diamond Design (Series), HELIOS, LA-2A, LA-3A, LUNA, OPAL, OX, OX AMP TOP BOX & Design, OXIDE, POWERED PLUG-INS, RAYMOND, SHAPE, SOUNDELUX and SOUNDELUX USA logo, SPHERE, SPHERE UNIVERSAL AUDIO and UA Diamond Design, STANDARD and UA Diamond Design, STARLIGHT ECHO STATION, TELETRONIX, THE AUTHENTIC SOUND OF ANALOG, TOWNSEND LABS, TRI-STEREO CHORUS, U UNISON PREAMPS & Design, UA Diamond Design, UAD, UAD 2 POWERED PLUG-INS, UAD SPARK, UAD-2 LIVE RACK, UAFX (Stylized), UNIVERSAL AUDIO, UNIVERSAL AUDIO and UA Diamond Design, VOLT UNIVERSAL AUDIO and UA INC. Diamond Design, APOLLO \| X, DREAM 65, POLYMAX, RUBY 63, SETTING THE TONE SINCE 1958, SOUNDELUX USA, SPHERE UNIVERSAL AUDIO and UA Diamond Design, UNIVERSAL AUDIO APOLLO, UNIVERSAL AUDIO UAD, VOLT UNIVERSAL AUDIO and UA Diamond Design, WATERFALL B3, WOODROW 55.

Unless otherwise agreed to in writing under a separate agreement, Customer shall have no interest in any UA Mark and UA will remain the sole and exclusive owner of all right, title and interest in all UA Marks and all applications, reissuances, divisions, re-examinations, renewals or extensions thereof. Other company and product names mentioned herein are trademarks of their respective owners.

ASIO is a trademark and software of Steinberg Media Technologies GmbH.

This manual and any associated software, artwork, product designs, and design concepts are subject to copyright protection. No part of this document may be reproduced, in any form, without prior written permission of Universal Audio, Inc.

## Disclaimer

The information contained in this manual is subject to change without notice. Universal Audio, Inc. makes no warranties of any kind with regard to this manual, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose. Universal Audio, Inc. shall not be liable for errors contained herein or direct, indirect, special, incidental, or consequential damages in connection with the furnishing, performance, or use of this material.

 

<span class="wysiwyg-font-size-small">v260219</span>

