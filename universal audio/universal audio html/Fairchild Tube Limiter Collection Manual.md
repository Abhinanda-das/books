---
source: '/Users/abhinanda/Downloads/zvuk/help.uaudio.com/hc/en-us/articles/13293388042900-Fairchild-Tube-Limiter-Collection-Manual.html'
converted_at: 2026-06-05T05:54:32Z
tool: htmlq+pandoc
title: 'Fairchild Tube Limiter Collection Manual'
word_count: 4229
---

# Fairchild Tube Limiter Collection Manual


<div class="callout callout--info">

The DSP UAD-2 and Native UADx plug-ins in this collection have different names. The UADx plug-in titles are Fairchild 660 Compressor and Fairchild 670 Compressor, and the UAD-2 titles are Fairchild 660, Fairchild 670, and Fairchild 670 Legacy.

</div>

## In this article

- <a href="#h_01GSGJR7NZZC0FZEGJZAGA033K" target="_self">Fairchild Plug-In Family</a>
- <a href="#h_01GSGJRR1R1560Z7YCWB6B54AY" target="_self">Fairchild 670 Operational Overview</a>
- <a href="#h_01GSGFAECKTCFCVGXY1N5DZRZB" target="_self">Fairchild 670 Modes</a>
- <a href="#h_01GSGJT12T5R6ZDVBEXT1JQN6V" target="_self">Fairchild Controls</a>
- <a href="#h_01GSGJT92QJ919X52K7KEGBEQZ" target="_self">Historical Background</a>

## Discover the rich sound of the world's most famous compressors.

- Give your tracks and mixes classic Fairchild tube warmth and character
- Add harmonics and punch to vocals, drums, and more using Fairchild’s tube-driven gain control and transformer sections
- Tweak compression easily with simple Wet/Dry, Sidechain Filter, and Headroom controls
- Enjoy the only accurate emulations of "golden-reference" vintage Fairchilds

## The Ultimate Companion to the LA-2A and 1176 Plug-In Collections

Combined with the Electro-Optical (LA-2A) and FET-based (1176) compressor plug-ins, the Fairchild's unique tube-driven sound completes the compression "Triple Crown." Renowned for its aggressive power on piano, bass, and guitar, the 660 is a stereo/mono version of the original mono compressor, while the flagship 670 is a full stereo compressor that can inject vibe and color into tracks or add the final touch to mixes.

<div class="wysiwyg-text-align-center">

![fairchild-660.png](64c386b571ed2e0c52d0d202990f35b0e7cf8c9d.png)

</div>

*UAD Fairchild 660*

<div class="wysiwyg-text-align-center">

![fairchild-670.png](39a8a78e9d8dae528113e83214a7ef6001236350.png)

</div>

*UAD Fairchild 670*

<div class="wysiwyg-text-align-center">

![fairchild-670-legacy.png](b88cd0c6a86aedc58531bdf0ab7b1a2d470dbc69.png)

</div>

*UAD Fairchild 670 Legacy (UAD-2 DSP only)*

------------------------------------------------------------------------

# Fairchild Plug-In Family

The complete Fairchild family consists of the following individual plug-ins, as seen in the screenshots above and described below. Each variation has its own unique sonic characteristics.

## Fairchild Tube Limiter Collection

The Fairchild Tube Limiter Collection includes two native UAD plug-ins (Fairchild 660 and Fairchild 670), and three UAD-2 plug-ins: Fairchild 660, Fairchild 670, and Fairchild 670 Legacy.

### Fairchild 660

The original Fairchild 660 hardware is a single-channel (monophonic) processor. The UAD Fairchild 660 plug-in was faithfully modeled from the original 660 hardware, independently from the Fairchild 670 plug-in modeling.

The Fairchild 660 may be handy with mono sources, or when less control is required via its simpler interface. The Fairchild 660 controls are identical to one channel of the Fairchild 670.

### Fairchild 670

The Fairchild 670 is the two-channel (stereo) workhorse revered by engineers and producers worldwide.

### Second-Generation Algorithms

The newer state-of-the-art algorithms in the Fairchild Tube Limiter Collection take full advantage of advances in DSP modeling and processing power, along with the design sophistication and expertise gained since the original Fairchild Legacy plug-in was developed.

### Sonic Differences

