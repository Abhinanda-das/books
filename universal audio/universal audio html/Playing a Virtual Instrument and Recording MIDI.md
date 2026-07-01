---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041441532-Playing-a-Virtual-Instrument-and-Recording-MIDI.html'
converted_at: 2026-05-31T13:44:53Z
tool: htmlq+pandoc
title: 'Playing a Virtual Instrument and Recording MIDI'
word_count: 2841
---

# Playing a Virtual Instrument and Recording MIDI


## In this article

- <a href="#h_cb224b11-7a90-4bb3-bf26-388b3409c871" target="_self">Instrument Track Overview</a>
- <a href="#h_3efc6478-05b5-4e8a-ab11-cc73dfec1df7" target="_self">Creating an Instrument Track</a>
- <a href="#h_bbcac4c1-094a-450d-85ab-780d9be7e0fc" target="_self">Choosing a MIDI Controller</a>
- <a href="#h_10d8bb6a-a5e7-4cc7-87b2-338c309e52f6" target="_self">Recording on an Instrument Track</a>
- <a href="#h_787be9ac-986e-4c6e-a343-b8969e2b26f1" target="_self">Playing Back Audio from an External MIDI Instrument</a>
- <a href="#h_24269f72-9a7a-4846-b9c9-40270c32d20f" target="_self">Overdubbing and Looping on an Instrument Track</a>
- <a href="#h_6dc782e8-2e30-4b24-b1c7-5b19368b0be1" target="_self">Loop Recording MIDI</a>

 

------------------------------------------------------------------------

 

# Instrument Track Overview

An instrument track can combine a UAD Instrument, Audio Unit, or VST3 instrument plug-in, and MIDI data. You can record MIDI on an instrument track with or without an instrument plug-in.LUNA uses a MIDI resolution of 960 pulses-per-quarter note (PPQ or PPQN).

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div class="wysiwyg-text-align-center" collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="midi-track-assignments.png" file-size="56723" data-height="232" data-id="bba341b5-45ef-4bb5-9b27-7b8e3c685e20" node-type="media" data-type="file" data-width="397" title="Attachment">

![midi-track-assignments.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/b73b55eac91333107002cbade6e4c5f58a497fa5.png)

</div>

</div>

 

------------------------------------------------------------------------

# Creating an Instrument Track

You record MIDI data, instantiate UAD Instruments, and use other instrument plug-ins on an instrument track. 

## To create an instrument track

1.  In the Tracks browser, click the plus (+) next to Tracks and choose Instrument from the contextual menu. If the Create New Tracks dialog is already open, choose Instrument from the Type drop menu.

2.  Type the number of tracks to create, choose the format (Mono or Stereo), and type a name for the track or tracks.

3.  From the INST drop menu, choose a UAD instrument, an Audio Unit or VST3 instrument plug-in, or choose None to record MIDI alone or to use an external MIDI instrument.

4.  To use tape on this track, select a tape machine from the Tape list. 

5.  To use the optional API Vision Console on this track, select API Vision or API 2500 from the Console list.

6.  Click OK to create the tracks, or Cancel to stop track creation. 

------------------------------------------------------------------------

# Choosing a MIDI Controller

LUNA can accept MIDI input from any MIDI devices recognized by your system. If you have multiple MIDI devices, you can choose which MIDI input the instrument track uses.

On an instrument track in the Mixer or on an instrument track Focused in the Timeline, click the MIDI In row, and choose the MIDI Input to use for the instrument. Press Esc or click the close button to close the MIDI In browser.

**Note:** A track that is Input enabled responds to an assigned MIDI controller only when the track is selected. However, record-enabled tracks respond to assigned MIDI controllers when the tracks are not selected.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="midi-in-selecting.png" file-size="107745" data-height="420" data-id="5cba6c8b-e65f-4726-a2ce-478b851604dd" node-type="media" data-type="file" data-width="419" title="Attachment">

![midi-in-selecting.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/3ccae0400bcc2752127384b91579446be75f0f17.png)

</div>

</div>

## Using MIDI Keyboard Mode to input MIDI

