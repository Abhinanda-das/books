---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041866251-LUNA-Concepts.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'LUNA Concepts'
word_count: 3927
---

# LUNA Concepts


LUNA Recording System is the music production system from Universal Audio. LUNA is the most inspiring recording system on the planet, providing a complete environment for recording, MIDI creation, editing, arranging, and mixing – all with an intuitive and contextual user interface.

This article includes:

- [Natural Analog Workflow](#h_a27138db-5351-465b-8575-ffe983d1aa02)
- [Apollo, Core Audio, or ASIO Modes](#Apollo-Integration)
- [Accelerated Realtime Monitoring (Apollo Mode)](#Accelerated-Realtime-Monitoring)
- [Recording Features](#Recording-Features)
- [LUNA and UAD Console (Apollo Mode)](#LUNA-and-Console)
- [LUNA Extensions](#LUNA-Extensions)
- [UAD Instruments](#LUNA-Instruments)
- [Non-Destructive Audio](#Non-Destructive-Audio)
- [How Do I Save?](#How-do-I-Save?)
- [Undo and Redo](#Undo-and-Redo)
- [Supported Plug-In Formats](#Supported-Plug-In-Formats)
- [Tempo Modes](#h_01JS589QBD7AHPT0B1RF3M0ECA)
- [Sample Rates, Imported Audio, and Imported Sessions](#Sample-Rates,-Imported-Audio,-and-Imported-Sessions)
- [Focus Browsers Overview](#Focus-Browsers-Overview)
- [Workflows](#Workflows)
- [Keyboard Shortcuts and Menu Reference](#Keyboard-Shortcuts-and-Menu-Reference)

------------------------------------------------------------------------

# Natural Analog Workflow

LUNA (in Apollo mode) is based on a powerful hardware-software integration, giving Apollo interface owners the fastest, most natural recording system for music creation, editing, and mixing. No more toggling between UAD Console and your DAW to track through UAD plug-ins in real time.

Instead, LUNA's Accelerated Realtime Monitoring™ lets you record through UAD plug-ins with no discernible latency, and eliminates hassles in creating monitor mixes, cue mixes, setting up Unison plug-ins, and so much more.

------------------------------------------------------------------------

# Apollo, Core Audio, or ASIO Modes

LUNA operates in Apollo, Core Audio, or ASIO modes.

## Apollo mode

in **Apollo mode** , LUNA is integrated directly with Universal Audio interface hardware. When a Thunderbolt-equipped Apollo is connected and powered on, you can set LUNA to Apollo mode. Tight integration with UA hardware means that much of the complexity of audio interface configuration is removed with LUNA. All of your available hardware inputs and outputs are automatically configured and available in LUNA. In addition, all preamp channel features and Unison inserts are automatically available in LUNA, and most routing features of the hardware, including Cues and routing matrix features, are available.

If you have an Apollo connected, LUNA automatically starts in Apollo mode.

## Core Audio mode

**Tip:** Core Audio mode is labeled as VOLT mode if you have a Universal Audio Volt interface connected.

In **Core Audio mode** on a Mac, you can use LUNA with supported Core Audio devices. LUNA can support multiple Core Audio devices at once. All of your available hardware inputs and outputs for enabled devices are automatically configured and available in LUNA, though you may have to make adjustments in the hardware setup panel. In Core Audio mode, Unison plug-ins are not supported on LUNA inputs, though you can use Unison inputs in UAD Console if you use an Apollo interface.

If you do not have an Apollo connected, LUNA automatically starts in Core Audio mode on a Mac.

### To switch between Apollo mode and Core Audio mode

- At the bottom left of the LUNA screen, click on the info area to open the Audio Settings popover, and choose Apollo or Core Audio.

<figure class="wysiwyg-image">
![select-apollo-core-audio-in-luna.png](LUNA%20Concepts_assets/4de7d1585bf9cb139c0215f3a516e9d6f4ff600e.png)
</figure>

## ASIO Mode

In **ASIO mode** , you can use LUNA with a supported ASIO device. Your available hardware inputs and outputs are automatically configured and available in LUNA, though you may have to make adjustments in the hardware setup panel. In ASIO mode, Unison plug-ins are not supported on LUNA inputs, though you can use Unison inputs in UAD Console if you use an Apollo interface.

If you do not have an Apollo connected, LUNA automatically starts in ASIO mode.

### To switch between Apollo mode and ASIO mode

- At the bottom left of the LUNA screen, click on the info area to open the Audio Settings popover, and choose Apollo or ASIO.

<figure class="wysiwyg-image">
![apollo-asio-choose.png](LUNA%20Concepts_assets/8d1b865f6751358688cc1e9019b83afa4b357a14.png)
</figure>

------------------------------------------------------------------------

# Accelerated Realtime Monitoring (Apollo Mode)

Accelerated Realtime Monitoring™ (ARM) is a deep hardware, DSP, and software integration feature inside LUNA that allows you to achieve the lowest possible latency while recording with UAD plug-ins in real time.

**Note:** Accelerated Realtime Monitoring is available only in Apollo mode. You cannot use Accelerated Realtime Monitoring in Core Audio or ASIO modes.

Accelerated Realtime Monitoring™ (ARM) eliminates the need to use the UAD Console to track and input monitor through UAD plug-ins at the lowest possible latency. Accelerated Realtime Monitoring offers you the ability to effortlessly achieve the lowest possible latency while recording with Apollo. Accelerated Realtime Monitoring seamlessly handles channel input states, allowing for the use of UAD plug-ins on channel inserts for Realtime UAD Processing, without having to leave the LUNA workspace. ARM offers UAD plug-in processing at undetectable latencies while monitoring and/or recording multiple inputs and tracks.

LUNA takes care of the muting of input channels, based on what is in use in the session. Apollo channels that are record-enabled have their inputs unmuted, and all other channels have their inputs muted. Apollo integration automatically controls the muting of inputs and recorded material on disk according to the record enable or input enable and transport state.

For a detailed description of Accelerated Realtime Monitoring, see <a href="360041440692-Accelerated-Realtime-Monitoring-ARM-in-Apollo-Mode.html" target="_self">Accelerated Realtime Monitoring</a> .

You can enable Accelerated Realtime Monitoring globally. Use this setting to achieve the lowest possible input monitoring latency when monitoring input signals through monitor, headphone, and cue outputs.

------------------------------------------------------------------------

# Recording Features

LUNA’s recording engine is fast and highly capable. LUNA records 24-bit audio at the current hardware sample rate, on as many tracks as your computer can support. With LUNA, you can switch the transport in and out of Record while playing audio. You can also enable and disable recording on tracks while the transport is running, so you can punch in manually on one or more tracks while playing back a session. All audio and MIDI tracks, buses, the main output, and hardware outputs are delay-compensated on playback, so everything stays tightly synchronized.

## Plug-in processing (Apollo mode only)

Previously, with UAD Console, you had to choose whether or not to record insert effects on input channels. In LUNA, as with the UAD Console, Unison insert processing is always recorded to disk. However, unlike the UAD Console, each input channel has four available Record FX slots in addition to eight standard inserts (used for any combination of Audio Unit or UAD plug-ins). These inserts allow you to record through up to four UAD plug-ins on any available input channel (depending on available UAD DSP resources). In addition, UAD and non-UAD plug-ins can be assigned to standard Inserts (not recorded to disk) for monitoring while you record, without being recorded to disk.

### Notes on plug-in processing:

- Only UAD plug-ins can be monitored on a record-enabled track when Accelerated Realtime Monitoring is enabled. When you enable ARM, any Audio Unit or VST3 plug-ins on a record or input-enabled track are disabled.
- UADx plug-ins that have UAD-2 equivalents convert automatically to UAD plug-ins when tracks or buses that require UAD processing are put into ARM mode. So, for example, in ARM mode, if your vocal track feeds an ARM-enabled bus with a UADx Pure Plate Reverb inserted, and you record-enable that vocal track, the UADX Pure Plate Reverb is switched out for the UAD-2 Pure Plate Reverb (if you have the plug-in).
- When you add an Audio Unit or VST3 plug-in to a record or input-enabled track when ARM is enabled, the plug-in is added in an inactive state, and LUNA displays a notification that the plug-in is disabled.\
  ![add-au-insert-arm.png](LUNA%20Concepts_assets/f43f4f10fcb4ecdd7e8bfb5b14dac1f2b6d8561a.png)
- When a track is record or input-enabled in ARM mode, the last four standard inserts are disabled.

------------------------------------------------------------------------

# LUNA and UAD Console (Apollo Mode)

You never need to use UAD Console when you are using LUNA in Apollo mode. LUNA replaces almost all functions for which you previously used UAD Console. LUNA also includes a number of features that UAD Console does not.

For example, a LUNA session includes persistent inputs. When you configure a LUNA track with an input, all settings, including Unison plug-ins, Record FX plug-ins, and Insert effect plug-ins, are retained on that track. You can reuse the same input on your Apollo on multiple tracks, and each track in the session will continue to retain the settings that were last used for it, even after you close and reopen the session.

If you prefer to use UAD Console, the settings you configure in UAD Console are removed when LUNA starts, and restored after you quit LUNA. Note that the Isolate and Flex Routing features are configured in UAD Console.

## Console Isolate feature

Isolate retains current channel settings when different UAD Console and LUNA sessions are loaded. Isolated channels are also not controlled by LUNA. Isolate allows you to seamlessly monitor live hardware inputs with Realtime UAD Processing, even when changing UAD Console and LUNA sessions. You can use this to prevent a UAD Console channel’s state from changing across LUNA sessions. When a channel or channel pair is Isolated the plug-ins on that channel cannot be changed in LUNA, and the channel input pair is not automatically muted and unmuted by the LUNA mixer—the channel or channel pair is always live.

The only exception to this is that an Isolated input or input pair is muted when a track that uses that input is record-enabled and LUNA is playing back audio from that track.

## Console Tracking Mode

Console Tracking Mode allows you to use UAD Console for live channel inputs, and prevents LUNA from automatically muting and unmuting UAD Console channels when recording. Essentially, all inputs remain live, and UAD Console works as it previously did, while LUNA is running.

In Console Tracking Mode, UAD plug‑ins do not persist in LUNA inputs as they normally do. Instead, when you record-enable a track in Console Tracking mode, the plug-ins assigned to the track in UAD Console are loaded into the LUNA channel. However, unlike with Isolated Console channels, in Console Tracking Mode, you can change the plug-ins assigned to the track in LUNA, and those changes will carry over to UAD Console. UAD Console channels then return to their previous states after you quit LUNA.

**Note:** A Console input is muted when ARM is enabled, a track that uses that input is Record-enabled, and LUNA is playing back audio from that track.

For more information about Console Tracking Mode, see <a href="360041441112-Recording-Audio.html#using-console-tracking-mode" target="_self">Using Console Tracking Mode</a> .

------------------------------------------------------------------------

 

# LUNA Extensions

LUNA Extensions are UA add-ons that run exclusively inside LUNA. LUNA includes the free Oxide Tape LUNA Extension. The optional API Vision Console, Studer A800, Ampex ATR-102, API Summing, and Neve Summing LUNA Extensions are available for purchase from within LUNA. The included free ARP LUNA Extension provides arpeggiation effects on Instrument tracks.

## Integrated Multitrack Tape

LUNA's Multitrack Tape sounds, courtesy of the included Oxide LUNA Extension and optional Studer A800 Extension, give you the rich warmth, punch, and texture of magnetic tape on any audio or instrument track. Simply adjust the per-track Saturation control to dial up the desired amount of harmonics and tape character on your sources.

You can even mix-and-match up to four tape machines total, harnessing different tape formulas, tape speeds, and per-track controls for Bias, Repro, and Tone. It's a tape-head's delight — perfect for gluing together your mixes.

<figure class="wysiwyg-image">
![tape-channel-expanded-alt.png](LUNA%20Concepts_assets/3f9102e2726fecb798b18ca64400c96fe1b5986e.png)
</figure>

## Integrated Master Tape

LUNA’s Master Tape sounds are provided by the Ampex ATR-102 Extension, which can be applied on bus tracks and on the Main track. Master Tape allows you to configure separate machines with different presets or settings on each bus and the main track, allowing deep flexibility in the mixing stage. You can set the tape machine as pre or post-fader, configure tape speed, tape head width, and tape formula directly on each bus track and on the main track. From the tape browser, you can configure the record and reproduce level, and configure bias settings, EQ, and enable noise.

<figure class="wysiwyg-image">
![master-tape-action-alt.png](LUNA%20Concepts_assets/5fc0a20e8b3e63758cf638a1155f65fe572ae7d3.png)
</figure>

## Console Summing

LUNA includes optional Neve® Summing and API Summing LUNA Extensions. These extensions impart the sound and feel of meticulously modeled consoles into the fabric of the LUNA mixer, on bus tracks and the Main track. Console Summing LUNA Extensions change the behavior and appearance of the LUNA buses and Main track to display accurate fader tapers. When you route tracks to a bus with a summing model enabled, the fader tapers of the bus or Main track and the source tracks change.

<figure class="wysiwyg-image">
![summing-bus-source-track-taper.png](LUNA%20Concepts_assets/078f75ed3b8b9413a79ea7efe391780340b7effc.png)
</figure>

### Built-in Neve® Summing

A major ingredient behind thousands of influential, chart-topping records, Neve 80 series consoles are without equal. These classic analog desks from the '60s and early '70s — made famous in the Sound City documentary — deliver three-dimensional nonlinearities and analog heft that infuses your mixes with vibrancy and color.

Developed in partnership with AMS Neve exclusively for LUNA Recording System, the Neve Summing Extension emulates the entire summing circuit of an iconic Neve 80 series console — including its coveted 1272 bus amplifiers — giving your LUNA mixes all the color of Neve's most cherished analog desk.

![neve-summing.png](LUNA%20Concepts_assets/ee701184de8938b6615eac8aa04cf0d259ee1861.png)

### Built-in API Summing

The sound behind five decades of landmark albums, API consoles are legend for good reason. From Stevie Wonder's *Talking Book* and Fleetwood Mac's *Rumours* , to The Cure's *Pornography* and Radiohead's *Hail to the Thief* — the mid-forward punch of API's classic analog consoles breathe aggressive, multi-dimensional color into your mixes.

Developed in partnership with API, exclusively for LUNA Recording System, the API Summing Extension emulates the 2520 op-amp and custom output transformers found in legendary API consoles over the past 50 years — giving your LUNA mixes all the attitude and tone of API's esteemed analog desks.

![api-summing-overview.png](LUNA%20Concepts_assets/5d174c91f16c2f1c451416eb4d4c11e8aaae53f4.png)

## API Vision Console Emulation

The API Vision Console Emulation Bundle turns LUNA into a full API console. Track in real time through API preamp and channel modules (in Apollo mode only), then mix with API's illustrious analog summing and bus compression — seamlessly switching between low-latency tracking using Apollo DSP (Apollo mode only), and high-powered native mixing within LUNA. You can create new audio, instrument, and bus tracks with API Vision Console elements pre-assigned, building sessions within the complete Vision console emulation experience.

![api-vision-console-overview.png](LUNA%20Concepts_assets/4d98a52e9d592465548b33cd13ca269221d09eee.png)

## About LUNA Extensions documentation

- Learn how to use the LUNA Tape Extensions at <a href="360041465732-Mixing-in-LUNA.html#using-tape" target="_self">Using Tape LUNA Extensions</a>.
- Learn how to use Neve and API Summing Extensions at <a href="360041465732-Mixing-in-LUNA.html#using-summing" target="_self">Using Neve Summing</a> and <a href="360041465732-Mixing-in-LUNA.html#using-api-summing" target="_self">Using API Summing</a>.
- Learn how to use API Vision Console Emulation at <a href="360060691752-LUNA-API-Vision-Console-Extension-Manual.html" target="_self">API Vision Console Emulation</a>.
- Learn how to operate the ARP MIDI Arpeggiator at <a href="360041911811-LUNA-ARP-MIDI-Arpeggiator-Extension-Manual.html" target="_self">ARP MIDI Arpeggiator</a>.
- Learn about LUNA Extensions at <a href="https://help.uaudio.com/hc/en-us/articles/360041911731" target="_self">About LUNA Extensions</a>.

------------------------------------------------------------------------

# UAD Instruments

UAD instruments bring Universal Audio's expertise in electrical and acoustic modeling, sampling, synthesis, and signal processing to instruments for the first time ever.

LUNA Recording System comes with a curated bundle of inspiring sounds, delivering a new level of realism for software-based instruments.

The Shape and Spitfire Audio UAD instruments are exclusive to LUNA Recording System. Other UAD Instruments can be used in LUNA and macOS hosts that support VST3, Audio Units, or AAX plug-ins.

## Shape

A comprehensive creative toolkit included free with LUNA, Shape is a painstakingly curated UAD Instrument featuring a collection of the best vintage keys, drums/percussion, guitar/bass, orchestral content, and real time synthesis - courtesy of Universal Audio, Spitfire Audio, Orange Tree Samples, Loops de la Creme, and more. You can expand Shape with more content and sample packs.

<figure class="wysiwyg-image">
![shape-new.png](LUNA%20Concepts_assets/6abf7e17b734a4cd3274342a1d63f81c6cfceeb4.png)
</figure>

## About UAD instruments documentation

- Learn how to insert, play, and record UAD Instruments in <a href="360041441532-Playing-a-Virtual-Instrument-and-Recording-MIDI.html" target="_self">Playing a Virtual Instrument and Recording MIDI</a>.

- Learn how to operate individual UAD Instrument controls in the separate <a href="360041479012-UAD-Instruments.html" target="_self">UAD Instruments</a> section.

------------------------------------------------------------------------

# Non-Destructive Audio

When you record audio in LUNA, that audio is stored in the session file. You can edit the audio by copying, cutting, trimming, and deleting sections, while not actually deleting the underlying audio file. Similarly, when you record multiple takes of audio with loop recording, or you record audio over an existing audio file or file section, the previous audio files are retained. You can access all whole audio files recorded with loop recording from the Track Versions feature.

------------------------------------------------------------------------

# How Do I Save?

With LUNA, all changes are saved automatically. LUNA writes changes to a database file that is embedded within the LUNA session file. This database is updated with every change and keeps a constant record of your LUNA session. All edits and modifications are automatically saved, and all audio is embedded in the LUNA session file. You can undo and redo changes (except when recording) even after closing and reopening a session.

While there is no traditional Save function in LUNA, you can save session Versions and Bookmarks. Versions and bookmarks have slight differences.

- Creating a version is like saving a new session, without actually creating a new session. A version creates a top-level item in the version history. The name of the currently loaded version appears appended to the session name at the top of the LUNA application. A version can be useful when you are adding elements to a session, changing the arrangement of a session, or otherwise significantly changing the session.
- Bookmarks recall a state oI the session, below a specific version. Bookmarks are created below the latest version, or the currently recalled version. A bookmark can be useful to save separate mixes below a version, or for minor changes in the mix or arrangement. For example, you could make bookmarks under a version for your test mix, a mix with the vocals up and down 3dB, and an instrumental mix.

LUNA also automatically autosaves versions to which you can revert, based on the Autosave Interval in LUNA settings. You can show autosaved versions when viewing sessions and bookmarks, and easily open any autosaved version.

For more information on session versions and bookmarks, see <a href="360041902831-Working-with-Sessions.html#h_01EKZDFT5BGPRSMSWRJX2KZ4DE" target="_self">Using Session Versions and Bookmarks</a> .

------------------------------------------------------------------------

# Undo and Redo

You can undo and redo changes in an open session at any time, except during recording. You can even undo and redo changes after a session has been closed and reopened.

------------------------------------------------------------------------

# Supported Plug-In Formats

LUNA supports UAD-2 plugins, UADx plug-ins, LUNA Extensions, UAD Instruments, VST3 plug-ins, and Audio Unit (AU) plug-ins (in macOS). LUNA Extensions include Tape Machines, API and Neve Summing, and API Vision Console. Extensions are incorporated into the LUNA workflow. Instruments appear in a separate plug-ins list from insert effect plug-ins.

------------------------------------------------------------------------

# Tempo Modes

A LUNA session can be set to Clips Follow Tempo mode. This mode is set when the session is created, and can be enabled or disabled freely within the session. Tempo mode can also be set individually for tracks and for clips.

- **Clips Follow Tempo mode enabled –** The session tempo determines what happens when you import an audio clip. LUNA uses advanced detection mechanisms to determine the tempo of imported files and conforms clips to the session tempo. Use this for loop-based workflows, and to import loops or clips and keep them aligned with the tempo events in your session.

- **Clips Follow Tempo mode disabled –** The session allows free import of clips, and does not attempt to adjust clips to the session tempo. Use this for sessions recorded without a click, or session work like podcasts or soundscapes that do not require tempo conformance.

------------------------------------------------------------------------

# Sample Rates, Imported Audio, and Imported Sessions

LUNA sessions are not locked to a specific sample rate. You can change the sample rate of a LUNA session after you create or import it, without changing the sound or playback speed of the session.

LUNA always records audio as 24-bit files at the current hardware sample rate. All internal files, exports, and mix operations employ a 32-bit floating point architecture. You can import audio of any sample rate, or play back an audio session at any supported hardware sample rate, and LUNA intelligently renders and manages the audio to play it back correctly. Audio that you import into LUNA is saved in the session file with the same bit depth and sample rate at which it was imported.

------------------------------------------------------------------------

# Focus Browsers Overview

In LUNA, many operations open a Focus Browser at the left of the screen. For example, when you click the Preset button on a plug-in, a list of available presets appears at the left side of the screen. This methodology is much more conducive to fast workflows instead of burying functions within menus and submenus.

The default view of the Focus Browser shows Tracks, Plug-Ins, and Presets in a tabbed view. For more information, see [Using LUNA](360041440592-Using-LUNA.html) .

<figure class="wysiwyg-image">
![tracks-browser-callouts.png](LUNA%20Concepts_assets/0a259e947f142d4f7ee19cf1078179b2f772b23c.png)
</figure>

With a Focus Browser, you typically make a choice. For example, you choose an input to use for a track, or a preset to use with a plug-in.

<figure class="wysiwyg-image">
![general-browser-callouts-2x.png](LUNA%20Concepts_assets/36b71fdbad12f1ca0e62079bc33c4e8651617c54.png)
</figure>

## Expanding and collapsing folders in the Focus Browser

To expand or collapse a folder in a Focus Browser, click the folder name. For example, click the UADx folder in the Inserts Focus Browser to open or close the list of UADx plug-ins. To expand or collapse all folders in a Focus Browser, Option+Click on any folder name.

**Note:** The Expand and Collapse settings for a Focus Browser are saved globally across all sessions in LUNA.

------------------------------------------------------------------------

# Workflows

Workflows provide common editing, arranging, and navigation commands on a toolbar that you can open under the main LUNA control bar.

![workflows-switch.png](LUNA%20Concepts_assets/685bd4a4629ab7b958baa48c4578f9eaa39487ac.png)

For more information about workflows, see <a href="360041440592-Using-LUNA.html#using-workflows" target="_self">Using Workflows</a> .

------------------------------------------------------------------------

# Keyboard Shortcuts and Menu Reference

LUNA includes many convenient keyboard shortcuts for menu items and workflows so you can operate the system quickly. A complete list of all keyboard shortcuts and a full menu reference are available. In addition, you can customize keyboard shortcuts, or remap the system shortcuts to match popular DAWs.

See these articles:

- [Customizing LUNA Keyboard Shortcuts](35314657057172-Customizing-LUNA-Keyboard-Shortcuts.html)
- <a href="360041651392-Default-LUNA-Keyboard-Shortcuts-and-Menu-Reference-macOS.html" target="_self">Keyboard Shortcuts and Menu Reference (macOS)</a>
- [Keyboard Shortcuts and Menu Reference (Windows)](26788810000788-Default-LUNA-Keyboard-Shortcuts-and-Menu-Reference-Windows.html)

## LUNA Key Commands Mapped to macOS Shortcuts

Some key commands are mapped to shortcuts in macOS by default. These key commands must be disabled or remapped in order to use the LUNA key commands. These key commands and remapping instructions are listed here.

- **Command+Spacebar** (Toggle Record): By default, this key command is mapped to the macOS Spotlight search feature. You must disable or remap this feature to use this key command. To disable or remap this command, in System Preferences \> Spotlight \> Keyboard Shortcuts uncheck the key commands, or map them to different key commands. Refer to your macOS documentation for more information.
- **Control+↑** (Increase selected track heights): By default, this key command is mapped to the macOS command for Mission Control. You must disable or remap this feature to use this key command. To disable or remap this command, in System Preferences \> Keyboard, click Shortcuts and disable this key command, or map it to a different key command. Refer to your macOS documentation for more information.
- **Control+↓** (Decrease selected track heights): By default, this key command is mapped to the macOS command for Application Windows. You must disable or remap this feature to use this key command. To disable or remap this command, in System Preferences \> Keyboard, click Shortcuts and disable this key command, or map it to a different key command. Refer to your macOS documentation for more information.
- **MIDI Keyboard Mode** : MIDI keyboard Mode overrides some keys that are used as shortcuts.

<span class="wysiwyg-font-size-small">251017</span>

