---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/4419505673620-API-2500-Bus-Compressor-Manual.html'
converted_at: 2026-05-31T13:45:00Z
tool: htmlq+pandoc
title: 'API 2500 Bus Compressor Manual'
word_count: 2934
---

# API 2500 Bus Compressor Manual


<div class="callout callout--info">

The DSP UAD-2 and Native UADx plug-ins have different names. The UADx plug-in title is API 2500 Bus Compressor, and the UAD-2 title is API 2500.

</div>

## An obsessively accurate emulation of API’s flagship compressor.

Considered the best of API’s Paul Wolff-era designs, the API 2500 Bus Compressor is a permanent fixture on the 2-bus of many the world’s top engineers and producers. Its dual-channel design adds energy, movement, and tone to stereo mixes unlike any other compressor.

The API 2500 Bus Compressor plug-in for UAD-2 hardware and Apollo interfaces is a spot-on emulation of the ultimate 2-bus workhorse, capturing its all-discrete circuit path, including fanatically detailed renderings of API’s custom transformers and 2510 and 2520 op amps.

- Dramatically improve your mixes with an all-encompassing circuit emulation of API’s iconic 2-bus compressor
- Select between "Old" and "New" compression, selecting between feedback and feed forward sounds
- Enhance and quicken your workflow with plug-in-only Mix and Headroom controls
- Punch up low frequency dynamic range with API’s patented Thrust® technology
- Contour your mix’s left/right dynamic interaction with API’s unique Link controls
- Mix with artist presets from Jeff Balding (Faith Hill, Trace Adkins), Vance Powell (Chris Stapleton, Jack White), Ryan Hewitt (The Avett Brothers, Red Hot Chili Peppers) and more

## The Only End-to-End API 2500 Emulation

Poring over proprietary "for-your eyes-only" schematics made available by API, UA’s team of DSP experts analyzed two AP2500s — rackmount and in-console — ensuring one of UA’s tightest behavioral circuit models to date. Then, together with API’s engineers, we scrutinized every facet of the plug-in against its analog counterpart, bringing forth the definitive representation of this iconic compressor.

## Built for the 2-Bus

API designed the 2500 compressor with program material firmly in mind. Its Attack and Release settings include fixed or variable options while the Threshold and Ratio controls offer musical tweaking throughout their range, making the API 2500 a tone-filled dynamics overlord for your stereo bus.

## Shaping Tone and Dynamics

Along with three custom-voiced compression Knees, "Old" selects characterful feedback, peak-detection operation harkening API’s earliest 525 module, as well as Fairchild and 1176 compressors, while "New" employs API’s modern feed forward design.

## Thrust Control for Unmatched Punch

Taken from their Paragon series of consoles, the API 2500’s Thrust feature puts a filter before the RMS detector, evening high and low frequency energy, so neither triggers the compressor more than the other. This feature gives you a tight punch beyond any other compressor available.

## Enhance Energy and Motion

Most compressors only allow you to turn left/right linking on or off. The API 2500 Bus Compressor Link parameters allow for precision control of your mix’s L/R dynamic interaction. Set exactly how much dependence — or independence — you want your L/R spatial dynamics field to have, and hone your dynamic contours even further with the Shape control.

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

![full-api-2500-no-preset.png](API%202500%20Bus%20Compressor%20Manual_assets/c1686fa83d1a0b0cc69454e03cc93bd5a5db8336.png)

*API 2500 Bus Compressor*

 

------------------------------------------------------------------------

 

# API 2500 Controls

**Note:** Some knob settings, when compared to the graphical user interface silkscreen numbers, may not match the actual parameter values. This behavior is identical to the original hardware, which is modeled exactly. When the plug-in is viewed in parameter list mode (Controls View within DAW), the actual parameter values are displayed.

## Compressor Section

![api-2500-comp.png](API%202500%20Bus%20Compressor%20Manual_assets/5d85b3cd9b45787bbcaf53bf76735ff949a58cd0.png)

### THRESHOLD

This continuously variable knob determines the amount of compression to be applied to the input signal. Rotate THRESHOLD clockwise to lower the threshold and increase compression. Signals below the threshold are not compressed. The available range is +10 to -20 dB.

### THRESHOLD LED

The red LED above the THRESH knob indicates when gain reduction is occurring in the compression circuit. The LED glows brighter as compression increases.

### ATTACK

The ATTACK knob sets the amount of time that must elapse after the input signal reaches the THRESHOLD level before compression is applied.

Seven fixed rates are available. The faster the attack, the more rapidly compression is applied to signals above the threshold. Slower attacks allow a signal’s attack transients (for example, the pluck of a string) to pass without compression, which can produce a punchier sound.

