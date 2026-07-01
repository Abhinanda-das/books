---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/35426861699220-CS-1-Channel-Strip-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'CS-1 Channel Strip Manual'
word_count: 3428
---

# CS-1 Channel Strip Manual


# Overview

The CS-1 Channel Strip provides the EX-1 Equalizer and Compressor, DM-1 Delay Modulator, and RS-1 Reflection Engine combined into one plug-in. Individual effects in the CS-1 Channel Strip can be bypassed when not in use to conserve UAD DSP loads.

The CS-1 is provided for compatibility with sessions created with UAD versions prior to v8.2. In UAD v8.2 and later, the EX-1, DM-1, DM-1L, and RS-1 plug-ins are replaced by the newer Precision Channel Strip, Precision Delay Modulation/Delay Modulation Long, and Precision Reflection Engine plug-ins, respectively. See [CS-1 Compatibility with Prior Sessions](#h_01JNPRZ9J89GTZ9S7R9NB5081C) for related information.

![CS-1.png](CS-1%20Channel%20Strip%20Manual_assets/33aebf2a6fc6ad51eab59e264eff947ecc1f66f8.png)

*CS-1 Channel Strip*

------------------------------------------------------------------------

# EX-1 Equalizer and Compressor

The EX-1 plug-in consists of a five-band parametric EQ and compressor.

![CS-1-eq-comp.png](CS-1%20Channel%20Strip%20Manual_assets/022eb286eb57f35cc117a21ebd09fa16be12e61b.png)

*EX-1 EQ/Compressor*

------------------------------------------------------------------------

# EX-1 Equalizer Controls

The Equalizer portion of the EX-1 is a five-band fully parametric EQ. Each band has its own set of controls. The first two bands can also be enabled to function as low-shelf or high-pass filter. Similarly, the last two bands can be enabled to function as either a high-shelf or low-pass filter.

## Band Disable Button

Each band can be individually deactivated with the Band Disable button. All bands default to enabled (brighter blue). To disable any band, click the Disable button. The button is darker blue when the band is disabled.

You can use these buttons to compare the band settings to that of the original signal, or to bypass the individual band.

## Gain (G) Knob

The Gain control determines the amount by which the frequency setting is boosted or attenuated. The available range is ±18 dB.

## Frequency (fc) Knob

Determines the center frequency to be boosted or attenuated by the Gain setting. The available range is 20 Hertz to 20 kiloHertz. When operating at sample rates less than 44.1kHz, the maximum frequency will be limited.

## Bandwidth (Q) Knob

Sets the proportion of frequencies surrounding the center frequency to be affected. The Bandwidth range is 0.03-32; higher values yield sharper bands.

In either of the first two bands, when the Bandwidth value is at minimum the band becomes a low-shelf filter, and at maximum the band becomes a high-pass filter.

Similarly, in either of the last two bands, when the Bandwidth value is at minimum the band becomes a high-shelf filter, and at maximum the band becomes a low-pass filter.

## Enable/Bypass Switch

Globally enables or disables all bands of the Equalizer. You can use this switch to compare the EQ settings to the original signal or bypass the entire EQ section to reduce UAD DSP load (unless UAD-2 DSP LoadLock is enabled).

## Output Knob

Adjusts the signal output level of the plug-in. This may be necessary if the signal is dramatically boosted or reduced by the EQ and/or compressor settings.

------------------------------------------------------------------------

# EX-1 Compressor Controls

## Attack Knob

Sets the amount of time that must elapse, once the input signal reaches the Threshold level, before compression will occur. The faster the Attack, the more rapidly compression is applied to signals above the Threshold. The range is 0.05 milliseconds to 100 ms.

## Release Knob

Sets the amount of time it takes for compression to cease once the input signal drops below the Threshold level. Slower release times can smooth the transition that occurs when the signal dips below the threshold, especially useful for material with frequent peaks. However, if you set too large of a Release time, compression for sections of audio with loud signals may extend to lengthy sections of audio with lower signals. The range is 25 milliseconds to 2500 milliseconds (2.5 seconds).

## Ratio Knob

Determines the amount of gain reduction used by the compression. For example, a value of 2 (expressed as a 2:1 ratio) reduces the signal by half, with an input signal of 20 dB being reduced to 10 dB. A value of 1 yields no compression. Values beyond 10 yield a limiting effect. The range is 1 to Infinity.

## Threshold Knob

Sets the threshold level for the compression. Any signals that exceed this level are compressed. Signals below the level are unaffected. A Threshold of 0 dB yields no compression. The range is 0 dB to -60 dB.

As the Threshold control is increased and more compression occurs, output level is typically reduced. However, the EX-1 provides an auto-makeup gain function to automatically compensate for reduced levels. Adjust the Output level control if more gain is desired.

## Meter Pop-up Menu

Determines whether the VU Meter monitors the Input Level, Output Level, Gain Reduction, or Meter Off. Click the menu above the meter display to select a different metering function.

## Enable/Bypass Switch

Enables or disables the Compressor.You can use this switch to compare the compressor settings to that of the original signal or bypass the entire compressor section to reduce UAD DSP load (unless UAD-2 DSP LoadLock is enabled).

## Compressor Output Knob

Adjusts the signal output level of the plug-in.

------------------------------------------------------------------------

# DM-1 Delay Modulator

The DM-1 Delay Modulator provides stereo effects for delay, chorus, and flange.

## DM-1L

The DM-1L is identical to the DM-1, except that the maximum available delay time per channel is 2400 milliseconds, and a link button is available for the delay time knobs.

**Note:** DM-1L requires more UAD memory resources than the DM-1.

![CS-1-delay-mod.png](CS-1%20Channel%20Strip%20Manual_assets/f731d72a7e5e673d1532b1a195ff0f1ab8fe5571.png)

*DM-1 Delay Modulator*

------------------------------------------------------------------------

# DM-1 Controls

## Sync Button

This button puts the plug-in into Tempo Sync mode. See the "Tempo Sync" chapter in the UAD System Manual for more information.

## L-R Delay Knobs

These knobs set the delay time between the original signal and the delayed signal for the left and right channels, respectively. When the Mode is set to one of the delay settings, the maximum delay is 300 msec (2400 ms with DM-1L). When the Mode is set to one of the chorus or flange settings, the maximum delay is 125 msec.

In the flanger modes, the L and R delay controls have slightly different functions than when in the chorus modes. The high peak of the flanger is controlled by the settings of the L and R delay controls. The low Peak of the flanger is determined by the setting of the Depth control.

## Link (DM-1L only)

The DM-1L Link button (located between the L/R delay time knobs) links the left and right delay knobs so that when you move one delay knob, the other follows. The ratio between the two knobs is maintained.

## Mode Drop Menu

Determines the DM-1 effect mode. The available modes are: Chorus, Chorus180, QuadChorus, Flanger1, Flanger2, Dual Delay, and Ping Pong Delay. In addition to reconfiguring the DM-1's settings, the Mode also determines the available parameter ranges for L/R Delay and Depth.

In Chorus mode, both oscillators (or modulating signals) are in phase.

In Chorus 180 mode, both oscillators (the modulating signals) are 180 degrees out of phase (inverted).

In QuadChorus mode, both oscillators (the modulating signals) are 90 degrees out of phase.

In Ping Pong delay mode, you will only get a ping-pong effect if you have a mono source feeding the DM-1 on a stereo group track or send effect. On a mono disk track, it works exactly like Dual Delay.

## Rate Knob

Sets the modulation rate for the delayed signal, expressed in Hertz.

## Depth Knob

Sets the modulation depth for the delayed signal, expressed as a percentage.

In Dual Delay and Ping Pong Delay modes, adjusting the Depth and Rate controls can offer some very otherworldly sounds.

## LFO Type Drop Menu

Determines the LFO (low frequency oscillator) waveshape and phase used to modulate the delayed signal. The waveshape can be set to triangle or sine, each with a phase value of 0, 90, or 180 degrees.

## Recirculation (RECIR) Knob

Sets the amount of processed signal fed back into its input. Higher values increase the number of delays and intensity of the processed signal.

Recirculation allows both positive and negative values. The polarity refers to the phase of the delays as compared to the original signal. If Recirculation displays a positive value, all the delays will be in phase with the source. If it displays a negative value, then the phase of the delays flips back and forth between in phase and out of phase.

In the flanger mode, Recir has the potential to make some very interesting sounds. Try turning RECIR fully clockwise or counter-clockwise, and set the delay to very short but different values.

The RECIR units are expressed as a percentage in all Modes except Dual Delay and Ping Pong. In these modes, RECIR values are expressed as T60 time, or the time before the signal drops 60 decibels.

## Damping Knob

This low pass filter reduces the amount of high frequencies in the signal. Turn down this control to reduce the brightness. Higher values yield a brighter signal. Damping also mimics air absorption, or high frequency roll-off inherent in tape-based delay systems.

## Wet/Dry Mix Knob

This control determines the balance between the delayed and original signal. Values greater than 50% emphasize the wet signal, and values less than 50% emphasize the dry signal. A value of 50% delivers equal signals. A value of 0% is just the dry signal.

Wet/Dry Mix allows both positive and negative values. The polarity refers to the phase of the delays as compared to the original signal. If a positive value is displayed, then all the delays will be in phase with the source. With a negative value, the delayed signal is flipped 180 degrees out of phase with the source.

## L-Pan Knob

Sets the stereo position for the left channel, allowing you to adjust the width or balance of the stereo signal. For a mono signal, L-Pan behaves as the level control for the left delay tap.

## R-Pan Knob

Sets the stereo position for the right channel, allowing you to adjust the width or balance of the stereo signal. For a mono signal, R-Pan behaves as the level control for the right delay tap.

## Enable/Bypass Switch

Enables or disables the Delay Modulator. You can use this switch to compare the DM-1 settings to the original signal or bypass the entire DM-1 section to reduce UAD DSP load (load is not reduced if UAD-2 DSP LoadLock is enabled).

## Output Knob

Adjusts the signal output level of the plug-in.

------------------------------------------------------------------------

# RS-1 Reflection Engine

The RS-1 Reflection Engine simulates a wide range of room shapes, and sizes, to drastically alter the pattern of reflections. While similar to that of the RealVerb Pro plug-in, the RS-1 does not offer the same breadth of features (such as room hybrids, room materials, morphing, and equalization). However, if you do not need the advanced capabilities that RealVerb Pro offers, you can use the RS-1 to achieve excellent room simulations, while also preserving DSP resources on the UAD device.

The Delay control sets the time between the direct signal and the first reflection. The Size parameter controls the spacing between the reflections. The Recir control affects the amount of reflections that are fed back to the input and controls how many repeats you hear.

![CS-1-reflection.png](CS-1%20Channel%20Strip%20Manual_assets/fdba259df282fdccf4b7207efb237410c49ba0ad.png)

*RS-1 Reflection Engine*

------------------------------------------------------------------------

# RS-1 Controls

## Sync Button

This button puts the plug-in into Tempo Sync mode. See the "Tempo Sync" chapter in the UAD System Manual for detailed information about tempo synchronization.

## Shape Pop-up Menu

Determines the shape of the reverberant space, and the resulting reflective patterns.

|             |                   |
|-------------|-------------------|
| Cube        | Square Plate      |
| Box         | Rectangular Plate |
| Corr        | Triangular Plate  |
| Cylinder    | Circular Plate    |
| Dome        | Echo              |
| Horseshoe   | Ping Pong         |
| Fan         | Echo 2            |
| Reverse Fan | Fractal           |
| A-Frame     | Gate 1            |
| Spring      | Gate 2            |
| Dual Spring | Reverse Gate      |

*Available RS-1 Shapes*

## Delay Knob

Sets the delay time between the original signal and the onset of the reflections.

## Size Knob

Sets the size of the reverberant space (from 1-99 meters) and defines the spacing of the reflections.

## Delay/Size Settings Interaction

You may notice that when Delay is set to its maximum value and the Size control is moved to its maximum value, the Delay value is decreased, and vice versa. This occurs because the maximum delay time available to the plug-in has been reached — the available delay time is limited and is divided among the Delay and Size values. Therefore, if the value of the Delay or Size setting is increased towards maximum when the other control is already high, its complementary setting may be reduced.

## Recirculation (RECIR) Knob

Sets the amount of processed signal fed back into its input. Higher values increase the number of reverberations/delays and intensity of the processed signal.

Recirculation allows both positive and negative values. The polarity refers to the phase of the delays as compared to the original signal. If Recirculation displays a positive value, all the delays will be in phase with the source. If it displays a negative value, then the phase of the delays flips back and forth between in phase and out of phase.

## Damping Knob

This low pass filter reduces the amount of high frequencies in the signal. Turn down this control to reduce the brightness. Higher values yield a brighter signal. Damping also mimics air absorption, or high frequency rolloff inherent in tape-based delay systems.

## Wet/Dry Mix Knob

This control determines the balance between the delayed and original signal. Values greater than 50% emphasize the wet signal, and values less than 50% emphasize the dry signal.

Wet/Dry Mix allows both positive and negative values. The polarity refers to the phase of the delays as compared to the original signal. If a positive value is displayed, then all the delays will be in phase with the source. With a negative value, the delayed signal is flipped 180 degrees out of phase with the source.

## L-Pan Knob

Sets the stereo position for the left channel, allowing you to adjust the width or balance of the stereo signal. For a mono signal, set both the L-Pan and R-Pan to the left.

## R-Pan Knob

Sets the stereo position for the right channel, allowing you to adjust the width or balance of the stereo signal. For a mono signal, set both the L-Pan and R-Pan to the left.

## Enable/Bypass Switch

Enables or disables the Reflection Engine. You can use this switch to compare the RS-1 settings to the original signal or bypass the entire RS-1 section to reduce UAD DSP load (load is not reduced if UAD-2 DSP LoadLock is enabled).

## Output Knob

Adjusts the relative output of the plug-in.

------------------------------------------------------------------------

# CS-1 Compatibility with Prior Sessions

As of UAD version 8.2, the Precision Mix Rack Collection plug-ins (Precision Channel Strip, Precision Delay Mod, Precision Delay Mod L, Precision Reflection Engine) replace the discontinued EX-1, DM-1, DM-1L, and RS-1 plug-ins, respectively.

When sessions containing the discontinued EX-1, DM-1, DM-1L, and RS-1 plug-ins are loaded in UAD v8.2 (and higher), the discontinued plug-ins in the session, along with their settings, are automatically migrated to their newer Precision Mix Rack Collection replacements.

The Precision Mix Rack Collection provides a modern interface, better controls, added features, and improved sonics versus the prior CS-1 sub-module plug-ins that they replace.

**Note:** Each individual plug-in title in the Precision Mix Rack Collection is doc- umented separately.

## Migrating Prior Sessions

If a session created with UAD v8.1 or lower contains the CS-1 plug-in, and that session is subsequently loaded with UAD v8.2 or higher, the original/identical CS-1 is loaded and the original settings and sonics are maintained.

If a session created with UAD v8.1 or lower contains the EX-1, DM-1, DM-1L, or RS-1 plug-ins, and that session is then loaded under UAD v8.2 or higher, those prior plug-in instances are automatically replaced by their newer counterparts, and the original settings in the session are maintained.

### UAD plug-in replacements when loading old sessions into UAD v8.2 and higher

- EX-1 instances are replaced with Precision Channel Strip
- DM-1 instances are replaced with Precision Delay Mod
- DM-1L instances are replaced with Precision Delay Mod L
- RS-1 instances are replaced with Precision Reflection Engine
- CS-1 instances are not replaced (original CS-1 is loaded)

**Note:** Precision Mix Rack Collection plug-in settings cannot be loaded into CS-1, EX-1, DM-1, DM-1L, or RS-1.

## Sonic Differences

In most cases (as detailed below), a migrated session with replaced EX-1/DM-1/DM-1L/RS-1 plug-ins will sound the same as, or subtly better than, the original session.

In some cases, the migrated session may be audibly different. The specific sonic differences when migrating from EX-1/DM-1/DM-1L/RS-1 plug-ins to their replacements are detailed below.

**Note:** In all migration cases, it is possible to revert to the exact same prior sonics (if desired) under UAD v8.2 and higher using the "Converting To Prior Sonics" procedure detailed later in this document.

### EX-1 to Precision Channel Strip

**Improved EQ filter design –** This change subtly improves the lowest and highest EQ frequencies in the EX-1/CS-1 and improves the Q (bandwidth) symmetry at the highest frequencies.

**Dynamics behavioral corrections at low ratio values –** A knee calculation error at small ratios in the original EX-1/CS-1 compressor is resolved with Precision Channel Strip, resulting in higher plug-in output levels if the Dynamics module was engaged when migrated.

The approximate level increases in Precision Channel Strip compared to EX-1 at given ratios are: 2 dB at 1.5:1, 1.3 dB at 2:1, 0.5 dB at 3:1, 0.25 dB at 4:1, and 0.1 dB at 6:1.

### RS-1 to Precision Reflection Engine

**Echo-based shapes are removed –** The three echo-based shapes are un- available within Precision Reflection Engine due to underlying technical constraints. When migrating from RS-1, Echo, Echo 2, and Ping Pong shapes are replaced with the Cube shape in the Precision Reflection Engine, with an au- dibly different sonic result.

### DM-1/DM-1L to Precision Delay Mod/Delay Mod L

There are no sonic differences between the discontinued DM-1/DM-1L and Precision Delay Mod/Delay Mod L plug-ins. The Precision Delay Mod/Delay Mod L has new features only.

## Converting To Exact Prior Sonics

If a session containing the EX-1 or RS-1 plug-ins is migrated to UAD v8.2 (and higher), and the migrated session sounds different due to the sonic differences detailed above (and those differences are undesirable), the session can be converted to the exact same prior sonics, even when using UAD v8.2 (and higher).

UAD v8.2 and higher includes the original CS-1 plug-in, and CS-1 can load preset files from EX-1/RS-1, resulting in identical sonics.

Therefore, converting to exact prior sonics is accomplished by loading EX-1/RS-1 preset file settings created in UAD v8.1 (or lower) into CS-1 in UAD v8.2 (and higher).

Detailed steps for this process are provided on the following page.

**Important:** Migration sessions from UAD v8.1 and lower to UAD v8.2 and higher is automatic. In most cases, migrated sessions will simply sound the same or subtly better. The process on the next page is only necessary if:a) the migrated session contains EX-1/RS-1, ANDb) the automatically-migrated session is sonically unsatisfactory or must sound identical to the pre-migrated session.

