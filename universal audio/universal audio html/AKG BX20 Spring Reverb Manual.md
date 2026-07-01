---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/28320595155988-AKG-BX20-Spring-Reverb-Manual.html'
converted_at: 2026-05-31T13:44:50Z
tool: htmlq+pandoc
title: 'AKG BX20 Spring Reverb Manual'
word_count: 2558
---

# AKG BX20 Spring Reverb Manual


## The only AKG-licensed emulation of this one-of-a-kind spring reverb.

Introduced in the late 1960s, the AKG BX 20 reverb was a high-water mark for AKG's esteemed engineers. An ingenious assembly of mechanical and electronic componentry, the BX 20 offered the glorious depth and color of spring reverb without any of the limitations.

The AKG BX 20 Spring Reverb plug-in for UAD-2 hardware and Apollo interfaces is exclusively endorsed by AKG Acoustics, Austria and envelops your sources in gorgeously dark, dense ambience that only spring reverb can provide.

- Mix with the only licensed and endorsed AKG Acoustics BX 20 reverb plug-in

- Envelop instruments in dark, dense, clear ambience with original dual spring tank configuration

- Harness new "plug-in only" features like stereoized A/B Tank Select, Direct signal defeat, and BX 10 Tone controls

- Mix with artist presets from Patrick Carney (The Black Keys), Vance Powell (Jack White), and Jacquire King (Kings of Leon)

![](AKG%20BX20%20Spring%20Reverb%20Manual_assets/3160306134d82c0f69df8408b0bceab9ef605d0f.png)

# Operational Overview

The AKG BX 20 plug-in for UAD-2 is a faithful recreation of AKG's coveted spring reverb that captures the subtle nuances of the original BX 20's dual tank Torsion Transmission Line (TTL) reverb unit along with the R20 Decay Remote Control. Unique among its competitors, the AKG BX 20 creates dark, dense spring reverb ambience for buses or individual sources without the flutter or overly metallic sound of other spring reverb emulations.

Re-imagined for today's DAW workflows, the AKG BX 20 also includes features like stereoized A and B tanks for balanced stereo imaging, pre-delay, low-cut filter, dry/wet blend control, and independent left/right pan and volume controls.

The AKG BX 20's all-important TTL (Torsional Transmission Line) reverb system is fully represented, including all of the mechanical behaviors and idiosyncrasies that are part of the AKG BX 20's unique variable decay time. Within the interactive electromagnetic and mechanical nature of the design, the hardware exhibits a unique two-stage decay which is faithfully captured by the plug-in.

## Hybrid Technology

The AKG BX 20 Spring Reverb is not a general impulse response ("IR") convolution reverb nor a typical algorithmic reverb. Instead, AKG BX 20 utilizes breakthrough hybrid technologies, combining advanced delay network and convolution technologies, layering impulse responses into a hybrid algorithmic plug-in design. Impulse responses are combined and synthesized in real time to match the onset of the reverb, regardless of the continuously adjustable decay time. The delay network component provides an uncanny model of the AKG BX 20's two stage decay, with DSP mechanisms keeping the two systems in sync.

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

**Note: **Switching through presets is not instantaneous and sonic artifacts can occur while the presets are loading. See Load Time below for related information.

## Load Time

When the Tank Select and Decay controls are modified, the impulse response engine is updated by the plug-in. These IR updates and recalculations are not instantaneous; there is a time lag before the new control values are heard. Additionally, sonic artifacts and/or host CPU increases can occur while these recalculations are performed if audio is currently being processed by the plug-in.

**Tip: **The Power Lamp is a status indicator that flashes while the impulse response engine is updated.

## Automation Limitations

The impulse response engine load time can be an impediment if the Tank Select, and to a lesser degree, Decay controls are modified with automation during a mix. We recommend against automating these specific controls to avoid sonic artifacts and/or host CPU increases. If automation must be used on these controls, only snapshot automation should be used (instead of continuous automation), and optimally only when the signal being processed is not audible (for example, between musical phrases).

## AKG BX 20 Latency

The AKG BX 20 plug-in uses upsampling and other proprietary techniques to achieve sonic design goals. These techniques result in a larger latency than most other UAD plug-ins (between 974 and 4120 samples, depending on the sample rate). Precautions should be observed to prevent the extra latency from becoming an issue during live performance (such as when recording) or monitoring with UAD Console or LUNA. 