#### Available Attack Times

<figure class="wysiwyg-table">
<table>
<tbody>
<tr>
<td>30 µs</td>
<td>100 µs</td>
<td>300 µs</td>
<td>1 ms</td>
<td>3 ms</td>
<td>10 ms</td>
<td>30 ms</td>
</tr>
</tbody>
</table>
</figure>

### RATIO

The RATIO knob defines the amount of gain reduction to be processed by the compressor. For example, a value of 2 (expressed as a 2:1 ratio) reduces the signal above the threshold by half, with an input signal of 20 dB being attenuated to 10 dB.

Note: Signals must exceed the THRESHOLD value before they are attenuated by the RATIO amount.

Seven ratios are available. Higher ratios produce a more compressed sound. When the control is at maximum (∞), the ratio is effectively infinity to one, producing a limiting effect.

#### Available Ratio Values

<figure class="wysiwyg-table">
<table>
<tbody>
<tr>
<td>1.5:1</td>
<td>2:1</td>
<td>3:1</td>
<td>4:1</td>
<td>6:1</td>
<td>10:1</td>
<td>∞:1</td>
</tr>
</tbody>
</table>
</figure>

### RELEASE (fixed)

The first RELEASE knob (to the left of variable knob) sets the amount of time that must elapse after the input signal drops below the THRESHOLD before compression processing is ceased.

Six rates are available. When this control is set to the fully clockwise position, continuously variable release times can be adjusted with the RELEASE (variable) knob.

#### Available Fixed Release Times

<figure class="wysiwyg-table">
<table>
<tbody>
<tr>
<td>50 ms</td>
<td>100 ms</td>
<td>200 ms</td>
<td>500 ms</td>
<td>1 sec</td>
<td>2 sec</td>
<td>Variable</td>
</tr>
</tbody>
</table>
</figure>

### RELEASE (variable)

The second RELEASE knob (rightmost knob in compressor section) continuously adjusts the compressor’s release time if the RELEASE (fixed) knob to the left of this control is at the fully clockwise position. The available range is 50 milliseconds to 3 seconds.

Note: This control has no effect unless RELEASE (fixed) is set to the fully clockwise position.

Tip: Click a value text label to select the value.

## Tone Section

![api-2500-tone.png](API%202500%20Bus%20Compressor%20Manual_assets/82b05138bbfb8fa5fe29b3139240643e2cf1c3bd.png)

### KNEE

The threshold knee (the compression onset characteristic) of the API 2500 can be set to SOFT, MEDIUM, or HARD. To change the KNEE setting, click the desired value or click the KNEE button to cycle through the available values.

#### Available KNEE Values

SOFT – Provides a subtle transition into compression, resulting in a less obvious effect.

MEDIUM – Provides a slight "fade-in" transition into compression.

HARD – Provides a more typical, sharp transition into compression.

### THRUST

THRUST can be set to NORMAL, MEDIUM, or LOUD. To change the THRUST setting, click the desired value or click the THRUST button to cycle through the available values.

THRUST is an API-patented circuit that inserts a high-pass filter in the control sidechain at the input of the RMS detector, limiting its response to lower frequencies.

The THRUST filter has a slope of 10 dB per decade, which is the inverse of the pink noise energy curve. THRUST adjusts the sidechain frequency response so each octave has the same amount of energy, creating a unique compression effect that reduces pumping and maintains punch.

![api-2500-thrust-diagram.png](API%202500%20Bus%20Compressor%20Manual_assets/8a103f7be3eb9df2a94793c680b7759d0c5928a5.png)

#### Available THRUST Values

NORMAL – The sidechain is unfiltered and compression response is uniform across the frequency spectrum. Behaves as most compressors do.

MEDIUM – The sidechain is slightly attenuated at low frequencies and slightly boosted at high frequencies. Midrange frequencies are unfiltered and remain flat. Reduces low frequency pumping and increases compression on upper frequency peaks.

LOUD – A gradual, linear filter is applied to the sidechain. Frequencies are attenuated 15 dB at 20 Hz and boosted 15 dB at 20 kHz, equalizing the energy entering the RMS detector. Noticeably increases low frequency punch.

### TYPE

TYPE changes the routing of the control sidechain signal within the compressor circuit. To change the TYPE setting, click a value or click the TYPE switch to cycle through the available values.

![api-2500-type-diagram1.png](API%202500%20Bus%20Compressor%20Manual_assets/24ebc46e54cbf6b07842f45147adbf17a45ffe2d.png)![api-2500-type-diagram.png](API%202500%20Bus%20Compressor%20Manual_assets/94255813f65127b6784fc24f588db7f93f755e12.png)