Like the differences between the original Fairchild 660 and 670 hardware units, the UAD models in the Fairchild Tube Limiter Collection offer variations in threshold behaviors, total gain, input attenuation range, distortion amount, distortion structure, program dependence, time constant subtleties and more. These differences provides an expanded palette within the Fairchild sound.

### Fairchild 670 Legacy (UAD-2 DSP only)

The original version of the Fairchild 670 was released in January of 2004 for the UAD-1 platform. To accommodate the limited DSP resources of the first-generation UAD-1 hardware, the transformer and I/O distortion characteristics were not modeled in this version of the plug-in.

The Fairchild 670 Legacy has a great sound and is very usable, especially in situations where less distortion is desirable, or when there are not enough DSP resources to use the second-generation models in the newer Fairchild Tube Limiter Collection. It also has slightly less overall latency since it is not an upsampled plug-in.

The Fairchild 670 Legacy can be distinguished from the two newer Fairchild plug-ins by the word LEGACY in the plug-in title and within the interface.

**Note:** The Fairchild 670 Legacy plug-in is a UAD-2 plug-in, and is not available natively. 

## Mono/Stereo Operation

Although the Fairchild 660 original hardware is a single-channel processor and the Fairchild 670 original hardware is a dual-channel processor, all UAD Fairchild plug-ins can each be used on either mono or stereo sources.

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

------------------------------------------------------------------------

# Fairchild 670 Operational Overview

## Unique Controls

Controls in the UAD Fairchild plug-ins are original Fairchild hardware controls with the following exceptions:

- The VU meter and the <a href="#h_01GSGFBNZ2G7GG9V6YWFJMS9PV" rel="undefined" target="_self">Meter Switch</a> are re-purposed, enabling the ability to monitor input and output levels (the original hardware does not have this ability). In the hardware, the function of the meter switch is to enable calibrating the bias currents; this function is achieved automatically in the plug-in when the <a href="#h_01GSGFC403S0N8SFQXWBS3N4JR" rel="undefined" target="_self">Balance</a> control is in the default position.
- The Headroom (HR) control replaces the VU meter's Zero control, which originally corrected for component wear offsets in the VU meter pin.
- The Sidechain Link control is a common modification which had been performed on the unit we modeled.
- Output Level, Controls Link, Sidechain Filter, Mix, and Headroom controls are digital-only additions for the UAD plug-ins.
- The D.C. Threshold controls are original controls, however on the Fairchild 660 they were located on the rear panel.

**Note: **Not all controls are available in the Fairchild 670 Legacy plug-in.

## Lateral/Vertical

One of the design goals of the Fairchild 670 hardware was to facilitate its use as a\
limiter when producing vinyl phonograph masters. The terms lateral (side-to-side) and vertical (up-and-down) refer to the mechanical modulations in a vinyl record groove that are transduced into electrical audio signals by the phonograph stylus and cartridge.

The Fairchild 670 can perform dynamics processing on the lateral (LAT) and vertical (VERT) components of stereo signals independently. In other words, the monophonic (middle) and/or stereo (side) components of a stereo source signal can be compressed or limited separately from the other component.

Lat/Vert processing facilitates maximum usable levels and efficient use of available groove space in phonograph mastering, resulting in higher volume recordings with longer playing times. Of course, the feature can also be used for creative effects outside of the phonograph environment.

**Note:** Lat/Vert processing is an operating mode of Fairchild 670. For additional details on the modes and how to access them, see <a href="#h_01GSGFAECKTCFCVGXY1N5DZRZB" rel="undefined" target="_self">Fairchild 670 Modes</a>.

Lat/Vert processing is accomplished by first routing the stereo source signal through a sum/difference (mid/side) matrix which separates the stereo source into lateral (middle, or center without stereo) and vertical (side, or stereo without mono) signal components. The lateral/vertical components are then compressed or limited independently. Finally, the mid/side components are recombined into a normal stereo signal via a second sum/difference matrix.

In the Fairchild 670, the left+right (sum) middle signals are routed to the Lat channel, and the left-right (difference) side signals are routed to the Vert channel. The two channels can work independently of each other, or the sidechain control signals can be optionally linked.

**Tip:** Controls related to Lat/Vert processing contain red Lat/Vert text labels.

## Operating Levels

The <a href="#h_01GSGFD0TJG86TC9K16PXFD05Q" rel="undefined" target="_self">Headroom</a> (HR) control enables adjustment of the internal operating reference level for the Fairchild 670 and Fairchild 660. This feature enables more sonic range and the ability to fine-tune the non-linear I/O distortion and compression response characteristics to be tailored independently of signal input levels.

