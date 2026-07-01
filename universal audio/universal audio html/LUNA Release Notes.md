---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041532452-LUNA-Release-Notes.html'
converted_at: 2026-05-31T13:44:54Z
tool: htmlq+pandoc
title: 'LUNA Release Notes'
word_count: 20690
---

# LUNA Release Notes


### Related Information

- <a href="360041532932-LUNA-System-Requirements.html" target="_self">LUNA System Requirements</a>
- <a href="../sections/360008484871-LUNA-Application-Manual.html" target="_self">LUNA User Documentation</a>
- <a href="https://www.uaudio.com/uad/downloads/" target="_self">Download LUNA</a>

**Tip:** To get the latest version of LUNA, choose **Check For Updates...** under the LUNA menu in any previous version of LUNA.

## LUNA 2.0.3 - April 14, 2026

### New

#### UAD Explore FREE Track Templates & Track Presets

- Easily add new tracks and access presets using plugins included in UAD Explore Free
- Get UAD Explore Free from the tab in UA Connect

#### Fixed

- Resolved an issue where I/O Settings & I/O Matrix were not updated after the audio device changed until LUNA was restarted
- General Bug Fixes

\
 

<div class="accordion__item">

<div class="accordion__item-title">

LUNA 2.0.2 - April 7, 2026

</div>

<div class="accordion__item-content">

### Fixed

- Resolved issues related to ARA plugins, including fixes for bugs affecting session saving and recall when ARA data is present
- Volt 876 preamp settings now display when assigning an input in a session that previously had no inputs assigned
- The Audio Settings popover now closes when you press the ESC key 
- Resolved an issue with non-Apollo interfaces where the LUNA Hardware Insert reported negative latency
- General stability improvements and maintenance enhancements

#### Downloads

- <a href="https://builds.uaudio.com/apps/luna/LUNA_2_0_2_4369.tgz" rel="noopener noreferrer" target="_blank"><strong>macOS</strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_2_0_2_4369.zip" rel="noopener noreferrer" target="_blank"><strong>Windows</strong></a>

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

LUNA 2.0.1 - November 4, 2025

</div>

<div class="accordion__item-content">

#### Fixed

- Resolved a crash on quit that could occur after using Melodyne
- Resolved Melodyne playback timing issues
- Resolved duplicate instances of Melodyne appearing in the Inserts browser
- Resolved an issue causing crashes when changing the sample rate with Auto-Align 2 ARA
- Resolved the feedback loop that could occur when powering off a Hardware Insert
- Resolved an issue that could cause silent clips to be exported when using ARA

#### Downloads

- <a href="https://builds.uaudio.com/apps/luna/LUNA_2_0_1_4206.tgz" rel="noopener noreferrer" target="_blank"><strong>macOS</strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_2_0_1_4206.zip" rel="noopener noreferrer" target="_blank"><strong>Windows</strong></a>

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

LUNA 2.0 (Supplemental Build 4195) - October 21st, 2025

</div>

<div class="accordion__item-content">

#### Fixed

- Resolved an issue loading ARA plug-ins if VST3 plug-ins were scanned before LUNA 1.9.1

#### Downloads

- <a href="https://builds.uaudio.com/apps/luna/LUNA_2_0_0_4195.tgz" rel="noopener noreferrer" target="_blank"><strong>macOS</strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_2_0_0_4195.zip" rel="noopener noreferrer" target="_blank"><strong>Windows</strong></a>

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

LUNA 2.0 - October 21st, 2025

</div>

<div class="accordion__item-content">

### New

#### ARA 2 Support