#### Available TYPE Values

NEW – Feed-forward sidechain routing typical of modern VCA-based compressors. The control sidechain input signal is tapped from the <span class="CharOverride-3">uncompressed audio signal. Harder compression with more transparency.</span>

OLD – Feed-back sidechain routing typical of vintage compressors such as the API 525. The control sidechain input signal is tapped from the <span class="CharOverride-3">compressed audio signal. Smoother compression with more character.</span>

Note: Unlike typical compressors, when tone TYPE is set to OLD (feed-back), the gain circuit is within the control sidechain. In this state, gain adjustments (whether automatic or manual), can change the compression amount.

## Link Section

![api-2500-link.png](API%202500%20Bus%20Compressor%20Manual_assets/45e0b6ff58d82cc03121a33f959be42997608d41.png)

### L/R LINK

When the plug-in is used in a stereo-in configuration, the stepped LINK knob allows the dynamics processors of both channels (left & right) to always be compressed in equal amounts (100%, fully linked), completely independently (0%, unlinked), or blended with a mix percentage (e.g., 50%, partially linked).

By de-linking the sidechains, dynamic interaction between the channels can be reduced or eliminated, enabling greater control of movement within the stereo field.

Note: When the plug-in used in a mono-in configuration, this switch is locked in the IND (independent) position.

#### Available L/R LINK Values

100% – The sidechains are stereo linked and the amount of compression is always the same for both channels. Stereo imaging at the input is maintained by preventing left-right shifting at the output when one channel has higher signal peaks compared to the other channel.

IND (0%) – The sidechains are not linked and the amount of compression occurring is completely independent in both channels. If one channel has higher signal peaks than the other channel, the left-right imaging may shift.

50% – 90% – The sidechains are partially linked and the amount of compression occurring is a mixed blend of the left and right channels. The amount of blend can be set to 50, 60, 70, 80, or 90%.

### LINK SHAPE

The SHAPE switch adjusts filtering of the control signal used by the L/R LINK parameter. Two SHAPE filters are available: HP (high pass/low cut) and LP (low pass/high cut). By enabling both filters, a bandpass filter shape is created.

By excluding frequencies from the L/R LINK control signal, sounds in only one channel that contain those frequencies will not cause the other channel to compress, while still linking the preferred frequency range.

To change the SHAPE setting, click a value or click the green SHAPE switch to cycle through the available values. The filter(s) is active when its LED indicator is lit.

Note: When the plug-in is used in a mono-in configuration, this switch has no effect.

## Output Section

![api-2500-output.png](API%202500%20Bus%20Compressor%20Manual_assets/e3f3cfb5b2258068e5c0a38844398e0bf08b3310.png)

### IN

The IN switch enables the compression circuit. The compressor is active when the green LED above the IN switch is lit. To toggle the IN/OUT state, click the IN switch, label, or LED.

When IN is disengaged, the compression circuit is bypassed while still routing the signal through the rest of the circuitry. With this "soft" bypass control, the signal is no longer compressed but the sound of the amplifiers, transformers, and other components are heard.

Note: If the BYP switch is engaged, the IN switch has no effect.

### BYP (BYPASS)

The BYP button bypasses all hardware circuitry. In the original hardware unit, this switch controls a relay that hard-wires the inputs directly to the outputs.

The compressor is bypassed when the yellow LED above the BYP button is lit. To toggle the BYPASS state, click the BYP button, label, or LED.

Tip: To unload the plug-in and conserve UAD resources, use the POWER switch.

### GAIN

The API 2500 has automatic or manual make-up gain to compensate for the lowered output levels that result from signal compression. To toggle between automatic and manual make-up gain, click the red make-up GAIN switch, label, or LED.

Note: Unlike typical compressors, when tone TYPE is set to OLD (feed-back), the gain circuit is within the control sidechain. In this state, gain adjustments (whether automatic or manual), can change the compression amount.

### AUTO GAIN

Automatic make-up gain is active when the red MAKE-UP GAIN switch is in the "out" position and the red LED above the switch is unlit.

When automatic make-up gain is active, the compressor’s output level is increased reciprocally as the compression amount increases, and decreases reciprocally as the compression amount decreases.

Automatic make-up gain facilitates easier adjusting and auditioning of the processor’s sound by keeping the output volume consistent as the compressor’s THRESHOLD and RATIO controls are adjusted. This function is especially useful in situations where adjustments need to be made without disturbing the output level to a recording or broadcast system.

### MANUAL GAIN

When manual make-up gain is active, the red dB GAIN knob continuously adjusts the compressor’s output level. The available range is 0 to +24 dB.

