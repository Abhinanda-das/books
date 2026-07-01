---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041903331-Working-with-MIDI-on-Instrument-Tracks.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'Working with MIDI on Instrument Tracks'
word_count: 3707
---

# Working with MIDI on Instrument Tracks


MIDI has some special editing functions because you can work with MIDI both as clips and as individual notes. Clips can be edited, copied and moved as individual objects that contain groups of notes. In Notes view, there are additional note-level selection and editing features. 

## In this article

- <a href="#h_ce4991ce-3e5d-4a38-8639-b00a6e046d4d" target="_self">Working with Clips on a MIDI Track</a>
- <a href="#h_bbb78fa2-57d6-4fc2-8a4f-8d4169308983" target="_self">Resizing the MIDI track</a>
- <a href="#h_b58094fd-15c2-46d2-9551-b5ea70405f44" target="_self">Showing MIDI Notes</a>
- <a href="#h_0aa1f3cd-2414-4c17-8f24-d2588647c763" target="_self">Selecting MIDI Notes</a>
- <a href="#h_c67208d8-5262-4ca4-ba99-7a9b58a73295" target="_self">Cutting, Copying, and Pasting MIDI Notes</a>
- <a href="#h_0b60d96a-fc46-496e-9873-0bb39d9dca11" target="_self">Shift-Editing MIDI Clips</a>
- <a href="#h_53da8ef9-083a-4870-bdc9-906ead6d41d9" target="_self">Editing MIDI with the Editing Tool</a>
- <a href="#h_2c079c99-6ce7-4425-9a4a-552e5b5aa7be" target="_self">Transposing MIDI Notes</a>
- <a href="#h_1717689f-7565-49b5-bccc-324c820cc9e7" target="_self">Quantizing MIDI nNotes</a>
- <a href="#h_76adf3c6-2bff-4beb-9976-160861f06d29" target="_self">Editing MIDI Continuous Controllers</a>
- <a href="#h_01EKZDNSGEYZTFKG62J1ZNZBRB" target="_self">Sending MIDI Clock to Devices</a>

------------------------------------------------------------------------

# Working with Clips on a MIDI track

The two main editing views on a MIDI (Instrument) track are Clips and Notes. 

**Note:** For clip editing functions (except for making selections), Clips and Notes view behave the same, so Notes view is used for some examples in this section.

## Selecting MIDI in Clips view

To select a clip, click near the vertical top or bottom of the clip. 

**Note:** In Notes view, you can only select a MIDI clip from the top of the clip.

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-clip-select.png" file-size="18162" data-height="169" data-id="b2c2bd5c-5ab4-49a0-800d-8435d83ada51" node-type="media" data-type="file" data-width="234" title="Attachment">

![midi-clip-select.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/a0537c9c0c18ea4b8efd7cc0c84a7ca0bc3d9721.png)

</div>

</div>

 

To select a range in a MIDI clip, hover your mouse above the vertical middle of the clip. The selection cursor appears. Click and drag to the left or right to make a selection. 

## Renaming a MIDI clip

Double-click in the top bar of a MIDI clip anywhere except on the CC view or Quantize button to rename the MIDI clip. A popover opens. Type the new clip name, then click Done.

![midi-clip-popover.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/539e9b3adfc49cd915f699630ca6054a1634b6aa.png)

## Moving MIDI clips

To move a clip, hover at the top of the clip. The move tool appears. Click and drag the clip to a new location. You can drag a clip on the same track, or to another track, if it is the same type (audio or MIDI). If you have Snap enabled, the moved clip snaps to the grid. To move without snapping to the grid, hold the Command (macOS) or Alt (Windows) key while you drag.

When you move a MIDI clip, it can overlap an existing clip. You can see the overlapping area when dragging the clip. The overlapping MIDI area is played, while any underlying notes are not. If you later move the clip again, any underlying clips that exist are revealed.

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-move-overlap.png" file-size="33007" data-height="199" data-id="55dc5f14-98e7-4221-b90d-0181c9ef3320" node-type="media" data-type="file" data-width="360" title="Attachment">

![midi-move-overlap.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/ff30879ab4cee510b5f3d907b9c76aaf354492d4.png)

