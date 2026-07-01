---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/34530260482324-1176-Classic-FET-Compressor-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: '1176 Classic FET Compressor Manual'
word_count: 1343
---

# 1176 Classic FET Compressor Manual


## Explore the iconic sound of the most famous audio compressor in the world.

Start your journey with the same iconic compression used on nearly every hit recording of our time. Then dive into all the incredible analog sounds in our UAD plug-in library — from vintage Teletronix LA-2As and Pultec EQs to hundreds more.

## Ratio Buttons for Iconic Color

The four Ratio buttons determine the degree of compression — lower ratios for compression, higher ratios for limiting. The famous "All Button" sound is included, by Shift-clicking any Ratio button.

------------------------------------------------------------------------

# 1176 Classic FET Compressor Overview

This model is based on the classic early 70's / Brad Plunkett "LN" (Low Noise) era of the 1176 circuit lineage, with variations including a more linear compression response, transistor gain amplification, and the characteristic musical program dependency that makes the 1176 one of the most enduring studio compressors of all-time.

![1176-fet-compressor.png](1176%20Classic%20FET%20Compressor%20Manual_assets/20fd5f80dbfe30846421749c4610bdf715a09cf6.png)

*1176 Classic FET Compressor*

------------------------------------------------------------------------

# Operational Overview

## Applications

Generally speaking, the primary use for the 1176 plug-in is as individual inserts for sources that require limiting or compression, such as an individual snare, vocal, or guitar track, or for multi-instrument sources such as a stereo drum bus. The 1176 is highly versatile, yielding results ranging from transparent, gentle limiting, to crushed and distorted. 

## Parameters

Using an 1176 is a study in simplicity. Input simultaneously sets compression threshold and the level of the signal entering the 1176; Output sets the final signal level. Attack sets the time it takes the 1176 to respond to incoming signal, while Release sets the time it takes the 1176 to return to its initial level. The VU meter displays the amount of gain reduction (GR) or output level (+4/+8).

The four Ratio buttons determine the degree of compression; lower ratios for compression, higher ratios for limiting. Including the famous "All Button" sound. 

## Grit

A simple 1176 trick is turning the attack and release up all the way to their fastest settings. This has the audible effect of adding compression distortion to the audio source, and is especially pronounced in all-buttons mode. What happens here is the attack and release are happening so fast that minute level fluctuations sound like distortion. It can add a very useful, gritty compression effect.

This effect is useful on bass, where you might need compression and distortion at the same time, and the 1176 can provide both in a unique way. This trick also sounds great on screaming lead vocals.

## Presets

The 1176 Classic FET Compressor includes useful presets designed by Universal Audio for a variety of common applications. Presets are accessed using the preset browser.

------------------------------------------------------------------------

# 1176 Controls

## Input

Input adjusts the amount of gain reduction as well as the relative threshold. Rotate the knob clockwise to increase the compression amount.

Like the original hardware, the label values are somewhat arbitrary; the knobs are not calibrated to any particular dB values. Even when the Input knob is set to " ∞ " signals can still pass into the processor and be compressed.

**Note:** Increasing Input will increase distortion.

## Output

Output determines the final output level of signal leaving the 1176. Once the desired amount of limiting or compression is achieved with the use of the Input control, the Output control can be used to make up any gain lost due to gain reduction.

To monitor the Output level, set the VU Meter to +8 or +4. The Output control does not affect the amount of compression.

**Note:** Increasing Output will increase distortion.

## Attack

Attack sets the amount of time it takes the 1176 to respond to an incoming signal and begin gain reduction. The 1176 attack time is adjustable from 20 microseconds to 800 microseconds (both extremely fast).

The attack time is fastest when the Attack knob is in its fully clockwise position, and is slowest when it is in its fully counter-clockwise position. When a fast attack time is selected, gain reduction kicks in almost immediately and catches transient signals of very brief duration, reducing their level and thus "softening" the sound.

Slower attack times allow transients (or partial transients) to pass before limiting or compression begins on the rest of the signal. Note that the actual attack time varies slightly based on the selected ratio and the particular plug-in model in use; lower ratios will maintain the fastest attack times.

## Release

Release sets the amount of time it takes the 1176 to return to its initial (pre-gain reduction) level. The 1176 release time is adjustable from 50 milliseconds to 1100 milliseconds (1.1 seconds).

The release time is fastest when the Release knob is in its fully clockwise position, and is slowest when it is in its fully counter-clockwise position. If the release time is fast, "pumping" and "breathing" effects can occur, due to the rapid rise of background noise as the gain is restored. If the release time is too slow, however, a loud section of the program may cause gain reduction that persists through a soft section, making the soft section difficult to hear. Adjust Release gradually to achieve the desired effect; small adjustments can make a significant difference. 

### About Program-Dependent Release

Program-dependent release is a feature of many classic UA compressor designs. The motivation for having program-dependent release is as follows: after a transient, it is desirable to have a fast release to avoid prolonged dropouts. However, while in a continued state of heavy compression, it is better to have a longer release time to reduce the pumping and harmonic distortion caused by repetitive attack-release cycles.

The 1176 compressor employs a release mechanism that is heavily program-dependent. There are three features to a program-dependent release: A fast release-time, a slow release-time, and a transition-time.

The fast release time is the effective release time after transients; the slow release time is the release time after sustained high-RMS signals. The transition time expresses how long the signal must be "in compression" before the slow release time comes into effect.

## Ratio

The four Ratio pushbutton switches (to the left of the VU Meter) determine the compression ratio of the plug-in. Ratios of 20:1, 12:1, 8:1, and 4:1 are available.

The 20:1 ratio is typically used when peak-limiting is desired, while the lower ratios are typically used for general dynamic range compression.

## All Button Mode

Engineers typically use "All Button" mode on drums or on ambience or room mics. It can also be used to make a bass or guitar sound "dirty" or for putting vocals "in your face." In All-Button mode (also known as "British Mode"), distortion increases radically due to a lag time on the attack of initial transients.

In All Button mode the ratio goes to somewhere between 12:1 and 20:1, and the bias points change throughout the circuit, thus changing the attack and release times as well. The unique and constantly shifting compression curve that results yields a trademark overdriven tone that can only be found in this family of limiter/compressors.

To toggle All Button mode, Shift-click any ratio button.

## VU Meter

This is a standard VU meter that displays either the amount of gain reduction, or output level, depending upon the setting of the Meter Function switch.

### Meter Function

These four pushbutton switches (to the right of the VU Meter) determine the mode of the VU Meter, and whether the plug-in is enabled. When set to GR, the VU Meter indicates the Gain Reduction level in dB. When set to +8 or +4, the VU Meter indicates the output level in dB; when set to +4, a meter reading of 0 corresponds to an output level of +4 dB.

When the Meter Function is set to GR mode and All Ratio buttons are engaged, the Meter will appear to behave strangely. This is normal behavior in the 1176 hardware, and is faithfully recreated in the plug-in.

When the OFF switch is engaged, the plug-in is disabled and processor usage is reduced.

![1176ln_classic_limiter_carousel.jpg](1176%20Classic%20FET%20Compressor%20Manual_assets/3bcd0948adf30ce7d8cf287f49f34c564641c99f.jpg)

*Original UA 1176 hardware*