By increasing the Headroom (by rotating the HR control counter-clockwise), signals at the input can be pushed higher before they compress. For complete details about this feature, see <a href="#h_01GSGFD0TJG86TC9K16PXFD05Q" rel="undefined" target="_self">Headroom</a>.

------------------------------------------------------------------------

# Fairchild 670 Modes

## 2 Compressors, 4 Modes

There are two independent compressors within the Fairchild 670. Depending on the state of the <a href="#h_01GSGF8YBME73FT02KBARKW9A9" rel="undefined" target="_self">AGC Switch</a> and the <a href="#h_01GSGF9WM55BPTCWT8PGPMP413" rel="undefined" target="_self">Sidechain Link</a> switch, four operating modes are possible. The modes are detailed in this section.

## Operating Modes

The switch positions required for each operating mode is shown in the table below. See <a href="#h_01GSGFETGTBPZ2YY87RG4G8901" rel="undefined" target="_self">Lateral/Vertical</a> for an overview of these terms.

<figure class="wysiwyg-table">
<table>
<thead>
<tr>
<th style="text-align: center;"><strong>AGC Switch Setting</strong></th>
<th style="text-align: center;"><strong>Sidechain Link Setting</strong></th>
<th style="text-align: center;"><strong>Operating Mode</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>Left Right</td>
<td>Unlinked</td>
<td>Dual Mono</td>
</tr>
<tr>
<td>Lat Vert</td>
<td>Unlinked</td>
<td>Dual Lateral/Vertical</td>
</tr>
<tr>
<td>Left Right</td>
<td>Linked</td>
<td>Stereo Left/Right</td>
</tr>
<tr>
<td>Lat Vert</td>
<td>Linked</td>
<td>Stereo Lateral/Vertical</td>
</tr>
</tbody>
</table>
</figure>

## Dual Mono

In dual mono mode, the Fairchild 670 operates as two separate monophonic compressors with independent control of the left and right channel signals. There is no interaction between the two compressors.

## Dual Lat/Vert

In dual lateral/vertical mode the Fairchild 670 operates as two monophonic compressors with independent control of the middle and side components of the two input signals. The input signals are processed by the sum/difference (mid/side) matrix before and after the compressors, but there is no interaction between the two compressors.

## Stereo Left/Right

In this mode, the Fairchild 670 operates as a typical stereo dynamics processor. The left input is fed to the one compressor, and the right input is fed to the other. The dynamics control signal sidechain of the two compressors are linked so that they both compress the same amount at any instant, preventing transients which appear on only one channel from shifting the stereo imaging of the output.

Any transient above the threshold (on either channel) will cause both channels to compress, and the amount of compression will be similar to the amount of compression for a transient which appears on both channels at the same time.

Additionally, the attack and release times for the two compressors will be the same, and attack and release behavior will be the average of the settings for the two channels. Mono transients will have an effective attack time of about one half the attack time for transients on only one of the two channels.

## Stereo Lat/Vert

Stereo lateral/vertical (mid/side) mode, like stereo left/right mode, causes the two compressors to be linked together so that they always compress the same amount. In this mode however, the inputs to the two compressors are fed with the middle and side components of the signal respectively. This generally means that a transient which occurs in both channels will cause a bit more compression than a transient which only appears on left or right. The attack and release behavior is determined by the average of the settings for the two channels.

------------------------------------------------------------------------

The control functions are essentially identical across all UAD plug-ins in the Fairchild family, so they are described only once. Any control differences between the three plug-ins are noted in the control descriptions.

## Stereo Controls

Controls that are identical for the left and right channels (Fairchild 670 and Fairchild 670 Legacy only) are only described once.

## Power Switch

This switch determines whether the plug-in is active. When set to Off, the plug-in uses no processor or DSP. When the UAD plug-in is set to Off and UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

### Power Lamp

The lamp beneath the Power switch is illuminated when the plug-in is active.

**Tip: **Click the Power Lamp to toggle the power state.

## VU Meters

There are two VU meters, one for each channel. The VU meters can display input levels, output levels, or gain reduction levels, as determined by the Meter Switch.

## Meter Switch

This switch determines what is displayed on the VU meters. Input, output, or gain reduction (GR) levels can be selected.

**Tip:** Click the control's text labels to change the switch position.

