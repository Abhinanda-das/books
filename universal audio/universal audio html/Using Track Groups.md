---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360050574411-Using-Track-Groups.html'
converted_at: 2026-05-31T13:44:56Z
tool: htmlq+pandoc
title: 'Using Track Groups'
word_count: 2278
---

# Using Track Groups


## In this article

- <a href="#h_01EKZDRPSJQXFNWDY9F55N43SK" target="_self">Track Group Properties</a>
- <a href="#h_01EKZDS5XNXPAYYE6CFMMR9P13" target="_self">The All Tracks Group and Selection Group </a>
- <a href="#h_01EKZDSJ2VHSA2H66PKXQFGH3Q" target="_self">Creating Track Groups</a>
- <a href="#h_01GCCSQAQNCMCGT0QE9044BTTJ" target="_self">Warp Editing with Track Groups</a>
- <a href="#h_01EKZDT7TKB33M9B4CAK8F4XG6" target="_self">Mixing with Track Groups</a>

## Track Groups overview

Track groups provide a way to make edits, mix changes, and add and control inserts across multiple tracks, multiple groups of tracks, or all tracks. When a track group is selected, edits and mix changes affect all tracks in the group.

------------------------------------------------------------------------

# Track Group Properties

With track groups you create, you can enable one or more of the following track group properties.

## Editing property

When the Editing property is enabled for a track group, edit commands and mouse gestures are linked across all tracks in the group. This includes cut, paste, and copy operations, fades, and warp editing.

The following controls and features apply when the Editing property is enabled, and you edit audio in a track group.

- **Timeline:** Clicking the playhead or making a selection on one track highlights that exact spot on all others.

- **Cutting, copying and pasting:** Cutting, copying, pasting, or trimming a clip affects every track in the group simultaneously.

- **Fades and warps:** Adjusting a fade-out or stretching audio (warping) on one track applies the same change to the rest.

- **Quantizing:** All tracks in the group are quantized. 

- **Track view:** Changing the height of one track or its view type (for example, from Clips to Volume) changes them all.

