---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/33030906406676-Empirical-Labs-EL7-Fatso-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'Empirical Labs EL7 Fatso Manual'
word_count: 3797
---

# Empirical Labs EL7 Fatso Manual


## Get the rich sound of magnetic tape, class A transformers, and tube circuits.

Able to warmly burnish frequencies and transients, or crush them with thick saturation, the FATSO Jr./Sr. Tape Sim. & Compressor plug-in for UAD-2 hardware and Apollo interfaces exhaustively emulates the iconic, industry standard Empirical Labs hardware.

Used by legendary engineers Ed Cherney, Al Schmitt, and Brendan O'Brien, the FATSO can also increase the apparent volume of your source material. The FATSO plug-in is officially endorsed and scrutinized for accuracy by its designer, Dave Derr.

- Inject your tracks and mixes with the warm, musical qualities of magnetic tape, tubes, and class A transformers
- Lightly color, or destroy, drums, vocals, and more with tube and tape saturation
- Harness "plug-in only" Tranny Saturation, Sidechain Filtering, and Stereo/Mono controls
- Dial-in a wealth of analog textures with Warmth and Spank controls

## Go From Tame — to Trashed

The FATSO plug-in offers a wide palette of possibilities for adding fat analog character and cohesiveness to your DAW tracks. It's also a creative tool, able to add varying degrees of saturation — from subtle to severe — on any source. The FATSO's Input control lets you dial in shades of harmonic generation and distortion, while the Tranny and Warmth features provide varying amounts of of tape and tube tone.

## Plug-In Only Features

The FATSO plug-in's versatility is greatly expanded with the addition of Dave Derr's custom mods. The FATSO Sr. offers a "Tranny" saturation control, Sidechain Filtering and deeper compression parameters including Threshold, Attack and Release. These special FATSO Sr. mods are only available with the UAD Powered Plug-In version of this essential studio tool.

<div>

<div class="wysiwyg-text-align-center">

![FatsoJr.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/8ac81e6a44fb222a3ce59ad02ff1338534416dd5.png)

</div>

</div>

*FATSO Jr.*

------------------------------------------------------------------------

# FATSO Functional Overview

## Four Processing Types

The FATSO was essentially designed to integrate frequencies in a musical manner and provide some foolproof vintage sounding compression. Generally, it is difficult to make the unit sound unnatural due to its vintage topology. FATSO provides four types of processing: Saturation and Distortion, Warmth, Tranny, and Compression.

## Saturation and Distortion Processor

### Harmonic Generation & Soft Clipper

Basically, this is a distortion generator associated with the Input knobs. Anytime you pass a signal through the FATSO, it passes through this part except in bypass. This processing is useful to softly but instantly clip peaks and transients, allowing a higher average level. Aggressive distortion can also be achieved through the same controls.

It is well known that the triode distortion in tube circuits produces lots of 2nd order and 3rd order harmonics, in somewhat varying ratios. Analog tape also saturates in this manner. The 3rd order harmonic is induced in the FATSO by increasing the level through two discrete distortion circuits and is usually the result of flattening the tops and bottoms of waveforms. Second order harmonics are also added especially while compressing in the FATSO.

The FATSO's input clipping will give you the same result. These lower order harmonics form "the octave" and "the octave and a fifth" to the fundamental musical tones. They are actually "musical" distortion. Harmonics above the 2nd and 3rd get increasingly harsh and unmusical, and therefore should be lower in amplitude (\<-60 dB) to keep within our line of thinking. Second harmonic is considered to be the warmest and most "consonant" harmonic distortion.

## Warmth Processor

### High Frequency Saturation

This circuit is meant to simulate the softening of the high frequencies that occurs with analog tape. Basically, as the Warmth is increased, overly bright signals and transients will be quickly attenuated. The time constants are very nearly instant, so the high frequencies return very quickly after a loud burst.

The Warmth circuit is by far the most complex part of the FATSO. Basically, it is a very strange high frequency (HF) gain control circuit or HF limiter. It is very unobtrusive in operation since it gets in and out of the way very quickly. The desired result is akin to the HF saturation that analog tape exhibits when the HF amplitude interacts with the tape recorder bias to produce "self erasure" of certain frequencies. The nature of the filter allows the corner frequency to move as attenuation occurs.

There is only one control for Warmth but there are other ways to control the overall action of this circuit. If you do decide to use the compressor, set it up first because it affects the operation of Warmth. There is heavy interaction between the compressor and Warmth settings. Perhaps the best way to think of the settings is as compressor threshold, with 7 having the lowest threshold and the most Warmth, responding quickly and often to high frequency content. Just remember that instead of controlling the overall level, the Warmth "compressor" threshold only affects the high frequencies.

