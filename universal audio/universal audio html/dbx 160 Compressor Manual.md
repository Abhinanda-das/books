---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/18741620620692-dbx-160-Compressor-Manual.html'
converted_at: 2026-05-31T13:44:46Z
tool: htmlq+pandoc
title: 'dbx 160 Compressor Manual'
word_count: 1053
---

# dbx 160 Compressor Manual


<div class="callout callout--info">

The DSP UAD-2 and Native UADx plug-ins have different names. The UADx plug-in title is dbx 160 Compressor, and the UAD-2 title is dbx 160.

</div>

## Experience the quirky VCA compression of the vintage hardware.

The dbx 160 Compressor/Limiter plug-in is a fully licensed, faithful emulation of the legendary studio hardware, capturing the quirky sonics of its colorful VCA compression along with added controls for modern workflows.

Capturing the signature quickness and quirky circuit-level nuances of a sourced "golden unit," now with added controls for modern workflows, the UAD dbx 160 plug-in boasts sonic authenticity all its own, bringing classic solid-state VCA compression into a new age.

- Add a unique voice and flavor to your compressor toolkit with the first solid-state VCA compressor ever made

- Harness fat compression textures on bass guitar, drum buses, synths, and more

- Give acoustic guitars and snare drums in-your-face "thwack" 

- Create with Dry/Wet mix control for quick parallel compression and Sidechain Filter for reduced low-frequency pumping 

## Add Versatile VCA Compression to your Tracks

Whether you’re using it on synths, bass guitar, or a drum bus, the dbx 160 plug-in emulates the original hardware’s grabby, low-end glue and old-school character, full of the same unique nonlinearities that make it a must-have for any engineer’s compressor toolkit.

## Simple to Use, Timeless Character

With the same simple control set and at-a-glance metering of the original, the dbx 160 plug-in makes it easy to crush a parallel drum bus, or inject subtle fatness. It can also add aggressiveness and impact to everything from guitar power chords to a hip-hop vocal.

## Leveled Up for Modern Workflows

Along with graphic enhancements and improved VU metering, the dbx 160 plug-in’s Dry/Wet Mix control lets you easily punch up a drum bus with parallel compression, while the added Sidechain Filter lets you keep the low end tight, enhancing the compressor’s impact.

------------------------------------------------------------------------

# dbx 160 Controls

The minimal controls on dbx 160 make it simple to operate.

 

![dbx 160 interface](dbx%20160%20Compressor%20Manual_assets/cace71a3c5a1a24f0f824ad5638b57782a3a83f8.png)

*dbx 160*

## Threshold

The Threshold knob defines the level at which the onset of compression occurs. Incoming signals that exceed the Threshold level are compressed, while signals below the Threshold remain uncompressed.

The available range is from -55 dB to 0 dB. The numbers on the panel indicate millivolts and volts, as on the original hardware.

As the Threshold control is decreased and more compression occurs, output level is typically reduced. Adjust the Output Gain control to increase the output to compensate if desired.

### Below LED

When the input signal is below the compression threshold value, the Below LED illuminates. No compression is occurring when Below is lit.

### Above LED

The Above LED illuminates when the input signal has exceeded the Threshold value, indicating that compression is occurring. The higher the signal is above the Threshold, the brighter the LED glows.

## Sidechain Filter

A fixed 10 dB per decade (3 dB per octave) custom linear filter is available for the compressor sidechain. The sidechain filter allows removal of low-frequency content from the compressor’s control sidechain, reducing excessive gain reduction and/or "pumping" on bass-heavy audio signals without reducing bass content of the audio signal itself. 

To toggle the function, click the PULL/SC text, or shift-click the Threshold knob. When the Sidechain Filter is active, the Threshold knob is "lifted" and slightly enlarged.

**Note: **The sidechain filter only acts on the compressor's sidechain signal. While this filter can produce an audible change in dynamics behavior, it does not act directly on the audio signal.

## Compression

The Compression parameter determines the ratio for the compressor. Less compression occurs at lower values. The available range is continuous, from 1.00:1 to Infinity:1. At values above approximately 10:1, the compressor behaves more like a peak limiter.

**Note:** For compression to occur, signals must exceed the Threshold value.

## Output Gain

Output Gain controls the signal level that is output from the plug-in. The available range is ±20 dB.

**Tip:** Click the "0" text label to return the control to its default value.

Generally speaking, adjust the Output control after the desired amount of compression is achieved with the Threshold and Compression controls. Output does not affect the amount of compression.

## Meter Select

These buttons determine what is displayed by the VU Meter. They do not change the sound of the audio signal. The active "pressed" button has a darker appearance when compared to the inactive buttons.

**Input –** The VU Meter indicates the plug-in input level in dB. 

**Output –** The VU Meter indicates the plug-in output level in dB. 

**Gain Reduction –** The VU Meter indicates the amount of Gain Reduction in dB.

## VU Meter

The analog-style VU meter displays what is selected with the Meter Select buttons. When the plug-in is disabled with the POWER button, the meter is unlit and the needle remains at 0 dB. When disabled by the host application, the needle is unlit but the needle returns to its minimum position.

## Mix

A blended output balance between the signal processed by the plug-in and the original dry source signal can be adjusted with the Mix control. Mix facilitates parallel compression techniques without having to create additional routings in the DAW.

When Mix is set fully counterclockwise, only the dry, unprocessed source signal is output. When set full clockwise (the default value), only the wet, processed signal is output. When set to 50% (when the set screw "dot" is in the 12 o’clock noon position), an equal blend of both the dry and wet signals is output. The balance is continuously variable, and phase accurate, throughout the control range.

**Tip: **Click the "dbx" label at the left of the control to reduce the value by 10%. Click the "160" label at the right of the control to increase the value by 10%. Click the "MIX" label to set the value to 50%.

## Power

The plug-in is active when the POWER switch is engaged and the VU Meter is lit. Click the POWER button to toggle the state.

When POWER is Off, the plug-in uses no processor or DSP. When the UAD plug-in is set to Off and UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

![dbx-160-hero.png](dbx%20160%20Compressor%20Manual_assets/a640defbbf40edde03cf05f6352b131e38210067.png)

*Original dbx 160 hardware*

