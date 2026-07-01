---
source: /Users/abhinanda/Downloads/zvuk/help.uaudio.com/hc/en-us/articles/17790028958228-Manley-VOXBOX-Channel-Strip-Manual.html
converted_at: 2026-06-05T05:54:36Z
tool: htmlq+pandoc
title: Manley VOXBOX Channel Strip Manual
word_count: 3968
updated: 05 июня 2026 07:56
---

# Manley VOXBOX Channel Strip Manual


<div class="callout callout--info">

The DSP UAD-2 and Native UADx plug-ins have different names. The UADx plug-in title is Manley VOXBOX Channel Strip, and the UAD-2 title is Manley VOXBOX.

</div>

## In this article

- [Operational Overview](#01H7G3YDWPE5W5EX74Q786A5K2)
- <a href="#h_01H6ETTW6WE2BBP2GB4W6VDWY2" target="_self">Manley VOXBOX Channel Strip Controls</a>
- <a href="#h_01H6PQVP7SXKCH14ECPXR84P35" target="_self">Additional Information</a>

![[VOXBOX.png]]

Manley’s VOXBOX channel strip is a beautiful system of tube‑driven preamp, dynamics and EQ circuits, designed specifically for your all‑important vocal sources. The Manley VOXBOX Channel Strip plug‑in gives you the same elevated, smooth sonics of this premium vocal channel strip.

## Get the Sound of Manley's Flagship Hardware

The Manley VOXBOX Channel Strip plug‑in thoroughly emulates the modern boutique hardware, including its high‑fidelity tube mic preamp, vactrol optical compressor, Pultec‑style passive EQ, and de‑esser/limiter, giving you hit‑making vocals that are clear, detailed, and full of life.

- <span class="text">Create rich, luxurious vocals with Manley’s high-fidelity, Class-A tube mic preamp</span>
- <span class="bullet" style="height: 15px; width: 15px;"></span><span class="text">Sculpt vocals with Manley’s Pultec-style passive EQ with 33 selectable frequencies</span>
- <span class="bullet" style="height: 15px; width: 15px;"></span><span class="text">Dial-in signals with perfectly tuned Attack and Release combinations</span>
- Harness Class A EQ and compression for bass, acoustic guitars, vocals, voiceovers, and more
- Organically tame sibilance with unmatched de-esser/limiter section
- Record in realtime "through" a high-end Manley VOXBOX with Apollo and Unison™ technology (Apollo/UAD-2 only)

## Add Magical EQ Sculpting

The Manley VOXBOX Channel Strip plug‑in’s three‑band, passive EQ is based on the classic Pultec MEQ‑5 but extended, giving you a broad‑stroke EQ that keeps the top end sweet, and the lows defined, yet natural sounding — even with extreme boosts and cuts.

## Compress Sources Before the Preamp

Just like the hardware, the Manley VOXBOX plug‑in lets you tame transients before the preamp with its perfectly tuned, flexible optical compressor. This, along with a ton of interactive Attack and Release combinations, you'll get exceptionally smooth‑sounding tracks every time.

## Get Ultra Transparent De‑Essing and Limiting

At the center of the Manley VOXBOX is its sublime, natural sounding de‑esser. With two knobs, you get complete control of not only vocals, but shrill electric guitars, or overly bright overheads. You can also turn off the de‑esser frequency control and use this section as an aggressive and colorful‑limiter.

## Use on Any Source for Pro Results

For years, the Manley VOXBOX has been a secret weapon for bassists looking to harness its high‑end tube signal path and slick EQ and compression features. The Manley VOXBOX is also perfect for clean electric guitars, strings, and drums as its always‑musical results can lift any source way beyond the ordinary.

## Record "Through" a Boutique Tube Preamp With Apollo

UA’s groundbreaking Unison technology lets you track in realtime through the Manley VOXBOX Channel Strip plug‑in using your Apollo, giving you the original boutique hardware’s line/mic preamp impedance, gain stage “sweet spots,” and exact circuit behaviors.

 

<div>

<div class="wysiwyg-text-align-center">

![manley-voxbox.png](9491bc8727275b25e6c3b66f8928a855303eb039.png)*Manley VOXBOX Channel Strip*

</div>

</div>

------------------------------------------------------------------------

# Operational Overview

This section provides a general overview of VOXBOX operational concepts. For specific details about individual controls, see <a href="#h_01H6ETTW6WE2BBP2GB4W6VDWY2" rel="undefined" target="_self">Manley VOXBOX Channel Strip Controls</a>.

## Signal Flow

A simplified version of the signal flow within the plug-in is shown in the diagram below. Understanding this signal flow can help you obtain a more predictable result. Note that unlike most channel strips, the compressor circuit is located before the preamplifier, even though the compressor controls are located to the right of the preamp controls in the interface.

![manley-voxbox-signal-flow-diagram.png](cb3105f3709455f5f67d9328780271090832fb28.png)

*Signal flow within VOXBOX*

## Control Groupings

Associated controls are grouped by processor function, as illustrated below. A notable exception is the transformer output option (XFMR switch). Although the transformer option switch is in the EQ control section, within the circuit itself the transformer is located after all other circuitry.<span class="image placeholder" original-image-src="https://help.uaudio.com/hc/en-us/articles/manley-voxbox-web-resources/image/manley-voxbox-callouts.png" original-image-title=""></span>

## Control groups in the VOXBOX interface

### Compressor

The VOXBOX compressor is based on a passive opto-isolator circuit with minimal components. Opto-isolators offer dynamic response characteristics that are musically pleasing when used with audio signals (Universal Audio's popular LA-2A compressor is based on an opto-isolator).

The opto-isolator adds no measurable distortion or noise and only 0.1 dB of insertion loss. Manley's all-passive circuitry and placement of the compressor before the preamplifier circuit allows for extremely low noise even when the signal is compressed.

The compression ratio is somewhat program dependent and non-linear, but it is generally similar to 3:1 ratios when compared to VCA-based compressors. Because this compressor is before the preamp, it does not have a conventional makeup gain control. The INPUT, GAIN THRESHOLD, and OUTPUT controls can be adjusted to compensate.

The amount of gain reduction occurring in the compressor can be displayed in the VU meter.

### Preamplifier

The VOXBOX preamp uses an all-tube amplifier circuit for gain. Note that the INPUT control is the primary "clean' input level control. The stepped GAIN control doesn't simply adjust the amount of amplification; instead it adjusts negative feedback within the preamp circuit.

In addition to gain, negative feedback also affects transient response, harmonic structure, clipping, and other sonic characteristics. As such, GAIN is typically used as a color control and the INPUT and/or OUTPUT controls can then be used to normalize signal levels.

### Equalizer

The VOXBOX EQ is based on the Pultec MEQ-5 midrange equalizer. Manley has extended the MEQ-5's capabilities with additional frequency bands for full-range sonic control.

Three EQ bands are available, each with 11 selectable center frequencies. The Low and High bands offer up to 10 dB of boost, while the Midrange band offers up to 10 dB of cut.

The EQ circuitry is 100% passive. Each EQ frequency band contains only one capacitor, one inductor, a conductive plastic pot, and a gold contact switch in the audio path for pristine signal quality. There are no tubes, transistors, or other active components in the EQ circuit.

### De-Esser / Limiter

A second opto-isolator limiter is located after the EQ circuit. A passive notch filter can be applied to the limiter's dynamic control sidechain, which enables de-ess functionality for sibilance control.

Four sibilant frequencies can be selected for the sidechain's notch filter. Sidechain filtering can be disabled to repurpose the de-esser as a secondary limiter. THRESHOLD controls the amount of de-essing or limiting.

The limiter has a compression ratio of 10:1 (the ratio is somewhat program dependent) and up to 20 dB of limiting is available. The amount of gain reduction occurring in the de-esser can be displayed in the VU meter.

### Unmarked Controls

Some controls are continuous and have a range of zero to ten when viewed in controls mode (if supported by the DAW). As with the original hardware, these controls are not marked with absolute values and are designed to be set by ear instead of by selecting pre-defined values.<span class="image placeholder" original-image-src="https://help.uaudio.com/hc/en-us/articles/manley-voxbox-web-resources/image/manley-voxbox-hero.png" original-image-title=""></span>

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

------------------------------------------------------------------------

# Manley VOXBOX Channel Strip Controls

## Preamplifier Controls

### SOURCE

The SOURCE rotary switch provides an attenuation pad for the input signal. When set to MIC, the input signal is not attenuated. When set to LINE, the input signal is attenuated by approximately 4 dB.

**Tip:** Click the LINE or MIC text labels to select the source value.

<span class="image placeholder" original-image-src="https://help.uaudio.com/hc/en-us/articles/manley-voxbox-web-resources/image/unison-icon.png" original-image-title=""></span>

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table style="border-collapse: collapse;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; height: 0px; vertical-align: middle; width: 0;">![unison-icon1.png](Manley%20VOXBOX%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="height: 0px; vertical-align: targetNone; width: 13.7143%"><h4 id="01H7G3YDWPMMJG8X1YKKVKX9D0">Apollo Unison Interactions</h4></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; height: 0px; width: 15.1429%;"><p>When the plug-in is placed in the dedicated Unison insert for the preamp channel within Apollo's Console application or LUNA, the following behaviors apply:</p>
<ul>
<li>SOURCE switches between the MIC and LINE hardware inputs of the Apollo preamp channel, and Apollo's hardware input switch can also be used to perform the same function.</li>
<li>When Apollo's Hi-Z input is connected, SOURCE is automatically overridden and the switch has no effect.</li>
</ul></td>
</tr>
</tbody>
</table>
</figure>

### LOW CUT

The Low Cut (high pass) filter for the Mic, Line, and Hi-Z inputs is available via this three position switch. Available filter cutoff values are 120 Hz (up position) and 80 Hz (middle position). When set to FLAT (down position), the filter is bypassed.

The Low Cut filter has a gentle slope of 6 dB per octave with minimal phase shift. Low Cut is typically used to eliminate rumble and/or other unwanted low frequencies from the input signal.

**Tip:** Click the 120/80/FLAT text labels to select a filter value.

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table style="border-collapse: collapse;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; height: 0px; vertical-align: middle; width: 0;">![unison-icon1.png](Manley%20VOXBOX%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="height: 0px; vertical-align: targetNone; width: 13.7143%"><h4 id="01H7G3YDWPQX1MC6H8ESKX26VP">Apollo Unison Interactions</h4></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; height: 0px; width: 15.1429%;"><p>When the plug-in is placed in the dedicated Unison insert for the preamp channel within Apollo's Console application or LUNA, the following behaviors apply:</p>
<ul>
<li>Apollo's hardware filter switch can be used to toggle this parameter.</li>
<li>When toggling the Low Cut filter state with Apollo's hardware switch, the frequency previously set in the plug-in is used.</li>
</ul></td>
</tr>
</tbody>
</table>
</figure>

### POLARITY

The Polarity switch affects the Mic, Line, and Hi-Z inputs. When in the 0° (up) position, the input signal polarity is normal. When in the 180° (down) position, the polarity of the input channel's signal is inverted.

Polarity inversion can help reduce phase cancellations when more than one microphone is used to record a single source.

**Tip:** Click the text label to select the desired setting.

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table style="border-collapse: collapse;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; height: 0px; vertical-align: middle; width: 0;">![unison-icon1.png](Manley%20VOXBOX%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="height: 0px; vertical-align: targetNone; width: 13.7143%"><h4 id="01H7G3YDWQVBA5HYADW80TW06R">Apollo Unison Interaction</h4></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; height: 0px; width: 15.1429%;"><p>When the plug-in is placed in the dedicated Unison insert for the preamp channel within Apollo's Console application or LUNA, the following behavior applies:</p>
<ul>
<li>Apollo's hardware polarity switch can be used to toggle this parameter.</li>
</ul></td>
</tr>
</tbody>
</table>
</figure>

### INPUT

INPUT is the main level control at the input to the plug-in. It attenuates the signal before the compressor and preamplifier.

The available range is 0 to 10 but values are arbitrary. Rotate the knob counter-clockwise to decrease the signal level.

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table style="border-collapse: collapse;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; height: 0px; vertical-align: middle; width: 0;">![unison-icon1.png](Manley%20VOXBOX%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="height: 0px; vertical-align: targetNone; width: 13.7143%"><h4 id="01H7G3YDWQ0QGHA8PD034DMJ17">Apollo Unison Interactions</h4></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; height: 0px; width: 15.1429%;"><p>When the plug-in is placed in the dedicated Unison insert for the preamp channel within Apollo's Console application or LUNA, the following behavior applies:</p>
<ul>
<li>Apollo's hardware PREAMP knob can be used to adjust this parameter.</li>
<li>When Apollo is in Unison Gain Stage Mode, an orange dot is overlaid on this parameter indicating it is available for hardware control. For details, see the Unison chapter within the Apollo Software Manual.</li>
</ul></td>
</tr>
</tbody>
</table>
</figure>

### GAIN

This five-position switch sets the amount of negative feedback in the mic preamp (it is not a pad or simple gain control). Negative feedback affects the transient response, harmonic structure, clipping, and other sonic characteristics of the preamp. As such, it is typically used as a tone control.

GAIN values of 40, 45, 50, 55, and 60 dB are available.

**Tip:** Click the GAIN text labels to select the value.

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table style="border-collapse: collapse;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; height: 0px; vertical-align: middle; width: 0;">![unison-icon1.png](Manley%20VOXBOX%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="height: 0px; vertical-align: targetNone; width: 13.7143%"><h4 id="01H7G3YDWQHWDH31JC8SSNEH81">Apollo Unison Interaction</h4></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; height: 0px; width: 15.1429%;">When the plug-in is placed in the dedicated Unison insert for the preamp channel within Apollo's Console application or LUNA, and Apollo is in Unison Gain Stage Mode, Apollo's hardware PREAMP knob can be used to adjust this parameter. In this state, an amber dot is overlaid on the parameter indicating it is available for hardware control. For details, see the Unison chapter within the <a href="https://help.uaudio.com/hc/en-us/articles/13445960631700" target="_self">Apollo Software Manual</a>.</td>
</tr>
</tbody>
</table>
</figure>

## Compressor Controls

Note:** **Unlike most channel strips, the compressor circuit is located before the preamp circuit.

### SIDECHAIN LINK

When the plug-in is used in a stereo-in configuration, this switch allows the dynamics processors of both channels (left & right) to always be compressed in equal amounts or completely independently. When used in a mono-in configuration, this switch is locked in the LINK position.

**Tip:** Click a text label to select the desired setting.

**Note:** This function applies to both the main compressor circuit and the de-esser/limiter circuit.

### LINK

When set to LINK, the amount of compression is always the same for both channels. Stereo imaging at the input is maintained by preventing left-right shifting at the output when one channel has higher signal peaks compared to the other channel.

### SEPARATE

When set to SEPARATE, the amount of compression occurring is completely independent in both channels.

**Note:** If one channel has higher signal peaks than the other channel, the left-right imaging may shift at the output.

### COMPRESSOR BYPASS

When this switch is in the COMPRESS 3:1 (up) position, the passive opto-isolator compressor circuit is engaged. When in the BYPASS (down) position, the circuit is disabled and the other compressor controls have no effect.

**Tip:** Click a text label to select the desired setting.

When the compressor circuit is bypassed, processor usage is reduced. On the UAD-2 plug-in, if UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

### THRESHOLD

This continuously variable control, which is located after the INPUT control in the circuit, determines the amount of compression to be applied to the input signal. Rotate THRESHOLD clockwise to lower the threshold and increase compression. Signals below the threshold are not compressed.

### ATTACK

ATTACK sets the amount of time that must elapse after the input signal reaches the THRESHOLD level before compression is applied. Five rates are available: Slow, Medium Slow, Medium, Medium Fast, and Fast.

**Tip:** Click near the left of the value label to select the value.

The faster the attack, the more rapidly compression is applied to signals above the threshold. Slower attacks allow a signal's attack transients (for example, the pluck of a string) to pass without compression, which can produce a punchier sound.

Unlike typical compressors, slower RELEASE settings with VOXBOX will make ATTACK changes more obvious. VOXBOX is noted for the unusual way the attack ‘rides' above the reduction set by the release.

### RELEASE

RELEASE sets the amount of time that must elapse after the input signal drops below the THRESHOLD before compression processing is ceased. The release time slows as gain reduction approaches 0 dB; this behavior is a function of the opto-isolator.

Note that due to interactivity in the passive circuitry, RELEASE has some effect on attack rates.

**Tip:** Click near the right of the value label to select the value.

Five rates are available: Slow, Medium Slow, Medium, Medium Fast, and Fast. Each release setting is carefully tuned for specific time constants, as described in the table below.

<figure class="wysiwyg-table" style="width: 100%;">
<table>
<thead>
<tr>
<th style="width: 20%">Rate Setting</th>
<th style="width: 20%">Time (seconds)</th>
<th style="width: 60%">Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td style="width: 20%">Slow</td>
<td style="width: 20%">5.0</td>
<td style="width: 60%">Very slow release for the most inaudible compression</td>
</tr>
<tr>
<td style="width: 20%">Medium Slow</td>
<td style="width: 20%">2.0</td>
<td style="width: 60%">Typical choices for vocals</td>
</tr>
<tr>
<td style="width: 20%">Medium</td>
<td style="width: 20%">1.0</td>
<td rowspan="2" style="width: 60%">Much like old LA-2A's but also tuned for drums and bass. Works well with dynamic broadcast audio. Pumps a bit when Attack is set to Slow.</td>
</tr>
<tr>
<td style="width: 20%">Medium Fast</td>
<td style="width: 20%">0.5</td>
</tr>
<tr>
<td style="width: 20%">Fast</td>
<td style="width: 20%">0.3</td>
<td style="width: 60%">Mimics the Manley Electro-Optical Limiter and works best in the range of 3 to 8 dB of compression</td>
</tr>
</tbody>
</table>
</figure>

*Compressor release times*

## Equalizer Controls

### EQ BYPASS

When this switch is in the EQ IN (up) position, the passive equalizer circuit is engaged. When in the BYPASS (down) position, the circuit is disabled and the other EQ controls have no effect.

**Tip:** Click the text label to select the desired setting.

When the EQ circuit is bypassed, processor usage is reduced. On the UAD-2 plug-in, if UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

### LOW PEAK

This continuous knob sets the amount of low EQ band gain applied to the LOW FREQUENCY value. The available range is 0 to 10 dB.

### LOW FREQUENCY

This rotary switch determines the frequency of the equalizer's low band. Eleven values are available (Hz): 20, 35, 50, 70, 100, 150, 200, 300, 500, 700, and 1000.

**Tip:** Click the text label to select the desired frequency.

**Note:** This switch has no effect when LOW PEAK is set to 0 dB.

### MID DIP

This continuous knob sets the amount of mid EQ band cut applied to the MID FREQUENCY value. The available range is 0 to -10 dB.

### MID FREQUENCY

This rotary switch determines the frequency of the equalizer's mid band. Eleven values are available (Hz, kHz): 200, 300, 500, 700, 1.5K, 2K, 3K, 4K, 5K, and 7K.

**Tip:** Click the text label to select the desired frequency.

**Note:** This switch has no effect when MID DIP is set to 0 dB.

### HI PEAK

This continuous knob sets the amount of low EQ band gain applied to the HIGH FREQUENCY value. The available range is 0 to 10 dB.

### HIGH FREQUENCY

This rotary switch determines the frequency of the equalizer's high band. Eleven values are available (kHz): 1.5K, 2K, 3K, 4K, 5K, 6.4K, 8K, 10K, 12K, 16K, and 20K.

**Tip:** Click the text label to select the desired frequency.

**Note:** This switch has no effect when HI PEAK is set to 0 dB.

## De-Esser / Limiter Controls

### DE-ESS BYPASS

When this switch is in the DE ESS (up) position, the de-esser/limiter circuit is engaged. When in the BYPASS (down) position, the circuit is disabled and the other de-esser/limiter controls have no effect.

**Tip: **Click the text label to select the desired setting.

When the de-esser circuit is bypassed, processor usage is reduced. On the UAD-2 plug-in, if UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

### DE-ESS SELECT

This rotary switch defines the center frequency of the dynamic control sidechain notch filter. Four sibilant frequencies are available (kHz): 3K, 6K, 9K, and 12K. The value is typically set to the center of the undesirable frequency range to be reduced.

When set to LIMIT 10:1, the sidechain notch filter is bypassed and the circuit behaves as an electro-optical limiter.

**Tip:** Click the text label to select the desired value.

### DE-ESS / LIMITER THRESHOLD

THRESHOLD controls the amount of de-essing or limiting by defining the signal level at which gain reduction is activated. Rotate the knob clockwise to lower the threshold and increase de-essing/limiting.

## Global Controls

### VU METER

The VU Meter displays average signal levels at several key points in the circuitry as well as gain reduction amounts in the main compressor and de-esser/limiter circuits. The displayed signal level is set with the METER SWITCH.

**Note:** The VU Meter displays average loudness and does not display signal peaks.

### METER SWITCH

This switch determines which signal is displayed in the VU Meter.

**Tip:** Click the text label to select the desired value.

### G-R (default setting)

Displays the amount of gain reduction occurring in the main compressor circuit.

### LINE IN

Displays average loudness at the input to the plug-in when SOURCE is set to LINE.

### PREOUT

Displays average loudness at the output of the preamplifier circuit.

**Note:** The VU Meter does not display levels at the output of the plug-in.

### EQ OUT

Displays average loudness at the output of the equalizer circuit.

### D-S

Displays average loudness at the output of the de-esser/limiter.

### TRANSFORMER BYPASS

When this switch is in the XFMR IN (up) position, the output signal is routed through the output transformer and the signal is slightly colored. When in the BYPASS (down) position, the transformer is bypassed and the signal is routed directly to the output.

In the original hardware unit, the transformer is in the balanced output circuit connection and the unbalanced output connection bypasses the transformer. In the digital realm, this switch conveniently provides both options.

**Tip:** Click a text label to select the desired setting.

When the transformer circuit is bypassed, processor usage is reduced. On the UAD-2 plug-in, if UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

### OUTPUT

OUTPUT is a clean digital gain control that adjusts the signal level at the output of the plug-in. The available range is -60 dB to +12.0 dB.

**Tip:** Click the "0" text label to return the value to 0 dB.

This control, which does not exist on the original hardware, facilitates the ability to maintain unity gain and/or maximize color of the overall signal. For example, compression and EQ can be adjusted to taste, while using OUTPUT to normalize levels.<span class="image placeholder" original-image-src="https://help.uaudio.com/hc/en-us/articles/manley-voxbox-web-resources/image/unison-icon.png" original-image-title=""></span>

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table style="border-collapse: collapse;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; height: 0px; vertical-align: middle; width: 0;">![unison-icon1.png](Manley%20VOXBOX%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="height: 0px; vertical-align: targetNone; width: 13.7143%"><h4 id="01H7G3YDWQ4GD17JNC0WVZGPYD">Apollo Unison Interaction</h4></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; height: 0px; width: 15.1429%;">When the plug-in is placed in the dedicated Unison insert for the preamp channel within Apollo's Console application or LUNA, and Apollo is in Unison Gain Stage Mode, Apollo's hardware PREAMP knob can be used to adjust this parameter. In this state, a green dot is overlaid on the parameter indicating it is available for hardware control. For details, see the Unison chapter within the <a href="https://help.uaudio.com/hc/en-us/articles/13445960631700" target="_self">Apollo Software Manual</a>.</td>
</tr>
</tbody>
</table>
</figure>

### POWER

The is the plug-in's overall bypass control for comparing the processed and unprocessed signal. In the ON (up) position, signal processing is active. In the down position, the unprocessed signal is heard.

**Tip:** Processor usage is reduced when the POWER is off. UAD-2 DSP usage is reduced when the POWER is off if DSP LoadLock is disabled in the Configuration panel within the UAD Meter & Control Panel application.

### READY LED

The READY LED, located below the POWER switch, illuminates three seconds after powering on. In the original hardware, the LED indicates the unit is ready for use. In the plug-in, this behavior is a cosmetic emulation only. The plug-in is fully functional when it is instantiated and/or enabled.

------------------------------------------------------------------------

# Additional Information

The original user manual written by Manley Labs for the hardware unit contains a wealth of great information about the philosophy, design decisions, and use of the VOXBOX. It is highly recommended reading for those interested in technical details. The manual can be found on the Manley website, along with info about their other great products.

[www.manley.com](https://www.manley.com/)

<div>

<div class="wysiwyg-text-align-center">

![VoxBox-HW-xlarge.jpg](a37277f5fdd4b79839070351d04d6a90aee8df5c.jpg)<span class="image placeholder" original-image-src="https://help.uaudio.com/hc/en-us/articles/manley-voxbox-web-resources/image/VoxBox-HW-xlarge.jpg" original-image-title=""></span>

</div>

</div>

*Original Manley VOXBOX Channel Strip hardware*

<div>

<div class="wysiwyg-text-align-center">

![manleylogo2013.png](92a6cd3ee9312e533344f20dd5e737edbb6bf322.png)<span class="image placeholder" original-image-src="https://help.uaudio.com/hc/en-us/articles/manley-voxbox-web-resources/image/manleylogo2013.png" original-image-title=""></span>

</div>

All visual and aural references to the VOXBOX and all use of MANLEY's trademarks are being made with written permission from MANLEY LABORATORIES INCORPORATED. Special thanks to EveAnna Manley and Chuck Zwicky.

<span class="wysiwyg-font-size-small">v260205</span>

</div>