### To convert a migrated session to exact prior sonics:

1.  Install UAD v8.1 (or lower) software.
2.  Load the session(s) containing the EX-1, DM-1, DM-1L, or RS-1 plug-in(s).
3.  Open the EX-1/DM-1/DM-1L/RS-1 plug-in that contains the settings you want\
    to migrate.
4.  Save the plug-in's settings to disk as a preset file via the UAD Toolbar (click the folder icon at the lower left of the interface). Save the preset(s) to a convenient disk location; you'll load these files in step 9.
5.  Repeat steps 2 – 4 for each plug-in instance whose settings you want to migrate.
6.  Install UAD v8.2 (or higher). Restart the computer after installation.
7.  Load the session containing the EX-1/DM-1/DM-1L/RS-1 plug-ins you are migrating. The EX-1/DM-1/DM-1L/RS-1 plug-ins are automatically migrated to their Precision Mix Rack equivalents.
8.  Replace the EX-1/DM-1/DM-1L/RS-1 plug-in(s) with the CS-1 plug-in.
9.  Load the previously-saved EX-1/DM-1/DM-1L/RS-1 preset file into CS-1 via the UAD Toolbar. The original settings for the sub-module are imported into CS-1.
10. Disable the unused sub-modules on CS-1 to ensure they are not processing audio. For example, if loading an EX-1 preset into CS-1, disable the DM-1 and RS-1 modules in CS-1.
11. Repeat steps 7 – 10 for each plug-in whose settings you want to migrate.
12. Save the session. Sonically identical migration is complete.

