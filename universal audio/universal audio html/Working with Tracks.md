---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/21314062845844-Working-with-Tracks.html'
converted_at: 2026-05-31T13:44:47Z
tool: htmlq+pandoc
title: 'Working with Tracks'
word_count: 814
---

# Working with Tracks


After you create tracks, you work with them in the timeline or mixer view to add audio or MIDI, record. and mix.

## In this article

- [Track Controls](#h_01HD2NTANYWB9J7H6ZNDV00VS9)
- [Selecting Tracks](#h_01HD2NTANYMG36J7EZMYQX9XZK)
- [Applying Changes to Multiple Tracks with Selection Grouping](#h_01HD2NTANYJHGZPK4R7N0BFBV3)
- [Applying Changes to all Tracks](#h_01HD2NTANYA02MXQ7V2QE9XGXH)
- [Deactivating Tracks](#h_01HGC112KM1QKM9YPMQSJ7QNMA)

------------------------------------------------------------------------

# Track Controls

In LUNA, you can use many of the same track controls in multiple views. 

For example, audio tracks in the Timeline have the following controls in the Track Controls area.

![timeline-track-controls.png](Working%20with%20Tracks_assets/96e2addec62ba2deaa4dcfc11a897ba2672a5da7.png)

Audio tracks in the Mixer and focused in the Timeline have the following controls.

![mixer-focus-audio-track-controls.png](Working%20with%20Tracks_assets/28688b364896004afae337108ad90873e43cbc29.png) 

You can make many of the same adjustments in both views. In both Timeline and the Mixer/Focus channel, you can:

- Assign inputs and outputs
- Adjust volume and panning
- Set the track automation mode
- Enable Record and Input monitoring
- Solo and mute tracks
- Change the track name
- Change the track color

However, there are some adjustments you can only make in the Timeline or Mixer/Focus view. 

In **Timeline View only**, you can:

- Configure the Warp algorithm
- Set a track to Clips Follow Tempo mode
- Edit audio and MIDI, create fades, and other editing tasks

In **Mixer/Focus track view only**, you can:

- Configure plug-ins
- Add UAD instruments
- Add Audio Unit or VST3 instruments
- Configure the LUNA Extensions for Tape, Master Tape, API Summing, and Neve Summing
- Configure API Vision Console Emulation extensions
- Adjust preamp controls and start Auto-Gain

**Note:** As with audio tracks, you can configure many settings for instrument tracks, buses, and the Main track in both the Timeline track controls and in the Mixer/Focus channel.

------------------------------------------------------------------------

# Selecting Tracks

To select a track, click the track name in the Mixer, Timeline, or Tracks browser. 

- To select multiple contiguous tracks, Shift-click the track names on the first and last track you want to select.
- To select multiple non-contiguous tracks, Command-click (macOS) or Ctrl-click (Windows) the track names. 
- To select all tracks, Option-click (macOS) or Alt-click (Windows) a track name.

------------------------------------------------------------------------

# Applying Changes to Multiple Tracks with Selection Grouping

LUNA includes a track grouping feature that allows you to change controls on multiple selected tracks without defining a specific Track Group.

To enable or disable selection grouping, select or deselect Mixing \> Selection Grouping from the LUNA menus, or press Ctrl+G (macOS) to toggle selection grouping. To enable or disable all track groups, press Shift+Command+G (macOS) or Ctrl+Shift+G (Windows). To create a group, press Command+G (macOS) or Ctrl+G (Windows).

The following items can be adjusted when selection grouping is enabled. 

- Volume
- Pan
- Track View
- Automation Mode
- Track Follows Mode
- Warp Algorithm
- Track input
- Auto-Gain
- Clips Follow Tempo mode
- Record Enable (only for tracks that have a unique Input assigned)
- Input Enable (only for tracks that have a unique Input assigned)
- Solo
- Mute
- Tape machine and tape settings
- API and Neve Summing assignments and settings
- API Vision Console Emulation Extension assignment and settings
- Inserts (adding an insert to a slot on a selection-grouped track will override existing inserts on the same slot on any other grouped tracks)
- Send assignments and controls
- Track outputs

For more information about track groups, see <a href="360050574411-Using-Track-Groups.html" target="_self">Using Track Groups</a>.

------------------------------------------------------------------------

# Applying Changes to all Tracks

To adjust items on all tracks, Option+Click (macOS) or Alt+Click (Windows) the setting in the track controls or mixer channel strip. For example, Option+Click/Alt+Click the record-enable button to record-enable all tracks that have unique input assignments.

**Note:** When you Option+Click or Alt+Click a control to enable or disable the setting, tracks that are hidden in the Tracks Browser are not affected.

------------------------------------------------------------------------

# Deactivating Tracks

You can deactivate tracks in LUNA. A deactivated track does not play back audio, and does not consume any CPU or DSP resources. You can deactivate audio, instrument and bus tracks. You cannot deactivate the Main track. You cannot change controls on a deactivated track. Deactivated tracks appear in the Timeline and Mixer view with diagonal marks through them to indicate that they are deactivated.

![active-deactivated-timeline.png](Working%20with%20Tracks_assets/a0fa45f9a5fc868dd7a27f70df094de7ba2038d6.png)

## Deactivate tracks

- To deactivate a single track In the Timeline or Mixer view, Control-click or right-click on the track name area, and choose Deactivate "track name".
- To deactivate multiple tracks, select multiple tracks or a track group, then Control-click or right-click on a track name, and choose Deactivate Selected Tracks.

## Activate deactivated tracks

- To activate a single deactivated track In the Timeline or Mixer view, Control-click or right-click on the track name of a deactivated track, and choose Activate "track name".
- To activate multiple deactivated tracks, select multiple deactivated tracks, then Control-click or right-click on a track name, and choose Activate Selected Tracks.

<span class="wysiwyg-font-size-small">251216</span>