</div>

</div>

## Trimming MIDI clips

Trim a MIDI clip to either make it smaller or to extend the MIDI clip. This is useful because if you want to add more MIDI notes before or after an existing passage, you must extend the MIDI clip to contain that data. Alternatively, you can shorten a MIDI clip to hide notes at the beginning or end of a clip. Those notes are still available if you later trim the MIDI clip out to show them.

#### To trim a MIDI clip:

- Hover near the bottom at the start or end of a MIDI clip. The Trim Editing Tool appears. 
- Click and drag to shorten or lengthen the MIDI clip. 

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-clip.png" file-size="9387" data-height="115" data-id="9714190a-fa61-4cac-9049-7f8cfbe599b4" node-type="media" data-type="file" data-width="217" title="Attachment">

![midi-clip.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/91cefcbdd650c7974f6d4931773d8823e443ef04.png)

</div>

</div>

*MIDI clip showing Trim Editing Tool*

  

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-clip-extend.png" file-size="12015" data-height="113" data-id="d9f36d0d-2904-4e28-9257-ca5e38182750" node-type="media" data-type="file" data-width="419" title="Attachment">

![midi-clip-extend.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/cb71c1d3aa8d0f29aa7560c92910574926bf7e65.png)

</div>

*MIDI clip extended with Trim Editing Tool*

------------------------------------------------------------------------

# Resizing the MIDI Track

Before you add and edit MIDI notes, or cut, copy or paste MIDI data, you will likely want to resize the MIDI track. There are several ways to do this.

- **Resize all tracks:** At the top of the Edit workspace, click the Tracks icon, and choose a new track height size.

![qs-resize-all-tracks.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/e89e0f5a0aea902465ed25f7b377b3a06eb69919.png)

![qs-track-heights.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/6bf5cd04e9610acfab0a351cd33fd82ba525a71c.png)

- **Resize one track:** Drag up or down from the lower edge of the Track controls area. This resizes just one track.

<div layout="align-start" node-type="mediaSingle" data-width="81">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="qs-resize-midi-drag.png" file-size="70256" data-height="237" data-id="1a2fbc47-2b4d-4b5d-8996-dac26c2a143b" node-type="media" data-type="file" data-width="563" title="Attachment">

![qs-resize-midi-drag.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/df55b7dff106ac638d949ec704a332e08b3fe563.png)

</div>

</div>

- **Expand the track to the full editing space:** Press the E key.

- **Resize (zoom) the track horizontally:** Click the plus and minus buttons at the bottom of the Edit workspace (or use the keyboard shortcuts Command+\[ to zoom out, and Command+\] to zoom in on macOS or Ctrl+\[ to zoom out, and Ctrl+\] to zoom in on Windows).

- **Marquee zoom (zoom to a mouse selection):** Press Option (macOS) or Alt (Windows) and hover your mouse. The marquee zoom tool appears, and you can click and drag to marquee zoom. Option+click in the timeline to step back through previous marquee zoom states.

- **Zoom horizontally with a trackpad:** Pinch in or out.

- **Zoom horizontally with a mousewheel:** Hold the Option (macOS) or Alt (Windows) key and scroll.

![increase-decrease-horiz-zoom.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/b2701b4bfae2676015739db632db132162da19e6.png)

------------------------------------------------------------------------

# Showing MIDI Notes

You can vertically resize the MIDI notes on an Instrument track to make them easier to edit and work with. 

Set the instrument track to MIDI Notes view. On the instrument track, click View, and from the View browser, choose Notes. Notes view is indicated, and the keyboard and piano roll appear to the right of the track controls.

![midi-notes-view.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/ee7f132276cd5149bbf93683ebff261532231b06.png)

At the left of the MIDI track is a scroll bar. You can use the scroll bar to move up and down in the piano roll, and to resize the notes in the piano roll vertically. 

## To resize MIDI notes on the piano roll

- Click and drag up or down at the top or bottom of the scroll bar. 
- Drag up to make notes smaller vertically. 
- Drag down to make notes larger vertically. 
- Click Fold at the top of the Notes view keyboard to show only the notes used on the clip, with note names.
- Click Fit at the bottom the Note view keyboard to fit the range of notes on the piano roll to the height of the track.