**Note: **See [this article](https://help.uaudio.com/hc/en-us/articles/15247166304148) for related information.

### Apollo Console

AKG BX 20 latency can exceed the maximum value of Apollo Console's Input Delay Compensation engine. When the plug-in is used on input inserts (but not auxiliary buses) within UAD Console, the "Input Delay Compensation Exceeded" dialog may appear. In this case, Console's Input Delay Compensation feature can be disabled (in the Console Settings window), or simply ignore the dialog.

### Live Performance

Extra latency can be problematic during live performance if the plug-in is inserted into the signal chain of the source signal and the performer is monitoring the source signal chain. For this reason, the AKG BX 20 is recommended for use in auxiliary send/return configurations (as is typical with time-based effects) during live performance.

 

# AKG BX 20 Controls

## Input Select

Input Select can be changed when the plug-in is used in a stereo channel configuration. When used in a mono channel configuration, this control is locked in the mono position.

**Note: **When the plug-in is used in a mono-in/stereo-out configuration, there is no sonic difference when Input Select is switched between mono and stereo.

### Mono

When set to Mono, a stereo input signal is summed to mono before reverb processing. If the plug-in is inserted on a stereo signal, the reverb output is stereoized even if the stereo inputs are summed to mono.

### Stereo

When set to Stereo, the stereo input signal is passed into the reverb processor.

**Tip: **Clicking the mono or stereo label text selects that configuration.

## Tank Select

The AKG BX 20 has two mono reverb tanks (the spring containers) and each has a unique sonic signature. This control determines which reverb tank is used for reverb processing.

The original hardware design incorporates the two spring tanks "a" and "b" which are associated with channels 1 and 2, respectively. As with the hardware, the plug-in allows for stereo input use with either a summed mono or discrete stereo input (single channel/mono use is also common). The AKG BX 20 plug-in faithfully captures this original stereo use case when "a/b" is selected with this control.

**Tip: **Clicking any tank label text selects that tank.

With the AKG BX 20, the two reverb tanks can behave and sound noticeably different from each other when used together as a stereo effect, which may not be suitable for all use cases. Therefore the AKG BX 20 plug-in goes beyond the hardware with useful stereoized versions of the original mono tanks when either the "a" or "b" tank is selected. These options provide two perfectly balanced stereo reverbs, each with unique sonic responses and decay behaviors.

**Note:** When Tank Select is adjusted, a time lag occurs before the new tank configuration is heard. The Power Lamp flashes while the impulse response engine is updated.

### Tank A

The stereoized Tank A features a dark and rich sound derived from a more intense reverberation of low frequencies. This darker reverb subdues reverberations of higher frequencies, allowing for a dissipation effect that warms the source it is applied to.

### Tank B

The stereoized Tank B provides a bright and present response that sits forward in the mix allowing both the content and the reverberation to be more prominently heard. It alleviates the low to mid frequency reverberation build up associated with muddiness.

### Tank A/B

When set to "a/b" the left signal is sent to Tank A and the right signal is sent to Tank B. Note that the A and B tanks are notstereoized in this mode. Instead, the original mono tank outputs are sent to the left and right channels respectively, resulting in a stereo reverb output.

**Note: **When used on mono signals, tank configurations A and B work in mono just like the hardware, while A/B sums both tanks.

## Direct

When Direct is engaged (when switch is depressed), the direct signal component within the reverberated signal is audible. When disengaged, the direct signal component is removed from the reverberated signal.

The naturally dominant direct signal component in spring-based systems can sometimes overwhelm the reverb's late field response with certain sources. The Direct control allows an alteration of the original reverberant sound by muting the spring tank's direct signal component, minimizing possible conflict with the original source audio.

Removing the direct signal component from the reverb is different than simply not mixing in the dry signal (as could be achieved with the Dry/Wet mix control). This is a UAD-only feature that is made possible by advanced modeling techniques.

Disabling the direct path signal enables greater BX 20 flexibility in ambience-shaping possibilities, especially with transient-rich sources such as drums and percussion.

## Tone Controls

The tone controls affect both reverb tanks (a, b) and both channels (1, 2).

### Bass

Bass controls the amount of low frequency reverberation processing. This continuous knob controls a Baxendall type filter centered at 150 Hz and spans a range of ±8 dB with a default setting of 0.

**Tip: **Clicking the "0" or "bass" label text returns the control to the default value of 0.

### Low Cut

The Low Cut button engages a high pass filter that reduces processing of frequencies below 80 Hz. This filter is useful for removing the buildup of low frequency reverberations that cause bass-heavy signals to sound muddy. The slope of the Low Cut filter is 12 dB per octave.

### Treble

Treble controls the amount of high frequency reverberation processing. This continuous knob controls a Baxendall type filter centered at 5 kHz and spans a range of ±4 dB with a default setting of 0.

**Tip: **Clicking the "0" or "treble" label text returns the control to the default value.

## Dry/Wet

The Dry/Wet controls determines the balance between the original and the processed signal. The range is from 0% (dry, unprocessed) to 100% (wet, processed signal only). The default value is 15%.

**Note: **If Wet Solo is active, adjusting Dry/Wet will have no effect.

Dry/Wet control behavior is based on a logarithmic scale to provide increased resolution when selecting lower values. When the knob is set to the 12 o'clock position, the blend value is 15%.

**Important: **When the Direct switch is engaged, Dry/Wet should be set to 100% (or engage Wet Solo) because the direct signal component is already mixed with the reverb signal. Otherwise, doubled and/or out-of-phase signals may be heard.

## Wet Solo

Wet Solo puts the plug-in into 100% Wet mode. When enabled, the dry unprocessed signal is muted and the dry/wet mix control has no effect.

Wet Solo is typically used when the plug-in is inserted on an auxiliary effect return bus that is configured for use with channel aux sends, for 100% wet send/return processing. When the plug-in is inserted on a track, Wet Solo is typically disabled so the dry/wet mix control can be heard. 

Wet Solo is a global (per plug-in instance) control. The switch state is saved within host DAW project/session files, but it doesn't change when a preset is loaded; the current state always overrides the preset state. 

This feature allows presets to be properly auditioned without changing the Wet Solo setting. If Wet Solo is disabled when a preset is loaded, the dry/wet mix value in the preset is loaded (and heard) and Wet Solo remains disabled. If Wet Solo is enabled when a preset is loaded, the dry/wet mix value in the preset is loaded (but not heard) and Wet Solo remains active. 

The global feature means preset settings are always loaded appropriately, whether the plug-in is loaded in a track insert (where Wet Solo is typically disabled and the mix control used instead), or in an aux return (where wet solo is typically enabled, defeating the mix control for 100% wet send/return processing).

Note (Pro Tools only): The Wet Solo setting is saved and loaded in presets when using the Pro Tools preset manager. To audition presets without changing Wet Solo state, the Load Preset function within the UAD Toolbar must be used.

## Predelay

The time between the dry signal and the onset of reverb is controlled with this knob. The range is 0.0 to 250 milliseconds with a default setting of 0.

This control uses a logarithmic scale to provide increased resolution when selecting lower values. When the knob is in the 12 o'clock position, the value is 50 milliseconds.

Higher Predelay values can be useful for tracks where the clarity of the source should stand out before the reverb starts.

## Decay

Channel 1 and 2 Decay controls the duration of the unique two-stage decay/frequency control which is faithfully captured by the plug-in. The available range is from 2 seconds to 4.5 seconds. The default value is 3 seconds. Rotate the control clockwise to increase the Decay time.

**Note: **When Decay is adjusted, the impulse response engine is updated by the plug-in and there is a time lag before the new Decay value is heard. The Power Lamp flashes while the impulse response engine is updated.

## Link

When activated, Link enables the three controls that are identical for the Channels 1 and 2 (Decay, Volume, and Pan) to be ganged for ease of operation when both channels require the same values, or unlinked when independent left/right control is desired. When linked, modifying any left or right channel control causes its adjacent stereo counterpart control to snap to the same position.

**Important: **When Link is inactive then Link is enabled, the left channel control values are copied to the right channel. Control offsets between channels are lost in this case.

## Volume

Channel 1 and 2 Volume controls the relative volume of the AKG BX 20's spring reverb effect. It does not affect the dry signal.

Rotate the control clockwise for more reverb. Reducing the control to its minimum value will disable the reverb.

**Tip: **Clicking the "0" or "vol" label text returns the value to 0 dB.

## Pan

Channel 1 and 2 Pan controls determine the placement of the reverb signals in the stereo panorama when the plug-in is used in mono-in/stereo-out and stereo-in/stereo-out configurations. When the AKG BX 20 is used in a mono-in/mono-out configuration, the Pan controls are disabled.

**Tip: **Clicking the "0" or "pan" label text sets the value to center.

## Power

The power button determines whether the plug-in is active. When engaged, the Power Lamp is illuminated. When set to off, the Power Lamp is de-illuminated indicating that all plug-in processing is disabled and UAD DSP usage is reduced (load is not reduced if UAD-2 DSP LoadLock is enabled).

**Tip: **The Power Lamp also functions as a Power button.

## Power Lamp

When the Power Lamp is illuminated, the reverberator is active. The Power Lamp flashes whenever the Tank Select or Decay controls are adjusted, indicating that a new impulse response is being loaded. After adjusting these controls, the Power Lamp remains solid again, indicating the new settings are active.

![](AKG%20BX20%20Spring%20Reverb%20Manual_assets/311d517fed26ba1947ac1b48e96acf2ae0e7f669.png)

![](AKG%20BX20%20Spring%20Reverb%20Manual_assets/9cb7f894eb8f3328c9c7868945584db2e6abc750.png)

![](AKG%20BX20%20Spring%20Reverb%20Manual_assets/192cbb579cd99df8218f5d99bf6237779ebe2620.png)

 

All visual and aural references to the AKG<sup>®</sup> BX 20 Spring Reverb and all use of AKG's trademarks are being made with written permission from AKG by HARMAN.

