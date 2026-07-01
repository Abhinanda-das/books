---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041428432-Working-with-Audio-in-the-Timeline.html'
converted_at: 2026-05-31T13:44:53Z
tool: htmlq+pandoc
title: 'Working with Audio in the Timeline'
word_count: 6295
---

# Working with Audio in the Timeline


## In this article

- [Syncing Clips to Tempo](#h_1d783205-54c8-4922-987c-749e5197a377)
- [Adding Audio Files and Tracks](#h_5fa64be2-9fce-4e24-9cd8-68674922f5ca)
- [Assigning Track Colors](#h_0f1ee8de-a7c3-442b-ad7d-094a35b90130)
- [Comping Tracks with Versions](#h_7a244ab5-9802-4242-ac9f-a5339e8bdb17)
- [Making Tempo and Time Signature Changes](#h_65f2fc9d-ee83-4323-bab5-02bf25ec9d05)
- [Quantizing Audio](#h_01FTBRX9BXM2Z7KKHJYHSY5JG4)

------------------------------------------------------------------------

# Syncing Clips to Tempo

In LUNA, audio tracks and clips can be in two distinct modes that determine how they interact with the project’s timeline: **Clips Follow Tempo** mode or **Unsynced** mode. The primary difference between these modes is whether the audio is anchored to absolute time (audio renains the same with tempo changes) or relative time (audio stretches and contracts with tempo changes).

### Clips Follow Tempo Mode

This mode is designed for musical projects where you want your audio to stay locked to the bars and beats of the session. When this mode is active, the following behaviors apply:

- **Tempo alignment:** Clips automatically adjust their duration to match the session tempo. If you speed up the session, the clips become shorter; if you slow it down, they become longer.

- **Tick-based anchoring:** Clip start and end points, durations, edits, and fades are locked to tick values. This means they remain fixed to their specific musical positions on the tempo map regardless of tempo changes.

- **Track elements adjust with tempo changes:** All associated elements, including automation breakpoints and fades, scale proportionally when the tempo is adjusted.

- **Automatic adjustment for imported clips:** When audio files are imported or dragged onto a track in this mode, LUNA analyzes their original tempo and automatically conforms them to the current project tempo.

### Unsynced Mode

Unsynced mode is for material that should remain independent of the musical grid, such as voiceovers, sound effects, or recordings where the original timing must be preserved exactly.

- **Duration persistence:** Clips maintain their original playback duration regardless of any tempo changes made to the session.

- **Time-based anchoring:** Clips start and end on absolute time values (minutes/seconds). Because they are not anchored to the grid, the time it takes to play these events never changes.

- **Fixed track elements:** Fades and automation breakpoints are stored at fixed time values. While a tempo change might cause these elements to shift position visually on the timeline, relative to the bars and beats, their actual timing does not change.

- **Fade behavior:** In this mode, fade-ins start the clip start, but end on a tick value relative to that start. Fade-outs start on a tick value relative to the clip end and stop at the end of the clip.

## Switching from Clips Follow Tempo to unsynced mode

The following happens when you switch a track out of Clips Follow Tempo mode:

- **Duration is preserved:** The clip maintains its current length; it does not automatically revert to its original, un-stretched duration.

- **Tick markers:** LUNA automatically adds markers at the start and end of the clip to lock its exact tick-based position.

- **Anchored start point:** The clip’s start position remains anchored to its relative spot in the timeline, so it will move as the session is updated, but it will not change duration.

- **Tempo independence:** Tempo changes will no longer affect the duration of the clip.

## Switching audio from unsynced to Clips Follow Tempo mode

The following happens when you switch a track to Clips Follow Tempo mode

- **No immediate change:** The clip duration stays the same when you initially switch modes.

- **Tick anchors:** Clips are anchored to their specific tick positions on the timeline.

- **Dynamic time-stretching:** Subsequent tempo changes  now automatically time-stretch or compress the audio.

- **Editing adjustments:** All edits, fades, crossfades, and automation breakpoints also stretch or compress to stay in sync with tempo changes.

### Restoring a time-stretched or compressed clip to its original duration

To restore a clip to its original duration and remove any warping, double-click the top of the clip, and in the Clip window, click Reset Warps.

## Workflow: Changing the tempo of a song and conforming audio and instrument tracks

The typical situation for this workflow is one where you have recorded some or all of the session tracks, and decide to change the tempo of the session to change the feel, for creative or other reasons.

To change session tempo, you’ll need to configure your session to follow the tempo, and set the Warp algorithm for the different types of tracks. 

### Recommended warp algorithms

As a starting point, the following warp algorithms are recommended:

- **LUNA Razor Blade** for drum loops and multitrack drum tracks. Razor Blade will maintain the best phase coherence and the most accurate transients and tails for time-stretched or time-compressed drum tracks, though with extreme stretching or compressing, audio artifacts can occur. 
- **LUNA Polyphonic** or **Polyphonic** for polyphonic material, instruments, and vocals.
- **Monophonic** for vocals or single-note lines. For example, a bass line or a monosynth without complex overtones might sound better with the Monophonic algorithm than the Polyphonic algorithm.

You can easily change Warp algorithms while material plays to audition different algorithms.

**Note:** You can apply Warp algorithms to a track, individually to audio clips, or to the entire session. You can also apply different algorithms to different clips on the same track.

### To configure your session to follow tempo

When creating a session, click Clips Follow Session Tempo.

![clips-follow-session-tempo-create-session.png](Working%20with%20Audio%20in%20the%20Timeline_assets/0aba61b140882025c10c09ea06edd7b607b4dd29.png)

After creating a session, you can change the session globally to follow tempo changes.

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

Click at the top of BPM in the Control Bar, or click the icon next to BPM, and toggle Clips Follow Tempo under Session Tempo Mode.

![clips-follow-tempo-toggle.png](Working%20with%20Audio%20in%20the%20Timeline_assets/fc924d07cc6445301fcaab66e58329a3f34f35c8.png)

</div>

### To configure the warp mode for your session

Click at the top of BPM in the Control Bar, or click the icon next to BPM, and choose a warp mode from the Session Warp Mode menu.

![session-warp-mode.png](Working%20with%20Audio%20in%20the%20Timeline_assets/2d45de10805875661c2ab40f963214bcea8b63a3.png)

### To configure the warp mode for a track 

1.  In the Timeline view, Click Warp on the track settings area.

2.  Choose a warp mode for the track.

![track-right-click.png](Working%20with%20Audio%20in%20the%20Timeline_assets/11ed6146e64f7220878c62ce150bfe9e4949e0b7.png)

### To configure an audio clip for tempo changes or warping

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  In the Timeline, double-click the header of the audio clip for which you want to change the Warp algorithm. The Clip window opens.
2.  From the Algorithm pulldown menu, choose the Warp algorithm for the clip.\
    ![clip-warp-menu.png](Working%20with%20Audio%20in%20the%20Timeline_assets/75e4d7ab7ed362a252ba815d5b99639017f1ad6d.png)\
     
3.  Click Done.

</div>

You can now make a global tempo change, or any other type of tempo change, and your audio and Instrument tracks will automatically adjust to the new tempo. See <a href="#h_ef549896-b22d-41a6-9ede-6d9d0315cf55" target="_self">Setting the tempo and making tempo changes </a>for more information.

------------------------------------------------------------------------

# Adding Audio Files and Tracks

You can import audio files by using File \> Import or Command + I. You can also drag and drop audio files into your session. 

## Importing an audio file

When you import an audio file, the file is placed at the playhead. If Sync Clips to Session Tempo is enabled for the track or the session, the clip's tempo is detected, and the clip is aligned to the grid, and stretched or compressed to fit the tempo. 

When you import an audio file into an empty session with Clips Follow Tempo enabled, you are prompted to either keep the session at the current tempo, or adjust the session to the tempo of the audio files.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="import-audio-tempo.png" file-size="79323" data-height="119" data-id="910c045c-96e0-484f-89d1-e3b0884f7efb" node-type="media" data-type="file" data-width="421" title="Attachment">

 ![import-audio-tempo.png](Working%20with%20Audio%20in%20the%20Timeline_assets/793ddb2f8116e9bd70cee73d5fa6d9f09866eecd.png)

</div>

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="import-audio-tempo.png" file-size="79323" data-height="119" data-id="910c045c-96e0-484f-89d1-e3b0884f7efb" node-type="media" data-type="file" data-width="421" title="Attachment">

</div>

</div>

Choose whether to keep the session at the current tempo, or to use the tempo from the imported audio file.

## Importing sessions

You can choose a LUNA session to import with this command. When you import a session with File \> Import or Command + I, the most recent version of the session is imported, and you can then choose import options for each track and session settings. To choose other versions when importing a session, use File \> Import Session Data or Option + I. See Importing Session Data for more information.

## Adjusting tempo after importing a file or files

When you import a file or files and your session or track is in Sync Clips to Tempo mode, the file or files are analyzed for tempo, and LUNA applies a guess as to the file tempo. However, other candidate tempos are available in the Clip controls popover.

The Clip popover lets you choose from other possible tempos identified for the clip, and to conform the clip to the session tempo, or conform the session to the clip’s tempo.

![clip-tempo-callouts.png](Working%20with%20Audio%20in%20the%20Timeline_assets/f497a52089c79098707d0e5fffcf29703557bc24.png)

#### To adjust clip tempo and conform the clip or session to tempo

1.  Double-click the name of the clip or the empty area next to the pitch control to open the Clip controls.\
    ![open-clip-controls.png](Working%20with%20Audio%20in%20the%20Timeline_assets/abd0c78f9de6a392b9f4bd719b08662d254fdd63.png)

2.  In the Click popover, you can click a tempo in the Tempo Candidates area to set that tempo for the clip. Candidate tempos are listed from green to orange, in order of candidate confidence.

3.  To align the clip to the session tempo (warping the clip to match the session tempo) click Align Clip to Session Tempo. The clip is warped to match the selected candidate tempo to the session’s tempo.

4.  To set the session tempo to the tempo of the clip, click Set Session Tempo to (tempo and meter).

## Dragging an audio file into the Tracks browser

You can drag audio files into the tracks browser. Each audio file will be created as a new track. The previous tempo rules apply.

## Dragging an audio file onto the Timeline

You can drag audio files directly into the timeline. The previous tempo rules apply; however, audio that you drag to the timeline is placed at the spot where you drop it. If you drop an audio file onto an existing track or tracks, the audio is added on that track or those tracks at the location where you dropped it. If you drop the audio into an empty part of the workspace, the audio is placed at the time location where you dropped it on a new track or tracks.

------------------------------------------------------------------------

# Assigning Track Colors

There are three color hotspots you can click to assign track colors:

- The colored strip at the bottom of a track in the Mixer
- The colored strip at the left of a track in the Timeline
- The colored square to the left of a track name in the Tracks browser

## To assign colors

1.  Click one of these locations to assign a track color. The Color browser opens, with a color wheel and a block of your recently used colors at the bottom of the color wheel. 
2.  On the Color wheel or in the block of used colors, click the color to use. The color is assigned to the track controls and track clips. 
3.  To exit the Color browser click Done or press Esc.  

<div layout="align-start" node-type="mediaSingle" data-width="90">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="assign-colors.png" file-size="192507" data-height="405" data-id="c5125eb2-7bd0-4950-991b-ca4320519e64" node-type="media" data-type="file" data-width="546" title="Attachment">

![assign-colors.png](Working%20with%20Audio%20in%20the%20Timeline_assets/f17630307beffdce7d5c8ff535b32e2ca5ed7a73.png)

</div>

</div>

<span id="comping"></span>

------------------------------------------------------------------------

# Comping Tracks with Versions

In LUNA, you can *comp* or create a compilation track from a recorded track to assemble a compilation of audio or MIDI on the same track or another track. The comping workflow in LUNA uses Track Versions. Track Versions are similar to what other applications may refer to as versions, playlists, or lanes.

Two methods for comping are provided here. 

- **Comp to the same track:** this method for comping assembles the comp track on the original track, by switching between versions and copying and pasting sections to either an existing track version or a new track version.
- **Comp to a different track:** this method for comping requires two tracks. With this method, you can either duplicate the track you are comping from, or you can create a blank track on which to assemble the comped track. 

## Prepare for comping

- Record a track.
- If you want to record an entirely new version, open the Versions panel, and click the plus (**+**) to create a new Version.
- To record Takes, simply loop record over a selection. A Take is the same as a version, but the name in prepended with a T to indicate it is a Take.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="versions-button.png" file-size="42026" data-height="135" data-id="92269fab-c388-4552-8bf6-88ea3e655cc9" node-type="media" data-type="file" data-width="401" title="Attachment">

![versions-button.png](Working%20with%20Audio%20in%20the%20Timeline_assets/b2dd1493d5364ef630421f01bfde994bfc30b45f.png)

</div>

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="versions-button.png" file-size="42026" data-height="135" data-id="92269fab-c388-4552-8bf6-88ea3e655cc9" node-type="media" data-type="file" data-width="401" title="Attachment">

</div>

</div>

![qs-versions-takes.png](Working%20with%20Audio%20in%20the%20Timeline_assets/000eb086419bc31b4ea9a5b3c4d5e2ac6e822c51.png)

<div layout="align-start" node-type="mediaSingle" data-width="90">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="qs-versions-takes.png" file-size="58218" data-height="114" data-id="f55814f6-7a40-4d3c-a03f-76aca7b83d25" node-type="media" data-type="file" data-width="578" title="Attachment">

</div>

</div>

## Comping to a new or existing version on the same track

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  If you want to create a new Version for the comp track, click the plus (**+**) in the Version list. Otherwise, you can easily comp to an existing version. 
2.  To easily recognize the comp track and any Versions or Takes, rename the Versions. Double-click each Version, or select the version and click the Pencil tool, and rename relevant Versions. For example, you might rename the comp track “comp,” and give descriptive names to Takes based on their content (louder, softer, aggressive, etc.).\
    \
    ![renamed-versions.png](Working%20with%20Audio%20in%20the%20Timeline_assets/31ea73860863e865e54bb2bfdd3375de2cf3387b.png)
3.  In the Versions list, select the Version on which you want to comp audio, or press Shift + ↓ or Shift + ↑ to navigate through the list.
4.  Enable Loop playback with Control+L on macOS / Alt+L on Windows, or or the Loop mode button on the transport.
5.  Select the section you want to audition and replace. 
6.  Press Play or the Spacebar. To move through the candidate takes and versions, press press Shift + ↓ or Shift + ↑, or click the different takes and versions on the Versions list.
7.  When you find a selection you want to use on the comped track, copy the selection with Command+C (macOS) / Ctrl+C (Windows), return to the main comp track with the Versions list or Shift +↓ / Shift + ↑, and press Command+V (macOS) / Ctrl+V (Windows) to paste it.

</div>

Repeat this process for each phrase or selection you want to comp. In this way, you can move through a number of versions and takes, selecting phrases and assembling a final comp track.

## Comping to a new track

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Create a new audio track and move it directly below or above the track from which you are comping.

2.  To easily recognize any Versions or Takes, rename the Versions. Double-click each Version, or select the version and click the Pencil tool, and rename relevant Versions. For example, you might rename the comp track “comp”, and give descriptive names to Takes based on their content (louder, softer, aggressive, etc.).\
    \
    ![renamed-versions-no-comp.png](Working%20with%20Audio%20in%20the%20Timeline_assets/b1735cc8ebc27f9f2ddd2823384268f54b0dc2e6.png)

3.  Enable Loop playback with Control+L on macOS / Alt+L on Windows, or or the Loop mode button on the transport.

4.  Select the section you want to comp from on the source track.

5.  Press Play or the Spacebar. To move through the candidate Versions, press Shift + ↓ or Shift + ↑, or click the Versions on the Versions list.

6.  When you find a selection you want to use on the comped track, copy the selection with Command+C (macOS) / Ctrl+C (Windows).

7.  Click the track name to select the comp track, and press Command+V (macOS) / Ctrl+V (Windows) to paste the selection. Clicking the track name retains the location selection on the target track so the paste occurs in the right location.\
    **Tip:** You can press the semicolon key ( **;** ) to move the selection down one track, or the P key to move the selection up one track.

</div>

Repeat this process for each phrase or selection you want to comp. In this way, you can move through a number of versions and takes, selecting phrases and assembling a final comped take.

 ![source-comp-track.png](Working%20with%20Audio%20in%20the%20Timeline_assets/6421ccb422a6533ef5b1318f65955d5c3100e667.png)

**Tip:** When comping from one track to another, you can use Solo Exclusive mode to quickly solo between your comp source and comp target track, without hearing duplicate or conflicting audio. To enable Solo Exclusive mode, toggle the Mix workflow and click the Solo Exclusive mode button. For more information about Workflows, see <a href="360041440592-Using-LUNA.html#h_0f5f806a-a9ff-415a-a28f-8db1acd5af64" target="_self">Using Workflows</a>.

![workflows-switch-mix.png](Working%20with%20Audio%20in%20the%20Timeline_assets/c52f247627e17a6529cddaee8edae8bc35c22499.png)

![solo-exclusive.png](Working%20with%20Audio%20in%20the%20Timeline_assets/2490123317639cc5c9ae9ba93c2563b12cf63738.png)

------------------------------------------------------------------------

# Making Tempo and Time Signature Changes

You use the Tempo and Signature rulers to specify tempo and time signature, and make tempo and time signature changes.

<div layout="align-start" node-type="mediaSingle" data-width="80">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="rulers-tempo-signature.png" file-size="60171" data-height="179" data-id="c20cb02c-e9ad-4453-8a42-6d9e5e640f9a" node-type="media" data-type="file" data-width="543" title="Attachment">

![rulers-tempo-signature.png](Working%20with%20Audio%20in%20the%20Timeline_assets/80a3faf1acfa4fc5a73417c3f31355cbd0ded075.png)

</div>

</div>

<span id="setting-tempo"></span>

## Setting the tempo and making tempo changes

When you change the session tempo, elements in the LUNA session that are tempo-based adjust to the new tempo. Instrument tracks are adjusted, and audio clips that are set to Clips Follow Tempo mode are stretched or compressed to fit the new tempo. Audio clips that are unsynced are not stretched or compressed, but LUNA keeps the start of each clip at the same relative point in the Timeline.

### To set the overall tempo of the session

- Click the BPM control. The cursor changes to a double arrow. Drag up or down to adjust the tempo by 1 BPM increments. You can click and drag to change tempo while the session is playing to hear your changes in real time.\
  ![drag-tempo.png](Working%20with%20Audio%20in%20the%20Timeline_assets/037f09895a48636754362a670912a9ab3aab8997.png)
- To type a new tempo, click to select the BPM in the control bar, type a new tempo, and press Return. 

### To set the session tempo by tapping

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  In Timeline view, double-click the session tempo in the Tempo ruler.\
    \
    ![tempo-in-temnpo-ruler.png](Working%20with%20Audio%20in%20the%20Timeline_assets/88c40996d5db6d70e8d59464d286697e38e05a43.png)
2.  The Edit Tempo popover opens. Tap the Tap button at least four times, then click Apply.\
    ![edit-tempo.png](Working%20with%20Audio%20in%20the%20Timeline_assets/bdf24121a108a30a1407b4e91fb805c9bdb22475.png)

</div>

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

**Tip:** You can close the Tempo browser by typing the Esc key.

### To set the session tempo by playing

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  In Timeline view, double-click the session tempo in the Tempo ruler.\
    \
    ![tempo-in-temnpo-ruler.png](Working%20with%20Audio%20in%20the%20Timeline_assets/88c40996d5db6d70e8d59464d286697e38e05a43.png)\
    The Edit Tempo popover opens.\
    \
    ![edit-tempo.png](Working%20with%20Audio%20in%20the%20Timeline_assets/bdf24121a108a30a1407b4e91fb805c9bdb22475.png)\
     
2.  Click Listen, then play through a record or input-enabled track. As you play, LUNA determines the tempo. Once the tempo is determined, click Apply to set the tempo.

![edit-tempo-listen.png](Working%20with%20Audio%20in%20the%20Timeline_assets/3247c105df738589bf0c563f82ada2afc91be182.png)

</div>

</div>

 

### To add a tempo change

1.  Place the playhead in the timeline where you want to apply the tempo change.

2.  Click on the Tempo ruler control area. 

    ![tempo-ruler-event-area.png](Working%20with%20Audio%20in%20the%20Timeline_assets/0fe170cb5deb49ec417f36428221057aa863b653.png)

3.  The Add Tempo popover opens. Type the tempo, tap in a tempo with the Tap button, or click Listen and play in a tempo. When you have specified the tempo, click Apply.

![add-tempo.png](Working%20with%20Audio%20in%20the%20Timeline_assets/e4ed4bfebce06bf44f13a5ffd2e2742d41ea48ff.png)

The tempo change is added at the playhead location.

## Extract tempo from a selection or session

1.  Hover over the Tempo ruler, and click Extract, or click the top of the BPM area in the Control Bar and click Extract.\
    ![extract-tempo-menu.png](Working%20with%20Audio%20in%20the%20Timeline_assets/8a21572337b51555c953c7602c58226656e755ca.png)\
     
2.  Select Selection or Entire Session. The tempo is extracted.
3.  To move the downbeat to the correct first beat (if incorrect), drag the downbeat marker (labeled MOVE DOWNBEAT) to the correct position. 

**Note:** You can more easily drag the downbeat marker to the correct position if SNAP is disabled, or you can use the Command (macOS) or Alt (Windows) modifier when dragging. 

![move-downbeat-callouts.png](Working%20with%20Audio%20in%20the%20Timeline_assets/57296532be8cf1eef1c3be1c158280c6444409af.png)

#### Extracted tempo overview

![tempo-extracted.png](Working%20with%20Audio%20in%20the%20Timeline_assets/9698d71639f4a1da942732d4d92f8594e95be35e.png)

- The Tempo area shows four possible candidate tempos for the session or selection. Cclick a square to accept that tempo.
- Colored squares from green to orange indicate confidence in the tempo candidates.
- Typically, tempos identified are multiples of each other, with possible meter variations. In the example above, 74 BPM, 37 BPM, and 149 BPM are all identified as possible tempo candidates, and 4/4 and 6/8 are identified as possible meter candidates.
- Tempo markers are placed on the tempo ruler to indicate tempo events and tempo variations recognized by LUNA.

### Conforming extracted session tempo

1.  Click a tempo in the Candidates section to accept that tempo.
2.  To set the session tempo to the detected tempo, double-click an audio clip in the session. \
    ![clip-tempo-callouts.png](Working%20with%20Audio%20in%20the%20Timeline_assets/f497a52089c79098707d0e5fffcf29703557bc24.png)\
     
3.  To set the session tempo to the current clip tempo, click Set Session Tempo To (tempo and meter).

## Changing tempo over time

You can draw a tempo change over time.

### To draw (automate) a tempo change

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Open the tempo lane by clicking **\>** on the Tempo ruler. The tempo lane opens and shows the tempo as a line.\
    \
    ![open-tempo-lane.png](Working%20with%20Audio%20in%20the%20Timeline_assets/a738e003f8a1b21240c65eb67bdafece39de7c2b.png)

2.  Control+Click to change the cursor to a pencil. With this cursor you can draw tempo events. Tempo events snap to the grid if Snap is enabled.\
    \
    ![tempo-draw-grid.png](Working%20with%20Audio%20in%20the%20Timeline_assets/a6831cd8c7d51ff2edb0d251ae3c5e554a491648.png)

3.  To disable snapping while drawing tempo events, press Command+Control (macOS) while you draw tempo events. In Windows, disable Snap to draw tempo events without snapping.

    \
    ![tempo-draw-no-grid.png](Working%20with%20Audio%20in%20the%20Timeline_assets/3619889687ca6dc5020f17ffcf6c15d96bc4a6df.png)

</div>

###  To edit tempo events (automation)

- Click and drag a tempo event up or down.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="click-drag-tempo-event.png" file-size="17828" data-height="152" data-id="c686c641-713b-40f1-9343-507462e68f0c" node-type="media" data-type="file" data-width="223" title="Attachment">

![click-drag-tempo-event.png](Working%20with%20Audio%20in%20the%20Timeline_assets/9f5cfe40d6cec7973826560986ca788a6b9bb4f5.png)

</div>

</div>

- To edit a range of events, click and drag above or below the tempo line to select a range. Click on a tempo line and drag up or down. 

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="edit-tempo-event-range.png" file-size="35083" data-height="184" data-id="f22f2326-37af-4546-8378-f691163a6ec8" node-type="media" data-type="file" data-width="359" title="Attachment">

![edit-tempo-event-range.png](Working%20with%20Audio%20in%20the%20Timeline_assets/6e58afeecdc57d0b4e06c29568569ccb78ff4eac.png)

</div>

</div>

### To delete tempo events

- Double-click a single tempo event to delete it.
- To delete a range of tempo events, click and drag above or below the tempo line to select a range. Press the Delete key to delete the range of tempo events.

<span id="setting-signature"></span>

## Setting the time signature and making meter changes

When you change time signature, elements in the LUNA session do not change, but rather, the way they are counted changes. For example, if you add a change from 4 / 4 time to 3 / 4 time, bar lines will move and the click will indicate a three bar measure instead of a four bar measure. However, audio and MIDI will not move, stretch, or expand.

### To set the time signature of a session

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Hover over the Signature ruler and click the plus (+) symbol. The Time Signature browser opens.\
    \
    ![signature-click-area.png](Working%20with%20Audio%20in%20the%20Timeline_assets/ee3d546eaf6e71ffb9c553a028a920e7354f7fb4.png)\
    \
    \
    ![time-signature-browser.png](Working%20with%20Audio%20in%20the%20Timeline_assets/a8b54fd20d9151b0cc53979a33f0f75ca29daab2.png)
2.  Type the bar at which you want the time signature to start.
3.  Type the number of beats in a bar.
4.  From the Note pull down, choose the note value that represents one beat. For example, choose 4 for a quarter note, or 8 for an eighth note.
5.  Press Return or click Apply. 

</div>

The Time Signature is changed on the ruler, at the bar you specify.

### To add a time signature change

1.  Click in the session where you want the time signature change to be located.
2.  Hover over the Signature ruler and click the plus (+) symbol. The Time Signature browser opens. 
3.  Type a bar number where you want the time signature change to start. The nearest preceding bar is automatically populated. 
4.  Type the number of beats in a bar.
5.  From the Note pull down, choose the note value that represents one beat. For example, choose 4 for a quarter note, or 8 for an eighth note.
6.  Press Return or click Apply. 

The Time Signature change is added to the ruler, at the bar specified.

### Other time signature operations

- Move a time signature marker on the Signature ruler by clicking the icon and dragging.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="click-drag-time-signature.png" file-size="14038" data-height="104" data-id="b1e12979-332c-4bb0-bb5d-045e2dc9df98" node-type="media" data-type="file" data-width="257" title="Attachment">

![click-drag-time-signature.png](Working%20with%20Audio%20in%20the%20Timeline_assets/6eec5c043b492d1a73541cdb3de9e5b04e452c8d.png)

</div>

</div>

 

- Edit a time signature by double-clicking the time signature marker to open the Time Signature browser. Make your changes and press Return or click Apply.  
- Delete a time signature marker by selecting the marker in the time signature ruler and pressing Delete.
- You can have the time signature markers follow your edits when arranging your session. Just be sure to select the Signature ruler along with other elements when you copy, cut, and paste elements in your session. 

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="deleting-time-signature-marker.png" file-size="21799" data-height="145" data-id="f2ee0c3d-2857-4b8d-8ffe-2c65ad0d97f1" node-type="media" data-type="file" data-width="271" title="Attachment">

![deleting-time-signature-marker.png](Working%20with%20Audio%20in%20the%20Timeline_assets/e13dcad1a9b3cf155b13e6ca8bf3c4e670ff5fca.png)

</div>

</div>

<span id="markers"></span>

------------------------------------------------------------------------

# Using Markers

Markers are an easy and colorful way to mark locations such as verses, choruses, or any other sections in your session. You can use markers to define locations, and easily navigate between locations in your session. You can resize the marker ruler vertically to easily see section changes.

## To add a marker

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Click a location in the session or on a ruler.
2.  Hover over the Markers ruler, and click anywhere on the highlighted bar, or press Enter (if you have a keyboard with a Numeric Keypad).\
    \
    ![markers-ruler-add.png](Working%20with%20Audio%20in%20the%20Timeline_assets/d7414ee31da249f8f31785417b22e6483cd710ce.png)
3.  In the Marker browser, specify the Start location. The location of the playhead is prefilled.
4.  Type a name for the marker.
5.  Choose a marker color.
6.  You can add optional comments in the Comments box.
7.  Press Return or click Apply to save the marker.

![marker-dialog-add.png](Working%20with%20Audio%20in%20the%20Timeline_assets/0965354b3d70f39af419cfc8ecfe878d709b9d86.png)

</div>

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="marker-dialog-add.png" file-size="75876" data-height="579" data-id="fb78eb8c-77f4-4ed8-bf54-2fcbb8eaa390" node-type="media" data-type="file" data-width="242" title="Attachment">

**Tip:** To quickly add a marker as recording or playback is occurring, press Enter twice on the numeric keypad. Multiple markers added this way are automatically numbered, and automatically cycle through the marker colors.

</div>

</div>

### To edit a marker

1.  Double-click the name of a marker on the marker ruler. The Marker browser opens.
2.  Edit the options for the marker, and press Return or click Apply.

The marker is updated with the options you set.

### Other marker operations

- To move a marker, click and drag the marker.

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="marker-moving.png" file-size="10652" data-height="57" data-id="d2cea83d-05e8-4726-89e2-ba713629d2b8" node-type="media" data-type="file" data-width="208" title="Attachment">

![marker-moving.png](Working%20with%20Audio%20in%20the%20Timeline_assets/73cf3693d775239158c2e8469fdfa2d06a48552d.png)

</div>

</div>

 

- To delete a marker, select the marker, and click Delete in the Marker browser.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div class="wysiwyg-text-align-center" collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="marker-delete.png" file-size="20242" data-height="115" data-id="42470bee-bc7f-4308-a3e8-df42b0d42d74" node-type="media" data-type="file" data-width="255" title="Attachment">

![marker-delete.png](Working%20with%20Audio%20in%20the%20Timeline_assets/3069651d25126f09dde2dc492a3dda08ef4451e2.png)

</div>

</div>

 

- To move the playhead to a marker, click the marker name. 
- To make a selection to a marker, place the playhead where you want to start the selection, then hold Shift and click the marker.
- You can copy, cut and paste markers by selecting on the Markers ruler. Make sure to select the start of the marker to copy or cut the marker.
- When you edit items on any other ruler, or audio or MIDI clips in the Timeline, you can copy, cut, paste, and delete markers along with those items by including the Markers ruler in your selection, or selecting and editing on the All Tracks ruler. Note that only markers that have their start selected are edited with other items.
- To move the playhead to the next marker, press Control+Option+’ (macOS) or use the menu command Navigation \> Selection \> Move to Next Marker.
- To move the playhead to the previous marker, press Control+Option+L (macOS) or use the menu command Navigation \> Selection \> Move to Previous Marker.

### To resize the Markers ruler

1.  At the right of the Markers ruler, click the \> to expand the Markers ruler.
2.  Drag the bottom edge of the Markers ruler to resize the ruler.

<div layout="center" node-type="mediaSingle" data-width="616" width-type="pixel">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="markers-ruler-resize.png" file-size="51343" data-height="249" data-id="e74cc2f1-54fa-4988-9841-6b92e9fcddb0" node-type="media" data-type="file" data-width="616" title="Attachment">

![markers-ruler-resize.png](Working%20with%20Audio%20in%20the%20Timeline_assets/cd011ee874bfa3efc13822ebb458f11f06a02408.png)

</div>

</div>

------------------------------------------------------------------------

# Quantizing Audio

You can quantize single or multiple audio clips and selections to any grid increment. Audio is quantized using detected transients and warp markers, which are added automatically to snap transients that are within the quantize settings to the specified grid.

Quantize warp markers differ from warp markers that you add manually, or manual warp markers:

- Quantize warp markers are updated, moved, deleted and replaced automatically when you update or change quantize settings.
- Quantize operations will not move or delete any manual warp markers you have placed.
- If you edit a quantize warp marker, that marker then becomes a manual warp marker, and further quantize operations do not move or delete it.

## Quantizing multiple audio tracks

When multiple audio tracks are quantized (through selection grouping or track groups) warp markers are added to all grouped tracks at every detected quantize point. You can specify tracks that have transient detection and quantizing priority (for example, kick and snare tracks in a drum group) to make sure that quantizing prioritizes those tracks.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="priority-group-warps.png" file-size="45771" data-height="431" data-id="788375ea-19c4-4d67-9998-97b80b76fd91" node-type="media" data-type="file" data-width="434" title="Attachment">

![priority-group-warps.png](Working%20with%20Audio%20in%20the%20Timeline_assets/1c7a3a23a2c03b17b99063bbde7ca5f90cd4511b.png)

</div>

</div>

 

### How prioritized tracks are quantized

When tracks in a group or selection group are prioritized, and selection grouping or track grouping is enabled, the quantize operation checks those tracks for transients within the range of the quantize grid first, and adds warp markers to all tracks (in a track group or selection group with the prioritized tracks) when it detects such transients on the prioritized tracks. This is useful when editing drums, for example, to prevent a secondary track (for example, a room microphone track) from overriding a snare or kick track, to prevent phasing and timing issues.

### How non-prioritized tracks are quantized

When multiple tracks are selected for quantizing, selection grouping or track grouping is enabled, and a transient is detected on a prioritized track, warp markers are added to all selected tracks (in a track group or selection group with the prioritized tracks) at that transient. The quantize operation snaps all warp markers to the grid according to the quantize settings.

When there is no transient on a priority track within a grid value and range, transients on non-prioritized tracks are used to quantize. In that scenario, if a transient is detected within the specified grid value and range, warp markers are added to all tracks based on the non-priority track transient, and snapped to the grid according to the quantize settings.

## Setting group editing priority

You can set group editing priority from the track name popover, from the track group settings, or from the Quantize settings view.

#### Set group editing priority from the track name popover

1.  Double-click on the track name in the mixer or timeline.
2.  Select Prioritize for Group Editing to prioritize the track.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="prioritize-track-popover.png" file-size="27981" data-height="224" data-id="a878f132-76de-40d1-99c2-2af19ce7bc43" node-type="media" data-type="file" data-width="451" title="Attachment">

![prioritize-track-popover.png](Working%20with%20Audio%20in%20the%20Timeline_assets/4fe65e1a6dac7940d0f42921efa0437eac920586.png)

</div>

</div>

 

#### Set group editing priority from the track group settings

1.  To edit an existing group, right-click or Control-click on the track group in the Groups list, and click Edit… To make a new track group, select the tracks you want to add to the track group, then select Track \> New Track Group from the LUNA menus, or press Command+G (macOS) / Ctrl+G (Windows).

2.  In the grouped tracks list, click the diamond for any tracks you want to prioritize. Tracks that are prioritized have solid diamonds, and non-prioritized tracks have hollow diamonds.\
    \
     

    <div layout="center" node-type="mediaSingle" data-width="">

    <div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="prioritize-tracks-groups.png" file-size="96443" data-height="534" data-id="4a4cb91f-2480-4a25-8d2d-bdece3052b6c" node-type="media" data-type="file" data-width="431" title="Attachment">

    ![prioritize-tracks-groups.png](Working%20with%20Audio%20in%20the%20Timeline_assets/510579ef336d85de6cf5996eb91e5f590bd9e4fd.png)

    </div>

    </div>

     

3.  Save the group.

#### Set group editing priority from the quantize settings

1.  Make a selection. You can select a range of audio on one or more tracks, one or more clips, or whole tracks.
2.  In the Priority section under Grouping, select whether to use selection grouping, track groups, or whether grouping is off.
3.  In the tracks list, click the diamond for any tracks you want to prioritize. Tracks that are prioritized have solid diamonds, and non-prioritized tracks have hollow diamonds.

 

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="prioritize-from-quantize.png" file-size="68429" data-height="426" data-id="4301ff6a-7d0b-4a72-a626-d5aecdf74514" node-type="media" data-type="file" data-width="465" title="Attachment">

![prioritize-tracks-groups.png](Working%20with%20Audio%20in%20the%20Timeline_assets/510579ef336d85de6cf5996eb91e5f590bd9e4fd.png)

</div>

</div>

## Quantize priority grouping

The priority grouping setting in the quantize settings determines how multiple tracks are quantized, along with prioritized tracks.

There are three options for quantize priority grouping:

- **Selection**: When Selection grouping is selected, All selected tracks are quantized as a selection group. Any prioritized tracks apply to all selected tracks. This option quantizes all material to any prioritized tracks, and then to the most prevalent transients (typically, drums or other constant rhythmic material)
- **Track Groups**: When Track Groups grouping is selected, all track groups in the selection are quantized separately. Within each track group, prioritized tracks determine how tracks are quantized. Quantize operations do not interact between track groups. This option preserves phase in groups (for example, drum tracks), while maintaining separation for material of different types.
- **Off**: When grouping is Off, all selected tracks are quantized independently. This option works best for material where the tracks have independent rhythmic material that should not be quantized to other tracks.

![priority-selection.png](Working%20with%20Audio%20in%20the%20Timeline_assets/0aaedcc48890cdfa21cc98812a99718d7700e550.png)

 

![priority-track-groups.png](Working%20with%20Audio%20in%20the%20Timeline_assets/fa30056afa9145a6f044696f8d9e211511dde104.png)

 

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="priority-selection.png" file-size="95298" data-height="480" data-id="7329f085-f625-491f-b035-154a26aacb48" node-type="media" data-type="file" data-width="585" title="Attachment">

![priority-off.png](Working%20with%20Audio%20in%20the%20Timeline_assets/226d09859ab36acdc497698fad4a4731df6ea5a4.png)

</div>

</div>

 

<div layout="center" node-type="mediaSingle" data-width="">

<div data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="priority-off.png" file-size="87140" data-height="482" data-id="5a00f23e-c380-451b-b5ad-0d473a57ce5b" node-type="media" data-type="file" data-width="577" title="Attachment">

</div>

</div>

## Quantize parameters

The following parameters are supported.

- **Grid:** Quantizes audio tracks based on the selected interval, ranging from **BAR** (whole notes) to **/64** (64th notes). Supports **Dotted** values, **Triplet** values, or a combination of both.

- **Follow Snap Setting**: Automatically matches the quantization to the current **Snap Grid** setting.

- **Swing:** Shifts every other grid boundary by a specified percentage (**0–100%**). At **100%**, the audio is shifted 2/3 of the way toward the next grid line to create a "shuffle" feel.

- **Strength:** Determines how aggressively the audio is pulled toward the grid. At **50%**, transients move halfway to the grid line; at **100%**, they are snapped perfectly to the grid.

- **Range:** Defines the "capture zone" for transients. The default **50%** detects audio within 1/4 of the grid value on either side of the line.

  - **Preventing mis-quantization:** By narrowing the range, you ensure that only notes played relatively close to the beat are moved. This prevents LUNA from accidentally shifting a note that was played significantly early/late toward the wrong grid line.\
    For example, on a **1/4 note grid**, a **50% range** captures audio within 1/16 note of the grid line. A **100% range** expands that window to 1/8 note on either side.

- **Auto Apply:** Provides near real-time visual and audible feedback as you adjust settings. When enabled, clicking a grid value applies the quantization immediately. note that when Auto Apply is disabled, you must manually click **Quantize** to see or hear changes. 

- To clear all quantization warps, click **OFF**.

## Quantize examples

The following examples show the results for different settings when quantizing a selection with multiple drum tracks.

### Quantize OFF

In this example, the audio selection is not quantized. Note that Auto Apply is enabled, and OFF is selected as the Grid value.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="quantize-example-none.png" file-size="147494" data-height="546" data-id="1c1cddd3-b5b1-4369-b242-c6bcd8c84caf" node-type="media" data-type="file" data-width="868" title="Attachment">

![quantize-example-none.png](Working%20with%20Audio%20in%20the%20Timeline_assets/71db2f6be006d21656b94173c87aefdc991cf743.png)

</div>

</div>

 

### Quantize quarter notes

In this example, the audio selection is quantized to quarter notes. Note that Auto Apply is enabled, and /4 is selected as the Grid value.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="quantize-example-4th.png" file-size="151125" data-height="543" data-id="449f5647-95ad-4671-9e0f-3ff0c5e1d930" node-type="media" data-type="file" data-width="844" title="Attachment">

![quantize-example-4th.png](Working%20with%20Audio%20in%20the%20Timeline_assets/fa889d70633a94a7d8149fc19e7bc24a65252769.png)

</div>

</div>

 

### Quantize eighth notes

In this example, the audio selection is quantized to eighth notes. Note that Auto Apply is enabled, and /8 is selected as the Grid value.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="quantize-example-8th.png" file-size="152206" data-height="543" data-id="d8423004-17d8-468b-b7de-2bf557210094" node-type="media" data-type="file" data-width="832" title="Attachment">

![quantize-example-8th.png](Working%20with%20Audio%20in%20the%20Timeline_assets/cad038afe1cdbc37e7e147d38991946f289384b6.png)

</div>

</div>

 

### Quantize sixteenth notes

In this example, the audio selection is quantized to sixteenth notes. Note that Auto Apply is enabled, and /16 is selected as the Grid value.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="quantize-example-16th.png" file-size="144888" data-height="544" data-id="29c3d1ef-36a5-4dc0-a5b3-4369ce12f36c" node-type="media" data-type="file" data-width="849" title="Attachment">

![quantize-example-16th.png](Working%20with%20Audio%20in%20the%20Timeline_assets/cc8d2dbccdbe0d91db0aa5a6a04bd203de525df1.png)

</div>

</div>

 

#### To quantize audio tracks:

1.  Make a selection. You can select a range of audio on one or more tracks, one or more clips, or whole tracks. Quantize operations follow your selection group and track group settings.

2.  To see the warp markers and quantize updates in real time, choose Warps view.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="choose-warps.png" file-size="60140" data-height="244" data-id="69187fe5-b0ea-47db-a8e7-e2542d936f94" node-type="media" data-type="file" data-width="530" title="Attachment">

    ![choose-warps.png](Working%20with%20Audio%20in%20the%20Timeline_assets/c8ec138e475d67a9b669d7bece511fbc9dc3f3ea.png)

    </div>

    </div>

     

3.  Press Command+Shift+U (macOS) / Ctrl+Shift+U (Windows) or select Edit \> Quantize Settings to open the quantize panel. You can also press the Q in the header of an audio clip, though this will change your selection unless you have enabled a track group.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740407" context-id="225740407" file-mime-type="image/png" file-name="audio-quantize.png" file-size="71803" data-height="557" data-id="773dc67d-e50c-453f-aa22-e9d08d625c82" node-type="media" data-type="file" data-width="256" title="Attachment">

    ![audio-quantize.png](Working%20with%20Audio%20in%20the%20Timeline_assets/b41e2065383b7c0b5666c510b3c667e4e8a6c73f.png)

    </div>

    </div>

     

4.  To preview your Quantize choices in real time, select Auto Apply.

5.  Choose a grid value to which to quantize notes. You can select from bar lines 64th notes, and dotted or triplet modifiers.

6.  To follow the Snap grid setting, click Follow Snap Setting.

7.  To adjust the amount of swing from 0 to 100%, move the Swing slider.

8.  To adjust quantize strength, move the Strength slider from 0 to 100%.

9.  To adjust the quantize detection range, move the Range slider from 0 to 100%.

10. Under Priority Grouping, select whether to use Selection grouping, Track Group grouping, or no grouping (OFF) to quantize the audio tracks.

11. Click Quantize to apply your settings.

**Note:** If Auto Apply is enabled, any setting you change will update in your audio track or tracks.

**Tip:** To remove any quantization in your selection, click OFF.

<span class="wysiwyg-font-size-small">251224</span>

