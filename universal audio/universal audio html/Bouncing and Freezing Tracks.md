---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/10540575702292-Bouncing-and-Freezing-Tracks.html'
converted_at: 2026-05-31T13:44:42Z
tool: htmlq+pandoc
title: 'Bouncing and Freezing Tracks'
word_count: 2229
---

# Bouncing and Freezing Tracks


## In this article

- [Bouncing Tracks](#h_01JETBNNXB5EP3AZNJEBNVBZB9)
- [Freezing Tracks](#h_01JETBNNXC4Z56PASPE7E8A6EP)
- [How Track Freeze Affects Your Tracks](#h_01JETBNNXC1VQFMQK134J3B3ZM)

## **Bounce and Freeze overview**

Bounce and Freeze both allow you to save tracks in their current state, to reduce system resource usage and prevent changes. However, Bounce and Freeze work differently in the LUNA session.

### **Bounce (mix down in place)**

- **Use:** Convert tracks to audio files with all effects and extensions baked in. Ideal for saving CPU or sharing files.

- **Tracks:** Available on Main, instrument, bus, and audio tracks.

- **Post-bounce options:** By default, LUNA **archives** the original tracks. You can optionally choose to keep them active or delete them.

- **Smart silence processing:** Automatically removes silence between clips, preserving reverb tails and delays.

- **Consolidation:** Creates individual clips where audio exists unless you choose to "Consolidate" into a single clip.

<figure class="wysiwyg-image">
![drums-bounce.png](Bouncing%20and%20Freezing%20Tracks_assets/e826d5302900884b96dcf88c8dda9f36acab3c8b.png)
</figure>

*Multi-out drum plug-in bounce showing silence between clips*

![reverb-tail-bounce.png](Bouncing%20and%20Freezing%20Tracks_assets/1adf8fbea5dece7889dacba7404ddc51c3d37013.png)

*Bounce with reverb tail*

### **Freeze (temporary mix)**

- **Use:** Quickly renders tracks as audio to free up system resources.

- **Tracks:** Available on audio, instrument, and bus tracks.

- **Post-freeze:** Tracks can be "unfrozen" at any time to edit the original MIDI, audio, or plug-in settings.

### **Choosing Bounce or Freeze**

Use **Freeze** for temporary CPU or UAD DSP plug-in relief while mixing. Use **Bounce** when you are finished with a track and want to commit it permanently to the session, or to share the session.

On a drum track with big spaces, for example, audio clips are only created where they are required, unless the Consolidate option is selected (see [Bounce settings](#h_01JETBNNXBEHYVN4FQC9CGCKJA) for more information).

------------------------------------------------------------------------

# Bouncing Tracks

Right-click on a track name in the timeline or mixer and choose Bounce, or press Command+B (macOS) or Ctrl+B (Windows). The entire range of the track is bounced and added as a new track in the session, with the name "*track-name* Bounce", and the original track is archived.

## Bouncing multiple tracks

To bounce multiple tracks, select multiple tracks in the session and right-click, then select Bounce, or press Command+B (macOS) or Ctrl+B (Windows).

To bounce tracks from a multi-out plug-in, select one or more of the multi-out tracks. To bounce all tracks from a multi-out plug-in, you can select all multi-out mixer tracks or the main main multi-out track.

![bounce-multiple.png](Bouncing%20and%20Freezing%20Tracks_assets/3c042e3c8c39ddec6fdc7a2f4b02a94cf2870626.png)

*Bouncing multi-out-mixer tracks by selecting main multi-out track*

## Bouncing a track range

1.  To bounce a range, select the range in the LUNA timeline, then select the tracks you want to bounce.
2.  From the LUNA menus, select Track \> Bounce Range, or press Option+B (macOS) or Alt+B (Windows).

The range you have selected is bounced.

**Note:** Bounce Range does not Archive or Delete the source tracks, if either option is selected.

## Bounce settings

To open the bounce settings, choose Track \> Bounce Settings from the LUNA menus, or press Option+Command+B (macOS) or Alt+Shift+B (Windows).

![bounce-settings-callouts-2x.png](Bouncing%20and%20Freezing%20Tracks_assets/33d22c52042b66a896ae202ab9197147bfbf0634.png)

### Bounce

- **Tracks:** Bounces complete tracks as long as audio is present for up to the entire length of the session
- **Range:** Bounces only the selected range

### Bounce Tracks Source

- **Archive:** Removes the original track or tracks after bouncing, but allows you to restore the original tracks later
- **Keep:** Keeps the original and bounced tracks in the session.
- **Delete:** Deletes the original tracks after the bounce. No restore is possible.

**Note:** Archive and Delete only remove tracks when you bounce the entire track, not when you bounce a range.

### Consolidate

Choose this option to create one audio file when bouncing. This option retains the silence between sounds, and outputs one audio file. When Consolidate is not selected, audio clips are created only where required by the audio source.

**Tip:** To conveniently share files, when bouncing a track and not a range, this option creates one file from the start of the session, regardless of where the first detected audio is on the source track.

### Destination

Destination lets you choose a track on which you can place the bounced audio. When rebouncing a track or a range, choose the destination track from this list to place the audio on the existing bounced track, or on any track you choose.

**Tip:** Only choose a destination when bouncing a single source track. When bouncing multiple tracks or a multi-output track, choose New Track.

## Partially bouncing a track

You can bounce a track only up to a certain point in the track processing. The processing follows the flow in the Mixer channel strip. When you bounce up to a specific point, the audio is processed for the preceding instruments, extensions, and plug-ins only. Any extensions or plug-ins that follow the bounce point remain active on the new bounced track, and continue to process the resulting audio.

**Note:** You cannot partially bounce the Main track.

### Bounce points on an audio or instrument track

You can bounce at any of the following points on an audio or instrument track:

- An instrument plug-in and MIDI FX plug-in if inserted (instrument track only)
- A multitrack tape extension
- The API Vision Console extension (which can be ordered before standard insert plug-ins, or in any standard insert plug-in position)
- Any of the standard insert plug-ins 1-8

![bounce-up-to-points-tracks.png](Bouncing%20and%20Freezing%20Tracks_assets/5d619eaafd1d7e41295358a8a23a2158be52c0de.png)

### Bounce points on a bus track

You can bounce at any of the following points on a bus track:

- The master tape extension (if configured pre fader)
- The API Vision Console extension (which can be ordered before standard insert plug-ins, or in any standard insert plug-in position)
- Any of the standard insert plug-ins 1-8
- The master tape extension (if configured post fader)

![bounce-up-to-buses.png](Bouncing%20and%20Freezing%20Tracks_assets/d330f341000e6ed3b0edbae8df5d12a04cc8ff85.png)

### To bounce up to a specific point on a track

1.  In the Mixer view or in the Focus channel, find the point at which you want to bounce the track.
2.  Right-click on the extension or plug-in and choose Bounce under Up To This Insert.

The track is bounced up to the selected insert point. The new bounced audio track appears, now including the remaining inserts or extensions.

![bounce-to-insert.png](Bouncing%20and%20Freezing%20Tracks_assets/d24f120d5eef0dc3598c39a549f66177dc6c0500.png)

## Restoring archived tracks

To restore an archived track, right-click on the track name in the LUNA mixer or timeline, and select Restore Bounce Source. You can also click on the track or tracks in the Tracks browser, then right-click and select Restore Bounce Source. You can restore multiple tracks with Selection Grouping enabled.

When you restore archived tracks, the bounced tracks are retained.

![restore-bounce-source.png](Bouncing%20and%20Freezing%20Tracks_assets/3cf0eb27b7ea992f4eb197ae40824c6e9286bfee.png)

------------------------------------------------------------------------

# Freezing Tracks

In Timeline view, click the snowflake button in the track controls to freeze a track.

![freeze-button.png](Bouncing%20and%20Freezing%20Tracks_assets/63c4b99940b3606565033b237957ccbbd9706c97.png)

The track is frozen, indicated by the highlighted snowflake button on the track controls and the grayed out appearance of the track and any plug-ins or extensions.

The track now plays back as audio with all instruments recorded to audio, and all track processing applied. Audio and MIDI data on the track appears grayed out, and when you hover your mouse over the track, the text "Frozen" appears. You can work with your session as normal; however you cannot edit the track contents, plug-ins or extensions. 

- Click the snowflake button again to unfreeze the track.

## Track Freeze notes

- You can only freeze or unfreeze a track when the transport is stopped.
- If a track has no content on the timeline, the Freeze option is not available.

![track-freeze-instrument-tl-callouts.png](Bouncing%20and%20Freezing%20Tracks_assets/736213e7f0b63c53f7022930cf3bad43566dc044.png)

*A frozen instrument track in the timeline*

*![frozen-inst-channel-strip.png](Bouncing%20and%20Freezing%20Tracks_assets/748e7aa6d6b7fe701993dc3257ffc108af0a7461.png)*

*A frozen instrument track in the mixer/focus channel*

## To freeze an audio, instrument, or bus track

- In Timeline view, click the snowflake button on the track controls to freeze the track, or
- In either Timeline or Mixer view, right-click or Control-click on the track name and choose Freeze.

![freeze-menu.png](Bouncing%20and%20Freezing%20Tracks_assets/575a1d45bea7b8fa335d364b0432b499aaf80679.png)

## To unfreeze a frozen track

- In the Timeline view, click the highlighted snowflake button on the track controls to unfreeze the track, or
- In either Timeline or Mixer view, right-click or Control-click on the track name and choose Unfreeze.

## Partially freezing a track

You can freeze a track only up to a certain point in the track processing. The processing follows the flow in the Mixer channel strip. When you freeze up to a specific point, the audio is processed for those instruments, extensions, and plug-ins only. Any extensions or plug-ins that follow the freeze point remain active and continue to process the resulting audio track.

**Note:** You cannot freeze or partially freeze a main track.

### Freeze points on an audio or instrument track

You can freeze at any of the following points on an audio or instrument track:

- An instrument plug-in and MIDI FX plug-in if inserted (instrument track only)
- A multitrack tape extension
- The API Vision Console extension (which can be ordered before standard insert plug-ins, or in any standard insert plug-in position)
- Any of the standard insert plug-ins 1-8

![freeze-up-to-points-tracks.png](Bouncing%20and%20Freezing%20Tracks_assets/24fa81fe104f55e6ed220f2721f154d61c3a1143.png)

### Freeze points on a bus track

You can freeze at any of the following points on a bus track:

- The master tape extension (if configured pre fader)
- The API Vision Console extension (which can be ordered before standard insert plug-ins, or in any standard insert plug-in position)
- Any of the standard insert plug-ins 1-8
- The master tape extension (if configured post fader)

![freeze-up-to-points-bus.png](Bouncing%20and%20Freezing%20Tracks_assets/f851fb9c06f07b921859f9583c3f7040f6801a95.png)

 

### To freeze up to a specific point on an audio, instrument, or bus track

1.  In the Mixer view or in the Focus channel, find the point at which you want to freeze the track.
2.  Click ••• to view the options menu for that item.
3.  Choose Freeze Up To This Insert.

![freeze-up-to-insert-menu.png](Bouncing%20and%20Freezing%20Tracks_assets/2eec00076231ad2b68fb3190052ae9518910acf4.png)

The track is frozen up to the selected insert point. Frozen audio clips appear on the timeline for all audio sections. All frozen plug-ins, instruments, and extensions are grayed out and uneditable. Plug-ins and extensions beyond the freeze point can still be edited.

## Freezing multiple tracks with track groups or selection groups

When you apply a freeze or unfreeze operation with multiple tracks selected in a track group or with a selection group, all selected or grouped tracks are frozen or unfrozen. 

**Note:** Track Freeze is controlled by the Mixing attribute in track groups.

------------------------------------------------------------------------

# How Track Freeze Affects Your Tracks

Frozen tracks are rendered as audio tracks and played back as audio by LUNA. If there are silences or spaces in a track, separate clips are rendered only for the audio portions of the track.

## Time signature and tempo changes

You can change session time signatures and tempos and frozen tracks will follow those changes. Frozen instrument and bus tracks use the Polyphonic warp algorithm. On audio tracks that have been frozen, you can change the warp algorithm. You cannot change the warp algorithm on a frozen instrument or bus track. 

## Frozen track appearance

In the Timeline view, frozen tracks appear as grayed out audio tracks. Instrument tracks show an overlay of the waveform and the MIDI data. When you hover your mouse over a frozen track in the timeline, "Frozen" appears.

![frozen-tracks-appearance.png](Bouncing%20and%20Freezing%20Tracks_assets/43e3b703b34a1ef336bf8acf82f90bfc8d1c64e4.png)

Any silent or muted regions of a track are replaced with silence, and not included in the frozen audio clips. Reverb and delay tails are intelligently calculated and included in frozen tracks. 

## Available functions on frozen tracks

In the Timeline and Mixer view, you can adjust the following settings for a frozen track.

- Volume
- Panning
- Solo
- Mute
- Sends, send volume, send mutes, send panning, and send pre/post routing (note that sends to a frozen bus are also frozen)
- Automation (for parameters that are not frozen)
- Track show/hide
- Track tempo/time signature changes
- Cues, cue volume, cue mutes, pre/post
- Insert plug-ins can be added after any frozen insert plug-ins
- Console and tape extensions can be added if none were on the track when it was frozen, or console/tape extensions were not frozen
- Sidechaining with a frozen track as an audio source, and sidechaining to a an insert-plug-in that is added after any frozen plug-ins

## Unavailable functions on frozen tracks in Timeline view

In the Timeline view, the following functions are unavailable.

- Editing waveform or MIDI data on a track
- Moving, cutting, duplicating, copying, or pasting a clip
- Clip options (clip pitch, clip gain, renaming a clip)
- Trimming or fading a clip
- Record-enable and input-enable buttons
- Track versions
- Converting a track from stereo to mono or mono to stereo

## Unavailable functions on frozen tracks in Mixer view

In the Mixer view, the following functions are disabled and grayed out for instruments, extensions, and plug-ins that are before or at the freeze point.

- Insert plug-ins that are on the track when frozen
- Instruments
- MIDI FX
- Tape extensions that are on track when frozen
- Summing extensions (note that you can still see metering for frozen summing extensions)
- Console extensions that are on on a track when frozen
- Track inputs
- Record-enable and input-enable buttons
- Trim control in the utility row
- Track conversion (stereo to mono or mono to stereo)

In both Mixer and Timeline views, any View items that cannot be edited or automated are shown in the View browser with an F, and you cannot edit or automate these items.

![frozen-view-items.png](Bouncing%20and%20Freezing%20Tracks_assets/59a70e77fd420d69dff0bc8ecc80f2e4a7abe53a.png)

 

<span class="wysiwyg-font-size-small">251230</span>