<div layout="align-start" node-type="mediaSingle" data-width="81">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-notes-resize-vertically.png" file-size="110855" data-height="484" data-id="9c52b992-0087-405a-9305-ac3af7728f67" node-type="media" data-type="file" data-width="492" title="Attachment">

![midi-notes-resize-vertically.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/4b778529e140a498421672e1b7b6343043580a53.png)

</div>

</div>

 

<div layout="align-start" node-type="mediaSingle" data-width="56">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-note-views.png" file-size="34192" data-height="242" data-id="db392927-2d84-4a1a-a20b-f4bdf0904701" node-type="media" data-type="file" data-width="290" title="Attachment">

![midi-note-views.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/596bc1f05418c5442d4a6cae5c1017051f5bc255.png)

</div>

</div>

------------------------------------------------------------------------

# Selecting MIDI Notes

There are several ways to select multiple MIDI notes

- Click and drag a selection rectangle around the notes (rubber banding).
- Shift+Click on multiple notes. You can select contiguous or non-contiguous notes.
- Click a note on the Notes view keyboard at the left edge of the track to select all instances of that note. This selects all notes on the track, not just in a clip.
- Shift+Click different notes on the Notes view keyboard at the left edge of the track to select all instances of multiple notes.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-drag-select-multiple.png" file-size="20824" data-height="210" data-id="dcbaec97-a5f2-4e8f-88fd-0367ac3ebe41" node-type="media" data-type="file" data-width="371" title="Attachment">

![midi-drag-select-multiple.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/a3fdd07f41562b51b6fcbd63999066ac9dac1791.png)

</div>

</div>

*Select with a selection rectangle*

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-select-multiple-non-contig.png" file-size="22216" data-height="239" data-id="e7e49ed1-3e57-4418-9e64-10905ed9cff3" node-type="media" data-type="file" data-width="294" title="Attachment">

![midi-select-multiple-non-contig.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/492f95ee165052d15a94fb18ca3f66c39c67c48f.png)

</div>

*Shift-click to select multiple contiguous or non-contiguous notes*

<div class="wysiwyg-text-align-center" layout="align-start" node-type="mediaSingle" data-width="56">

<div collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-select-notes-keyboard.png" file-size="22514" data-height="239" data-id="9975553b-7d4a-46f9-8b6b-1675f5bfe933" node-type="media" data-type="file" data-width="346" title="Attachment">

![midi-select-notes-keyboard.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/a4d95f2297473b72dd9c35d695b91f82949e9f74.png)

</div>

</div>

*Select from the Notes view keyboard*

------------------------------------------------------------------------

# Cutting, Copying, and Pasting MIDI Notes

Cutting, copying, and pasting MIDI works differently from editing audio: 

- You can select non-contiguous MIDI notes.

- The paste operation respects the structure of the cut or copied data. If you paste within an existing clip, the notes are pasted within the boundaries of the clip. If you paste MIDI notes on the timeline outside a MIDI clip, a new MIDI clip is created.

- MIDI notes are selected, cut, copied, and pasted with the same time relationships and durations as the selection.

MIDI selections conform to the grid if Snap is enabled.

![multiple-midi-notes-pasted.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/2c98c6bd78b46ac1c1985e67abde7ed30a0f16a4.png)

 

## To cut and paste MIDI notes

1.  Select MIDI notes to cut. You can select a range with the Select Editing Tool, draw a selection with the selection rectangle, select contiguous or non-contiguous notes by shift-clicking individual notes, or select specific notes from the Notes View Keyboard.

2.  To cut notes, press X (if MIDI Keyboard Mode is not enabled), or Command+X (macOS) / Ctrl+X (Windows). The MIDI notes are removed from the clip and copied to the clipboard.

3.  To paste notes, place the playhead at a location in the Timeline or in another MIDI clip and press V (if MIDI Keyboard Mode is not enabled), or Command+V (macOS) / Ctrl+V (Windows). 

## To copy and paste MIDI notes

