---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/18741515014676-Empirical-Labs-EL8-Distressor-Manual.html'
converted_at: 2026-05-31T13:44:46Z
tool: htmlq+pandoc
title: 'Empirical Labs EL8 Distressor Manual'
word_count: 4710
---

# Empirical Labs EL8 Distressor Manual


## In this article

- [Distressor Controls](#h_01HDM09QSZ3S1762W6BHC7MMSE)
- [Operation Notes From Empirical Labs](#h_01HDM09QT00P8WHZ89XZCR4FR9)

## Get the colorful sound of the world’s most popular compressor.

The Empirical Labs EL8 Distressor is revered in studios the world over as the modern, “must-have” compressor. Versatile with tons of color, the Distressor picks up where the legendary UA 1176 and Teletronix LA-2A compressors leave off — giving you a modern tool that’s equal parts utilitarian and creative, as heard on thousands of hit records.

- Track and mix with the only authentic emulation of the EL8 Distressor — the world's most sought-after modern compressor

- Radically shape guitars, drums, and vocals with nearly infinite gain reduction variations

- Harness plug-in-only features like Dry/Wet parallel processing and Headroom for user‑customizable operating level

- Creatively color instruments and vocals with famous “Dist 2” and “Dist 3” modes

- Embellish, pump up, or destroy bass, synth, and room mics with custom detector filtering

- Mix with presets from Joe Chiccarelli (The Strokes), Vance Powell (Jack White), Jacquire King (Kings of Leon), Jimmy Douglass (The Rolling Stones), and more

## Shape with the Only End‑to‑End Distressor Emulation

The EL8 Distressor Compressor plug-in gives you all the features and tone of the original hardware. Simply compare other Distressor emulations for yourself, and contrast the original hardware’s ultra-fast attack time to quickly hear where most plug-ins fail, and the authentic UAD Distressor succeeds.

## Find the Perfect Compression Ratio

The crux of the Distressor are its staggering variations in compression — 1:1, 2:1, 3:1, 4:1, 6:1, 10:1, 20:1 and Nuke — each offering unique sounds. Use the 1:1 ratio to gently warm up synths or strings without compression, while adding musical harmonics. Conversely, the Nuke setting gives explosive excitement to room mics or your entire mix.

## Add Color with Distortion Modes

The Distressor's iconic Dist 2 and Dist 3 modes give you a wide palette of compression textures, letting you shape sources with even or combined even/odd-order harmonic distortion, from delicate thickening to burnished tape to fully saturated.

## Focus Dynamics with Powerful Sidechain Controls

The Distressor’s sidechain control gets rid of unwanted low-frequency pumping — perfect for drum bus processing — while Band Emphasis tames strident vocals and harsh “power region” instrument peaks. You can also harness "plug-in only" features like Dry/Wet Mix for easy parallel compression on a mix bus or instrument group.

 

------------------------------------------------------------------------

 

# Distressor Controls

![distressor-interface.png](Empirical%20Labs%20EL8%20Distressor%20Manual_assets/696fd7e0fe3a9b58c086329194030baf01d67224.png)

*Empirical Labs EL8 Distressor*

A simplified version of the signal flow within the plug-in is shown in the diagram below. Understanding this signal flow may help you obtain a more predictable result.

![distressor-flow.png](Empirical%20Labs%20EL8%20Distressor%20Manual_assets/be30377f960802aab0cf3db75ab95063850604a1.png)

## BYPASS

BYPASS disables the Distressor circuit but keeps the plug-in loaded on UAD DSP for a glitch-free bypass. To toggle the BYPASS state, click the BYPASS button, label, or LED. BYPASS is active when its LED is lit.

The gain reduction meter remains active in bypass mode. In the original hardware unit, this switch controls a relay that hard-wires the inputs directly to the outputs. 

**Tip: **To conserve processing resources, use the POWER switch.

## RATIO

This switch cycles through the available compression ratios. Each ratio provides a distinct compression curve and threshold offset. The table below lists the available values and a description of the setting.

**Caution:** With high amounts of gain reduction, switching RATIO to 1:1 can cause extreme increases in output level (as there is no gain reduction with 1:1 RATIO). To avoid sudden output increases when adjusting RATIO, click directly on a RATIO text label or LED to change the value instead of cycling through available values with the RATIO button.

**Tip: **To cycle through available ratios in reverse, hold SHIFT while clicking RATIO.

### Ratio descriptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td class="wysiwyg-text-align-center" style="width: 25%"><p><strong>Ratio</strong></p></td>
<td class="wysiwyg-text-align-center" style="width: 75%"><p><strong>Description</strong></p></td>
</tr>
<tr>
<td style="width: 25%"><p>1:1</p></td>
<td style="width: 75%"><p>Saturation only. No compression. Warms the signal.</p></td>
</tr>
<tr>
<td data-colwidth="90" style="width: 25%"><p>2:1<br />
3:1</p></td>
<td style="width: 75%"><p>Mild compression with gentle "parabolic" knee shape. 2:1 knee can be as long as 30 dB, depending on attack and release settings. </p></td>
</tr>
<tr>
<td style="width: 25%"><p>4:1<br />
6:1</p></td>
<td style="width: 75%"><p>Mid-level compression with steeper knee shape. A good starting point for many signals.</p></td>
</tr>
<tr>
<td style="width: 25%"><p>10:1</p></td>
<td style="width: 75%"><p>"Opto" compression curve, with special detection circuitry that emulates electro-luminescent optical gain reduction.</p></td>
</tr>
<tr>
<td style="width: 25%"><p>20:1<br />
NUKE</p></td>
<td style="width: 75%"><p>Hard limiting curves with special detector circuitry. Great for controlling highly dynamic signals and for "blowing up" room sounds.</p></td>
</tr>
</tbody>
</table>

## DETECTOR

![distressor-detector.png](Empirical%20Labs%20EL8%20Distressor%20Manual_assets/f11816bf7a060479a5aa80e2dd6a37f1d79534d5.png)

This switch cycles through eight modes of sidechain signal processing. Each mode has a distinct effect on dynamics detection and compression behavior.

Three separate sidechain functions are available: High Pass, Band Emphasis, and Stereo Link. The function is active when its LED is lit. The functions can be combined to access all detector modes.

To select a detector mode, click the LEDs or labels directly, or SHIFT click to select multiple functions. To cycle through detector modes in reverse, hold SHIFT while clicking DETECTOR. 

### Detector modes

<table style="height: 264px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 22px;">
<td class="wysiwyg-text-align-center" style="width: 35%"><p><strong>Detector Switch State</strong></p></td>
<td class="wysiwyg-text-align-center" style="width: 65%"><p><strong>Detector Mode Description</strong></p></td>
</tr>
<tr style="height: 22px;">
<td style="width: 35%"><p>Normal (Detector LEDs off)</p></td>
<td style="width: 65%"><p>Standard detector behavior.</p></td>
</tr>
<tr style="height: 44px;">
<td style="width: 35%"><p>High Pass<br />
(Green LED)</p></td>
<td style="width: 65%"><p>A high pass filter (100 Hz cutoff, 6 dB/oct. slope) is applied to the sidechain, reducing low-frequency modulation.</p></td>
</tr>
<tr style="height: 44px;">
<td style="width: 35%"><p>Band Emphasis<br />
(Yellow LED)</p></td>
<td style="width: 65%"><p>Sidechain signal is boosted around 6 kHz, influencing the compressor to tame harsh upper-mid frequencies.</p></td>
</tr>
<tr style="height: 22px;">
<td style="width: 35%"><p>High Pass + Band Emphasis</p></td>
<td style="width: 65%"><p>High Pass and Band Emphasis modes are enabled.</p></td>
</tr>
<tr style="height: 44px;">
<td style="width: 35%"><p>Link<br />
(Red LED)</p></td>
<td style="width: 65%"><p>Stereo linking is enabled, for more coherent gain reduction behavior on heavily divergent stereo sources.</p></td>
</tr>
<tr style="height: 22px;">
<td style="width: 35%"><p>High Pass + Link</p></td>
<td style="width: 65%"><p>High Pass and Stereo Link modes are enabled.</p></td>
</tr>
<tr style="height: 22px;">
<td style="width: 35%"><p>Band Emphasis + Link</p></td>
<td style="width: 65%"><p>Band Emphasis and Stereo Link modes are enabled.</p></td>
</tr>
<tr style="height: 22px;">
<td style="width: 35%"><p>HP + Band Emphasis + Link</p></td>
<td style="width: 65%"><p>All three detector modes are enabled.</p></td>
</tr>
</tbody>
</table>

### Unique mono Detector Link behavior

#### Hardware Link overview

The Distressor hardware unit is monophonic. However, it features sidechain I/O jacks for linking two units together in a stereo configuration. With two properly connected units, the Link switch enables stereo operation.

The Link switch influences the sound even when there is only a single unit. When Link is on but nothing is connected to the hardware's sidechain I/O, this "dead patch" impacts threshold behavior and increases harmonic distortion.

#### UAD mono out behavior

UAD Empirical Labs Distressor models the unique mono link behaviors of the original hardware. When the plug-in is used in a mono-out configuration and Link is on, the "dead patch" response of the hardware is fully emulated.

**Important:** Because of the hardware's unique monophonic Link behaviors, UAD Distressor presets saved in mono-out configurations with Link enabled may sound different when subsequently opened in stereo-out configurations.

## AUDIO

AUDIO cycles through six modes of audio processing. Each mode has a distinct effect on frequency balance and saturation.

Three separate audio functions are available: High Pass, Distortion 2, and Distortion 3. The function is active when its LED is lit. The functions can be combined to access all audio modes.

To change the audio mode, click the LEDs or labels directly, or SHIFT click to select multiple functions.

**Tip: **To cycle through audio processing modes in reverse, hold SHIFT while clicking AUDIO. 

### Audio mode descriptions

|  |  |
|----|----|
| Audio Switch State | Audio Mode Description |
| Normal (Audio LEDs off) | No special audio processing. |
| High Pass | Applies an 18 dB per octave Bessel type high pass filter with 80 Hz cutoff to help reduce rumble and clean up signals. |
| Dist 2 | Engages a distortion circuit that emphasizes the 2nd harmonic. Adds warm, consonant saturation, akin to an overdriven tube circuit. |
| High Pass + Dist 2 | High Pass and Distortion 2 modes are enabled. |
| Distortion 3 | Engages a distortion circuit that emphasizes the 3rd harmonic. Emulates friendly tape-like behavior when pushed. |
| High Pass + Dist 3 | High Pass and Distortion 3 modes are enabled. |

## DISTORTION METERS

These LEDs provide a visual approximation of total harmonic distortion and can be used to gauge audible distortion. The distortion is measured at the input amplifier, and also from the distortion VCAs when Distortion 2 or Distortion 3 audio modes are active. 

### REDLINE LED

This LED glows when total harmonic distortion reaches approximately 3%. When lit, REDLINE also indicates output clipping.

### 1% LED

This LED glows when total harmonic distortion reaches approximately 1%.

## POWER

POWER disables the plug-in and unloads it from DSP, conserving UAD resources.

## GAIN REDUCTION METER

The Gain Reduction Meter displays the amount of gain attenuation occurring in the compression circuit. Greater negative dB values (as the LEDs move towards the left) indicate more compression is occurring.

**Note:** The gain reduction meter remains active when BYPASS is engaged. The meter is unlit when POWER is off. 

## INPUT

INPUT simultaneously adjusts input gain and modifies compressor threshold. The amount of threshold modification is relative to the response of each RATIO setting. 

The nonlinear input amplifier response of the hardware is fully emulated. 

## ATTACK

ATTACK sets the amount of time that must elapse once the input signal reaches compressor threshold before compression is applied. Setting the knob to 0 produces the fastest attack time. The faster the attack time, the more rapidly compression is applied to signals above the threshold. 

The available range is from 50 microseconds to 30 milliseconds. However, with ATTACK at 0, Distressor can achieve even faster times when RATIO is set to 2:1, 3:1, and 4:1.

## RELEASE

RELEASE sets the time it takes for processing to cease once the input signal drops below the threshold level. Setting the knob to 0 produces the fastest release time. The available range is from 0.05 seconds to 3.5 seconds.

**Note:** In 10:1 "Opto" mode, release can extend up to 20 seconds due to program dependent behaviors.

## OUTPUT

OUTPUT adjusts the signal level at the output of the plug-in. The nonlinear output amplifier response of the hardware is fully emulated. 

## HEADROOM (HR)

![distressor-headroom.png](Empirical%20Labs%20EL8%20Distressor%20Manual_assets/5b6c422a4acc2094df974b6f7c1915da58561628.png)

The Headroom control is a UAD-only feature that is not available in the original hardware. Headroom enables adjustment of the internal operating reference level for the plug-in so that the plug-in is not "pushed" into processing as much. Headroom enables best practice operating level matching, or it can be used creatively to expand the sonic range of the processor. 

By fine-tuning Headroom, the nonlinear I/O distortion and compression response characteristics can be tailored independently of signal input levels. Increasing Headroom (by rotating the control counter-clockwise) allows signals at the input to be pushed higher before they are processed. 

Headroom can be set (in dB) to 4, 8, 12, 16, 20, 24, or 28. The default value is 16 dB (when the set screw "dot" is in the straight up 12 o'clock position). Note that Headroom is increased as the dB value decreases.

**Tip:** Click the "HR" text label to return the control to the default value.

At higher dB values (clockwise rotation), signals will push the plug-in into processing more easily. Set the control to a lower value (counter-clockwise rotation) when less processing and less color is desired.

**Note: **To avoid the temporary gain increases that can result when adjusting Headroom, automating this control is not recommended.

## MIX

A blended output balance between the signal processed by the plug-in and the original dry source signal can be adjusted with the MIX control. Mix facilitates parallel compression techniques without having to create additional routings in the DAW.

**Note:** The MIX control does not exist in the original hardware.

When MIX is set to Dry, only the unprocessed source signal is output. When set to Comp (the default value), only the processed (wet) signal is output. When the knob's tick mark is pointing straight up (50%), an equal blend of both the dry and wet signals is output. The balance is continuously variable, and phase accurate, throughout the control range.

**Tip: **Click the Dry text label to set the control to the minimum position. Click the Comp text label to set the control to the maximum position.

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

<div>

|                |                 |
|----------------|-----------------|
| Chris Coady    | Jimmy Douglass  |
| Chris Zane     | Joe Chiccarelli |
| Hector Delgado | Mike Larson     |
| Jacquire King  | Vance Powell    |

</div>

*Artists that have provided presets for Empirical Labs EL8 Distressor*

------------------------------------------------------------------------

# Operation Notes From Empirical Labs

*Courtesy of Dave Derr, designer of the EL8 Distressor*

## Using the Distressor for the first time

### Where to start - 5 5 5 5

Start with 6:1 ratio and set all four knobs to 5, the midway position. This is a great starting place for anything. Push the ratio button until the LED's cycle to the 6:1 ratio (Yellow LED). Adjust input to drive into more compression. The harder you drive, the more knee you'll hit, and the greater the ratio will be. Only 1 LED should be lit - the 6:1 LED (not counting any bargraph LED's). If you need more obvious compression, push ratio button to progress to higher ratios. If you would like lower ratios, the very long knees of 2:1, 3:1, 4:1 are silky smooth. The 2:1 ratio has a +15 dB knee, where the ratio gradually increases! Unit will scroll around "Nuke" back to these lower ratios, but if you must cycle through 1:1 while unit is in use, do it quickly since compression will be turned "off" and the signal will swell to its peak input levels, possibly becoming dangerously loud. Waiting for a pause in the input before changing ratio is a safe thing to do. For a quick +4 tape levels, try setting output knob to 8.

### Distortion settings

If all the LED's are off in the "Audio" area, your Distressor is operating in its cleanest mode. Distortion settings should be used when subtle analog distortion is desired. Dist 2 mode produces "Class A" type warmth, producing mostly 2nd harmonic when compressing (tube distortion is known for its 2nd harmonic) and Dist 3 adds 3rd along with 2nd harmonic. Dist 3 can look and sound very similar to tape distortion - it gradually flattens out the top and bottom of the waveform. If you want a digital signal to sound like an analog tape signal, try 2:1 mode with Dist 3 engaged, and compress 1 - 3 dB (as displayed on bargraph). Tape goes in and out of saturation quickly, so fast attacks and decays are appropriate. If you want to make it sound like over-saturated tape, you could try one of the higher ratios and drive the input to produce 1 - 5 dB of compression. With the quick release, 2nd harmonic will still be strong in Dist 3 mode. More than 3 to 5 dB of reduction will sound less like tape, more like compression.

### Advanced Detector function

The new user may want to stick with a basic setup until he feels comfortable, but with the push of a button he can enable some advanced sidechain functions. While tracking vocals for instance, sometimes "p's" and "b's" can hit the mic with an air blast that shows up as a high amplitude, low frequency signal, causing the compressor to "kick in". The result may be a brief, unnatural drop in the apparent vocal level. By pushing the detector button once, you engage a high-pass (abbreviated with HP) filter in the detector (the part of the circuit that figures out how much to turn down the signal). This high-pass, or low cut, will not allow low, low frequencies to trigger compression, and in this case, prevent the unnatural drop in vocal level from a "p" or "b" blasting the mic with wind. It may also help to HP (high-pass) the audio in this case.

Another detector sidechain filter can be engaged with a second push of the button. This is the "band emphasis function" that inserts an Eq into the detector circuitry that makes the circuit much more sensitive to harsh, mid band frequencies. This is useful on vocals (for those singers with a nasty edge to their voice when they go up high), guitars, synths, and many other solo instruments that may become harsh and too loud in the mix. See "Detector Modes" on page 6 for more info.

## Example settings

Generally, it is difficult to make the unit sound unnatural due to its vintage topology. The ratio and release times are the most critical settings. Again, around 5 on the release knob is a good starting spot. The attack is variable from 50uS to 30mS. The release is variable from 50mS to 3 seconds. For percussive material, if you need to add attack, add attack. That is, slow the attack by turning the knob clockwise towards 10. Conversely, if you need to get rid of some pick noise, or over transient sounds, the fast attack and release is the way to go. With these tools, an engineer can mold the envelope of sounds in a very controlled manner, adding or softening attack, sustaining, smoothing and evening until the sounds fit into the mix as desired.

**Vocals –** Turn off all distort modes if you're going to tape, however the High-pass (HP) in both the detector and audio paths may be useful. Set ratio to 6:1 or less, attack 5, release 4. Adjust input to produce anywhere from 3 to 17 dB of compression. Sometimes the band emphasis setting is effective for those dynamic, "piercing" vocal passages. On mixdowns, Dist 2 can add a warm edge to vocals. The "Opto" mode in 10:1 is guaranteed to give you a classic compression curve. Try 10:1, with attack on 10, release on 0. Separate detector circuitry will be enabled.

A well known producer gave us another more aggressive vocal compressor setting: Ratio 6:1, Attack 2.5-3,5, Release 0 – 2, Audio modes HP & Dist 2. In soft passages, no compression should occur while on loud passages 17 – 20dB. This setting was used for tracking as well as mixing.

**Bass –** 4:1, 6:1 turn attack on 5, release 4. The distortion audio modes sound great on bass, but caution should be observed if you are going to tape/HD. You cannot un-distort. If you have a very "clacky" bass player, sometimes the band emphasis in the detector just flattens that stuff out. Use fast attack and release times to keep "clacks" from pumping. Also, try "Opto" mode.

**Electric Guitar –** A wide range of settings can be used. To get rid of edgy attacks, use quick attack, medium release. To smooth out solos, try the band emphasis in the detector to pull up the lower, softer notes and push back and sustain the higher, and often, thinner notes. Try "Opto".

**Acoustic Guitar –** We've been told by a couple of engineers that the Distressor is one of the best sounding units for acoustic they've ever heard. Use 6:1, \[ 7, 2, 5, 7\] settings (i.e. Input 7, Attack 2, Release 5, Output 7). High-pass (HP) is often useful in both detector and audio modes. The fast attack will get you a "glassy" full sound since the pick noise will be attenuated and the sustain lengthened.

**Piano / Keys –** Start with quick attack (0-4) and medium release (4-6). Acoustic pianos often need less attack to fit into a mix, but there are millions of exceptions. Bruce Hornsbyish pianos are often real or samples of real pianos with medium attack and medium release, getting that "bite" followed by sustained body. Try attack 5, rel 5. Opto mode is very nice here, too. Sometimes brittle high notes can be extra compressed by using the "band emphasis" detector mode.

**Drums –** Start by keeping the attack over 3 to keep transients. Play with decay to get more or less "in your face" sounds. Because of the wide range of attack, the Distressor puts the drum "percussiveness" much more into the engineer's control than the older, classic units.

**Snares / Kicks / Toms –** Try (3:1 to 6:1, 6,5,5,6). Shorten decay if you need to bring up "after ring". If a tom has too much attack , turn attack down between 0 - 4. If crackling from L.F., modulation occurs, play with longer attack or release times, or Det HP. Since you can load compression on without sounding funny, watch "mic leakage" which can become a problem. Kick drums sound great using Opto mode (10:1, attack on 10, release 0) and Det HP on.

**Room Mics –** For radical treatment, try 20:1 or "Nuke", \[10, 6, 2.5, 6\]. The "Nuke" ratio was originally developed for room mics, but we have since found it useful in many areas. "Nuke" and 20:1 are pretty much brick wall limiting, keeping any normal signal within 1 dB or so. Just patch in a room mic that is 10 - 25 feet from drums (or other instruments) and slam the meters. Try attack on 5 and release on 3. Fifteen to twenty dB of compression is starting to sound about right for the John Bonham thing, but don't be afraid to run the gain reduction meters right off scale. You will find the output a little lower than the other ratios in "Nuke".

Better have quiet mic preamps too - as 20 dB of compression can bring the noise floor up by 20 dB. The release should be quick (\< 3) for the largest sound, but slower releases can often be effective when mixed in with the rest of the kit. Room ambience can be made to "swell up" on the tom and snare rings later, filling in behind the close mics. If you want to add "grunge", experiment with Dist 2 and Dist 3.

## The ratios and their curves

Each "ratio mode" of the Distressor sets both the threshold and the ratio, in the standard sense of the word. This was done to provide an easy to set, yet versatile group of curves. The 1:1 mode provides no compression, but allows the audio to pass through the "warming" circuits of the unit (we'll get to the distortion modes in a moment). Ratios 2 through 6 are general purpose curves great for tracking. The 2:1 and 3:1 ratios are "parabolic" knees - very gentle curves that won't typically go into hard limiting and therefore, also won't provide absolute overload protection. Ratios 4:1 and 6:1 have steeper knees and are good general purpose curves that gradually move towards hard limiting, "nailing" the signal in its place. The ratio of 6:1 is very useful for vocals, bass, and acoustic instruments. It has an easy slope at first until after the knee, where an increasing ratio "musically" limits the peaks of the signal before damage is done. The 6:1 and 10:1 Opto ratios employ shorter knee limiting, reminiscent of some old classics from the 60's and 70's (see Classic Emulation).

"Nuke" is a different story. The "Nuke" ratio was developed for room mics, but we have since found it useful in many areas. "Nuke" has a medium threshold but when the signal hits it, a nuclear blast won't budge the output level. It is brick wall limiting, keeping any normal signal within 1 dB or so. Just patch in a room mic while recording drums (or other instruments) and slam the meters. Try attack on 4 and release on 2. The release curve of "Nuke" is logarithmic, meaning it lets off quickly at first and then slows. This release curve is a big part of the Distressor's sound. Experiment with the release times - this guy can release really fast without too much crackling, even on bass. 20:1 can be used similarly to "Nuke".

Each of these curves again has their own feel to them, with the release slopes slightly altered, and the knees falling in slightly different places. Most exceptional are the 2:1, 10:1 and Nuke ratios, which employ special detector circuitry. Just what is a soft knee? A "soft knee" is a compression curve where the first few dB of gain reduction occur at very low ratios, gradually increasing as the signal increases (gets louder). This makes the onset of compression very hard to detect. The knee usually extends for a few dB and gradually flattens out toward a final ratio. All curves with the exception of 20:1 and "Nuke" have dominant knees. The 2:1 ratio has a knee that can be as long as 30 dB, depending on attack and decay settings.

### Just what is a soft knee?

A "soft knee" is a compression curve where the first few dB of gain reduction occur at very low ratios, gradually increasing as the signal increases (gets louder). This makes the onset of compression very hard to detect. The knee usually extends for a few dB and gradually flattens out toward a final ratio. All curves with the exception of 20:1 and "Nuke" have dominant knees. The 2:1 ratio has a knee that can be as long as 30 dB, depending on attack and decay settings.

## Classic emulation

Since the unit is based on the oldest compressor topology, the unit can be made to sound very similar to older classics. The nonlinear nature of the older gain control elements of opto-couplers, FET's, pentode (or triode) tube bias or "mu" modulation, etc., can be closely emulated if proper settings are used. A special "Opto" mode has been provided in the 10:1 ratio.

### Some examples:

- To simulate the opto-VCA models of old (the LA-2A, LA-3A, LA-4A), try 10:1 "Opto" ratio, with attack on 10, release on 0, Det HP on. Adjust input and outputs to your taste. Keep the attack above 4 to keep the OPTO flavor. Faster attacks will give you a more aggressive sound. Remember our LED metering deflects much faster than the old VU's so don't be afraid to hit the unit quite hard (10-20 dB of compression on peaks). To emulate tubes, try Dist 2 & 3 mode, but let your ears be your guide.

- For a classic "Over E-Z" type sound, try ratios 2:1 thru 6:1, att 9, release 2, clean mode.

- 1176LN 6:1, Att 0 - 3.5, rel 1 - 10.5. Use ratios 3:1, 4:1, 6:1, 20:1 to emulate 4 1176LN ratios. Clean mode is appropriate (Dist 2 or 3 off). Remember that the 1176LN attacks extremely fast and you must keep attack under 4 max. A familiar sound is 6:1, att2, rel 4.

- Old Fairchild IGFET - 6:1 att 3-5, rel 2 - 7 (start with att 4 and rel 4)

Due to the transformerless design, you will maintain a low transient intermodulation distortion, but will get the warming grunge of 2nd and 3rd harmonic distortion, if distortion modes are enabled. Also, unlike some of the older units, the Distressor is uniform and predictable from one unit to the next. Precise factory calibration assures that if you go from one Distressor to another, these settings will all sound the same.

*Empirical Labs would like to thank Universal Audio for not only creating classic audio gear, but for kindly allowing us to refer to their model numbers. As they say "Once a classic, always a classic."*

![empirical-labs-logo.jpg](Empirical%20Labs%20EL8%20Distressor%20Manual_assets/37c2fa7d2917fc7593cacd4089b7a29c7d52493d.jpg) ![empirical_labs_distressor_el8-hw.jpg](Empirical%20Labs%20EL8%20Distressor%20Manual_assets/f2fca65811be1eff713531a0669fdb24767e67ce.jpg)

*Original Empirical Labs EL8 Distressor hardware*

All visual and aural references to the EL8 Distressor and all use of EMPIRICAL LABS's trademarks are being made with written permission from EMPIRICAL LABS, INC. Special thanks to Dave Derr for assistance with this project.

