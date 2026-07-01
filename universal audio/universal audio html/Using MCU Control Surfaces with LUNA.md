---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/4406796987540-Using-MCU-Control-Surfaces-with-LUNA.html'
converted_at: 2026-05-31T13:44:59Z
tool: htmlq+pandoc
title: 'Using MCU Control Surfaces with LUNA'
word_count: 2922
---

# Using MCU Control Surfaces with LUNA


## In this article

- <a href="#h_01FFJHJZ86G332BK7C618Z6J3G" target="_self">MCU Control Surface Support in LUNA</a>
- <a href="#h_01FFJHK6ZZRF434WKCDBPYJDE8" target="_self">Setting up your MCU Control Surface with LUNA</a>
- <a href="#h_01FFJHKJP181N4SNNC8PF6S6ED" target="_self">MCU Control Surface Mix and Transport Features</a>
- <a href="#h_01FFJHM27GEF26FJ2KP7WT26EW" target="_self">Control Surface Function Keys</a>
- <a href="#h_01FFJHMK53EC7HEG4H4HYJBX1D" target="_self">Control Surface Automation Features</a>
- <a href="#h_01FFJHSY4K5SPFBZYJJN71GEHG" target="_self">Control Surface Navigation Features</a>
- <a href="#h_01FFJHTN5C0BNCM61K14CKFCG9" target="_self">Using Markers in LUNA with a Control Surface</a>
- <a href="#h_01GFV8T1N3H1BJWP3959XQYH43" rel="undefined" target="_self">Using V-Pots on a Control Surface</a>
- <a href="#h_01FFJHV1YNBRVWHJGX1D38YHVF" target="_self">Using Bus Spill on a Control Surface</a>
- <a href="#h_01FFJHVB65YJJPWXPTPSWF3GC5" target="_self">Undo</a>

------------------------------------------------------------------------

# MCU Control Surface Support in LUNA

LUNA supports MCU-compatible (Mackie Control Universal-compatible) MIDI control surface devices for externally adjusting LUNA's functions. 

- **Multiple-fader devices:** You can connect up to six MIDI control surfaces to LUNA using the MCU protocol. Multiple surfaces work together as one large mixing board.

- **Single-Fader Devices:** LUNA automatically configures these in *focus module* mode, meaning the fader always controls whichever track you have selected.

- **Compatibility:** LUNA supports the MCU standard, but button layouts and functions vary by device. Your MCU control surface might not support all functions, and some functions might be accessed with secondary/modifier keys on the control surface. Consult your control surface's documentation for specific operating instructions. 

<span id="focus"></span>

## Focus module overview

A focus module allows you to always have the track or bus you are working with at your fingertips, while one or more other control surfaces with more channels work seamlessly alongside the focus module to provide deeper mix control capabilities. When you define a single-fader control surface in LUNA control surface settings, that control surface should be automatically configured as a focus module. 

A focus module has the following features:

- Functions as a separate control surface from additional surface modules, which is isolated from channel banking and nudging, ensuring that the selected track always remains assigned to your designated control surface.
- When a bus is not spilled, the focus module shows the focus channel (the most recently selected channel). The focus module maintains this channel, even as you bank or navigate channel-by-channel through tracks on another control surface.
- When a bus is spilled, the focus module switches to show the bus channel, regardless of the selected channel.
- Only one focus module can be defined at a time.

**Note:** When you have enabled a focus module, and Show Main Track is off, when you select the Main track it does not appear on the focus module. It is assumed that when you disable Show Main Track, you are using a control surface that includes a dedicated Main Track fader.

------------------------------------------------------------------------

# Setting up your MCU Control Surface with LUNA

Connect your control surfaces to your computer, and make sure they are recognized or configured as required. A USB control surface typically only requires that it is connected and powered on, while a virtual control surface might require more extensive configuration. Refer to your control surface's documentation for specific details.

## Control surface notes