If you don't have an external MIDI controller, or you prefer to use the computer keyboard to input MIDI notes, you can use MIDI Keyboard Mode. MIDI Keyboard Mode maps MIDI notes (1-⅓ octave from C to E) to keys on the computer keyboard, which you can use to perform MIDI recording. 

When you enable MIDI Keyboard Mode, you can enter MIDI notes when monitoring or recording by pressing keys on the computer keyboard. MIDI Keyboard Mode provides the ability to change the octave of the keyboard and to set a velocity level for MIDI notes you input with the computer keyboard. 

**Note:** Any single-key commands that use one of the notes on the MIDI keyboard will not work when MIDI Keyboard Mode is enabled. For example, "E" (Frame Selection) and "F" (Create a Fade) are not supported when MIDI Keyboard Mode is enabled. When available, use the modifier-key version of such a key command (for example, Command+F / Ctrl+F to create a fade). There is no modifier key for the "E" command.

### To enable or disable MIDI Keyboard Mode

- Press Option+Command+M (macOS) / Ctrl+Alt+M (Windows), or 
- Choose View \> MIDI Keyboard Mode, or
- Click the MIDI icon under Workflows at the top of the screen to enable the MIDI Workflow, then toggle MIDI Keyboard Mode (for more information about workflows, see <a href="360041440592-Using-LUNA.html#using-workflows" target="_self">Using Workflows</a>).

 

<div layout="align-start" node-type="mediaSingle" data-width="25">

<div class="wysiwyg-text-align-center" collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="workflows-switch-midi.png" file-size="8528" data-height="103" data-id="bf9af3d0-4f20-46ac-bd88-153e607e9418" node-type="media" data-type="file" data-width="90" title="Attachment">

![workflows-switch-midi.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/80c2ccd816cccfbd93c7e08212615d2184c5e9a8.png)

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="workflows-switch-midi.png" file-size="8528" data-height="103" data-id="bf9af3d0-4f20-46ac-bd88-153e607e9418" node-type="media" data-type="file" data-width="90" title="Attachment">

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="workflows-switch-midi.png" file-size="8528" data-height="103" data-id="bf9af3d0-4f20-46ac-bd88-153e607e9418" node-type="media" data-type="file" data-width="90" title="Attachment">

</div>

<div class="wysiwyg-text-align-center" collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="workflows-switch-midi.png" file-size="8528" data-height="103" data-id="bf9af3d0-4f20-46ac-bd88-153e607e9418" node-type="media" data-type="file" data-width="90" title="Attachment">

![midi-keyboard-mode.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/5299f1a301af674dccd4f6639cfa6c721e2f510d.png)

</div>

</div>

<div layout="align-start" node-type="mediaSingle" data-width="90">

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="midi-keyboard-mode.png" file-size="48801" data-height="155" data-id="831ceb74-5566-4e4b-9a8e-7202a52b59be" node-type="media" data-type="file" data-width="613" title="Attachment">

</div>

</div>

### To play notes with MIDI Keyboard Mode

- Press the keys as indicated in the MIDI Keyboard map in the workflow bar at the top of the screen.
- To change the octave over which the keys send MIDI notes, press Z on the computer keyboard to lower the range one octave. Press X to raise the range one octave. You can also click the Up and Down arrows under Octave in the Workflow area at the top of the screen.
- To set the MIDI Note velocity that each key press sends, press C on the computer keyboard to decrease the velocity, or D to increase the velocity, or click the Up and Down arrows under Velocity in the Workflow area at the top of the screen.

## MIDI Merge or MIDI Replace

Before you record, decide whether you want to use MIDI Merge or MIDI Replace. 

- **MIDI Merge (Transport \> MIDI Merge):** The MIDI notes you play are combined with the existing notes over which you record. MIDI Merge is useful if you want to build up a track like a drum part by playing in separate drums on successive record passes.

- **MIDI Replace (Transport \> MIDI Merge):** The MIDI notes you play replace those in the selection over which you record. MIDI Replace is useful when you want to correct a part, or play a part differently, without keeping the previous part.

------------------------------------------------------------------------

# Recording on an Instrument Track