## The Tranny Processor

### Transformer & Tape Head Emulation

The Tranny circuit ("Tranny" is short for transformer) is a simulation of the effect of input and output transformers of older devices and adds the low frequency harmonics that characterize analog tape. This is extremely useful on pure low frequency type tones that don't cut through small speakers. It adds upper "warm" harmonics to frequencies below 150 Hz, especially those even lower such as 40 Hz, the low string on a bass guitar, helping it to cut through on smaller speakers.

Transformer design and use is an art, and there are always trade-offs. However, it has been widely known that a good audio transformer circuit can do wonderful things to an audio signal. This was the goal of the Tranny circuit. The hardware designers tried to emulate the desirable characteristics of the good old input/output transformers in a consistent musical way, and in a selectable fashion. The addition of harmonics and peak saturation along with frequency and phase changes on the low frequencies occurs. They found that they could capture the low frequency effects of large and now expensive older output transformers in a weird, internally buffered switchable design.

To sum up the musical results of the Tranny circuit, there will be a little more edge in the midrange, and the super low frequencies will have been harmonically altered in a way that allows them to sound louder, even though the peaks are less than the original. Playback on small speakers will show an improved audibility of low end from the result of the psycho-acoustically-pleasing distortion the Tranny adds.

## Compression Processor

### Classic Knee Compression, Empirical Labs Style

These are your typical automatic leveling devices that you find used on just about every instrument and vocal track, as well as on the overall buss. Only it's Empirical Labs compression - smooth and sweet, but in your face!

There are essentially four discrete compressors in the FATSO: Buss, General Purpose (G.P.), Tracking, and Spank. Switching modes simultaneously sets the compressor threshold, ratio, attack, and decay. This was done to provide an easy-to-set, yet versatile group of curves. The release curve of all types is logarithmic, meaning it lets off quickly at first and then slows. This release curve is a big part of the FATSO's compressor sound.

**Note:** Threshold, attack, and decay values can be modified in the FATSO Sr.

### Buss

Buss mode (green LED) is a very gentle 2:1 type ratio with slow attack, fast release, and very soft knee. One to four dB of gain reduction is typical for this compressor type. Five or more dB of Buss compression is hitting it hard!

### G.P.

General Purpose mode (yellow LED) is medium attack slow release type that sounds pretty invisible while able to maintain a consistent RMS level. The slow release will not pull things into your face unnaturally.

### Tracking

Tracking mode (green and yellow LED) is an 1176 type compressor that is great for tracking instruments and vocals during the recording process or during mixdown.

### Spank

Spank mode (red LED) is a radical limiter type compressor that was specifically designed to emulate the nice squeeze of the older SSL talkback compressors from the 70's & 80's, but with quite a bit of higher fidelity. Note that Spank's aggressive nature will tend to dominate when combined with any of the other modes.

------------------------------------------------------------------------

# FATSO Controls

General notes about FATSO controls are below, followed by a detailed description of each channel-specific control, the global controls, and the FATSO SR. controls.

## Mono/Stereo Operation