1.  Select MIDI notes to copy. You can select a range with the Select Editing Tool, draw a selection with the selection rectangle, select contiguous or non-contiguous notes by shift-clicking individual notes, or select specific notes from the Notes View Keyboard.

2.  To copy notes, press C (if MIDI Keyboard Mode is not enabled), or Command+C (macOS) / Ctrl+C (Windows). The MIDI notes are copied to the clipboard.

3.  To paste notes, place the playhead at a location in the Timeline or in another MIDI clip and press V (if MIDI Keyboard Mode is not enabled), or Command+V (macOS) / Ctrl+V (Windows). 

------------------------------------------------------------------------

# Shift-Editing MIDI Clips

The shift workflow allows you to edit MIDI and keep your arrangement flowing around your edits (also known as ripple editing). For example, you can cut or paste MIDI, and have the MIDI clips on one or more tracks shift back or forward in time to accommodate the cut or paste.

**Note:** The Shift-editing workflow works only with a time selection on a clip (for example, a whole clip, or a selection made with the Select Editing Tool). You cannot Shift edit with single notes, rectangular selections, non-contiguous notes, or note selections made with the Notes View Keyboard.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="shift-workflow-midi.png" file-size="84517" data-height="549" data-id="474d2bf6-2459-4de8-9ed1-56f185ff6370" node-type="media" data-type="file" data-width="371" title="Attachment">

</div>

</div>

![shift-workflow-midi.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/e17fe10184a7cc85c3de9bbd4d4800d62754d33f.png) 

 

- **Shift+X:** Cuts the selection and pulls all following MIDI data forward to fill the gap.
- **Shift+V:** Pastes the selection and pushes all following MIDI data later in the timeline to make room.
- **Shift+D:** Copies and inserts the selection immediately after itself, pushing all following MIDI data further back.
- **Shift+I:** Creates a gap by pushing MIDI data forward based on the length of your current selection.
- **Shift+Delete:** Deletes the selection and pulls all following MIDI data forward to close the empty space.

------------------------------------------------------------------------

# Editing MIDI with the Editing Tool

You can record MIDI from a MIDI controller to an Instrument track, and you can add or edit MIDI notes and controller values with MIDI on an Instrument track manually, using the Editing Tool. Set the Grid settings to specify the default note length. When you add a MIDI note, the default note length is the Grid setting. Notes you add snap to the grid if Snap is enabled.

## Adding and editing MIDI notes on an instrument track

To work with notes in a MIDI clip or on an Instrument track, click View on the track, and choose Notes in the Browser to set the track to MIDI Notes view.

<div layout="align-start" node-type="mediaSingle" data-width="81">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-select-notes-view.png" file-size="55580" data-height="215" data-id="8e28e492-838f-4bd1-9fe6-0946b5a3a307" node-type="media" data-type="file" data-width="620" title="Attachment">

![midi-select-notes-view.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/4f6a9f73207b840b33571c2e3b7ababfbce22011.png)

</div>

</div>

 

## Add MIDI notes

Hover over a note location. The MIDI Note Editing Tool (a plus symbol) appears. Double-click on the location where you want to add the note. The note is added.

<div layout="align-start" node-type="mediaSingle" data-width="56">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-smart-add-note.png" file-size="15823" data-height="210" data-id="b59fa198-ea51-4778-96c4-1335a566d157" node-type="media" data-type="file" data-width="370" title="Attachment">

![midi-smart-add-note.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/fa3bf47d5da7e758e4c3d775391e867e30c32e36.png)

</div>

</div>

 

## Add multiple MIDI notes

To add multiple notes, press Control and click and drag from left to right across the track. The MIDI Pencil Editing Tool appears and draws notes across the track. MIDI notes of the duration determined by the Grid size are added, on the pitch where you release the click.

<div layout="align-start" node-type="mediaSingle" data-width="56">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-add-multiple-notes.png" file-size="20583" data-height="209" data-id="f76d016c-43f4-404e-8905-8cb82e488760" node-type="media" data-type="file" data-width="371" title="Attachment">

![midi-add-multiple-notes.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/a5b971e6c840f4717c0eccb9933bd47043a134c9.png)