When you record on an instrument track in Apollo mode on macOS, ARM mode sets the system to get a faster response from UAD instruments or third-party Audio Unit or VST3 instruments. In Windows, ARM mode does not do this, so set your buffer size to the smallest size that balances performance and feel. If you use UAD-2 plug-ins to process audio on the instrument track or on a bus, you should enable ARM mode to get the lowest possible latency. In ARM mode, any non-UAD-2 Audio Unit or VST3 insert effect plug-ins on a record-enabled track are disabled.

## To record on an instrument track

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  In the Tracks browser, click the plus (**+**) next to Tracks and choose Instrument. If the Create New Tracks dialog is open, from the Type drop menu, choose Instrument.

2.  Type the number of tracks to create, choose the format (Mono or Stereo), and type a name for the track or tracks.

3.  From the INST drop menu, choose a UAD instrument, an Audio Unit/VST3 instrument plug-in, or None to record MIDI alone.

4.  Click OK to create the tracks, or Cancel to stop track creation. 

5.  In the Focus channel or Mixer, click the Input mixer row. The Input browser opens.

6.  Choose the MIDI input to which your controller is connected. MIDI devices recognized in by the macOS Audio MIDI Setup app or the Windows OS are available here. You can also play and record MIDI notes using the computer keyboard. Select View \> MIDI Keyboard Mode from the menus, or press Option+Command+M (macOS) / Alt+Ctrl+M to use the computer keyboard to input MIDI notes.

7.  Click the Input enable button (Shift+T) or click the Record enable button (Shift+R) on the track or Focus channel (Timeline view) or on the channel (Mixer view). Input-enabling a track allows you to monitor the Instrument or audio source when the Instrument, plug-in, or device is triggered with the MIDI Input source. Record-enabling a track allows you to record MIDI data to the Instrument track, when you click Record. \
    **Note:** If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.\
    \
    \
    ![record-input-enable.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/201203f5db123b3b97b7dcc3b2247b16930f9077.png)\
     

8.  If you are using UAD plug-ins in the Record FX or standard inserts on the instrument track, enable ARM mode for the lowest possible latency.

9.  Choose whether to use <a href="#h_c062522f-a221-45ff-9006-1a0de3666b13" target="_self">MIDI Merge or MIDI Replace</a>.

10. Click Record on the transport or Command+Spacebar (macOS) / Ctrl+Spacebar (Windows) to record MIDI.

11. Click Stop or press the Spacebar to stop recording.

</div>

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="recording-midi.png" file-size="43635" data-height="161" data-id="d58fcba0-28a5-49a1-b597-c5c07f9e2fae" node-type="media" data-type="file" data-width="532" title="Attachment">

 

</div>

</div>

------------------------------------------------------------------------

# Playing Back Audio From an External MIDI Instrument

You can record MIDI from an external MIDI instrument, while monitoring the audio from that device or another device. By sending the MIDI output from an instrument track to an external MIDI hardware device, for example a synth or a drum module, you can monitor or record the audio from this device on an available audio input. 

## To trigger and record MIDI and monitor or record audio from a MIDI sound generator

You can send MIDI data from an instrument track to an external MIDI device, and monitor or record the audio output from that device on a separate audio track. Use this to record a synth or sound module to an audio track, while retaining the ability to edit the original MIDI performance data. 

First, create a mono or stereo audio track, and connect the synth or sound module to a hardware input or stereo input pair.

1.  In the Tracks browser, Timeline, or Mixer, select the instrument track on which you have recorded MIDI. 
2.  In the Mixer channel or Focus channel for the track, click the MIDI Out mixer row. The MIDI Out browser opens.
3.  Choose the MIDI Output to which you want to send MIDI data. MIDI devices recognized in the macOS Audio MIDI Setup app or by the Windows OS are available here, as are all instrument tracks in your session. Choose the MIDI device that you have connected as the audio generator.
4.  On the audio track, click on the Input slot, then from the Input browser, choose the hardware input or stereo input pair to which the device is connected.
5.  Press the Input-enable button (Shift+T) to monitor the audio source when the instrument is triggered with the MIDI output.
6.  Press the Record-enable button (Shift+R) on the instrument track to record MIDI data. Press the Record-enable button (Shift+R) on the audio track to enable audio recording.\
    **Note:** If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.