Tip: Click the "0" text label to return the value to 0 dB.

Manual make-up gain is active when the red MAKE-UP GAIN switch is in the "in" position and the red LED above the switch (below the "man" text label) is lit.

**Note: **This control only operates when the make-up GAIN switch is engaged.

## Other Controls

![api-2500-other.png](API%202500%20Bus%20Compressor%20Manual_assets/9e616c303e4e494890f46541d371423e8baac4ea.png)

### POWER

The POWER switch determines whether the plug-in is active or not. To change the power state, click the yellow POWER switch or the POWER text label.

When set to off (switch unlit), the VU meters go dark to indicate signal processing has ceased. In this state, plug-in processing is disabled and UAD DSP usage is reduced (unless UAD-2 DSP LoadLock is enabled).

### MIX

A blended output balance between the signal processed by the plug-in and the original dry source signal can be adjusted with the MIX control. Mix facilitates parallel compression techniques without having to create additional routings in the DAW.

Note: The MIX control does not exist in the original hardware.

When MIX is set to 0%, only the unprocessed (dry) source signal is output. When set to 100% (the default value), only the processed (wet) signal is output. When set to 50%, an equal blend of both the dry and wet signals is output. The balance is continuously variable, and phase accurate, throughout the control range.

Tip: Click the MIX text label to set the control to the 50% position. Click the 0 text label to set the control to the minimum position. Click the 100% text label to set the control to the maximum position.

### VU METERS

The calibrated VU Meters can display either input levels, output levels, or gain reduction levels. The levels being displayed are determined by the VU METER SOURCE switch.

Each channel (left and right) has its own VU Meter. When the plug-in is used in a mono-in configuration, both meters display the same levels.

Note: The VU Meters displays average loudness and do not display signal peaks.

#### Meter Scales

The VU Meters have two different text scales printed on the meter background. The active scale is set with the VU METER SOURCE switch.

IN/OUT Scale – The upper scale (ranging from -20 dB to +3 dB) is used to display input and output levels. With this scale, 0 VU represents +4 dBu.

GR Scale – The lower scale (ranging from 20 dB to 0 dB) is used to display gain reduction levels.

### VU METER SOURCE

This switch determines what is displayed by the VU Meters. To change the VU Meters source setting, click a value, or click the METER switch to cycle through the available values.

#### Available METER SOURCE Values

GR – The VU Meters display the amount of gain reduction occurring in each channel.

OUT – The VU Meters display signal levels at the output of the plug-in.

IN – The VU Meters display signal levels at the input of the plug-in.

### HEADROOM (HR)

![API_2500_FINAL_2x6.png](API%202500%20Bus%20Compressor%20Manual_assets/cdc5bb78143bfc3d361096154234a25f2aab758f.png)

The Headroom control is a UAD-only feature that is not available in the original hardware. Headroom enables adjustment of the internal operating reference level for the plug-in so that the plug-in is not "pushed" into gain reduction as much. Headroom enables best practice operating level matching, or it can be used creatively to expand the sonic range of the processor.

By fine-tuning Headroom, the nonlinear I/O distortion and compression response characteristics can be tailored independently of signal input levels. Increasing Headroom (by rotating the control counter-clockwise) allows signals at the input to be pushed higher before they compress.

Headroom can be set (in dB) to 4, 8, 12, 16, 20, 24, or 28. The default value is 16 dB (when the set screw "dot" is in the straight up 12 o’clock position). Note that Headroom is increased as the dB value decreases.

Tip: Click the "HR" text label to return the control to the default value.

At higher dB values (clockwise rotation), signals will push the plug-in into gain reduction (and more non-linearity and "good" harmonic distortion color) more easily. Set the control to a lower value (counter-clockwise rotation) when less gain reduction and less color is desired.

Note: To avoid the temporary gain increases that can result when adjusting Headroom, automating this control is not recommended.

HR replaces the L/R TILT control that is available on the original hardware. Because L/R TILT is used to compensate for analog component tolerances and drift, it is not needed with the plug-in.

![API_logo.png](API%202500%20Bus%20Compressor%20Manual_assets/f18a4c860fe9148b96198d8e3a4065c511025652.png)

![api-2500-hw-lunchbox.png](API%202500%20Bus%20Compressor%20Manual_assets/6a771dd2e1b967ebe1c80571c0f5538aa5a06cf3.png)

*API 2500 Bus Compressor hardware*

All visual and aural references to the API 2500 Bus Compressor and all use of API’s trademarks are being made with written permission from Automated Processes, Inc. Special thanks to Paul Wolff, Larry Droppa, Todd Humora, and Jeffrey Richards.