</div>

</div>

 

## Delete a MIDI note

To delete a MIDI note, hover over the note. The MIDI Hand Editing Tool appears. Double-click the note to delete it.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-smart-tool-hand.png" file-size="19135" data-height="238" data-id="96f7857d-cd24-4844-ab5d-b640c92bd98a" node-type="media" data-type="file" data-width="510" title="Attachment">

![midi-smart-tool-hand.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/de606a72b37de0f38866256d926b0ee587625a2c.png)

</div>

</div>

 

## Move a MIDI note

Hover over the note. The MIDI Hand Editing Tool appears. Click on the note and drag it up or down to change the MIDI note, and left or right to change the time location. As you move the note up and down, the different notes are triggered on the Instrument plug-in. MIDI notes will snap to the grid if Snap is enabled.

## Trim a MIDI note

Hover near the edge of a MIDI note. The MIDI Trim Editing Tool appears. Click on the left or right edge of the note and drag to trim the note. MIDI note edges will snap to the grid if Snap is enabled. To ignore the Grid when trimming, press Command (macOS / Ctrl (Windows) after you start to trim. 

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-smart-trim.png" file-size="22071" data-height="210" data-id="468d4c9e-9467-436c-95f0-1da588709b31" node-type="media" data-type="file" data-width="399" title="Attachment">

![midi-smart-trim.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/6ec324c8040c8fce356c419b9d602c8c38aa8461.png)

</div>

</div>

 

## Change the velocity of a MIDI note

- **In the MIDI track:** Press Command (macOS) / Ctrl (Windows) and hover over a note. The MIDI Velocity Editing Tool appears. Command+Click on the note and drag up or down to increase or decrease the note velocity. The relative transparency of the note indicates the velocity. Notes become less opaque and more transparent as velocity decreases, and more opaque and less transparent as velocity increases.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-smart-velocity.png" file-size="21221" data-height="210" data-id="12f50006-a72c-418c-9f55-47e149c6921b" node-type="media" data-type="file" data-width="371" title="Attachment">

![midi-smart-velocity.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/6f4d153b6d018300eaf13cc3a4d46f6b704f6fbb.png)

</div>

</div>

- **In the CC Velocity view:** Show the MIDI CC sliders (set to Velocity by default), and click and drag on a velocity stalk to edit velocity for a note. You can click the note to highlight the note’s velocity stalk. If you select multiple notes, Option+Click and drag to edit multiple velocity stalks. Shift-click to select multiple velocity stalks.

## Show the MIDI CC track for an instrument track

Click the MIDI CC icon at the top of the track, next to the track name.

![midi-cc-show.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/49a64767375bd8fd280e1b2325018b8c76d1ca6d.png)

 

## Edit the velocity of a MIDI note on the velocity track

Click on the velocity stalk and drag it up or down.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-edit-note-velocity.png" file-size="26409" data-height="277" data-id="1ef5bd79-5c6f-41b8-ba13-368231a2dc23" node-type="media" data-type="file" data-width="372" title="Attachment">

![midi-edit-note-velocity.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/d610ec3c0823b93a520c9300500116887802659f.png)

</div>

</div>

 

## Edit the velocity for multiple MIDI notes

1.  Select multiple notes on the timeline, or select multiple velocity stalks on the velocity track. Shift-click to select multiple non-contiguous velocity stalks.
2.  Option+Click (macOS) / Alt+Click (Windows) on a note velocity stalk and drag up or down. All selected note velocities are adjusted relative to each other.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="mide-multiple-notes-select-velocity.png" file-size="28811" data-height="279" data-id="91f8eec1-93a0-4f7c-b2b0-0c274fe78889" node-type="media" data-type="file" data-width="372" title="Attachment">

![mide-multiple-notes-select-velocity.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/ecb4ea26ca3f51ce6a21cba1c4ad77eba099e57c.png)

</div>

</div>

 

## Draw MIDI note velocities

1.  Press Control on the velocity track. The cursor changes to a pencil.
2.  Draw velocities across the velocity track. Note that if you have made a selection, you can only draw velocities on selected notes.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-draw-note-velocity.png" file-size="26696" data-height="277" data-id="70aebd36-f557-4655-bbe0-4c78c4b89e4b" node-type="media" data-type="file" data-width="372" title="Attachment">

![midi-draw-note-velocity.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/9f150d32c9e8275f1f599c4a19723ebcf4a6d30f.png)

</div>

</div>

 

------------------------------------------------------------------------

# Transposing MIDI Notes

- To transpose one or more selected MIDI notes up one semitone, press ↑. 
- To transpose one or more selected MIDI notes down one semitone, press ↓.
- To transpose one or more selected MIDI notes up an octave, press Shift+↑.
- To transpose one or more selected MIDI notes down an octave, press Shift+↓.

<div layout="align-start" node-type="mediaSingle" data-width="56">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="shift-notes-midi.png" file-size="52568" data-height="537" data-id="4c2fb1ae-e957-4da6-b076-2a8f74147f39" node-type="media" data-type="file" data-width="265" title="Attachment">

![transpose-notes-midi.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/d194401119dd5c4d7443f9396df8162182bff8fd.png)

</div>

</div>

 

------------------------------------------------------------------------

# Quantizing MIDI notes

You can quantize MIDI notes, selections, or clips to any grid increment, and add swing. 

- **Grid**: Quantize notes to the selected Grid setting, ranging from **BAR** (whole notes) to **/64** (64th notes). You can also select **Dotted** values, **Triplet** values, or both.

- **Follow Snap Setting:** Quantize notes based on the current **Snap Grid** setting.

- **Swing:** Shifts every other Grid boundary by a specified percentage (**0–100%**). A Swing of 0% does not shift notes, while 100% shifts notes 2/3 of the way to the next grid line.

- **Strength:** Sets the intensity of the quantization. At **50%**, notes move halfway toward the grid; at **100%**, notes are fully snapped to the grid.

- **Range:** Determines the detection window for notes to be quantized. The default **100%** detects notes within half the grid value to the left and right.

  - *Example:* With a **1/4 note grid**, a **100% range** detects notes within 1/8 note of the grid line. A **50% range** detects notes within 1/16 note of the grid line.

- **Auto Apply:** When enabled, you can hear and see quantization changes in near real time as you adjust settings. If disabled, you must manually click **Quantize** to apply changes.

## To quantize MIDI notes

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Select a MIDI note or notes, or a MIDI clip.

2.  Press Command+Shift+U (macOS) / Ctrl+Shift+U (Windows) to open the quantize panel. You can also press the Q in the header of an audio clip, though this will change your selection unless you have enabled a track group.

    \
    ![midi-quantize.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/c63898e5643fd36efb3b0482172ebdf57428df0b.png)\
     

3.  To preview your Quantize choices in real time, select Auto Apply.

4.  Choose a grid value to which to quantize notes. You can select from 64th notes to whole notes, and dotted or triplet modifiers.

5.  To follow the Snap grid setting, click Follow Snap Setting.

6.  To adjust the amount of swing from 0 to 100%, move the Swing slider.

7.  To adjust quantize strength, move the Strength slider from 0 to 100%.

8.  To adjust the quantize detection range, move the Range slider from 0 to 100%.

9.  Click Quantize to apply your settings.

**Note:** If Auto Apply is enabled, any setting you change will update your selection.

</div>

------------------------------------------------------------------------

# Editing MIDI Continuous Controllers

You can show MIDI Continuous Controller (CC) lanes and edit automation.  

To show MIDI Continuous Controllers, click the MIDI CC button on a MIDI clip.

<div layout="align-start" node-type="mediaSingle" data-width="56">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-cc-show.png" file-size="16255" data-height="224" data-id="2473093c-117a-4922-aa82-b42eda68ec2d" node-type="media" data-type="file" data-width="253" title="Attachment">

![midi-cc-show.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/49a64767375bd8fd280e1b2325018b8c76d1ca6d.png)

</div>

</div>

 

By default, MIDI CC view shows Velocity and the velocity sliders.

## To show a MIDI CC controller lane

1.  Click the MIDI CC button on the MIDI clip.
2.  Click on the Velocity button on the track control area to open the MIDI CC browser. The MIDI CC browser lists all the MIDI CCs.  
3.  Choose a MIDI CC controller. The automation lane for the controller is displayed.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div class="wysiwyg-text-align-center" collection="contentId-200606089" context-id="200606089" file-mime-type="image/png" file-name="midi-cc-change.png" file-size="24583" data-height="216" data-id="fa4e4634-5536-4e07-a25c-04ee4c8ce71e" node-type="media" data-type="file" data-width="258" title="Attachment">

![enable-cc-automation.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/de82ddc93b8c67032e3367dfa78deac5da3019b5.png)

</div>

</div>

To write automation for a CC, see <a href="https://help.uaudio.com/hc/en-us/articles/360041469672#midi-cc" target="_self">Automating a MIDI Continuous Controller</a>.

------------------------------------------------------------------------

# Sending MIDI Clock to Devices

You can configure LUNA to send MIDI Clock position and timing information to connected MIDI devices.

## To send MIDI Clock to a device

1.  In LUNA, click the UA logo at the top left of the screen, or select LUNA \> Preferences from the application menus.

2.  Click MIDI. The MIDI Settings screen opens.

    ![midi-settings.png](Working%20with%20MIDI%20on%20Instrument%20Tracks_assets/95bdfd7c091767cf24d3a9424b1c911826ef5821.png)

3.  To enable MIDI Clock for a device, click the box next to the device name.

4.  Select the Clock mode (Song or Pattern).

5.  If necessary, you can configure an offset, from -200 to +200 milliseconds, by typing a number or moving the Delay slider.\
    In most instances, this setting is not required. However, if you find that your device is not in sync or out of phase with LUNA playback, small adjustments to the MIDI clock timing sent to the device may correct this issue.

## MIDI Clock modes

You can set the MIDI clock output to Song mode or Pattern mode. If you are working with a pattern-based generator (for example, a drum machine that triggers loops or sequences), Pattern mode will provide the best experience. If the device should be syncing for the duration of the song, Song mode will provide the best experience.

### Song Mode MIDI messages

 In Song mode, LUNA sends MIDI messages to the device with the following rules.

- **Start play in LUNA**
  - **MIDI Messages:** Song position pointer, START, CLOCK (ongoing)
  - **Additional Info:** CLOCK is sent until stop.
- **Stop play in LUNA**
  - **MIDI Messages:** STOP, Song position pointer
- **Click on the Bars and Beats ruler during playback**
  - **MIDI Messages:** STOP, Song position pointer, CONTINUE, CLOCK (ongoing)
  - **Additional Info:** CLOCK is sent until stop.
- **Loop reaches the end and restarts**
  - **MIDI Messages:** STOP, Song position pointer, CONTINUE, CLOCK (ongoing)
  - **Additional Info:** CLOCK is sent until stop.

### Pattern Mode MIDI messages

In Pattern mode, LUNA sends MIDI messages to the device according to the following rules.

<div>

<div>

- <div>

  **Start play in LUNA, not on a bar**

  </div>

  - <div>

    **MIDI Messages:** Song position pointer (0), START (when a bar is reached), CLOCK (ongoing)

    </div>

  - <div>

    **Additional Info:** CLOCK is sent until stop.

    </div>

- <div>

  **Start play in LUNA on a bar**

  </div>

  - <div>

    **MIDI Messages:** START, CLOCK (ongoing)

    </div>

  - <div>

    **Additional Info:** CLOCK is sent until stop.

    </div>

- <div>

  **Stop play in LUNA**

  </div>

  - <div>

    **MIDI Messages:** STOP

    </div>

- <div>

  **Click on the Bars and Beats ruler during playback**

  </div>

  - <div>

    **MIDI Messages:** CLOCK (ongoing)

    </div>

  - <div>

    **Additional Info:** CLOCK is sent until stop.

    </div>

- <div>

  **Loop reaches the end and restarts**

  </div>

  - <div>

    **MIDI Messages:** No messages

    </div>

</div>

<div>

 

</div>

<div>

<span class="wysiwyg-font-size-small">251222</span>

</div>

</div>

