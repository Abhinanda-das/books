---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/33030860246676-Cooper-Time-Cube-MkII-Delay-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'Cooper Time Cube MkII Delay Manual'
word_count: 1478
---

# Cooper Time Cube MkII Delay Manual


## Unique, garden hose-based mechanical delay device, captured as a plug-in.

Designed by Duane H. Cooper and Bill Putnam, the Cooper Time Cube was a garden hose-based mechanical delay device introduced in 1971. It has achieved cult status as the most unique delay ever made. Famous for its spectacular short delay and doubling effects — as well its uncanny ability to sit perfectly in the mix — the Cooper Time Cube is as character‑filled a device as you will ever find.

The Cooper Time Cube MkII plug-in for UAD‑2 hardware and Apollo interfaces is an exacting emulation of this utterly original, and usable device with an expanded feature set far beyond the original hardware. By capturing the sound of the original delay system, while offering modern delay features, the Cooper Time Cube MkII plug‑in is a versatile, fat‑sounding space maker without equal.

- Craft delay textures with the most unique delay device ever made
- Add intense doubling effects to thicken vocals, guitars, synths, and more
- Adjust Tempo Sync for A & B delay lines separately for intriguing rhythmic delays
- Expertly tweak repeats with Treble, Bass, Color, and High Pass Filter controls

<div class="wysiwyg-text-align-center">

![](Cooper%20Time%20Cube%20MkII%20Delay%20Manual_assets/2e701f1b009e4cf09a7946d7ef9068bb98f252da.png)

</div>

*Cooper Time Cube*

# Design Overview

The original Model 920-16 Cooper Time Cube hardware has two audio channels, A and B. Each channel is transduced to/from a coiled length of plastic tubing which provides the acoustic "sound columns" that define its distinctive sonic character.

The coils for each channel are at fixed but different lengths, which define the available single delay times of 16 ms for channel A, and 14 ms for channel B. The two channels can be cascaded in series via external routing, for a total available delay time of 30 ms at reasonable fidelity for its era, which (according to the original product brochure) "brings complete respectability to the heretofore marginally feasible acoustical delay line."

The UAD plug-in has all the vibe of the original, with modern feature enhancements. It is a true stereo plug-in with two independent delay processors. Each channel has its own set of controls, and there are global controls that affect the plug-in overall.

# Cooper Time Cube MkII Controls

## Global Controls

The global controls affect both channels of the processor simultaneously.

### Gain

Gain controls the signal input level to the plug-in for both A (left) and B (right) channels. Gain affects the combined wet and dry signals.

The available range is ±15 dB and the 12 o'clock position is unity gain.

**Tip:** Click the GAIN label to return the value to zero.

### HP Filter

The 12 dB per octave high pass filter is used to reduce low frequencies at the input to both delays when desired. The high pass filter affects the delayed (wet) signals only. The available frequency range is from 20 Hz to 12 kHz.

Turn the knob clockwise to reduce low frequencies into the delay processors. Full processor bandwidth is obtained when the knob is in the OFF position.

**Tip:** Click the OFF text label to quickly disable the HP Filter. Click the OFF label again to return to the previous value.

### Echo A/B

These two readouts display the current delay times of channels A and B. Displayed values are defined by the Delay A/B parameter. Delay or beat values can be entered here directly using the text entry method.

When Sync mode is off, delay times are expressed in milliseconds. When Sync is on, delay times are expressed as a fractional bar value.

When the beat value is out of range, the value is displayed in parentheses. This occurs in Sync mode when the time of the note value exceeds 2500 ms (as defined by the current tempo of the host application).

### Sync

This switch engages Sync mode for both channels of the plug-in. In Sync mode, delay times are synchronized to (and therefore dependent upon) the master tempo of the host application. When Sync is toggled, parameter units are converted between milliseconds and beats to the closest matching value.

See the "Tempo Sync" chapter in the UAD System Manual for detailed information about tempo synchronization.

**Tip:** Click the SYNC ON/OFF labels to change the setting.

### Send