- **Tab to transient:** Tab to transient within an edit group moves from one transient zone to the next, requiring fewer tab keys to navigate with multiple tracks (see [Warp Editing with Track Groups](#h_01GCCSQAQNCMCGT0QE9044BTTJ)).

- **Automation:** Recording automation applies to all tracks in the track group. Note that drawing automation manually on one track in the group does not draw that same automation on other tracks in the group. 

## Mixing property

When the Mixing property is enabled for a track group, mixer controls and mix operations are linked on all applicable grouped tracks.

The following controls and features apply when the Mixing property is enabled for a track group.

- **Relative mix changes:** If you move one fader or pan control, the others move with it while keeping their original offsets.

- **Toggles:** Pressing Mute, Solo, Record Arm, or Input Monitor on one track activates it for the whole group.

- **Extensions:** Adding and removing extensions applies across track and selection groups. Setting changes are mirrored across the group. Note that preset selections for extensions are not mirrored across the group.

- **Automation:** Changing the automation mode (like "Touch" or "Read") and recording automation applies to every track in the group.

- **Preamp Auto-Gain:** Auto-Gain enable is grouped.

## Inserts property

When Inserts are enabled for a track group, inserts and insert controls are linked on grouped tracks. When you add an insert to a grouped track, it is added in the same slot on all grouped tracks. When you adjust controls on such an insert on enabled grouped tracks, the controls are adjusted for the same insert on all grouped tracks. Plug-in presets are not mirrored across groups. 

**Note:** Grouped controls only work on identical plug-ins that are inserted in the same slot in a track group. 

## Sends property

When Sends are enabled for a track group, sends are linked on grouped tracks. When you add or adjust a send to a grouped track with this property enabled, the same send is added or adjusted on all tracks in the group.

## Group editing priority

Prioritized tracks are checked first for transients, and assigned higher priority for audio quantizing.

### How group editing priority works

When tracks in a group or selection group are prioritized, transient, quantize, and warp operations prioritize those tracks for transient detection and for quantize operations. If a transient appears on multiple tracks, the transient on the priority track is chosen first. This is useful when editing drums, for example, to detect primary transients, and prevent a secondary track (for example, a room microphone track) from overriding a snare or kick track, to prevent phasing and timing issues.

When multiple tracks are selected, transients are detected first on prioritized tracks. When there is no transient on a priority track, transients on non-prioritized tracks are used.

------------------------------------------------------------------------

# The All Tracks Group and Selection Group 

There are two default track groups. These track groups cannot be edited, but they can be individually enabled or disabled.

- All Tracks Group - This group includes all tracks in the session, and enables Mixing, Editing, and Inserts. 
- Selection Group - This group replaces the Selection Grouping feature. When enabled, this allows you to use selection grouping, and enables Mixing, Editing, and Inserts. You can toggle this group with the existing Selection Grouping command, Track \> Selection Grouping, or Control+G on macOS.

------------------------------------------------------------------------

# Creating Track Groups

You can create, enable, disable, and edit groups from the Groups browser. You can create or add to groups with a menu item, or by right-clicking or control-clicking on one or more selected track names in the Timeline or Mixer. 

**Note:** The Browser must be visible to see the Groups browser. 

<div layout="align-start" node-type="mediaSingle" data-width="82">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="groups-panel.png" file-size="82566" data-height="222" data-id="8e670e07-09d6-4c5f-a0cf-54101356930d" node-type="media" data-type="file" data-width="531" title="Attachment">

![groups-panel.png](Using%20Track%20Groups_assets/2be4a0b1baa3f6e07b19be8f02ba029ce4507249.png)

</div>

</div>

## To create a track group using the Groups panel

1.  Select the track or tracks you want to add to the new group. 

2.  In the Groups panel, click the **+** symbol to add a group.

3.  The Create Group browser opens.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-create-no-annotation.png" file-size="175636" data-height="509" data-id="5da96b39-962d-449c-b56b-520a036d62fa" node-type="media" data-type="file" data-width="509" title="Attachment">

    ![create-group.png](Using%20Track%20Groups_assets/839c8ae6c3b0878dcf70c0ad15db1919f5922917.png)

    </div>

    </div>

4.  Type a name for the group.

5.  Select whether the group behavior applies to Mixing, Editing, and Inserts, and Sends.

6.  To add or remove a track, click it in the Tracks browser. You can also remove a track by clicking the X next to the track in the Grouped Tracks list.

7.  To prioritize a track, click the diamond next to the track name. Tracks that are prioritized have solid diamonds, and non-prioritized tracks have hollow diamonds.

8.  Click OK to create the group.

The new group appears in the Groups browser. If you don’t type a name for the group, the group is added as Group, plus a number, if applicable.

## To create a track group by dragging tracks

1.  Select one or more tracks in the Mixer or Timeline.

2.  Drag and drop the tracks to the top of the Groups browser.

     

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-create-by-dragging.png" file-size="81438" data-height="210" data-id="75d6d4ef-c480-45d1-919a-ab2f9ecb5dd8" node-type="media" data-type="file" data-width="351" title="Attachment">

![group-create-by-dragging.png](Using%20Track%20Groups_assets/5649a927b17bc6aca07ec55323127babf6b84d2f.png)

</div>

</div>

 

The label for the Groups browser changes to Create New Group when you drag the tracks over the top of the browser. When you drop the tracks, a new group called GROUP, plus a number, if applicable, is created. 

## To create a track group with the LUNA menu or a key command

1.  Select the track or tracks you want to add to the new group. 

2.  Select Track \> New Track Group, or type Command+G (macOS) / Ctrl+G (Windows).

3.  The Create Group browser opens.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-create-no-annotation.png" file-size="175636" data-height="509" data-id="5da96b39-962d-449c-b56b-520a036d62fa" node-type="media" data-type="file" data-width="509" title="Attachment">

    ![create-group.png](Using%20Track%20Groups_assets/839c8ae6c3b0878dcf70c0ad15db1919f5922917.png)

    </div>

    </div>

     

4.  Type a name for the group.

5.  Select whether the grouped track behavior applies to Mixing, Editing, Inserts, and Sends.

6.  To add or remove a track, click it in the Tracks browser. You can also remove a track by clicking the X next to the track in the Grouped Tracks list.

7.  To prioritize a track, click the diamond next to the track name. Tracks that are prioritized have solid diamonds, and non-prioritized tracks have hollow diamonds.

8.  Click OK to create the group.

## To add tracks to a track group by dragging

1.  Select the track or tracks you want to add to the group. 

2.  Drag the track or tracks over the group in the Groups browser. The Browser name changes to Add to Group, and the group over which you hover is highlighted.

    <div layout="center" node-type="mediaSingle" data-width="45">

    <div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-add-tracks-drag.png" file-size="51321" data-height="230" data-id="22b52ef8-4ebd-4eb3-8048-914a51f76e30" node-type="media" data-type="file" data-width="255" title="Attachment">

    ![group-add-tracks-drag.png](Using%20Track%20Groups_assets/ecb072e93f01c8c075dc9d53e627f4ca4c6ad53d.png)

    </div>

    </div>

3.  Drop the tracks to add them to the group. 

## To edit a track group

1.  Right-click or Control-click on the track group in the Groups browser.

    <div layout="center" node-type="mediaSingle" data-width="45">

    <div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-context-menu.png" file-size="84154" data-height="290" data-id="e418e317-128a-4586-8fdc-3d8d946f8281" node-type="media" data-type="file" data-width="255" title="Attachment">

    ![group-context-menu.png](Using%20Track%20Groups_assets/408420a3fcf478b8a51d2bc4c44f5405be747d1f.png)

    </div>

    </div>

2.  To change the Mixing, Editing, Inserts, or Sends property, select from the menu. 

3.  To edit tracks in the group or the group name, select Edit.

    ![edit-group.png](Using%20Track%20Groups_assets/c267e128d6ffaa909fde2e4b916999fd568d97cb.png)

4.  Make the changes to the group, and click OK. To discard changes to the group, click Revert.

## To delete a track group

- In the Track groups browser, right-click or Control-click on a track group, and select Delete. 

The track group is deleted, but tracks are not deleted. You cannot delete the All Tracks Group or Selection Group. 

## To show or hide the tracks in a track group

- In the Track Groups browser, click the indicator to the right of the track group name to toggle track group visibility.
- To show only the tracks in the group, Command+Click (macOS) / Control+Click (Windows) the indicator.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="groups-hidden-shown.png" file-size="58585" data-height="230" data-id="d8ad7bc0-e25e-42b5-a7a7-f0b1732ec095" node-type="media" data-type="file" data-width="417" title="Attachment">

![groups-hidden-shown.png](Using%20Track%20Groups_assets/e7e66fd5027feb81b101ab6700850694d5044a38.png)

</div>

</div>

## To enable or disable a track group

- Click on the track group name to toggle the enabled or disabled state. Enabled track groups are highlighted.

## To enable or disable all track groups

- Press Command+Shift+G (macOS) / Ctrl+Shift+G (Windows), or click the toggle on the upper right of the Groups browser.

<div layout="align-start" node-type="mediaSingle" data-width="82">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-all-enable-disable.png" file-size="83812" data-height="261" data-id="09c7a49f-60a1-4b17-89a8-f9d64893ffff" node-type="media" data-type="file" data-width="514" title="Attachment">

![group-all-enable-disable.png](Using%20Track%20Groups_assets/ba8a44933eabde4b2e2b81399283315e1154a6ca.png)

</div>

</div>

------------------------------------------------------------------------

# Warp Editing with Track Groups

When a track group with audio tracks is enabled for Editing, you can perform multitrack Warp edits. Use this to tighten up the performance on drum tracks, for example. Warp markers are placed for a group of tracks by finding the earliest transient within a transient zone (within a 30 millisecond range). To place a warp marker at a specific location regardless of the transient zone, Control-click the location where you want to add the warp marker. 

**Note**: Warp markers for prioritized tracks take precedence over non-prioritized tracks. For this reason, when transients are detected on prioritized and non-prioritized tracks in a group, the automatic warp markers are aligned first with transients on the prioritized tracks within a transient zone, then with transients on non-prioritized tracks.

## To Warp edit multiple tracks

1.  Enable a group with the tracks you want to edit. 

2.  In the Timeline, click View on one of the tracks in the group, and select Warps from the browser.

    <div layout="center" node-type="mediaSingle" data-width="70">

    <div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-warp-enable.png" file-size="137311" data-height="400" data-id="714d1adc-2195-472e-b383-139c8de9be7f" node-type="media" data-type="file" data-width="488" title="Attachment">

    </div>

    </div>

    ![group-warp-enable.png](Using%20Track%20Groups_assets/c769482d2442e8d354f3bb2e064b7d5cb9b404de.png)

     

3.  Click next to Warp and set the Warp Algorithm for the track group from the menu.

    ![group-warp-algorithms.png](Using%20Track%20Groups_assets/b2cb4503bf5bf7aa816e5c24345bd87a72010d27.png)

4.  Place one or more Warp markers on a track in the group. Warp markers are placed on all tracks in the group. Warp markers are placed on all tracks in the group. A warp marker is placed on prioritized tracks first, then on the earliest transient in the group. To place an arbitrary warp marker, Control-click.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="multitrack-warp-edits.png" file-size="38560" data-height="544" data-id="fad6533f-d736-426b-b7a4-1dcdf79d379d" node-type="media" data-type="file" data-width="425" title="Attachment">

![multitrack-warp-edits.png](Using%20Track%20Groups_assets/d8438b57a55e1e9acdcdecbd993bb6a968242f57.png)

</div>

</div>

 

When you adjust Warp markers on a track in a group, Warp markers on all grouped tracks are warped along with the Warp marker you move.

------------------------------------------------------------------------

# Mixing with Track Groups

When a track group is enabled for Mixing, grouped tracks in the Mixer appear highlighted. When you move a fader or knob on a grouped track, all other knobs or faders move relative to the knob you move. If you drag tracks to reorder them, all group members move as a block.

To adjust a single control without affecting the rest of the group, Control-click the control. The group is temporarily suspended while you configure the control. 

 

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="grouped-tracks-mixer.png" file-size="138824" data-height="394" data-id="4eb9c37f-fb21-428c-b0ab-cbd72c384af2" node-type="media" data-type="file" data-width="286" title="Attachment">

![grouped-tracks-mixer.png](Using%20Track%20Groups_assets/844f56d5574c3a87820bdbcbb8c41b5b40358614.png)

</div>

</div>

 

## Using Inserts with Track Groups

To use Inserts with Track Groups, enable the Inserts property in the Track Group.

When you add an insert to a track, the same insert is added in the same slot on other tracks in the group. The controls for grouped plug-ins are linked, so any adjustments you make to one plug-in are made to the identical plug-ins on the other grouped tracks.

**Note:** Presets are not applied across groups. 

 

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-insert-plug-ins.png" file-size="1463305" data-height="629" data-id="c71593b1-54ff-4c37-899b-1e36a2c1f9c2" node-type="media" data-type="file" data-width="645" title="Attachment">

![group-insert-plug-ins.png](Using%20Track%20Groups_assets/062d4b6fd30afc3020430be1baad2ec84946538e.png)

</div>

<div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-insert-plug-ins.png" file-size="1463305" data-height="629" data-id="c71593b1-54ff-4c37-899b-1e36a2c1f9c2" node-type="media" data-type="file" data-width="645" title="Attachment">

</div>

<div collection="contentId-662044673" context-id="662044673" file-mime-type="image/png" file-name="group-insert-plug-ins.png" file-size="1463305" data-height="629" data-id="c71593b1-54ff-4c37-899b-1e36a2c1f9c2" node-type="media" data-type="file" data-width="645" title="Attachment">

## Using Sends with Track Groups

To use Sends with Track Groups, enable the Sends property in the Track Group.

When you add a send on a track, the same send is added in the same slot on other tracks in the group. The controls for sends are linked, so any adjustments you make to one send are made to the same send on the other grouped tracks.

</div>

</div>

![sends-grouped-adjust.png](Using%20Track%20Groups_assets/35b1045fd7a22c15c12e34ebe6217cb440a46358.png)

 

<span class="wysiwyg-font-size-small">260105</span>

