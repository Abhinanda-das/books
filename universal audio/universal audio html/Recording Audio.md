---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041441112-Recording-Audio.html'
converted_at: 2026-05-31T13:44:53Z
tool: htmlq+pandoc
title: 'Recording Audio'
word_count: 5971
---

# Recording Audio


LUNA includes a robust recording engine with sophisticated realtime features that can be used with Apollo, Core Audio, or ASIO to make great recordings.   

## This article includes:

- [Basic Recording](#h_86032ade-140c-4222-be87-5f284dd09005)
- [Configuring Track Inputs on Apollo](#h_2beb9ce3-1668-417a-b161-163434bf8c4a)
- [Configuring Track Inputs on Volt 876](#h_01K7XS4EEG93S7Q9E2RS94VD8A)
- [Assistive Auto-Gain (Apollo X Gen 2 and Volt 876)](#h_01KCPSWR7BZSHK7AH5BS4NT6XG)
- [Recording Audio from Inputs](#h_5f9c4d51-a71b-4ba4-8b94-1655d91341bc)
- [Loop Playback and Recording](#h_5fc0a2e8-1c81-452e-93a3-23fdccbdf2a8)
- [Tracking Multiple Audio Sources](#h_d600a046-fe00-4419-9911-951d4891b645)
- [Recording Multiple Inputs at Once](#h_01HYCTJWGT9DEBWS9DA56HC6GT)

## Apollo recording features

With LUNA's Accelerated Realtime Monitoring (ARM) and Apollo, you can easily record and monitor multiple audio and instrument tracks with no discernible latency. On tracks that are record-enabled or input-enabled, you can monitor with UAD plug-ins, and you can monitor two ARM AUX-enabled buses that are in the record path (buses that are receiving audio from a record or input-enabled track). While recording, you can monitor tracks that are not record-enabled or input-enabled with UAD plug-ins.

## Common recording features

With Apollo, ASIO, or Core Audio, you can monitor tracks with LUNA Tape emulation, Audio Unit or VST3 plug-ins, and monitor buses with plug-ins and API or Neve Summing. All latencies are automatically delay-compensated by LUNA, and track counts are limited only by the capabilities of your computer. 

In Core Audio or ASIO mode, ARM is not available, there is no Unison insert, and recording latency is determined by your system’s audio buffer. With Volt 876, you can adjust and recall preamp channel controls directly in LUNA, with bi-directional communication between UAD Console and LUNA. 

 

 

------------------------------------------------------------------------

 

# Basic Recording

The basic recording process in LUNA is simple. More input and tone shaping options are available when operating LUNA in Apollo Mode, or when using a Volt 876 interface. For other interfaces, set your track input levels and other options using your interface controls and/or software.

## Basic recording process

1.  On the audio track, click on the Input row in the Mixer channel or on the Focus channel. The Input Focus Browser opens.
2.  Choose the Input to which your source is connected.
3.  Adjust the gain and preamp options for your input, if available. 
4.  Click the Record enable button on the track, or press Shift+R.\
    **Note:** If no tracks are record-enabled, when you press Record, any currently selected tracks are record-enabled, and audio or MIDI is recorded on those tracks.
5.  Press the Record button in the LUNA transport, or press the key command to start recording (Command+Spacebar on macOS, Control+Spacebar on Windows).

------------------------------------------------------------------------

# Configuring Track Inputs on Apollo

Apollo interfaces include several special preamp features for inputs.

![record-inputs.png](Recording%20Audio_assets/b74acea0e9810754c1f2fc6e62f8f24233d87fa1.png) *Audio inputs (Apollo / ARM mode)*

Preamp controls correspond to the equivalent preamp controls on the Apollo hardware. Adjusting Apollo’s hardware preamp options updates LUNA, and vice versa.

Some preamp hardware controls (Gain, Low Cut, 48V, Pad, and Polarity) are Unison parameters that interact with Unison plug-ins placed in the Unison insert. 

**Note:** You can only adjust preamp controls and Unison plug-in parameters when a track is record-enabled or input-enabled.

## Preamp Inputs

Each of Apollo’s preamp channels have multiple analog inputs (mic, line, Hi-Z) that can be selected with the preamp controls. 

Click to switch between mic and line inputs manually in LUNA or on the Apollo hardware. Channels are automatically switched to Hi-Z inputs when a 1⁄4” mono (tip-sleeve) cable is connected to Apollo’s Hi-Z input jack.

With preamp inputs and Apollo X Gen 2 interfaces, you can use Auto-Gain to set preamp levels. See [Assistive Auto-Gain](#h_01KCPSWR7BZSHK7AH5BS4NT6XG) for more information.

## Line inputs

Analog line inputs without mic preamps are available on some Apollo models. These line inputs may have a reference level switch instead of preamp controls.

## Digital inputs

Digital inputs work like analog inputs, except they don’t have the extra preamp and reference level settings that may be available on the analog inputs.

## Virtual inputs

Virtual input channels do not reflect Apollo hardware inputs. Instead, they receive digital signals from the computer system via Apollo’s device drivers, enabling Realtime UAD Processing on digital audio signals that may be present in the system. On macOS, you can route digital signals to virtual inputs with the Audio MIDI Setup utility.

## Low Cut

When enabled, the channel’s input signal passes through a low cut (high pass) filter. The filter has a cutoff frequency of 75 Hz with a slope of 12 dB per octave by default, though the filter can change when a Unison plug-in is active in the channel. The Low Cut filter affects the Mic, Line, and Hi-Z inputs. Low Cut is typically used to eliminate rumble and other unwanted low frequencies from the input signal. 

**Note:** The default low cut filter slope and frequency can change if a Unison plug-in is active in the channel. The input scaling and fader taper can also change if you use a Unison plug-in.

## 48V

Enable the 48V control to supply 48 volts of phantom power to the equipment connected to the Apollo channel’s Mic input. The indicator light is red when enabled. Many modern condenser microphones require 48V phantom power to operate. This option can only be activated when the Mic/Line switch is set to Mic. 

Activate 48V phantom power only with compatible equipment such as phantom-powered microphones. Incompatible equipment, such as some ribbon microphones, may be damaged by the applied voltage. There is a delay and audio is muted when changing the 48V state, to minimize the clicks and pops that are inherent when engaging phantom power. The 48V LED on the Apollo flashes during this delay.

**Caution:** To avoid potential equipment damage, disable +48V phantom power on the channel before connecting or disconnecting its XLR input.

## Pad

Enable the PAD control to attenuate the microphone input signal level by 20 dB. The indicator light turns yellow when enabled. Pad does not affect the Line or Hi-Z inputs. Pad is used to reduce signal levels when overload distortion is present at low preamp gain levels, such as when particularly sensitive microphones are used on loud instruments, or if the A/D converter is clipping.

## Polarity

Enable the polarity switch to invert the channel’s signal. The indicator light turns yellow when enabled. Polarity affects the Mic, Line, and Hi-Z inputs. 

**Tip:** Polarity inversion can help reduce phase cancellations when more than one microphone is used to record a single source.

------------------------------------------------------------------------

## Configuring Track Inputs on Volt 876

Volt 876 interfaces include tone shaping features for inputs.

 

![volt-876-in-luna.png](Recording%20Audio_assets/38ff6071c2215d059db4e9afef9ef29bf1dc9fab.png)

## Input

Opens the Input browser to select an input or input pair from Volt 876.

## Vintage preamp mode

Vintage preamp mode adds a carefully crafted analog tube preamp emulation, inspired by Universal Audio’s all-tube 610 console preamplifier, for a richer sound. When the button is lit orange, the circuit is active.

Press the Vintage switches to toggle Vintage preamp mode. Vintage preamp mode can be used on mic, line, and instrument inputs. When enabled, the Vintage button is lit in LUNA and UAD Console, and on the Volt 876 hardware for the input.

## 76 compressor

To enable or disable a 76 compressor preset, click the preset name, or press the 76 Comp button to toggle the 76 compressor circuit on/off. The 76 compressors can be used on mic, line, and instrument inputs. The button is lit orange when the compression circuit is active.

The 76 Compressor lets you add clarity and punch to voice, guitars, and more, with an analog compressor based on UA's iconic 1176 Limiting Amplifier.

**Tip:** The input level increases when the compressor is active, so you may want to readjust your Gain setting.

### 76 Compressor Presets

The indicators below the 76 Comp button indicate whether the compressor is off or enabled with one of the presets. The 76 Comp presets have the following characteristics:

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="table--striped wysiwyg-table-resized">
<colgroup>
<col style="width: 17%" />
<col style="width: 83%" />
</colgroup>
<tbody>
<tr>
<td>FAST</td>
<td>Very fast attack and medium release for aggressive compression</td>
</tr>
<tr>
<td>GUITAR</td>
<td>Slow attack and relatively quick release allows more guitar/bass transients</td>
</tr>
<tr>
<td>VOCAL</td>
<td>Fast attack and slow release for classic smooth vocal compression</td>
</tr>
</tbody>
</table>
</figure>

</div>

**Tip:** Although these presets are designed to work well with these particular sources, you can use any setting with any source. Feel free to use the 76 Comp creatively.

## Instrument switch (channels 1–2 only)

Press the INST switch to toggle the impedance and gain of the ¼" input to accommodate a Hi-Z instrument, such as an electric guitar or bass.

## Gain knob

You can manually adjust the gain for an input channel with the gain knob in LUNA or UAD Console, or you can use the encoder on the left side of the Volt 876 hardware. In LUNA, drag the knob to adjust the level. Adjust the level so your loudest sources do not peak in the red on the LUNA track meter. 

## 48V phantom power

If you are using equipment that requires phantom power, such as a condenser microphone, engage the 48V switch on the channel. When 48v phantom power is enabled, the 48V LED is lit red in LUNA and UAD Console, and on the Volt 876 hardware for the channel. The 48V LED blinks briefly when enabling or disabling phantom power. Do not connect or disconnect equipment from the input when 48V phantom power is enabled, or when the LED is blinking.  

**Caution**: Activate 48V only with compatible equipment such as phantom powered microphones. Incompatible equipment could be damaged by the applied voltage.

## Polarity

Enable the polarity (phase) switch to invert the channel's signal polarity. When enabled, the switch is lit in LUNA and UAD Console, and on the Volt 876 hardware for the selected channel.  

**Tip:** Invert polarity to reduce phase cancellations when more than one microphone is used to record a single source.

## Volt 876 digital input details

The digital inputs route digital signals (ADAT or S/PDIF) into the mixer.

Unlike analog inputs, there are no tone-shaping features or preamp controls for digital channels. Signal levels for the digital inputs are set by adjusting the output levels of the digital gear connected to Volt 876.

------------------------------------------------------------------------

# Assistive Auto-Gain (Apollo X Gen 2 and Volt 876)

You can set preamp input gain automatically with Assistive Auto-Gain.

**Caution:** Assistive Auto-Gain automatically adjusts preamp levels for recording. To avoid damage to your hearing, confirm your monitor levels are set safely before proceeding.

## To set gain automatically

1.  On any preamp channel, press the Auto-Gain button under the gain knob. The Auto-Gain floating window opens.

![](Recording%20Audio_assets/749a7d028a3ad4f414490acc3f51ef7fdbb20781.png)

2.  Press Start, and play your source as loudly as you will play during the performance. The gain is set automatically.

By default, Assistive Auto-Gain detects and adjusts levels for 10 seconds. To increase or decrease the duration by ±5 seconds, press the -5 or +5 buttons. You can adjust the duration while Auto-Gain is listening.

The Auto-Gain floating window closes after the listening duration completes. To close the Auto-Gain window, click Done.

**Note:** When using Auto-Gain with stereo linked inputs, the same gain amount is applied to both inputs. Auto-Gain sets the level based on the peak information from the loudest input.

**Tip:** You can set Auto-Gain on multiple preamps simultaneously. Simply click the Auto-Gain button for each preamp you want to adjust. The Auto-Gain options in the floating window apply to all Auto-Gain-enabled preamps.

## Auto-Gain settings

Click SHOW MORE to see more settings for Auto-Gain.

![](Recording%20Audio_assets/86769073dc213b92b1748b7b2f9dbaef2b266480.png)

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="table--striped wysiwyg-table-resized" style="margin-left: 0px; margin-right: auto;">
<colgroup>
<col style="width: 28%" />
<col style="width: 72%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; width: 25%;"><strong>Feature</strong></td>
<td style="text-align: center; width: 75%;"><strong>Details</strong></td>
</tr>
<tr>
<td style="text-align: center; width: 25%;">Duration</td>
<td style="text-align: center; width: 75%;"><p>Sets the amount of time that Auto-Gain listens while setting gain levels.</p>
<p>The default setting is 10 seconds. To set a different duration, click and drag up or down in the box, or click the -5 or +5 buttons. You can also click in the box and type a new value, then press Enter.</p>
<p><strong>Note:</strong> The maximum duration is 90 seconds. </p></td>
</tr>
<tr>
<td style="text-align: center; width: 25%;"><p>Apply Gain</p>
<p><br />
 </p></td>
<td style="text-align: center; width: 75%;"><p>Sets the Auto-Gain adjustment behavior.</p>
<p>WHILE LISTENING applies gain changes every two seconds for the Auto-Gain duration. You can only use WHILE LISTENING with one or two preamps enabled for Auto-Gain. </p>
<p>AFTER LISTENING applies the gain change after the Auto-Gain listening duration is complete.</p></td>
</tr>
<tr>
<td style="text-align: center; width: 25%;">Listening Threshold</td>
<td style="text-align: center; width: 75%;">Determines the lowest level at which Auto-Gain detects a signal and begins adjusting gain. This setting ensures that Auto-Gain doesn’t set very loud gains when no detectable signal is available. The default setting is -50 dBFS, which may be too quiet for low level sources. To set a different threshold, click and drag up or down in the box, or click in the box and type a new value, then press Enter.</td>
</tr>
<tr>
<td style="text-align: center; width: 25%;"><p>Peak Target</p>
<p><br />
 </p></td>
<td style="text-align: center; width: 75%;">Determines the maximum peak level that Auto-Gain should set for your material. The default setting is -8 dBFS, but you can adjust it higher or lower. Be aware that higher settings (less headroom) increase the risk of digital clipping. To set a different peak target, click and drag up or down in the box, or click in the box and type a new value, then press Enter.</td>
</tr>
</tbody>
</table>
</figure>

</div>

------------------------------------------------------------------------

# Recording Audio from Inputs

With non-Apollo devices in Core Audio or ASIO modes, plug-in processing is not recorded. 

## What is recorded in Apollo Mode?

Audio can be recorded with or without UAD plug-in processing with Apollo.

Unison technology is activated when a Unison-enabled UAD plug-in is loaded in the dedicated Unison insert located above the preamp options. The Unison insert is only available on preamp channels. 

Audio on preamp channels is processed by the Unison insert before the Record FX inserts. Unison and Record FX plug-in processing is always recorded. 

**Tip:** You can monitor through UAD plug-ins without recording their processing by placing them in the standard inserts.

## Record enabling and Input enabling tracks

Record and/or Input enable tracks to monitor track inputs according to your workflow needs. 

![record-input-enable.png](Recording%20Audio_assets/201203f5db123b3b97b7dcc3b2247b16930f9077.png)

When you record-enable or input-enable a Unison-capable track, the Unison insert and Record FX inserts are made available, and the channel preamp controls become active.

![record-input-enabled-vs-disabled.png](Recording%20Audio_assets/8253332211a5b6782a952dfb038f932e6be0a7a3.png)

### Record enabled

When an audio track is Record enabled, you can monitor the input to the track while the transport is stopped and while the transport is playing and record-ready. When an audio track is record-enabled, and the transport is playing but not recording, audio from the input is muted, and audio clips on the track are played through LUNA. When the transport is recording, all Record enabled tracks are recorded to disk.

#### Record-enable tips

- You can record-enable one or more selected tracks by pressing Shift+R.
- If no tracks are record-enabled, when you press Record, any currently selected tracks are record-enabled, and audio or MIDI is recorded on those tracks.

### Input enabled

When an audio track is input-enabled, you can monitor the input to the track at all times, whether the transport is stopped, playing, or recording. When an audio track is input-enabled, the audio clips on the track do not play through the LUNA mixer. When a track is both record-enabled and input-enabled, the track is monitored at all times, but the track is recorded to disk when the transport is recording.

#### Input-enable tips

- You can input-enable all record-enabled tracks automatically by pressing Option+K (macOS) or Alt+K (Windows).
- You can input-enable one or more selected tracks by pressing Shift+T.

## To record audio

1.  In the Tracks browser, click the plus (+) next to Create New Tracks.
2.  From the Type drop menu, choose Audio. Choose the number of tracks to create, the format (Mono or Stereo), and type a name for the track or tracks.
3.  Click OK to create the tracks, or Cancel to stop track creation.
4.  (Apollo Mode) To record with ARM for the lowest latency, click the ARM button in Global Controls, or choose Transport \> Accelerated Realtime Monitoring to enable ARM.\
    \
    ![arm-button.png](Recording%20Audio_assets/db70ec6b85ad25b9d54e2ba1c081f8857064c77d.png)\
     
5.  Connect a mic, line source, or Hi-Z instrument into an input on your audio interface.
6.  On the audio track in the Focus channel or Mixer, click the Input mixer row. The Input browser opens.
7.  Choose the input to which your source is connected.
8.  Click the Record enable button in the track or Focus channel (Timeline view) or in the channel (Mixer view) or press Shift+R to record enable the audio source. If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.
9.  (Volt 876) Adjust Vintage preamp mode and 76 Compressor settings.
10. (Apollo mode) If you want to use a Unison plug-in click the Unison insert and choose the plug-in. Adjust the settings for the Unison plug-in. Some Unison plug-in settings can be adjusted from Apollo hardware. All settings can be adjusted from the plug-in and LUNA channel controls.
11. (Apollo mode) To record with Record FX, insert up to four UAD plug-ins in the channel’s Record FX inserts.
12. Adjust the audio settings until the audio levels are correct. You want to record with enough headroom so the recording track doesn’t clip. \
    If your preamp includes Auto-Gain capability, you can set levels automatically by clicking Auto-Gain.See <a href="#h_01KCPSWR7BZSHK7AH5BS4NT6XG" style="background-color: #ffffff; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">Assistive Auto-Gain</a><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> for more information.</span>
13. Click Record in the transport or press Command+Spacebar (macOS) or Ctrl+Spacebar (Windows) to record audio.
14. Click Stop or press the Spacebar to stop recording.

To listen back to the recording, press Play or the Spacebar. 

**Note:** You can listen to the recorded track if the track is record-enabled, but not if the track is Input-enabled. 

## To record starting at a specific point on the timeline

1.  Switch to Timeline view. 
2.  Click on a location in the Timeline where you want to begin recording. Click above the center of an audio track, or in any of the rulers. 
3.  To use Pre-roll (listen to the existing track for a specified period of time before you start recording), Option+Click (macOS) or Alt+Click (Windows) to the left of the playhead on the Bars and Beats ruler.\
    \
    ![qs-option-click-pre-roll.png](Recording%20Audio_assets/2681847a0d39857736125cc8bcd08e3798f10c2a.png)
4.  Record-enable track(s), and input-enable if necessary. If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.
5.  Click Record in the transport or press Command+Spacebar.
6.  Click Stop or the Spacebar to stop recording.

You can also move the playhead to a specific time by typing a time in the Counter field, and pressing Return. For example, in Bars and Beats mode, type 122 to move the playhead to 122\|0\|000, or type 122\|2 to move the playhead to 122\|2\|000.

<div layout="align-start" node-type="mediaSingle" data-width="25">

<div class="wysiwyg-text-align-center" collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="counter-set-location.png" file-size="15237" data-height="187" data-id="acfbd922-6d6b-4926-8a03-967de7c2cbb1" node-type="media" data-type="file" data-width="123" title="Attachment">

![counter-set-location.png](Recording%20Audio_assets/ed52d0242b143e75d4e5489f5e3f5b35d956089e.png)

</div>

</div>

 

## To record in a selection on the timeline (punch-in recording)

1.  Switch to Timeline view. 
2.  Click on a location in the Timeline where you want to begin recording, and drag to the right or the left to select the range to record. Click and drag above the center of an audio track, or in any of the rulers. 
3.  To adjust the selection length, move the playhead to a position to the right or left of the center of the selection and Shift+Click. Note that you can lengthen or shorten a selection with this method. 
4.  To use Pre-roll (listen to the existing track for a specified period of time before you start recording), Option+Click (macOS) or Alt+Click (Windows) to the left of the playhead on the Bars and Beats ruler.\
    \
    ![qs-option-click-pre-roll.png](Recording%20Audio_assets/2681847a0d39857736125cc8bcd08e3798f10c2a.png)\
     
5.  Record-enable track(s), and input-enable if necessary. If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.
6.  Click Record or press Command+Spacebar (macOS) or Ctrl+Spacebar (Windows).
7.  Click Stop or the Spacebar to stop recording.

You can also make a selection by typing a start time in the Start time field, and either a length in the Length field, or a stop time in the End field, then pressing Enter. For example, in Bars and Beats mode, type 122 in the start field and 8 in the Length field to select 8 bars from 122\|1\|000 to 130\|1\|000.

<div layout="align-start" node-type="mediaSingle" data-width="30">

<div collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="enter-selection-values.png" file-size="17777" data-height="127" data-id="84b2278f-a9fd-4878-9df7-17f0900846a2" node-type="media" data-type="file" data-width="141" title="Attachment">

</div>

![enter-selection-values.png](Recording%20Audio_assets/487fe1a5744db8d4503dd3d96fa522b975d6b771.png)

 

## Using Count In

You can use Count In to play 1, 2, or 4 bars of clicks before recording starts. There is no session playback during Count In. Count In bars only play when the Record button is enabled in the transport.

### To enable or disable Count In

1.  Click the Count In icon (a 1, 2, or 4 next to the metronome), or press Shift+K or 8 on the Numeric Keypad to toggle Count In on or off
2.  To set the number of bars of Count In, click at the top of the click ruler to open Click options. Under Count In Bars, click the number of bars of Count In.

<div class="rich-media-item mediaSingleView-content-wrap image-align-start sc-ktHwxA krYOxy sc-hEsumM ctvdQk" layout="align-start" node-type="mediaSingle" data-width="55">

<div class="sc-tilXH ebLIpN">

<div class="sc-iUVpnZ kjiQPu" collection="contentId-225739029" context-id="225739029" file-mime-type="image/png" file-name="count-in-enabled-bars.png" file-size="101903" data-height="246" data-id="dcdb52ce-4cfc-4864-8dbb-d866639a3517" node-type="media" data-type="file" data-width="347">

<div class="sc-bXopBW gkwhtE" testid="media-card-view">

<div class="wysiwyg-text-align-center media-file-card-view sc-hhaNoI hPeodW" test-media-name="count-in-enabled-bars.png" test-progress="1" test-status="complete" testid="media-file-card-view">

![count-in-enabled-bars.png](Recording%20Audio_assets/d38cc167d24a2fb0a5095398e7264164df5211a4.png)

</div>

</div>

</div>

</div>

</div>

 

<div collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="enter-selection-values.png" file-size="17777" data-height="127" data-id="84b2278f-a9fd-4878-9df7-17f0900846a2" node-type="media" data-type="file" data-width="141" title="Attachment">

</div>

</div>

## Stop recording and discard recorded files

To stop any in-progress recordings and immediately delete the audio or MIDI, press Command+Shift+.\[period\] (macOS) or Control+Shift+.\[period\] (Windows), or select Transport \> Abort Recording while recording. The session continues playback, but the audio or MIDI you are recording is removed from the timeline and deleted from the session file. 

When you discard a recording during loop recording, only the most recent take is removed from the timeline and deleted from the session file. Files being recorded are moved to the macOS Trash. There is no undo for Discard Recording.

 

------------------------------------------------------------------------

 

# Loop Playback and Recording

In loop playback/record mode, you play or record over a selection repeatedly. Use loop playback to audition a section repeatedly, when editing or adjusting levels or plug-ins. Use loop recording to build up or replace a MIDI performance with successive takes, or to record multiple takes on audio tracks. You can enable Loop by making a selection on any ruler or in the timeline, or with the special-use Loop Ruler.

You can make a selection on the Loop ruler to continuously loop a section of the session, while making edits to audio or MIDI data, without changing the original selection or moving the playhead. The Loop ruler appears in orange in Timeline view at the top of the track area. A selection on the Loop ruler is only active when Loop Playback/Record is enabled.

## Loop Playback behavior

A selection on the Loop ruler continues to loop during playback. You can make selections on the Timeline, and edit audio and MIDI tracks, and the Loop ruler continues to play the same loop. However, if you make a selection on the Bar and Beats ruler, that selection overrides the Loop ruler selection. When you stop and start playback, playback starts from the selection on the Loop ruler, unless the selection has been overridden by a selection on the Bars and beats ruler. When Link Edit/Play Selections is active, after the transport stops, playback starts from the timeline selection or playhead location, even if there is a Loop ruler selection.

## Loop Record behavior

A selection on the Loop ruler continues to loop during record. The selection continues to loop and record over that selection, even if you make a different selection on the Bars and Beats ruler or in the timeline, until the transport stops.

<div layout="align-start" node-type="mediaSingle" data-width="90">

<div collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="enable-loop-ruler.png" file-size="95134" data-height="202" data-id="47f717fe-6f29-4de3-a690-b7f13978a54c" node-type="media" data-type="file" data-width="609" title="Attachment">

![enable-loop-ruler.png](Recording%20Audio_assets/40c97962dfd51967c569e0c37c5fa8342c9a9764.png)

</div>

<div collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="enable-loop-ruler.png" file-size="95134" data-height="202" data-id="47f717fe-6f29-4de3-a690-b7f13978a54c" node-type="media" data-type="file" data-width="609" title="Attachment">

</div>

</div>

#### To loop playback while editing audio or MIDI:

1.  Disable Link Edit/Play selections on the Bars and Beats ruler.
2.  Enable Loop Playback/Record on the Transport (Ctrl+L on macOS or Alt+L on Windows).
3.  Select a range in the Loop ruler. This range indicates the start and end of the section to loop. You can click and drag on either end of the loop selection to extend or shorten the selection.
4.  Click Play on the Transport or press the Spacebar. 

The section you selected plays back. While the looped selection is playing you can select, edit, copy, paste, or delete data from any audio or Instrument tracks in the timeline, and make any other adjustment, without the loop stopping or changing. When you complete edits for a section, you can click and drag the loop to a different position in the timeline, or edit the length of the loop. Loop playback continues as you adjust the loop.

After you make changes to a loop, Loop playback resumes, based on the Update Playback setting.

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 100%;">
<table data-autosize="false" data-layout="default" data-number-column="false">
<tbody>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="309" style="width: 40%"><strong>Setting</strong></td>
<td class="pm-table-cell-content-wrap" data-colwidth="450" style="width: 60%"><strong>Playback behavior after the loop changes</strong></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="309" style="width: 40%">Transport > Update Playback > Instantly</td>
<td class="pm-table-cell-content-wrap" data-colwidth="450" style="width: 60%">Playback immediately restarts from the beginning of the new loop selection.</td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="309" style="width: 40%">Transport > Update Playback > At Next Bar</td>
<td class="pm-table-cell-content-wrap" data-colwidth="450" style="width: 60%">Playback continues to the end of the next bar, then restarts from the beginning of the new loop selection.</td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="309" style="width: 40%">Transport > Update Playback > At Loop End</td>
<td class="pm-table-cell-content-wrap" data-colwidth="450" style="width: 60%">Playback continues to the end of the loop that was previously defined, then restarts from the beginning of the new loop selection.</td>
</tr>
</tbody>
</table>
</figure>

### Loop recording, Versions, and Takes

When you loop record, you replace a section of a track that you select with one or more recording passes, or "takes." When LUNA reaches the end of the selection, the transport returns back to the start of the selection, and records again. Each loop record pass is saved as a Version labeled with a T (for Take).  The first recording on a track is labeled with a V, as are all other Versions created by adding or duplicating Versions. Takes are labeled with a T to indicate that they were automatically created by the loop record process.To show recorded Versions and Takes, click the Versions button at the top of the Tracks area.

**Note:** If the track height is too small to show the Versions list, the name of the current version appears in the Versions area, and you can click on the name to open a list of Versions and perform Version operations.

A Take is not always a complete track. Therefore, when you switch from a Version to a Take, you will not see the entire track, but only the section that was loop-recorded. 

#### To loop record:

1.  Make an audio selection and click the Loop Play / Record button or press Control+L (macOS) or Alt+L (Windows).\
    \
    ![transport-loop-enabled.png](Recording%20Audio_assets/81916c20a09e55f39c69d566bb5bc1c5134f4aa2.png)
2.  Record your source.
3.  Click the Versions icon to show track Versions. \
    ![versions-button.png](Recording%20Audio_assets/b2dd1493d5364ef630421f01bfde994bfc30b45f.png)\
     
4.  To switch between Versions, click a Version. \
    ![qs-versions-takes.png](Recording%20Audio_assets/000eb086419bc31b4ea9a5b3c4d5e2ac6e822c51.png)

To assemble different clips together using Versions, see <a href="360041428432-Working-with-Audio-in-the-Timeline.html#comping" target="_self">Comping Tracks with Versions</a>.

------------------------------------------------------------------------

# Tracking Multiple Audio Sources

Features for recording multiple audio sources in LUNA include: 

- Setting up audio tracks for multiple inputs at once by assigning cascading inputs. 
- Using cues to send a click and custom mixes to different groups of performers. 
- Easily copying the current mix to a cue bus. 
- Punch-in recording with multiple tracks.
- Switching the transport in and out of record on the fly.

## Configuring multiple tracks for recording

Use Cascade mode to route multiple inputs to audio tracks quickly.

### To assign multiple inputs in order to tracks:

1.  Select multiple tracks in the Timeline or Mixer. (If you do not select multiple tracks, you can click Apply to All to apply cascade routing to all tracks in the session.) 
2.  Click the input on the first track you want to assign. The Input browser opens.
3.  Next to Routing, click the ••• options menu and select Cascade.\
    \
    ![cascade-routing.png](Recording%20Audio_assets/a706511082d5d489ca99b195f7b99298e54b2552.png)
4.  Click the first input you want to assign.
5.  At the bottom of the tracks list, under Apply To, click All or Selected to choose the tracks to which you will apply cascade routing.

![cascade-apply-all-selected.png](Recording%20Audio_assets/5aa61adf118ecad5e065d1c47437631777e7e6e2.png)

The selected tracks (or all tracks) are assigned the remaining inputs, in order.

 

------------------------------------------------------------------------

 

# Recording Multiple Inputs at Once

To record on multiple inputs, use selection grouping to enable recording on multiple tracks. To enable selection grouping, select Track \> Selection Grouping (Command+G).

## To record on multiple tracks

1.  In the Mixer or Timeline, select multiple tracks. In Apollo mode, all tracks you record enable must be assigned with unique inputs. \
    **Tip:** You can assign multiple track inputs with <a href="#h_cf3db2ba-0c99-49ab-b395-d258a56864c3" target="_self">Cascade routing</a>.
2.  Record-enable one track, either by clicking the record-enable button, or pressing Shift+R. All selected tracks will be record-enabled.
3.  Add Unison, Record FX, and standard insert plug-ins to the tracks if needed.
4.  Adjust the audio settings until the audio levels are correct. You want to record with enough headroom so the recording track doesn’t clip.
5.  Click Record in the transport to record audio.
6.  Click Stop or press the Spacebar to stop recording.

You can make multiple input recordings with all of the same options as a single track recording, including Unison plug-ins, Record FX plug-ins, standard insert plug-ins, and buses, as DSP is available. 

## Recording features with multiple tracks

You can easily switch multiple tracks in and out of record mode while playing a session. Simply record enable the tracks you want to record, and press the Record button on the transport to toggle in and out of record. Enable ARM mode to do this seamlessly.

**Note:** If you do not record-enable one or more tracks, any selected tracks are recorded when you toggle recording.

<span id="using-console-tracking-mode"></span>

## Using Console Tracking Mode with UAD Console

Console Tracking Mode allows you to use UAD Console for live channel inputs, and prevents LUNA from automatically muting and unmuting UAD Console channels when recording. Essentially, all inputs remain live, and UAD Console works as it previously did, while LUNA is running. 

In Console Tracking Mode, UAD plug‑ins do not persist in LUNA inputs as they normally do. Instead, when you record-enable a track in Console Tracking Mode, the plug-ins assigned to the track in UAD Console are loaded into the LUNA channel.

Because you always hear the channels from UAD Console in Console Tracking Mode, you do not need to use the Input enable button on a track to monitor the audio source, as long as the source is not muted in UAD Console. However, you still need to record-enable tracks to record audio. 

#### To enable Console Tracking Mode

-  From the LUNA app menu, choose Transport \> Console Tracking Mode.

## Punch-in recording with multiple tracks

You can easily punch-in record on multiple record-enabled tracks, with multiple performers. You can even record-enable input tracks while LUNA is playing or recording, which allows you to enter record mode for any input without stopping the transport.

### To prepare for punch-in recording

- If you want to record at a specific point, move the playhead to the record location, or make a selection you want to record over. Alternatively, you can play the song and punch in with the record button as needed.

- Set the system in ARM mode.

- Make sure record-enabled tracks are not input-enabled. This allows performers to hear the recorded tracks until recording starts, and after recording stops, and hear live input while recording.

  **Note:** If you do not record-enable one or more tracks, any selected tracks are recorded when you toggle recording.

- Set a pre-roll for the performers. This allows the performers to play along to the music before the recording starts.

In this scenario, you can press Record to record on multiple tracks. With the capabilities of the LUNA recording engine, you can also easily play the song and have the performers play along, and punch them in and out manually by pressing the Record button on the Transport to toggle recording on and off. 

<span id="cue-mixes"></span>

## Making cue mixes

You can use up to four independent stereo Cue mixes in LUNA. You set Cue sources and assign Cue mixes to those sources, to allow performers to listen to a different mix when recording. When a hardware output pair is set to Cue (in the Cue Outputs popover), the cue source is the dedicated cue mix, determined by the settings on the Cue row in the Mixer. In this mode, the mix of the cue bus is determined by the cue send controls in the session’s tracks.

Note: The number of available Cue mixes is determined by the connected UA audio interface hardware and the Cue Bus Count value in LUNA Settings.

Cue sends are pre-fader by default, though they can be configured to be post-fader. When a Cue is pre-fader, changes to levels, pan, mute and solo on the channel strip do not affect the Cue mix send for that channel. 

Once you assign outputs to Cues (in the Cue Outputs popover), you can set channels as pre-fader in a Cue mix, and you can use the compact or large Cue strips to set the level and pan for each track in the Cue mix, and to mute tracks in the Cue mix. To simplify setting up a Cue mix, you can easily copy the levels and pan settings from your mix to one or more Cue mixes.

Cues have a dedicated Level knob, mute and Pre-fader switch. When you expand a Cue row to Large view, the expanded Cue channel has a more accurate fader and dedicated pan controls.

<div layout="align-start" node-type="mediaSingle" data-width="80">

<div class="wysiwyg-text-align-center" collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="cues-small-large-annotated.png" file-size="166717" data-height="428" data-id="710453e7-bcbb-4805-b87a-5b0bca3e44a5" node-type="media" data-type="file" data-width="529" title="Attachment">

![cues-small-large-annotated.png](Recording%20Audio_assets/24811773fd9ed05952cf1a0989847668230ec639.png)

</div>

<div collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="cues-small-large-annotated.png" file-size="166717" data-height="428" data-id="710453e7-bcbb-4805-b87a-5b0bca3e44a5" node-type="media" data-type="file" data-width="529" title="Attachment">

</div>

</div>

### To assign an Apollo Cue to an output:

1.  Choose View \> Section \> Monitor.
2.  Click the Cue Outputs button on the Monitor column. A list of devices and available Cue outputs appears on a popover window. The left column displays connected devices, the right columns display available outputs for each Cue, and each row displays the device’s current Cue output assignments. 
3.  If you want to make a custom mix for a Cue, deselect Mix in a column on the popover. When Mix is NOT illuminated, you create a Cue mix using the channel strip Cue sends.

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div class="wysiwyg-text-align-center" collection="contentId-194674764" context-id="194674764" file-mime-type="image/png" file-name="assigning-cues.png" file-size="184048" data-height="303" data-id="175f543c-8540-46ed-82f0-8b1fbd475da6" node-type="media" data-type="file" data-width="433" title="Attachment">

![assigning-cues.png](Recording%20Audio_assets/6a88a8117355c51657f60d572e3ede697d867aec.png)

</div>

</div>

 

### To copy the main mix to a Cue:

1.  In the Mixer, right-click on an audio, Instrument, or bus track’s volume fader or pan knob.
2.  Select the Cue to which you want to copy the main mix. 

<div layout="align-start" node-type="mediaSingle" data-width="41">

<div class="wysiwyg-text-align-center" collection="contentId-225739665" context-id="225739665" file-mime-type="image/png" file-name="copy-mix-to-cue.png" file-size="246776" data-height="398" data-id="ccc804cd-36ae-4106-85db-6cf15f093a85" node-type="media" data-type="file" data-width="288" title="Attachment">

![copy-mix-to-cue.png](Recording%20Audio_assets/d0e33d317388bad065b25498233e71ad1d6d1e2c.png)

</div>

</div>

 

Levels and panning for all track faders are copied to the selected Cue.

 

<span class="wysiwyg-font-size-small">260115</span>