Send determines whether or not signals are sent into the delay processors. When Send is ON, the input signals are delayed. When OFF, the delay inputs are muted.

Tip: Delay trails are preserved when Send is switched off, facilitating creative use of the Send feature.

### Coils

When both coiled tubes of the original hardware are cascaded to increase the available delay time (when both channels are serially connected), the sonics are slightly different than when only one coil is used. The Coils switch toggles between these two sounds that are available on the hardware, regardless of the Delay value or whether both channels are in use.

**Tip:** Longer Decay A/B ranges are available when the Coils switch is set to 1.

### Color

The Color switch toggles between the original filter emphasis of the hardware in position A and the "leveled" filter in position B, allowing for longer Decay A/B ranges. Color can be subtle, and its effect can vary depending on the value of Coils and/or Decay.

**Note:** Unlike the other A/B parameters, the A and B labels for Color are for reference only. They do not represent the left and right channels.

### Treble

Treble controls the high frequency response in the delayed portion of the signals. It does not affect the dry signal. Treble is a cut/boost control; it has no effect when in the 12 o'clock position.

**Tip: **Click the TREBLE label to return the value to zero.

### Bass

Bass controls the low frequency response in the delayed portion of the signals. It does not affect the dry signal. Bass is a cut/boost control; it has no effect when in the 12 o'clock position.

**Tip:** Click the BASS label to return the value to zero.

### Wet Solo

The Wet Solo switch puts the Cooper Time Cube into 100% Wet mode. When Wet Solo is on (in the "up" position), it mutes the dry unprocessed signal.

Wet Solo is optimal when the plug-in is used on an effect group/bus that is configured for use with channel sends. When the plug-in is used on a channel insert, this control should be deactivated.

**Note:** Wet Solo is a global (per plug-in instance) control. Its value is saved within the host project/session file, but not within individual preset files.

### Power

The Power switch determines whether the plug-in is active. It's useful for comparing the processed sound to the original signal.

### Meter

The VU Meter provides a visual indication of the output level of the plug-in (the meter is not calibrated).

## Channel Controls

The channel controls affect each channel of the processor independently. The control functionality is identical for each channel. "A" indicates the left channel and "B" is the right channel.

### Delay A/B

Delay controls the delay time for each channel of the effect. The selected value is shown in the Echo A/B display.

The available delay range for each channel is 5 milliseconds to 2.5 seconds (2500 ms). When Sync is active, beat values from 1/64 to 3/1 can be selected.

When the beat value is out of range, the value flashes. This occurs in Sync mode when the time of the note value exceeds 2500 ms (as defined by the current tempo of the host application). See the "Tempo Sync" chapter in the UAD System Manual for detailed information about tempo synchronization.

**Tip:** Click the knob then use the computer keyboard arrow keys to increment/decrement beat values in Sync mode. You can also use your mouse's scroll function to adjust values when hovering over the knob.

### Decay A/B

Decay sets the amount of processed signal fed back into its input (feedback). At the minimum value, one delayed repeat is heard. Higher values (clockwise) increase the number of repeats and intensity of the processed signal, with "near infinite" repeats available at the maximum setting.

### Pan A/B

Pan sets the position of the delayed (wet) signal in the stereo field; it does not affect the unprocessed (dry) signal. When the plug-in is used in a mono-in/mono-out configuration, the Pan knobs do not function and cannot be adjusted.

**Tip: **Click the PAN label to return to the center position.

### Echo Volume A/B

This control determines the volume of the delayed signal. Rotate the control clockwise for louder echo. Up to +10 dB of gain is available at the maximum setting. Reducing the control to its minimum position (OFF) mutes the delay.

**Tip:** Click the OFF label to mute/unmute the delayed output. Click OFF again to return to its previous setting.

<div class="wysiwyg-text-align-center">

![](Cooper%20Time%20Cube%20MkII%20Delay%20Manual_assets/c18566618717042b583e225484df6542b0ea8660.jpg)

</div>

*Cooper Time Cube Original Hardware*

