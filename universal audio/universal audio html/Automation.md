---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041469672-Automation.html'
converted_at: 2026-05-31T13:44:54Z
tool: htmlq+pandoc
title: 'Automation'
word_count: 3229
---

# Automation


## In this article

- [Automation Overview](#h_f2c67b7a-f077-4e65-86b5-c2d810f1eeb0)
- <a href="#h_deee8fe3-4558-42f7-a21c-c509f8a674c9" target="_self">Automation Modes</a>
- [Choosing What to Automate](#h_56306a13-8abf-4d7c-b14e-16a3319d210d)
- <a href="#h_8f117168-411a-450e-9757-11465a97ee82" target="_self">Drawing Automation</a>
- [Writing Volume Automation with the Volume Fader](#h_d94891ba-b892-4d99-a70c-9e653f7da646)
- [Writing Pan Automation](#h_f2980a03-d42d-4530-9580-bc54b8920211)
- [Automating Plug-In Parameters](#h_3b9f5734-d02f-45d6-bc24-71971e858ced)
- [Automating LUNA Extension Controls](#h_01EC5PQB75CAA0ND6V95MPZC10)
- [Automating a MIDI Continuous Controller](#h_231f1a15-4e57-4173-acca-cc7c44ed21e7)
- [Trimming Automation](#h_556312ba-53a7-42d9-b02d-e24e0c170051)
- [Clearing all Automation for a Selection](#h_01EC5NBC3BVESWZHHTTVRJPBK2)
- [Writing and Trimming Control Values](#h_01HYDZN25YVHX6F95ST5NCSNV8)

------------------------------------------------------------------------

# Automation Overview

Automation is the process of writing changes to controls in your session over time that are then played back as the session is played back {when track automation is enabled). Most parameters on a track can be automated. 

------------------------------------------------------------------------

# Automation Modes

LUNA has the following automation modes.

- **Off:** Automation is ignored; the track plays back based on current mix levels and pan controls.

- **Read:** Standard playback mode. The track plays back all previously recorded automation data.

- **Touch:** Track plays back all existing automation. Automation is only written while you are actively holding or moving a control. Once released, the control snaps back to the existing automation. Use Touch to write initial automation, "touch-up" existing automation, and for specific spot fixes.

- **Latch:** Functions like Touch, but continues writing the last value after you release the control. The control stays at that "latched" value until playback stops or the loop restarts. Use this to touch up automation, then set a specific level for the remainder of a section.

- **Trim (Read T):** Allows you to offset the existing automation without overwriting it. When enabled, the volume fader changes color and becomes a "relative" control, raising or lowering the overall level of the existing automation pass. Note that Trim only applies to Volume. 

- **Touch Trim and Latch Trim are** hybrid modes that allow you to record "trim adjustments" in real-time.

  - **Touch Trim:** Records a relative offset only while you hold the fader.

  - **Latch Trim:** Records a relative offset and stays at that new offset after you let go.

------------------------------------------------------------------------

# Choosing What to Automate

The View browser for a track (accessed from Timeline view) shows the items you can automate. 

- For an audio track, you can automate volume, mute, and mono or stereo pans, and the controls for any plug-ins and extensions on the track. 

- For an instrument track, you can automate  volume, mute, and mono or stereo pans, plus all the MIDI Continuous Controllers (CCs) of the Instrument plug-in, and controls for any plug-ins on the track. 

- Plug-ins and extensions on audio and instrument tracks also have controls that can be automated. 

The browser shows all automatable parameters for all plug-ins on a track. When automation has been added, the View browser highlights any automated parameter in yellow.

<figure class="wysiwyg-image">
![automation-extension.png](Automation_assets/a80b84e166062dbe1e3fe8cf05c59462874c377c.png)
</figure>

------------------------------------------------------------------------

# Drawing Automation

You can manually draw automation breakpoints for precise control, even in areas where there are no audio clips.

- You can add points anywhere on a track's automation lane to create breakpoints.

- By default, new points snap to the grid. Hold Command (macOS) or Ctrl (Windows) to place points without snapping to the grid.

## To draw automation on an audio or Instrument clip

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  In Timeline view, click View, and choose the parameter for which you want to draw automation (for example, Volume). The audio or MIDI clip shows a line for the automatable parameter.\
    \
    ![view-settings.png](Automation_assets/fd0553284cbdb55a4acf9fde3913a9c6d6611214.png)\
    \
    \
    ![automation-show-volume.png](Automation_assets/ee6f52fec897251ac37d76b8891a308ea3be0150.png)\
    \
    \
    ![automation-lines.png](Automation_assets/6655df2f8b3191fbf2558f00298a8cdb3b131536.png)
2.  To add automation points, press Control and hover over the clip. The cursor changes to the Pencil Editing Tool.\
    \
    ![automation-pencil-tool.png](Automation_assets/f198c836117f250fbe59317665aab29135fb4565.png)
3.  While you hold Control, click the points you want to add on the automation line. Hold Control and drag to draw automation across the track.\
    \
    ![automation-drawn.png](Automation_assets/cffdc223981ad3c6ef318d59c8a43b946d431f6d.png)
4.  To draw automation without snapping automation points to the grid, press Control+Command (macOS) while drawing automation. To draw automation without snapping to the grid on Windows, disable Snap.\
    \
    ![automation-drawn-no-grid.png](Automation_assets/81b0dc1adc5f35a0c19a3cddae9a81ba0268bbd6.png)
5.  To adjust an automation point, click the point and drag up or down. To adjust with fine control, hold Shift while you drag.
6.  To clear an automation point, hold Control and hover over an automation point. The cursor changes to the Eraser Editing Tool (the pencil turns around). Click an automation point to remove it.\
    \
    ![automation-eraser-tool.png](Automation_assets/555583b58597341084d6475e30b0ea38acf1d46a.png)
7.  To clear a range of automation, select the range on the audio or Instrument track, and press Delete.\
    \
    ![automation-range-selected.png](Automation_assets/96873c9f8d82ad19b80cc13b120757e0625397a7.png)

</div>

Your automation changes are played back when the session plays the clip, when an Auto Mode is enabled. When Auto Mode is Off, automation is ignored.

------------------------------------------------------------------------

# Writing Volume Automation with the Volume Fader

To write automation, switch a track to Touch or Latch mode. You do not need to press a global "Record" button to write automation. Automation begins recording the moment you move a fader or control.

Recording stops when you release the control (in Touch mode), stop playback, restart a loop, or change automation modes.

You can write volume automation on any track type.

## Automation mode behaviors

- **Touch Mode:** When you release the control, the fader snaps back to its original level.

- **Latch Mode:** When you release the control, the fader stays at the new level and continues writing that value until playback stops.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div class="wysiwyg-text-align-center" collection="contentId-199393432" context-id="199393432" file-mime-type="image/png" file-name="automation-writing-all-track-types.png" file-size="86164" data-height="428" data-id="84a8345f-88cc-4521-ae34-e676ebdd2bd0" node-type="media" data-type="file" data-width="269" title="Attachment">

![automation-writing-all-track-types.png](Automation_assets/288512f72d3f4673b7d9f8581a64e8acdf1a4e5b.png)

</div>

</div>

 

## To write volume automation

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  On the Focus channel in the Timeline, or on the track in the Mixer, set the track for which you want to automate volume to either Touch or Latch mode.\
    \
    ![automation-enable-latch-touch.png](Automation_assets/aff15b20781fc60b2bd2f859094585dde0facb59.png)
2.  To view the results of your automation, and to edit the automation, switch the track view to Volume. In the track control area in the Timeline, click View, then from the browser choose Volume.\
    ![automation-set-track-volume.png](Automation_assets/65188d7d0197177d6d7fa53c6bbf5587d8a54f33.png)\
     
3.  Make a selection or place the playhead where you want to start playback.
4.  Press Play or the Spacebar.
5.  As the track plays, adjust the volume. Volume automation is written to the track.\
    \
    ![automation-writing-voume-with-fader.png](Automation_assets/d53d82edaa14c64b6f72cd8394b1b6892ffae029.png)
6.  To stop writing automation, press the Stop button or the Spacebar, or release the fader. Automation also stops writing when playback stops (for example, at the end of a selection). 

</div>

If you are writing Touch automation, release the fader to stop writing automation and return the fader to the previous level (before you started writing automation). 

If you are writing Latch automation, the fader remains at the release level.

------------------------------------------------------------------------

# Writing Pan Automation

Pan automation is represented on a horizontal line.

- The center line is unpanned (centered).

- Above the center, signal pans to the left.

- Below the center, signal pans to the right. 

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div class="wysiwyg-text-align-center" collection="contentId-199393432" context-id="199393432" file-mime-type="image/png" file-name="pan-automation-panning.png" file-size="51009" data-height="313" data-id="96f1c351-ae93-4e9e-9bfe-eb47d444d0f9" node-type="media" data-type="file" data-width="203" title="Attachment">

![pan-automation-panning.png](Automation_assets/6ffa2c5510de05f79836cfd7053e8b10ba156d35.png)

</div>

</div>

 

## To write pan automation

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  In the Track controls on the Timeline, on the Focus channel in the Timeline, or on the track channel strip in the Mixer, set the track for which you want to automate panning to either Touch or Latch mode.\
    \
    ![automation-enable-latch-touch.png](Automation_assets/aff15b20781fc60b2bd2f859094585dde0facb59.png)
2.  To view the results of your automation, and to edit the automation, switch the track view to Pan. In the track control area in the Timeline, click View, then from the browser choose Pan.
3.  Make a selection or place your cursor where you want to start playback.
4.  Press Play or the Spacebar.
5.  As the track plays, adjust the pan control in the mixer or on the track. Pan automation is written to the track.\
    \
    ![audio-pan-automation-writing.png](Automation_assets/a6313d61ce7ef708337f361fcb4186bb086f8b98.png)
6.  To stop writing automation, press the Stop button or the Spacebar, or release the fader. Automation also stops writing when playback stops (for example, at the end of a selection). 

</div>

If you are writing Touch automation, release the fader to stop writing automation and return the fader to the previous level (before you started writing automation). If you are writing Latch automation, the fader remains at the release level.

------------------------------------------------------------------------

# Automating Plug-In Parameters

You can edit automation for any plug-in assigned to a track. All automatable plug-in parameters appear in the track’s View browser.

## To write plug-in automation

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  On the Track control area in the Timeline, click View, then from the browser choose the plug-in parameter to automate. On the track, the plug-in parameter line appears.
2.  To add automation points, press Control and hover over the track. The cursor changes to the Pencil Editing Tool.\
    \
    ![automation-pencil-tool.png](Automation_assets/f198c836117f250fbe59317665aab29135fb4565.png)
3.  While you hold Control, click the points you want to add on the automation line. Hold Control and drag to draw automation across the track.\
    \
    ![automation-drawn.png](Automation_assets/cffdc223981ad3c6ef318d59c8a43b946d431f6d.png)
4.  To draw automation without snapping automation points to the grid, press Control+Command (macOS) while drawing automation. To draw automation without snapping to the grid on Windows, disable Snap.\
    \
    ![automation-drawn-no-grid.png](Automation_assets/81b0dc1adc5f35a0c19a3cddae9a81ba0268bbd6.png)
5.  To clear an automation point, hold Control and hover over an automation point. The cursor changes to the Eraser Editing Tool (the pencil turns around). Click an automation point to remove it.\
    \
    ![automation-eraser-tool.png](Automation_assets/555583b58597341084d6475e30b0ea38acf1d46a.png)
6.  To clear a range of automation, select the range on the track and press Delete.\
    \
    ![automation-selected-cleared-audio.png](Automation_assets/751c147cb7e00229cfece5fef6697bb4f07de4d9.png)

</div>

Your automation changes are played back when the session plays the clip and Automation is enabled. When Auto Mode is Off, automation is ignored.

------------------------------------------------------------------------

# Automating LUNA Extension Controls

You can write automation for any LUNA Extension assigned to a track. All automatable LUNA Extension controls are listed in the track’s View browser.

## To write LUNA Extension automation by adjusting a control

1.  On the track controls, set the track for which you want to automate LUNA Extension controls to either Touch or Latch mode. \
    ![set-automation-mode-track-mixer.png](Automation_assets/2061a82ee0f4f87568b7d79a328644de23bfeded.png)\
     
2.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">To see the results of your automation in the timeline during playback, click View on the track controls, and from the View browser, select the control for which you want to view automation. </span>\
    \
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![automation-extension.png](Automation_assets/a80b84e166062dbe1e3fe8cf05c59462874c377c.png)</span>\
     
3.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"></span><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">Press the Spacebar or play on the transport. While the track is playing, adjust the control you want to automate.</span>
4.  Press the Spacebar or stop on the transport to stop writing automation.

If you selected the control in the View browser, you can see the control automation while it is being written, and see the automation results after it is written.

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div class="wysiwyg-text-align-center" collection="contentId-225740993" context-id="225740993" file-mime-type="image/png" file-name="extension-automation-writing.png" file-size="26373" data-height="277" data-id="85c256d7-c135-4fc5-b2d3-13136ae1204f" node-type="media" data-type="file" data-width="146" title="Attachment">

![extension-automation-writing.png](Automation_assets/54a7bf26effd7c4b03efaef7ac8dcdece1adf771.png)

</div>

</div>

## To draw LUNA Extension automation

1.  On the Track control area in the Timeline, click View, then from the browser choose the LUNA Extension control to automate. On the track, the LUNA Extension control line appears.\
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![automation-extension.png](Automation_assets/a80b84e166062dbe1e3fe8cf05c59462874c377c.png)</span>\
    \
    \
    ![extension-automation-on-track.png](Automation_assets/86d4790dd4d3789b11ade71133cb35217b901f63.png)\
     
2.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">To add automation points, press Control and hover over the track. The cursor changes to the Pencil Editing Tool. You can also double-click to add an automation point at the cursor.</span>\
    \
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![pencil-tool-automation.png](Automation_assets/b4959c980064c9237bb628bb369684efbd1536ac.png)</span>\
     
3.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"></span><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">While you hold Control, click the points you want to add on the automation line. Hold Control and drag to draw automation across the track. To adjust a single automation point, click and drag.</span>\
    \
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![draw-or-drag-automation.png](Automation_assets/314ec1d819945e3157e718bd82c309a434771c3f.png)</span>\
     
4.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"></span><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">To draw automation without snapping automation points to the grid, press Control+Command (macOS) while drawing automation. To draw automation without snapping to the grid on Windows, disable Snap.</span>\
    \
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![automation-ctrl-cmd.png](Automation_assets/c69042b87a5b95c4d9e13a7eaf2d4685cefbb00b.png)</span>\
    \
     
5.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"></span><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">To clear an automation point, hold Control and hover over an automation point. The cursor changes to the Eraser Editing Tool (the pencil turns around). Click an automation point to remove it.</span>\
    \
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![erase-automation.png](Automation_assets/36b10f3fd74c2db66b0bdb78bd0ac73435935e85.png)</span>\
    \
     
6.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"></span><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">To clear a range of automation, select the range on the audio or Instrument track, and press Delete.</span>\
    \
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![automation-selected-cleared-audio.png](Automation_assets/751c147cb7e00229cfece5fef6697bb4f07de4d9.png)</span>

Your automation changes are played back when the session plays the clip and Automation is enabled. When Auto Mode is Off, automation is ignored.

<span id="midi-cc"></span>

------------------------------------------------------------------------

# Automating a MIDI Continuous Controller

You can edit automation for any MIDI Continuous Controller (CC) on an instrument track. All automatable CC messages appear in the track’s View browser.

**Note:** you can edit all MIDI CCs supported by the Instrument, even if the CC is not used in a program.

## To write MIDI CC automation

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Enable the MIDI CC view by clicking the MIDI CC icon on a clip on the instrument track.\
    \
    ![midi-cc-show.png](Automation_assets/49a64767375bd8fd280e1b2325018b8c76d1ca6d.png)
2.  On the Track control area in the Timeline, click the CC Controller button (this defaults to Volume), then from the browser choose the MIDI CC to automate. Below the MIDI piano roll, the MIDI CC line appears.
3.  To add automation points, press Control and hover over the CC track. The cursor changes to the Pencil Editing Tool.\
    \
    ![midi-cc-pencil.png](Automation_assets/fac97386b3f97c26eca6668f9f03f0928ba8067b.png)
4.  While you hold Control, click the points you want to add on the automation line. Hold Control and drag to draw automation across the track.\
    \
    ![midi-cc-automation-drawing.png](Automation_assets/b0b35c8c5c54151a10ff7920cba64e0710640acd.png)
5.  To draw automation without snapping automation points to the grid, press Control+Command (macOS) while drawing automation. To draw automation without snapping to the grid on Windows, disable Snap.\
    \
    ![midi-cc-automation-command-ctrl.png](Automation_assets/f26c4de41c22183395eff4dc7ae167a9294f0143.png)
6.  To clear an automation point, hold Control and hover over an automation point. The cursor changes to the Eraser Editing Tool (the pencil turns around). Click an automation point to remove it.
7.  To clear a range of automation, select the range on the track, and press Delete.\
    \
    ![automation-range-selected.png](Automation_assets/96873c9f8d82ad19b80cc13b120757e0625397a7.png)

</div>

Your automation changes are played back when the session plays the clip and Automation is enabled. When Auto Mode is Off, automation is ignored.

## Automating MIDI program changes

You can automate MIDI program changes with the Program Change control.

## To automate a MIDI program change

1.  Enable the MIDI CC view by clicking the MIDI CC icon on a clip on the instrument track.

    <div layout="center" node-type="mediaSingle" data-width="55.27">

    <div data-alt="" collection="contentId-225740993" context-id="225740993" file-mime-type="image/png" file-name="midi-program-change-show.png" file-size="47108" data-height="341" data-id="d6528696-6ef4-4765-ae7e-81403493bee6" node-type="media" data-type="file" data-width="461" title="Attachment">

    ![midi-cc-enable.png](Automation_assets/4e34252408daa3c6db354efc24dad780ce3a26b7.png)

    </div>

    </div>

2.  On the Track control area in the Timeline, click the CC Controller button (this defaults to Volume), then from the browser choose Program Change. Below the MIDI piano roll, the MIDI CC area appears.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div data-alt="" collection="contentId-225740993" context-id="225740993" file-mime-type="image/png" file-name="midi-program-change-selected.png" file-size="8849" data-height="104" data-id="1e71a1a6-3b4c-4e3a-a884-097d564bdea2" node-type="media" data-type="file" data-width="461" title="Attachment">

    ![midi-program-change-selected.png](Automation_assets/2ba196ea271f41c957740887979298df4dea2acc.png)

    </div>

    </div>

3.  Double-click in the program change area where you want to program change to occur. The Program Change window appears.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div data-alt="" collection="contentId-225740993" context-id="225740993" file-mime-type="image/png" file-name="midi-program-change.png" file-size="105254" data-height="198" data-id="36b7e63b-e057-475a-b747-378fa3e2be8c" node-type="media" data-type="file" data-width="332" title="Attachment">

    ![midi-program-change.png](Automation_assets/a6cf88cf394966342ba0cb6cd6b3c0d01c11238e.png)

    </div>

    </div>

4.  Configure the program change by setting the Program Change, Bank MSB, and Bank LSB settings as required, then click Done. The program change appears in the track.

![mid-program-changes-in-track.png](Automation_assets/92564105025f58dc32528f530e4953bf6b18ee2f.png)

------------------------------------------------------------------------

# Trimming Automation

Trimming automation is the process of adjusting a range of automation data. You can trim a selection, a segment <span style="font-weight: 400;">(the line between two automation points)</span>, or all automation on a clip. 

## Show automation

Before you trim automation, you must show the automation in the Timeline that you want to trim. 

- Click View on the track to select the automated control you want to adjust.

**Tip:** Automated controls are highlighted in the Focus Browser. 

- To adjust a MIDI CC, open the MIDI CC view and choose the MIDI CC from the Track controls panel.

![automation-midi-cc.png](Automation_assets/3d07fa3354dd664e08b3c3eaa7513498ba17ad54.png)

## To trim all automation on a clip

1.  Hover the cursor over the automation line on the clip. The Automation Trim Editing Tool appears. Note that the cursor must be between automation points, and you may have to zoom in to place the cursor.
2.  Click on the automation line and move the automation up or down to trim.
3.  To trim automation with fine control, hold Shift while you drag the automation up or down.\
     

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div class="wysiwyg-text-align-center" collection="contentId-199393432" context-id="199393432" file-mime-type="image/png" file-name="automation-trim-clip.png" file-size="38115" data-height="161" data-id="34df8fbc-13ff-4c33-a1b1-57477768b2e9" node-type="media" data-type="file" data-width="384" title="Attachment">

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![automation-trim-clip.png](Automation_assets/7a3215ddcd5a3a02a9d4bb7dfdc6f7827460cdfc.png) </span>

</div>

</div>

**Note:** Automation is trimmed for the entire clip. Automation breakpoints are added at the start and end of the clip.

## To trim an automation selection

1.  Make a selection on the track or CC automation line.
2.  Hover the cursor over the automation line on the clip or CC track. Make sure the cursor is over the automation line and not an automation point. The Automation Trim Editing Tool appears.
3.  Click on the automation line and move the selected automation up or down to trim.
4.  To trim automation with fine control, hold Shift while you drag the automation up or down.\
     

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-199393432" context-id="199393432" file-mime-type="image/png" file-name="automation-trim-with-smart-tool.png" file-size="73168" data-height="297" data-id="e7240eca-2551-457b-863f-53a2dc539d2c" node-type="media" data-type="file" data-width="306" title="Attachment">

![automation-trim-with-smart-tool.png](Automation_assets/a6709cc09fd92831f25cd7a14a72c8f6eb526e49.png)

</div>

</div>

## To trim an automation segment

1.  Hover the cursor over an automation segment on the clip. The Automation Trim Editing Tool appears.
2.  Click on the automation segment and move the segment up or down to trim.
3.  To trim automation with fine control, hold Shift while you drag the automation up or down.\
     

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-199393432" context-id="199393432" file-mime-type="image/png" file-name="automation-trim-segment.png" file-size="27503" data-height="156" data-id="8f9375cd-ca80-4807-b41e-658ddf1d40a3" node-type="media" data-type="file" data-width="265" title="Attachment">

![automation-trim-segment.png](Automation_assets/bd84de98ccb8254477d1884116796558bdd5439a.png)

</div>

</div>

 

**Tip:** You may have to zoom in to trim an automation segment instead of the entire clip. You can only trim an automation segment when it has no slope (it begins and ends on the same value).

------------------------------------------------------------------------

# Clearing all Automation for a Selection

To clear all automation data within a selection, make a selection on one or more tracks in the timeline, then choose Edit \> Clear All Automation. When you clear automation for a selection, breakpoints are added at the beginning and end of the selection, if automation extends beyond the selection. This command clears automation for all controls and CCs for the selection.

![clear-all-automation.png](Automation_assets/f1d6917a4c3a283e840c54e14b709d6ee9022d13.png)

------------------------------------------------------------------------

# Writing and Trimming Control Values

To write a control value for a displayed automation parameter, press Command+/ (macOS) / Ctrl+/ (Windows). Type the control value and press OK. The control is adjusted to the value you specify.  If there is a selection, the selection is adjusted. Otherwise, the control is adjusted from the playhead location. 

![write-control-value.png](Automation_assets/0113744cbb22be077a49079edbefb2a567fe051c.png)

To trim a control value for a displayed automation parameter, press Command+Option+/ (macOS) / Ctrl+Alt+/ (Windows). Type the control value to trim and press OK. The control is trimmed by the value you specify.  If there is a selection, the selection is adjusted. Otherwise, the control is adjusted for the duration of the current control segment.

![trim-control-value.png](Automation_assets/d069bb6a4f9f9cb0b89fdcde6d4ed6e5649569ce.png) 

<span class="wysiwyg-font-size-small">260105</span>