The FATSO is a two-channel device capable of running in stereo or dual-mono modes. Controls for both channels can be linked for ease of stereo operation when both channels require the same values (see [Link Controls](#h_01JF8FGAGR4CFVR7B311Y2TDTW)), or unlinked when dual-mono operation is desired.

Each of the channel functions has its own separate group of controls (one set each for channels 1 and 2). Since the controls for each of the two channels are identical, they are detailed only once.

**Note:** When the FATSO is used in a mono-in/mono-out configuration, the channel 2 controls have no effect and the LINK parameters are disabled.

## Pushbuttons

All FATSO pushbuttons are momentary. The value of the parameter increments by one step each time the button is clicked (holding the button down does not continue to increment the value). The value cycles to the beginning when the end of the range is reached. Clicking on the control LED indicators has no effect, with the exception of the LINK parameters.

**Tip:** Shift+click any pushbutton to decrement its value by one.

------------------------------------------------------------------------

# Channel Controls

**Note:** The channel controls are identical for channels 1 and 2.

<div>

<div class="wysiwyg-text-align-center">

![fatso-input.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/b9eb0866ea2ed6bf0000a757fae117e260928a30.png)

</div>

</div>

Input

The Input knob defines the signal level going into the plug-in. Higher levels result in a more saturated signal. Levels above 0 VU provide dramatically higher distortion characteristics, especially when clipped (as indicated by the Pinned LED).

When the compressor is active, higher input values also result in more compression, as indicated by the gain reduction meters.

**Note:** This control has no effect when Bypass is active.

## THD Indicators

The Total Harmonic Distortion (THD) LEDs provide some reference operating levels. The yellow "0 VU" LED light indicates around 1% THD, and the red "Pinned" LED indicates 5% THD or more. These LEDs are an excellent guide to where the user is in the "Grunge Department." You will find that the harmonic distortion is generally more obvious on overall mixes and complex programs. On individual instruments, sometimes 10% distortion sounds "fat" and "analog" and isn't heard as distortion at all.

## Compressor Mode

The COMP button defines which compressor mode is active. See [Compression Processor](#h_01JF7BP4632CZB0Q2CWNJVDGDG) for a description of the modes.

Spank mode can be combined with any of the other three modes for a total of seven available compressor modes.

**Note:** Generally speaking, the Input and compressor Mode controls should be set before the other FATSO processor settings, because of the high degree of interaction between the compressor and the other processors.

## Mode LEDs

The three Mode LEDs indicate the active mode. Refer to the table below for each specific value. The compressor is inactive when all Mode LEDs are off.

| Compressor Mode LED State | Active Compressor Mode(s)       |
|---------------------------|---------------------------------|
| All Unit                  | Compressor inactive             |
| Green                     | Buss                            |
| Yellow                    | General Purpose (G.P.)          |
| Green + Yellow            | Tracking (most versatile ratio) |
| Red                       | Spank                           |
| Red + Green               | Spank + Buss                    |
| Red + Yellow              | Spank + General Purpose         |
| Red + Green + Yellow      | Spank + Tracking                |

*Compressor Mode LED States*

## GR Meter

The Gain Reduction Meter displays the amount of gain reduction occurring within the FATSO compressor, expressed as negative dB values.

**Note:** At extreme settings, the GR Meter may indicate gain reduction is occurring even when the compressor is disabled. This behavior is identical to the hardware unit.

## Warmth

This button defines the Warmth amount. Warmth simulates the softening of the high frequencies that occurs with analog tape saturation (see [Warmth Processor](#h_01JF7BM68V6M3DE4ASSBKD26JD) for a detailed description). Higher values increase the Warmth, as indicated by the Warmth Meter.

Values of 1 to 7 are available. The current value is indicated by the arc of Warmth LEDs. Warmth is off when all LEDs are unlit.

## Warmth Meter

The Warmth Meter is a very accurate display of the amount of high frequency attenuation, as defined by the Warmth button. The meter shows the amount of HF gain reduction occurring at 20 kHz.

**Note:** At extreme settings, the Warmth Meter may indicate activity even when Warmth is disabled. This behavior is identical to the hardware unit.

## Bypass/Tranny

This black button is a multifunction control. Clicking the button repeatedly cycles through Tranny, Bypass, and Tranny Off modes. The currently active mode is indicated by the adjacent LEDs.

### Tranny (green LED)

[The Tranny Processor](#h_01JF7BMX4QZJ3JWQVG1RM08QYH) is active in this mode. The Tranny circuit adds frequency "rounding," low order clipping, intermodular distortion and transient clipping. On FATSO Sr., the Tranny amount can be set with the [Tranny Level](#h_01JF8FN1FYY6P7DMWPXM97AGJ2) control

**Note:** Disabling Tranny will yield a significant reduction in UAD DSP usage when DSP LoadLock is disabled. If DSP LoadLock is enabled (the default setting), disabling Tranny will not reduce DSP usage.

### Tranny Off (red and green LEDs off)

In this mode, the Tranny processor is inactive but the other processors are active. This mode requires less UAD DSP than when Tranny is active.

### Bypass (red LED)

All FATSO controls and processing for the channel are inactive in this mode.

**Note:** UAD DSP load is not reduced in Bypass mode. If you want to reduce UAD DSP usage when bypassing both channels of the FATSO, use the [Power](#h_01JF8FJPCY1S8CVBMM6QVRRNMM) switch instead.

## Output

The Output knob controls the signal level that is output from the plug-in.

**Note:** This control has no effect when [Bypass/Tranny](#h_01JF8FDT3C2D2SKY12H9TZBW79) is active.

------------------------------------------------------------------------

# Global Controls

The global controls are not channel-specific; they apply to both channels.

## Link Compress

The control signal sidechains of the gain reduction processors for channels 1 and 2 can be linked using the Link Compress function.

<div>

<div class="wysiwyg-text-align-center">

![fatso-link-compress.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/5bbcda0386e5f68152378448e01359d9e20e2bad.png)

</div>

</div>

To activate Link Compress, click the LINK COMPRESS text or LED on Ch1, on the left. The feature is active when the LED is illuminated.

In typical use on stereo signals, Link Compress should be active so the stereo imaging is maintained. If the compressor is inactive ([Compressor Mode](#h_01JF8GGEKCZWP0G754H4NHG4YD)), or when FATSO is used in a mono-in/mono-out configuration, this control has no effect.

Important: Unlike the other controls for channels 1 and 2, which are identical on the left and right sides of the interface, the Link COMPRESS function is on the left side only (not to be confused with Link CONTROLS, which is on the right side only).

## Link Controls

The parameter controls for channels 1 and 2 can be linked using the Link Controls function.

<div>

<div class="wysiwyg-text-align-center">

![fatso-link-controls.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/5a3fdeb68fe4165365812d11a974af1ab0dfce30.png)

</div>

</div>

To activate Link Controls, click on the LINK CONTROLS text or LED on Ch2, on the right. The feature is active when the LED is illuminated.

**Note:** Although the left/right Warmth and Tranny controls are linked when Link Controls is active, the actual Warmth and Tranny processors are not stereo linked. This behavior is identical to the original hardware.

### Controls Linked

Link Controls is provided for stereo operation when both channels require the same values. When enabled, the right channel controls "snap" to match the left channel control values, and modifying any channel control causes its stereo counterpart control to move to the same position (channel 1 & 2 controls are ganged together in this mode).

Important: Right channel parameter values are lost the moment Link Controls is enabled.

### Controls Unlinked

**Important:** Unlink the controls when dual-mono operation is desired. Channel 1 and 2 controls are completely independent in this mode, and automation data is written and read by each channel separately. Link Controls is disabled when the FATSO is used in a mono-in/mono-out configuration.

**Important:** Unlike the other controls for channels 1 and 2, which are identical on the left and right sides of the interface, the Link CONTROLS function is on the right side only (not to be confused with Link COMPRESS, which is on the left side only).

## Power

The Power toggle switch determines whether the plug-in is active. It is useful for comparing the processed settings to the original signal. When Power is in the Off (down) position, plug-in processing is disabled, UAD DSP usage is reduced, and all LEDs are unlit.

**Note:** UAD-2 DSP usage is reduced only when DSP LoadLock is disabled. If DSP LoadLock is enabled (the default setting), disabling Power will not reduce DSP usage.

Click the lower portion of the switch to disable the plug-in; click the upper portion to activate (or click+drag up/down on the switch).

------------------------------------------------------------------------

# FATSO Sr. Controls

These controls are unique to the FATSO Sr. However, because the additional controls in the FATSO Sr. do not add to the DSP functionality of the FATSO Jr., both plug-ins use the same amount of UAD DSP.

**Note:** The additional controls in the FATSO Sr. do not add to the DSP functionality of the FATSO Jr. Both plug-ins use the same amount of UAD DSP.

<div>

<div class="wysiwyg-text-align-center">

![fatso-sr.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/32a3c9a9e6a5fa9424da28c3fd642a5519e1a050.png)

</div>

</div>

## Threshold

This knob enables manual threshold control of the FATSO compressor. Higher values lower the threshold, and therefore increase the amount of compression. A value of 5 is the unity setting.

The [Input](https://help.uaudio.com/hc/en-us/articles/empirical-labs-el7-fatso.html#_idTextAnchor006) control also affects the compression threshold. Generally speaking, set the amount of desired signal saturation with Input first, then adjust Threshold as desired.

## Filter (HP SIDE FILT)

Filter regulates the cutoff frequency of the filter on the compressor's control signal sidechain. When active, frequencies below the filter value are not passed to the sidechain. Values of 60 Hz, 120 Hz, 240 Hz, 480 Hz, and Off are available. The filter slope is 6 dB per octave. When the compressor is disabled, Filter has no effect and its LED turns off. When the compressor is enabled, Filter returns to its original value.

**Tip:** Removing low frequency content from the sidechain can reduce excessive gain reduction and/or "pumping" on bass-heavy audio signals without reducing bass content of the audio signal itself.

**Note:** The Filter parameter affects the control signal (sidechain) of the compressor only. It does not filter the audio signal.

## Attack

Attack sets the amount of time that must elapse once the input signal reaches the threshold level before compression is applied. The faster the attack, the more rapidly compression is applied to signals above the threshold.

The available attack time values are 0.9ms, 10ms, 30ms, 60ms, and Default (unlit). The unlit behavior is depends upon whether or not the compressor is active. These behaviors are described below.

**Note:** Attack values are approximations. Actual attack and release times may vary depending on the compressor mode selected.

### Attack LEDs Unlit - Compressor Active

When the compressor is enabled and all Attack LEDs are unlit, the attack characteristic of the active compressor mode in FATSO Jr. is used. This "default" FATSO Jr. behavior can then be manually overridden with the Attack button. However, when "pure" Spank mode is active, Attack cannot be modified. When Spank mode is combined with another compressor mode, Attack can be changed, but the results are typically very subtle.

**Tip:** After experimenting with other time constants, one can return to the default attack setting of the FATSO Jr. if desired by cycling the attack control until NO LEDs are lit (which indicates the default FATSO Jr. time constant).

### Attack LEDs Unlit - Compressor Inactive

When the compressor is disabled and all Attack LEDs are unlit, the button is disabled.

**Note:** This control has no effect when the compressor is inactive, or when it is in "pure" Spank mode (see [Compressor Mode](#h_01JF8GGEKCZWP0G754H4NHG4YD)).

## Release

Release sets the amount of time it takes for compression to cease once the input signal drops below the threshold level. Slower release times can smooth the transition that occurs when the signal dips below the threshold, especially useful for material with frequent peaks. However, if you set too large of a Release time, compression for sections of audio with loud signals may extend to lengthy sections of audio with lower signals.

The available release time values are 0.05s, 0.1s, 0.s, 0.5s, and Default (unlit). The unlit behavior is depends upon whether or not the compressor is active. These behaviors are described below.

**Note:** Release values are approximations. Actual attack and release times may vary depending on the compressor mode selected.

### Release LEDs Unlit - Compressor Active

When the compressor is enabled and all Release LEDs are unlit, the release characteristic of the active compressor mode in FATSO Jr. is used. This "default" FATSO Jr. behavior can then be manually overridden with the Release button. However, when "pure" Spank mode is active, Release cannot be modified. When Spank mode is combined with another compressor mode, Release can be changed, but the results are typically very subtle.

**Tip:** After experimenting with other time constants, one can return to the default release setting of the FATSO Jr. if desired by cycling the release control until NO LEDs are lit (which indicates the default FATSO Jr. time constant).

### Release LEDs Unlit - Compressor Inactive

When the compressor is disabled and all Release LEDs are unlit, the button is disabled.

**Note:** This control has no effect when the compressor is inactive, or when it is in "pure" Spank mode (see [Compressor Mode](#h_01JF8GGEKCZWP0G754H4NHG4YD)).

## Tranny Level

This control determines the amount of Tranny processing (see [The Tranny Processor](#h_01JF7BMX4QZJ3JWQVG1RM08QYH) for a detailed description). Higher values make the Tranny effect more prominent. Increasing the Tranny level also increases the signal THD (see [THD Indicators](#h_01JF8GGBN9X73CG965JF1J7DHT)), and the sensitivity of the [Warmth](#h_01JF7BM68V6M3DE4ASSBKD26JD) processor. A value of 5 is the unity setting.

**Note:** This control has no effect when the Tranny processor is inactive.

## LF Sat LED

The LF Sat (Low Frequency Saturation) LED indicates the amount of LF saturation in the Tranny processor. Higher Tranny Level values increase the LF saturation.

## FATSO Jr. Presets

When loading presets created on the FATSO Jr. into the FATSO Sr., the parameters that are unique to FATSO Sr. are set to their default control values. The default values of the unique FATSO Sr. parameters are: Threshold/Tranny knobs at 5, and Filter/Attack/Release buttons off.

<div>

<div class="wysiwyg-text-align-center">

![EmpiricalLabs.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/764c06b81dd521361a18b3f836b5816e4e24c8b2.png)

</div>

</div>

<div class="wysiwyg-text-align-center">

![FATSO-HW.png](Empirical%20Labs%20EL7%20Fatso%20Manual_assets/43893506dabbf90e642be818658977516790d4b8.png)

</div>

*Empirical Labs EL7 FATSO Jr. hardware*

All visual and aural references to the FATSO and all use of EMPIRICAL LABS's trademarks are being made with written permission from EMPIRICAL LABS, INC. Special thanks to Dave Derr for assistance with this project.