The default position is GR. If GR is selected, the meter will show gain reduction in dB for the corresponding compressor channel.

If the <a href="#h_01GSGF8YBME73FT02KBARKW9A9" rel="undefined" target="_self">AGC Switch</a> is set to left/right, the GR shown will be for the left or right channel. If the AGC switch is set to Lat/Vert, the GR shown will be for the middle (upper meter) or side (lower meter) channel. In GR mode, the upper labels show gain reduction in dB.

If the meter select switch is set to IN or OUT, then that meter will reflect the relative level of the right or left input or output signal (the I/O meters are not calibrated).

## Channel Input Gain

This is a stepped attenuation control which always applies to the left or right input, regardless of the AGC control setting. The steps are approximately 1 dB apart.

### Fairchild 670

The available range is -20 to 0 dB with a default value of -4 dB (unity gain).

### Fairchild 660

The available range is -Infinity (off) to 0 dB with a default value of -14 dB (unity gain).

**Note:** As with the 660 hardware, there is some signal leakage even when Input Gain is set to -Inf.

### Fairchild 670 Legacy

The available range is -20 to 0 dB with a default value of -18 dB (unity gain).

## Threshold

This continuously variable control determines the amount of compression to be applied to the channel. Rotate clockwise for more compression (increasing the control lowers\
the threshold).

In the Fairchild 670, the default value is 1.5. In the Fairchild 660, the default value is 5. In the Fairchild 670 Legacy, the default value is 3.

### Input Gain versus Threshold

The amount of signal compression is determined by both the Input Gain and Threshold controls. If one is increased and the other decreased, the compression characteristics won't change much, but the distortion characteristics will.

The input control is located ahead of the tubes, directly "behind" the input transformer. Therefore as the input control is increased, the input tube (the gain-varying stage) is hit with more signal which can increase distortion (which may or may not be desirable).

**Tip:** For less distortion with the same amount of compression, lower the input gain and increase the threshold control.

## Time Constant

This 6-position switch provides fixed and variable time constants (attack and release times) to accommodate various types of program material. Positions 1-4 provide successively slower behavior, and 5 and 6 provide program dependent response.

**Tip:** Click the control's text labels to change the switch position.

The values published by Fairchild for each position are in Fairchild Time Constants\
below. The actual measured times are a bit different, but the overall trend is the same. The default value is Position 5.

**Tip: **When Sidechain Link is enabled and Controls Link is disabled, the Time Constant settings of the two channels are interactive, which enables the ability to have many other attack/release variations than those listed in the table.

## Fairchild Time Constants

<figure class="wysiwyg-table">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Time Constant</strong></th>
<th style="text-align: center;"><strong>Attack Time</strong></th>
<th style="text-align: center;"><strong>Release Time</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>Position 1</td>
<td>200 microseconds</td>
<td>300 milliseconds</td>
</tr>
<tr>
<td>Position 2</td>
<td>200 microseconds</td>
<td>800 milliseconds</td>
</tr>
<tr>
<td>Position 3</td>
<td>400 microseconds</td>
<td>2 seconds</td>
</tr>
<tr>
<td>Position 4</td>
<td>800 microseconds</td>
<td>5 seconds</td>
</tr>
<tr>
<td>Position 5</td>
<td>200 microseconds</td>
<td>Program dependent:<br />
- 2 seconds for transients<br />
- 10 seconds for multiple peaks</td>
</tr>
<tr>
<td>Position 6</td>
<td>400 microseconds</td>
<td>Program dependent:<br />
- 300 milliseconds for transients<br />
- 10 seconds for multiple peaks<br />
- 25 seconds for consistently high program level</td>
</tr>
</tbody>
</table>
</figure>

## AGC Switch

This switch determines whether the two compression channels will receive left/right or lateral/vertical (mid/side) signals as the inputs.

**Tip: **Click the control's text labels to change the switch position.

In conjunction with the <a href="#h_01GSGF9WM55BPTCWT8PGPMP413" rel="undefined" target="_self">Sidechain Link</a> switch, this control determines the operating mode of the Fairchild 670. See <a href="#h_01GSGFAECKTCFCVGXY1N5DZRZB" rel="undefined" target="_self">Fairchild 670 Modes</a> for detailed mode descriptions.

**Note:** This control is unavailable on the Fairchild 660.

### Left/Right