- For specific configuration steps and known issues for supported control surfaces, [<span class="wysiwyg-underline">see this article</span>](https://help.uaudio.com/hc/en-us/articles/4406777753236).
- Any required software and device firmware for your control surface should be installed and up to date.

## To set up your control surfaces with LUNA

1.  Open the LUNA Sidebar by clicking the three dots on the left of the screen, and clicking Settings, or choose LUNA \> Preferences from the app menu.

2.  Click Controllers.

3.  In one of the MIDI Control Surface rows, click under Input Device and select a connected MIDI control surface from the drop menu.

    ![surface-input-device.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/730a8eabe9388e8886d607f539bebf9caffd2bae.png)

4.  In the same MIDI Control Surface row, click under Output Device and select the same MIDI control surface.

    ![surface-output-device.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/14ca3b2979677a877ee9593e19d13922868b8532.png)

5.  Select the box in the On column to enable the control surface.

    ![surface-enable.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/a6c63342359d5e5a593c8b19e16e7bb4ec0792ee.png)

6.  If the control surface is a single fader control surface, the Focus Module box is automatically selected. if you do not want to use the control surface to follow the focused track, or to control a bus when the bus is spilled, deselect this box. See <a href="#h_01FFJG5Z6MJ9PVQGXNYA88F6HP" target="_self">Focus Module overview</a> for more information.

7.  If the surface is an extender module (for example, a Behringer X-Touch Extender or an additional SSL UF8 used as an extender), click the Extender box.

**Tip**: If your single fader control surface is not automatically configured as a focus module, check the focus module box. (To have your control surface considered for addition to the supported controllers list, you can submit feedback by clicking the feedback button in the upper right corner of the LUNA window.) 

## Reordering MCU control surfaces

When you have two or more MIDI control surfaces defined in LUNA, you can reorder control surfaces to change the order of tracks on the control surfaces.

### To reorder MIDI control surfaces

1.  Open the LUNA Sidebar by clicking the UA diamond logo on the left of the screen, and clicking Settings, or choose LUNA \> Preferences from the app menu.
2.  Click Controllers.
3.  Click the number of the MIDI control surface you want to reorder, and drag to the new location.

<div layout="center" node-type="mediaSingle" data-width="">

<div data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="5AaSUpAF_6dL82Fc6v7fBSPrmYK98QtNyK-JST6STrmDrqkuT0jPEvZhH33qtSg8tD_-DtlLzK0M7KrjjlpgMnOW_QiKuOMS4Yi1dZiggiIaSAqXqZREMhSLHamUg0wINP0mhBtX=s0" file-size="39374" data-height="432" data-id="d98cb568-3a02-475a-b5fb-d21c56635627" node-type="media" occurrence-key="385f8a44-dac3-461b-858a-c7854cb05a5b" data-type="file" data-width="1360" title="Attachment">

![surface-reorder.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/464fa8502bfb2f990702fe1ec420e7e571c60790.png)

</div>

</div>

The control surfaces are reordered. If you have an open session, the tracks are reallocated between the control surfaces.

## Configuring MIDI control surface settings

You can configure settings for how the control surface works with LUNA. To configure these settings:

1.  Open the LUNA Sidebar by clicking the UA diamond logo on the left of the screen, and clicking Settings, or choose LUNA \> Preferences from the app menu.
2.  Click Controllers.
3.  Adjust the settings as described in this section. The control surface is active when its ON button is lit.

### Surface Shows Tracks From

- **Main Window:** The control surface always registers tracks from the main window, even if you open and switch focus to alternate windows. 
- **Focused Window:** The control surface registers tracks from the currently focused window, whether main or an alternate. 

### Bank to Selected Track

- **On:** When you select a track, the control surface banks to show the bank which contains the selected track. 
- **Off:** You bank the control surface manually, and selecting a track in LUNA does not change the bank position on the faders.

### Scroll LUNA When Banking

- **On:** When you switch banks on the control surface, this option scrolls LUNA to show the tracks in the bank in LUNA on both the mixer and timeline. Note that if you have large track heights, not all tracks in a bank might show. 
- **Off:** LUNA's mixer and timeline windows do not adjust when you switch banks on the control surface. 

### Show Main Track

- **On:** Shows the Main track in the group of faders on the control surface. LUNA automatically places the Main track on the master fader for any control surface that supports it, but you can use this setting to show the Main track fader when you are using a control surface that doesn't have a dedicated master fader. 
- **Off:** Does not show the Main track on the group of faders on the control surface. Use this when your control surface has a dedicated master fader, and you don't want to duplicate the Main track fader. 

**Note:** When you have enabled a focus module, and Show Main Track is off, when you select the Main track it does not appear on the focus module. It is assumed when you disable Show Main Track that you are using a control surface that includes a dedicated Main Track fader.

### Use Surface Fader Taper

- On: LUNA adheres to the markings and positions on the control surface as closely as possible. For example, if you set a track to -15 dB, the control surface fader will register at the -15 dB mark on the control surface. This allows you to use the fader throw on the control surface as it was originally designed, instead of as it is represented in LUNA.
- Off: LUNA sets the faders to represent the physical fader orientation in LUNA, without adhering to the markings and numbers on the control surface. When you choose this setting, the fader layout on the control surface adopts the values of API Vision Console extensions on a track, or Neve or API Summing on a bus or the main track, just as it adjusts onscreen in LUNA.

------------------------------------------------------------------------

# MCU Control Surface Mix and Transport Features

Typical MCU-compatible control surfaces have some common mix and transport features. These include transport functions, track-level functions, and function keys.

## Transport Functions

MCU-compatible control surfaces use standardized controls for the system transport. 

<div layout="center" node-type="mediaSingle" data-width="">

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![surface-transport-controls.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/f45fab25c2e02d2deefbb62e162cf92b20559bbf.png)
</figure>

</div>

- **Play/Pause:** Starts playback; press again to stop.

- **Stop:** Ends playback.

- **Record Arm (Global):** Enables the global record function for all record-enabled tracks.

- **Loop:** Toggles loop playback on or off.

- **Fast Forward / Rewind:** Quickly navigates to either the start (Return to Zero) or the end of the session.

## Track functions

Per-track functions are available on your control surface. 

![surface-track-controls.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/8def1030f8e1cd742a76695f54ca75ad6c4b95e6.png)

<div layout="center" node-type="mediaSingle" data-width="">

<div data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="ogMnhmgbXDGPRmMtgKJF2mxyTsNLruEHe7q29AGK57TCBQbex1Vh7wyp89--yQ8s_TrGW2Jt3gPquKIP1_xt9f644FaNgeItKW2BT4A8zjcIk0uFZC9PpHbmNoP3KvhUMqI9mwWV=s0" file-size="62170" data-height="715" data-id="dda74b64-afbf-49e8-864b-1b19f192f7b4" node-type="media" occurrence-key="2cea363e-1681-481b-8ee2-416f8f1e3513" data-type="file" data-width="190" title="Attachment">

</div>

</div>

- **Name:** Displays the track name (abbreviated if necessary). *Note: Not supported by all devices.*

- **Pan Readout:** Shows the current pan value. *Note: Not supported by all devices.*

- **Select:** Selects the track in LUNA and on the surface. The last-selected track appears on the Focus Module.

- **Solo:** Solos the track.

- **Mute:** Mutes the track.

- **Record Arm (Track):** Record-arms audio/instrument tracks, or "spills" a bus or main track.

- **Volume Fader:** Adjusts the track volume level.

- **Pan:** Controls track panning. On stereo tracks, this adjusts both channels to match the physical knob position.

- **Click / Metronome:** Toggles the LUNA click track on or off (on supported surfaces).

------------------------------------------------------------------------

# Control Surface Function Keys

Function keys are an MCU standard, but not all control surfaces include them, and some control surfaces may have a limited set of function keys. LUNA supports the function keys F1 and F2.

- **F1:** Toggles between timeline and mixer views. 
- **F2:** Spills the main bus.

------------------------------------------------------------------------

# Control Surface Automation Features

The following control surface track automation features are available in LUNA. To change the automation mode with a control surface, a track must be selected. The automation mode of a selected track is displayed on the control surface.

**Note:** Write mode is not supported in LUNA.

 

![surface-automation-features.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/22d1badb0ae2745891097679e94acb79df602ee1.png)

<div layout="center" node-type="mediaSingle" data-width="">

- **Read:** Toggles automation between **Read** and **Off**.

- **Touch:** Toggles automation **Touch** mode.

- **Latch:** Toggles automation **Latch** mode.

- **Trim:** Toggles **Trim** automation while Read, Latch, or Touch modes are active.

</div>

------------------------------------------------------------------------

# Control Surface Navigation Features

MCU-compatible control surfaces include several features for navigating, resizing and zooming tracks in the timeline view. 

## Bank, next/previous track, and channel functions

Most control surfaces have banking and/or nudging features that shift the faders on the control surface to the left or right by eight or by one. Other control surfaces have a combination of banking and channel selection features that can shift the faders on the control surface to the left or right by eight, but can also select the next or previous track. 

Banking and nudging typically occurs without changing the track selection, and simply changes which faders the control surface shows. However, control surfaces that use channel selection to nudge cause the track selection to change, and can shift the control surface faders as the track selection is moved out of the fader area.

Different banking, channel navigation, and channel selection buttons are shown below. 

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="AoVNveQKcibxBc7dbCrydPK6Nesos6EKCD_zyhdSkFuAMT-WGqSev0DwsrVs8nGuy72huZTpuM92-n2V9VriLlWvsEyhbsimpa-ivjBCCvagtji7aqo5iR_lN9GwqB7rPadPWMvZ=s0" file-size="101824" data-height="444" data-id="5979334f-2af5-474e-a9a2-2f2413088b5e" node-type="media" occurrence-key="9204911a-3453-47c6-828b-95045cefcd2a" data-type="file" data-width="432" title="Attachment">

![surface-bank-channel.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/a16c772515a80bfe75a10aa09d88ef3ae8a0cc10.png)

</div>

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="AoVNveQKcibxBc7dbCrydPK6Nesos6EKCD_zyhdSkFuAMT-WGqSev0DwsrVs8nGuy72huZTpuM92-n2V9VriLlWvsEyhbsimpa-ivjBCCvagtji7aqo5iR_lN9GwqB7rPadPWMvZ=s0" file-size="101824" data-height="444" data-id="5979334f-2af5-474e-a9a2-2f2413088b5e" node-type="media" occurrence-key="9204911a-3453-47c6-828b-95045cefcd2a" data-type="file" data-width="432" title="Attachment">

![surface-banks-channels-daw-control.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/2f797abffcd6113231b53f47b0619d701266d869.png)

</div>

</div>

<div layout="center" node-type="mediaSingle" data-width="">

<div data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="WYnIgIwvudZRNa1GxDPEMtJ83vGYRW8xjlmI-yM_mmpIlcA8Zm6HA1Nr79ji5lqpPDQuCFKqAXeZNw34DgT84KqIWCzgbTVLkGbhDlthFXnHdBlt6uAYtHDYpjgn4FMTpLR2KTXW=s0" file-size="34542" data-height="291" data-id="b2cb379e-1e02-4312-93b3-3ff822dbc68d" node-type="media" occurrence-key="877f3dd6-b531-42ba-9af9-c2b99e90fed4" data-type="file" data-width="229" title="Attachment">

</div>

</div>

## Next and previous tracks and next and previous markers

Some surfaces have a 4-way arrow key pad for navigation. 

- The up and down arrows move the track selection one track to the left or right. 
- The right and left arrows move to the next or previous marker. 

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="TMXeYl2aYZdqzEC-xk_tceC_vZz3ogpDJeGJr_u5eAPtK37ZPVtwOgS-ei5FeBTwKX-fnmfjomT89slwjU9M3FI-PSFUJa9nzyXs1MLPJCoKIRs5eC36qWT-8Lubj5xvCO-fqTz3=s0" file-size="49275" data-height="355" data-id="83533e2f-c009-47cd-ace1-47b9114fa975" node-type="media" occurrence-key="b8b17b30-f500-4c74-975b-7326a2fe7951" data-type="file" data-width="498" title="Attachment">

![surface-select-left-right.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/77f0ef06fafefa2ead81d2c34e6d467d85db1acf.png)

</div>

</div>

## Scroll functions

Some control surfaces implement scrolling features with arrow keys, knobs, or a jog wheel. Typically, these controls allow you to navigate forward and backward one bar at a time. Scrolling functions might be labeled Jog, Scroll, or Next/Previous. 

## Zoom and resize functions

Some control surfaces implement timeline zoom and track height controls. For example, with the DAW Control app as shown below, the arrow buttons flash red when zoom functions are active.

<div layout="center" node-type="mediaSingle" data-width="">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-1559461889" context-id="1559461889" external="true" file-mime-type="image/png" file-name="a_r8RuO5_PYBPUc95Xtn2PMUZ61YQ8FUJOhRYfkiXj1QGJbmxkZC3it-P_9ioudDojJkbCPrsx43qLcfgQ8W_K7xBuA-F0qxVnXBk5B74xFIjBGi3vEiCSZ22L3YVnj5Vni11cVA=s0" file-size="35424" data-height="338" data-id="f0bc8904-2fd4-4d27-8428-9277c193cb97" node-type="media" occurrence-key="282f21aa-0684-4ecb-bcb1-52e4ab40d20b" data-type="file" data-width="437" title="Attachment">

![surface-track-zoom.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/95e7d891559d7097b245bebd9a116f38bb6a65ae.png)

</div>

</div>

**Zoom In:** Increases the horizontal size of the timeline data.

**Zoom Out:** Decreases the horizontal size of the timeline data.

**Reduce All Track Heights:** Shrinks the vertical height of all tracks simultaneously.

**Increase All Track Heights:** Expands the vertical height of all tracks simultaneously.

------------------------------------------------------------------------

# Using Markers in LUNA with a Control Surface

If your control surface includes a Marker button, you can use this to add a marker. You can also navigate between markers. 

## Place a marker

Press the Marker key on your control surface. This opens the marker browser, and you can optionally type a name for the marker and choose a color, then click Apply to add the marker.

## Navigate between markers

You can navigate between markers in different ways, depending on your control surface. On control surfaces that have arrow keys, use the right and left arrow keys to navigate between markers. On others, you may have to press the Section button, then use a control such as a jog wheel or knob to navigate between markers. 

------------------------------------------------------------------------

# Using V-Pots on a Control Surface

If your MCU control surface has V-Pots, LUNA supports additional features on that surface.

## Single Sends and CUEs V-Pot Mode

Press and hold the designated SENDS or CUES V-Pot assign buttons, then press down on the encoder to cause all V-Pots to display a given send or cue.

## Expanded Sends and Cues V-Pot Mode

MCU surfaces with V-Pots can show expanded controls for a selected track's sends and cues.

Press the designated send or cue mode button on your MCU surface to cycle through send and cue overview and detail pages, which allow control of the parameters on a selected track.

## Flip Faders

If your MCU controller has a Flip function, press Flip to swap the LUNA controls displayed on the V-Pots with those on the faders.

------------------------------------------------------------------------

# Using Bus Spill on a Control Surface

You can spill a bus by pressing the Record Arm button on a bus track. Bus track spill is dependent on your bus and track layout in LUNA, the number of faders and control surfaces in your control surface layout, and the number of tracks spilled.

## Bus spill: no focus module

When you spill a bus and you do not have a focus module configured, the bus track appears fixed at the right or left of one control surface, and the spilled tracks appear to the other side on the same or multiple control surfaces, with empty faders in between (if your bus spills less tracks than the control surface can represent). The bus fader remains fixed in that location, even if you navigate through tracks or banks on the control surface, so it is always available to adjust. The bus position is determined by the order of the bus in relation to its source tracks in LUNA.

 In the example below, using DAW Control on iPadOS, the bus spills tracks to the right of the bus control track.

 

![bus-spill-no-focus-module.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/b20856e7d4c4ec469fce6530a4c23858277314fe.png)

*Bus spill (no focus module)*

 

## Bus spill: with focus module

When you have a defined focus module in LUNA settings, and you spill a bus, that module automatically takes control of the fader for the spilled bus. The bus fader is locked on the focus module, while the rest of the tracks appear on your other control surface or control surfaces. This allows you to mix the bus with a single fader, while the other modules are spilled onto one or more other control surfaces. 

<div layout="center" node-type="mediaSingle" data-width="">

<figure class="wysiwyg-image">
![bus-spill-with-focus-module.png](Using%20MCU%20Control%20Surfaces%20with%20LUNA_assets/2026e7fec1f2d449b9efbf5aeb800ebeb93193fa.png)
</figure>

</div>

*Bus spill (with focus module)*

When you "unspill" the bus, by disabling Record Arm on the focus module, the focus module again controls the focused track.

 

------------------------------------------------------------------------

 

# Controlling Extensions and Plug-Ins

Many control surfaces can control Extensions and plug-ins in LUNA. 

For information on controlling Extensions and plug-ins with your MCU device, see the specific article for your control surface:

- [Behringer](https://help.uaudio.com/hc/en-us/articles/4406787140372)
- [DAW Control](https://help.uaudio.com/hc/en-us/articles/4406787178132) 
- [iCon Pro Audio](https://help.uaudio.com/hc/en-us/articles/4406787158548)
- [ONE Control Plus](https://help.uaudio.com/hc/en-us/articles/4410783094164)
- [Presonus FaderPort](https://help.uaudio.com/hc/en-us/articles/4406788167956)
- [SSL UF8](https://help.uaudio.com/hc/en-us/articles/4406786967828)
- [V-Control](https://help.uaudio.com/hc/en-us/articles/4406857951380)

 

------------------------------------------------------------------------

# Undo

If your control surface has an Undo button, it controls LUNA's undo function. 

**Note:** LUNA does not support Redo from a control surface.

 

<span class="wysiwyg-font-size-small">260102</span>

 

 

