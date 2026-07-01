---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/33030978351892-EMT-140-Plate-Reverb-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'EMT 140 Plate Reverb Manual'
word_count: 1665
---

# EMT 140 Plate Reverb Manual


## Three Legendary Plate Reverbs Captured in Single, Powerful Plug-In

Endorsed by EMT International GmbH, the EMT 140 Classic Plate Reverberator plug-in for UAD-2 hardware and Apollo interfaces gives you the organic lushness that only plate reverb can provide.

By expertly modeling three uniquely different EMT 140s installed at The Plant Studios in Sausalito, California, the EMT 140 plug-in will infuse your sources with the unmistakable warmth and beauty of this iconic plate reverb.

- Choose from three uniquely different EMT plate reverbs
- Add natural depth and shimmer to vocals and instruments
- Sculpt your sound with original controls such as mechanical damping and system input filters
- Enhance plate ambience further with "plug-in only" Balance, Width and Modulation controls

## Expertly Emulated Features

The EMT 140 plug-in offers three distinct flavors of the classic EMT hardware. Plates A and B model the original EMT electronics system, for which the plates themselves had intentionally not been tuned in some time. Conversely, Plate C — the most full-frequency plate — uses the more modern Martech electronics which had just been fully serviced.

## New Controls, More Flexibility

WIth "plug-in only" features such as Balance, Width, and Modulation, you're able to harness the EMT 140 in ways previously unavailable with the hardware. Pinpoint a mono snare reverb with the Balance control, spread out strings with the Width function, or use the Modulation feature to add subtle shimmer, or an intense reverb trail, to a lead vocal. By adding these controls to the original EMT circuit, you're afforded tons of plate reverb textures for all of your sources.

# EMT 140 Controls

The EMT 140 interface is an amalgam of controls found at the plate amplifier itself and the remote damper controls, plus a few DAW-friendly controls that we added for your convenience. The GUI incorporates the original look and feel of those controls, and utilizes that look for the DAW-only controls.

<div class="wysiwyg-text-align-center">

![](EMT%20140%20Plate%20Reverb%20Manual_assets/6447e280293762024929ba39549437807e7dd254.png)

</div>

*EMT 140 Plate Reverb*

## Input Filter

The Input Filter is a dedicated equalizer that is used to reduce low frequency content in the reverb. On hardware plate systems, this setting is rarely modified because it is found at the plate amplifier unit itself and is not easily accessed from the control room.

EMT 140 contains two types of filters: original EMT electronics and Martech electronics which was/is a common plate system retrofit.

In the modeled source units at The Plant, plates A and B use the EMT electronics while Plate C utilizes the Martech electronics. In EMT 140, you can use either filter type with any of the three available plates.

The original EMT filter (indicated by black text) is a cut filter centered at 80 Hz, with three available levels of attenuation: -4 dB, -10 dB, and -16 dB. In controls mode, these values are prefaced with an "E" to designate the original EMT electronics model.

The Martech filter (indicated by red text) is a shelf filter, therefore all frequencies below the frequency are reduced. Six shelving frequencies are available: 90 Hz, 125 Hz, 180 Hz, 250 Hz, 270 Hz, and 360 Hz. In controls mode, these values are prefaced with an "M" to designate the aftermarket Martech electronics model.

**Note:** There is one Input Filter per plug-in instance. Each plate model (A, B, C) within a preset cannot have a unique Input Filter value.

## Reverb Controls

Plate reverb systems are extremely simple: A remote damper setting, and a high pass or shelf filter found at the plate itself. Additional manipulation is often used, including reverb return equalization, which is typically achieved at the console. Predelay is/was often achieved when necessary with tape delay, sending the return to a tape deck. Different tape speeds allowed different pre-delay amount.

The original damper controls are remote control devices, usually found somewhere near the control room for quick access. Our hybrid panel combines three remotes into the panel, with a switch to select each of the three available systems.

**Note:** The reverb controls (Plate Select and Reverb Time) are completely independent from all other plug-in controls.

### Plate Select

Three plate models (algorithms) are available for reverb processing. The Plate Select switch specifies which plate will be active.

Each setting is a model of a completely separate and unique plate system. Three 140's for the price of one!

**Tip:** You can also switch the active plate by clicking the A, B, or C letters above the Plate Select switch and the Reverb Time meters.

### Reverb Time Meters

The Reverb Time Meters display the reverb time of plates A, B, and C in seconds. The meter for the active plate model (as specified by the Plate Select switch) is illuminated.

### Damper Controls (Reverb Time)

The Damper Controls (the green buttons beneath the Reverb Time Meters) change the reverb time for each plate. The range is from 0.5 to 5.5 seconds, in intervals of 0.1 sec. Click the buttons to increment or decrement the reverb time.