If Left/Right is selected and Sidechain Link is off, the compressor is in dual mono mode. If Sidechain Link is on, the mode is stereo left/right.

### Lat/Vert

If Lat/Vert (mid/side) is selected and Sidechain Link is off, the compressor is in dual lateral/vertical mode. If Sidechain Link is on, the mode is stereo lateral/vertical.

## Sidechain Link

When this control is set to Link, it causes the two channels of the compressor to compress in equal amounts. This does not mean that the compressor will be equally sensitive to either channel however; that depends on the settings of the other controls.

**Note:** This control is unavailable on the Fairchild 660.

Linking the sidechains simply means that the instantaneous amount of compression for the two channels will always be the same, thereby preventing left-right image shifting at the output. Threshold and input gains can be set independently to cause the compressor to be more sensitive to instruments which are panned to one side or the other. Output controls can be set separately in order to correct an overall image shift at the output.

**Tip:** In conjunction with the <a href="#h_01GSGF8YBME73FT02KBARKW9A9" rel="undefined" target="_self">AGC Switch</a>, the Sidechain Link switch determines the operating mode of the Fairchild 670 and Fairchild 670 Legacy.

## Controls Link

This switch allows the two sets of controls for the interface to be stereo linked. The control is unavailable on the Fairchild 660.

**Important:** When unlink is switched to link, the left channel values are copied to the right channel, and any control offsets between channels are lost.

## Headroom

The Fairchild hardware units can accept an analog signal level of approximately +27 dBm before undesirable signal clipping occurs. As the signal increases up to this point however, desirable audio-path nonlinearities and "good" harmonic distortion characteristics occur. This musically pleasing "warmth" at higher levels is what gives the unit much of its revered sonic character. Because analog mixing consoles can typically output high signal levels, audio engineers often take advantage of the ability to "push" the hardware unit into the colorful arena.

This complete pallet of sonic nuance, including the dynamic input response, is captured in the Fairchild Tube Limiter Collection models (but not the Fairchild 670 Legacy). The 660 and 670 plug-ins are calibrated internally so that when the Headroom control is at its nominal value of 16 dB, 0 dBFS at their input is equivalent to an input level of approximately +20 dBu on the hardware, where the coloring is more prominent. The result is that a typical signal within a DAW will drive the UAD Fairchild 660/670 into these "virtual" higher levels, resulting in fairly high amounts gain reduction.

### Headroom Control

The Headroom (HR) control is provided to accommodate applications where high amounts of gain reduction are not desired. Headroom simply changes the internal operating level so that the plug-in is not "pushed" into gain reduction as much.

**Note:** There is only one headroom parameter. Although the HR control appears twice in the Fairchild 670 window, they are permanently linked.