7.  If you are using UAD plug-ins in the Record FX or standard inserts on the instrument track, enable ARM mode for the lowest possible latency.
8.  Select the range you want to record, or place the playhead where you want to start recording. 
9.  Press Record or Command + Spacebar (macOS) / Ctrl+Spacebar (Windows). 

Audio generated by the synth or sound module is recorded to the audio track and the MIDI source data is recorded to the instrument track.

**Note:** If the external MIDI controller is the same device as the MIDI sound generator (if it's a MIDI keyboard controller with built-in sounds), be sure to disable the MIDI keyboard's "MIDI Local Control" setting to prevent doubled MIDI notes. 

## Playing back an instrument track

Place the playhead or make a selection, and press Play on the transport, or press the Spacebar.

MIDI notes, program changes, and continuous controllers (CCs) are played from the playhead, even if the playhead starts after the MIDI events occur. Like audio and track automation, MIDI data values at the current play position are played correctly. This type of MIDI playback is called MIDI Chase, Note Chasing, or MIDI Note Chasing.

------------------------------------------------------------------------

# Overdubbing and Looping on an Instrument Track

You can overdub directly on a MIDI clip, starting wherever you place the playhead, or in a range that you select. You also have the option to loop record, which creates separate Versions (which are labeled as Takes when loop recording) for each complete loop recording pass.

Before you record, decide whether you want to use <a href="#h_c062522f-a221-45ff-9006-1a0de3666b13" target="_self">MIDI Merge or MIDI Replace</a>.

- **MIDI Merge (Transport \> MIDI Merge):** The MIDI notes you play are combined with the existing notes over which you record. MIDI Merge is useful if you want to build up a track like a drum part by playing in separate drums on successive record passes.

- **MIDI Replace (Transport \> MIDI Merge):** The MIDI notes you play replace those in the selection over which you record. MIDI Replace is useful when you want to correct a part, or play a part differently, without keeping the previous part.

## To record over existing MIDI without a selection

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Click within the track or in a ruler above the tracks to place the playhead where you want to start recording.\
    \
    ![midi-record-cursor.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/8206929d9ab6d728aa99599ef4244eb1c82c9e56.png)\
     
2.  To use Pre-roll (listen to the existing track for a specified period of time before you start recording), Option+click to the left of the playhead on the Bars and Beats ruler.\
    \
    ![qs-option-click-pre-roll.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/2681847a0d39857736125cc8bcd08e3798f10c2a.png)\
     
3.  Record-enable the MIDI track.\
    **Note:** If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.
4.  Press Record and begin playing. MIDI records from the playhead. If you set a pre-roll amount, the system plays the pre-roll section before recording starts.
5.  Click Stop or press the Spacebar to stop recording.

 

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![midi-overdub-merge.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/3f9d926b094c664649fe5649679a96ff35f600db.png) </span>

 

</div>

## To record over a MIDI selection

1.  Hovering the cursor over the bottom solid-colored border of the audio clip, click and drag to make a selection. The selection snaps to the grid, if Snap is enabled.\
    \
    ![midi-selection.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/8f79319d5536c186ebf8cd44734874a50df56b56.png)
2.  To use Pre-roll (listen to the existing track for a specified period of time before you start recording) Option+Click to the left of the playhead on the Bars and Beats ruler. To set post-roll, Option+Click to the right of the selection on the Bars and Beats ruler.\
    ![qs-option-click-pre-roll.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/2681847a0d39857736125cc8bcd08e3798f10c2a.png)\
     
3.  Record-enable the track.\
    **Note:** If you do not record-enable one or more tracks, any selected tracks are recorded when you start recording.
4.  Press Record and play your MIDI controller or the computer keyboard. MIDI records from the start of the selection, and stops recording at the end of the selection. If you set a pre-roll amount, the system plays the pre-roll selection before recording starts. If you set a post-roll amount, the system plays the post-roll selection after recording completes.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="midi-loop-recording.png" file-size="12509" data-height="108" data-id="b09a74c8-4740-41ad-a954-066eddf4a1ae" node-type="media" data-type="file" data-width="354" title="Attachment">

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="midi-loop-recording.png" file-size="12509" data-height="108" data-id="b09a74c8-4740-41ad-a954-066eddf4a1ae" node-type="media" data-type="file" data-width="354" title="Attachment">

![midi-loop-recording.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/d42bc1b4a8508b45764581fa00294c2c0ae289cb.png)

</div>

</div>

 

The MIDI you record is either merged with the existing MIDI, or replaces it, depending on whether MIDI Merge is enabled.

------------------------------------------------------------------------

# Loop Recording MIDI

When you loop record, you either replace a section of a track that you select with one or more recorded takes, or you record multiple merged passes. When LUNA reaches the end of the selection, the transport returns back to the start of the selection, and records again. Each complete record pass is saved as a Take. To show recorded Takes, click the Versions button at the top of the Tracks area.

On a MIDI track, takes are separate from track versions. You can switch between Takes of one clip, and the selected track version and any other clips associated with it remain. 

## To loop record (with MIDI Merge)

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Select Transport \> MIDI Merge.
2.  Make a MIDI selection and click the Loop Play / Record button.\
    \
    ![transport-loop-enabled.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/81916c20a09e55f39c69d566bb5bc1c5134f4aa2.png)\
     
3.  Record your source. As the loop plays, you can record additional notes with each pass.\
    \
    ![midi-loop-recording-merge.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/9f6ebb3c70fa6d35a369fb0497667ba697486e62.png)\
     
4.  To switch between Versions or Takes, click the Version or Take. 

</div>

<div layout="align-start" node-type="mediaSingle" data-width="90">

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="qs-midi-versions-takes.png" file-size="50515" data-height="114" data-id="6465cf65-d691-46b6-b1ae-4fb1209684c3" node-type="media" data-type="file" data-width="498" title="Attachment">

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="qs-midi-versions-takes.png" file-size="50515" data-height="114" data-id="6465cf65-d691-46b6-b1ae-4fb1209684c3" node-type="media" data-type="file" data-width="498" title="Attachment">

![qs-versions-takes.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/000eb086419bc31b4ea9a5b3c4d5e2ac6e822c51.png)

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="qs-midi-versions-takes.png" file-size="50515" data-height="114" data-id="6465cf65-d691-46b6-b1ae-4fb1209684c3" node-type="media" data-type="file" data-width="498" title="Attachment">

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="qs-midi-versions-takes.png" file-size="50515" data-height="114" data-id="6465cf65-d691-46b6-b1ae-4fb1209684c3" node-type="media" data-type="file" data-width="498" title="Attachment">

</div>

</div>

## To loop record (with MIDI Replace)

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Deselect Transport \> MIDI Merge.
2.  Make a MIDI selection and click the Loop Play / Record button.\
    \
    ![transport-loop-enabled.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/81916c20a09e55f39c69d566bb5bc1c5134f4aa2.png)
3.  Record your source. As the loop plays, you replace the previous recording with each pass.\
    \
    ![midi-loop-record-no-merge.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/f61c81656a566e8ec01168c1aa08bf45df69b8ca.png)\
     
4.  To switch between Versions and Takes, click the Version or Take.

</div>

<div layout="align-start" node-type="mediaSingle" data-width="80">

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="qs-midi-versions-takes.png" file-size="50515" data-height="114" data-id="6465cf65-d691-46b6-b1ae-4fb1209684c3" node-type="media" data-type="file" data-width="498" title="Attachment">

</div>

<div collection="contentId-194707780" context-id="194707780" file-mime-type="image/png" file-name="qs-midi-versions-takes.png" file-size="50515" data-height="114" data-id="6465cf65-d691-46b6-b1ae-4fb1209684c3" node-type="media" data-type="file" data-width="498" title="Attachment">

![qs-versions-takes.png](Playing%20a%20Virtual%20Instrument%20and%20Recording%20MIDI_assets/000eb086419bc31b4ea9a5b3c4d5e2ac6e822c51.png)

</div>

</div>

 

<span class="wysiwyg-font-size-small">251219</span>

