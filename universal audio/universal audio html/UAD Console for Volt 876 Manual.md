---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/41288447947284-UAD-Console-for-Volt-876-Manual.html'
converted_at: 2026-05-31T13:44:58Z
tool: htmlq+pandoc
title: 'UAD Console for Volt 876 Manual'
word_count: 10335
---

# UAD Console for Volt 876 Manual


This article contains complete operating instructions for UAD Console, your software for controlling Volt 876.

<div class="callout callout--info">

**Note:** If you're controlling an Apollo audio interface, see the [UAD Console for Apollo manual](../sections/25052396869908.html). 

</div>

 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![volt-logo.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/9103ff4dde2744f55565a736f5f03c1fb5e26542.png)
</figure>

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![volt-876-console.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/dcf4a7526e4a9d4dcc272add6924ac9e1e446741.png)
</figure>

 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![volt-876-3qtr.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/a18d2742bc7bd85b0c538a0fe268b089e2259fc4.png)
</figure>

 

## In This Article

- [Introducing UAD Console for Volt 876](#h_01K77VBV384PQ59GB79KSDT5T7)
- [Overview of UAD Console for Volt 876](#h_01K77VBV3ERBWNM60FENZ5EBSZ)
- [UAD Console for Volt 876 Layout](#h_01K77VBV3PZ9XJX9V57TX4VE6X)
- [Inputs in UAD Console for Volt 876](#h_01K77VBV4P1CF9PSZGKKW09K9Q)
- [Monitor Mix Controls](#h_01K77VBV5NCPA5A3ZNH3F0QSEH)
- [Monitor Column](#h_01K77VBV5Z4TG8TPE148P4MW8T)
- [Control Room](#h_01K782Q24T3Y5SSN3R2VH6TA95)
- [Cues](#h_01K77VBV6PZXPCKQ3G0G55ATF7)
- [USB and ADAT Mode](#h_01K77VBV6X9KN67646H2N4D10Z)
- [ADAT expansion with multiple Volt 876 interfaces](#h_01K77VBV75YSYVZ79H4FZE51K9)
- [ADAT Expansion with Other Digital Gear](#h_01KM126HEP7435K661X7BWJ29Q)
- [UAD Console for Volt 876 Settings](#h_01K77VBV7MWSF8DYA1TMS5GX2A)

------------------------------------------------------------------------

# Introducing UAD Console for Volt 876

UAD Console for 876 is powerful companion software for your Volt 876 audio interface that provides full remote control of all hardware functions, right from your computer. You can also create a latency-free main monitor mix and two additional cue mixes for performers, control a loopback channel for software inputs, use the talkback mic, and much more.

UAD Console for Volt 876 lets you:

- Adjust preamp settings for all analog inputs (gain, Vintage mode, 76 Compressor, Polarity, and +48V phantom power)
- Adjust preamp gain automatically with Assistive Auto-Gain
- Enable instrument (Hi-Z) levels on analog inputs 1 & 2
- Adjust monitor and cue mixes from the analog, digital, and loopback inputs
- Route two independent cue mixes to the headphone outputs and line or digital outputs
- Use Volt 876's built-in talkback mic to communicate with performers through cue mixes
- Control a stereo loopback (software playback) to monitor the output of other apps
- Control an expanded system for full mixing of 16 – 24 analog input channels with two or three Volt 876 units
- Save and load UAD Console session files for total recall of all relevant settings
- Configure Volt 876 as your primary audio interface, a standalone ADAT A/D - D/A converter with preamp control, or configure multiple Volt 876 units in an expanded system

## About Volt 876 Documentation

- For UAD Console setup and descriptions, use this manual.
- For hardware configuration and descriptions, see the [Volt 876 Hardware Manual](41288385879956-Volt-876-Hardware-Manual.html).
- For registering your Volt in UA Connect and redeeming included software, see [How to set up your Volt Interface](4409233546644-How-to-set-up-your-Volt-Interface.html).

## Get UAD Console

To download and install the latest UAD Console app, and to update your Volt 876 firmware, use the UA Connect app. See [this article](4409233546644-How-to-set-up-your-Volt-Interface.html) for details.

------------------------------------------------------------------------

# Overview of UAD Console for Volt 876

UAD Console for Volt 876 is remote control software for your Volt 876 hardware, providing complete control of all hardware features, except headphone volumes and the power switch. It also functions as a mixer for combining analog and digital audio signals at your Volt 876 inputs for latency-free direct monitoring. Unlike UAD Console with Apollo, UAD Console for Volt 876 does not have any plug-in inserts or plug-in processing. All plug-in processing occurs in your DAW.

You can route your input signals to the main monitor mix, and send two independent cue mixes to designated outputs for performers. UAD Console for Volt 876 also controls the built-in talkback mic that you can use to communicate with performers through the cue mixes, and a loopback channel for including the output from other software, such as system sounds or video conferencing software, to your monitor and cue mixes.

With Volt 876, you can also record the *outputs* of UAD Console for Volt 876 (monitor mix, talkback mic, and loopback channel) into your DAW (digital audio workstation) software. Simply choose these "virtual" software outputs as the source for your DAW's input channel.

## Hardware versus software monitoring

Direct hardware monitoring routes Volt 876 inputs directly to outputs for live monitoring, without being sent to the DAW first. Unlike software monitoring in your DAW, which has buffering latency, direct monitoring lets you hear your inputs without any latency.

UAD Console for Volt 876 **does not** mix signals that are software monitored in your DAW – for example, when you are playing through DAW plug-ins. When software monitoring, you must mute the input(s) in UAD Console, or disable Direct monitoring on the Volt 876 hardware, to prevent doubled signals. 

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table-resized" style="border-color: #096ECC;">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td style="background-color: #CEE2F2; border-color: #000000; padding: 10px"><h3 id="h_01K77VBV3GY9PZG95C1JH9V7MT">Essential concept: Hardware monitoring (Direct) and software monitoring (Mute)</h3>
<p><strong>Direct monitoring:</strong> Volt 876 inputs are <strong>unmuted</strong> and heard without latency. Input signals are still sent to the DAW so they can be recorded.</p>
<p><strong>Software monitoring:</strong> Volt 876 inputs are <strong>muted</strong> and heard from the DAW's mixer. Inputs can be processed with DAW plug-ins, but the monitored signals are subject to latency that depends on your buffer size setting.</p>
<p><strong>Important:</strong> When software monitoring, you must mute the input(s) in UAD Console, or disable Direct monitoring on the Volt 876 hardware, to prevent doubled "phasey" or "thin" audio.</p></td>
</tr>
</tbody>
</table>
</figure>

</div>

## Modes overview

Volt 876 has two main operating modes, USB and ADAT. These two modes are completely different configurations of the Volt 876 inputs and outputs. The mode you need depends on how you use Volt 876. For details, see [Mode](#h_01K77VBV6X9KN67646H2N4D10Z).

**USB mode –** The standard audio interface mode, which allows you to route up to 24 analog and digital inputs into and out of your computer. USB mode is also the mode for the control unit in an ADAT expansion system. 

**ADAT mode –** Reconfigures Volt 876 as a standalone mic preamp and A/D - D/A converter, or for use in an ADAT expansion system. In ADAT mode, digital audio is *routed* via optical cables, but the unit can be *controlled* by UAD Console for Volt 876 when connected to the computer via USB. ADAT mode has two possible states:

- ADAT standalone mode, with or without computer control via USB.
- ADAT expansion mode, when connecting two or three Volt 876's together as a multi-unit system. In this configuration, expander units are interconnected with optical cables, and up to 72 inputs are controlled via USB within a single, consolidated window in UAD Console for Volt 876. 

------------------------------------------------------------------------

# UAD Console for Volt 876 Layout

UAD Console for Volt 876 always shows certain screen elements (the title bar, info bar, meter bridge, and input channel strips). You can show or hide other UAD Console elements to suit your workflow. The following illustration highlights some sections of the UAD Console for Volt 876 window. 

**Tip:** UAD Console supports multiple levels of undo and redo. To undo a change in UAD Console, press Command+Z (Mac) or Alt+Z (Windows).

<figure class="wysiwyg-image">
![volt-876-console-callouts.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/c87fb719a43271cc9de81c277a0831df45b68f7c.png)
</figure>

 

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 7%" />
<col style="width: 28%" />
<col style="width: 64%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Overview</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;"><a href="#h_01K77VBV441B8WA3ANJ6B8QY2M">Title bar</a></td>
<td style="text-align: center;">Includes the Device Name or Device Selector and Close, Minimize, and Maximize buttons. </td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;"><a href="#h_01K77VBV4RJ23NKF93Y6VES67C">Preamp controls</a></td>
<td style="text-align: center;">On analog inputs 1-8, allows you to configure the preamp settings.</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;"><a href="#h_01K77VBV6PZXPCKQ3G0G55ATF7">Cue controls</a></td>
<td style="text-align: center;">Allows you to adjust the two independent cue mixes for Volt 876.</td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;"><a href="#h_01K77VBV46VNP3E2R6B4FARH42">Meter bridge</a></td>
<td style="text-align: center;">Shows small level meters for all currently visible inputs. Drag left or right in the meter bridge to see any inputs that may be out of view. </td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;">Device Name or Selector</td>
<td style="text-align: center;">Select the device view for UAD Console here. You can select either Volt, Apollo, or Apollo E devices (if present).</td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;"><a href="#h_01K77VBV4QWWTA43J9CB5NZMX7">Analog inputs</a></td>
<td style="text-align: center;">Analog inputs 1–8 are preamp inputs that can be connected to the outputs of analog equipment with ¼" or XLR connectors.</td>
</tr>
<tr>
<td style="text-align: center;">7</td>
<td style="text-align: center;"><a href="#h_01K77VBV59XNZSAJGR00QPZMEG">Digital inputs</a></td>
<td style="text-align: center;">Digital inputs are for mixing ADAT or S/PDIF signals from the outputs of other digital gear.</td>
</tr>
<tr>
<td style="text-align: center;">8</td>
<td style="text-align: center;"><a href="#h_01K77VBV5M8WP0CQFW43TYECFX">Loopback channel</a></td>
<td style="text-align: center;">The Loopback channel can be used to blend any audio routed to the system's "loopback" outputs into the mixer.</td>
</tr>
<tr>
<td style="text-align: center;">9</td>
<td style="text-align: center;"><a href="#h_01K77VBV6H1BPVRSXRJM94Z4S2">Control Room column</a></td>
<td style="text-align: center;">Lets you use the talkback mic on the front of the Volt 876 to address performers through Cue mixes, and to choose which  source to monitor.</td>
</tr>
<tr>
<td style="text-align: center;">10</td>
<td style="text-align: center;"><a href="#h_01K77VBV5Z4TG8TPE148P4MW8T">Monitor column</a></td>
<td style="text-align: center;">Lets you configure which inputs to show in UAD Console, configure cue sources, and control the main mix level to your monitor speakers.</td>
</tr>
<tr>
<td style="text-align: center;">11</td>
<td style="text-align: center;"><a href="#h_01K77VBV4H1219R0RRTV3XR3ZX">Info bar</a></td>
<td style="text-align: center;">Lets you choose the Volt 876 operating mode, sample rate, and clock source.</td>
</tr>
<tr>
<td style="text-align: center;">12</td>
<td style="text-align: center;">Options column</td>
<td style="text-align: center;">Includes large and small switches for each Cues row, and the Clear Solo (S) and Clear Over Limit (OL) switches. Clear Solo allows you to toggle Solo on/off for any soloed channels. Clear OL clears any clipped meter LEDs in UAD Console. </td>
</tr>
</tbody>
</table>
</figure>

</div>

## Title Bar

The Title Bar is the topmost strip in the UAD Console window, as shown below.

<figure class="wysiwyg-image">
![volt-876-top-bar.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/8b010bf0c212b1cf5f960932ab9ae31e18646250.png)
</figure>

*UAD Console Title Bar*

Volt 876 (or your custom Volt device name, if entered in Settings) and the session name  is displayed at the top of the title bar, in the Volt tab. Click a tab to switch to another device view, or use the key commands to navigate (Shift+Cmd+←/→ in macOS, Shift+Ctrl+←/→ on Windows). 

The Title Bar includes Close, Minimize, and Maximize buttons. Click the “X” button to close the UAD Console window and quit UAD Console.

## Meter Bridge

The meter bridge appears at the top of the UAD Console window. The Meter Bridge shows small level meters for all displayed inputs, even if not visible. The analog inputs are always visible. You can show or hide the two banks of digital inputs with the ADAT switches in the Monitor column. 

Drag left or right in the meter bridge to see any inputs that may be out of view (if all channels are not already visible). 

<figure class="wysiwyg-image">
![volt-876-meter-bridge-arrows.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/865bb42e7b0226e9603f38f78a204d66bd0058c1.png)
</figure>

### Meter Bridge Channel Meters

The vertical LED meters represent input signal activity for each displayed channel. These small meters mirror the activity of the high-resolution input meters that are displayed next to each channel’s input fader.

## Signal flow overview

The following illustration shows how signals move through an input channel strip in UAD Console. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![volt-876-channel-flow.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/80b59abf84a7fa2dfb1bcb4e769fff1b98e7cf61.png)
</figure>

 

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 6%" />
<col style="width: 26%" />
<col style="width: 68%" />
</colgroup>
<tbody>
<tr>
<td>#</td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Overview</strong></td>
</tr>
<tr>
<td>1</td>
<td style="text-align: center;"><a href="#h_01K77VBV4YA3F90S05DAQ3BMM2">Vintage preamp mode</a></td>
<td style="text-align: center;">Applies analog vintage preamp processing to the input signal (analog inputs only) </td>
</tr>
<tr>
<td>2</td>
<td style="text-align: center;"><a href="#h_01K77VBV4Z6DRY82Q94DFZK1MX">76 Compressor</a></td>
<td style="text-align: center;">Compresses the input signal with adjustable analog compression (analog inputs only) </td>
</tr>
<tr>
<td>3</td>
<td style="text-align: center;"><a href="#h_01K77VBV52WQ3CZEPEQBE89KTR">Gain</a></td>
<td style="text-align: center;">Sets the signal level manually (analog inputs only) </td>
</tr>
<tr>
<td>4</td>
<td style="text-align: center;"><a href="#h_01K77VBV52SQ9EEC6N9HB0NKMR">Assistive Auto-Gain</a></td>
<td style="text-align: center;">Sets the signal level automatically (analog inputs only) </td>
</tr>
<tr>
<td>5</td>
<td style="text-align: center;"><a href="#h_01K77VBV583EECPVCQ5MZTMXR2">48V phantom power</a> and <a href="#h_01K77VBV59YEVJZH71GQ9K281G">polarity</a></td>
<td style="text-align: center;">Enables/disables phantom power and reverses polarity (analog inputs only) </td>
</tr>
<tr>
<td>6</td>
<td style="text-align: center;"><a href="#h_01K77VBV6PZXPCKQ3G0G55ATF7">Cues</a></td>
<td style="text-align: center;">All inputs can be routed to up to two cue buses, letting you create separate individual mixes for performers with levels tailored to their needs. Cues can be routed to headphone outputs, and mirrored to line outputs.</td>
</tr>
<tr>
<td>7</td>
<td style="text-align: center;">Pan</td>
<td style="text-align: center;">All inputs can be panned to the right or left in the stereo field.</td>
</tr>
<tr>
<td>8</td>
<td style="text-align: center;">Solo and Mute</td>
<td style="text-align: center;">You can solo one or more inputs to temporarily hear individual sources alone. You can mute one or more inputs to temporarily remove them from the mix. </td>
</tr>
<tr>
<td>9</td>
<td style="text-align: center;">Fader</td>
<td style="text-align: center;">You can adjust the fader for an input to set the level of the source in the mix. The fader does not affect the input level of a track (the level that is received by your DAW software).</td>
</tr>
<tr>
<td>10</td>
<td style="text-align: center;">Out to Main Mix</td>
<td style="text-align: center;">All inputs are routed to the main mix, which you can listen to on speakers connected to the Monitor outputs or headphones connected to headphone outputs 1 & 2 (if not used for cues).</td>
</tr>
</tbody>
</table>
</figure>

</div>

## Info Bar

The Info Bar is where you can access commonly adjusted settings.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![volt-876-info-bar-usb.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/96a4b991ad6cc28dbd179531ca29f04b263e318e.png)
</figure>

### Mode

Sets the operating mode for Volt 876. See [USB mode](#h_01K77VBV6YQMY5QCP4M70EA042) and [ADAT mode](#h_01K77VBV72B0NHDAVDRQN06Z35) for complete details.

### Sample Rate

This displays the current sample rate for A/D and D/A conversion. Select a different sample rate from this drop menu. [The number of available ADAT channels](#h_01K77VBV5AG1NV5EDD6TWVSJ91) changes at higher sample rates (88.2 kHz or higher). 

#### *Available sample rates (kHz)*

- 44.1
- 48
- 88.2
- 96
- 176.4
- 192

### Clock Source

The active clock source (Internal, ADAT, S/PDIF, or Word Clock) is displayed here. You can select a different clock source from this drop menu. The clock source flashes red if the currently selected clock is unresolved (when digital audio is not synchronized).

- **Internal:** The clock source is Volt 876's internal clock. 
- **Word Clock:** The clock source is from an external clock connected to the word clock input on Volt 876.
- **ADAT:** The clock source is from an incoming ADAT signal. ADAT is only available when the digital input format is ADAT in UAD Console settings, or the unit is in ADAT mode. 
- **S/PDIF:** The clock source is from an incoming S/PDIF signal. S/PDIF is only available when the digital input format is S/PDIF in UAD Console settings. 

**Important:** When the Clock Source parameter is set to use any external clock source, the sample rate must be manually set to match the sample rate of the external clock.

------------------------------------------------------------------------

# Inputs in UAD Console for Volt 876

The following input channel types are available on Volt 876 in UAD Console.

- [Volt 876 analog inputs](#h_01K77VBV4QWWTA43J9CB5NZMX7)
- [Volt 876 digital inputs](#h_01K77VBV59XNZSAJGR00QPZMEG)
- [Volt 876 loopback channel](#h_01K77VBV5M8WP0CQFW43TYECFX)

## Volt 876 analog inputs

All analog inputs have preamps and accept audio from analog sources such as a microphone, guitar or bass instruments, or the analog outputs from line-level equipment such as keyboards. There are two analog connector types available for each analog input 1–8. 

- **XLR connectors –** When an XLR plug is connected to a jack, all preamp features are available except for the INST (Hi-Z) setting on channels 1–2. 
- **¼" connectors –** When a ¼" TRS or TS plug is connected to a jack, all preamp settings are available except for 48V phantom power, which is only available on XLR connections. 
- **Hi-Z connectors–** When a ¼" plug is connected to analog inputs 1–2, these inputs can be set to accept Hi-Z instrument signals by engaging the INST switch on the hardware or in UAD Console. 48V phantom power is disabled when the INST button is lit.

## Analog preamp quick reference

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![volt-876-analog-preamp-channel-callouts.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/76ec08385534a504c42ba27b5cac2cecb6af99b6.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 7%" />
<col style="width: 32%" />
<col style="width: 61%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Overview</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;"><a href="#h_01K77VBV4YA3F90S05DAQ3BMM2">Vintage preamp mode</a></td>
<td style="text-align: center;">Enable Vintage preamp mode to add classic analog preamp tone to your signal. Vintage preamp tone is recorded in your DAW software.</td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;"><a href="#h_01K77VBV4Z6DRY82Q94DFZK1MX">76 Compressor</a></td>
<td style="text-align: center;">Enable the 76 compressor to provide analog 1176-style compression to the input signal. 76 compression is recorded in your DAW software.</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;"><a href="#h_01K77VBV52VMVCAJ97B2BD6JZQ">Instrument switch</a></td>
<td style="text-align: center;">Sets input 1 or 2 to accept instrument (Hi-Z) input.</td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;"><a href="#h_01K77VBV52WQ3CZEPEQBE89KTR">Gain knob</a></td>
<td style="text-align: center;">Manually set the level for the incoming signal with the Gain knob. This adjusts the signal level to your DAW software.</td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;"><a href="#h_01K77VBV52SQ9EEC6N9HB0NKMR">Assistive Auto-Gain</a></td>
<td style="text-align: center;">Adjust the input level for one or more channels automatically using Assistive Auto-Gain.This sets the level to your DAW software.</td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;"><a href="#h_01K77VBV583EECPVCQ5MZTMXR2">48V phantom power switch</a></td>
<td style="text-align: center;">Apply 48V phantom power when required for microphones. </td>
</tr>
<tr>
<td style="text-align: center;">7</td>
<td style="text-align: center;"><a href="#h_01K77VBV59YEVJZH71GQ9K281G">Polarity switch</a></td>
<td style="text-align: center;">Reverse the polarity of the channel to correct for phase problems. </td>
</tr>
</tbody>
</table>
</figure>

------------------------------------------------------------------------

 

</div>

## Volt 876 analog input details

### Vintage preamp mode

Vintage preamp mode adds a carefully crafted analog tube preamp emulation, inspired by Universal Audio’s all-tube 610 console preamplifier, for a richer sound. When the button is lit orange, the circuit is active.

Press the Vintage switches to toggle Vintage preamp mode. Vintage preamp mode can be used on mic, line, and instrument inputs. When enabled, the Vintage button is lit in UAD Console and on the Volt 876 hardware for the input.

### 76 compressor

To enable or disable a 76 comp preset, click the preset name, or press the 76 Comp button to toggle the 76 compressor circuit on/off. The 76 compressors can be used on mic, line, and instrument inputs. The button is lit orange when the compression circuit is active.

The 76 Compressor lets you add clarity and punch to voice, guitars, and more, with an analog compressor based on UA's iconic 1176 Limiting Amplifier.

**Tip:** The input level increases when the compressor is active, so you may want to readjust your Gain setting.

#### *76 Compressor Presets*

The indicators below the 76 Comp button indicate whether the compressor is off or enabled with one of the presets. The 76 Comp presets have the following characteristics:

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 17%" />
<col style="width: 83%" />
</colgroup>
<tbody>
<tr>
<td>FAST</td>
<td>Fastest attack and fast release for aggressive compression</td>
</tr>
<tr>
<td>GUITAR</td>
<td>Medium attack and very slow release allows guitar/bass transients and longer sustain</td>
</tr>
<tr>
<td>VOCAL</td>
<td>Slowest attack and slow release for classic smooth vocal compression</td>
</tr>
</tbody>
</table>
</figure>

</div>

**Tip:** Although these presets are designed to work well with these particular sources, you can use any setting with any source. Feel free to use the 76 Comp creatively.

### Instrument switch (channels 1–2 only)

Press the INST switch to toggle the impedance and gain of the ¼" input to accommodate a Hi-Z instrument, such as an electric guitar or bass.

### Gain knob

You can manually adjust the gain for an input channel with the gain knob in UAD Console, or you can use the encoder on the left side of the Volt 876 hardware. In UAD Console, drag the knob to adjust the level. Adjust the level so your loudest sources do not peak in the red on the UAD Console input strip meter. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 13%;">
![gain-arrow.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/1565b3c98293cecf27abaca98ac16fe0f9a2fe06.png)
</figure>

### Assistive Auto-Gain

You can set the preamp's input gain automatically with Assistive Auto-Gain.

**CAUTION:** Assistive Auto-Gain automatically adjusts preamp levels for recording. To avoid damage to your hearing, confirm your monitor levels are set safely before proceeding.

#### *To set gain automatically*

1.  On any preamp channel, press the Auto-Gain button under the gain knob. The Auto-Gain floating window opens.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![auto-gain-fw.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/749a7d028a3ad4f414490acc3f51ef7fdbb20781.png)
</figure>

2.  Press Start, and play your source as loudly as you will play during the performance. The gain is set automatically.

By default, Assistive Auto-Gain detects and adjusts levels for 10 seconds. To increase or decrease the duration by ±5 seconds, press the -5 or +5 buttons. You can adjust the duration while Auto-Gain is listening.

The Auto-Gain floating window closes after the listening duration completes. To close the Auto-Gain window, click Done.

**Note:** When using Auto-Gain with stereo linked inputs, the same gain amount is applied to both inputs. Auto-Gain sets the level based on the peak from the loudest input. 

**Tip:** You can set Auto-Gain on multiple preamps simultaneously. Simply click the Auto-Gain button for each preamp you want to adjust. The Auto-Gain options in the floating window apply to all Auto-Gain-enabled preamps.

#### *Auto-Gain settings*

Click SHOW MORE to see more settings for Auto-Gain.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![auto-gain-fw-more.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/86769073dc213b92b1748b7b2f9dbaef2b266480.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 28%" />
<col style="width: 72%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; width: 25%;"><strong>Feature</strong></td>
<td style="text-align: center; width: 75%;"><strong>Details</strong></td>
</tr>
<tr>
<td style="text-align: center; width: 25%;">Duration</td>
<td style="text-align: center; width: 75%;"><p>Sets the amount of time that Auto-Gain listens while setting gain levels.</p>
<p>The default setting is 10 seconds. To set a different duration, click and drag up or down in the box, or click the -5 or +5 buttons. You can also click in the box and type a new value, then press Enter.</p>
<p><strong>Note:</strong> The maximum duration is 90 seconds. </p></td>
</tr>
<tr>
<td style="text-align: center; width: 25%;"><p>Apply Gain</p>
<p><br />
 </p></td>
<td style="text-align: center; width: 75%;"><p>Sets the Auto-Gain adjustment behavior.</p>
<p>WHILE LISTENING applies gain changes every two seconds for the Auto-Gain duration. You can only use WHILE LISTENING with one or two preamps enabled for Auto-Gain. </p>
<p>AFTER LISTENING applies the gain change after the Auto-Gain listening duration is complete.</p></td>
</tr>
<tr>
<td style="text-align: center; width: 25%;">Listening Threshold</td>
<td style="text-align: center; width: 75%;">Determines the lowest level at which Auto-Gain detects a signal and begins adjusting gain. This setting ensures that Auto-Gain doesn’t set very loud gains when no detectable signal is available. The default setting is -50 dBFS, which may be too quiet for low level sources. To set a different threshold, click and drag up or down in the box, or click in the box and type a new value, then press Enter.</td>
</tr>
<tr>
<td style="text-align: center; width: 25%;"><p>Peak Target</p>
<p><br />
 </p></td>
<td style="text-align: center; width: 75%;">Determines the maximum peak level that Auto-Gain should set for your material. The default setting is -8 dBFS, but you can adjust it higher or lower. Be aware that higher settings (less headroom) increase the risk of digital clipping. To set a different peak target, click and drag up or down in the box, or click in the box and type a new value, then press Enter.</td>
</tr>
</tbody>
</table>
</figure>

</div>

### 48V phantom power

If you are using equipment that requires phantom power, such as a condenser microphone, engage the 48V switch on the channel. When 48v phantom power is enabled, the 48V LED is lit red in UAD Console and on the Volt 876 hardware for the channel. The 48V LED blinks briefly when enabling or disabling phantom power. Do not connect or disconnect equipment from the input when 48V phantom power is enabled, or when the LED is blinking.  

**Caution**: Activate 48V only with compatible equipment such as phantom powered microphones. Incompatible equipment could be damaged by the applied voltage.

### Polarity

Enable the polarity (phase) switch to invert the channel's signal polarity. When enabled, the switch is lit in UAD Console and on the Volt 876 hardware for the selected channel.  

**Tip:** Invert polarity to reduce phase cancellations when more than one microphone is used to record a single source.

## Volt 876 digital input details

The digital inputs route digital signals (ADAT or S/PDIF) into the mixer. With UAD Console, you can route the digital inputs to cues. With your DAW, you can route the digital inputs to any Volt 876 outputs. 

Unlike analog inputs, there are no tone-shaping features or preamp controls for digital channels. Signal levels for the digital inputs are set by adjusting the output levels of the digital gear connected to Volt 876.

To choose the digital channel format, see [UAD Console for Volt 876 Settings](#h_01K77VBV7MWSF8DYA1TMS5GX2A).

### Toggle ADAT channel visibility

Volt 876's ADAT channels can be shown or hidden in UAD Console. To toggle ADAT channel visibility, click the buttons below Cues in the Monitor strip. These buttons are labeled with the channels that will be shown/hidden when toggled. When a button is lit those channels are shown in UAD Console. The number of available channels is updated if you change the sample rate. 

Note that the visibility of an input does not mute or unmute audio. Use the Mute switch to mute a digital channel. If S/PDIF digital format is specified, those channels are always displayed and the buttons for ADAT channels do not appear.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 13%;">
![show-adat-channels.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/defc78c4cb923c1de04d5008bcdbd934116ce888.png)
</figure>

### ADAT

With ADAT inputs, up to 16 ADAT input channels are available in the UAD Console mixer, depending on the digital format and sample rate. 

### S/PDIF

With S/PDIF inputs, two input channels and two output channels are available, regardless of the sample rate. S/PDIF output channels are mirrored on the two optical outputs.

#### Digital audio channels and sample rates

A simple overview of the available digital audio channels at different sample rates is provided in the table below.

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 16%" />
<col style="width: 20%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td><span class="wysiwyg-font-size-small"><strong>Optical Format</strong></span></td>
<td><span class="wysiwyg-font-size-small"><strong>Sample Rate (kHz)</strong></span></td>
<td><span class="wysiwyg-font-size-small"><strong>Optical IN 1</strong></span></td>
<td><span class="wysiwyg-font-size-small"><strong>Optical OUT 1</strong></span></td>
<td><span class="wysiwyg-font-size-small"><strong>Optical IN 2</strong></span></td>
<td><span class="wysiwyg-font-size-small"><strong>Optical OUT 2</strong></span></td>
</tr>
<tr>
<td rowspan="3"><span class="wysiwyg-font-size-small">S/PDIF</span></td>
<td><span class="wysiwyg-font-size-small">44.1, 48 </span></td>
<td rowspan="3"><p><span class="wysiwyg-font-size-small">Two channels</span></p>
<p><span class="wysiwyg-font-size-small">S/PDIF L/R</span></p></td>
<td rowspan="3"><p><span class="wysiwyg-font-size-small">Two channels</span></p>
<p><span class="wysiwyg-font-size-small">S/PDIF L/R</span></p></td>
<td rowspan="3"><span class="wysiwyg-font-size-small">Disabled</span></td>
<td rowspan="3"><p><span class="wysiwyg-font-size-small">Two  channels</span></p>
<p><span class="wysiwyg-font-size-small">S/PDIF L/R (mirrored)</span></p></td>
</tr>
<tr>
<td><span class="wysiwyg-font-size-small">88.2, 96 </span></td>
</tr>
<tr>
<td><span class="wysiwyg-font-size-small">176.4, 192 </span></td>
</tr>
<tr>
<td rowspan="3"><span class="wysiwyg-font-size-small">ADAT</span></td>
<td><span class="wysiwyg-font-size-small">44.1, 48 </span></td>
<td><p><span class="wysiwyg-font-size-small">Eight channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 1–8</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Eight channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 1–8</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Eight channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 9–16</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Eight channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 9–16</span></p></td>
</tr>
<tr>
<td><span class="wysiwyg-font-size-small">88.2, 96 (S/MUX)</span></td>
<td><p><span class="wysiwyg-font-size-small">Four channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 1–4</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Four channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 1–4</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Four channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 5–8</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Four channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 5–8</span></p></td>
</tr>
<tr>
<td><span class="wysiwyg-font-size-small">176.4, 192 (S/MUX)</span></td>
<td><p><span class="wysiwyg-font-size-small">Two channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 1–2</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Two channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 1–2</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Two channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 3–4</span></p></td>
<td><p><span class="wysiwyg-font-size-small">Two channels</span></p>
<p><span class="wysiwyg-font-size-small">ADAT 3–4</span></p></td>
</tr>
</tbody>
</table>
</figure>

</div>

## Volt 876 loopback channel

The loopback (software playback) channel routes system audio into your UAD Console mixer. With this channel you can incorporate audio from audio apps, videos, games, or other system events into your audio production stream. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 13%;">
![loopback-with-audio.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/92cdb350e19214134bb2d272074ff260545cc23c.png)
</figure>

Typical loopback uses:

- **Recording system audio –** Capture music, podcasts, or video sound directly from your computer without a microphone
- **Live streaming –** Play background music or sound effects for your audience while live streaming
- **Virtual meetings –** Share audio clips or a song with others during a virtual meeting or a video conference call
- **Capturing game audio –** Record in-game sounds cleanly, without picking up keyboard noise or other room sounds

To route audio into the loopback channel, select LOOPBACK as the output device in your audio software's advanced settings. Note that not all software has this capability.

------------------------------------------------------------------------

# Monitor Mix Controls

Monitor mix are the controls in UAD Console that allow you to mix audio signals that appear in monitor outputs 1-2 (and Alt outputs 3-4, when configured). Monitor mix controls appear slightly differently for mono and stereo linked tracks.

**Tip:** You can toggle compact faders (making them shorter) by clicking the top edge of the fader area. Alternatively, choose View \> Compact Monitor Faders from the UAD Console menus to toggle fader height. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![volt-876-monitor-channel.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/6b60a49ee4116bab25dc78a0d138a05cde7308b6.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 5%" />
<col style="width: 24%" />
<col style="width: 71%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Description</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">Input pan</td>
<td style="text-align: center;">Moves the track left and right in the stereo panorama. Stereo linked inputs include left and right pan controls. </td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;">Input solo</td>
<td style="text-align: center;">Only this input is heard in the monitor mix. Multiple inputs can be soloed at the same time. </td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;">Input mute</td>
<td style="text-align: center;"><p>Input is not heard in the monitor mix. Multiple inputs can be muted at the same time. </p>
<p>Note that to monitor an input only through your DAW (software monitoring), you must mute the input. When not muted, direct monitoring is enabled on the input.</p></td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;">Input fader</td>
<td style="text-align: center;">Adjusts the level of the input in the monitor mix. The input fader does not affect the level sent to the DAW. </td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;">Input level meter</td>
<td style="text-align: center;">Displays the input signal level. The input fader does not change the meter level. To change the meter level, adjust the input's preamp gain (analog inputs only).</td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;">Input fader value</td>
<td style="text-align: center;">Displays the level in dB of the fader. Click to enter a specific value.  </td>
</tr>
<tr>
<td style="text-align: center;">7</td>
<td style="text-align: center;">Channel name</td>
<td style="text-align: center;">Displays the input name. Click to rename the input, and to link or unlink stereo inputs. </td>
</tr>
</tbody>
</table>
</figure>

</div>

## Renaming and linking inputs

Click on the name of an input at the bottom of the channel strip to open the rename / link popover. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![volt-876-rename-link.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/d99e31c659a62a00781856be2779b75faf338b14.png)
</figure>

 

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 5%" />
<col style="width: 25%" />
<col style="width: 70%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Description</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">Input name</td>
<td style="text-align: center;">You can enter a custom name here. To restore the original name, clear the entry the close the popover </td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;">Link button</td>
<td style="text-align: center;">Click this button to link or unlink a stereo pair. When the link button is lit, the track is linked. Stereo pairs must begin with an odd-numbered input (you can link input 5 & 6, but not 6 & 7).</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;">Previous / Next</td>
<td style="text-align: center;">Click the arrows to cycle through the previous and next inputs.</td>
</tr>
</tbody>
</table>
</figure>

</div>

------------------------------------------------------------------------

# Monitor Column

The Monitor Column contains elements related to monitor outputs, fader display, and cues. The Monitor Column is visible at the right side of the UAD Console window, when View \> Section \> Monitor is selected from the UAD Console menus. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![volt-876-monitor-column.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/da3b9094c5e7363361104751d125622a5aac07b0.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 5%" />
<col style="width: 31%" />
<col style="width: 64%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Description</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">Stereo level meters</td>
<td style="text-align: center;"><p>Display the levels of the monitor mix. Levels displayed here mirror the Monitor 1–2 LED meters on the Volt 876 hardware.</p>
<p>These meters show the signals before the monitor output level control (pre-fader) and reflect the level of the D/A converters at the monitor outputs.</p>
<p><strong>Important:</strong> If clipping occurs, reduce levels feeding the monitor mix by lowering channel faders.</p></td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;">Show: Loopback</td>
<td style="text-align: center;">Toggles display of the Loopback channel. See <a href="#h_01K77VBV5M8WP0CQFW43TYECFX">Volt 876 Loopback channel</a> for details.</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;">Show: Cues</td>
<td style="text-align: center;">Opens the Cue Outputs popover, where cue mixes are assigned. See <a href="#h_01K77VBV6PZXPCKQ3G0G55ATF7">Cues</a> for details.</td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;">Show: ADAT inputs</td>
<td style="text-align: center;">Toggles visibility of the ADAT inputs (if ADAT digital inputs are enabled in UAD Console Settings).</td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;">Show: Settings</td>
<td style="text-align: center;">Shows the Settings window, where you can configure Volt 876 hardware settings. </td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;">Monitor output: Monitor switch</td>
<td style="text-align: center;">When lit, the monitor mix is heard in the monitor (1–2) outputs. This button is visible only when <a href="#h_01K77VBV68G20TDEPPR2NWVND4">ALT monitoring is enabled</a>.</td>
</tr>
<tr>
<td style="text-align: center;">7</td>
<td style="text-align: center;">Monitor output: Alt switch</td>
<td style="text-align: center;">When lit, the monitor mix is heard in the Alt (3–4) outputs. This button is visible only when <a href="#h_01K77VBV68G20TDEPPR2NWVND4">ALT monitoring is enabled</a>.</td>
</tr>
<tr>
<td style="text-align: center;">8</td>
<td style="text-align: center;">Monitor output: Mono switch</td>
<td style="text-align: center;">Sums the left and right channels of the stereo monitor mix into a mono signal. The monitor output is mono when the button is lit.</td>
</tr>
<tr>
<td style="text-align: center;">9</td>
<td style="text-align: center;">Monitor level knob</td>
<td style="text-align: center;">This is the master level control for Volt's monitor outputs. It mirrors the monitor level knob on the Volt 876 hardware.</td>
</tr>
<tr>
<td style="text-align: center;">10</td>
<td style="text-align: center;">Show: Control Room switch</td>
<td style="text-align: center;">Toggles display of the <a href="#h_01K782Q24T3Y5SSN3R2VH6TA95">Control room</a> column, where you enable talkback, adjust talkback sends, and select which mix is heard at the monitor outputs.</td>
</tr>
<tr>
<td style="text-align: center;">11</td>
<td style="text-align: center;">Monitor output: Mute switch</td>
<td style="text-align: center;">Mutes/unmutes the monitor 1–2 outputs. Headphone outputs are not muted. </td>
</tr>
<tr>
<td style="text-align: center;">12</td>
<td style="text-align: center;">Session File</td>
<td style="text-align: center;">Displays the current session file name. Click here to open the session browser to save or load a Volt 876 UAD Console session. See <a href="#h_01K77VBV6BK4TPTR44G7Z3W4M0">Session Files</a> for more information. </td>
</tr>
</tbody>
</table>
</figure>

</div>

## Output section details

Monitor options are controlled with the switches in the Output section.

By default, only Mono and Mute switches are displayed. When Alt monitoring is enabled, the Monitor and Alt switches are displayed.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 30%;">
![output-alt-enabled-disabled.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/57a564811a035f14e55f332e2c964c5579009e5e.png)
</figure>

*Output section with Alt disabled (left) and Alt enabled (right)*

### Alt monitoring

Volt 876 features the ability to monitor an alternate set of speakers, for quickly comparing how a mix sounds through a different set of speakers.  You can enable Alt monitoring in UAD Console software, or from your Volt 876 hardware front panel. 

### Alt monitor outputs

When Alt monitoring is enabled, you hear the alt mix on analog outputs 3–4. Connect your alternate speakers to those outputs for Alt monitoring. 

When Alt monitoring is enabled, any signals that were previously heard on outputs 3–4 are no longer heard on those output. For example, if a Cue mix is mirrored to outputs 3–4, that connection is removed. When Alt monitoring is disabled, signals previously heard on outputs 3–4 are restored.

#### To enable Alt monitoring in UAD Console:

1.  Click Settings in the Monitor column on the right side of the UAD Console window, or choose UAD Console \> Settings from the UAD Console menus.
2.  Set the Alt Count to 1. 
3.  To disable Alt monitoring, set Alt Count to 0.

#### To enable Alt monitoring on Volt 876 hardware: 

1.  On the Volt 876 front panel, press and hold the ALT button until the button flashes (approximately 2 seconds). \
    Volt 876 is now in Alt Monitor mode and any signals that were routed to outputs 3–4 are no longer routed to those outputs.
2.  When in Alt Monitor mode, press the ALT button once to toggle signal to the Alt outputs. When the ALT button is lit, the main mix is now routed to outputs 3–4 instead of the Monitor L/R outputs. When the button is unlit (toggled off) the main mix is again routed to the Monitor L/R outputs, and no signal is sent to outputs 3-4.
3.  To exit ALT mode from the Volt 876 hardware, press and hold the ALT button again until the button flashes (approximately 2 seconds). Any channels previously routed to outputs 3-4 are now restored.

### Monitor / Alt switches

The Monitor and Alt switches send the mix to either the Monitor outputs or the Alt outputs. These switches are only available when Alt monitoring is enabled.

### Mono

This switch sums the left and right channels of the stereo monitor mix into a monophonic signal. The mix is mono when the button is lit.

### Mute

This switch mutes the monitor outputs. The monitor outputs are muted when the switch is lit. The Monitor Level Indicator (the ring around the level knob) in UAD Console and on the Volt 876 hardware is red when the monitor outputs are muted.

### Level

This is the master level control for monitor outputs. It performs the same function as the MONITOR hardware knob. When the ring around the knob is RED, the monitor outputs are muted.

#### Adjusting and muting Monitor Level on macOS

You can use function keys to adjust Volt's monitor level and mute. The key combinations depend on a macOS setting. 

Check this macOS setting:

MacOS System Settings \> Keyboard \> Keyboard Shortcuts \> Function Keys \> **Use F1, F2, etc. keys as standard function keys**

If this setting is **enabled**:

- Fn + F10: Mac  mute 
- Fn + F11: Mac volume down 
- Fn + F12: Mac volume up
- Cmd + F10: Volt monitor mute
- Cmd + F11: Volt monitor volume down
- Cmd + F12: Volt monitor volume up

If this setting is **disabled**:

- F10: Mac  mute
- F11: Mac volume down
- F12: Mac volume up
- Cmd + Fn + F10: Volt monitor volume mute
- Cmd + Fn + F11: Volt monitor volume down
- Cmd + Fn + F12: Volt monitor volume up

## Session Files

You can manage your Volt 876 UAD Console configurations with session files. A session file saves your current session settings to disk. You can load a session file to restore UAD Console to a previously saved state.

**Note:** Monitor settings and hardware settings are global parameters that are not saved in session files.

The specific parameters saved in Volt 876 UAD Console session files are listed below:

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 51%" />
<col style="width: 49%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Saved in Volt 876 session file</strong></td>
<td style="text-align: center;"><strong>Not saved in Volt 876 session file</strong></td>
</tr>
<tr>
<td rowspan="5" style="text-align: center;"><p>Analog preamp settings (Vintage, 76 Comp, Inst switch, Gain, 48V, Polarity)</p>
<p>All knob, mute/solo, and fader values (pans, cues, levels)</p>
<p>Channel mute state</p>
<p>Input stereo link state</p>
<p>Loopback channel level</p></td>
<td rowspan="5" style="text-align: center;"><p>Input names</p>
<p>Monitor level</p>
<p>Clock source</p>
<p>Sample rate</p>
<p>Cue output settings</p></td>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>
</figure>

</div>

### Session File Location

By default, session files are stored in:

- Mac: Users/\[UserName\]/Documents/Universal Audio/Volt Sessions/
- Windows: C:\Users\\UserName\]\AppData\Roaming\Universal Audio\Volt Sessions

Session files can be stored anywhere on disk, but using the default location is recommended, because UAD Console always uses this location for the Session Browser and Open/Save dialogs presented by the computer's operating system.

**Note:** Session files must reside in the default location to appear in the Session Browser within UAD Console.

### Session Files Suffix

Volt 876 session files have the ".volt876" suffix. The suffix is added to session files automatically when saving to disk; however, the suffix is not displayed in the file save dialog (the suffix should not be manually typed when saving a session file).

### To save and load sessions

- Click the session name at the bottom of the Monitor Column to open the Session Browser at the left of the UAD Console window. 
- To load a session, click the session name. \
  **Note:** A warning appears if the session you are loading requires +48V phantom power to be enabled on one or more input. To load the session and enable +48V phantom power, you must click OK. Otherwise, click Cancel.  
- To save the current session, click Save, type the name (or leave it as is), and click Save.
- To rename a selected session, click Rename, type the new name and click Rename. 
- To delete a selected session, click Delete, then click Delete again.

 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![volt-876-session-browser.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/75ecfd659844190b8c43dc57d8a2569f24a927b4.png)
</figure>

*The Session Browser*

------------------------------------------------------------------------

# Control Room

The Control Room column can be accessed by clicking CTRL ROOM on the Show section of the Monitor column. The Control Room controls allow you to activate the Talkback mic and adjust talkback levels to the Cues, and select the source that is heard at the monitor 1–2 outputs. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![ctrl-room.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/931c08d0293ca308926cbce9c2d35b6d712963f5.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 5%" />
<col style="width: 31%" />
<col style="width: 64%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Overview</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">Talkback controls</td>
<td style="text-align: center;">These knobs control the talkback mic levels heard in Cues 1 & 2. The mute switches prevent talkback mic from being heard in the cues. </td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;"><a href="#h_01K77VBV6M3A1HAQQ4HW37M3CN">Dim / Talk switch</a></td>
<td style="text-align: center;">Activates the talkback mic and the Dim function. Talkback is active when the button is lit, and the monitor level is reduced to prevent feedback.</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;"><a href="#h_01K77VBV6NYYHTQYTG6BVMC8H0">Source</a></td>
<td style="text-align: center;">Selects which mix bus is heard at the monitor outputs. You can choose either Monitor, Cue 1, or Cue 2. </td>
</tr>
</tbody>
</table>
</figure>

</div>

## Talkback

Talkback is activated using the dedicated hardware TALK button on Volt 876, or the DIM / TALK button within the UAD Console Control Room strip.

Adjust the levels heard on each Cue

### Dim / Talk switch

- **Continuous (latched) talkback** – Press the switch once to latch or unlatch talkback. When latched (lit), the talkback mic signal is sent to the monitors and cues. 
- **Momentary (unlatched) talkback** – Press and hold for momentary talkback. The talkback mic sends signal while the button is held and stops sending signal when the button is released. 

### Talkback microphone

The talkback microphone is sensitive. To avoid equipment damage, do not insert any object into the mic hole, apply pressurized air into the mic hole, or use a vacuum over the mic hole.

### Dimming

When talkback is active, monitor output is lowered (dimmed) by 20 dB to allow the talkback mic to better capture the voice input instead of program material from the monitor speakers. 

## Talkback to Cues

When talkback is active (the button is latched or held), the talkback mic signal is sent to the two Cues. You can control the level of talkback signal to each Cue with the knobs on the Control Room strip, and mute the talkback signal to a Cue by pressing the mute switch.

## Source

Enable a Source button to select which mix is heard at the monitor or Alt outputs. You can choose either Monitor, Cue 1, or Cue 2. 

- To hear the main mix, choose Monitor. 
- To hear a Cue mix, choose Cue 1 or Cue 2. Note that if a Cue is set to Mix in the Cue Outputs popover, you cannot set the monitor source to that Cue, because the main mix is the default setting. A dialog with instructions appears if you try to monitor a Cue that is set to Mix.

------------------------------------------------------------------------

# Cues

You can use cues to create mixes that are different from the main monitor mix. Cues are typically used for performers that want to hear a custom mix in headphones. 

The cue mixes can also be sent (mirrored) to an available pair of outputs.

**Note:** In an expanded system, mirroring to an ADAT output pair effectively sends the cue mix to the expander unit's corresponding analog outputs. For example, routing to ADAT 3-4 on an expanded system sends audio to analog outputs 3–4 on the first expander unit.

In the image above, Cue 2 is mirrored to Line 5-6. Signals routed to Cue 2 (Headphone 2) are also duplicated to Line outputs 5-6, which can then be used to send the Cue mix out to another monitoring device. 

The cue mixes are adjusted using the two cue sends on each input strip and on the Loopback strip. All cue sends are pre-fader and pre-mute so they are not affected by adjustments to the main monitor mix, but do include Vintage and 76 compressor signals (analog inputs only).

## How do I listen to Cues?

Cues are assigned in the Cue Outputs popover, where you assign Cue mixes or the main mix to headphones, and optionally to other outputs. 

By default, the headphones receive the main mix. To hear the cue mixes in the headphones, disable the MIX button in the Cue Outputs popover. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 13%;">
![volt-876-cues-button.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/fec8e79b6ff108de540177523241b17e527b7495.png)
</figure>

### Cue popover options

To open the Cue outputs popover, click Cues in the Monitor column.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![volt-876-cue-outputs png.](UAD%20Console%20for%20Volt%20876%20Manual_assets/780740b4043ff849376a2453ffb3d8449500d6cb.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 5%" />
<col style="width: 30%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Description</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">Devices column</td>
<td style="text-align: center;">Shows the units that have assignable Cue mixes, and their headphone outputs. If there are multiple Volt 876 units, each has a different letter designation (A, B, or C).</td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;">Cue 1 routing column</td>
<td style="text-align: center;">Sets the audio source for Cue 1 (Headphone 1).</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;">Cue 2 routing column</td>
<td style="text-align: center;">Sets the audio source for Cue 2 (Headphone 2). </td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;">MIX button</td>
<td style="text-align: center;">Deselect to enable the Cue mix in headphones. The main monitor mix is heard in the headphones when the MIX button is lit, and the Cue mix is heard when the MIX button is unlit.</td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;">Mirror To menu</td>
<td style="text-align: center;">You can mirror the main mix or a cue output to an output channel pair. Click to select an output pair from the drop menu. </td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;">Cue Routings</td>
<td style="text-align: center;">The current cue routings are shown in the blue boxes. In this example, the main mix is routed to Headphone out 1, and the Cue 2 mix is routed to Headphone out 2. </td>
</tr>
</tbody>
</table>
</figure>

</div>

## Large and Small Cues

By default, cues are shown in Small view, which includes a level knob and mute switch. You can expand Cues to reveal the pan control for the cue, and to use a long-throw fader for more accurate level control.  

To expand a cue row, click the Large icon to the left of the row.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![volt-876-cue-size.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/a9cf178bda54d0fba27d232d004ca4d17555584a.png)
</figure>

## Adjusting Cue Levels

To adjust the level of the input sent to the cue mix, rotate the Cue knob. The cue level is shown while you engage the knob. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 13%;">
![volt-876-cues.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/8789573abd9983d75ee1be56264f2b0e3df76bed.png)
</figure>

You can enter a level by double-clicking the Cue knob to open the Cue volume popover, then type a dB value (-144 to +12), and click OK.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 25%;">
![volume-popover.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/b1d2fdbba693700137df1f756d6181efce11ed7e.png)
</figure>

When Cues are in Large view, drag the fader to adjust the cue level, or click the level value at the bottom of the meter to open the cue volume popover and type the level. You can also adjust the pan control in this view. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 13%;">
![volt-876-large-cue.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/e345532db0fe93d826e630e77e6a600e885a4eb0.png)
</figure>

------------------------------------------------------------------------

# USB and ADAT Mode

From this drop menu you can switch between USB interface mode and ADAT mode. The two modes are completely different configurations of Volt 876 inputs and outputs. USB mode is the standard audio interface mode, which allows you to route up to 24 analog and digital inputs through your interface. ADAT mode reconfigures the unit as a standalone mic preamp and A/D - D/A converter, or for use in an ADAT expansion system.

**Note:** To switch modes using the Volt 876 hardware front panel, a specific procedure is required. See the [Volt 876 Hardware Manual](41288385879956-Volt-876-Hardware-Manual.html).

### Active MIDI ports

On any Volt 876 that is connected via USB, the MIDI ports remain active. This includes both USB and ADAT modes, in any configuration.

**Note:** On macOS, Volt 876 appears as two different MIDI devices depending on whether the unit is in USB mode or ADAT mode. When configuring the device in Audio MIDI Setup, make sure to use the Volt 876 device that is currently active. To distinguish between the devices in Audio MIDI Setup, you can double-click each Volt 876 MIDI device and give it a unique name.

## USB mode

USB mode is the default configuration for Volt 876. In USB mode, analog inputs and digital outputs are unlinked, and can be routed independently using UAD Console and/or your DAW. USB mode is also the mode for the control unit in an ADAT expansion system. 

**USB interface mode sample rates and I/O**

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 34%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Sample Rate (kHz)</strong></td>
<td style="text-align: center;"><strong>Analog I/O</strong></td>
<td style="text-align: center;"><strong>ADAT Digital I/O</strong></td>
</tr>
<tr>
<td style="text-align: center;">44.1, 48</td>
<td style="text-align: center;">8 x 8</td>
<td style="text-align: center;">16 x 16</td>
</tr>
<tr>
<td style="text-align: center;">88.2, 96</td>
<td style="text-align: center;">8 x 8</td>
<td style="text-align: center;">8 x 8</td>
</tr>
<tr>
<td style="text-align: center;">176.4, 192</td>
<td style="text-align: center;">8 x 8</td>
<td style="text-align: center;">4 x 4</td>
</tr>
</tbody>
</table>
</figure>

</div>

<figure class="wysiwyg-image">
![volt-876-usb-mode.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/faab8129ad2fc3eac25918613f4a43f3261d844a.png)
</figure>

*Volt 876 in USB interface mode*

## ADAT mode

ADAT mode has two possible states:

1.  ADAT standalone mode
2.  ADAT expansion mode

### ADAT standalone mode

ADAT standalone mode is the default mode when you switch a Volt 876 unit to ADAT mode. In this mode:

- Volt 876 functions as a standalone mic preamp and A/D - D/A converter
- Analog inputs 1-8 are routed directly to corresponding ADAT outputs 1-8
- ADAT inputs 1-8 are routed directly to corresponding analog outputs 1-8
- Audio is not routed to the computer (there is no audio in UAD Console)
- Volt 876 does not appear as a Core Audio or ASIO device
- Loopback is disabled

### ADAT standalone mode with computer control

In ADAT standalone mode, when Volt 876 is connected to your computer via USB, the following settings can be controlled within UAD Console:

- Preamp settings
- Sample rate
- Clock source
- USB or ADAT mode

<figure class="wysiwyg-image">
![volt-876-adat-mode.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/53a7f7a95f701f9782b8267ba11b23ea11fffa6a.png)
</figure>

*Volt 876 in ADAT standalone mode in UAD Console*

### ADAT expansion mode

In ADAT mode you can configure the Volt 876 as an expander unit. In this mode, two or three Volt 876 units can be combined to provide control within UAD Console of up to 24 preamp inputs. See [ADAT expansion with multiple Volt 876 interfaces](#h_01K77VBV75YSYVZ79H4FZE51K9) for more information.

------------------------------------------------------------------------

# ADAT Expansion with Multiple Volt 876 Interfaces

You can expand your Volt 876 system to include two or three Volt 876 interfaces for 16 or 24 analog inputs (at 44.1 kHz and 48 kHz). In this configuration, one Volt 876 is set as the USB interface unit, and the other Volt 876 units are set as ADAT expander units. 

**Important:** ADAT expansion mode requires two or more Volt 876 units connected to your computer via USB and to each other via optical cables. ADAT expansion mode also requires the UAD Console app. ADAT expansion mode cannot be configured using Volt 876 hardware buttons. 

In this configuration, the ADAT outputs from the ADAT expander units are connected to the ADAT inputs on the USB interface unit, and vice versa. 

Each Volt 876 must also be connected separately to the host computer via USB. You can then control all analog preamp settings for the ADAT expander units within UAD Console, and all audio from the expander units is available in the UAD console monitor and cue mixes. 

**Caution:** To prevent feedback, before you switch a device between USB mode and ADAT mode, make sure all microphones are muted.

## ADAT Expansion and sample rates

For sample rates higher than 48 kHz, the maximum number of expander channels is eight, and only one expander unit is supported. 

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 34%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Sample rate</strong></td>
<td style="text-align: center;"><strong>Available preamp channels</strong></td>
<td style="text-align: center;"><strong>Expander units</strong></td>
</tr>
<tr>
<td style="text-align: center;">44.1 kHz / 48 kHz</td>
<td style="text-align: center;"><p>8 (one expander unit)</p>
<p>16 (two expander units)</p></td>
<td style="text-align: center;">One or two</td>
</tr>
<tr>
<td style="text-align: center;">88.2 kHz / 96 kHz</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">One</td>
</tr>
<tr>
<td style="text-align: center;">176.4 kHz / 192 kHz</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">One</td>
</tr>
</tbody>
</table>
</figure>

</div>

## Cabling Volt 876 hardware for ADAT expansion (44.1 kHz / 48 kHz)

1.  Power off all Volt 876 hardware units.
2.  Connect the ADAT expander units to the USB interface unit via optical cables, as shown in the image and table below. 
3.  Connect the USB interface unit and ADAT expander units to the computer via USB. You can use a USB hub to make these connections.
4.  After making the connections, power on the Volt 876 hardware units.

### Optical & USB Connections for Volt 876 ADAT expansion (44.1 kHz / 48 kHz) **![expanded-system.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/689fc7b115143cff6e4659d43c0b694d80d8466f.png)**

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 34%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>USB interface unit</strong></td>
<td style="text-align: center;"><strong>ADAT expander unit 1</strong></td>
<td style="text-align: center;"><strong>ADAT expander unit 2</strong></td>
</tr>
<tr>
<td style="text-align: center;">Optical In 1</td>
<td style="text-align: center;">Optical Out 1</td>
<td style="text-align: center;"> </td>
</tr>
<tr>
<td style="text-align: center;">Optical In 2</td>
<td style="text-align: center;"> </td>
<td style="text-align: center;">Optical Out 1</td>
</tr>
<tr>
<td style="text-align: center;">Optical Out 1</td>
<td style="text-align: center;">Optical In 1</td>
<td style="text-align: center;"> </td>
</tr>
<tr>
<td style="text-align: center;">Optical Out 2</td>
<td style="text-align: center;"> </td>
<td style="text-align: center;">Optical In 1</td>
</tr>
</tbody>
</table>
</figure>

</div>

## Cabling Volt 876 hardware for ADAT expansion (88.2 kHz – 192 kHz)

1.  Power off all Volt 876 hardware units.
2.  Connect the ADAT expander unit to the USB interface unit via optical cables, as shown in the image and table below. 
3.  Connect the USB interface unit and ADAT expander unit to the computer via USB. You can use a USB hub to make these connections.
4.  After making the connections, power on the Volt 876 hardware units.

### Optical & USB Connections for Volt 876 ADAT expansion (88.2 kHz – 192 kHz)

<figure class="wysiwyg-image">
![expanded-system-high-sr.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/60b588bc97df74863c68fc4216f2afcba8232a0d.png)
</figure>

** **

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 46%" />
<col style="width: 54%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>USB interface unit</strong></td>
<td style="text-align: center;"><strong>ADAT expander unit</strong></td>
</tr>
<tr>
<td style="text-align: center;">Optical In 1</td>
<td style="text-align: center;">Optical Out 1</td>
</tr>
<tr>
<td style="text-align: center;">Optical In 2</td>
<td style="text-align: center;">Optical Out 2</td>
</tr>
<tr>
<td style="text-align: center;">Optical Out 1</td>
<td style="text-align: center;">Optical In 1</td>
</tr>
<tr>
<td style="text-align: center;">Optical Out 2</td>
<td style="text-align: center;">Optical In 2</td>
</tr>
</tbody>
</table>
</figure>

</div>

 

## Configuring UAD Console for ADAT expansion

1.  Open UAD Console.
2.  Open UAD Console settings by clicking Settings in the Monitor column of the UAD Console window (right side), or choosing UAD Console \> Settings from the UAD Console menus.
3.  From the Devices list, select the Volt 876 unit that you want to set as an ADAT expander unit, and select ADAT from its Mode menu. Repeat for the third unit (if applicable).
4.  From the Devices list, select the Volt 876 unit that is set to USB mode. This is the USB interface device that carries all computer audio I/O.
5.  From the ADAT 1-8 menu (44.1 kHz – 96 kHz), select the ADAT expander unit connected to Optical in 1 and optical out 1 on the Usb interface unit. This becomes ADAT expander unit 1.\
    At 176.4 kHz or 192 kHz the menu label is ADAT 1-4.\
    ![volt-876-selecting-adat-interface.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/da632835dba3d0d774c99e814213a919ae7e5ed8.png)\
       
6.  If using three Volt 876 units, from the ADAT 9-16 menu, select the second ADAT expander unit. 
7.  Set the Volt 876 unit clock sources.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 100%;">
![volt-expanded-two-units-settings.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/dbe6e2fd4b5629b21d2e11222ca268a1d9e5d6cf.png)
</figure>

**Note:** Settings shown are for 44.1 kHz and 48 kHz sample rate operation. At higher sample rates, labels and inputs appear differently. At 88.2 kHz and 96 kHz, only one expander unit can be selected, and the  expander unit is listed as ADAT 1–8. At 176.4 kHz and 192 kHz, only one expander unit can be selected, and the expander unit is listed as ADAT 1–4.

### UAD Console with Volt 876 ADAT expansion

After configuring Volt 876 ADAT expansion with one or two additional Volt 876 units, the preamps from the ADAT expander units appear in UAD Console. These inputs are adjustable from UAD Console or from the hardware, in addition to the inputs on the USB interface unit. All audio from the USB interface unit and the ADAT expander units is available in UAD Console. 

**Note:** Linking ADAT inputs on ADAT expander units is not supported.  

<figure class="wysiwyg-image">
![volt-876-usb-mode-16-channels.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/4c9c054b5fe002f3076d7015f5d20a3f00081347.png)
</figure>

*UAD Console with one Volt 876 showing 16 inputs (no expander unit)*

<figure class="wysiwyg-image">
![volt-876-expanded-16-channels.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/65fcb6f9449ee44220760b4735db187e222b5ccb.png)
</figure>

*UAD Console with one ADAT expander unit, showing 16 preamp inputs*

------------------------------------------------------------------------

# ADAT Expansion with Other Digital Gear

You can expand your Volt 876 system to include one or two other ADAT or S/PDIF digital devices (including non-Volt interfaces), to expand your inputs to as many as 24 inputs (at 44.1 kHz and 48 kHz). In this configuration, you route the digital optical outputs of other devices into the Volt 876 digital optical inputs. The audio channels appear in UAD Console, routed through the ADAT channels. 

- **Input levels:** There is no adjustment available in UAD Console for digital input levels from non-Volt devices. You must set the levels on your digital outboard gear. 
- **Clocking:** If your gear is connected only from outputs to the inputs via the TOSLINK connections, the outboard gear must be the digital clock source, so you should set the clock source in UAD Console to ADAT.

<figure class="wysiwyg-image">
![volt-876-external-adat.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/15068b4ed7b66f357561af18a7306b4a0adda962.png)
</figure>

*Example connections for digital outboard gear with Volt 876*

## Cabling Volt 876 hardware for ADAT expansion with digital outboard gear

1.  Power off all hardware units.
2.  Connect the ADAT expander units to the Volt 876 via optical cables, as shown in the image above. 
3.  Connect the Volt 876 interface to the computer via USB.
4.  After making the connections, power on all hardware units. 

ADAT or S/PDIF inputs appear in UAD Console. You can assign these tracks to Cue mixes, and adjust monitor mix levels, solo, and mute. You cannot adjust input levels for external digital gear inputs. You must make those adjustments on the gear. ADAT or S/PDIF channel availability depends on the system sample rate. See [Digital audio channels and sample rates](#h_01K77VBV5AG1NV5EDD6TWVSJ91) for details. 

------------------------------------------------------------------------

# UAD Console for Volt 876 Settings

To access settings in UAD Console for Volt 876:

1.  Click Settings in the Monitor column at the right side of the UAD Console window, or 
2.  Choose UAD Console \> Settings from the UAD Console menus.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![volt-876-settings.png](UAD%20Console%20for%20Volt%20876%20Manual_assets/b7c61048facb4868db33b0417670eb03eaba14e5.png)
</figure>

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 5%" />
<col style="width: 23%" />
<col style="width: 72%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>#</strong></td>
<td style="text-align: center;"><strong>Feature</strong></td>
<td style="text-align: center;"><strong>Description</strong></td>
</tr>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">Device Type</td>
<td style="text-align: center;">Select the Device type here (Apollo or Volt). This option is visible only if Apollo software is installed.</td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;">Device Name</td>
<td style="text-align: center;">You can rename your Volt 876 here. Type a name and press Enter to rename.</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;">Identify</td>
<td style="text-align: center;">To identify the hardware, press Identify. This flashes all lights on the front of the hardware. Identify is especially helpful when multiple units are connected.</td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;">Mode</td>
<td style="text-align: center;">You can switch the unit between USB and ADAT modes here. </td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;">ADAT 1</td>
<td style="text-align: center;">When combining two Volt 876 units, select the ADAT expander unit here. The expander unit must be set to ADAT mode. </td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;">ADAT 2</td>
<td style="text-align: center;">When combining three Volt 876 units, select the second ADAT expander unit here. The second expander unit must be set to ADAT mode.</td>
</tr>
<tr>
<td style="text-align: center;">7</td>
<td style="text-align: center;">Digital Input</td>
<td style="text-align: center;">Choose ADAT or S/PDIF depending on the digital input format you want to use.</td>
</tr>
<tr>
<td style="text-align: center;">8</td>
<td style="text-align: center;">Digital Output</td>
<td style="text-align: center;">Choose ADAT or S/PDIF depending on the digital output format you want to use.</td>
</tr>
<tr>
<td style="text-align: center;">9</td>
<td style="text-align: center;">Alt Count</td>
<td style="text-align: center;">Choose 1 to define an ALT monitoring option on analog outputs 3–4. Note that this is the same as defining ALT outputs using the <a href="#h_01K77VBV690HPZPWPC9RAMFYJZ">hardware ALT procedure</a>. </td>
</tr>
<tr>
<td style="text-align: center;">10</td>
<td style="text-align: center;"><a href="#h_01K77VBV4JW35G14QAWX0VJ0G7">Sample Rate</a></td>
<td style="text-align: center;">Sets the sample rate for the hardware. </td>
</tr>
<tr>
<td style="text-align: center;">11</td>
<td style="text-align: center;"><a href="#h_01K77VBV4M7E7ZQZFZTQVS9MQF">Clock Source</a></td>
<td style="text-align: center;">Sets the digital clock source for the hardware.</td>
</tr>
</tbody>
</table>
</figure>

 

<span class="wysiwyg-font-size-small">v260224</span>

</div>