Headroom can be set (in dB) to 4, 8, 12, 16, 20, 24, or 28. The default value is 16 dB (when the set screw dot is in the straight up 12 o'clock position). Note that Headroom is increased as the dB value decreases.

**Tip:** Click the HR text label to return the control to its default value.

At higher dB values (clockwise rotation), signals will push the plug-in into gain reduction (and more non-linearity and "good" harmonic distortion color) more easily. Set the control to a lower value (counter-clockwise rotation) when less gain reduction and less color is desired.

**Note:** To avoid the temporary gain increases that can result when adjusting Headroom, automating this control is not recommended.

Keep in mind there are no hard and fast headroom rules. Feel free to experiment with the various positions of the HR control regardless of the audio source. If it sounds good, use it!

**Note:** The HR control is not available with Fairchild 670 Legacy. On the hardware unit, the Zero screw (as displayed in the Fairchild 670 Legacy) adjusted the meter pointer to compensate voltage fluctuation and component wear.

## Balance

Balance (BAL) controls the bias current balance. It always controls one channel of the compressor, regardless of what the nearby Meter Switch is set to. The point of perfectly calibrated bias currents is achieved when the screw slot is at the 12 o'clock position (the default value).

**Tip:** Click the BAL text label to return the control to its default position.

At the default setting, the amount of additive signal deflection ("thud") which happens due to an attack is minimized. Setting this control counter-clockwise from this position results in a thud of one polarity on transients, and going clockwise produces a thud of opposite polarity.

**Note:** To avoid the DC settling artifacts that can result when adjusting Balance, automating this control is not recommended.

## Sidechain Filter

The Sidechain Filters (one each for the Left/Lat and Right/Vert channels) control the cutoff frequency of a low-cut filter on the compressor's control signal sidechain. They have a slope of 12 dB per octave. The available range is 20 Hz to 500 Hz, and Off. The default value is Off.

**Tip:** Click the OFF label to disable the sidechain filter.

Removing low-frequency content from the sidechain can reduce excessive gain reduction and/or "pumping" on bass-heavy audio signals without reducing bass content of the audio signal itself.

**Note:** Sidechain Filters are not available with Fairchild 670 Legacy.

### Auditioning the Sidechain Filter

To quickly switch back and forth between OFF and the last set value, click the OFF label. This feature is handy for comparing the filtered and unfiltered sidechains.

**Note:** The Sidechain Filter affects the control signal of the compressor only. It does not filter the audio signal.

## DC Threshold

DC Threshold controls the ratio of compression as well as the knee width. As the knob is turned clockwise, the ratio gets lower and the knee gets broader. The threshold also gets lower as the knob is turned clockwise.

It's more technically accurate to say that this control simply changes the knee width, since no matter where it's set, the ratio always approaches true limiting eventually. However, the knee becomes so broad that it becomes more practical to speak of the ratio changing, because for reasonable amounts of compression (less than 25 dB), this is the case.

## CAL

To calibrate the plug-in to factory specifications (the default value), align the white CAL mark with the black dot on the adjustment screw.

Tip: Click the CAL text label to return the control to the factory calibrated position.

## OWR

To calibrate the plug-in to the setting used by Ocean Way Recording (the source unit for the plug-in modeling), align the white OWR mark with the black dot on the adjustment screw.

**Tip:** Click the OWR text label to return the control to the Ocean Way Recording position.

## Output Gain

These controls provide clean, uncolored gain to the output signals. The available range is ±20 dB. The default value is 0 dB.

**Tip:** Click the OUTPUT text label to return the control to its default position.

### Fairchild 670 Legacy

In the Fairchild 670 Legacy, Output Gain is a stepped control, with each step being separated by 0.5 dB, and an available range of -18 dB to +6 dB.

## Mix

The output balance between the signal processed by the plug-in and the original dry source signal can be adjusted with the Mix control. Mix facilitates parallel compression techniques without having to create additional routings in the DAW.

**Note:** This control is not available with Fairchild 670 Legacy.

When set to 0%, only the unprocessed (dry) source signal is output. When set to 100% (the default value), only the processed (wet) signal is output. When set to 50%, an equal blend of both the dry and wet signals is output. The balance is continuously variable throughout the control range.

**Tip:** Click the MIX text label to set the control to the 50% position. Click the 0 text label to set the control to its minimum position. Click the 100% text label to set the control to its maximum position.

![fairchild-660-hw1.jpg](1c6f7391d1c22b1e0a5dc8f6e21bb73dc7768744.jpg)

------------------------------------------------------------------------

# Historical Background

The origins of the Fairchild 660/670 design come from Estonian-born immigrant Rein Narma. Les Paul hired Narma to modify his first 8-track Ampex machine. Later, Narma built consoles for Olmsted Recording, Rudy Van Gelder, and Les Paul, who then asked him to build an all-new, sonically reliable audio limiter. In the post-war years, this refugee from Soviet Russia worked for the U.S. Army as a broadcast/recording tech during the Nuremberg trials, then later immigrated to the New York and took a job at Gotham Recording. Narma and others founded Gotham Audio Developments to build recording gear.

The compressor's Fairchild connection begins with Sherman Fairchild, the son of Congressman George Winthrop Fairchild, one of the founders of IBM. Sherman Fairchild built and designed the first aerial photography equipment during World War I. After that war ended, he started the Fairchild Aerial Camera Corporation in 1920. Sherman Fairchild eventually went on to design a multitude of products, from aircraft to semiconductors, and opened several more companies, including Fairchild Recording Equipment Corporation. After Narma began the limiter project for Les Paul, Sherman Fairchild heard about it, licensed the design, and hired Narma as the company's chief engineer. After his time at Fairchild, Narma moved to Northern California and was a vice-president at Ampex. The Fairchild was advertised as "The World Accepted Standard for Level Control" back in the 1950s when it was originally sold. It is still revered for its extremely smooth, artifact-free sound.

![fairchild-670-hw1.jpg](966c9c5863a046b63e8151ca72f6811c41fca155.jpg)

<span class="wysiwyg-font-size-small">v260205</span>

