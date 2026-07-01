---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/44409566769684-Creating-Tracks.html'
converted_at: 2026-05-31T13:45:00Z
tool: htmlq+pandoc
title: 'Creating Tracks'
word_count: 2748
---

# Creating Tracks


## In this article

- [About LUNA Tracks](#h_01KCMF08801ZQYDA6F21RSZ1G5)
- [Creating Audio Tracks](#h_01HD2NTANYNEJ588ZSQJ99WDV6)
- [Creating Instrument Tracks](#h_01HG9KH07CASKQ6MNCJRNHDH76)
- [Creating and Routing Bus Tracks](#h_01HD2NTANY4015F021ATWG1YFE)
- [Using the Main track](#h_01HD2NTANY9G8KKKDFZE4EXHYM)

------------------------------------------------------------------------

# About LUNA Tracks

A LUNA session consists of tracks. A track contains audio or MIDI information, and audio and MIDI control automation information. LUNA has four track types:

- On *audio tracks* you can record audio, and add existing audio files such as samples or loops. 
- On *instrument tracks*, you can record MIDI from external controllers or LUNA's internal keyboard, and import or paste MIDI loops or phrases. Instrument tracks can play sound from a UAD Instrument or an instrument plug-in.
- On *bus tracks*, you can sum (mix) audio sources in the session, route audio for Aux-style plug-in processing, and use the Neve and API Summing LUNA Extensions to add punch and warmth to audio sources in your session. 
- On the *main track*, you can mix all the audio, instrument, and bus tracks together to create a stereo mix. The main track is the only default track in a LUNA session.

When you create tracks, you can choose the track type, stereo or mono format, the number of tracks to add, track names, a UAD Instrument or other instrument plug-in (on an instrument track), optional Neve or API Summing (on a bus track), and optional API Vision Console Emulation extensions for all types of tracks. 

When you create a new track, a channel strip is also created. The new track appears in the Tracks browser, the Timeline, and the Mixer.

  ![tracks-timeline.png](Creating%20Tracks_assets/138c17804a4e549c159de4513b3a83a83b5aaa7c.png)

*Tracks in the Timeline*

![tracks-mixer.png](Creating%20Tracks_assets/5127e61fdc98ab84d19e63c2172da6149554fb77.png)

*Tracks in the Mixer*

------------------------------------------------------------------------

# Creating Audio Tracks

You use audio tracks to record audio and to place imported audio files within a LUNA session. Audio is recorded in 24-bit depth at the current audio interface hardware sample rate. LUNA can import WAV, AIFF, AAC, FLAC, ALAC, and MP3 audio that has a valid sample rate, and play it back at the correct pitch. 

## Creating an empty audio track

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 33%;">
![create-new-track.png](Creating%20Tracks_assets/a8a4a7e24ca16469c338f1696cf60c59123a6bba.png)
</figure>

 

#### To create an empty audio track

1.  In the Tracks Focus Browser, select Audio in the Create New Tracks dialog (Track \> New Tracks or Shift+Command+N on macOS, Ctrl+Shift+N on Windows), or click the plus (+) next to Tracks and choose Audio.
2.  Choose the number of tracks to create and the format (MONO or STEREO). You can optionally type a name for the track or tracks here if desired. 
3.  Select a tape machine to assign to the track or tracks, if desired.
4.  If you have optional API Vision Console Emulation, you can select API Vision or API 2500 from the Console row.
5.  Click OK to create the tracks, or Cancel to stop track creation. 

### Track creation tips

- You can open the Create New Tracks dialog by selecting the menu item Track \> New Tracks, or typing Command+Shift+N (macOS) or Ctrl+Shift+N (Windows). 
- You can open multiple Create New Tracks dialogs in the Tracks Focus Browser, allowing you to create multiple types and formats of tracks at the same time.
- If you create multiple tracks, the tracks are created with the name you specify, and a number is appended and incremented for each track. For example, if you create four tracks called Vox, the tracks Vox 1, Vox 2, Vox 3, and Vox 4 are created.
- In the Create New Tracks dialog, press Command+↑ or Command+↓ (macOS) or Ctrl+↑ or Ctrl+↓ (Windows) to cycle through track types.
- In the Create New Tracks dialog, press Command+← or Command+→ (macOS) or Ctrl+← or Ctrl+→ (Windows) to cycle between Mono or Stereo track formats. 
- In the Create New Tracks dialog, press Control+↑ or Control+↓(macOS) or Alt+↑ or Alt+↓ (Windows) to change the number of tracks to create. 

## Creating a new audio track from existing audio

You can create a new track or tracks from one or more existing audio files with either of these methods:

- Drag the audio file(s) directly from the macOS Finder or Windows Explorer to the Tracks Focus Browser, or to the empty area below any existing tracks in the Timeline.
- Drag the audio file(s) to the Tracks Focus Browser or below the Timeline to create one or more new audio tracks containing the files, located at the start of the session.

## Assigning inputs

![input-record-controls.png](Creating%20Tracks_assets/5796e66362216169e5f03d9d2351a39ae45e02ff.png)

 

When you click on the input for a track, the Input Focus Browser opens, from which you can choose the input for the track. The list includes all available inputs in your system. Select an input from the Input Focus Browser. The type of input you select determines the options that appear. For example, a Unison-capable input track (Apollo mode) includes preamp controls.

**Note:** Unison insert and Record FX inserts are available in Apollo Mode only, when a track is record-enabled or input-enabled.

------------------------------------------------------------------------

# Creating Instrument Tracks

You can use instrument tracks to play audio from UAD instruments, a MIDI virtual instrument or a MIDI hardware device such as a synth or sampler. On an instrument track you can:

- Insert UAD instruments or any virtual instrument plug-in into an Instrument track.
- Record MIDI data from an external MIDI device. 
- Import MIDI data.
- Route the MIDI output from an instrument track to an external MIDI device.
- Route the audio from a MIDI device back to the instrument track for monitoring. 
- Edit notes directly in Notes view. 

## Creating an empty instrument track

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 33%;">
![create-new-instrument-track.png](Creating%20Tracks_assets/f111880ac3d13aff39de1d35dd14f81cd59417ca.png)
</figure>

 

#### To create an empty instrument track

1.  In the Tracks Focus Browser, select Instrument in the Create New Tracks dialog, or click the plus (+) next to Tracks and choose Instrument.
2.  Select the number of tracks to create, the format (Mono or Stereo), and an optional name for the track or tracks if desired. 
3.  From the INST drop menu, choose the UAD Instrument, Audio Unit, or VST3 instrument plug-in. Choose None to create a MIDI track or MIDI tracks without instruments.
4.  Select a tape machine to assign to the track or tracks, if desired.
5.  If you have optional API Vision Console Emulation, you can select API Vision or API 2500 from the Console row.
6.  Click OK to create the tracks, or Cancel to stop track creation. 

### Track creation tips

- You can open the Create New Tracks dialog by selecting the menu item Track \> New Tracks, or typing Command+Shift+N (macOS) or Ctrl+Shift+N (Windows). 
- You can open multiple Create New Tracks dialogs in the Tracks Focus Browser, allowing you to create multiple types and formats of tracks at the same time.
- If you create multiple tracks, the tracks are created with the name you specify, and a number is appended and incremented for each track. For example, if you create four tracks called Synth, the tracks Synth 1, Synth 2, Synth 3, and Synth 4 are created.
- In the Create New Tracks dialog, press Command+↑ or Command+↓ (macOS) or Ctrl+↑ or Ctrl+↓ (Windows) to cycle through track types.
- In the Create New Tracks dialog, press Command+← or Command+→ (macOS) or Ctrl+← or Ctrl+→ (Windows) to cycle between Mono or Stereo track formats. 
- In the Create New Tracks dialog, press Control+↑ or Control+↓(macOS) or Alt+↑ or Alt+↓ (Windows) to change the number of tracks to create.

## Creating a new instrument track from existing MIDI

You can create a new MIDI track or tracks from one or more existing MIDI (.mid) files by dragging the file(s) directly from the macOS Finder or Windows Explorer to the Tracks Focus Browser, or to the empty area below any existing tracks in the Timeline.

Dragging MIDI files to the Tracks Focus Browser or below the Timeline creates one or more new instrument tracks containing the MIDI data, located at the start of the session. You can also drag a MIDI clip from a plug-in, the macOS Finder, or Windows Explorer directly onto an existing instrument track.

**Note:** You will be prompted to either use the tempo from the MIDI file, or to adjust the MIDI file to the session tempo. 

![import-tempo-midi.png](Creating%20Tracks_assets/26adb9a6458f5365b857d70b6e26c00d77885af0.png)

------------------------------------------------------------------------

# Creating and Routing Bus Tracks

You can use bus tracks to route audio through the mix system. A bus track can carry more than one signal. Use a bus to submix, or for any purpose that requires the grouping or routing of audio streams. You can create a bus track on its own, and assign sends or outputs to it, or you can select a track or tracks, and automatically assign those tracks when creating the bus.

For more information on mixing with bus sends, see <a href="360041465732-Mixing-in-LUNA.html#sends" target="_self">Using Sends</a>.

Use a bus:

- to combine multiple signals that you want to submix or create "stems" (for example, a submix of the rhythm guitars or background vocals in a session), and to optionally add Neve Summing or API Summing.
- to combine multiple signals to effect with a plug-in (for example, as a reverb bus for several vocal tracks)
- for other mix purposes, such as parallel compression of drums
- to route audio to separate outputs

#### To create a bus track from specific tracks

1.   
    1.  Select the track or tracks which you want to send or route directly to a bus. You can route audio, instrument, and other bus tracks to a bus.

    2.  Type Command+Shift+B (macOS) or Ctrl+Shift+B (Windows), or choose Mixing \> Create Bus from the LUNA menus. The Create Bus dialog opens.

        \
        ![create-bus-dialog.png](Creating%20Tracks_assets/09b7c91b444f689f246869856107c01b05d4317d.png)

    3.  Type a name for the bus.

    4.  In the Route From Selected pulldown, select the track source for the bus. For example, if you want to route the selected track outputs directly to the bus, select Output. To use a send to route the tracks to the bus, select a send.\
        ![create-bus-new.png](Creating%20Tracks_assets/d6d0d5154a8ed2ea929c93c40a26938249d9da66.png)\
         

    5.  To create a bus from a bus preset, select the preset from the Bus Presets list, then click Create.

    6.  If you have an optional API or Neve Summing LUNA Extension, you can select it from the Summing list. You can enable or disable summing after you create the track or tracks.

    7.  If you have optional ATR-102 Master Tape, you can select it from the Tape list, if desired.

    8.  If you have optional API Vision Console Emulation, you can select API 2500 or API Vision from the Console list.

    9.  Click Create. The bus is created, with the routing you specified. 

**Note:** If you assign the bus source to a send that is already in use for the selected tracks, that send assignment is overwritten with the new bus assignment. If you assign the bus source to Output, the selected tracks' outputs are routed to the bus. Note that you can manually route the output of one or more tracks to multiple buses.

#### To create a bus track on its own

1.  In the Tracks browser, click the plus (+) next to Tracks.\
    ![create-track-bus-menu.png](Creating%20Tracks_assets/b9f2f54d09eac2e440db6dfb3da8b4dbf87e2d68.png)\
     
2.  From the Type list, select Bus.\
    ![create-track-bus.png](Creating%20Tracks_assets/40170bdb48222578463bb1be1301c786d267c6aa.png)\
     
3.  Select the number of buses to create and the format (Mono or Stereo), and type a name for the bus or buses.
4.  If you have the optional Neve or API Summing LUNA Extension, you can select it here. You can enable or disable Neve Summing or API Summing after you create the bus or buses.
5.  If you have optional ATR-102 Master Tape, you can select it from the Tape list, if desired.
6.  If you have optional API Vision Console Emulation, you can select API 2500 OR API Vision from the Console row.
7.  Click OK to create the bus or buses.

## Bus inputs and bus routing overview

Once you have created a bus, you can route (send) audio to it. There are two methods for busing: 

- Direct busing routes audio directly to a bus. In this scenario, the bus functions as the track output, and the bus then outputs either to another bus, a pair of outputs, or the Main track. Use output busing to submix to a bus, or to create stem outputs. For example, you can route drums, instruments, and vocals all to separate buses to control levels, adjust effects, and apply Neve Summing, then either route those to the Main track or their own physical outputs.
- Send busing sends audio from the track to a bus, without changing the output of the track. Send busing is useful when you want to effect the audio and mix it back in to the main mix in a controllable way. For example, you can send drums to a compressor on a bus and mix the compressed drums with the main drum tracks (parallel compression), or send instruments and vocals to 100% wet reverb bus, and mix the reverb bus in with the existing tracks.

### To route audio directly to an existing bus

1.  Select the track or tracks you want to route directly to the bus. 
2.  Click Out in the Timeline or the Output in the Mixer or on the Focus channel. The Output Focus Browser opens.\
    ![track-outputs.png](Creating%20Tracks_assets/1014037953da6180196b346910a1ac06e46998fe.png)
3.  Choose the bus to which you want to route the output of the track or tracks.\
    \
    ![outputs-routed-to-bus.png](Creating%20Tracks_assets/96263a106c09876d3f842b1ae03df59f16754332.png)

 

The selected track or tracks are now routed to the bus outputs.The fader and pan controls on the bus track now control overall mix characteristics of the tracks, and you can assign plug-ins and Neve Summing to the bus to affect all source tracks. 

### To route audio to an existing bus using a send

1.  Select the track or tracks you want to send to the bus.
2.  Click an available Send slot in the Mixer or on the Focus channel for a track. The Send Routing Focus Browser opens.\
    \
    ![bus-single-routing-from-send.png](Creating%20Tracks_assets/cd64986f6b6934dbe5db8aba4a539f43ee027b7b.png)
3.  Select the destination bus for the send. Send destinations that you have previously created appear in the Focus Browser under Buses.
4.  The selected track or track sends are now routed to the bus. 

When a send is routed to a single bus, the destination bus name is listed in the Sends mixer row.

![sends-row-single-bus-routing.png](Creating%20Tracks_assets/37ea084fe072a33115db06d1992f6407b2c2c370.png)

 

### To route audio to multiple existing buses using a send

1.  Select the track or tracks you want to send to the bus.
2.  Click an available Send slot in the Mixer or on the Focus channel for a track. The Send Routing Focus Browser opens.
3.  Command-click multiple non-contiguous destination buses to route the audio to those sends. Send destinations that you have previously created appear in the Focus Browser under Buses.\
    \
    ![bus-multiple-routing-from-send.png](Creating%20Tracks_assets/99fcf2704c88188d910abca94d798cc2a5364499.png)
4.  The selected track or track sends are now routed to the selected buses.

When a send is routed to multiple buses, the destination in the Sends mixer row is listed as Multiple.

![sends-row-multiple-routing.png](Creating%20Tracks_assets/00d29dcac060401672370a5e6619cbbfcde8eb3e.png)

## Controlling send audio levels and panning

You can control the send level with the Bus level control. The fader and pan controls on the bus track now control the overall characteristics of the bus track audio, and you can assign plug-ins and Summing to the bus to process the audio from the send. 

## Using Accelerated Realtime Monitoring (ARM) with bus tracks (Apollo Mode only)

When you use Accelerated Realtime Monitoring (ARM), you can configure two bus tracks to work in ARM mode. ARM allows you to use Realtime UAD Processing on these two buses, while monitoring and/or recording with indiscernible latency. 

To set ARM Mode for a bus track, enable ARM, then click the ARM button on the bus track, and select either Aux 1 or Aux 2. When LUNA is in ARM mode, all bus tracks that do not use one of the two ARM-enabled aux buses will incur some latency when processing audio.

------------------------------------------------------------------------

# Using the Main track

The Main track is the master fader or stereo output bus channel for your LUNA session. All audio that is routed to Main runs through this bus, and is summed for listening and mixdown purposes. By default, all audio, instrument, and bus tracks are routed to the Main track.

You cannot delete the Main track, and you cannot create a new Main track. However, you can route audio to other outputs instead of the Main track.

The Main track is where you assign your master track Insert plug-ins. You can also enable Neve Summing or API Summing, and ATR-102 Master Tape on the Main track.

 

<span class="wysiwyg-font-size-small">251216</span>

