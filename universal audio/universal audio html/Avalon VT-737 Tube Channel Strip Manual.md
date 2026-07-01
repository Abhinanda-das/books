---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/18741383023892-Avalon-VT-737-Tube-Channel-Strip-Manual.html'
converted_at: 2026-05-31T13:44:46Z
tool: htmlq+pandoc
title: 'Avalon VT-737 Tube Channel Strip Manual'
word_count: 3810
---

# Avalon VT-737 Tube Channel Strip Manual


<div class="callout callout--info">

The DSP UAD-2 and Native UADx plug-ins have different names. The UADx plug-in title is Avalon VT-737 Channel Strip, and the UAD-2 title is Avalon VT-737sp.

</div>

## In this article

- [Operational Overview](#h_01HDM1ZSE5W2DSB7ZGRJYJBJHC)
- [Avalon VT-737sp Tube Channel Strip Controls](#h_01HDM1ZSE60XAMZZVZ8FPP7BKF)
- [Preamp Controls](#h_01HDM1ZSE6FXMNGJYD603G4BP6)
- [Compressor Knobs](#h_01HDM1ZSE65YN0P0JK1BCK3EBQ)
- [Compressor Switches](#h_01HDM1ZSE646C8VAZVCHXX9TJ2)
- [EQ Knobs](#h_01HDM1ZSE6QWFX326D659R0D1R)
- [EQ Switches](#h_01HDM1ZSE623SS5BVEFNC1ENY1)

## Get the larger-than-life sound of pop, hip-hop, and R&B.

The dominant player in chart-topping productions, Avalon's flagship VT-737 channel strip is the best-selling standalone channel strip ever made. From Jay-Z and Dr. Dre, to Babyface and Beyonce, the Avalon VT-737 Tube Channel Strip plug-in delivers the same consistently polished results, with radio-ready gloss and detail.

- Track and mix through an exacting emulation of the Avalon VT‑737 analog channel strip

- Get the full character of the original hardware’s tube mic preamp with Unison technology

- Add legendary Avalon gloss and presence to bass, vocals, voice‑over, and more

- Sculpt your sources with a vocal‑flattering optical compressor

- Tweak sounds with four-band EQ and add high‑end detail with 32k "air" band

- Mix with artist presets from Eric J Dubowsky, (Flume, Odesza), Hector Delgado (A\$AP Rocky, Lana Del Rey), Michael Brauer (Coldplay, My Morning Jacket), and more

## Capturing the sound of modern music

By artfully capturing our "golden unit" Avalon's flagship VT-737 hardware's class-A tube amplifier section, LED-style optical compression, and discrete four-band EQ, you can give your tracks the signature Avalon sound heard on thousands of chart-topping hits.

## Record Vocals and Bass “Through” a Hit-Making Tube Preamp with Apollo

UA’s groundbreaking Unison technology lets you track in realtime through the Avalon VT-737 Channel Strip plug-in using your Apollo, giving you the chart-topping sound of the original hardware’s line/mic preamp impedance, gain stage “sweet spots,” and exact circuit behaviors.

## Experience Versatile Compression on Vocals and More

Excelling on vocals, bass, acoustic guitar, and voice-over work, the VT-737 plug-in's dynamics section gives your tracks the hardware's gentle touch, rather than adding squash or crunch. This transparent compression is perfect for "stacking" the compressor again at mixdown, so you can control a vocal in a dense mix.

## Fine-Tune Your Mixes with Bold EQ

The Avalon VT-737 plug-in's four-band EQ, gives your vocals a lively presence and sophistication, placing them front-and-center in any mix. Like the hardware, the EQ can be placed before or after the compressor, and the mid bands can be engaged as sidechain filters for laser-focused compression. And with the 32k high frequency "air band," you can add delicate shimmer to everything from strings to background vocals to acoustic guitars.

![Avalon_VT_737_Silver.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/c96288f2c562d9647ae2d4a597f509aa18baf12e.png) ![Avalon_VT_737_Black.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/b08f8521b8e7787d187fbb549346f66bfc1956b5.png)

*Avalon VT-737sp showing the silver and black panel views*

------------------------------------------------------------------------

# Operational Overview

This section provides a general overview of Avalon VT-737sp Channel Strip operational concepts. For specific details about individual controls, see Avalon VT-737sp Channel Strip Controls later in this chapter.

**Tip:** For VT-737sp application notes from Avalon, see the end of this chapter.

## Signal flow

The Avalon VT-737sp combines a transformer-coupled, dual vacuum tube preamplifier with a tube opto-compressor and a high-voltage, discrete Class A four-band parametric equalizer.

A simplified version of the signal flow within the plug-in is shown in the diagram below. By default, signal enters at the first tube gain stage which outputs to the high pass filter, then to the second tube gain stage, compressor, EQ, and output circuitry. The EQ module can be routed before the dynamics module as needed, by engaging the EQ\>COMP option. Engaging the SC\<MIDS option causes that the EQ mid bands to act solely on the dynamics sidechain signal, and removes the midrange EQ from the audio signal path.

![avalon-vt-737sp-flow.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/809f229523c8c0addc1057528247d3df6ebcaba4.png)

*Simplified signal flow within Avalon VT-737sp*

## Unison™ integration

The UAD Avalon VT-737sp Channel Strip plug-in features Unison technology for integration with the mic preamp hardware in Universal Audio's Apollo and Arrow audio interfaces. With Unison interfaces, the ultra-transparent mic preamps inherit all of the unique sonics, input characteristics, and features of emulated preamps.

**Note:** Unison is active only when the plug-in is placed in the dedicated UNISON insert within the Apollo/Arrow Console application. For complete details, see the Unison chapter within the Apollo Software Manual or Arrow Manual.

With Unison, the hardware preamp adapts to the modeled preamp's physical input impedance. Combined with UA's transparent analog amplification, this provides the plug-in's full gain and tone range from clean to clipped — with broad, musical sweet spots in-between.

### Realistic tandem control

Unison facilitates seamless interactive control of plug-in settings using both the digitally-controlled panel hardware on the UA audio interface and the graphical UAD plug-in interface. All equivalent preamp controls (gain, cut filter, polarity, pad) are mirrored and bidirectional. The preamp controls respond to adjustments with precisely the same interplay behavior as the modeled preamp, including gain levels and clipping points.

### Hardware input impedance

All Unison mic preamps feature variable input impedance in the analog hardware that can be physically changed by Unison-enabled UAD plug-ins for physical, microphone-to-preamp resistive interaction. This impedance switching enables Unison preamps to match the input impedance of the emulated hardware, which can significantly impact the sound of a microphone. Because the electrical loading occurs on input, prior to A/D conversion, the realism is faithful to the emulated hardware preamp.

### Tactile gain staging

The hardware preamp knob on the UA audio interface can independently adjust the gain and level parameters available within the Unison plug-in via Gain Stage Mode. The gain stage being adjusted can be remotely switched via the interface hardware, so the gain levels and their associated colorations can be tuned from the hardware knob for precise physical tactile control, all without using the Unison plug-in's software interface.

|  |  |  |
|----|----|----|
| ![avalon-gsm-1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/ef7b01c7900a54ec32f2ae28d0b3307e1db8d505.png) | ![avalon-gsm-3.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/8369038216ad6b37d167d4cb3c64493703832cfb.png) | ![avalon-gsm-2.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/92cd595cf0be9a633e042b3c8d5df4c7388e3916.png) |

*The three outlined gain controls as they appear when in Unison Gain Stage Mode*

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

**Tip:** Avalon's VT-737sp settings from the original hardware manual, which have been recreated as plug-in presets, are also included.

|                 |             |                |                |
|-----------------|-------------|----------------|----------------|
| Eric J Dubowsky | Ian Boxill  | Michael Brauer | Mike Larson    |
| Hector Delgado  | Ivan Barias | Mike Dean      | Richard Robson |

*Artists that have provided presets for the Avalon VT-737sp Tube Channel Strip*

## Alternate panel view

The UAD Avalon VT-737sp plug-in can be displayed in either Silver or Black panel views. To toggle between the two display modes, click the VT-737sp logo on the left side of the interface.

|  |  |
|----|----|
| ![avalon-panel-logo-black.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/044c43d74cd3b528187e33311899697a94579af1.png) | ![avalon-panel-logo-silver.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/9e3f3e8182b0b448c31b6cdb43dcdda8036c008b.png) |

*Click the logo to display the alternate panel view*

## Application Notes from Avalon

Detailed VT-737sp application notes are provided in Avalon's original hardware operation manual, which is available at Avalon's website:

- [www.avalondesign.com](http://www.avalondesign.com)

------------------------------------------------------------------------

# Avalon VT-737sp Tube Channel Strip Controls

## About Unison Interactions (Apollo hardware only)

Some control descriptions begin with the Unison Interaction heading and include the Unison icon at left. Descriptions in these sections apply only when the plug-in is placed in the dedicated UNISON insert on an Apollo/Arrow preamp channel within the Console application. When the plug-in is used in standard (non-Unison) inserts in Console, or within a DAW, these descriptions do not apply.

**Note:** For complete details, see the Unison chapter within the Apollo Software Manual or Arrow Manual.

------------------------------------------------------------------------

# Preamp Controls

## Preamp Gain

This continuously variable rotary control adjusts the amount of gain applied to the input signal. Increasing the gain will drive the circuit harder to get more tube tone into the preamp. You can use this control at minimum and maximum levels for different sounds and colors.

**Tip:** Click the "0" text label to return the control to the zero position.

The available preamp gain range depends on INPUT SELECT setting, as follows.

- When set to MIC, the gain range is 0 dB to +45 dB.

- When set to LINE, the gain range is -28 dB to +9 dB.

- When Hi-Z input is connected (Unison mode only), the gain range is -30 dB to +10 dB.

**Note:** The knob silkscreen labels are for general gain guidelines only. The knob values are not calibrated.

 

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="width: 59.75px">![unison-icon1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 617.25px"><h4 id="h_01HDME8MHS1BVAPWKFFKTBZQNB">Apollo Unison Interactions</h4></td>
</tr>
<tr>
<td colspan="2" style="width: 688px"><h4 id="h_01HDM1ZSE6GSJ4N4N4QZBQAY11">Input Impedance</h4>
<p>Hardware input impedances of the preamp are automatically switched to match the original hardware for physical, microphone-to-preamp resistive interaction.</p>
<h4 id="h_01HDM1ZSE6YHY37BY1YCM9N1WN">Hardware Control Mirroring</h4>
<p>Software and hardware adjustment of this control is mirrored. The setting can be changed within the plug-in interface, with Console's preamp gain knob, or with the main hardware level knob on the UA audio interface.</p>
<h4 id="h_01HDM1ZSE68V41084H1EZYRDTH">Gain Stage Mode 1</h4>
<p>When the plug-in is placed in the dedicated Unison insert within the Console application and the channel is in Unison Gain Stage Mode, the hardware PREAMP knob on the UA audio interface can be used to adjust Preamp Gain. In this state, an orange outline surrounds this parameter, indicating it is available for hardware control.</p>
<p><strong>Tip:</strong> For details on how to enter and exit Gain Stage Mode, see the Unison chapter within the Apollo Software Manual or Arrow Manual.</p></td>
</tr>
</tbody>
</table>

 

## Input Select

Input Select switches the plug-in between Line and Mic input. To toggle the setting, click the LINE or MIC text labels, or rotate the control.

**Important:** Use caution when switching to Line from Mic, as signal output levels can increase significantly (as they would with a hardware preamp).

This control interacts with the Preamp Gain control. The gain range and amount of available gain changes when the Input Select setting is changed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="width: 56.8594px">![unison-icon1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 620.141px"><h4 id="h_01HDMETJPXWP0XTDJ7WFJT6AM7">Apollo Unison Interactions</h4></td>
</tr>
<tr>
<td colspan="2" style="width: 688px"><h4 id="h_01HDM1ZSE6Y3B8041F7GZEWY51">Hardware Control Mirroring</h4>
<p>Software and hardware adjustment of this control is mirrored. The setting can be changed within the plug-in interface, with Console's preamp input controls, or with the hardware INPUT button on the UA audio interface.</p>
<h4 id="h_01HDM1ZSE611M90R62D9Y6682T">Automatic Hi-Z Selection</h4>
<p>When a ¼" unbalanced (TS tip-sleeve) instrument cable is connected to the Apollo/Arrow channel's Hi-Z input, Input Select is locked to the Mic position and the available gain range changes to -30 dB to +10 dB.</p></td>
</tr>
</tbody>
</table>

## High Gain

This switch boosts the overall gain of the preamp. High Gain mode is active when the button is illuminated red. Click the button or its text label to toggle the state.

When Input Select is set to LINE, preamp gain is increased by +8 dB. When Input Select is set to MIC, preamp gain is increased by +18 dB. This extra signal boost can be used in conjunction with the OUTPUT control to overdrive the vacuum tube stages. Various effects, from soft tube overdrive to all out distortion, can be achieved with the High Gain boost.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="width: 56.8828px">![unison-icon1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 620.117px"><h4 id="h_01HDMEX9H25XWY668GEYHF5EG4">Apollo Unison Interaction</h4></td>
</tr>
<tr>
<td colspan="2" style="width: 688px"><h4 id="h_01HDM1ZSE639N3CSD2E54K39V6">Gain Stage Mode 2</h4>
<p>When the channel is in Unison Gain Stage Mode, the hardware PREAMP knob on the UA audio interface can be used to adjust High Gain. In this state, an amber outline surrounds this parameter, indicating it is available for hardware control.</p>
<p><strong>Tip:</strong> For details on how to enter and exit Gain Stage Mode, see the Unison chapter within the Apollo Software Manual or Arrow Manual.</p></td>
</tr>
</tbody>
</table>

## Pad

When Pad is enabled, the input signal level is attenuated (lowered) by 20 dB. The pad is engaged when the switch is illuminated red. Click the button or its text label to toggle the state.

Pad is available with the plug-in only; the feature is not available on the original hardware. Pad can be used to reduce signal levels when undesirable overload distortion is present at low preamp gain levels.

**Note:** Pad is unavailable when Input Select is set to LINE.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="width: 50.1094px">![unison-icon1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 626.891px"><h4 id="h_01HDMF2K01FBJFMF6KXYJJH7GT">Apollo Unison Interactions</h4></td>
</tr>
<tr>
<td colspan="2" style="width: 688px"><h4 id="h_01HDM1ZSE6KT699DKR100HAKS7">Hardware Control Mirroring</h4>
<p>Software and hardware adjustment of this control is mirrored. The setting can be changed within the plug-in interface, with Console's preamp pad control, or with the hardware PAD button on the UA audio interface.</p>
<h4 id="h_01HDM1ZSE69ZYFC83SNRR37YYR">Hi-Z Connection</h4>
<p>When a ¼" unbalanced (TS tip-sleeve) instrument cable is connected to the Apollo/Arrow channel's Hi-Z input, the pad is automatically disengaged. Pad is unavailable with Hi-Z input.</p></td>
</tr>
</tbody>
</table>

## Filter

This switch enables the 6 dB per octave high-pass input filter. The input filter is enabled when the switch is illuminated red. Click the button or its text label to toggle the state.

**Note:** The cutoff frequency of the input filter is adjusted with the High Pass Frequency control.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td>![unison-icon1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td><h4 id="h_01HDMF2K01F37HWQXX9A0GW6QJ">Apollo Unison Interaction</h4></td>
</tr>
<tr>
<td colspan="2"><h4 id="h_01HDM1ZSE6735CKGXBTY5SZ5K6">Hardware Control Mirroring</h4>
<p>Software and hardware adjustment of this control is mirrored. The setting can be changed within the plug-in interface, with Console's preamp filter control, or with the hardware filter button on the UA audio interface.</p></td>
</tr>
</tbody>
</table>

## High Pass Frequency

This knob controls the continuously variable frequency of the high-pass input filter. The available range is 30 Hz to 140 Hz.

**Note:** This control has no effect unless the Filter switch is enabled.

## Phase

This button inverts the polarity of the incoming signal. Phase is inverted by 180º when the switch is illuminated red. Leave the button off (unlit) for normal polarity. Click the button or its text label to toggle the state.

When more than one microphone is used to record a single source, inverting the polarity can help reduce phase cancellations. Phase can also be used for creative effects.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="width: 52.0625px">![unison-icon1.png](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 624.938px"><h4 id="h_01HDMF2K01KEWF7FS0M5T6JV2Y">Apollo Unison Interaction</h4></td>
</tr>
<tr>
<td colspan="2" style="width: 688px"><h4 id="h_01HDM1ZSE61GGR3Z693RRA6KSV">Hardware Control Mirroring</h4>
<p>Software and hardware adjustment of this control is mirrored. The setting can be changed within the plug-in interface, with Console's preamp polarity control, or with the hardware polarity button (Ø) on the UA audio interface.</p></td>
</tr>
</tbody>
</table>

 

------------------------------------------------------------------------

# Compressor Knobs

**Note:** The four Compressor knobs are continuously variable.

## Threshold

Threshold determines the signal level at which compression is applied to the input signal. Signals above the threshold are compressed, while signals below the threshold are not compressed.

Rotate THRESHOLD counter-clockwise to lower the threshold and increase compression. The available threshold range is -30 dB to +20 dB.

**Tip:** Click the "0" text label to return to the zero position.

## Compression (Ratio)

This control determines the compression ratio to be applied in the gain reduction circuit. The available compression ratio range is 1:1 (no compression) to 20:1.

For example, a value of 2 (expressed as a 2:1 ratio) reduces the signal above the threshold by half, with an input signal of 20 dB being attenuated to 10 dB.

**Note:** Signals must exceed the Threshold value before they are attenuated by the Compression amount.

## Attack

ATTACK sets the amount of time that must elapse after the input signal reaches the THRESHOLD level before compression is applied. The available range is approximately 2 milliseconds to 200 milliseconds.

**Tip:** When the Comp X4 switch is engaged, the available attack range is four times faster.

The faster the attack, the more rapidly compression is applied to signals above the threshold. Slower attacks allow a signal's attack transients (for example, the pluck of a string) to pass without compression, which can produce a punchier sound.

## Release

RELEASE sets the amount of time that must elapse after the input signal drops below the THRESHOLD before compression processing is ceased. The available range is approximately 100 milliseconds to 5 seconds.

------------------------------------------------------------------------

# Compressor Switches

**Note:** Compressor switch functions are active when the switch is lit. Click the switch or its text label to toggle the latched on/off state.

## EQ \> Comp

When the PRE switch is lit, the EQ circuit is routed before the compressor circuit, increasing tonal option flexibility.

## Meter

When the GR switch is lit, the VU meter displays the amount of gain reduction occurring in the compression circuit. When unlit, the VU meter displays the output level.

## Comp In

When the IN switch is lit, the compressor is active. When unlit, dynamics processing is disabled.

**Tip:** If DSP LoadLock is disabled in the UAD Meter & Control Panel, UAD DSP load is reduced when the compressor is disabled.

## SC (Sidechain) Link

When the plug-in is used in a stereo-input configuration and the IN switch is lit, the compressor sidechain for both channels (left & right) are linked, and both channels are always compressed in equal amounts.

Linking the sidechains maintains the stereo imaging at the input by preventing left-right shifting at the output when one channel has higher signal peaks compared to the other channel.

When this switch is unlit in a stereo-in configuration, the amount of compression occurring is completely independent in both channels. In this case, If one channel has higher signal peaks than the other channel, the left-right imaging may shift at the output.

**Note:** When used in a mono-in configuration, this switch cannot be enabled.

## Comp X4

The Comp X4 switch changes the response of the compressor's Attack control. This switch, which is not available on the original hardware, increases the available attack time speed by a factor of four. This feature improves dynamic control across a broader range of sources, including transient-rich material such as drums.

When lit, the available attack time range is faster. When unlit, the Attack knob response matches the original hardware.

------------------------------------------------------------------------

# EQ Knobs

## Bass Gain

This continuous knob adjusts the amplitude of the passive low shelving band. Up to ±24 dB of boost or attenuation is available.

**Tip:** Click the "0" text label to return the control to its center position.

## Bass Frequency

This stepped knob sets the edge frequency to be boosted or attenuated by the Bass Gain knob. Available bass frequency values are (in Hz): 15, 30, 60, and 150.

**Tip:** Click the knob's text labels to select a frequency value.

## Low Mid Gain

This continuous knob adjusts the amplitude of the low midrange band. Up to ±16 dB of continuous boost or attenuation is available.

**Tip:** Click the "0" text label to return the control to its center position.

## Low Mid Frequency

This continuous knob sets the center frequency for the low midrange band. The available range is normally 35 Hz to 450 Hz. When the band's X10 switch is engaged, the available range is 350 Hz to 4.5 kHz.

**Tip:** Click the knob's text labels to select a frequency value.

## High Mid Gain

This continuous knob adjusts the amplitude of the high midrange band. Up to ±16 dB of continuous boost or attenuation is available.

**Tip:** Click the "0" text label to return the control to its center position.

## High Mid Frequency

This continuous knob sets the center frequency for the high midrange band. The available range is normally 220 Hz to 2.8 kHz. When the band's X10 switch is engaged, the available range is 2.2 kHz to 28 kHz.

**Tip:** Click the knob's text labels to select a frequency value.

## Treble Gain

This continuous knob adjusts the amplitude of the passive high shelving band. Up to ±20 dB of boost or attenuation is available.

**Tip:** Click the "0" text label to return the control to its center position.

## Treble Frequency

This stepped knob sets the edge frequency to be boosted or attenuated by the Treble Gain knob. Available treble frequency values are (in kHz): 10, 15, 20, and 32.

**Tip:** Click the knob's text labels to select a frequency value.

------------------------------------------------------------------------

# EQ Switches

**Note:** EQ switch functions are active when the switch is lit. Click the switch or its text label to toggle the latched on/off state.

## Hi Q

The Hi Q switch sets the bandwidth of frequencies surrounding the midrange band's center frequency. When unlit, the Q value is 0.2 and bandwidth is broader, affecting a wider frequency range.

When lit, the Q value is 0.85 and bandwidth is narrower, for more precise control.

**Note:** Each midrange band (Low and High) has its own Q switch.

## Frequency X10

The X10 switch multiplies the center frequency of the midrange band by a factor of ten, extending the available range of frequencies for the band.

When lit, the frequency set by the band's knob is multiplied by ten. When unlit, the frequency indicated by the knob pointer's text label is used.

**Note:** Each midrange band (Low and High) has its own X10 switch.

## Sidechain EQ (SC \< MIDS)

This switch enables the sidechain EQ function. When lit, the low and high midrange EQ bands are removed from the audio path, and are instead routed to control ("key") the compressor sidechain signal.

Sidechain EQ is typically used for vocal de-essing and similar frequency-selective compression techniques.

**Tip:** Sidechain EQ can be active even if the main EQ In switch is disabled.

## Equalizer In

When this IN switch is lit, the EQ circuit is active. When unlit, the audio signal bypasses the EQ circuit. Note that the sidechain EQ (SC\<MIDS switch) can be used even if the EQUALIZER switch is disengaged.

**Tip:** When the equalizer is disabled, processor usage is reduced. With the UAD-2 plug-in, if UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

## Output

This continuous knob adjusts the final output level. The available gain range is -40 dB to +10 dB.

**Tip:** Click the "0" text label to return the control to its center position.

## VU Meter

The VU Meter displays the main output level when the compressor's METER switch is unlit. When the compressor's METER switch is engaged, the VU Meter displays the amount of gain reduction occurring in the compressor circuit.

**Tip:** The VU Meter's needle is speed sensitive when measuring gain reduction, which can help when setting the compressor's ATTACK and RELEASE controls.

## Power

Use the I/O rocker switch to bypass plug-in processing and conserve UAD DSP. Bypass is useful for comparing the processed signal to the original, unprocessed signal.

**Tip:** The red power lamp below the VU Meter also functions as a power switch.

 

![Avalon_Hero.jpg](Avalon%20VT-737%20Tube%20Channel%20Strip%20Manual_assets/d18c4c910b18e5f9cd7212109eaf85ff787c2a98.jpg)

*Avalon VT-737sp original hardware*

All references to the Avalon VT-737sp and all use of Avalon Design's trademarks are being made with written permission from Avalon Industries, Inc. Special thanks to Devin Powers, Tom Fritze, and Anthony Morro.