**Note:** The reverb time can be changed by dragging a Reverb Time Meter "needle" in addition to its corresponding Damper controls.

## Stereo Controls

### Width

Width allows you to narrow the stereo image of EMT 140. The range is from 0 - 100%. At a value of zero, EMT 140 returns a monophonic reverb. At 100%, the stereo reverb field is as wide as possible.

### Balance

This control balances the level between the left and right channels of the reverb return. Rotating the knob to the left attenuates the right channel, and vice versa (it is not a mono pan control).

## EQ Controls

This group of parameters contains the controls for EMT 140's onboard utility equalizer. It is a two band (low and high) shelving EQ that uses analog-sounding algorithms for great tonal shaping options.

The EQ section is independent from the reverb algorithms and the [Input Filter](#h_01JF8PZK89H6PJBQ4MM8C3C2Q6) on the modeled plate systems.

The frequency parameters specify the center of the transition band, which is defined as the frequency at which the level in dB is the midpoint between DC and the band edge level.

**Note:** There is one EQ per plug-in instance. Each plate model (A, B, C) within a preset cannot have unique EQ values.

### EQ Enable

The EMT 140 equalizer can be disabled with the EQ Enable switch. UAD DSP usage is not increased when EQ is enabled.

### Low Frequency

This parameter specifies the low shelving band transition frequency to be boosted or attenuated by the low band Gain setting. The range is 20 Hz to 2 kHz.

Because this is a shelving EQ, all frequencies below this setting will be effected by the low band Gain value.

### Low Gain

This parameter determines the amount by which the transition frequency setting for the low band is boosted or attenuated. The available range is ±12 dB, in increments of 0.5 dB.

### High Frequency

This parameter determines the high shelving band transition frequency to be boosted or attenuated by the high band Gain setting. The range is 200 Hz to 20 kHz.

Because this is a shelving EQ, all frequencies above this setting will be effected by the high band Gain value.

### High Gain

This parameter determines the amount by which the frequency setting for the high band is boosted or attenuated. The available range is ±12 dB, in increments of 0.5 dB.

## Modulation Controls

The EMT 140 reverb time can be modulated by a low frequency oscillator using rate and depth controls. The effect is subtle but it can increase dispersion and reduce ringing on some source material, such as loud signals with sudden endings and percussive content.

### Mod Rate

Mod Rate controls the rate of reverb time modulation. The available range is from 0.01 Hz to 1.0 Hz.

### Mod Depth

This parameter controls the amount of reverb time modulation. The available range is from 0 - 10 cents.

## Output Meter

The vintage-style VU Meter represents the plug-in output level. It is active when the Power switch is on, and slowly returns to zero when Power is switched off.

## Blend Controls

### Predelay

The amount of time between the dry signal and the onset of the reverb is controlled with this knob. The range is 0.0 to 250 milliseconds.

This control uses a logarithmic scale to provide increased resolution when selecting lower values. When the knob is in the 12 o'clock position, the value is 50 milliseconds.

### Mix

The Mix control determines the balance between the original and the processed signal. The range is from Dry (0%, unprocessed) to Wet (100%, processed signal only).

This control uses a logarithmic scale to provide increased resolution when selecting lower values. When the knob is in the 12 o'clock position, the value is 15%.

**Note:** If Wet Solo is active, adjusting this knob will have no effect.

## Wet Solo

The Wet Solo button puts EMT 140 into 100% Wet mode. When Wet Solo is on, it is the equivalent of setting the Mix knob value to 100% wet (and the Mix value is ignored).

Wet Solo defaults to On, which is optimal when using EMT 140 in the "classic" reverb configuration (placed on an effect group/bus that is configured for use with channel sends). When EMT 140 is used on a channel insert, this control should be deactivated.

**Note:** Wet Solo is a global (per EMT 140 plug-in instance) control.

## Power Switch

This toggle switch enables or disables EMT 140. You can use it to compare the processed settings to the original signal, or to bypass the plug-in which reduces (but not eliminates) the UAD DSP load (unless UAD-2 DSP LoadLock is enabled). The red EMT power indicator glows brighter when the plug-in is enabled.

<div>

 

</div>

<div class="wysiwyg-text-align-center">

![](EMT%20140%20Plate%20Reverb%20Manual_assets/1f2553e76f0d60d7f74b46ec656942d3599870b2.png)

</div>

<div class="wysiwyg-text-align-center">

![](EMT%20140%20Plate%20Reverb%20Manual_assets/4bcd0079280a79816d8d1e035ca440863de850c0.png)

</div>

***Note: **The EMT 140 distills 1800+ pounds of classic vintage reverb into a single plug-in. Exercise caution when lifting.*