- Supported ARA plug-ins provide deeper audio editing for pitch, alignment, AI-powered audio tools, and more, integrated in the LUNA timeline
- Access your ARA plug-ins from LUNA's track WARP menu
- Available VST3 ARA-enabled plug-ins appear in the ARA sub-menu, without additional scanning
- Show your ARA editor in the new docked editor panel, and toggle visibility of any currently used ARA plug-ins from the new LUNA footer
- Optionally toggle any ARA editor between a docked and undocked window by clicking the window button in the editor
- To learn more about ARA plug-in support in LUNA, [go here](https://help.uaudio.com/hc/en-us/articles/42434346072212)

#### Hardware Inserts (LUNA Pro required)

- Seamlessly route tracks, buses, or the MAIN channel through your outboard gear
- Click an insert, find the new Hardware Inserts folder, and choose New Hardware Insert
- Configure your routing and press the CALC button to effortlessly set up round trip delay compensation
- Save your hardware insert as a preset and easily recall its settings on any track from the Hardware Inserts folder
- To get LUNA Pro, [go here](https://www.uaudio.com/products/luna-pro?utm_source=luna&utm_medium=app&utm_content=lunapro2)

#### Instrument Detection

- LUNA uses AI-powered instrument detection to identify the instrument type for your audio tracks, then sets a track color and icon
- LUNA automatically chooses the best default warp algorithm for your audio material, so warping and tempo changes have the best possible sound quality
- Click the instrument icon in the audio track header to change the instrument type and open instrument detection settings
- Define default instrument color settings and default names for the optional auto-naming feature
- Enable or disable track coloring, warp assignment, and automatic naming in instrument detection settings
- Choose Run Instrument Detection from the Assistant menu to identify instruments and apply instrument detection settings

### Improved

#### Track Header Visibility

- Improved legibility of track names
- Improved access to the most commonly used features such as volume and pan

#### Audio Settings and Resource Display

- Audio settings and resource usage are now displayed in a popover to reduce clutter
- Click Audio or resource meters at lower left of new footer to view gauges and access device, sample rate, clock, and buffer size settings

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.9.1 - August 19, 2025

</div>

<div class="accordion__item-content">

### Installers

- [macOS](https://builds.uaudio.com/apps/luna/LUNA_1_9_1_4119.tgz)
- [Windows](https://builds.uaudio.com/apps/luna/LUNA_1_9_1_4119.zip)

### Improved

#### New Voice Commands

Additional prompts for marker navigation, count-in, pre/post roll, and click:

- “Go to next marker” or “Next marker”
- “Go to previous marker” or “Previous marker”
- “Toggle count in” or “Count in”
- “Toggle pre roll” or “Pre roll”
- “Click,” “Toggle click,” “Toggle the click,” “Metronome,” “Toggle metronome,” “Toggle the metronome”

### Fixed

- Resolved an intermittent crash when scanning VST3 plug-ins
- Resolved an issue that could prevent some VST3 plug-in changes from being saved
- Resolved an intermittent crash when editing clips
- Resolved an error that could occur when freezing a bus
- Resolved an issue preventing master volume, meter, and mute functions in non-Apollo setups\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.9.0 - July 16, 2025

</div>

<div class="accordion__item-content">

### Installers

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_9_0_4070.tgz" rel="noopener noreferrer" target="_blank">macOS</a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_9_0_4070.zip" rel="noopener noreferrer" target="_blank">Windows</a>

### New

#### Tooltips & Help

- Hover over LUNA controls and elements to display helpful details
- Click the ⓘ button to the right of the toolbar to toggle tips on/off

#### Feature Previews

- Help us improve LUNA by trying experimental features and tools
- From the Create page, click Preview Upcoming Features, then click Turn On Feature Preview at the bottom of the screen
- Submit your thoughts directly via LUNA's feedback button
- Read the [LUNA 1.9 Feature Previews FAQ](https://help.uaudio.com/hc/en-us/articles/39211229674132-FAQ-LUNA-1-9-Feature-Previews) to learn more

### Preview

#### Voice Control

- Control recording or playback with your voice, from anywhere in the room
- Use mics already set up for recording, or specify an input like Apollo's talkback mic
- Use "Hey LUNA," specify a custom phrase, or say commands without any wake up phrase
- Available on Apple silicon Macs only

#### Track Analysis Powered by AI Instrument Detection

- LUNA can automatically color-code and rename recorded or imported tracks based on the detected instruments
- Hover over the assistant icon in the bottom right corner of the timeline, click Analysis, then click settings to define custom names and colors for instrument categories

### Fixed

-  Resolved an issue with Shift editing after making a selection on the All Tracks ruler\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.8.5 - May 20, 2025

</div>

<div class="accordion__item-content">

### Installers

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_8_5_3992.tgz" rel="noopener noreferrer" target="_blank"><strong>Download This Version (macOS)</strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_8_5_3992.zip" rel="noopener noreferrer" target="_blank"><strong>Download This Version (Windows)</strong></a>

### New

#### UAD Software 11.7

- LUNA now requires UAD software 11.7 or newer with Apollo audio interfaces

### Improved

#### AI Tempo Detection

- Improved detection of long passages where tempo is constant
- Improved detection of tempo in loops and shorter files

#### Minimum Browser Width

- The browser can now be resized to a narrower minimum width

### Fixed

- Resolved an issue that could cause recording to hang after changing Core Audio devices when a session is open
- Resolved an issue that prevented importing tempo from MIDI files
- Resolved an appearance issue with solo-safe tracks that are soloed
- Resolved an issue that prevented newly added or changed modifier keys from working in shortcut profiles

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.8.4 – April 28, 2025

</div>

<div class="accordion__item-content">

### Installers

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_8_4_3961.tgz" rel="noopener noreferrer" target="_blank"><strong>Download This Version (macOS)</strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_8_4_3961.zip" rel="noopener noreferrer" target="_blank"><strong>Download This Version (Windows)</strong></a>

### Open Beta

#### AI Tempo Detection

- Early access to three new tempo detection features powered by machine learning
- Tempo Listen Mode listens as you play, matching the tempo to your feel before you record
- Import tempo detection syncs loops and clips to the session tempo as you drag and drop
- Extract tempo to create a tempo grid for the entire session or a selection, so you can provide an accurate click for material originally played freely

#### Tempo Listen

- In the LUNA toolbar, right-click the BPM area or left-click the BPM header to access the new tempo settings popover
- Click Listen in the Edit Tempo popover to set the BPM while you play
- As you play LUNA determines the tempo; click Apply to set the tempo

#### Import Tempo Detection

- Shorter audio files imported to the timeline will be analyzed for tempo
- Toggle CLIPS FOLLOW SESSION TEMPO on the Create Session page or via the new tempo settings popover, to determine how audio behaves in your session as the tempo is changed
- When clips are set to follow tempo, newly imported loops automatically warp to the current session tempo

#### Extract Tempo

- Calculate a complete tempo map from your entire session or a time range to align the grid and metronome to the performance
- Hover over the Tempo ruler header area and click EXTRACT, right-click in the BPM area, or click the BPM toolbar header to access the tempo settings popover
- Calculate tempo for the entire session, or calculate the tempo for a selected range
- Audition tempo candidates in the tempo ruler area, while listening to the click as it follows your track
- Drag the Move Downbeat marker to align the grid to the start of your song

### Improved

#### Updated Warp Trim Modifier Key

- Warp Trim mode is updated to use the Option (macOS) or Alt (Windows) keys
- Warp Trim to time-stretch or time-compress a clip – while holding Option (macOS) or Alt (Windows), drag the trim tool at the left or right edge of a clip to shorten or lengthen the clip while warping the audio to the new length

### Fixed

- Resolved an error message that could occur on launch
- Resolved a crash that could occur when exporting a mixdown from an audio interface output path
- Resolved errors that sometimes occured while editing clips with warp markers
- Windows: Resolved an issue that caused plug-in windows to move behind the main LUNA window when using the plug-in preset browser from an alternate window
- Resolved an issue that caused recently disabled plug-in formats to remain visible in the plug-in browser until LUNA restarted

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.8.3 – April 1, 2025

</div>

<div class="accordion__item-content">

### Installers

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_8_3_3924.tgz" rel="noopener noreferrer" target="_blank"><strong>Download This Version (macOS)</strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_8_3_3924.zip" rel="noopener noreferrer" target="_blank"><strong>Download This Version (Windows)</strong></a>

### Improved

- **Speaker Utilities for Apollo X and Apollo X Gen 2**
  - Mute, Solo, and Trim features are now available for all speaker outputs on desktop models, including the sub output when bass management is enabled
  - Sub output Mute, Solo, and Trim are now available on rackmount Apollo interfaces in stereo monitor mode when bass management is enabled
  - Requires UAD Software 11.6
- **Apollo Metering for Stereo Plus Sub**
  - Monitor meters now show stereo plus the sub channel when bass management is enabled in stereo monitor mode
  - Requires UAD Software 11.6

### Fixed

- Resolved an issue that could cause UAD-2 plug-in GUI issues at scaling factors greater than 125%
- Resolved an issue that prevented AU and VST3 format to display for Waves plug-ins when both formats were enabled

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.8.2 – March 4, 2025

</div>

<div class="accordion__item-content">

### Installers

[**Download This Version (macOS)**](https://builds.uaudio.com/apps/luna/LUNA_1_8_2_3881.tgz)

[**Download This Version (Windows)**](https://builds.uaudio.com/apps/luna/LUNA_1_8_2_3881.zip)

### New

- **Keyboard Shortcut Customization**
  - Define your own shortcuts for LUNA commands, and assign keystrokes to features that were previously unassigned
  - Click LUNA menu \> Keyboard Shortcuts \> Customize to open the keyboard shortcut editor
- **Popular DAW Keyboard Shortcut Presets**
  - Use shortcuts mapped from another DAW to simplify your LUNA workflow

### <span style="font-family: Helvetica, sans-serif;">Improved</span>

- <span style="font-family: Helvetica, sans-serif;">Bus spill: Inactive tracks are no longer displayed unexpectedly when spilled</span>
- <span style="font-family: Helvetica, sans-serif;">MANAGE PLUG-INS in the navigation menu now lists the number of new plug-ins found</span>
- <span style="font-family: Helvetica, sans-serif;">The assign menu in a plug-in's window header now indicates whether the plug-in is AU or VST3 version if both formats are installed</span>

### <span style="font-family: Helvetica, sans-serif;">Fixed</span>

- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that could cause new changes in a session to fail with a device.database_error</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that could cause the playhead and main counter to stop updating during playback after LUNA was open for many hours</span>
- <span style="font-family: Helvetica, sans-serif;">Fixed an issue that prevented duplicated buses from being selected automatically</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that caused the track selection to clear when right-clicking on selected tracks in the mixer view</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that prevented some columns in the Plug-In Manager from sorting correctly</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that could cause bus outputs to MAIN to appear inactive</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that could prevent bounced tracks from being saved as a track preset</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that caused auto-gain to remain in "Waiting for Audio" state indefinitely after re-ordering Apollo devices in a multi-unit configuration</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that could cause errors when importing session data from frozen tracks</span>
- <span style="font-family: Helvetica, sans-serif;">Resolved an issue that could cause bounce or freeze to ignore trimmed clip boundaries at the end of the session</span>

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.8.1 – February 4, 2025

</div>

<div class="accordion__item-content">

### Installers

- [**Download This Version (macOS)**](https://builds.uaudio.com/apps/luna/LUNA_1_8_1_3861.tgz)
- [**Download This Version (Windows)**](https://builds.uaudio.com/apps/luna/LUNA_1_8_1_3861.zip)

### New

- **Plug-In Manager**
  - Manage formats, scan and rescan, edit categories, ignore individual plug-ins, and troubleshoot plug-in issues by clicking MANAGE PLUG-INS in the LUNA navigation bar or by going to the Plug-Ins tab on the Settings page
- <span id="h_01JK8ZK913WA67HHX53KWYZJPK">**Open Beta**</span>
  - **VST3 Support for macOS**
    - Via the new Plug-Ins Manager, LUNA can now scan and use VST3 plug-ins installed on your system
    - By exclusively using VST3 format for third party plug-ins, LUNA sessions can now be fully compatible between macOS and Windows systems
    - Please submit feedback on any VST3 specific issues during the open beta period
- <span id="h_01JK8ZRBGMZC9BCRBHT5N8J490">**Custom VST3 Location**</span>
  - Specify an additional location for VST3 scanning in the MANAGE PLUG-INS page
- <span id="h_01JK8ZVA5BRGYX699SKFJAF0Z0">**AU/VST3 Plug-In Scan After Launch**</span>
  - New plug-ins are no longer scanned during the launch process
  - Newly installed plug-ins are detected automatically in the Manage Plug-Ins page
  - Click SCAN NEW to load all new plug-ins or scan individual plug-ins
  - It is no longer necessary to restart LUNA when installing third party plug-ins
- <span id="h_01JK8ZXTGZEWNGME2EQAZW3X34">**Show/Hide Fader Section**</span>
  - Toggle visibility of the FADER section for mixer view and the focus channel from the Mixer Navigation panel
  - Toggle visibility of the FADER section for mixer view and the focus channel from the Mixer Navigation panel

### Fixed

- Resolved an issue that could cause grouped fader moves on a control surface to set volume levels above +12 dB
- Resolved an issue that caused default settings to be applied to plug-ins after bouncing a track with Bounce Up To This Insert
- Resolved an issue that caused an unexpected Dante-related sample rate error when changing Sample Rate from an alternate window
- Resolved a VST3 performance issue that could prevent gain reduction meters from displaying values in some plug-ins
- Resolved an issue that could cause track name issues in Sound Radix Auto-Align 2 VST3 plug-in
- Windows: Fixed a set of issues related to floating window appearance while toggling between apps
- Resolved an issue that caused the plug-in window header sidechain enable button to appear active despite no sidechain connection
- Windows: Resolved overlapping cues power and window close buttons in CUE management popover
- Resolved an issue that prevented option or alt click from setting API Vision Channel Strip EQ controls to default value
- Resolved an issue that could cause errors instantiating some AU plug-ins such as Modartt Organteq
- Resolved an issue that caused the deactivated treatment to appear with controls in the mixer instead of on top of them

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.8 – December 11, 2024

</div>

<div class="accordion__item-content">

### Installers

- [**Download This Version (macOS)**](https://builds.uaudio.com/apps/luna/LUNA_1_8_0_3794.tgz)
- [**Download This Version (Windows)**](https://builds.uaudio.com/apps/luna/LUNA_1_8_0_3794.zip)

### New

- **Bounce**
  - Bounce tracks and buses in place to render audio to a new or target destination track
  - Access Bounce and Bounce Range from the Track menu or by right clicking a track name or timeline selection range
  - Command + B (macOS) or Ctrl + B (Win) to Bounce selected tracks from start to finish
  - Option + B (macOS) or Alt + B (Win) to Bounce the selected tracks for the duration of the edit selection range
  - Shift + Option + B (macOS) or Shift + Alt + B (Win) to open the Bounce Settings browser where source track, audio clip, and destination track options can be selected
  - By default bounced tracks are "Archived" which fully deactivates and removes the track from the tracks list. Right click on resulting bounce tracks and choose "Restore Bounce Source" to unarchive the original track
- **Track Presets**
  - Save and recall one or more selected tracks as a preset
  - Right click a track selection or click the Track menu and choose "Save Tracks as Preset"
  - Shift + Option + P (macOS) or Shift + Alt + P (Win) to save a track preset
  - Shift + Command + P (macOS) or Shift + Ctrl + P (Win) to create a new track from preset
  - Update an existing track by double clicking the track name or right clicking and selecting "Assign Preset"
- **Browser Tabs**
  - Click to toggle between Tracks, Plug-ins, and Presets views or cycle tabs via Option + \` (backtick (macOS) or Alt + \` (backtick (Win)
  - Plug-ins tab allows drag and drop or keyboard assignment of plug-ins
  - Drag a plug-in to any track or insert slot to assign it
  - Press return or click the Add button to add a plugin to the next available insert on the focused channel
  - Presets tab allows drag and drop or keyboard assignment of user track presets and instrument plug-in presets
  - Drag a preset to the timeline or mixer to either create a new track from preset or directly on to an existing track to update it
  - Press return or click the New button to create a new track from preset

### Improved

- **Browser Toggle Button**
  - Toggle browser visibility by clicking the new browser show/hide button in the LUNA toolbar or by pressing the \` (backtick) key

### Fixed

- Resolved an issue that could prevent the Find Tracks command from focusing the tracks list search field
- Resolved an issue that prevented display of some UAD-2 plug-in presets
- Resolved an issue that could intermittently cause audio drop-outs when exporting or freezing tracks

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.7.3 – November 12, 2024

</div>

<div class="accordion__item-content">

### Installers

- [**Download This Version (macOS)**](https://builds.uaudio.com/apps/luna/LUNA_1_7_3_3768.tgz)
- [**Download This Version (Windows)**](https://builds.uaudio.com/apps/luna/LUNA_1_7_3_3768.zip)

### New

- **Apollo Monitor Correction by Sonarworks (UAD v11.5.1 Required)**
  - Apply custom profiles to your reference headphones, or studio monitors to correct your room's acoustics
  - To get started, open the MONITOR CONTROLLER window or click the new MAIN MON or HEADPHONES buttons in the Monitor column
  - <a href="https://www.uaudio.com/uad-console#correction" rel="noopener noreferrer" target="_blank">Learn more about Apollo Monitor Correction</a>
- **Improved Plug-In Processing Engine**
  - LUNA now uses two mixers that run at different buffer sizes, allowing simultaneous optimization for low latency recording and high performance mixing
  - Tracks and their destinations that are input monitored or recording run in the Render IO mixer, where latency and performance are managed by the Buffer Size pop-up, which now defaults to 64
  - Tracks and their destinations that are not input monitored or recording run in the Render mixer, which operates at a fixed 512 buffer size
  - Setting the buffer size above 512 will cause the entire system to run at the higher buffer size when mixing performance requires 1024 or higher
  - This system enhances LUNA's overall performance for non-Apollo systems or for when ARM mode is disabled, especially in processing-intensive recording sessions

### Improved

- **Mixdown and Freeze Reliability**
  - Complete rewrite of LUNA mixdown/freeze code
  - Freeze no longer requires two passes in scenarios involving busses and tracks
  - Addressed numerous stability and reliability issues with the mixdown process
- **Multi-Output Channel Format Selection**
  - Replaced FORMAT selection in the ADD MULTI-OUTPUT popover with a channel selection pop-up, making it easier to choose between the desired mono and stereo outputs of the plug-in
- **Mixdown and Export Clips Browsers**
  - Export Mixdown and Export Clips focus browsers have been moved to LUNA's left side
  - Export Mixdown column is now wider, enabling easier Mixdown channel selection
- **Double-click to Close Focus Browser**
  - Double-clicking an assignment item in the various LUNA focus browsers now completes the assignment and closes the browser
- **Browser visibility can now be toggled by typing the backtick (\`) key**
- **Shape no longer appears in a separate folder in the instrument plug-ins list**

### Fixed

- (Windows) Resolved an issue that could cause recorded audio and MIDI to appear on the timeline earlier than performed
- Resolved an issue that could cause display and folder hierarchy issues with UAD-2 plug-in user presets
- Resolved an issue that could cause "unable to touch control" error after converting a UADx plug-in to UAD-2
- Export Mixdown now always starts from the beginning of the session if there is not a timeline range selection
- Resolved an issue that could cause the Monitor Controller window to freeze while using ALT monitors
- Resolved an issue causing stereo Auto-Gain to detect peak values on left channel only

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.7.2 – October 8, 2024

</div>

<div class="accordion__item-content">

### Installers

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_7_2_3725.tgz" rel="noopener noreferrer" target="_blank"><strong><span class="wysiwyg-underline">Download This Version (macOS)</span></strong></a>
- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_7_2_3725.zip" rel="noopener noreferrer" target="_blank"><strong><span class="wysiwyg-underline">Download This Version (Windows)</span></strong></a>

### New

- **Support for Apollo X Gen 2 audio interfaces (UAD v11.5 required)**
  - <a href="https://www.uaudio.com/audio-interfaces/apollo.html" rel="noopener noreferrer" target="_blank">Learn more</a> about the entire line of Apollo X Gen 2 models
- **Preamp Auto-Gain for Apollo X Gen 2 (UAD v11.5 required)**
  - Automatically set gain for one or more Apollo X Gen 2 preamps
  - To start, simply click Auto-Gain in the preamp row for the channels you want to adjust
- **Bass Management for all Apollo X Series (UAD v11.5 required)**
  - Control your satellite/LFE speaker filters and crossover for surround monitoring modes
  - Control your subwoofer with crossover for stereo mode
- **Monitor Controller Window (UAD v11.5 required)**
  - Manage all monitoring features in one place — configure bass management, apply speaker trims, solos, and mutes, set up dB SPL calibration, and more
  - Click the new MONITOR CONTROLLER button in the monitor column to access features

### Improved

- Added section headers to the timeline pop-up menu for improved usability while editing
- Added section headers to the track pop-up menu in the Timeline View and Tracks List

### Fixed

- Resolved an issue that prevented Arturia keyboard faders from controlling LUNA
- Windows: Resolved an issue with some third party ASIO drivers that could prevent playback without providing instructions to check settings
- Resolved an issue that hid floating windows if another app was focused when LUNA was still visible
- Windows: Resolved an issue that could prevent plug-in windows from re-appearing when closing and reopening the same session without quitting LUNA
- Windows: Resolved an issue that could cause floating windows from LUNA or UAD Console to appear over other applications
- Resolved a crash that could occur when updating plug-ins via UA Connect with a LUNA session open
- The default preset for most native UAD plug-ins are now automatically selected in the plug-in browser when instantiated

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.7.1 – September 17, 2024

</div>

<div class="accordion__item-content">

### Installers

- [**Download This Version (macOS)**](https://builds.uaudio.com/apps/luna/LUNA_1_7_1_3679.tgz)
- [**Download This Version (Windows)**](https://builds.uaudio.com/apps/luna/LUNA_1_7_1_3679.zip)

### Fixed

- Windows: Fixed an issue that could cause playback to fail when using multiple instances of certain VST3 plug-ins
- Resolved an issue that could cause the message "Audio Unit Error" when instantiating some Audio Units plug-ins
- Resolved an intermittent error message that could occur when instantiating a multi-output plug-in
- Delete track option is once again available for individually selected tracks in the Tracks List context (right-click) menu
- Monitor mute button has been restored when in CORE AUDIO mode

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.7 – September 5, 2024

</div>

<div class="accordion__item-content">

### Installers

- [**Download This Version (macOS)**](https://builds.uaudio.com/apps/luna/LUNA_1_7_0_3657.tgz)
- [**Download This Version (Windows)**](https://builds.uaudio.com/apps/luna/LUNA_1_6_3_3565.zip)

### New

- **Multi-Output Plug-in Support**
  - LUNA now allows you to assign additional plug-in outputs to new multi-out channels in LUNA
  - Multi-out channels are MIDI-based, and allow you to route audio out of a plug-in and MIDI back in for multi-timbral workflows
  - The Multi-Out Mixer integrated in the plug-in window allows all basic channel workflow steps to occur within the plug-in
  - <a href="https://www.youtube.com/watch?v=wGTtIdn1_Ro&feature=youtu.be" rel="noopener noreferrer" target="_blank">Click here to watch the launch video</a>
- **Export Selected Tracks**
  - Quickly set up a new audio export based on just the selected tracks
  - With the desired tracks selected, right click and choose Export Selected Tracks or File \> Export Selected Tracks

### Improved

- The track name context menu has been reorganized

### Fixed

- Windows: Resolved an intermittent issue that could cause LUNA to become unstable after changing the buffer size or sample rate
- Windows: Resolved an issue that could cause a VOLT's buffer size to reset to 512 after relaunching LUNA
- Windows: Resolved a VST3_HostContext error message and potential crash that could occur when instantiating various third-party plug-ins
- Windows: Resolved a LUNA issue that could prevent Spitfire and other virtual instruments from passing audio if instantiated when creating an instrument track
- Windows: Resolved an issue that could cause floating windows from LUNA or UAD Console to appear over other applications
- Resolved an issue that caused floating windows to disappear if another application was focused, even when LUNA was still visible

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.6.3 – July 9, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_6_3_3565.tgz)

### Improved

- LUNA sessions on Windows can now be opened from File Explorer by double-clicking the Open Session shortcut inside the directory
- Ampex ATR-102 LUNA Extension Presets can now be filtered by Tags

### Fixed

- Resolved an issue that could cause overlapping text in the preset browser
- Resolved a crash that could occur when instantiating Steinberg's The Grand 3 instrument
- Resolved a crash that could occur when instantiating some Softube plug-ins on Windows

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.6.2 – June 25, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_6_2_3555.tgz)

### Fixed

- Resolved issues that could cause hangs and UI flickering when using ASIO devices after launching LUNA or changing sample rate or buffer size
- Resolved a VST3_HostContext error message and potential crash that could occur instantiating various third party plug-ins
- Resolved a windows-only issue that could prevent Spitfire and other virtual instruments from passing audio if instantiated as part of track creation
- Resolved an issue that prevented import of AIFF files on Windows
- Clicking the CUE OUTPUTS button if the window is already open now closes the window

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.6.1 – June 4, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_6_1_3527.tgz) 

### Fixed

- Resolved an issue that could cause Export Mixdown to fail when deactivated tracks were selected for export
- Significantly decreased the memory usage of LUNA Poly and LUNA Razor Blade Warp algorithms
- Resolved an issue that could cause some Native Instruments plug-ins to crash Windows LUNA when instantiating
- ASIO device channels now show correctly on the Settings \> I/O SETTINGS screen on Windows
- Resolved an issue that occurred in Windows LUNA when importing audio from an exFAT formatted drive
- Resolved a crash that could occur during offline mixdown on Windows
- Resolved a repeated "Driver_Windows_MidiIO" issue that could occur when launching LUNA on Windows
- The close button location for plug-in floating windows has been corrected on Windows

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.6 – May 21, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_6_0_3515.tgz)

### New

- **Windows Support**
  - LUNA is now available on Windows through an Open Beta
  - <a href="https://help.uaudio.com/hc/en-us/articles/26636829359252" rel="noopener noreferrer" target="_blank">Read the <strong>Windows Open Beta FAQ here</strong></a>

### Improved

- **Font Size**
  - The default font size has been increased
- **Drag and Drop to Remove Plug-ins**
  - Plug-ins can now be removed from their assigned insert by dragging and dropping outside of the INSERTS mixer row
- **Insert Bypass on Hover**
  - Plug-ins that support soft bypass can now be bypassed by clicking the "IN" button while hovering over a plug-in assignment
  - If a plug-in does not support soft bypass, the button is replaced with the power switch which enables or disables the plug-in
  - The contents of the "..." menu button that was replaced can be accessed by right-clicking or Control-clicking the insert
- **Unison Gain dB**
  - Unison insert gain is now always displayed

### Fixed

- Resolved an issue that focused the browser search field unexpectedly when clicking on a plug-in preset
- Resolved an issue that prevented CUE send meters from displaying signal level

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.5.5 – April 10, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_5_5_3477.tgz)

### New

- **Resizable UAD-2 Plug-ins**
  - Most UAD-2 plug-ins can now be resized by clicking the "..." menu in the window header and choosing a scale percentage
  - UAD Software 11.2 Required

### Improved

- **User Preset management**
  - Create additional user presets folders by right clicking in the presets list and choosing "New Folder"
  - Backup and reorganize your user presets by right clicking in the presets list and choosing "Show in Finder"

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.5.4 – March 13, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_5_4_3416.tgz%20:+1:%201)

### New

- **Play From Stop Location**
  - New Transport menu setting allows LUNA transport to have a pause-like behavior where playback continues from the last stop location
  - While Play From Stop Location is enabled, stop button turns into a a pause button
  - Shift + Spacebar shortcut toggles the behavior from the current setting as a one time option. Use this feature to keep a preferred default setting but have the option to stop in the alternate mode at any time
- **SSL 360 Link**
  - SSL 360 Link VST3 Plug-in now supported

### Improved

- Edit performance on tracks with many clips has been improved
- Clicking on Bar labels in the ruler now locates exactly to the bar regardless of SNAP setting
- Tape machine browser layout updated to better match INSERTS and CONSOLE browser\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.5.3 – January 17, 2024

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_5_3_3356.tgz)

### Improved

- Large LUNA sessions now use significantly less RAM

### Fixed

- Resolved an issue that prevented full screen mode from filling the entire screen
- Resolved group-related issues that could occur when adjusting LUNA Extension controls
- Resolved an issue which could cause loop recorded files to appear offline after using the Abort Recording feature
- Resolved an issue that caused automation edits to be undone when some third-party Audio Units plug-ins were instantiated in a session
- Resolved an issue that prevented audio from passing on tracks in ARM mode if there was a deactivated and soloed track in the session\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.5.2 – December 20, 2023

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_5_2_3323.dmg)

### Fixed

- Resolved an issue that could prevent undo from working and cause inconsistent clip, fade, and automation edit behavior
- Resolved an issue that could occur when using the Control Room section for Apollo interfaces
- Resolved an issue that prevented the FOLD feature from updating the range of visible notes

### Improved

- Deactivated tracks now show Hide and Show options
- The Activate License button is now displayed in the LUNA splash screen when no license is currently activated but a license is available\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.5.1 – November 30, 2023

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_5_1_3306.dmg)

### New

- **Deactivate Tracks**
  - Right click on a track name and choose "Deactivate"
  - Deactivated tracks free up all CPU, DSP, and memory usage related to channel processing

### Improved

- **Buffer Size Selection**
  - You can now choose a standard buffer size, from 32 to 2048 samples
- **Apollo Preamp Gain**
  - Gain dB Value is now displayed while adjusting
  - Double click gain knob to enter a precise dB value
- **Resizable Markers Lane**
  - The Markers ruler can now be expanded so performers can easily see song structure changes as they approach
- Page Up and Page Down keys now scroll the timeline by the visible area
- The ATR-102 LUNA Extension default preset is now more linear with higher headroom, to provide a cleaner starting point when importing mixed tracks into LUNA

### Fixed

- Resolved an issue that caused erratic performance of knobs on MCU surfaces
- Resolved an issue that could prevent sidechain connections from restoring correctly after reopening a session
- Resolved an issue that prevented use of the Tap Tempo button
- Resolved an issue that caused owned UAD-2 plug-ins to appear in the Inactive folder. License information for UAD-2 plug-ins is not available to LUNA when Apollo Interface Software is not installed.
- Resolved an issue that caused default preset and preset favorite assignments to be lost when trashing the LUNA workspace
- Resolved an issue with LUNA launch speed when the recent sessions list contained very large numbers of sessions

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.5.0 – November 9, 2023

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_5_0_3278.dmg)

### New

- **Host Computer Licensing**
  - As of November 9th (with **LUNA 1.5**), new LUNA licenses support **three simultaneous iLok USB** and **host computer authorization locations**.
  - Existing LUNA license locations are unchanged, but will transition over the next several months.\
    \
     
- **Demo Session**
  - Included Demo Session template highlights the power of LUNA Extensions on a full mix.
  - Click OPEN DEMO SESSION on the Create page to explore the mix.\
     
- **Assign Default Extensions**
  - Owned and Active Demo LUNA Extensions are now added to tracks by default in new sessions.
  - **New Tracks** and **Create Bus** dialogs let you configure per-session defaults.
  - Toggle **Assign Default Extensions** in **Settings \> Options \> Miscellaneous**.

### Fixed

- Resolved UADx display issues after reopening a session.\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.8 – September 27, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_8_3237.dmg" rel="noopener noreferrer" target="_blank"><strong>Download This Version</strong></a>

### New

- **MCU Control Surface Plug-ins Support**
  - Control Console, Tape, and any of the 8 Inserts directly from your MCU-compatible control surface with V-Pots
  - <a href="https://help.uaudio.com/hc/en-us/articles/4406796987540" rel="noopener noreferrer" target="_blank">Click here to learn how to access Plug-ins controls on your surface</a>

### Improved 

- **Running LUNA Offline (iLok USB Required)**
  - LUNA now runs reliably without internet while using an iLok USB
  - LUNA launch will no longer be blocked if there is an issue communicating with UA Connect, www.uaudio.com, or ilok.com as long as there is already a LUNA license present
- **SSL UC1/UF8/UF1 Integration**
  - Enhanced VST3 DAW integration for 360 v1.6 release (October 10th)
  - Requires SSL 360 v1.6 and all updated SSL 360 enabled plug-ins coming October 10th

### Fixed

- Note Off midi data is now treated the same as Note On (Velocity 0) when using MCU peripherals. This may improve usability of LUNA with Streamdeck peripherals

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.7 – August 8, 2023

</div>

<div class="accordion__item-content">

### Installer

- [**Download This Version**](https://builds.uaudio.com/apps/luna/LUNA_1_4_7_3152.dmg)

### New

- **Trash Unused Audio**
  - Click File \> Trash Unused Audio... to check the session for files that are no longer used and move them to the trash

### Improved

- **Instrument plug-in assignments are now displayed in the Timeline track header**
  - Click the assigned instrument to show or hide the plug-in window
  - Right click the assigned instrument to reassign
- Context menu items now show keyboard shortcuts for listed commands if applicable

### Fixed

- Resolved an issue that could prevent full capture of very low volume audio when freezing tracks
- Metering, Clip Hold, Peak Hold, and Controls Mode settings are now saved properly when UAD Software / Apollo Thunderbolt Driver is not installed
- Resolved an issue that prevented Option+clicking a fader in LUNA from also resetting the Console 1 fader to default
- Resolved an issue that caused a preset to be loaded unexpectedly when changing the favorite status\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.6 – July 13, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_6_3123.dmg" rel="noopener noreferrer" target="_blank"><strong>Download This Version</strong></a>

### New

- **Softube Console 1 & SSL UC1 Support**
  - Softube Console 1 and current SSL 360° plug-ins now load as VST3, enabling these control surfaces for deeper plug-in and track control
  - Control LUNA faders, mutes, solos, and sends 1-3 from Softube Console 1 control surfaces by inserting the Console 1 plug-in

### Improved

- The icon that opens the navigation sidebar has been changed from the UA diamond logo to a more recognizable options menu icon

### Fixed

- Resolved several issues related to open plug-in window position and appearance when adding, removing, or re-ordering plug-ins
- Resolved an issue that prevented sessions from restoring the FIXED SLOTS mixer view setting after quitting LUNA
- Resolved an issue that could cause send and cue volume knobs to remain visible after removing a send or closing the mixer row
- Resolved a hang that could occur when editing automation, midi, or warp data\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.5 – June 21, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_5_3094.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **Mix Bypass Panel**
  - Bypass all extensions, all inserts, or all mix processing using the BYPASS panel in the LUNA Monitor section to quickly A/B the effect of processing on your session

### Improved

- **Assign any Console Extension to any Track Type**
  - API Vision Channel Strip can now be assigned to the CONSOLE slot on buses and MAIN
  - API 2500 can now be assigned to the CONSOLE slot on audio and instrument tracks
- **New Track Creation Tape Assignment**
  - Tape Machines and Master Tape can be assigned when creating tracks and buses

### Fixed

- Resolved an issue that could cause LUNA to scan the factory VST2 plug-ins folder if no UAD plug-ins were installed, causing launch issues on some systems
- Command+W keyboard shortcut once again closes plug-in windows\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.4 (Supplemental Build 3043) – May 4, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_4_3043.dmg" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved an issue where Oxide tape was automatically assigned to new audio tracks
- Resolved an issue when creating a new audio or instrument track where Console assignment was labeled incorrectly\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.4 – May 3, 2023

</div>

<div class="accordion__item-content">

### Fixed

- Resolved an issue that prevented expanding and collapsing routing categories in the track routing browser
- Resolved an issue that prevented Command+clicking to assign multiple outputs in the track routing browser
- Resolved a crash that could occur after making a selection in the track routing browser
- The playhead is once again visible in the Universe view in the Mixer panel
- Restored the ability to swipe-drag across IN/EQ/DYN buttons on API Vision Channel Strip console
- Restored the ability to vertically scroll a channel using Mixer section labels\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.3 – April 27, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_3_3034.dmg" target="_self"><strong>Download This Version</strong></a>

### Improved

- **Redesigned Graphics System**
  - Overhauled drawing and animation code
  - Substantially improved GPU performance\
    **Note:** This should prevent fans from ramping up unexpectedly. Keep us informed with the Feedback button!

### Fixed

- Resolved an issue that could prevent output re-assignment after switching between Core Audio and Apollo mode
- Resolved an issue that could prevent presets from saving in certain Audio Units plug-ins such as Sound Radix Auto-Align 2\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.2 (Supplemental Build 2997) – March 30, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_2_2997.dmg" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved an issue that could cause unexpected Import Audio behavior after closing the Import Audio dialog\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.2 – March 29, 2023

</div>

<div class="accordion__item-content">

### Installer

### Improved

- When Importing Session Data, TEMPO & TIME SIGNATURE and MARKERS settings are no longer selected by default
- When LUNA cannot save Audio Units plug-in user presets due to a folder permissions issue, LUNA now shows a warning message

### Fixed

- Resolved an issue that could occur when selecting Sonnox ListenHub as a device in Core Audio mode
- Resolved an issue that could prevent adding or editing warp markers after switching a track between Time and Tempo mode
- Resolved a preset query error message that could occur when using UAD-2 plug-ins
- Resolved an issue with Import Session Data that could show an error message when importing tracks without Track Settings or Audio & Track Versions
- Resolved an issue that prevented a renamed version from immediately displaying in the Session Versions window
- The Input Monitoring button on the track controls now displays the correct status when ARM-enabled\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.1 – March 7, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_1_2967.dmg" target="_self"><strong>Download This Version</strong></a>

### Improved

- Color chip added to meters in the Mixer view meter bridge
- Progress is now more accurately displayed when opening large sessions

### Fixed

- Resolved an issue that could disconnect a sidechain route when changing from no output or removing all outputs from a track
- Resolved an issue that could prevent switching out of Core Audio mode after launching LUNA, when LUNA was launched by double-clicking a LUNA session package
- Resolved an issue that could cause duplicate API Vision console inserts to appear after copy and pasting console settings, and prevent these inserts from being removed
- Resolved an issue that prevented restoring custom names of inputs and outputs in aggregated audio devices
- Resolved an issue that prevented mixer view scrolling after duplicating a track using option + click and drag
- Resolved an issue that prevented RODECaster Pro II device from being selected in Core Audio mode
- Resolved an issue that could cause plug-in copy and paste to paste the plug-in with default values
- Resolved an issue that prevented expanded tape controls view from restoring in the mixer when reloading a session
- Resolved an issue that could prevent moving plug-ins with over 1024 parameters (for example, Valhalla FreqShifter) from one plug-in slot to another

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.4.0 – February 15, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_4_0_2944.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **(Open Beta) macOS Core Audio Device Support**
  - Please send your feedback so we can work together to improve stability and performance before the next big announcement
  - Use LUNA when Apollo is not connected
  - Use any Core Audio device, or aggregate multiple devices on the fly
  - Use any device output as your Monitor output
  - Use any device outputs as integrated Cues
  - Automatic I/O mapping preserves session routing when switching devices

<!-- -->

- **(Open Beta) Buffer Size Setting**
  - Choose Small, Default, or Large buffer options
  - Use Small or Default for lower latency while recording, or Large to run more plug-ins while mixing

<!-- -->

- **Automatic Conversion Between UAD-2 and UADx Plug-Ins**
  - When enabling ARM, your UADx plug-ins automatically switch to your UAD-2 versions, and vice versa
  - Click the + icon in any UAD plug-in to easily switch between your DSP or CPU versions
  - Click Mixing \> Convert to quickly switch your UAD plug-ins to the desired processing type

<!-- -->

- **Import Session Data**
  - Press Option + I or click File \> Import Session to choose a session from which to import data
  - Select a recent session or any of its other versions or bookmarks, or open a session from disk
  - Use the Import Session Data browser to configure various import options and preview the import results
  - Add or match tracks to existing tracks, choose which session data to import, and configure how track data is added or merged with existing data
  - Import only a specific range of the timeline using the Import Range ruler

### Improved

- In the Versions list on a track, hovering over a long track version name now displays the full name as a tooltip

### Fixed

- Resolved an issue that prevented Send automation from appearing in the browser until a session was reopened
- Resolved an issue that could cause fader taper graphics to reset when opening a session
- LUNA Documentation link in the HELP menu once again directs to the LUNA application manual\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.3.2 – January 17, 2023

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_3_2_2898.dmg" target="_self"><strong>Download this version</strong></a>

### New

- **Resizable UADx Plug-ins**
  - Click ••• in the right corner of a UADx plug-in or instrument window and choose a scale to resize all instances of that plug-in or instrument
  - Choose Apply to All to resize all UADx plug-ins and instruments to that scale
- **Additional Click Sounds**
  - Choose from a number of popular click sounds from the Click popover

### Improved

- **Reverse Audio**
  - Reverse command added to the Edit menu
  - Use Control + Shift + R to reverse selected audio clips
- **Loop Toggle**
  - Command + L now toggles loop mode and updates the loop to match the current selection
- Categories section of Inserts browser now opens by default
- Clicking Track Mode now toggles between TIME and TEMPO mode instead of opening a menu

### Fixed

- Resolved an issue that could cause unexpected "device configuration changed" messages and session reloading
- Resolved an issue that could cause render performance issues on macOS versions prior to Big Sur
- Resolved an issue that prevented frozen tracks in templates from being unfrozen. Re-save your templates that include frozen tracks to restore the correct behavior\
  \
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.3.1 – December 13, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_3_1_2861.dmg" target="_self"><strong>Download This Version</strong></a>

### Improved

- Improved render performance on systems with macOS 11 Big Sur and newer

### Fixed

- Resolved an issue that could cause doubled processing of API Vision Channel Strip Extension when a track is in ARM mode
- Resolved an issue that could cause an error when attempting to replace a template
- Resolved an issue that caused inaccurate counter values when a manual counter entry started with a 0
- Resolved an issue that could cause only a single Record FX slot to be visible in the Focus channel
- Resolved an issue that could cause long load times in sessions with large amounts of Warp markers\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.3 – November 08, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_3_0_2817.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **macOS Ventura Compatibility**
  - LUNA is now compatible with macOS 13 Ventura
- **Track Freeze**
  - Freeze button renders audio, instruments, extensions, and plug-ins as uneditable audio and deactivates all processing
  - Click ••• on any insert and choose "Freeze Up To This Insert" in order to render as audio and deactivate plug-in and extension processing up to that point in the track
  - Click the highlighted Freeze button to unfreeze a track
- **Plug-in Favorites**
  - You can now favorite plug-ins and instruments in their respective browsers by clicking the star to the right of the item name. Click Favorites at the top of the plug-in or instrument browser to view only favorites
- **Plug-In and Instrument Default Preset**
  - Right click on a preset in the preset browser for a plug-in or instrument, and choose "Set Default Preset" to set the default preset, which loads automatically when the plug-in is instantiated

### Improved

- **Focus Channel**
  - Focus channel now shows and hides track items independently of the settings in Mixer view
  - Right-click on the row header in the Focus channel and choose Navigation... to configure Focus channel view settings
- **Custom names** in the Export Mixdown settings are now stored with the session

### Fixed

- Resolved an issue that prevented saving of presets with quotation marks in the name\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.13 – October 11, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_2_13_2771.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **MCU: Single Sends and CUEs V-Pot Mode**
  - Press and hold designated SENDS or CUES v-pot assign buttons and then press down on the designated encoder to cause all v-pots to display a given send or cue
- **MCU: Expanded Sends and Cues V-Pot Mode**
  - MCU surfaces with V-Pots can now show expanded controls for the selected track's sends and cues
  - Press the designated send or cue mode button on your MCU surface to cycle through send and cue overview and detail pages that allow control of all parameters for the selected track\
     
- **MCU: Flip Faders**
  - MCU surfaces with Flip functionality can now swap the LUNA controls displayed on the V-Pots with those on the faders

### Improved

- **Recording**
  - Clicking the transport Record button begins recording, including count-in if enabled
  - If no tracks are record-enabled, any selected tracks are automatically record-enabled
- Significantly improved offline bounce times
- Multiple selected clips can now be trimmed
- Duplicating tracks now automatically selects the newly created tracks

### Fixed

- Resolved an issue that could cause MIDI Clock timing issues on macOS Monterey
- Resolved an issue that could cause playback artifacts across MIDI clip boundaries when such clips included large amounts of controller data
- Resolved an issue that could prevent Bar numbers from drawing at certain zoom levels in some sessions
- Resolved an issue that caused Native Instruments RC48 to display incorrectly
- 7 character MCU scribble strips now show only one decimal place
- Improved display of Bar and Beat values in the SSL 360 application\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.12 – September 12, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_2_12_2733.dmg" target="_self"><strong>Download This Version</strong></a>

### New

**Native Apple Silicon Support**

- LUNA, LUNA Extensions, and UAD Instruments run natively on Apple M1/M2 processors\
  **Note:** UAD Instruments (Shape Expansion and Spitfire Audio) require updates for native Apple silicon. Check the manage page in the LUNA sidebar and update if needed.

### Improved

- Improved system performance when importing or editing large amounts of MIDI data
- Double-clicking the loop region in the loop ruler now toggles loop mode

### Fixed

- Resolved an issue that could prevent LUNA from relaunching UA Connect on launch
- Resolved an issue that prevented using LUNA offline after logging in previously with an iLok USB present
- Resolved an issue that could prevent LUNA from restoring with the last used window size
- Resolved an issue that could cause certain sessions to restore without the last used View settings
- Resolved an issue that could prevent saving a Waterfall B3 or Opal preset
- Resolved an issue that prevented Oxide UAD-2 plug-in user presets from appearing in the Oxide Tape preset browser
- Resolved an issue that prevented changing Oxide Tape extension presets
- Export Mixdown file names list once again responds to Command + up/down arrow keyboard shortcuts to navigate through the list
- Resolved a licensing issue that could occur when launching LUNA if the user's iLok cloud session was open on another computer\
  \
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.11 – August 3, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_2_11_2684.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **Categorize Audio Units Plug-ins**
  - Click the "+" button in the plug-in window header and click Categories to categorize your Audio Units plug-ins (many plug-ins are already categorized)

### Improved

- Track Routing browser has been updated with improved graphics and usability

### Fixed

- Resolved an issue that could cause LUNA to stop responding after adjusting controls in some Audio Units plug-ins
- Resolved an issue that could cause LUNA to stop responding when opening a session that contained the Output Movement plug-in
- Plug-in Categories now appear when browsing Record FX
- Resolved an issue that could prevent Ravel and Minimoog from appearing in the LUNA manage page after purchase
- UAD-2 plug-in ownership status is now displayed when assigning Unison and Record FX plug-ins
- Resolved an issue that prevented API Vision Console controls from appearing to update after Option + clicking on the controls in the Console row
- Resolved an issue that could display presets from the previous plug-in after switching a Unison or Record FX plug-in\
  \
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.10 – July 12, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_2_10_2649.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **Plug-in Categories for UADx and UAD-2**
  - Plug-in categories now allow you to filter UADx and UAD-2 plug-ins by processor type (requires latest UADx plug-in updates)

### Fixed

- Resolved an issue loading sessions with Output Movement and possibly other plugins that check for timeline information on instantiation
- Resolved an issue that could cause the system to stop responding while editing MIDI CC data
- Simple Pan setting is now copied when using the Duplicate Track command
- Create Fades now creates crossfades on clips edited together by using Shift + Delete
- Resolved an issue that could remove crossfades when changing clip gain or pitch on a contributing clip\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.9 – June 22, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_2_9_2627.dmg" target="_self"><strong>Download This Version</strong></a>

### Improved

- **Session Versions and Bookmarks**
  - Improved text and layout for versions and bookmarks in the OPEN VERSION window
  - Right click on a session in the CREATE page recent list to open a version or auto-backup
  - Check "SHOW AUTO-BACKUPS" in the Session Versions window to see any automatically saved sessions
  - "Revert To" on File menu now shows revert points and auto-backups
  - Switching between bookmarks and versions never prompts to save changes. Changes are always saved and prior states are always kept as auto-backups.
  - Session states prior to loading a bookmark are now labeled with the time and date and a note to indicate the purpose of the revert point
- **Bus Duplicate**
  - "Duplicate" Creates a new duplicate bus and updates all source tracks to include routing
  - "Duplicate Without Content" Creates a new duplicate bus without any source track routing
- **Favorite Plug-in Presets**
  - Plug-in preset favorites now work for UAD-2 plug-ins in the Unison and Record FX insert slots

### Fixed

- Resolved an issue that could cause the undo queue to become stuck after interacting with certain plug-in GUIs
- Resolved an issue that could prevent "Revert to Last Opened" from working more than once in a session
- Resolved an issue that could cause the Skip button on the log in page to appear inactive when an iLok USB with LUNA license was present. If issue exists, launch UA Connect to update
- Resolved an issue that caused Marquee Zoom to unexpectedly reduce track height when there were hidden tracks in a session
- Resolved an issue that prevented the Write and Trim Control Value shortcuts from working on a German keyboard layout
- Resolved an issue that could prevent moving of multiple selected clips when tracks were hidden
- Resolved an issue that prevented track names from displaying in FabFilter Pro Q3 Internal Sidechain\
  \
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.8 – May 24, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/apps/luna/LUNA_1_2_8_2584.dmg" target="_self"><strong>Download This Version</strong></a>

### New

- **Write Control Value**
  - Command + /: Write Control Value command opens a popover with the current value of the control for the displayed automation lane. Enter a value and press return to write a breakpoint or new range within the selection using the value
- **Trim Control Value**
  - Command + Option + /: Trim Control Value command opens a popover with the current value of the trim fader for the displayed volume lane. Enter a value and press return to trim the current volume level by the entered amount
- **Marquee Zoom**
  - Option+Click and drag in Tracks view to zoom to a selection. Option+Click to step back through the previous zoom levels
  - Horizontal zoom buttons along with the new marquee zoom button are now located at the bottom right of the tracks in the Timeline

### Improved

- Instrument plug-in selection during new track creation is now remembered

### Fixed

- Resolved an issue that could cause undo to restore incorrect values on automation when restoring the first automation breakpoint
- Shift Clicking an Insert tile once again replaces the current plug-in window with the newly clicked one
- Resolved an issue that caused CUE and Send levels in fader view to display at inaccurate levels on tracks routed to Neve or API summing buses\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.7 (Supplemental Build 2564) – May 4, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v127x_dhq7q/LUNA-v1.2.7.zip" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved an Export Mixdown issue in specific sessions\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.7 – April 27, 2022

</div>

<div class="accordion__item-content">

### Installer

### New

- **Preset Favorites**
  - Presets for all plug-ins can now be set as favorites and the preset list can be filtered to show only those favorite presets
- **UADx Preset Tags**
  - Tags and Categories are now available for UADx and UAD Instrument presets

### Improved

- **Plug-in Window Performance**
  - Significantly improved plug-in windows design to fix numerous display and responsiveness issues
  - "Channel Strip View" feature has been removed from plug-in windows
- The most recently used Export Mixdown settings in a session are now stored
- Improved control surface automation writing for track groups
- Improved performance of audio analysis and transient detection algorithm
- Improved the functionality of "FIT" mode on Instrument Tracks to better show all MIDI notes while editing
- Improved responsiveness of the the MIDI Piano Roll scroll zoom handles
- Browser view now updates to show the selected track in a group

### Fixed

- Resolved an issue that could prevent UAD-2 Plug-ins from appearing if the UAD v10 Software update failed to remove the previously used "Powered Plug-ins" folder from the system
- Resolved an issue that could cause factory presets to disappear for UADx plug-ins and UAD Instruments after launching LUNA and installing or updating a plug-in
- Resolved an issue that could cause an inaccurate Update Available count on the MANAGE button on the LUNA Manage page
- Resolved an issue that could create unexpectedly large session files when importing an AAF
- Tape track extensions are now edited according to REMOVE and COPY channel modifier operations
- Resolved an issue that caused empty tape machine LUNA extension preset lists when clicking on the track tape slot buttons\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.6 – March 30, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v126x_6hapf/LUNA-v1.2.6.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **UADx Support**
  - LUNA now supports UADx plug-ins
  - New UADx folder shows plug-ins you can use right away
  - New UAD-2 folder shows UAD-2 plug-ins you can use right away
  - New Universal Audio (Inactive) folder shows plug-ins that have expired demos
- **UA Connect**
  - LUNA v1.2.6 requires UA Connect v1.1
  - UA Connect will be installed automatically when the LUNA update completes
  - UA Connect manages installation, licensing, and updates for UADx and LUNA Extensions
- **UAD v10.0 Required**
  - LUNA v1.2.6 requires UAD v10.0 to launch. Visit <a href="https://www.uaudio.com/downloads" rel="noopener noreferrer" target="_blank">uaudio.com/download</a> to get the latest software.

### Improved

- LUNA v1.2.6 will automatically install iLok License Manager 5.5 if needed

### Fixed

- Resolved an issue that could prevent Auto-Tune Realtime parameter changes from taking effect while in ARM mode (requires UAD Software v10)
- Resolved an issue that could cause a sample rate mismatch between LUNA and Vienna Ensemble Pro
- Resolved an issue that could prevent clip gain and pitch returning to default settings when using Option + Click with multiple clips selected
- Resolved an issue that could mute the MAIN bus when soloing a sidechained track if the sidechain source was not also routed to the MAIN bus\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.5 – January 26, 2022

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v125x_40jca/LUNA-v125.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Quantize Audio**
  - Audio clips can now be quantized to the grid using the Quantize command
  - "Q" button now appears on audio clips. Click to access the Quantize browser
  - All existing Quantize browser features now function for transients by snapping the audio event nearest to the grid into alignment
  - New "RANGE" control specifies the area around a grid value within which events will be quantized, allowing control over the extent of quantization (RANGE control has also been added for MIDI quantize operations)
  - New group Track Priority feature allows quantization to be driven by specified tracks in a selection or group, ensuring that desired instruments in a multi-microphone recording are snapped to the grid, while preserving phase alignment on related tracks
- **Align Grid Command**
  - Use Align Grid to calculate a tempo map to the cursor position at a resolution matching the current grid setting
  - Option + Command + I: Align Grid
  - Shift + Option + Command + I: Align Bar

### Improved

- Significantly improved performance for Razor Blade and UA Polyphonic warp algorithms
- Sidechain input assignment is now assignable for groups of tracks when the track group MIXING option is enabled

### Fixed

- Resolved an issue that could cause playback of MIDI Pitch Bend data to sound different than when originally performed
- Resolved an issue that could prevent some LUNA Extension and UAD Instruments presets from reloading correctly
- Resolved a crash that could occur when downloading instruments to an external drive on M1 Mac computers
- Resolved an issue that could cause undo queue issues after writing automation from a control surface
- Resolved an issue that prevented Command + Clicking the Console alias in the INSERT mixer row from toggling between Enabled / Disabled
- Resolved an issue that caused some characters to be silently dropped from an exported file name
- Resolved an issue that prevented all tape slots from updating when holding Option and toggling Tape power in the mixer
- Resolved an error message that could occur when loading Audio Units plug-ins made by Neural DSP\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.4 – December 15, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v124x_o0pze/LUNA-v124.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Insert In/Out (Bypass)**
  - Automatable In/Out control for UAD2 and Audio Units plug-ins that have implemented an internal power or bypass parameter
  - "IN" button in plug-in window header allows easy access to A/B the effect of any insert without any glitch or delay
  - Command + Click on an insert to toggle In/Out (Bypass)
  - Control + Command + Click on an insert to toggle Enabled/Disabled (Power)

### Improved

- Sessions load times have been significantly improved
- Improved playing or recording new sustain pedal changes while performing over an existing recording in MIDI Merge mode

### Fixed

- Resolved an issue that caused stereo plug-ins by Fuse Audio Labs to crash upon instantiation
- Resolved a crash that could sometimes occur when putting the computer to sleep or waking it up from sleep while LUNA was running
- Resolved an issue that prevented restoration of VIEW settings for the Timeline and Mixer
- Resolved an issue that could cause undo queue issues after writing automation from a control surface
- Resolved an issue that could cause trimming of a discrete automation segment near the beginning or end of a clip to unexpectedly change the value of automation for the entire clip
- Resolved an issue that could cause MIDI notes to continue playing back after being deleted\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.3 (Supplemental Build 2357) – November 16, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v123x_wwbeo/LUNA-v123.zip" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved a random crash that could occur during playback in rare cases when using a control surface
- Resolved a crash that could occur while using RealVerb-Pro (requires UAD Software 9.15)\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.3 – November 11, 2021

</div>

<div class="accordion__item-content">

### Installer

### New

- Shift + R keyboard shortcut toggles SPILL for selected buses

### Fixed

- Resolved an issue that could cause Record FX plug-ins to lose preset assignments when reloading the session (requires UAD Software v9.15)
- Resolved a crash that could occur instantiating Softube Vocoder while in ARM mode (requires UAD Software 9.15)
- Resolved an issue that prevented Softube plug-in volume meters from working while in ARM mode (requires UAD Software 9.15)
- Resolved an issue that prevented VU meters in the Valley People Dyna-mite plug-in from functioning in ARM mode (Requires UAD Software 9.15)
- Resolved an issue that prevented proper recording of MIDI data from the Alesis Nitro drum module
- Resolved an issue that could cause MIDI clock output jitter when using negative offsets
- Resolved an issue that prevented importing of AAC files that were labeled incorrectly with the MP3 file extension
- Resolved an issue that could result in fades being locked in place after moving and trimming a clip
- Resolved a crash that could occur after changing track views\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.2 – October 20, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v122x_a8rei/LUNA-v122.zip" target="_self"><strong>Download This Version</strong></a>

### Improved

- New session names that are typed before choosing a template are now retained during session creation

### Fixed

- Resolved an issue that could cause a crash when using SynchroArts VocAlign Ultra
- Resolved an issue that could prevent editing of automation, clips, or track positions after playing back audio through some third party Audio Units plug-ins
- Resolved an issue that could prevent undo of API Vision control changes while the browser was open with the search field focused
- Resolved an issue that could cause the automation value tooltip to show the wrong value when trimming an automation line segment
- Resolved an issue with Behringer X-Touch One next/prev channel selection that prevented moving beyond a range of 8 tracks at a time
- Resolved an issue that caused the Presonus FaderPort 16 to bank by only 8 tracks at a time
- Resolved an issue that could cause clip gain and pitch to unexpectedly change on subsequent segments of an overlapped clip
- Resolved an issue that prevented LUNA from auto-scrolling when using the tracks browser to select tracks in a group
- Automation modes are now correctly displayed for spilled bus tracks on a Focus Module
- Resolved an issue that prevented the Log In button in the LUNA navigation bar from updating after a successful log in
- Resolved an issue that caused incorrect fader taper values when using V-Control with V-Console running in the Mackie Control profile\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2.1 – September 30, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v121x_q0fje/LUNA-v121.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **MCU Extender Support**
  - Set up SSL UF8 and Behringer X-Touch "Extenders" using the new "EXTENDER" checkbox in controller settings
  - This setting resolves an issue that caused blank text scribble strips on devices that require extender mode
- **Send and Insert Track View Info**
  - Track View labels now show send and insert number information before parameter names
- **Send and Insert Automation Tooltip Info**
  - Track parameter tooltips in timeline view now show send and insert number information as well as plug-in name before parameter names and values

### Improved

- Sidechain Input trim is now automatable
- Improved fader taper accuracy for Neyrinck V-Control and Behringer X-Touch One

### Fixed

- Resolved a crash that could occur when adding a sidechain input to an instrument track in ARM
- Resolved an issue that could prevent Presonus FP2 Prev / Next channel selection from moving through tracks in an active track group
- Resolved an issue that prevented single fader surfaces from displaying a spilled channel selected in LUNA
- Resolved an issue that would revert the first channel's pan to the center when pressing the fifth channel pan knob
- Resolved an issue that could cause Prev / Next channel navigation on the Presonus FP2 to skip backwards in some cases
- Resolved an issue that could prevent Presonus FP2 Prev / Next channel selection from moving through tracks in an active track group
- Resolved an issue that caused duplicate entries to appear for all V-Control virtual MIDI ports\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.2 – September 15, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v120x_djaa8/LUNA-v120.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Sidechain Input**
  - New Sidechain utility feature allows assignment of a persistent sidechain input per track/bus
  - Sidechain directly from Console emulations (API Vision Channel Strip / API 2500) or any capable Audio Units plug-in
  - Sidechain trim allows you to adjust the sidechain source track level
  - Sidechain Solo allows you to temporarily listen to the sidechain source
- **MCU Control Surface Support**
  - Control LUNA using any control surface that implements the Mackie Control Universal protocol
  - Configure up to 6 MCU compatible control surfaces on the new CONTROLLERS tab of the SETTINGS page
  - Dedicate a single fader controller as a "Focus Module" that always follows the LUNA Focus Channel based on track selection
  - Use your surface to change volume and pan, toggle mute, solo, and record enable for every track in your session
  - Spill Bus track sources onto the surface using the record enable button
  - Change automation modes for selected tracks so fader moves can easily be recorded during playback
  - Control LUNA's transport controls and toggle looping and click
  - Access many additional controls using common surface features like zooming, scrolling, and much more
  - <a href="https://help.uaudio.com/hc/en-us/articles/4406796987540" rel="noopener noreferrer" target="_blank">Click here to learn more</a>

### Improved

- LUNA v1.2 will automatically install iLok License Manager 5.4
- Copy to CUES and Copy to SENDS command now works based on the track selection instead of all tracks
- Using keyboard shortcuts to extend the track selection now scrolls the timeline view when necessary
- Focus Channel now shows the last selected track in a selection of tracks and switches to any clicked track in an edit group where all tracks are selected

### Fixed

- Resolved an issue that could cause Console channels in ISOLATE mode to stop passing audio when opening a session with a soloed track
- Resolved an issue that prevented renaming a template
- Resolved an issue that could prevent quantize settings from being shared between session versions
- Resolved an issue that prevented timeline selection on bus tracks that were at Mini or smaller track heights
- Command + Up/Down arrow no longer fails to change the track focus when renaming tracks with the track color picker open
- Tracks now retain their current track view when duplicated\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.11 (Supplemental Build 2206) – August 12, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v1111x_5ja8s/LUNA-v1111b.zip" rel="undefined" target="_self"><strong>Download This Version</strong></a>

### Fixed

-  Removed inadvertent development graphics\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.11 – August 11, 2021

</div>

<div class="accordion__item-content">

### Installer

### New

- **Apple Silicon Rosetta Compatibility**
  - LUNA Recording System, UAD Instruments, and LUNA Extensions are now compatible under Rosetta with Apple Silicon M1 Macs
  - For details, please visit the <a href="https://help.uaudio.com/hc/en-us/articles/360057137692-Apple-Silicon-M1-Compatibility-Info" rel="noopener noreferrer" target="_blank">M1 Compatibility article</a>

### Improved

- Improved display of Trim, Fade, and Grabber tools for very small clips when zoomed out to make it easier to grab a clip and harder to accidentally trim or fade
- At the smallest track heights the edit tool available for clips has changed from the selector tool to the grabber tool
- In the Versions list on a track, hovering over a long track version name now displays the full name as a tooltip
- The mute command now automatically separates and mutes the selected area of a clip
- Export Mixdown browser list now shows track color and type, and allows click and drag in source checkboxes to quickly select multiple items
- Space bar now starts and stops the transport instead of entering a blank space while any numeric field, such as Tempo, is in focus
- A preset name in the preset browser displays in italics when the preset settings have been changed

### Fixed

- Resolved a crash that could occur downloading products in the MANAGE page
- Resolved a crash that could occur transferring audio to Melodyne if there were any plug-ins before it in the processing chain
- Resolved an issue that could cause the ATR-102 PRE LED to display the wrong state
- Resolved a crash that could occur when switching instrument plug-ins to or from various AIR Music Technology instruments while a plug-in window was open
- Resolved an issue that could prevent copy and paste of plug-in settings between Audio Units plug-ins using the plug-in window toolbar\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.10 (Supplemental Build 2161) – July 15, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v1110x_73gks/LUNA-v1110b.zip" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved an issue that caused the render meter to show inaccurate CPU usage while in ARM mode\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.10 – July 14, 2021

</div>

<div class="accordion__item-content">

### Installer

### New

- **Undo/Redo Command Names**
  - Command names now appear in the Edit menu for Undo and Redo actions
- **Mixer Arrow Key Scrolling**
  - Up or Down arrow keys scroll the mixer vertically to the previous or next mixer row
  - Left or Right arrow keys horizontally scroll the mixer horizontally by one track
  - Command + Left or Right arrow keys scroll the mixer horizontally by one "page"
  - Option + Command + Left or Right arrow keys scroll the mixer horizontally to the far left and far right
- **Default Activation Location**
  - Choose whether LUNA activates its software licenses to iLok cloud or a connected iLok USB

### Improved

- Click and dragging track function switches across tracks in the mixer and timeline now scrolls the window
- Buses with MIDI-capable effects can now receive MIDI from Instrument tracks
- Added bulk operations and context menu items to make modifications to all slots in the INSERTS row
- LUNA v1.1.10 will automatically install iLok License Manager 5.3.3

### Fixed

- Resolved an issue that could cause the order of the API Vision Channel Strip extension to change after reopening a session
- Resolved an issue that could prevent display of API Vision Channel Strip meters after using Revert To
- Resolved crashing that could occur when a MIDI device was added or removed during offline bounce, including those that could be created by plug-ins
- Resolved an issue that prevented pre-fader sends from passing signal when a muted track was in ARM mode
- INSERT and TAPE assignments in an alternate window no longer follow track selection from the main window
- Changing the Headroom control in the HARDWARE tab of the SETTINGS now successfully updates the setting in CONSOLE
- Resolved an issue that could cause inaccurate transfer of fader and pan settings using Copy to Cues in a group
- Resolved an issue that could cause inaccurate fader and pan settings using Copy to Cues in a group\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.9 – June 14, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v119x_29fhz/LUNA-v119.zip" rel="undefined" target="_self"><strong>Download This Version</strong></a>

### New

- **Nudge Editing**
  - Use nudge command to make small timing adjustments to clips, MIDI notes, selections, and the playhead
  - Nudge settings can now be accessed in the Edit Workflow toolbar
  - Nudge settings can now also be accessed by Right-clicking on an audio clip or midi clip
  - Nudge settings can now be set to follow the grid settings
  - Nudge settings can now be set to nudge to the grid, beats and bars, note divisions, milliseconds, samples, and ticks
  - Keyboard commands for Nudge Editing are listed in the article <a href="360041651392-Default-LUNA-Keyboard-Shortcuts-and-Menu-Reference-macOS.html#nudge" rel="noopener noreferrer" target="_blank">Keyboard Shortcuts and Menu Reference</a>
- **Select All Tracks Command**
  - Shift + Command + A selects all tracks in the session
- **Delete Selected Tracks Command**
  - Shift + Command + delete deletes selected tracks

### Improved

- Added CONSOLE assignment option to the Create Bus popover. Option + Command + Up/Down cycles CONSOLE options
- Improved mouse target areas for dual-concentric API 550L EQ Frequency and Gain knobs
- Added Transformer modeling to the ATR-102 Master Tape recorder LUNA Extension
- Added file import support for FLAC (.flac) and Apple Lossless Audio Codec (.caf or .m4a)
- Grid Value Shift + and Shift - shortcuts now work on the numeric keypad
- Command + = shortcut now toggles between timeline/mixer view on the numeric keypad

### Fixed

- Resolved an issue when duplicating tracks that could cause track version order to change
- Resolved an issue that could prevent the space bar from starting playback while a browser was open with no search string entered
- Resolved an issue that could cause an error when switching between bookmarks in a Session Version
- Resolved "unable to touch control" error messages that could occur when adjusting API Vision Console Emulation channel strip settings
- Resolved an "unable to touch a control" error that could occur when adjusting Pan controls
- Resolved an issue that prevented reloading the current I/O Matrix Preset if it was modified since loading
- Resolved an issue that prevented TAPE assignments from restoring correctly when undoing a Convert to Stereo command
- "PRE" and "MUTE" buttons are no longer missing on MAIN track CUE sends in expanded view
- Resolved a crash that could occur when holding the Esc key during launch
- Resolved an issue that prevented import of very long MP3 files
- Resolved an issue that prevented the correct tape reel graphics from appearing in the Tape browser
- Resolved a graphical issue with window title text in Alternate Windows
- Arrow key transposing of MIDI notes no longer fails when the Track Versions area is visible
- Resolved an issue that caused persistent inaccurate product download and update status on the MANAGE page\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.8 (Supplemental Build 2079) – May 24, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v118x_7477d/LUNA-v118b.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **UAD Software Requirements** <a href="https://www.uaudio.com/uad/downloads/" rel="undefined" target="_self"><strong>(download now)</strong></a>
  - UAD v9.14.5 (macOS 10 Mojave or Catalina)
  - UAD v9.14.6 (macOS 11 Big Sur)

### Fixed

- Resolved 560L EQ module polarity issue within the API Vision Channel Strip
- "Delete Selected Tracks" toolbar menu item has been restored
- Resolved an issue that could prevent play, stop, and other commands from operating after going into ARM mode in certain sessions
- Resolved an issue that could cause existing UNISON assignments to be replaced when assigning API Vision Channel Strip
- Dragging a plug-in from RECORD FX to INSERTS no longer removes the API Vision Channel Strip insert state plate\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.8 – May 10, 2021

</div>

<div class="accordion__item-content">

### Installer

### Important

- LUNA sessions opened in v1.1.8 cannot be opened in earlier LUNA versions due to file format changes

### New

- **API Vision Console Emulation Bundle**
  - Transform LUNA into API's flagship Vision Console
  - CONSOLE Mixer Row allows assignment and control of Console emulation directly within LUNA's mixer without floating windows
  - CONSOLE Focus Browser offers access to expanded controls views and extensive artist presets for API Vision Console Emulation
  - API Preamp Unison insert and API Vision Channel Strip with six modules and two switchable EQ modules for audio tracks
  - API Vision Channel Strip with six modules and two switchable EQ modules for Instruments
  - API 2500 Bus Compressor for Buses and MAIN
  - Console emulation runs natively while mixing and switches seamlessly to UAD processing while tracking, optimizing resource usage for the task at hand
  - "Paint" console emulations across your session using the CONSOLE ASSIGN mixer button
  - Summing LUNA Extensions are now assigned using the renamed SUMMING Mixer Row
  - API Vision Console Emulation Bundle is now available for 14 day demo and purchase
- **UAD Software Requirements** <a href="https://www.uaudio.com/uad/downloads/" rel="undefined" target="_self"><strong>(download now)</strong></a>
  - UAD v9.14.0 (macOS 10 Mojave or Catalina)
  - UAD v9.14.1 (macOS 11 Big Sur)

### Improved

- Optimized performance of LUNA Razor Blade and LUNA Polyphonic algorithms
- Comments now appear when editing track names in the Mixer
- 'p' and ';' keyboard shortcuts to move selection to previous and next track now function on MIXER page
- Collections now appear as folders on the Manage page
- Improved crash reporting

### Fixed

- Resolved an issue that prevented sessions created from a template from prompting to adjust or accept file tempo on import
- Export Mixdown default location no longer uses the template origin session folder when creating a new session from a template
- Resolved an issue that caused templates to be created with the track version name of the origin session when audio content is not saved in the template
- Resolved an issue that could cause MAIN to inadvertently route to a destination other than MON L/R
- Resolved an issue that could prevent immediate log in to the LUNA web view from certain regions
- Resolved an issue that prevented display of factory presets for some AudioUnits plug-ins
- Resolved an issue that caused the Clear command to add extraneous entries to the undo queue
- Resolved an issue that prevented copy and paste using the Mixer Modifiers for inserts on ARM-enabled tracks
- Resolved an issue that could cause the position of the gain control in a Unison preamp to change when powering off the preamp
- Resolved an issue that could prevent Studer A800 Noise automation from working correctly
- Stereo TAPE extension VU meters are now calibrated to -12dbU for 0 VU
- Resolved an issue that could cause CREATE page log in to fail on systems running macOS Big Sur in certain regions
- Resolved an issue that prevented Utility Delay changes from applying to previously created sends
- Resolved an issue that could cause notes to shift after muting one of several separated MIDI clips
- Resolved an issue that could cause record-enabled tracks to stop passing audio after saving an I/O Preset from within LUNA
- Resolved a crash that could occur when resizing the LUNA window while viewing the MANAGE page
- Resolved an issue that could prevent activation of a LUNA Extension license if such a license was required when adding the Extension to a track or bus
- Resolved a rare issue that could cause clips warped using the LUNA Razor Blade algorithm to stop playing audio
- Resolved an issue that could prevent display of the decimal place in the Utility row Trim after double-clicking to manually enter a dB value\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.7 – March 31, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v117x_l3377/LUNA-v117.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Session Templates**
  - Save the exact state of the current session as a LUNA Template file
  - Create new sessions from LUNA templates
  - Optionally include media in templates
- **Utility: Mixer Delay**
  - Fully automatable track level "Delay" control added to UTILITY row allows 0 to 1000 milliseconds delay of audio and midi playback on all track types

### Improved

- Utility row mixer Trim value display now shows tenths of a dB
- Increase/Decrease Grid value key command direction has been reversed to more intuitively change the value direction
- UAD2 Plug-ins with long names now use shortened name text in INSERT assignments

### Fixed

- Resolved a crash that could occur when deleting an Instrument track with multiple MIDI output assignments
- Resolved an issue that could cause LUNA to crash after using the Set Bar One command and starting playback
- Resolved an issue that could prevent accurate note velocity capture for chords that are played right before the Count In ends
- Resolved an issue that caused delay compensation issues after changing sample rates
- Resolved an issue that prevented AU plug-ins from copying successfully. Note that this fix only applies to newly instantiated AU plug-ins; existing AU instances that have already been copied once will not paste successfully
- Return key now saves in Save Bookmark and Save New Version popovers
- Toggle Snap and Toggle Relative Snap keyboard shortcuts now work on German keyboard layouts using the modifier and 7 key where "\\ is located
- Shift+I to insert time now shifts Time Signature events correctly after making a selection in the All Tracks ruler
- Resolved an issue that could cause UAD Instrument plug-in windows to occasionally load with a very small window size
- UAD Instruments no longer ignore initial automation breakpoints after loading a preset
- Sends and Cues POWER modifier overlay button now accurately reflects power status
- Duplicated tracks no longer appear in alternate windows that have a bus SPILL engaged\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.6 – March 02, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v116x_7usmm/LUNA-v116.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Polarity Invert Control**
  - Per channel automated Polarity Invert control on all track types reverses polarity during playback
  - Fader area Polarity Invert button to see and adjust polarity setting while mixing
- **Utility Mixer Trim**
  - Per channel automated Trim control adjusts pre-insert levels during playback
- **Utility Mixer Row**
  - "UTILITY" Mixer Row displays new Polarity Invert and Trim Controls
  - LINK/UNLINK function for L and R controls on stereo track allows editing of one or both channel's controls simultaneously
  - In Mixer Navigation panel, the UTLITY row can be shown, hidden, expanded, or collapsed
- **Toggle Input for Record Armed Tracks**
  - Option + K toggles input monitoring on all tracks that are currently record enabled

### Improved

- Simple Pan setting now available on buses
- Studer A800 Noise parameter now available in track automation lanes
- Neve Summing Impedance setting is remembered and restored when switching back and forth between API Summing

### Fixed

- Resolved an issue that caused delay compensation issues after changing sample rates
- Resolved a crash that could occur when scanning Audio Units plug-ins that do not contain any factory presets such as Waldorf Music D-Pole
- L and R pan values are now copied correctly to mono tracks created from Convert to Mono command
- Pan values are now summed to mono when dragging a send from a stereo to a mono track
- Resolved an issue that could occasionally cause stuck MIDI notes while stopping or relocating the playhead during playback
- Resolved an issue that could prevent creation of a new session using the same name as a previously deleted session in the same location on disk
- Resolved an issue that could prevent undo after stopping a loop recording more than half way through the loop
- Resolved an issue that caused inaccurate readings on bus summing VU meters until changing sample rate
- Resolved an issue that could cause playback to become stuck in a short loop after disk read errors
- Improved load time for sessions containing large amounts of MIDI data
- Resolved an issue that could cause an automation tooltip to show the wrong value after undoing a trim command\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.5 – February 11, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v115x_a82hd/LUNA-v115.zip" target="_self"><strong>Download This Version</strong></a>

### Important

- LUNA sessions opened in v1.1.5 cannot be opened in earlier LUNA versions due to file format changes

### New

- **Recording Count-In**
  - Toggle a 1, 2, or 4 bar count-in before recording begins
  - New Count-In Toolbar Icon and CLICK pop up menu display count-in and metronome settings
  - Configure metronome to run during only playback, recording, or both
  - K or Numpad 7 Toggle Metronome keyboard shortcut
  - Shift + K or Numpad 8 Toggle Count-In keyboard shortcut
- **Sends Group Setting**
  - Added "SENDS" group setting in the group edit browser
  - Added individual send slot modifiers to group functionality
  - Added batch Modifiers to group functionality

### Improved

- Oxide, Studer A800, and Ampex ATR-102 Extensions' meters now display the exact same post-tape signal as the original hardware circuitry and UAD Plug-Ins
- Added separate CREATE and OPEN RECENT buttons on the CREATE page

### Fixed

- Resolved an issue that caused delay compensation issues after changing sample rates
- Resolved an issue that could cause Extension and Instrument plugin presets to recall incorrectly when undoing a preset change
- Undo / Redo no longer applies to session data changes while a text entry pop-up is focused
- Resolved an issue that could prevent undo after using the Mute All command for sends
- Fixed a crash that could occur when editing MIDI notes or MIDI CC automation
- "Rescan Drives" now finds instrument data on an external drive that has been connected after launching LUNA
- Resolved an issue that could cause LUNA to hang when quitting
- Folder Open/Close states in the Inserts browser prior to text searching are remembered after clearing the search filter\
  \
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.4 (Supplemental Build 1939) – February 1, 2021

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v114x_p0w3r/LUNA-v114.zip" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved a performance issue introduced in 1.1.4

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.4 – January 20, 2021

</div>

<div class="accordion__item-content">

### Installer

### Known Issue

- Opening a session in LUNA v1.1.4 may trigger a one time re-rendering of warped audio which can cause unexpected temporarily high CPU usage

### New

- **Automation Edit Value Display**
  - See automation lane parameter values while editing using the pencil, grabber, or trim automation editing workflows
- **Automation Fine Adjust Mode**
  - Hold Shift while dragging breakpoints or trimming automation to enter fine adjust mode
- **Enhanced Sends Workflow**
  - Added Hover controls to sends slot (assign, expand, menu)
  - Drag and drop to move a send to other available send slots
  - Drag and reorder sends on hover
  - Option + Drag to copy a send to a new send slot
  - Command + Click to disable/enable send
  - Copy / Paste all sends in a track in modifiers section
  - Power on / off all sends in a track in modifiers section
  - Remove all sends in a track in modifiers section
  - Right click sends section header to access modifier functions
- **Manage Page Install/Update All**
  - Header section offers global update and install functionality

### Improved

- Manage Page notification now displays number of updates and installations available

### Fixed

- Resolved an issue that could cause the RECENT list to repopulate after using the Clear Recent command
- Fixed a text display issue when the session name includes an umlaut
- Plug-ins with reserved hotkeys, such as Celemony Melodyne, now receive keyboard input after clicking the plug-in window header to focus the plug-in
- Storage volumes with an em dash in the name no longer appear as read-only to LUNA
- Resolved an issue that caused double processing of fades in sample rate converted or warped audio renderings
- Loop Playback OFF state is once again saved and recalled with sessions
- Volume fader adjustments made in Trim mode are now added to the undo queue
- Resolved an issue that could prevent opening a bookmark quickly after saving it
- Resolved an issue that could cause automation to appear used and breakpoints that could not be edited after deleting all automation
- Changing sample rate no longer resets Solo Mode setting\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.3 – December 15, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v113x_8haal/LUNA-v113.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **macOS Big Sur Compatibility**
  - LUNA is now compatible with macOS 11 Big Sur
- **UAD Software Requirements**
  - macOS Mojave and Catalina: UAD Software v9.13.0
  - macOS Big Sur: UAD Software v9.13.1

### Fixed

- Resolved graphical issues that could affect Waves v11 plug-in window graphics
- Resolved a crash that could occur when adding or removing MIDI devices, particularly virtual instruments such as Superior Drummer that can add a virtual MIDI output
- "Cannot connect to uaudio.com" error no longer occurs unexpectedly after launching LUNA immediately after system is started
- Export Mixdown progress bar window now hides behind other applications when changing window focus
- Resolved "Unable to Bounce Session" error that could occur after attempting to export clips from multiple track versions
- Save Bookmark and Version dialogs no longer close when changing application focus
- Resolved an issue that could prevent MIDI CC automation from appearing as in use in the MIDI view focus browser
- Talkback track name plate height is correctly aligned with the rest of the mixer view when scrolling is required\
  \
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.2 (Supplemental Build 1866) – December 4, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v112x_78dyg/LUNA-v112.zip" target="_self"><strong>Download This Version</strong></a>

### Fixed

- Resolved an issue that could prevent opening of duplicated sessions

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.2 – December 1, 2020

</div>

<div class="accordion__item-content">

### Known Issue

- Waves v12 plug-in window graphics appear upside down. Use Waves v11 or await a fix from Waves before updating.

### New

- **Duplicate Track Without Content**
  - Shift + Option + D - Duplicate the selected tracks without any content
  - Shift + Option + Drag and Drop - Duplicate the dragged tracks without any content
  - Right-click or Control-Click on track nameplate \> Duplicate Without Content

### Improved

- Audio import progress display for large numbers of files has been improved
- AAF import time has been improved
- The Session Info popover now includes the Version Name and a button to View Versions and Bookmarks

### Fixed

- Resolved an issue that prevented Toontrack EZ Drummer's Follow Host setting from restoring correctly when reopening a session
- Resolved a crash that could occur when inserting AIR Music Technology instrument plug-ins
- Resolved a crash that could occur when opening the Edit Group focus browser
- Resolved a crash that could occur when editing MIDI note velocity
- Resolved an issue that caused Kontakt to have settings set to minimum values when loading some libraries
- Resolved an issue that could cause right-click/Control-click menus to disappear immediately when running third-party window management software
- Resolved an issue that could cause the Monophonic warp algorithm to output silence within nominal warp ranges
- Previously disabled Inserts are no longer enabled unexpectedly after an offline mixdown
- Extend Selection Down keyboard shortcut now works with Belgian keyboard layout
- Resolved an issue that could cause some automation to play out of sync during offline mixdown
- Resolved an issue that prevented accurate transmission of MIDI beat clock after bar 1024
- Enabling and disabling inserts in a group now follows the INSERTS group setting
- Option + Click to toggle power for all API and Neve Summing LUNA Extensions once again works in alternate windows
- Resolved an issue that could prevent bookmarks and versions from appearing in the Session Versions window after duplicating a session file
- Using Undo to revert to a previous Summing LUNA Extension no longer causes the Headroom setting to reset to default

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.1.1 – November 10, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v111x_z0es3/LUNA-v111.zip" target="_self"><strong>Download This Version</strong></a>

**IMPORTANT: LUNA sessions opened in v1.1.1 cannot be opened in earlier LUNA versions due to file format changes.**

### New

- **API Summing LUNA Extension**
  - New API Summing LUNA Extension faithfully models API console bus summing circuitry
  - Apply API Summing to the bus input console effect slot
  - Swap between Neve and API Summing with common settings preserved for true sonic A/B

### Improved

- Groups: Suspend Groups feature only suspends user-made groups, allowing Selection Group and All Tracks Group to remain in use
- Improved Undo when loop recording MIDI to allow all other actions performed during the pass be undone individually, as well as allow MIDI passes recorded on the track to be undone with a single undo operation
- Solo Safe now allows channels in ARM mode to remain audible while soloing other tracks **(Requires UAD Software v9.13)**
- Improved performance of grouped control changes for all mixer controls on large track counts
- Pressing the Escape key clears the current track selection if there is nothing else selected that can be escaped

### Fixed

- Resolved an issue in a shared library that could cause many third party instrument plug-ins to crash
- Activation of LUNA Extension and Instrument licenses to a cloud session no longer fails after linking an iLok account name that includes capital letters
- Clips no longer snap to their origin point while dragging on the original track, making it easier to move clips by very small amounts
- Muted tracks no longer pass audio when re-opening a session version
- Resolved multiple issues that caused "unable to sync metadata" errors when opening sessions
- Command + Left/Right arrow keys now update track selection when renaming tracks in Mixer view
- Resolved an issue that could prevent a newly saved version title from appearing in the session titlebar
- Dragging tracks vertically in the timeline once again scrolls the timeline view up and down
- Click track level is no longer included in the ALL TRACKS group
- Resolved a crash that could occur when opening the Edit Group focus browser
- Resolved a crash that could occur when starting Shape Expansion Pack download from within Shape window
- Resolved a crash that could occur when editing MIDI Clock output delay
- MIDI Clock messages are no longer sent during Offline Mixdown
- Moog Multimode Filter XL now responds to and stores sequence changes while in ARM mode **(Requires UAD Software 9.13)**
- Resolved an issue that caused UAD plug-ins to reset to their defaults after disarming a track after loading a preset from the plug-in window header
- Master Tape processing is now included in post-fader sends on buses
- Resolved an issue that could prevent cleanup of temporary audio files created when Warp editing on audio Tracks
- Resolved an issue that prevented Instrument track ARM mode from passing signal in certain I/O Matrix configurations
- Resolved an issue that caused Track Versions behaviors in Groups to be linked by the Mixing attribute instead of the Editing attribute
- When a range is selected, and the play start marker is subsequently moved, Export Mixdown now correctly exports the selected range
- Clicking on a fader on a grouped track while volume automation is playing back no longer causes a level offset
- Tape machine focus browsers are now scrollable at lower window sizes and screen resolutions
- Resolved an issue that could cause alternate LUNA windows to always reopen on top of primary windows regardless of the window arrangement when the session was closed
- Resolved an issue that could leave very small clips to the left and right of a selection when clearing
- Track color is preserved when using Convert to Mono on a stereo track\
   

## Version 1.1 – October 6, 2020

</div>

- <a href="https://builds.uaudio.com/LUNA/v110x_h01hx/LUNA-v110.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Track Groups**
  - New GROUPS panel in Tracks column to display and work with group
  - Create/Edit Track Groups with editing, mixing, and insert grouping attributes
  - New Track Group: Command + G
  - Suspend Groups: Shift + Command + G
  - Toggle Selection Grouping: Control + G
  - Show/Hide all tracks in a group
  - Command + Click Show/Hide to show only group tracks
  - Right click on or drag tracks to groups list to create/add to groups
- **Session Versions**
  - "Save New Version" command creates separate session versions within the session package
  - "Save Bookmark" command creates a permanent marker of the state of the session, for any desired production milestone, that can be restored exactly at any time
  - Versions window allows access to Versions, Bookmarks, and their notes
- **MIDI Clock Output**
  - New Settings Panel MIDI Tab
  - Song or Pattern clock modes for exact timeline synchronization or groovebox pattern triggering
  - +/- 200ms clock offset to compensate for MIDI data transmission and external device latencies

### Improved

- Numerous stability and general performance improvements
- Performance of grouped fader movements is improved
- ATR-102 AUTO CAL LED turns red when parameters no longer match calibrated settings
- Improved visibility of very short clips when zooming out

### Fixed

- Resolved an issue that could prevent a session from loading completely when opened from the macOS Finder
- Resolved an automation editing issue that could cause newly created tracks, buses, or plug-in instances to disappear
- Resolved an issue that could cause offline mixdown to hang indefinitely
- Resolved an issue that could cause audio artifacts with Instrument track processing while in ARM mode
- Resolved a rare issue that could cause audio clips to appear offline when reopening a session
- Resolved an issue that could cause the INSERT focus browser to remain visible after assigning and insert and exiting the browser
- Resolved an issue that caused fader volume dB display and other visible parameter values to show values from earlier in the session, rather than the playhead location
- Resolved a crash that could occur when displaying the Master Tape focus browser
- Resolved a conflict with Native Instruments background services that caused issues, including UAD Instruments with blurred graphics
- Resolved an issue that could prevent plug-ins on ARM-enabled buses from loading when reopening a session
- Resolved an issue that prevented multiple copy and paste operations of the same insert
- Resolved an issue that could prevent large sessions from reopening with the correct location and zoom settings
- Playback of MIDI CC data is no longer modified by editing CC automation on unrelated areas in the timeline
- Removing a Neve Summing extension with previously written automation no longer causes incorrect automation levels
- Removing a plug-in when automation is written no longer leaves stale automation
- Toggling power for plug-ins and LUNA Extensions no longer writes automation for all automatable parameters
- Resolved an issue that caused an empty session window to appear when including "/" while renaming a session
- Resolved a crash that could occur when Ctrl-clicking on certain knobs in the mixer view or monitor section
- Resolved an issue that could prevent grid lines from drawing when changing the time signature in a session with negative bars
- Plug-in windows are no longer unexpectedly closed while swapping insert assignment positions
- Resolved an "Unable to set the preset" error that could occur after assigning a plug-in
- File Open and Open Recent menu options now function correctly when an alternate window is focused
- Resolved an issue that prevented correct adjustment of linked ATR-102 Record/Repro parameters on tracks in a selection group
- The "Copy Mix to Cue" command can now be undone
- Resolved an issue that could cause "Unable to subscribe to path" error when undoing or redoing
- Newly created buses are now selected automatically when created
- Resolved an issue that caused Steinberg HALion Sonic to display an error when inserted\
   

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.9 – September 8, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v109x_rnd03/LUNA-v109.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **ATR-102 Master Tape Recorder LUNA Extension**
  - Master Tape Assignment for Buses and MAIN enables analog tape summing workflows
  - Ampex ATR-102 Master Tape LUNA Extension is now available for 14 day demo and purchase, and free for all current owners of the UAD version
- **MP3 Export**
  - When exporting a Mixdown or Clips, you can now select MP3 as the file type option, and set VBR or CBR settings

### Improved

- Changes from drawing, dragging, and trimming automation are now audible immediately as they are edited
- Accuracy and smoothness of fade curve editing has been improved

### Fixed

- Resolved a crash that could occur opening the Tape Machine Focus Browser
- Resolved an issue that could require an additional login for the CREATE page when using LUNA in certain countries
- Resolved an issue that prevented the Teletronix LA-3A from loading in existing sessions
- Resolved an issue that could cause plug-in windows to be placed behind LUNA application windows
- Resolved a crash that could occur when renaming a session
- Resolved a crash that could occur when deleting tracks
- Resolved an issue that could prevent soloed buses from passing audio when reopening a session
- Resolved an issue that could cause artifacts during offline mixdown of multitimbral instruments
- The Default Fade Shape option now applies to all fades, whether created with the Fade tool or keyboard shortcuts
- Resolved an issue that could prevent tape Saturation control changes from displaying correctly in all LUNA windows
- Move To Next/Previous Bar commands now function in Mixer view
- Hidden tracks are no longer visible in the mixing workflow's Universe view
- Tape Reel graphics in the Machine assignment Focus Browser now match the machine configuration
- An Instrument track's Fit setting is restored when opening a session\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.8 (Supplemental Build 1723) – August 7, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v108x_85q20/LUNA-v108b.zip" target="_self"><strong>Download This Version</strong></a>

### Known Issue

- For optimum results, update any Native Instruments plug-ins to their latest versions

### Fixed

- Resolved a crash that could occur when closing a plug-in window while adjusting controls
- Resolved a crash that could occur when reordering tracks to top of tracks list
- Resolved a crash that could occur when opening Tape Machine controls view

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.8 – August 5, 2020

</div>

<div class="accordion__item-content">

### Installer

### New

- **Direct Output Delay Compensation**
  - All SEND and OUTPUT routings to Apollo LINE and MON outputs are now aligned
- **Discard Recording Shortcut**
  - Punch out of record and move the recorded wav file to the trash: Shift + Command + "."
- **Tape Assign Hover Functions**
  - Direct navigation to global assignment and control panels
  - Easier access to secondary track controls and functions

### Improved

- Timeline drawing and track resizing use less GPU resources

### Fixed

- Resolved track mixdown delay compensation for tracks feeding buses with latency that are not in the mixdown
- Resolved an issue which could cause artifacts when recording from Apollo Virtual inputs or with ARM disabled
- Resolved a brief hang that could occur when dragging or trimming clips
- Resolved an offline mixdown issue that could delay audio from instrument tracks with MIDI data at the exact start of the session
- MIDI note playback is no longer cut short on first loop after recording
- User-generated AU plug-in icons are no longer removed when installing UAD software
- Navigate To Next/Previous Bar commands now scroll timeline view
- CUE BUS assignments are reflected immediately in CUE OUTPUTS window
- Resolved issue when pasting volume automation from multiple tracks
- Resolved "Unable to Set Preset" issue that could occur while searching INSERT focus browser
- Values typed into track volume popover are applied correctly to all tracks when selection grouping is enabled
- Trim Clip To Selection command no longer changes selection when there are multiple track versions
- Resolved issue with focus channel Tape Saturation adjustment when using selection grouping
- Pressing apply works on the first attempt when changing time signatures at bar 1
- Resolved MIDI note recording issues while loop recording data from channels 2-16
- POWER modifier correctly toggles Neve Summing bypass
- OUTPUT routing assignment no longer disappears from focus channel after collapsing and expanding the mixer row\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.7 – July 14, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v107x_ya82c/LUNA-v107.zip" target="_self"><strong>Download This Version</strong></a>

### New

- **Trim Shortcuts**
  - Trim From Clip Start: A
  - Trim From Clip End: S
  - Trim Clip to Selection: Command+T
- **Session Folder**
  - New Luna sessions are created within a parent folder
- **Default Export Location**
  - Export Clips/Mixdown creates "Exported Files" subfolder within new session's parent folder

### Improved

- **Feedback Form**
  - Choose report topic for analysis categorization
  - Enhance analysis with System Profile and Log options
  - "Remember Me" option for additional reports
- Improved progress bar visibility

### Fixed

- Resolved an issue that could prevent track duplication after deleting track versions
- 32-bit fixed (non-float) WAV files now import successfully
- Export Mixdown no longer hangs if a track is in ARM mode when mixdown begins
- Resolved "unable to touch a control" error that could occur when swiping over mute or solo switches with multiple tracks selected
- Resolved a rare crash that could occur while playing or editing MIDI
- Undo clip move now restores previous selection
- MIDI notes recorded from channels 2-16 preserve channel data when edited
- Resolved an error that could occur when adjusting Softube Amp Room plug-in controls
- Control change undo now works with Soundtoys plug-ins
- LUNA Extensions and Instruments purchased in demo period now reflect the updated license state
- Resolved display flickering issue that could occur while editing fades
- DISCOVER panel no longer requires separate login\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.6 – July 1, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v106x_lod03/LUNA-v106.zip" target="_self"><strong>Download This Version</strong></a>

**IMPORTANT: LUNA sessions opened in v1.0.6 cannot be opened in earlier LUNA versions due to file format changes.**

### New

- **Drag/Drop MIDI to Tracks**
  - Drag/drop MIDI from Finder or plug-in window directly to existing track
- **Reverse Audio**
  - Right-click waveform to reverse selection via contextual menu
- **Neve Summing and Tape Extension Automation**
  - Automate and edit parameters of Neve Summing, Studer A800, and Oxide LUNA Extensions
- **Clear All Automation**
  - Edit \> Clear All Automation to delete all automation data on tracks within edit selection
- **Clear Recent List**
  - Clear recent sessions in CREATE panel via right-click or File menu

### Improved

- Added Copy/Paste of compatible automation types such as sends to other sends
- Improved MIDI loop recording performance
- Log In window remains open if another application is focused
- Audio Units plug-ins added in ARM mode are disabled with a notification

### Fixed

- Resolved an issue that could prevent tracks from being hidden
- Resolved an issue that prevented playback of newly recorded audio clips for several seconds
- Resolved an "unable to sync session metadata" error that could occur when tracks lost cue assignments
- Resolved an issue that could cause all plug-ins to appear in an "Other" folder
- Resolved an issue that could prevent UAD plug-ins from activating on buses in ARM mode
- Exported WAV files now recognized by MPC hardware
- Tape machine C and D no longer appear blank when changing machine type after assignment
- Resolved an issue that prevented plug-in presets from displaying
- Resolved an error that could occur selecting overwritten presets for Audio Units plug-ins
- Disabled plug-ins that are dragged to another insert are no longer enabled
- Fixed hotkeys that use the "=" key position on German and Austrian keyboard layouts
- MIDI CC automation value updates made during playback are now audible immediately
- Resolved an issue that caused grid lines to disappear when changing time signature
- Save Copy As no longer allows replacing an open session
- Renaming an open session to the same name as a previously deleted session no longer causes an unexpected error
- Resolved an issue that could cause fader levels and automation to appear offset for tracks routed to a Neve Summing bus
- Resolved an issue with log in case sensitivity that could prevent log in for web views in the CREATE panel
- LUNA Documentation link resolves correctly again
- Resolved 74 additional internal bug reports\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.5 (Supplemental Build 1634) – June 11, 2020

</div>

<div class="accordion__item-content">

### Installer

- <a href="https://builds.uaudio.com/LUNA/v105x_9ap1f/LUNA-v105.zip" rel="noopener noreferrer" target="_blank"><strong>Download This Version</strong></a>

### Fixed

- Resolved macOS notarization issue preventing application launch on some Catalina systems\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.5 – June 10, 2020

</div>

<div class="accordion__item-content">

### Installer

### New

- **"My Universal Audio" Plug-in Folder**
  - Top folder in inserts focus browser shows only owned and active demo UAD plugins
- **Timeline Auto-Scroll**
  - New Bars\|Beats ruler icon for automatic scrolling in timeline view
  - New Navigation menu option for automatic scrolling in timeline view
- **Rename Exported Files**
  - Double-click to rename files in Export Mixdown and Export Clips views
- **Snap Drag and Drop/Duplicate Clips**
  - Snap clips to original timeline position by holding control while dragging clips to different tracks
- **Move/Select to Next and Previous Bar**
  - Press \[ or \] to go forward and backward one bar
  - Press 1 or 2 on the keypad to go forward or backward one bar
  - Add Shift key to extend selection by one bar
- **Heal Separation Command**
  - Repair separated clips that have aligned content
  - Edit\>Heal Separation or Command + H

### Improved

- Better offline mixdown speed when exporting multiple tracks
- Double-click anywhere in track automation lane to add new automation breakpoint
- Plug-in windows open on correct display on multi-display systems
- Better visibility of automation data on Instrument tracks

### Fixed

- Resolved rare issue that could cause incorrect recorded file lengths when punching in with pre-roll enabled
- Resolved issue that could prevent displaying of Shape Expansion presets
- Unexpected automation data no longer created when editing clips on tracks routed to a Neve Summing bus
- Mixer view no longer scrolls to wrong track when selecting tracks in large sessions
- Showing/hiding tracks no longer cancels SPILL
- Simple pan mode state is now restored when reopening sessions
- Click drag tempo field only adjusts current value when session contains multiple tempos
- Addressed an Audio Units plug-in load issue for MOTU MachFive and other older plug-ins that report channel information differently
- Resolved 59 additional internal bug reports\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.4 – May 26, 2020

</div>

<div class="accordion__item-content">

### New

- **Track Toggle Shortcuts**
  - Record: Shift+R
  - Input: Shift+T
  - Solo: Shift+S
  - Mute: Shift+M
- **MIDI Chase - **MIDI note and controller data playback now follows transport and playhead changes
- **Drag Tempo Value - **Drag in the Control Bar's BPM field to dynamically adjust session tempo
- **Playback Input Monitoring** (Requires UAD Software v9.12) - Record-enabled inputs are now audible during playback in Console Tracking Mode
- **Open/Close All Folders Shortcut** -** **Option+Click any Focus Browser folder to open/close all folders
- **Save Focus Browser State **- Folder open/close state of all Focus Browser views now saved
- **MIDI Clip Rename **- Double-click at top of any MIDI clip to rename the clip

### Improved

- Command+W shortcut no longer closes session
- Improved timing of MIDI played from computer keyboard in MIDI Keyboard Mode
- Option+Click 'do to all' modifier for mixer switches no longer affects hidden tracks
- Track name display works inside Audio Units plug-ins that support this feature
- Notification when deactivated routing assignments prevent audio feedback
- Toggle Mixer/Timeline shortcut works on keyboard layouts with "=" on keys 0, 6, 7

### Fixed

- Resolved crash that could occur while progress bar is displayed
- Resolved case where mixdown file was not time-aligned with original source
- Resolved rare issue causing clips to appear as if recording when stopped
- Instrument tracks no longer process live MIDI input during offline mixdown
- Resolved an issue preventing initial assignment of Tape Machines to slot C and D
- Undo now works when plug-in windows are closed while controls are being adjusted
- Fader dB values now match fader positions when exiting Trim automation mode
- Clips selected on multiple tracks separated by a bus now move correctly
- Horizontal mixer scrolling behavior after renaming tracks
- All Kontakt MIDI connections are now restored when session is reopened
- Tape VU Meters on Instrument tracks now show signals in ARM mode
- Resolved Send/Cue knob value brightness issue
- Transposing all MIDI notes within a marker area no longer deletes the marker
- Fader value display returns to correct value when exiting Trim automation mode
- Logic Pro X AAF files containing "+" in audio filenames now import correctly
- Resolved 36 additional internal bug reports\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.3 – May 6, 2020

</div>

<div class="accordion__item-content">

### New

- **Trackpad Zoom** – Pinch trackpad with two fingers on Timeline to zoom in/out horizontally

### Improved

- Resolved several specific issues that could cause metadata errors when opening session files
- Audio Units plug-ins with transport controls are now synchronized to LUNA's transport and timeline
- Playback metering uses less GPU resources
- Improved visibility of grid lines in WARP view and automation data in track parameter views
- Resolved several issues with plug-in insert drag/drop functions
- Next/Previous Marker navigation shortcuts update playback and are now available in Mixer View
- The Consolidate shortcut (Shift+Option+3) now works with numeric keypads
- New "Hide Selected Tracks" option when right-clicking track labels in Mixer view

### Fixed

- Resolved MIDI recording issues when Pre-Roll is enabled at beginning of timeline
- Resolved audio processing and metering issues with Waves compressor plug-ins
- Certain Audio Units instrument plug-ins now maintain pitch when sample rate is changed
- Resolved note shift issues when imported MIDI file clips are edited
- Duplicating no longer creates unexpected automation ramps
- Resolved issues with Copy/Paste header buttons for plug-ins
- Resolved timing issues with tempo sync plug-ins inserted on bus tracks
- UAD plug-ins in active demo period no longer display in red disabled state
- Export now works as expected when more than 10 clips with same name are selected
- Resolved erratic control Undo after adjusting Tape Saturation
- Tape Saturation adjustments are now mirrored in Alternate windows
- Resolved state display issues when replacing tape machines
- The Import Tempo dialog now appears again if the first Import Tempo dialog was canceled
- Resolved browser arrow key navigation issue after inserting plug-ins
- Resolved 48 additional internal bug reports

### Known Issue

- Audio Units plug-ins requiring Steinberg eLicenser cannot be used with macOS Catalina.\
  A workaround is available with macOS Mojave. Visit <a href="https://help.uaudio.com/hc/en-us/articles/360043151071" target="_self">this KB article</a> for details.\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.2 – April 21, 2020

</div>

<div class="accordion__item-content">

### Improved

- Improved shortcut modifier key handling on international keyboards
- Improved GPU resource utilization (may decrease fan speeds on some systems)
- Login credentials are now properly retained when Remember Me option is checked
- Markers are automatically assigned different colors when created
- Command+A shortcut now selects all Warp markers on a track in WARP view
- Numerous general stability enhancements

### Fixed

- The Content Location selector no longer causes LUNA to become unresponsive when many storage volumes are mounted
- Resolved issue preventing installation of UAD Instrument content to external storage
- Consolidate command now correctly renders Clip Gain
- Metronome is no longer muted when solo is enabled on a bus
- "Save a Copy As" now offers the option to overwrite existing session files
- Sessions closed due to Apollo hardware disconnection now open correctly without having to relaunch LUNA
- Studer A800 CAL control now updates correctly when recalling presets
- Tape Machine Copy and Paste modifiers now function reliably
- The MIDI Keyboard Mode menu item now remains active when a floating plug-in window has focus
- Copy and Paste now work correctly in the DISCOVER panel
- Resolved 66 additional internal bug reports\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.1 – April 10, 2020

</div>

<div class="accordion__item-content">

### Fixed

- The following UAD Direct Developer plug-ins are now available for use within LUNA:
  - UAD Auto-Tune Realtime Advanced
  - UAD Oxford Dynamic EQ
  - UAD Oxford SuprEsser DS
  - UAD MDWEQ5-3B
  - UAD MDWEQ5-5B
- Resolved cases where Audio Units plug-ins could crash LUNA when opening or interacting with the AudioUnits plug-in GUI
- Resolved cases where downloading or transferring UAD Instrument content could crash LUNA
- Improved communications with iLok licensing services

### Known Issue

- In some cases, web content in LUNA's sidebar CREATE panel may not be visible.\
  Workaround: Select any other LUNA panel, then return to the CREATE panel.\
  (This issue is fixed in LUNA v1.0.2)\
   

</div>

</div>

<div class="accordion__item">

<div class="accordion__item-title">

Version 1.0.0 – April 7, 2020

</div>

<div class="accordion__item-content">

### Initial release of LUNA Recording System

- Available in LUNA v1.0.0:
  - Shape Creative Toolkit UAD Instrument (free)
  - Moog® Minimoog UAD Instrument
  - Ravel™ Grand Piano UAD Instrument
  - Spitfire Audio UAD Instruments
  - Oxide Tape LUNA Extension (free)
  - Neve® Summing LUNA Extension
  - Studer A800 Tape LUNA Extension

Known Issue

- <a href="https://help.uaudio.com/hc/en-us/articles/360042020611" rel="noopener noreferrer" target="_blank">Certain UAD plug-ins are missing from LUNA v1.0.0</a> \
  (This issue is fixed in LUNA v1.0.1)

</div>

</div>

