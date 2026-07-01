---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041441712-Working-in-Timeline-View.html'
converted_at: 2026-05-31T13:44:54Z
tool: htmlq+pandoc
title: 'Working in Timeline View'
word_count: 2238
---

# Working in Timeline View


You can warp a clip to change the tempo of the clip with or without changing the pitch of the clip. You can also warp audio to correct the timing within an audio clip, or to create an effect. You can use ARA (Audio Random Access) integration with supported ARA plug-ins, to seamlessly integrate warping plug-ins into the timeline.

## In this article

- [Warping Overview ](https://help.uaudio.com/hc/en-us/articles/44637107191700#h_01KD688GD2VJSY4KXA2KVNZJSQ)
- [Using ARA to Warp Tracks or Clips ](https://help.uaudio.com/hc/en-us/articles/44637107191700#h_01K7NKFCQ2MECVVZVKD87J6YAA)
- [Changing Audio Pitch or Duration ](https://help.uaudio.com/hc/en-us/articles/44637107191700#01K81GKADXDE3D629ADY73DVZ0)
- [Warp Trimming ](https://help.uaudio.com/hc/en-us/articles/44637107191700#h_01KD68FGY23PFB34J0ZR4M8P1P)
- [Warp Editing on Multiple Tracks ](https://help.uaudio.com/hc/en-us/articles/44637107191700#h_01KD69AG3T27Z0XMJQGSQZ8333)

------------------------------------------------------------------------

# Warping Overview

You warp audio in Warps view. Enter Warps view by clicking View on the Timeline track controls, and choosing Warps from the browser.

<div layout="align-start" node-type="mediaSingle" data-width="80">

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![choose-warps.png](Working%20in%20Timeline%20View_assets/c8ec138e475d67a9b669d7bece511fbc9dc3f3ea.png)
</figure>

</div>

 

Warps view shows transient markers that are automatically generated in audio clips on a track. Warps view also allows access to the Warp Trim Editing Tool, with which you can time-stretch or time-compress a clip. You can adjust these warp markers independently or in combination, or you can add manual warp markers.

You can also pitch shift an audio clip with clip controls.

## Warp algorithms

Warp algorithms are applied when you stretch or compress clips in Sync Clips to Tempo mode by adjusting session tempo, and when you pitch shift audio using the clip pitch controls. Warp algorithms also affect how LUNA plays back warp trimmed audio, and how audio plays when you make inter-clip adjustments using warp markers. Warp algorithms are applied non-destructively during playback.

You can audition different warp algorithms by changing the warp algorithm while playing back warped or pitch-shifted material.

- **Polyphonic:** The default setting for tempo-based tracks; works for complex musical material (chords), bands, and multiple instruments. While this works for monophonic material and drums, other specialized algorithms may provide more accurate results.

- **Monophonic:** Best suited for single-note material, such as a vocal line or a bass part.

- **Varispeed:** Mimics a tape transport by changing the pitch in relation to the tempo (pitch drops as speed slows; pitch rises as speed increases). Useful for creative sound manipulation or classic tape-style effects.

- **LUNA Razor Blade:** A UA-designed algorithm specifically for percussion and drums. Razor Blade minimizes artifacts and preserves transients to ensure drums don't lose impact when stretched. It is highly effective for multitrack drums, as it avoids phasing issues.

- **LUNA Polyphonic:** A general-use UA algorithm that handles a wide range of transients and pitched instruments. LUNA Polyphonic is less specialized for transients than Razor Blade, but sounds better on instruments like staccato guitars.

- **ARA:** Allows for the use of ARA-capable plug-ins (like Melodyne) directly within the LUNA timeline. When the ARA plug-in is selected, the plug-in is integrated into the playback engine for seamless audio adjustments.

------------------------------------------------------------------------

# Using ARA to Warp Tracks or Clips

ARA (Audio Random Access) plug-ins are incorporated directly into the LUNA timeline. An ARA plug-in panel appears at the bottom of the LUNA timeline window when instantiated. The ARA plug-in panel can be toggled open or closed by clicking the plug-in's name at the bottom of the window. If the plug-in has been instantiated on multiple tracks, the plug-in panel changes to reflect the selected track.

## ARA guidelines

- Installed ARA plug-ins can be selected from the ARA menu item on the Warp algorithms list. This menu item appears only if you have an ARA plug-in installed.

- ARA replaces any other Warp algorithm. A single clip or track can only have either a Warp algorithm or an ARA plug-in assigned. Separate clips on the same track can have different Warp algorithms or an ARA plug-in assigned.

- If you edit Warps on a clip or track, those changes must be committed (bounced) or reverted when you instantiate an ARA plug-in. When you instantiate an ARA plug-in as the Warp algorithm, you will be prompted to revert, commit changes, or cancel if any Warps need to be applied.

- Pitch adjustments must be applied (committed) when an ARA plug-in is instantiated on a clip. When you instantiate an ARA plug-in on a clip that has Pitch control changes, you will be prompted to revert, commit changes, or cancel.

<figure class="wysiwyg-image">
![ara-in-timeline.png](Working%20in%20Timeline%20View_assets/e34848605f60ded6a96397b2fcad174f568b2262.png)
</figure>

*An ARA plug-in in the timeline *

## To instantiate an ARA plug-in on a track

- In Timeline view, click the Warp control on a track, and choose ARA, then select the ARA plug-in from the list.

## To instantiate an ARA plug-in on a clip

1.  In Timeline view, double-click a clip.

2.  From the Warp Type menu, choose ARA, then select the ARA plug-in from the list.

## To show or hide an ARA plug-in panel

- Click the name of the plug-in at the bottom of the Timeline to show or hide the ARA plug-in panel. When the ARA plug-in is shown, the panel remains open as you switch between tracks. The panel will update to show the contents of any track on which that plug-in is instantiated.

- When you select multiple tracks with the same ARA plug-in , the ARA plug-in can show the editors for all selected tracks in the same window.

## To dock or undock an ARA plug-in panel

- Click the window icon at the top corner of the plug-in panel to dock or undock  the ARA plug-in panel.

------------------------------------------------------------------------

# Changing Audio Pitch or Duration

You can easily change the pitch of an audio clip. You can change the duration of an audio clip while retaining rhythm and pitch, or while changing the pitch and rhythm.

## Configuring a track for warping or pitch shifting

1.  In Timeline view, click the Warp control on a track, and choose a Warp algorithm.

2.  To view Warp markers on the track, click the View control on the track, and choose Warps from the browser.

3.  If you are adjusting tempo and want the track to conform to tempo changes, set the session, track, or clip to Clips Follow Tempo mode. \
    To apply these changes to multiple tracks, select multiple tracks before you make the selections.

<div layout="align-start" node-type="mediaSingle" data-width="80">

<figure class="wysiwyg-image">
![settings-for-warping.png](Working%20in%20Timeline%20View_assets/ecc8a7c940cfe8f6d11c25a68e3be4d59e51ef07.png)
</figure>

**Note:** You can apply pitch changes to clips, adjust warp markers and Warp Trim clips in Clips Follow Tempo mode or unsynced mode; however audio tracks will only adjust to session tempo changes in Clips Follow Tempo mode.

</div>

## Pitching an audio clip up or down while maintaining track length

To pitch an audio clip up, use the pitch clip controls. You can do this with the Pitch Editing Tool or the clip controls.

### Change clip pitch using the Pitch Editing Tool

1.  Hover over the pitch control in the clip header. The Pitch Editing Tool appears.
2.  Slide the control up or down to raise or lower the pitch. To type an exact value, double-click the pitch control, and type the pitch change value in semitones and cents in the popover, then press Return or click OK.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<figure class="wysiwyg-image">
![pitch-smart-tool.png](Working%20in%20Timeline%20View_assets/25ad28288ff6d514fd5924fdf9597a3479f2d7a9.png)
</figure>

</div>

### Change clip pitch using the Clip header controls

<div level="1">

1.  Double-click the name of the clip or the empty area next to the pitch control to open the Clip controls.

2.  Raise or lower the pitch with the Pitch knob. To type a value, double-click the Pitch knob and type a semitone and cent value, then click Done. \
     

    <figure class="wysiwyg-image">
    ![open-clip-controls.png](Working%20in%20Timeline%20View_assets/abd0c78f9de6a392b9f4bd719b08662d254fdd63.png)
    </figure>

------------------------------------------------------------------------

# Warp Trimming

</div>

You can Warp Trim to time-stretch or time-compress a clip. With Warp Trim, you can easily conform an imported loop to a tempo, or stretch a clip to double-time or half-time. You can also warp trim clips for creative effect.

**Note:** If you set the Warp Algorithm to Varispeed, Warp Trimming changes the pitch of the clip based on the amount of time stretching or time compression.

## Warp Trimming to time-stretch or time-compress a clip in Clips view

1.  With Clips view enabled, hover the cursor at the start or end of a clip, below the vertical center. The Trim Editing Tool appears.
2.  Option+drag (macOS) or Alt+drag (Windows) to Warp Trim. Warp Trim snaps to the grid if Snap is enabled unless you hold the Command (macOS) or Windows (Windows) key while trimming.

<figure class="wysiwyg-image">
![warp-trim-clip-view.png](Working%20in%20Timeline%20View_assets/394eb5fd4f9a9870dcfca3ca0da65f14dd90eed9.png)
</figure>

## Warp Trimming to time-stretch or time-compress a clip in Warps view

<div level="1">

1.  With Warps view enabled, hover the cursor at the start or end of a clip, below the vertical center. The Warp Trim Editing Tool appears. \
    \
    ![smart-tool-warp-trim.png](Working%20in%20Timeline%20View_assets/fec856e703edc0b7fe15f7bac3226df2e4f36c2d.png)
2.  Click and drag to Warp Trim. Warp Trim snaps to the grid if Snap is enabled unless you hold the Command key while trimming.

</div>

Depending on the algorithm, extreme Warp Trims may not play or may have undesirable audio artifacts. For UA-developed algorithms, extreme settings are indicated by the waveforms appearing red as they approach settings that may have undesirable audio artifacts, or may not play.

<div layout="align-start" node-type="mediaSingle" data-width="55">

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![warp-trim-overcompressed.png](Working%20in%20Timeline%20View_assets/87044d2fb059150c5ac7aabad4dadd7e71642beb.png)
</figure>

</div>

## Warping within a clip

Within a clip you can easily move elements back and forth in time with warp markers. LUNA automatically adds indicators to transients in each audio clip, and you can also add arbitrary warp markers. When you add warp markers, you can then move (stretch and compress) audio before and after the warp marker.

There are three ways you can add Warp markers to a clip:

- Adding a single warp marker on a transient indicator.
- Adding a Bounded Warp (three Warp markers on three adjacent transient indicators) with the Bounded Warp Editing Tool. A bounded Warp allows you to adjust the center Warp freely, while the Warp markers to the left and right prevent the changes from affecting the rest of the clip.
- Adding an arbitrary warp marker.

### To add and adjust a single warp marker

1.  Hover the cursor over a transient indicator. The Warp Editing Tool appears.
2.  Click to add a warp marker.
3.  Click and drag to adjust the warp marker. The warp marker snaps to the grid if Snap is enabled.
4.  To drag without snapping to the grid, press Command while you drag.

<div layout="align-start" node-type="mediaSingle" data-width="75">

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![single-warp-stretch-compress.png](Working%20in%20Timeline%20View_assets/d5d95927decbd722849c4b4b4edaa8de7c367530.png)
</figure>

</div>

 

### To add and adjust a Bounded Warp marker

1.  Hover the cursor below the vertical center of the clip, below a transient indicator. The Bounded Warp Editing Tool appears.
2.  Click to add a Bounded Warp. A warp marker appears on the transient you hovered over, and on the transient to the left and right.
3.  Click and drag to adjust the warp marker. The warp marker snaps to the grid if Snap is enabled.
4.  To drag without snapping to the grid, press Command (macOS) / Ctrl (Windows) while you drag.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="bounded-warp-stretch-compress.png" file-size="46665" data-height="354" data-id="b30accea-f331-498b-a9a9-7190fda1b101" node-type="media" data-type="file" data-width="362" title="Attachment">

</div>

</div>

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![bounded-warp-stretch-compress.png](Working%20in%20Timeline%20View_assets/fcdbb02893ed82451a4f242429157c16d0e932e2.png)
</figure>

### To add an arbitrary warp marker

1.  Hover the cursor near the top of the clip, where the transient indicators appear. You can add a warp marker anywhere (your cursor will snap to the grid if Snap is enabled).
2.  Click to add a warp marker.
3.  Click and drag to adjust the warp marker. The warp marker snaps to the grid if Snap is enabled.
4.  To drag without snapping to the grid, press Command (macOS) / Ctrl (Windows) while you drag.

<div layout="align-start" node-type="mediaSingle" data-width="30">

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![arbitrary-warp-marker.png](Working%20in%20Timeline%20View_assets/a0b25ef2eb7672483bd43813b2f35b55249170a0.png)
</figure>

</div>

 

### To delete warp markers

There are several ways to delete one or more warp markers.

- To delete a single warp marker, double-click it, or select the warp marker and press Delete.
- To delete multiple warp markers, select multiple markers and press Delete.
- To delete all markers from a clip, double-click the top of the clip. In the Clip popover that opens, click Reset Warps. Note that this will remove all warp markers and warped audio, and also revert any Warp Trim operations.

### To select and move multiple warp markers

- Hold Shift, then click in the vertical middle of the clip and drag to select multiple contiguous warp markers. Click one warp marker and drag to adjust all selected markers.

![select-contiguous-warp-markers.png](Working%20in%20Timeline%20View_assets/c207d4ce5930e26192632936d665181ff9368b78.png)

- Hold Shift, and click and drag over only each warp marker you want to select, to select multiple non-contiguous warp markers (tip: disable Snap). Click one warp marker, and drag to adjust all selected markers.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="select-non-contiguous-warp-markers.png" file-size="22443" data-height="189" data-id="5dd0723c-fa80-4b6e-8506-06eac0bc3be2" node-type="media" data-type="file" data-width="288" title="Attachment">

![select-non-contiguous-warp-markers.png](Working%20in%20Timeline%20View_assets/37bace09846e3cea0d8cc4081b0695b19b0ff994.png)

</div>

<div collection="contentId-200507413" context-id="200507413" file-mime-type="image/png" file-name="select-non-contiguous-warp-markers.png" file-size="22443" data-height="189" data-id="5dd0723c-fa80-4b6e-8506-06eac0bc3be2" node-type="media" data-type="file" data-width="288" title="Attachment">

</div>

</div>

------------------------------------------------------------------------

# Warp Editing on Multiple Tracks

You can warp edit audio on multiple tracks, with a selection, a selection group, or a track group.

When you warp audio on multiple tracks, you can specify tracks that have group editing priority for transient detection (for example, kick and snare tracks in a drum group), so that as you tab through transients in a selection group or track group, transients on the priority tracks are detected, while transients on other tracks are ignored.

See <a href="#h_01FTBRZRSGR28BG00Z7FHQ1VK9" target="_self">Setting group editing priority</a> to set track priority within groups for transient detection.

<span class="wysiwyg-font-size-small">260108</span>

