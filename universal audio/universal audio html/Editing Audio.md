---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041866811-Editing-Audio.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'Editing Audio'
word_count: 4309
---

# Editing Audio


You can easily edit audio using a single, context-sensitive editing tool.

## In this article

- [Resizing and Zooming the Audio Track](#h_189bf296-4301-4744-8d0f-cc500b72aeaa)
- [Audio Clips and Fades](#h_01HYCW4WT72F9BCAVCAZHH2HPA)
- [Cutting, Copying, and Pasting Audio](#h_01HYCW4WT747302AZ7XMCC2J2T)
- [Nudging Audio, MIDI, and Selections](#h_01F85PK337HK9BHVP5QCK53BH2)
- [Duplicating Audio](#h_01HYCW4WT720MT2X6QW5DG8ZDE)
- [Shifting Audio](#h_38f6ad81-f353-4772-8dfb-ea9167ee81cd)
- [Trimming an Audio Clip](#h_450eb299-33f9-45fe-a5ab-3e71e3633678)
- [Selecting Within an Audio Clip](#h_7a1640bd-1ffe-44f4-b4d1-7a64f4e9769c)
- [Moving or Copying an Audio Clip](#h_9b4385be-2a6f-4033-94a8-8e1073a139c1)
- [Reversing Audio](#Reversing-Audio)
- [Navigating Between Clip Transients](#h_9bed0129-3c9d-46c2-9d5e-48664e945f1f)
- [Navigating Between Bars](#h_95bd4166-f6fc-4099-805a-eea4cd91dc97)
- [Separating Audio Clips](#h_740b91a1-5e2f-41a6-9d9a-3b01d7ae60b8)
- [Healing (Recombining) Separated Clips](#h_abf32634-d9f3-4923-91a7-c7d45d54b6b1)
- [Consolidating Audio Clips](#h_1d91bf4d-a8a4-4a2e-b7b7-5ce67250a6d1)
- [Working with Fades on Audio Clips](#h_fbe8026d-4108-41f7-a8c5-343fa2b8bfc5)
- [Crossfading Between Audio Clips](#h_689d61bf-346d-4824-8c12-a19916258f2c)

 

<span id="resize-audio"></span>

 

------------------------------------------------------------------------

# Resizing and Zooming the Audio Track

You can resize all audio tracks to simplify editing. At the top of the timeline tracks area, below the Rulers, click the Tracks icon, and choose a new track height size.

![qs-resize-all-tracks.png](Editing%20Audio_assets/e89e0f5a0aea902465ed25f7b377b3a06eb69919.png)

 

This resizes all tracks to the new size.

 

![qs-track-heights-audio.png](Editing%20Audio_assets/98257507c46272762af710edc7bd9d78c673cfaa.png)

 

- To resize selected tracks with a key command, press Ctrl+↑ or ↓ to increase/decrease track heights
- To resize all tracks with a key command, press Control+Option+↑ or ↓ (macOS) to increase/decrease all track heights
- To resize an individual track, hover over the lower edge of the Track controls area. A double arrow appears. Drag up or down to resize.

![qs-audio-resize.png](Editing%20Audio_assets/1c82cb0a0e81f70292ef30bf834c23f5a326ca52.png)

- To expand a selection to the full available editing space, press the E key (if the system is not in MIDI Keyboard Mode).
- To resize (zoom) the track horizontally, click the plus and minus buttons at the bottom of the Edit workspace (or use the keyboard shortcuts Command+\[ to zoom out, and Command+\] to zoom in on macOS or Ctrl+\[ to zoom out, and Ctrl+\] to zoom in on Windows).
- To marquee zoom (zoom to a mouse selection), press Option (macOS) or Alt (Windows) and hover your mouse. The marquee zoom tool appears, and you can click and drag to marquee zoom. Option+click in the timeline to step back through previous marquee zoom states.
- <span class="fabric-editor-annotation" data-id="546a9e5c-3075-44d5-932d-cfdc443cb4cf" mark-annotation-type="inlineComment" mark-type="annotation">On a trackpad, you can pinch in or out to zoom the timeline horizontally.</span>
- With a mousewheel, you can hold the Option (macOS) or Alt (Windows) key and scroll to zoom horizontally.

![increase-decrease-horiz-zoom.png](Editing%20Audio_assets/b2701b4bfae2676015739db632db132162da19e6.png)

## To zoom out/decrease waveform size, type:

- **macOS –** Command+Option+\[
- **Windows –** Ctrl+Alt+\[

## To zoom in/increase waveform size, type:

- **macOS –** Command+Option+\]
- **Windows –** Ctrl+Alt+\]

![zoomed-waveforms.png](Editing%20Audio_assets/86a96de18ca8aa6c48b22f17c6d2c733b1f2a08a.png)

*Zooming waveforms*

------------------------------------------------------------------------

# Audio Clips and Fades

An audio clip is a self-contained section of audio that is either recorded, imported, pasted, or duplicated on an audio track. Audio tracks can contain multiple clips, and clips can overlap or be combined or split.

You can edit audio with the Editing Tool and key commands.

When you hover the mouse cursor over an audio or MIDI clip, it becomes the Editing Tool. Where you place the cursor, and what the editing context is, determines the Editing Tool behavior.

![clips-fades-annotated.png](Editing%20Audio_assets/4ae0891a5c7e9208ae5350fa847c8c3bcd31f40c.png)

## Making selections

- To select audio, hover your cursor above the vertical middle of the clip. The cursor changes to the Select Editing Tool. \
  ![smart-tool-select.png](Editing%20Audio_assets/f9badc0275524738d1af0064c0162801a21e35fc.png) \
   
- Click and drag to the right or left to select an audio range. Selections conform to the Snap setting and grid. \
  ![smart-tool-selection-made.png](Editing%20Audio_assets/cb57e600e1f28821511d9eb35c8a9a7fee38b72a.png) \
   
- To extend or shorten a selection, press Shift, then click the location to which you want to extend or shorten the selection.
- To make a free selection when Snap is enabled, press Command (macOS) or Ctrl (Windows), then make the selection.
- To select on multiple tracks, press Shift to select multiple tracks, then make your selection.
- To extend a selection you have already made to more tracks, press Shift, then click on the tracks you want to add to the selection.

## Moving a clip

To move a clip, hover at the top or in the lower half of a clip. The move tool appears. Click and drag the clip to a new location. You can drag a clip on the same track, or to another track, if it is the same type (audio or MIDI). If you have Snap enabled, the moved clip snaps to the grid. To move without snapping to the grid, press the Command key while you drag.

![smart-tool-move-annotated.png](Editing%20Audio_assets/0f3a249959af1488195730f5597aae32af35947a.png)

 

When you move an audio clip, it can overlap an existing clip. You can see this overlapping and underlying area when dragging the audio clip. When you play a section with overlapping clips, you only hear the topmost audio clip. If you later move the clip again, any underlying clips that exist are revealed. If you fade or crossfade audio, the underlying audio can be revealed or used in the fade or crossfade, depending on the length of the overlapping and underlying audio clips.

![audio-move-overlap.png](Editing%20Audio_assets/87115e54763617e0baf1f940f11ed1313c77877d.png)

 

## Snapping to the clip start time or the playhead

When you drag a clip to another track or on the same track, you can snap the clip to the original start time by pressing the Control key while dragging, or at any time before you release the clip.

To snap the start of a clip to the playhead location, place your playhead, then Control+Click the clip.

------------------------------------------------------------------------

# Cutting, Copying, and Pasting Audio

Cut audio to remove it from the timeline and place it on the clipboard, ready to be pasted. Copy audio to place it on the clipboard without removing it from the timeline. Paste audio to place the contents of the clipboard on the timeline, at the playhead.

## Copying and pasting audio by dragging

To quickly copy a clip and drag it to a new location, Option+Click (macOS) or Alt+Click (Windows) the clip and drag it to a new location. This “copy and drag” operation retains the underlying audio structure.

## Cutting audio

To cut audio, select the audio range or clip and press Command+X (macOS) or Ctrl+X (Windows). The audio range or clip is cut, and placed on  the clipboard, ready to be pasted. When you cut audio, a gap is left in the audio file from which you cut. if you selected a clip, the clip is removed from the timeline. Note that when you cut audio, you are cutting a representation of the audio, but the cut is non-destructive, and the original audio file remains unchanged. You can drag the edges of the cut section back together (trim the clips) to restore the audio you have removed (see <a href="#h_450eb299-33f9-45fe-a5ab-3e71e3633678" target="_self">Trimming an audio clip</a>).

## Copying audio

To copy audio, select the audio range or clip and press Command+C (macOS) or Ctrl+C (Windows). The audio is copied, and placed on the clipboard, ready to be pasted.

## Pasting audio

To paste audio, place the playhead or make a selection, and press Command+V (macOS) or Ctrl+V (Windows). Note that the full length of the cut or copied selection is pasted, and the underlying audio and audio structure under the paste is not retained. For example, if you paste an audio selection over other layered clips and crossfades, those elements are not restored if you later move, cut, or delete the overlaying clip.

**Tip:** If you want to place an audio clip while retaining the underlying clip structure, Move the clip instead of pasting it, or copy and paste by Option+Clicking (macOS) or Alt+Clicking (Windows) and dragging the audio.

------------------------------------------------------------------------

# Nudging Audio, MIDI, and Selections

When you nudge audio or MIDI, you move it by a small amount, using key commands or menu items. You can nudge an audio clip, audio within an audio clip (adjusting the audio back and forwards without moving the clip boundaries), MIDI notes, and MIDI clips. If there is no selection, the nudge commands move the playhead. If there is a selection, but no clips or MIDI notes are selected entirely within that selection, the nudge commands move the selection area.

You can nudge by the following amounts:

- The current grid setting
- Bars, beats, or note divisions
- Time (from 1 millisecond to 1 second)
- Samples (from 1 to 10,000)
- Ticks (from 1 to 200)

## What is nudged?

Nudge commands nudge based on what is and is not selected. You can nudge on a single track or on multiple selected tracks.

- If nothing is selected, nudge commands move the playhead.
- If a selection is made within an audio clip, and no whole clips are selected, nudge commands move the selection only.
- If an audio or MIDI clip is selected, nudge commands move the clip.
- If an area is selected containing multiple clips, nudge commands move all completely selected clips within that selection.
- If one or more MIDI notes are selected, nudge commands move the MIDI notes.

## Setting the Nudge units and amount

Set the nudge units and amount on the Edit Workflow pane, or by starting the Nudge settings.

1.  Open the Edit Workflow by pressing the edit workflow switch or open the Nudge Settings by choosing Edit \> Nudge \> Settings… from the LUNA menus.

    ![workflows-switch-edit.png](Editing%20Audio_assets/924cd4354e29be62f8e3ce991a4e1e8b19238f6b.png)

     

2.  To the right of Nudge, click the nudge units to open the Nudge Settings popover.

    ![nudge-settings.png](Editing%20Audio_assets/ed7e8f564424a484b6ff78c60983cf1de3158338.png)

     

3.  Click to select the nudge units (Grid, Beats, Time, Samples, or Ticks).

4.  Select the nudge amount. Different selection amounts are available depending on the units you select.

5.  To specify a custom amount, type the amount in the nudge amount field and press Enter.

## Nudging a clip

The basic keys to nudge a note, clip, the playhead, or a selection are the comma ( **,** ) and the period ( **.** ). The comma nudges to the left, or earlier in time, and the period nudges to the right, or later in time.

- To nudge left, press the comma ( **,** ), select Edit \> Nudge \> Left, or click the **\<** in the Edit workflow / Nudge settings.
- To nudge right, press the period ( **.** ), select Edit \> Nudge \> Right, or click the **\>** in the Edit workflow / Nudge settings.
- To nudge left by the next higher nudge amount, press M, select Edit \> Nudge \> Left Next Amount, or click the **\<\<** in the Edit workflow / Nudge settings.
- To nudge right by the next higher nudge amount, press / , select Edit \> Nudge \> Right Next Amount, or click the **\>\>** in the Edit workflow / Nudge settings.

![nudge-clip-2k-samples.png](Editing%20Audio_assets/1d2e60e1b702ac8d7d21c1f49bb6784f7d101e3e.png)

## Nudging within an audio clip

To nudge audio within an audio clip, without moving the boundaries of the audio clip, you can use the Nudge Content commands.

**Note:** Nudge Content key commands are not currently supported in Windows. However, you can Nudge Content from the LUNA menus.

- To nudge content left, press Control + , or select Edit \> Nudge Content \> Left from the LUNA menus.
- To nudge content right, press Control + . or select Edit \> Nudge Content \> Right from the LUNA menus.
- To nudge content left by the next higher nudge amount, press Control + M or select Edit \> Nudge Content \> Left Next Amount from the LUNA menus.
- To nudge content right by the next higher nudge amount, press Control + / or select Edit \> Nudge Content \> Right Next Amount from the LUNA menus.

![nudge-content-2k-samples.png](Editing%20Audio_assets/40856734c1ae7b65002fc604a53b51ec77c3b7b8.png)

## Nudging a MIDI clip or MIDI notes

You can nudge whole MIDI clips or selected MIDI notes within one or more clips. The basic keys to nudge a clip or notes are the comma ( **,** ) and the period ( **.** ). The comma nudges to the left, or earlier in time, and the period nudges to the right, or later in time.

- To nudge left, press the period ( **,** ), select Edit \> Nudge \> Left, or click the **\<** in the Edit workflow / Nudge settings.
- To nudge right, press the period ( **.** ), select Edit \> Nudge \> Right, or click the **\>** in the Edit workflow / Nudge settings.
- To nudge left by the next higher nudge amount, press M , select Edit \> Nudge \> Left Next Amount, or click the **\<\<** in the Edit workflow / Nudge settings.
- To nudge right by the next higher nudge amount, press / , select Edit \> Nudge \> Right Next Amount, or click the **\>\>** in the Edit workflow / Nudge settings.

![nudge-midi-clip-1-16.png](Editing%20Audio_assets/d7520ba6ae442f60398c99258f76598ca37850a3.png)

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-225739774" context-id="225739774" file-mime-type="image/png" file-name="nudge-midi-notes-1-16.png" file-size="70742" data-height="564" data-id="3e97389a-06e9-4b72-b4ba-a5cce21aa47a" node-type="media" data-type="file" data-width="494" title="Attachment">

</div>

</div>

![nudge-midi-notes-1-16.png](Editing%20Audio_assets/7fce2bfc8a4c25c7b2ad0a757a6d1f0fc9ce668c.png)

## Nudging within a MIDI clip

To nudge notes within a MIDI clip, without moving the boundaries of the MIDI clip, you can use the Nudge Content commands.

**Note:** Nudge Content key commands are not currently supported in Windows. However, you can Nudge Content from the LUNA menus.

- To nudge content left, press Control + , or select Edit \> Nudge Content \> Left from the LUNA menus.
- To nudge content right, press Control + . or select Edit \> Nudge Content \> Right from the LUNA menus.
- To nudge content left by the next higher nudge amount, press Control + M or select Edit \> Nudge Content \> Left Next Amount from the LUNA menus.
- To nudge content right by the next higher nudge amount, press Control + / or select Edit \> Nudge Content \> Right Next Amount from the LUNA menus.

![nudge-midi-content-1-16.png](Editing%20Audio_assets/42c143ba9a455781bd5c577f6e3403e977dc9d2c.png)

## Nudging to clip boundaries

You can nudge a clip to the next or previous clip boundary.

**Note:** Nudging to clip boundaries with key commands is not currently supported in Windows. However, you can nudge to clip boundaries from the LUNA menus.

- To nudge a clip to the next clip boundary, press Control+Option+. (macOS) or choose Edit \> Nudge \> To Next Clip from the LUNA menus.
- To nudge a clip to the previous clip boundary, press Control+Option+, (macOS) or choose Edit \> Nudge \> To Previous Clip from the LUNA menus.

![nudge-next-previous-clip.png](Editing%20Audio_assets/0b0ee79c9e8a42faf26a88ef423ea281c3adfd2f.png)

------------------------------------------------------------------------

# Duplicating Audio

When you duplicate audio, you copy the audio selection or clip and immediately paste it starting at the end of the current selection. Any existing audio is replaced. Duplicated audio, like pasted audio, does not retain the underlying clip structure.

Press Command+D (macOS) or Ctrl+D (Windows) to duplicate audio.

------------------------------------------------------------------------

# Shifting Audio

Shift editing allows you to edit audio and keep your arrangement flowing around your edits. For example, you can cut or paste audio or MIDI, and have the audio on one or more tracks shift back or forward in time to accommodate the cut or paste. You perform shift editing by pressing the Shift key with the modifier key (for example, Shift+V to shift-paste).

 

![paste-shift-workflows.png](Editing%20Audio_assets/4080d8983e0a20e84030f4ff569e16a4fd34836d.png)

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div collection="contentId-194969894" context-id="194969894" file-mime-type="image/png" file-name="paste-shift-workflows.png" file-size="85017" data-height="569" data-id="46f5040f-b64e-4a23-8028-cd616dfff074" node-type="media" data-type="file" data-width="338" title="Attachment">

</div>

</div>

- **Shift+X:** Cut the selection, and shift all the following audio or MIDI data to fill the space that is removed. You can do this on a single track, multiple selected tracks, or all tracks.

- **Shift+V:** Paste a selection, and shift all the following audio or MIDI data to accommodate the pasted data. You can do this on a single track, multiple selected tracks, or all tracks.

- **Shift+D:** Duplicate (copy and paste) the selection, and shift all the following audio or MIDI data to fill the space that is removed. You can do this on a single track, multiple selected tracks, or all tracks.

- **Shift+I:** Insert space, and shift audio or MIDI data following your selection by the length of the selection. You can do this on a single track, multiple selected tracks, or all tracks.

- **Shift+Delete:** Delete your selection and shift audio or MIDI data following your selection by the length of the selection. You can do this on a single track, multiple selected tracks, or all tracks.

------------------------------------------------------------------------

# Trimming an Audio Clip

Hover the Editing Tool near the bottom at the start or end of a clip to trim the length of the clip. Click and drag to the right from the start of the clip, or to the left from the end of the clip to trim its length. Note that trimming follows the Snap settings, unless you hold the Command (macOS) or Ctrl (Windows) key while trimming.

![smart-tool-trim.png](Editing%20Audio_assets/7fa2a9990756397990507f0210864f3732e818f4.png)

*Trim tool*

 

<div class="wysiwyg-text-align-center" collection="contentId-194969894" context-id="194969894" file-mime-type="image/png" file-name="smart-tool-trim-in-progress.png" file-size="38402" data-height="113" data-id="7d17dd78-4c38-4ed1-a692-997f84006d67" node-type="media" data-type="file" data-width="301" title="Attachment">

![smart-tool-trim-in-progress.png](Editing%20Audio_assets/8dfa6d483b40086235a4b3865296e00b1bd55171.png)

</div>

*Trim in progress*

## Trimming a clip with key commands

You can use key commands to trim clips.

- Press A to trim from the start of a clip to the playhead or to the start of a selection.
- Press S to trim from the playhead or the end of a selection to the end of the clip.
- With a selection made, Command+T (macOS) or Ctrl+T (Windows) to trim the clip and retain only the selection.

![trim-key-commands.png](Editing%20Audio_assets/5326da448b73184e32f3f88d92b2ae7737edd07c.png)

 

------------------------------------------------------------------------

# Selecting Within an Audio Clip

Hover just above the vertical center at the start or end of a clip to select. Note that this works anywhere in a clip, not just at the start or end. Click and drag to select. Selections follow the Snap settings, unless you hold the Command (macOS) or Ctrl (Windows) key while selecting.

![smart-tool-select.png](Editing%20Audio_assets/f9badc0275524738d1af0064c0162801a21e35fc.png)

*Tool appearance*

<div class="wysiwyg-text-align-center" collection="contentId-194969894" context-id="194969894" file-mime-type="image/png" file-name="smart-tool-selection-made.png" file-size="34329" data-height="113" data-id="dafded41-1dd9-4e0b-98d8-fa0a4e032df9" node-type="media" data-type="file" data-width="414" title="Attachment">

![smart-tool-selection-made.png](Editing%20Audio_assets/cb57e600e1f28821511d9eb35c8a9a7fee38b72a.png)

</div>

*Selection made*

------------------------------------------------------------------------

# Moving or Copying an Audio Clip

When you hover near the vertical and horizontal center, the cursor changes to the move/copy Crosshair Arrows Editing Tool. Drag the clip to a new location or a different track. Note that selections snap to the Snap settings, unless you hold the Command (macOS) or Ctrl (Windows) key while dragging.

Option+Click (macOS) or Alt+Click (Windows) to create a copy of the clip that you can then drag to a new location or track.

![smart-tool-move.png](Editing%20Audio_assets/72f45a7d1848681102a0a1af31ab0213e424750f.png)

 

------------------------------------------------------------------------

# Reversing Audio

To hear one or more audio clips play backwards, select clips on one or more tracks, then select Edit \> Reverse from the LUNA Menus, or press Control+Command+R (macOS) or Ctrl+Shift+R (Windows). You can also right-click on a selected clip and select Reverse from the context menu. The selected audio is reversed, and new clips are created, replacing the original clips.

**Tip:** To reverse audio with a trackpad instead of a mouse, click the trackpad with two fingers and select Reverse.

![reverse-audio.png](Editing%20Audio_assets/131de4d62d35454e1ea268d4970b33b43e60db9f.png)

 

------------------------------------------------------------------------

# Navigating Between Clip Transients

An audio transient is a loud, quick sound at the beginning of a waveform. You can use transients to find audio start points. For example, a transient is the start of a beat on a drum track, the start of a picked note on a guitar track, or the start of a phrase on a vocal track. In LUNA, you can navigate between transients using key commands. Navigating between transients works on a single track or multiple tracks. Note that with many tracks selected, navigating between transients can move the playhead very slowly, as there are many more transients.

- Press Tab to move to the next transient.
- Press Option+Tab (macOS) or Alt+Tab (Windows) to move to the previous transient.
- Press Shift+Tab to select to the next transient.
- Press Shift+Option+Tab (macOS) or Shift+Alt+Tab (Windows) to select to the previous transient.

------------------------------------------------------------------------

# Navigating Between Bars

You can move the playhead between bars with key commands.

- Press \] or 2 on the Numeric Keypad to move the playhead one bar to the right.
- Press \[ or 1 on the Numeric Keypad to move the playhead one bar to the left.
- Add the Shift key to extend the selection when navigating between bars.

------------------------------------------------------------------------

# Separating Audio Clips

You can separate audio clips to create two or more audio clips from an existing clip.

- Separate an audio clip at the playhead with the menu command Edit \> Separate Selection, or Command+E (macOS) / Ctrl+E (Windows).
- Separate a selection on the current grid with the menu command Edit \> Separate on Grid.

![separate-clip.png](Editing%20Audio_assets/3d524d441bdde217df3c0ba07dfd28028a6fdeef.png)

 

------------------------------------------------------------------------

# Healing (Recombining) Separated Clips

After you separate clips, you can press Command+H (macOS) or Ctrl+H (Windows) or choose Edit \> Heal Separation to recombine separated clips. The Heal Separation command works on two or more clips. Separated clips can only be recombined if the clips are arranged as they were originally. If you have rearranged clips, Heal Separation does not work. If you have made changes to separated clips with warps, clip gain, or clip pitch, those changes are discarded when the clips are healed. With clips you have rearranged that you want to combine, Consolidate clips.

![heal-separations.png](Editing%20Audio_assets/3e22628cb7f3909663d2aab60fcfa7a13464a43d.png)

------------------------------------------------------------------------

# Consolidating Audio Clips

You can combine two or more selected clips together by consolidating clips. You can also consolidate clips with spaces between them. When you consolidate such files, LUNA adds silence for the length of the space in the consolidated audio file.

- To consolidate, select one or more clips, and choose the menu item Edit \> Consolidate, or Option+Shift+3 (macOS) or Alt+Shift+3 (Windows).

![consoliodated-clips.png](Editing%20Audio_assets/8adcbf169820349e8a4d84af4c9bcd9c637537d0.png)

 

------------------------------------------------------------------------

# Working with Fades on Audio Clips

Hover near the top at the start or end of an audio clip to show the Fade Editing Tool.

![smart-tool-fade-tool.png](Editing%20Audio_assets/376c786a530416bb917096616a82bb4517652628.png)

## Creating a fade

Click and drag to the right from the beginning of the clip or to the left from the end of the clip to create a fade in or out. Fades follow the snap settings, unless you hold the Command (macOS) or Ctrl (Windows) key while dragging.

**Note:** When you trim a clip that has a fade applied, the original fade length is preserved.

![smart-tool-fade-created.png](Editing%20Audio_assets/0ae60e66551b39bda5b67e67069041f48df6e6a2.png)

 

## Editing the length of a fade

Hover over the fade boundary marker. The Fade Editing Tool appears. You can click and drag a fade to change its length. Fade length adjustments follow the snap settings, unless you hold the Command (macOS) or Ctrl (Windows) key while dragging.

![smart-tool-fade-resize.png](Editing%20Audio_assets/784945f361477a43de97d2d9b460f5520881c543.png)

## Editing the slope of an audio fade

Hover over the fade slope adjust point at the center of the fade. The Fade Slope Editing Tool appears, indicating you can adjust the fade slope.

Click and drag with the Fade Slope Editing Tool to adjust the fade slope. Drag up or down to adjust the slope of the fade to be more or less gradual. Drag towards the clip boundary or fade boundary to change how quickly the fade slopes in or out. Option+Click (macOS) or Alt+Click (Windows) on a fade to reset to the original fade.

![smart-tool-adjust-fade-slope.png](Editing%20Audio_assets/3acfce5ce2c6a6e53cc977977e6bc3a0d46c9d55.png)

Right-click, Control+Click (macOS), or Alt+Click (Windows) on a fade to switch between Equal Power and Equal Gain mode.

**Tip: Equal Power is a logarithmic fade, where equal gain is a linear fade. These options are not critical for fading in and out, because you can easily adjust the fade shape manually.**

![smart-tool-fade-equal-power-gain.png](Editing%20Audio_assets/f6353e92906fe066434500306018e0f203d40678.png)

------------------------------------------------------------------------

# Crossfading Between Audio Clips

<span class="fabric-editor-annotation" data-id="89cc456c-d928-4734-bc2b-0edf35273d6b" mark-annotation-type="inlineComment" mark-type="annotation">Crossfades can be created between material where two clips meet. </span>Use a crossfade to blend or smooth the transition between edits or clips. 

## Show the crossfade tool

- Hover your cursor over the vertical center of the boundary where two clips meet, or on the vertical center of the edge of one clip.
- If there is sufficient material to the right of the left clip, and to the left of the right clip, crossfades can be created across a gap. Such a crossfade reveals trimmed audio to accommodate the crossfade. 
- You can create a crossfade where only one of the two clips has material. In this case, the crossfade is adjusted to accommodate the clip that does not have material available. 
- You can adjust the start, end, and center point of a crossfade after the crossfade is created, and you can adjust the crossfade slope.

 

![smart-tool-crossfade-tool.png](Editing%20Audio_assets/681825452021a3c1f11085bde5ed394f3a9630f2.png)

*Crossfade tool at clip boundary*

 

<div class="wysiwyg-text-align-center" collection="contentId-194969894" context-id="194969894" file-mime-type="image/png" file-name="smart-tool-crossfade-edge.png" file-size="36506" data-height="113" data-id="9bc39652-8856-466c-9c46-bd144b5d8bd2" node-type="media" data-type="file" data-width="414" title="Attachment">

![smart-tool-crossfade-edge.png](Editing%20Audio_assets/acbf8bd3ba5c0874074663b3c74443f74cb6102f.png)

</div>

*Crossfade tool at clip edge (crossfading across a gap)*

### Create a crossfade

Drag the crossfade tool across the clip boundary or across the gap to crossfade between the clips. Crossfade adjustments follow the snap settings, unless you click the Command (macOS) / Ctrl (Windows) key while dragging.

![smart-tool-crossfade-created.png](Editing%20Audio_assets/fff36a132cf3243b1df19068cdf9d7831c507415.png)

### Adjust a crossfade

To adjust where the crossfade is centered, click and drag from the crossfade slope adjust point. Option+Click (macOS) / Alt+Click (Windows) the crossfade slope adjust point to reset the crossfade to default.

![smart-tool-crossfade-adjust.png](Editing%20Audio_assets/73e534848315504f732e64349261bc7bdfd918af.png)

To lengthen or shorten one end of an existing crossfade, hover your cursor over an edge of the crossfade. The crossfade boundary markers (white inverted triangles) appear at the upper edge of each side of the crossfade. Click the marker you want to adjust. The hand cursor appears. Drag to shorten or lengthen a crossfade edge. 

![smart-tool-crossfade-tool-hand.png](Editing%20Audio_assets/d55f9447e9cb0dd2a7ba2806dc35aeff3f1100d7.png)

 

### Move a crossfade

To move a crossfade, click in the lower half of the crossfade to select the crossfade. Drag the crossfade to move it. Note that you can only drag a crossfade as long as there is audio material underlying the fade being crossfaded. Crossfades snap to the Snap settings. To move the crossfade freely when Snap is enabled, click the Command (macOS) / Ctrl (Windows) key while dragging.

![smart-tool-crossfade-move.png](Editing%20Audio_assets/6b35d88aa9e270e87b671c7653df0b8e4dfaa29d.png)

### Delete a crossfade

To delete a crossfade, click in the lower half of the crossfade to select the crossfade, then press the Delete key.

### Use Equal Power or Equal Gain crossfades

To switch Equal Power and Equal Gain mode for the crossfade, Right-click or Control+click in the center of the crossfade, and choose the mode.

**Tip:** Equal Gain is the default mode, and is recommended for phase-coherent material, for example when fading between clips from the same guitar track or drum track. Equal Power mode works better for material that is less similar, dissimilar, or not phase-coherent, for example two different vocalists or two different guitar recordings.

![smart-tool-crossfade-eq-power-gain.png](Editing%20Audio_assets/83bb17a914387429d36c0d9ef9f31233ed4d66ea.png)

 

<span class="wysiwyg-font-size-small">251217</span>

