---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041909631-Configuring-LUNA-Settings.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'Configuring LUNA Settings'
word_count: 4282
---

# Configuring LUNA Settings


You can configure settings for LUNA using the Setting screens, or by choosing LUNA \> Settings from the LUNA menus. Many settings in the article are for LUNA in Apollo Mode. 

- To configure LUNA settings in Core Audio mode, see [Using LUNA with Core Audio.](https://help.uaudio.com/hc/en-us/articles/13210238444948)

- To configure LUNA settings in Windows, see [Using LUNA in Windows.](https://help.uaudio.com/hc/en-us/articles/26793892701460)

## In this article

- [Configuring the Session Autosave Interval](#h_e661b4b3-6667-47c3-9b33-578f49acba66)
- [Assigning Default Extensions](#h_01HER034JRQ6XW5VXW91NZ4AZ7)
- [Selecting Apollo Mode, Core Audio Mode, or ASIO Mode](#h_01H3FF4FN3R59GQ2WP2N2PYNZB)
- [Setting the Hardware Sample Rate](#h_d163c2eb-b6a1-4c69-a684-ef9ba2fb0318)
- [Choosing a Clock Source](#h_9ad23c25-3cc6-48e9-9732-5fa944c83285)
- [Configuring Input Delay Compensation (Apollo Mode)](#h_fd9b05ad-9b8c-4b56-83f6-ba0f75b44dd4)
- [Configuring Cue Buses](#h_28474905-d875-4a38-8c13-00d091e9d2d9)
- [Configuring Alt Monitor Count](#h_9a98fdeb-e709-4246-a25b-cc4d2d64f4f6)
- [Configuring Devices](#h_fcbded3a-bda8-4842-9924-ffe7b5c2ff31)
- [Setting up the I/O Matrix](#h_b1facf8c-ee99-448a-9252-95ea0469a067)
- [Setting Display Options](#h_d3b48bba-6e23-4205-ad3b-694454c65eed)
- [Configuring Editing Options](#h_e14f585d-1ebf-45fe-b0f4-726e039f725a)
- [Using Monitor, Control Room, and Talkback Sections](#h_e7cc224c-a7e5-4b53-9d6b-5314309f3aac)
- [Using Global Controls](#h_23a07dab-5a80-4093-949e-eee62d9a865b)
- [Viewing  and Adjusting Audio Settings](#h_c82af173-991a-4f48-a2be-31b8710d7f76)

------------------------------------------------------------------------

# Configuring the Session Autosave Interval

#### To specify an automatic save interval:

1.  Open the LUNA Sidebar by clicking the UA diamond logo on the left of the screen, and clicking Settings, or choose LUNA \> Settings from the app menu.
2.  Click Options.
3.  In the Autosave Interval field under Miscellaneous in the Options panel, type an auto-save interval in minutes.

#### To revert to a previous autosaved version:

- From the LUNA app menu, select File \> Open Version, and select a version, bookmark, or auto-saved file to which to revert. **Note:** Select Show Auto-Backups to show automatic backup files.

#### To save a session copy:

- From the app menus, choose File \> Duplicate. Specify the location and filename, and click Save.

------------------------------------------------------------------------

# Assigning Default Extensions

LUNA can assign default LUNA Extensions that you own are that are currently being demoed. For example, LUNA can assign the Oxide Tape plug-in to all tracks, or Neve Summing to all buses and the Main track. When assigned by default, you can change which Extensions are assigned (on a per-session basis) simply by making changes to the Extensions in the New Tracks dialog or the Create Bus dialog.

## To enable or disable default extensions

1.  Open the LUNA Sidebar by clicking the three dots on the left of the screen, and clicking Settings, or choose LUNA \> Settings from the app menu.
2.  Click Options.
3.  Under Miscellaneous, turn Assign Default Extensions on or off.

------------------------------------------------------------------------

# Selecting Apollo Mode, Core Audio Mode, or ASIO Mode

LUNA can run in Apollo mode, Core Audio mode, or ASIO mode. The mode is displayed and selectable in the Audio Device menu at lower left of LUNA’s main window. You can switch the mode at any time.

#### To change between Apollo mode and Core Audio mode or Apollo mode and ASIO mode within a LUNA session

1.  Make sure the Info section is displayed (View \> Section \> Info).
2.  At the lower left corner, click the info area to show the Audio Settings popover.
3.  From the Device menu, choose Apollo, Core Audio, or ASIO.

<figure class="wysiwyg-image">
![audio-settings-popover-apollo.png](Configuring%20LUNA%20Settings_assets/e3f01e7fc1fca5f551abb8b8d7203ad93055e68a.png)
</figure>

------------------------------------------------------------------------

# Setting the Hardware Sample Rate

LUNA can run a session at any supported hardware sample rate. The sample rate is displayed and selectable in the Settings \> Hardware Panel \> Sample Rate menu, and also in the Audio Settings popover at the lower left of LUNA’s main window. You can switch the sample rate of a session at any time, and LUNA will create temporary audio files to maintain the session pitch and time.

## To change the hardware sample rate in LUNA

1.  Make sure the Info section is displayed (View \> Section \> Info).
2.  At the lower left corner, click the info area to show the Audio Settings popover.
3.  From the Rate menu, choose the sample rate.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![audio-settings-popover-rate.png](Configuring%20LUNA%20Settings_assets/eb2a0ae55b658a400b07a58cf7f5781950e3eab5.png)
</figure>

<div class="wysiwyg-text-align-center" title="Attachment">

 

</div>

## To change the hardware sample rate from Hardware Settings

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware panel.
3.  From the Sample Rate menu, select the new sample rate.

------------------------------------------------------------------------

# Choosing a Clock Source

The active clock source (Internal, ADAT, S/PDIF, or Word Clock) is displayed here. This area flashes red if the currently selected clock is unresolved (when digital audio is not synchronized).

## To choose a clock source

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware page.
3.  From the Clock Source drop menu, choose the clock source.

## Configuring the Digital Mirror setting

This setting configures the S/PDIF outputs (Apollo, Apollo 8/x8, Apollo 8p/x8p and Apollo x4) or AES/EBU outputs (Apollo 16/x16) to mirror the Monitor 1 and 2 outputs. This feature is typically used when connecting to the stereo inputs of other devices with digital inputs such as a speaker system, stereo recorder, or external D/A converter. When Digital Mirror is ON, the Monitor Level knob controls both the digital output level and the analog monitor output level (these digital outputs are post-fader when mirrored).

------------------------------------------------------------------------

# Configuring Input Delay Compensation (Apollo Mode)

UAD plug-in latency can be automatically compensated with Input Delay Compensation (IDC). Input Delay Compensation maintains phase alignment across all analog and digital inputs when UAD plug-ins that induce latency are used in LUNA. For example, if you use two microphones on an acoustic source (such as a drum kit) and a latency-inducing UAD plug-in is used on one of the mic channels but not the other, without input delay compensation, the phase of the two mic channels would no longer be aligned.

**Note:** LUNA shows a warning when this situation occurs.

## To change the input delay compensation from Hardware Settings

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware page.
3.  From the Input Delay Compensation menu, choose the input delay compensation value.

### **Input delay compensation values**

- **Off**: 0 samples

- **Short**: 100 samples

- **Medium**: 200 samples

- **Medium-Long**: 300 samples

- **Long**: 1000 samples

For more information about Input Delay Compensation, see [Hardware Settings Panel](25403573794836-Hardware-Settings-Panel.html).

------------------------------------------------------------------------

# Configuring Cue Buses

In addition to the main monitor stereo mix bus and the two auxiliary stereo mix buses, Apollo features up to four stereo cue mix buses (two with Apollo Twin) that can be used for a variety of signal routing purposes.

The cue mix buses are used to create unique mixes that are separate from the main monitor mix. Cues are typically used for performers that want to hear a headphone mix that is different from the main monitor mix, sending separate mixes to other rooms or audio equipment, and similar applications.

#### To set the number of cue buses available in LUNA:

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware panel.
3.  From the Cue Bus Count menu, choose the number of cue buses (if available).

## Cue labels

The cue labels vary per Apollo device model, as described below.

- **Apollo rack models and Apollo x4 (Gen 1 & 2)–** The cues are labeled CUE 1, CUE 2, CUE 3, and CUE 4 respectively.\
  \
  ![cue-outputs-x8p.png](Configuring%20LUNA%20Settings_assets/103314af6a18409d8c5b371bb1bd815526b7b49a.png)
- **Apollo Twin, Twin X (Gen 1 & 2) –** With Apollo Twin, the two cues are labeled HP (headphone) and LINE 3/4 (line outputs 3 and 4) to reflect the available hardware outputs on the device.\
  \
  ![cue-outputs-twin.png](Configuring%20LUNA%20Settings_assets/e893c276ca9737c08b1c07deab4091e8d0908fef.png)

## Cue components

The complete cue system comprises the cue mix buses, the cue sends, and the cue outputs.

- **Cue Mix Buses:** A cue mix bus is the summed stereo mix of individual audio signals. Signals are routed into the cue mix buses via the cue send controls, and returned from the cue mix bus via the cue outputs controls.

- **Cue Sends:** The cue sends adjust the individual channel signals going into the cue mix bus. Each input channel and aux return contains individual level, pan, **\*** and mute controls for each active cue mix bus. All cue sends are pre-fader and pre-mute so they are not affected by adjustments to the main monitor mix. Note that if two input channels are stereo-linked, the cue sends on the stereo pair cannot be panned. Sends for stereo channels are hard-panned left and right.\
  \
  ![cue-mixing.png](Configuring%20LUNA%20Settings_assets/321c9a5ed609bcfdb24e90931b7eb0abd625406b.png)

   

- **Cue Outputs:** Cue mix buses are returned via the Cue Outputs window, which is a matrix for routing the cues to Apollo’s available hardware outputs.

- **Cue Monitoring:** Available cue outputs also can be selected as a source for the main monitor outs via the Monitor Output Options, enabling any cue mix bus to be heard in the main monitor speakers.

## Cue count

By default, two cues are displayed in LUNA (four with Apollo 16 and x16). Up to four cues are available with Apollo by increasing the Cue Bus Count.

------------------------------------------------------------------------

# Configuring Alt Monitor Count

Apollo features Alt (alternate) monitoring capabilities. Alt monitoring can be used to control an alternate pair or pairs of monitor speakers, which is convenient for quickly comparing how a mix sounds through a different set of speakers. Up to two pairs of Alt monitors can be used (one pair with Apollo Twin).

#### To configure one or more Alt Monitor settings:

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware page.
3.  From the Alt Count menu, choose the number of Alt Monitor mixes.

Alt monitoring is enabled in Hardware Settings within the Settings window by increasing the Alt Count setting to a non-zero value.

## Alt monitor connections

**Note**: The Alt channel output assignments cannot be modified.

- **Apollo rack models and Apollo x4 (Gen 1 & 2)–** The Alt 1 monitor signal is routed to line outputs 1-2, and the Alt 2 monitor signal is routed to line outputs 3-4.
- **Apollo Twin and Twin X (Gen 1 & 2) –** The Alt monitor signal is routed to line outputs 3-4.

See the [Hardware Settings Panel](25403573794836-Hardware-Settings-Panel.html) for more information.

------------------------------------------------------------------------

# Configuring Devices

You can set digital input and output formats, output reference level, and configure line inputs to bypass preamps. You can also configure channel DSP pairing, and easily identify devices.

## Setting digital input formats

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware panel.
3.  From the Digital Input menu, choose the digital input format.

This menu selects the digital input type (ADAT or S/PDIF) to be used by the TOSLINK optical connector and Console’s digital input channels.

Optical S/PDIF digital input is supported at sample rates up to 96 kHz. If the current setting is ADAT and the sample rate is higher than 96 kHz, when S/PDIF input is selected, the clock source is changed to Internal and the S/PDIF inputs are no longer available.

### Apollo models with digital inputs

- Apollo 8p
- Apollo x8p
- Apollo x8p Gen 2
- Apollo Twin
- Apollo Twin X
- Apollo Twin X Gen 2
- Apollo x4
- Apollo x4 Gen 2

## Setting digital output formats

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware page.
3.  From the Digital Output menu, choose the format of the digital output.

This menu selects the digital output type (ADAT or S/PDIF) to be used by the TOSLINK optical connector and Console’s digital outputs channels.

Optical S/PDIF digital output is supported at sample rates up to 96 kHz. If the current setting is ADAT and the sample rate is higher than 96 kHz, when S/PDIF input is selected, the clock source is changed to Internal and the S/PDIF outputs are no longer available.

### Apollo models with digital outputs

- Apollo 8p
- Apollo x8p
- Apollo x8p Gen 2
- Apollo x4
- Apollo x4 Gen 2

## Setting output reference levels

Use the Output Reference Levels section for each interface to set reference level for the line outputs. The number of menus displayed depends on the currently connected Apollo hardware (for example, Apollo 16, which features more outputs, will display more output menus).

The line output reference levels can be set to –10 dBV or +4 dBu in adjacent pairs. The value is usually set to match the nominal input level of devices connected to these outputs (a setting of +4 dBu outputs a higher signal level than –10 dBV).

With Apollo X Series rackmount interfaces, you can set output reference levels to +24 dBu in LUNA Settings for operating level compatibility with professional mixing consoles and other high-end pro audio equipment.

## Allowing line input gain

By default, line inputs on preamp channels are routed through the channel’s preamp so the line input level can be adjusted with the Gain knob. However, preamp channel line inputs can be individually set to completely bypass the channel’s preamp circuitry and instead operate at a fixed reference level.

Use this feature to route the preamp channel’s line input signal directly into the D/A converter for the purest path when additional gain is not needed (for example, when connecting external mic preamps to preamp channel line inputs).

Two settings are available:

- **On** – The line input is routed through the channel’s preamp
- **Bypass** – The preamp and associated circuitry are bypassed.The Preamp Gain Indicator ring for the channel is lit solid green. If a Unison plug-in is on a track that uses this channel’s line input, the Unison plug-in is bypassed.

**Note:** Line Input Gain availability depends on the Apollo model.

### Apollo models with Line Input Gain

- Apollo 8
- Apollo 8p
- Apollo x6
- Apollo x8
- Apollo x8pApollo x6 Gen 2
- Apollo x8 Gen 2
- Apollo x8p Gen 2
- Apollo Twin X Gen 2
- Apollo x4 Gen 2

### Apollo models without Line input Gain

- Apollo FireWire
- Apollo 16 FireWire
- Apollo x16
- Apollo x16 Gen 2
- Apollo x16D
- Apollo TwinApollo Twin X
- Apollo x4 
- Apollo Twin USB
- Apollo Twin X USB
- Apollo SOLO
- Apollo SOLO USB
- Arrow

## Channel DSP Pairing

Channel DSP Pairing lets you use more plug-ins on a single LUNA channel than a single DSP could normally handle. Essentially, DSP is stacked to support heavier DSP plug-in use on a channel.

- Channel DSP Pairing doubles the processing power available for a single input, allowing you to run complex chains of plug-ins without running out of DSP power for a specific track.

- Channel DSP pairing doesn't give you more DSP power, but reallocates existing DSP.

- All plug-ins still have to individually fit on one chip. Plug-ins aren't partially processed on two chips, but plug-ins on two chips can be used with the same track.

- Once enabled, LUNA automatically configures DSP pairing. Add plug-ins as usual, and LUNA will inteliigently allocate DSP

- More pairs require that you reduce virtual channels. As you increase the number of DSP pairs, available virtual channels decrease.

### Hardware Limits

- **Apollo rack models: ** Default two pairs, maximum four pairs
- **Apollo Twin and x4: ** Default one pair, maximum two pairs

For more details, see [Hardware Settings Panel](25403573794836-Hardware-Settings-Panel.html).

### To configure Channel DSP Pairing

1.  At the left of the LUNA window, click the three dots, then click Settings.
2.  Choose the Hardware page.
3.  Under Channel DSP Pairing, move the slider to balance DSP Pairs with Virtual Channels.

## Identifying devices

Click the Identify switch to cause the currently selected unit’s front panel LEDs to flash in a pattern. This feature is typically used with multi-unit systems to distinguish units when making I/O connections.

------------------------------------------------------------------------

# Setting up the I/O Matrix

Use the I/O Matrix panel to configure custom I/O routings for Core Audio that are managed at the driver level. For an overview of I/O Matrix features, see [I/O Matrix Settings Panel](https://help.uaudio.com/hc/en-us/articles/25403673923220).

**Note:** Audio artifacts can occur with some Apollo multi-unit configurations when more than 64 inputs are available to LUNA. To prevent these artifacts, set the maximum number of inputs to 64 (or less) in the I/O Matrix panel.

------------------------------------------------------------------------

# Setting Display Options

To set display options, open the LUNA Sidebar, and click Settings.

<div class="wysiwyg-text-align-center" title="Attachment">

![user-panel-annotated.png](Configuring%20LUNA%20Settings_assets/64a0f3c26347190f99e34d41ae798e52cd27dc54.png)

</div>

## Configuring pre or post fader metering

1.  Click the Options tab.
2.  From the Metering popover, choose Post-Fader or Pre-Fader.

## Setting clip holds

1.  Click the Options tab.
2.  From the Clip hold popover, choose the clp hold duration. To clear meter clips to clear immediately, choose None. If meter clips should persist for the entire time a session is open, choose Infinite. You can also choose a duration in seconds from the available options.

## Setting peak holds

1.  Click the Options tab.
2.  From the Peak Hold popover, choose the duration that peaks on LUNA meters should remain.

## Showing device names

1.  Click the Options tab.
2.  From the Show Device Names popover, choose Off or On.

------------------------------------------------------------------------

# Configuring Editing Options

You can configure the default fade shape and length, and set the controls mode.

## Configuring the default fade shape

From the Fade Shape menu, you can configure the default fade shape as Equal Power or Equal Gain.

Equal Gain is the default mode, and it works better for phase-coherent material, for example when fading between clips from the same guitar track or drum track. Equal Power mode works better for material that is less similar, dissimilar, or not phase-coherent, for example two different vocalists or two different guitar recordings.

## Configuring the default fade length

Configure the default fade length to specify the default length of any fade that is created automatically. For example, if you select a range of audio with edits in it, and select Edit \> Create Fades (Command+F), this value determines the length of the fades created.

**Note:** This value specifies the *total* length of the default fade or crossfade, so with the default setting of 100ms, the length of a fade in or fade out is 100ms, and the length of a crossfade is 100ms, or 50ms on each side of the crossfade.

## Setting controls mode

This setting determines how LUNA knobs and UAD plug-in parameter knobs respond to adjustment. Three control modes are offered: Circular, Relative Circular, and Linear. The behavior of each mode is described below.

- **Linear** (slider) – In Linear mode, the knob is adjusted by dragging horizontally or vertically instead of by rotating. This behavior is similar to moving a physical fader.
- **Circular** (jump) – In Circular mode, the software knobs behave similar to physical rotary knobs. Values are changed by clicking on the knob then rotating in a circular direction. When the edge of the knob is clicked, the parameter value jumps to the mouse position.
- **Relative Circular** (grab) – Relative Circular mode operates similar to Circular mode, but the knob value does not jump to the mouse position when clicked. Instead, the knob value is modified relative to its original value. In Relative Circular mode, click anywhere on the knob to make an adjustment originating at the original value (it’s not necessary to click on the current knob position).

**Tip:** To increase resolution when adjusting rotary controls in circular and relative circular modes, increase the radius of the mouse relative to the knob while dragging (move the mouse farther away from the knob while dragging in a circular motion).

------------------------------------------------------------------------

# Using Monitor, Control Room, and Talkback Sections

The Monitor, Control Room, and Talkback sections show controls for monitoring and for using talkback on talkback-enabled Apollo units. This section also allows you to bypass processing for inserts, Extensions, or both.

To bypass processing, see [Bypassing processing.](360041465732-Mixing-in-LUNA.html#h_01H3FG40RYSH7ZGT2QFNDE234A)

To work with the Monitor Controller window, see [Apollo X Bass Management](https://help.uaudio.com/hc/en-us/articles/30920209088404) and [Speaker Utilities](https://help.uaudio.com/hc/en-us/articles/36177324309140).

## Viewing the Monitor strip

The meters on the Monitor strip display the signal levels of the monitor mix bus just before the monitor level control. Levels displayed here mirror the state of the Monitor 1 – 2 LED meters on Apollo monitor unit’s front panel. You can control the level of the Monitor outs, switch to Mono, and Mute the Monitor outs.

**Note:** Output metering in UAD Console is adjusted to reflect the actual output post processing (after any speaker correction, Bass Management, and Safe Headroom are applied). For this reason, UAD Console's output meters may not match the level on LUNA’s Main track. Refer to the Main track level meters when mixing.

From the Monitor strip, you can also open the Control Room strip, the Monitor Controller window (Apollo X hardware only), Monitor Correction windows for Headphones and/or Monitors, and the Cue Outputs window.

- To work with Cues, see <a href="360041441112-Recording-Audio.html#cue-mixes" target="_self">Making cue mixes</a>.
- To work with the Monitor Controller window, see [Apollo X Bass Management](https://help.uaudio.com/hc/en-us/articles/30920209088404) and [Speaker Utilities](https://help.uaudio.com/hc/en-us/articles/36177324309140).
- To work with Apollo Monitor Correction, see [Apollo Monitor Correction by Sonarworks®](31655084572820-Apollo-Monitor-Correction-by-Sonarworks.html). You can show or hide Apollo Monitor Correction buttons and windows by choosing View \> Section \> Monitor Correction.

<div class="wysiwyg-text-align-center" title="Attachment">

![monitor-column.png](Configuring%20LUNA%20Settings_assets/14462772e9f68c4c33c659f8f045a03f78162d9c.png)

</div>

#### To show the Monitor strip

In the View section, click the Other Views icon and choose Mon, or from the app menu, choose View \> Section \> Monitor.

![other-views-mon.png](Configuring%20LUNA%20Settings_assets/18f122f65ab11122567cfea995ad313cdabff0a4.png)

## Viewing the Control Room strip

The control room strip allows you to configure options for the monitor outputs.

By default, the control room column is not visible. To show the column, click Control Room on the Monitor strip, or choose View \> Section \> Control Room from the app menu.

<div class="wysiwyg-text-align-center" title="Attachment">

![control-room-luna.png](Configuring%20LUNA%20Settings_assets/30ef497dd317b348c45a47d537f082bc1e1a0e02.png)

</div>

## Control Room Sources

Use the Source options to choose the source for the mix bus that is sent to Apollo’s monitor outputs. The source is selected when its switch is lit.

The control room Source switches control the source that feeds the control room mix. The source can be the Monitor mix or any of the available cues.

Use Dim to quickly reduce the listening volume in the control room by a set amount and quickly return to the prior volume.

## Alt Trims

The ALT trim controls are typically used to compensate for different levels of the alternate monitor speakers so they have the same apparent volume as the main monitor speakers.

**Note:** ALT controls are only visible when the Alt Count menu in the Hardware panel within the Settings window is set to a non-zero value.

## Talkback strip

The talkback input channel strip is available in the Control Room module within Console whenever an Apollo model featuring talkback is connected.

The talkback strip has eight UAD plug-in inserts for Realtime UAD Processing. All talkback plug-in inserts operate the same way as other inputs.

Talkback sends display an overview of the talkback levels being sent to each available send bus, including Aux 1 and 2, and 2 Cue mix buses.

To access the Talkback Sends Popover window, where individual talkback send levels are adjusted, click the Talkback Sends Display.

------------------------------------------------------------------------

# Using Global Controls

Use global controls to toggle LUNA settings globally.

<div class="wysiwyg-text-align-center" title="Attachment">

![global-controls.png](Configuring%20LUNA%20Settings_assets/118e4ef405e96f69a7e19ef8e2ae30a532f880b0.png)

</div>

- To toggle record-enabled tracks globally, on the control bar in the Global section, click the Toggle Record button. All record-enabled tracks are toggled out of record-enabled mode. Click Toggle Record again to toggle the tracks back to record-enabled mode.
- To toggle input-enabled tracks globally, on the control bar in the Global section, click the Toggle Input Enable button. All input-enabled tracks are toggled out of input-enabled mode. Click Toggle Input Enable again to toggle the tracks back to input-enabled mode.
- To toggle soloed tracks globally, on the control bar in the Global section, click the Toggle Solo button. All soloed tracks are toggled out of solo mode. Click Toggle Solo again to solo the tracks.
- To toggle muted tracks globally, on the control bar in the Global section, click the Toggle Mute button. All muted tracks are unmuted. Click Toggle Mute again to mute the tracks again.
- To toggle ARM mode, on the control bar in the Global section, click the Toggle ARM Mode button. The system is ARM-enabled and any audio tracks that are record-enabled or input-enabled are put into ARM mode. To leave ARM mode, click Toggle ARM Mode again.
- To clear meter clips globally, on the control bar in the Global section, click the Clear Meter Clips button. All meter clips are cleared.

------------------------------------------------------------------------

# Viewing and Adjusting Audio Settings

From the menu, select View \> Section \> Info.

The audio settings overview is displayed at the bottom left of the LUNA window. Click this section to open the Audio Settings popover.

In Audio Settings, you can show and adjust the following settings:

- Audio Device (Apollo, Core Audio, or ASIO). If you have a Volt interface, this setting will say VOLT, but will be either Core Audio or ASIO depending on your OS.

- Current hardware sample rate

- Clock source (Apollo mode)

- Buffer size (32–2048 samples)

- More Settings (this opens LUNA’s Settings)

In addition, the following informational settings are shown:

- Render (the amount of CPU used for all native processing)

- Render IO (the amount of CPU used by plug-ins on instrument tracks)

- Memory (the amount of memory used by LUNA)

- In Apollo mode, UAD-2 DSP, Program, and Memory resource meters (identical to those on the the UAD Meter & Control Panel)

![audio-settings-popover-apollo.png](Configuring%20LUNA%20Settings_assets/e3f01e7fc1fca5f551abb8b8d7203ad93055e68a.png)

*Audio Settings popover (Apollo mode)*

![audio-settings-popover-volt.png](Configuring%20LUNA%20Settings_assets/91b73159c8db98cb7794c723189c3647f0a78d57.png)

*Audio Settings popover (Core Audio with a Volt interface)*

<span class="wysiwyg-font-size-small">250106</span>

