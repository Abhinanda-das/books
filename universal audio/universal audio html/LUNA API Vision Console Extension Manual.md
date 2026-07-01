---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360060691752-LUNA-API-Vision-Console-Extension-Manual.html'
converted_at: 2026-05-31T13:44:57Z
tool: htmlq+pandoc
title: 'LUNA API Vision Console Extension Manual'
word_count: 10579
---

# LUNA API Vision Console Extension Manual


![api-vision-overview.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/384118d5c71ae491ca8d1e60987e2c3c3b8d567c.png)

# Transform LUNA Recording System into API's Flagship Analog Console

API® analog consoles are at the heart of some of the best-sounding albums ever recorded. From Fleetwood Mac's Rumours to Radiohead's In Rainbows, API desks add character, color, and punch to everything that passes through them.

The API Vision Console Emulation Bundle turns LUNA into a full API console. Track in real time through API preamp and channel modules, then mix with API's illustrious analog summing and bus compression — seamlessly switching between low-latency tracking using Apollo DSP (Apollo mode only), and high-powered native mixing within LUNA. You can create new audio, instrument, and bus tracks with API Vision Console elements pre-assigned, building sessions within the complete Vision console emulation experience.

This article includes:

- <a href="#h_01F5CQBVBPA120B06TGC0PKXRS" target="_self">LUNA Integration</a>
- <a href="#h_01F5CQC2W68FX7WB3GTAZ508VP" target="_self">UAD Plug-In Integration (Apollo mode only)</a>
- <a href="#h_01F5CQCNG2F5WJ4JBME715M0MY" target="_self">API Vision Console Emulation Extensions</a>
- <a href="#h_01F5CQCYT64X5B779BWP9WGET8" target="_self">Assigning API Vision to Tracks</a>
- <a href="#h_01F5CQDCV1AEAYGJAKPVP6M07P" target="_self">Using API Vision</a>
- <a href="#h_01F5CQDTQS5D3SCFK88VTSWD8S" target="_self">Switching Between API Vision Modules</a>
- <a href="#h_01F5CQE6T7VXCV7EGDEDEABF3E" target="_self">Using Sweep Filter and EQ Side Chains</a>
- <a href="#h_01F5CQENC2R6Y3ADX91QASZQJN" target="_self">Inserting EQs Before Dynamics</a>
- <a href="#h_01H2GQ4EFGH8R3AW5SJTK9HDS0" target="_self">Reordering API Vision Extensions with Plug-In Inserts</a>
- <a href="#h_01F5CQK2NBVE3H2ABRK69129VX" target="_self">Using Presets</a>
- <a href="#h_01F5C3NE3X0EEPBPN1AAKQ9C2T" target="_self">API Vision Channel Strip Parameters</a>
- <a href="#h_01F5CQKT7EWF6BWAKPB1D4GF0P" target="_self">API 2500 Bus Compressor Parameters</a>

 

 

------------------------------------------------------------------------

# LUNA Integration

API Vision extensions integrate into a unique Console row within the LUNA mixer, on the focus channel, and in the Console Browser. When API Vision extensions are instantiated, they appear in the Console row, and also as plug-in icons in the Inserts area. This allows you to re-order API Vision extensions with other plug-ins in the inserts. 

On an audio track, instrument track, bus, or the Main track, you can assign API Vision or API 2500.

With API Vision, you can toggle between the views for Input/Filter, Gate/Comp, and EQ on a track or globally for the session. You can also toggle the views based on selection grouping or a track group. 

With the API 2500 Bus Compressor, the entire set of controls is shown in compact form. 

You can expand API Vision Console or API 2500 to full width in the focus browser.

 

------------------------------------------------------------------------

# UAD Plug-In Integration (Apollo mode only)

When instantiated on a record or input-enabled track or on an ARM-enabled bus, in Apollo mode only, API Vision runs as a UAD plug-in on your Apollo DSP. When the track or bus is no longer ARM-enabled, API Vision runs natively. In this way, you can use a large number of API Vision processors, while only consuming UAD resources when required for real-time tracking and AUX-enabled buses.

## API Preamp Unison Integration

When API Vision is instantiated on a track, LUNA loads the API Preamp into the Unison insert, if there is no other Unison preamp loaded. The API Preamp, like any Unison plug-in, appears in Unison insert view only when the track is record-enabled or input-enabled. API Preamp controls appear inline in the Unison insert. The Gain control changes from blue to gray to indicate mic or line gain ranges in Unison insert view.

**Note:** Unison inserts are available only in Apollo mode.

API Preamp does not automatically open as a separate plug-in window when it is automatically instantiated. For access to all features, hover your mouse over the API Preamp plate in the Unison row and click the square icon. 

<div layout="center" node-type="mediaSingle" data-width="31">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="api-preamp-inline-view.png" file-size="71611" data-height="289" data-id="fe8cd6b6-a4bb-40db-8714-e56b874ad6b7" node-type="media" data-type="file" data-width="190" title="Attachment">

![api-preamp-inline-view.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/f1a603cc80a099107cccbfae7339f3aadeabca60.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

 *API Preamp (Unison insert view)*

</div>

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-preamp-expanded-unison-controls.png" file-size="747916" data-height="401" data-id="2734c633-4af0-4c23-8961-43dcb922bde2" node-type="media" data-type="file" data-width="311" title="Attachment">

</div>

</div>

![avc-preamp-expanded-unison-controls.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/a43b935e20626873d834035378958fe1f75bf11b.png)

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*API Preamp (expanded view)*

 

 

------------------------------------------------------------------------

<span style="font-size: 2.1em;">Control Descriptions</span>

</div>

Individual API Vision control functions are detailed in the <a href="#h_01F5C3NE3X0EEPBPN1AAKQ9C2T" target="_self">API Vision Channel Strip Parameters</a> and <a href="#h_01F5CQKT7EWF6BWAKPB1D4GF0P" target="_self">API 2500 Bus Compressor Parameters</a> sections.

 

 

------------------------------------------------------------------------

# API Vision Console Emulation Extensions

## API Vision Channel Strip

When instantiated, API Vision appears as a channel strip, including Input gain, Input filters, Gate/Expander, Compressor/Limiter, and EQ. You can change the EQ module from the default 550L (parametric) to the 560L (graphic) EQ. 

![avc-track-modules-callouts.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/da88da37c2a5c4d2d2df7be811bddb5f845cef31.png)

<div layout="center" node-type="mediaSingle" data-width="81">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-track-modules-callouts.png" file-size="375009" data-height="537" data-id="1e8c34de-6a2d-4bbe-92be-fda5ccc98c38" node-type="media" data-type="file" data-width="450" title="Attachment">

</div>

</div>

You can open the full channel strip in the Console browser by hovering your mouse over the API Vision plate in the Console row and clicking the square icon. 

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-hover-open-console-browser.png" file-size="28135" data-height="160" data-id="1085dd61-1c6e-4290-88f0-f28ab6ea2eae" node-type="media" data-type="file" data-width="207" title="Attachment">

![avc-hover-open-console-browser.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/4ac47114a090e2bfcb5e06ebc624c16c0550de84.png)

</div>

</div>

 

## API 2500 Bus Compressor

API 2500 is instantiated as a compact version of the API 2500 Bus Compressor, with the most important controls of the hardware shown.

![avc-2500-small-big.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/db42898c77b76bfc1ee306b6efd43128a37e8dff.png)

<div layout="center" node-type="mediaSingle" data-width="65">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-small-big.png" file-size="377563" data-height="487" data-id="43e0376f-5773-4b30-8888-ae38586917c4" node-type="media" data-type="file" data-width="409" title="Attachment">

</div>

</div>

To see the full set of controls, you can open the API 2500 Bus Compressor in the Console browser by hovering your mouse over the API 2500 plate in the Console row and clicking the square icon.

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-hover-open.png" file-size="59589" data-height="217" data-id="5060a3f1-980a-410d-9b48-4a9a657eb28a" node-type="media" data-type="file" data-width="208" title="Attachment">

![avc-2500-hover-open.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/c61c67b6148cbfe3b72af9bdc2fdbc4f9e8586ed.png)

</div>

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-hover-open.png" file-size="59589" data-height="217" data-id="5060a3f1-980a-410d-9b48-4a9a657eb28a" node-type="media" data-type="file" data-width="208" title="Attachment">

</div>

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-hover-open.png" file-size="59589" data-height="217" data-id="5060a3f1-980a-410d-9b48-4a9a657eb28a" node-type="media" data-type="file" data-width="208" title="Attachment">

</div>

</div>

------------------------------------------------------------------------

# Assigning API Vision to Tracks

There are several ways to assign API Vision to your tracks. 

## Creating tracks with API Vision

1.  In the Tracks Focus Browser, select a track type, in the Create New Tracks dialog (Track Menu \> New Tracks or Shift+Command+N) and select a track type, or click the plus (+) next to Tracks and select a track type.

2.  Choose the number of tracks to create and the format (MONO or STEREO). You can optionally type a name for the track or tracks here if desired. 

3.  For an instrument track, select the instrument.

4.  From the Console item, select API Vision.

5.  Click OK to create the tracks, or Cancel to stop track creation. 

![avc-create-new-tracks.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/c3a859387708ee5acfbf8a4e58379a8577db4435.png)

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="create-new-track.png" file-size="33603" data-height="179" data-id="77f05ab5-e0cc-4d01-adea-fd280022f482" node-type="media" data-type="file" data-width="253" title="Attachment">

</div>

</div>

## Creating tracks with API 2500

1.  In the Tracks Focus Browser, select a track type, in the Create New Tracks dialog (Track Menu \> New Tracks or Shift+Command+N) select a track type, or click the plus (+) next to Tracks and choose a track type.

2.  Select the number of tracks to create and the format (Mono or Stereo), and type a name for the tracks.

3.  To enable API 2500, select API 2500 from the Console list.

4.  To enable API Summing on a bus track, select API Summing from the Summing list. 

5.  Click OK to create the tracks.

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-create-new-track-bus.png" file-size="39161" data-height="200" data-id="6da3c151-536a-4374-9ae6-0d0b39ffaf4b" node-type="media" data-type="file" data-width="277" title="Attachment">

![avc-create-new-track-bus.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/cf244ac87bd09c1cc979d3ee40b4d64fd0c7c46e.png)

</div>

</div>

 

## Assigning API Vision or API 2500 to a Track

1.  Make sure the Console row is showing in the LUNA mixer.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-console-row-show-hide.png" file-size="93873" data-height="338" data-id="9914ecb8-e2f5-4da2-bda7-24905a86fe1f" node-type="media" data-type="file" data-width="505" title="Attachment">

    ![avc-console-row-show-hide.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/acd2d1a8fac51f369ac650cf76e922e39220a161.png)

    </div>

    </div>

     

     

2.  Click on the Console row on a track and choose API Vision or API 2500.\
    \
    ![avc-add-console.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/ea415f4e16c8f37e722bd1e0e35f2db2141ce43e.png)

API Vision or API 2500 is assigned to the track, and appears inline in the mixer, and in the Console browser.

<div layout="center" node-type="mediaSingle" data-width="65">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-in-track-and-browser.png" file-size="667036" data-height="762" data-id="4dbe3127-23f9-4d4d-a7b0-3251b66c4e19" node-type="media" data-type="file" data-width="510" title="Attachment">

![avc-in-track-and-browser.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/4023093f13ca9f2c4910caf14a08588218300cd5.png)

</div>

<div class="wysiwyg-text-align-center" collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-in-track-and-browser.png" file-size="667036" data-height="762" data-id="4dbe3127-23f9-4d4d-a7b0-3251b66c4e19" node-type="media" data-type="file" data-width="510" title="Attachment">

*API Vision assigned to a track*

</div>

</div>

![avc-2500-assigned-track-and-browser.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/8fae6b19535ca761bb1b5f4567c070f5671c99cf.png)

*API 2500 assigned to a track*

You can assign API Vision or API 2500 to multiple tracks with track selection groups or track groups:

- Assign API Vision to a track in an enabled selection group to assign to all tracks in that selection group. 

- Assign API Vision to a track in an enabled track group with the Mixing property enabled to assign to all tracks in that track group.

## Assigning API Vision to multiple tracks and buses

<div layout="center" node-type="mediaSingle" data-width="45">

</div>

You can assign API Vision to multiple tracks and buses with a menu item or with the Console button in the Mixer navigation panel. 

#### Assign API Vision to multiple tracks with Session Console Assignment browser

1.  Press the Console button in the Assign area (it will blink when activated), or choose Mixing \> Assign Console Extension from the LUNA menus. The console assignment browser opens, and the Console assignment inserts are highlighted with green icons in the Mixer.

    <div layout="center" node-type="mediaSingle" data-width="36">

    <div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-console-button.png" file-size="78794" data-height="253" data-id="5b29232d-910a-40cc-8634-6dcbbc63a2d4" node-type="media" data-type="file" data-width="258" title="Attachment">

    ![avc-console-button.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/8636547e5f92bdd286f3f85db3772be072b9fac5.png)

    </div>

    </div>

     

2.  In the Session Console Assignment browser, click the plus (**+**) next to a track name to assign API Vision to that track. Click the **X** next to a track name to remove API Vision from that track. 

3.  Click and drag to assign API Vision to multiple tracks, or to remove API Vision from multiple tracks.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-multiple-assign.png" file-size="356327" data-height="619" data-id="bbc0f61d-5e69-4aed-9d9e-e34006e2e20c" node-type="media" data-type="file" data-width="765" title="Attachment">

    ![avc-multiple-assign.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/843010ba9a29da523318cb4f6fe33b4e6e9d599e.png)

    </div>

    </div>

     

4.  When you are finished, click the Console button again to stop assigning API Vision to tracks.

#### Assign API Vision to multiple tracks in the Mixer

1.  Press the Console button in the Assign area (it will blink when activated). The console assignment browser opens, and the Console assignment inserts are highlighted with green icons in the Mixer.

2.  In the Mixer in the Console row, click on the green icons to assign API Vision to a track. 

3.  Click and drag to assign API Vision to multiple tracks. 

4.  In the Input row, click to assign API Preamp to the Unison insert on any record-enabled or input-enabled audio tracks (Apollo mode only).\
    **Note:** When you assign API Vision to an audio track with a mic, line, or Hi-Z input (in Apollo mode only), API Preamp is automatically assigned to the Unison insert on that track, if there is no other Unison preamp assigned to that track. Unison plug-ins are instantiated only when the track is record-enabled or input-enabled.

5.  When you are finished, click the Console button again to stop assigning API Vision to tracks.

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-multiple-assign-per-track.png" file-size="230260" data-height="529" data-id="4a51748f-4abc-4edb-8ae8-c14001e7e8c7" node-type="media" data-type="file" data-width="636" title="Attachment">

![avc-multiple-assign-per-track.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/43da22e08d425948e1a5f9f0f513f2a0433e4812.png)

</div>

#  

 

</div>

------------------------------------------------------------------------

# Using API Vision

After API Vision is loaded on a track, there are a number of ways you can work with it. You can enable individual modules on a single track or on multiple tracks. Individual controls for each module or multiple modules can be adjusted, and presets can be loaded and saved.

In ARM mode in Apollo mode only, API Vision automatically runs on UAD DSP, when a track is record or input-enabled. When mixing or not in ARM mode, API Vision runs natively.

## Working with API Vision 

You can use the option menus on the Console row in the Mixer or on the Focus channel to enable, disable, and configure API Vision, and to show the full channel strip in the Console browser. To use these options, hover your mouse over the top of the console row then click an icon.

<div layout="center" node-type="mediaSingle" data-width="81">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-hover-menu-items.png" file-size="263690" data-height="365" data-id="596d8b54-a084-4f7b-99d5-ed63bfaa835f" node-type="media" data-type="file" data-width="578" title="Attachment">

![avc-hover-menu-items.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/4227b77c3a75cd06a29ef8fba0341fb4affb9113.png)

</div>

</div>

- Click the plus (**+**) on the left of the console row to select API Vision.

- Click the square icon in the center of the console row header to open the full channel strip in the Console browser on the left of the LUNA window.

- Click the three dots (**•••**) to open the API Vision Console configuration menu. This menu allows you to copy, paste, remove, and disable API Vision, and to enable and disable individual modules and configure routing options. These module options are also available within the module interface.

## Enabling and disabling modules

When you first instantiate API Vision on an audio or instrument track, all modules are disabled. You must enable any modules you want to use on a track. Only those modules that are enabled use processor resources. You can enable modules on an individual track, on multiple tracks with selection or track grouping, and on all tracks to which API Vision is assigned.

**Note:** The API 2500 Bus Compressor is enabled when assigned, unlike the API Vision channel modules.

To enable or disable a module, click the ON button in a module to toggle the state, or use the menu items.

To power off all modules on a channel, click the Power button in the console browser.

## Module Notes

- The API Line Amp is always enabled, so you can add gain, enable the pad, flip the polarity, or apply the low cut filter without enabling the module. All other API Vision modules must be enabled. 

- To enable the side chain (SC) on the 215L Sweep Filter module, the 235L Gate/Expander or 225L Compressor/Limiter modules must be enabled. 

<div layout="center" node-type="mediaSingle" data-width="81">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-modules-enable-disable.png" file-size="203194" data-height="469" data-id="133f650b-a1c3-486a-bc7d-550dcbdc7401" node-type="media" data-type="file" data-width="501" title="Attachment">

![avc-modules-enable-disable.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/c3abed7b6517b150179c5766e2d825b62d4519bd.png)

</div>

</div>

 

## Enabling or disabling an API Vision module on multiple tracks

To enable or disable a module on multiple tracks you can use selection grouping or track groups. 

- With selection grouping enabled, select the tracks on which you want to enable or disable the module, then enable the module on one track. The module is enabled on all tracks in the selection group.

- With a track group, make sure that the Mixing property is assigned in the track group’s settings menu, and the track group is enabled. Enable or disable a module on a track in the track group to enable or disable that module on all tracks in the track group. 

## Enabling or disabling an API Vision module on all tracks

To enable or disable a module on all tracks on which API Vision is instantiated, Option-Click the On button on the module. The module state is toggled on all modules.

 

------------------------------------------------------------------------

# Switching Between API Vision Modules

In the Console browser, all modules for the track are shown in one layout. However, on a track in the Mixer or in the Focus channel, only one row of modules is shown at a time. You can choose which modules to show on one or more tracks.

- To switch between modules, click IN, DYN, or EQ at the top of the module row.

- To switch between modules with selection grouping enabled (in the Groups browser), select the tracks, then click IN, DYN, or EQ at the top of the module row.

- To switch between modules with a track group enabled, make sure that the track group includes the Mixing property, then on a track in the group, click IN, DYN, or EQ at the top of the module row.

- To switch between modules on all audio and instrument tracks, click IN, DYN, or EQ to the left of the tracks in the Console row.

- To switch between modules by clicking and dragging, click a module type on one track and then drag left or right to switch the view to that module on adjacent tracks.

<div layout="center" node-type="mediaSingle" data-width="81">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-track-module-switch.png" file-size="377130" data-height="508" data-id="b1e208d7-30ac-4f04-baef-f037507a4fa9" node-type="media" data-type="file" data-width="482" title="Attachment">

![avc-track-module-switch.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/46b6cc58b39cd47921be48d99f337cad9adb8a80.png)

</div>

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-track-module-switch.png" file-size="377130" data-height="508" data-id="b1e208d7-30ac-4f04-baef-f037507a4fa9" node-type="media" data-type="file" data-width="482" title="Attachment">

</div>

</div>

![avc-switch-all-modules.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/7a2ce4268558d738e3a1f27b5d7ccd0b7ed77eec.png)

<div layout="center" node-type="mediaSingle" data-width="65">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-switch-all-modules.png" file-size="163796" data-height="497" data-id="6470a4e9-06a6-4dc6-a080-4a13669c9163" node-type="media" data-type="file" data-width="332" title="Attachment">

</div>

</div>

## Changing controls

You can change controls on an API Vision module or on multiple modules by using the mouse and mouse+key combinations. 

- To change a control, click and drag the control. 

- To adjust a control with finer resolution, Shift-click and drag the control.

- To return a control to the default setting, Option-Click on the control. 

- To change a control on all channel strips, Command-Click and drag the control. 

- To enter or select a precise value for a control, double-click the control.

- On a stepped control, right-click or double-click to select a value from the list.

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-controls-double-click-right-click.png" file-size="498220" data-height="471" data-id="1d1d0006-156c-4e1b-9b44-fa324e07fad2" node-type="media" data-type="file" data-width="727" title="Attachment">

![avc-controls-double-click-right-click.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/8d1cc40bd9f69782982ea6e470c00236485c3c28.png)

</div>

#  

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-controls-double-click-right-click.png" file-size="498220" data-height="471" data-id="1d1d0006-156c-4e1b-9b44-fa324e07fad2" node-type="media" data-type="file" data-width="727" title="Attachment">

</div>

</div>

------------------------------------------------------------------------

# Using Sweep Filter and EQ Side Chains

You can enable dynamic side chaining for the 215 Sweep Filter, and/or for the 550L or 560L EQ. This moves the sweep filters and/or EQ out of the audio path and into the dynamics side chain path, so the compressor is keyed to those frequencies that are emphasized or reduced.

<div layout="center" node-type="mediaSingle" data-width="65">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-enable-sidechain.png" file-size="282731" data-height="515" data-id="3d6b048d-8954-4599-8007-2b7617f64622" node-type="media" data-type="file" data-width="409" title="Attachment">

![avc-enable-sidechain.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/aadb21f0655a326f6adc72ef1e5e7f15073aa663.png)

</div>

</div>

 

## Enabling the 215L Sweep Filter side chain

You can enable the side chain on the 215L Sweep Filters. The side chain routes the filters into the dynamic processors. For more information, see <a href="#h_01F9EWE3J8GEJWRB82MTAV85B2" rel="undefined" target="_self">215L Side Chain (SC)</a>.

- To enable the 215L Sweep Filter side chain, on the Input module, click the SC button. 

**Note:** The side chain can only be enabled when one or both dynamics processors (Gate/Expander or Compressor/Limiter) are enabled.

## Enabling the 550L/560L EQ side chain

You can enable the dynamic side chain on the 550L or 560L EQ. The side chain routes the output of the EQ module into the dynamic processors. For more information, see <a href="#h_01F9EWETHRRNZBXY81YX2JA93K" rel="undefined" target="_self">EQ Dynamics Side Chain (DYN SC)</a>.

- To enable the 550L or 560L EQ dynamic side chain, on the 550L or 560L module, click the DYN SC button. 

#  

 

------------------------------------------------------------------------

# Inserting EQs Before Dynamics

By default, the 550L or 560L EQ is routed after the dynamics processors. You can change the routing so the 550L or 560L process audio before the dynamics processors.

- To route the 550L/560L EQs before the dynamics processors, click the PREDYN button on the EQ module. For more information, see <a href="#h_01F9EWF95A1GSYG404JFSCXEFM" rel="undefined" target="_self">EQ Pre-Dynamics (PREDYN)</a>.

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-eq-pre-post.png" file-size="215995" data-height="474" data-id="75a62df8-bfc6-485d-b072-5cd23f1c7b86" node-type="media" data-type="file" data-width="496" title="Attachment">

![avc-eq-pre-post.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/0195521e8ac2a7147b6af9647adb33818fdd7e82.png)

</div>

#  

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-eq-pre-post.png" file-size="215995" data-height="474" data-id="75a62df8-bfc6-485d-b072-5cd23f1c7b86" node-type="media" data-type="file" data-width="496" title="Attachment">

</div>

</div>

------------------------------------------------------------------------

# Reordering API Vision Extensions with Plug-In Inserts

API Vision extensions are built into the Console row in LUNA. However, the API Vision extensions can be reordered with other plug-ins in the Insert section, to allow for mixing flexibility. On audio and instrument tracks, Console processing occurs after Tape extension processing. On buses and the Main track, console processing is ordered before or after Master Tape extension processing, according to the Pre-Fader or Post-Fader setting.

To reorder the console item, drag the API Vision or API 2500 insert plate to reorder it with other insert plug-ins.

- ![avc-plugin-reordering.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/d709d23192decaedcc69503d3df2afca4557ea3a.png)

<div layout="center" node-type="mediaSingle" data-width="65">

#  

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-plugin-reordering.png" file-size="85138" data-height="239" data-id="e9a9511d-76d1-4f4f-bda2-32c4bd7b92c4" node-type="media" data-type="file" data-width="420" title="Attachment">

</div>

</div>

------------------------------------------------------------------------

# Using Presets

API Vision Console extensions include a preset browser that provides deep and comprehensive ways to work with presets.

When you open an API Vision Console extension in the browser, the search bar takes keyboard focus so you can find presets and tags. API Vision includes a number of factory presets, sorted with tags for Type and Artist. The preset browser appears at the bottom of the console browser on narrower screens, and to the left of the console browser on wider screens. You can drag the console browser edge in or out to resize the browser, and arrange the presets at the bottom or to the left of the browser.

<div layout="center" node-type="mediaSingle" data-width="100">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-resize-browser.png" file-size="307459" data-height="373" data-id="daa357e5-48db-425f-8d3f-1db7cfe35670" node-type="media" data-type="file" data-width="659" title="Attachment">

![avc-resize-browser.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/85b9530c3d7de7d774b09441288ded81b253a3e9.png)

</div>

</div>

 

## Loading a preset

1.  Hover over the Console row entry and click the square to open the API Vision channel strip or the API 2500 Bus Compressor in the Console Browser. \
    ![avc-2500-hover-open.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/c61c67b6148cbfe3b72af9bdc2fdbc4f9e8586ed.png)

    <div layout="center" node-type="mediaSingle" data-width="36">

    <div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-hover-open.png" file-size="59589" data-height="217" data-id="5060a3f1-980a-410d-9b48-4a9a657eb28a" node-type="media" data-type="file" data-width="208" title="Attachment">

    </div>

    </div>

2.  From the Preset browser, select the preset.

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-preset-selected.png" file-size="300499" data-height="525" data-id="747021aa-9834-4f52-b7c9-14923c19f84b" node-type="media" data-type="file" data-width="533" title="Attachment">

![avc-preset-selected.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/cdf01d08cc354cb43a5ec47b7d6219ae46cde6d6.png)

</div>

</div>

 

Use the Up and Down arrows to navigate through presets. To search for a preset, click next to the magnifying glass at the top of the browser, and begin typing.

## Using Tags to find a preset by characteristics

The Tags feature allows you to find presets by type and by artist .

- To show the list of tags, click TAGS.
- To close the list of tags, click TAGS again.
- To filter the list of presets by a tag, click the tag. Click one or more tags to narrow the list of presets. Each tag you add narrows the list of results further, and also reduces the list of tags.
- To remove a tag, click one of the selected tags.
- To stop filtering by tags, click the X next to TAGS.

![avc-tags.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/73beac6adaaa57dd6e189d73115e7bfd535c1757.png)

## Saving a preset

1.  Select a preset from the Preset Browser.

2.  Make changes to the preset as required. 

3.  Click Save. The Save Preset As dialog opens.

4.  Click Save to save the changes to the existing preset, or type a name for the preset to save a new preset, then click Save. 

## Favoriting presets

You can favorite presets, and filter the list of presets by your favorites.

- To favorite a preset, hover over the preset name, and click the star to the right of the preset name.
- To unfavorite a preset, hover over the preset name, and click the favorite star again.
- To show only favorites in your preset list, click Favorites in the Tags bar.

![avc-favorites.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/7aebdfe49a71db28fdcd88cdd750e7329108ef5d.png)

 

------------------------------------------------------------------------

# API Vision Channel Strip Parameters

Individual control functions are detailed in this section, along with an overview of the design and signal flows.

## Modular Design

As with the original hardware, API Vision has a modular design. Each module controls a different signal processing function, and associated controls are grouped within each module. The following modules are contained in API Vision:

- 212L Microphone Preamplifier

- 215L High/Low Sweep Filters

- 235L Gate/Expander

- 225L Compressor/Limiter

- 550L Four-Band Equalizer

- 560L Ten-Band Graphic Equalizer

## Selectable EQ

### API Vision Channel Strip

The EQ module can be switched between the 550L and 560L equalizers with the TYPE button in the EQ module. In these operating instructions, “EQ” represents the 550L/560L EQ module in API Vision channel strip. 

The channel strip stores the current settings in both EQ modules, allowing for convenient comparisons of both EQ types or other creative uses.

## Signal Flows

A simplified view of the default signal flow routing within the channel strip is illustrated in the diagram below. The audio path is shown with solid lines, and the side chain control keys for the 235L and 225L dynamics modules are shown with dashed lines.

<div layout="center" node-type="mediaSingle" data-width="83">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-normal-flow.png" file-size="12159" data-height="65" data-id="6add733c-ccb2-4274-aa55-6cb6a33f5a6b" node-type="media" data-type="file" data-width="457" title="Attachment">

![avc-normal-flow.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/d6d189df99eb05fea61d6a4964ddf10980ce62b6.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Simplified default API Vision signal flow*

</div>

Signal flows can be re-routed via options in the channel strip. The EQ module can be placed before the dynamics modules via the PREDYN (pre-dynamics) button, and the sweep filters and/or EQ can be moved out of the audio path and into the dynamics side chain path via the SC (side chain) buttons in those modules.

Note that the side chains for the dynamics modules are in series by default (as in the diagram above). However, when the sweep filters and/or EQ are moved into the side chain via their SC buttons, the side chain inputs for the dynamics modules are in parallel, as shown in the diagram below with 215L SC enabled.

<div layout="center" node-type="mediaSingle" data-width="66">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-eq-pre-filter-sidechain.png" file-size="11976" data-height="103" data-id="8600bfa2-5d5a-4326-a532-f28d18d1061d" node-type="media" data-type="file" data-width="362" title="Attachment">

</div>

</div>

![avc-filter-side-chain.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/c692e99ddbb8e360ebd9a3c8cdf91a0d0d3d7a54.png)

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Simplified signal flow illustrating parallel side chain inputs with 215L SC enabled*

</div>

 

## 215L Side Chain (SC)

The SC button in the 215L module routes the sweep filters into the dynamics processing side chain. Click the SC button or its LED to toggle the setting.The default value is Off.

When the 215L side chain is active, signal output from the 215L module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules in parallel as shown in the diagram below. To listen to the 215L side chain key, simply disengage 215L SC to hear the equalized signal.

**Note:** The 215L module must be enabled for the 215L side chain to function.

 

<div layout="center" node-type="mediaSingle" data-width="66">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-eq-pre-filter-sidechain.png" file-size="11976" data-height="103" data-id="8600bfa2-5d5a-4326-a532-f28d18d1061d" node-type="media" data-type="file" data-width="362" title="Attachment">

![avc-filter-side-chain.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/c692e99ddbb8e360ebd9a3c8cdf91a0d0d3d7a54.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Signal flow with 215L Sweep Filters SC enabled*

</div>

 

### EQ Pre-Dynamics (PREDYN)

The Pre-Dynamics button (PREDYN) in the EQ module re-routes the EQ. By default, the audio signal is routed into the EQ after dynamics processing. When PREDYN is enabled, this routing is swapped, and the EQ precedes the dynamics modules instead.

When PREDYN is active, the dynamics side chain is always tapped after the EQ module, regardless of the state of the 215L module’s SC function. The effect of the PREDYN button is shown in the diagrams below.

**Note:** PREDYN has no effect when the EQ’s DYN SC button is active.

 

<div layout="center" node-type="mediaSingle" data-width="83">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-pre-eq.png" file-size="11845" data-height="64" data-id="75b6abfa-fa30-469b-b4a5-433b3ae01439" node-type="media" data-type="file" data-width="456" title="Attachment">

![avc-pre-eq.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/b2935287982dc66d65241a9dc188d8e8d4a4c4d8.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*PREDYN routes the EQ before the dynamics modules*

</div>

 

<div layout="center" node-type="mediaSingle" data-width="66">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-eq-pre-filter-sidechain.png" file-size="11976" data-height="103" data-id="8600bfa2-5d5a-4326-a532-f28d18d1061d" node-type="media" data-type="file" data-width="362" title="Attachment">

![avc-eq-pre-filter-sidechain.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/0f8556bb1aa114aa5a527b42ea146118c6881b86.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*EQ always precedes the side chain tap when PREDYN is active*

</div>

 

### EQ Dynamics Side Chain (DYN SC)

The DYN SC button in the EQ module routes EQ into the dynamics processing side chain. When the EQ side chain is active (when the DYN SC LED is lit), signal output from the EQ module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules.

<div layout="center" node-type="mediaSingle" data-width="66">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-eq-side-chain.png" file-size="11961" data-height="103" data-id="cfc5c8f4-cd38-417c-9e55-dbb6b287094a" node-type="media" data-type="file" data-width="362" title="Attachment">

![avc-eq-side-chain.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/0933c216230c004401cd00ac05442f9ddb01b57c.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Signal flow with EQ SC enabled*

</div>

 

Note that both the EQ and 215L modules can both be routed simultaneously to the dynamics side chain. In this case, the 215L precedes the EQ in the side chain path, as shown below.

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-both-sidechain.png" file-size="12695" data-height="123" data-id="0f920b90-3ada-43b7-add9-9d239c1174ef" node-type="media" data-type="file" data-width="310" title="Attachment">

![avc-both-sidechain.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/f4b291f120288ec01b4bbdf5d4b2a17985f87e01.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Signal flow with SC enabled in both 215L and EQ modules*

</div>

 

## Displayed Values

Knob settings, when compared to the interface silkscreen numbers, may not match the actual parameter values. For example, in the 215L Sweep Filters module, the highest value shown in the interface is 20 kHz. However, the actual value when the knob is at maximum is 40 kHz.

This behavior is identical to the original hardware, which is modeled exactly. When viewing control parameters (for example, by double-clicking a control), the actual parameter values are displayed.

 

## API Preamp - 212L Microphone Preamplifier

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-preamp-inline-controls.png" file-size="33306" data-height="217" data-id="b1b4bee2-2983-4cdb-9ad7-c226e6d88e04" node-type="media" data-type="file" data-width="96" title="Attachment">

![avc-preamp-inline-controls.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/82592168936cf22cbcdd8cfb508346c738ac7e25.png)

</div>

</div>

*API Preamp (Unison insert view)*

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-preamp-expanded-unison-controls.png" file-size="747916" data-height="401" data-id="2734c633-4af0-4c23-8961-43dcb922bde2" node-type="media" data-type="file" data-width="311" title="Attachment">

![avc-preamp-expanded-unison-controls.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/a43b935e20626873d834035378958fe1f75bf11b.png)

</div>

</div>

*API Preamp (expanded view)*

 

### 212L Input Select

The INPUT button switches between the mic and line input gain knobs. Press the button to toggle the active selection. 

#### Unison Interaction

Software and hardware control is mirrored and can be changed with LUNA software controls or with Apollo’s hardware button (MIC/LINE on Apollo rackmount models, or INPUT on Apollo Twin models).

### 212L Mic Gain

This knob adjusts the amount of gain applied to the mic input signal. The available range is 30 dB to 65 dB. The default value is 40.5 dB (unity gain).

**Tip:** Click the API logo atop the API preamp (when opened from the Unison insert) to return the gain to its default value.

#### Unison Interaction

Apollo’s hardware preamp knob can be used to adjust this parameter when Input Select is set to Mic, and/or when this parameter is selected in Gain Stage Mode.

### 212L Line Gain

This knob adjusts the amount of gain applied to the line input signal. The available range is 0 dB to 12 dB. The default value is 0 dB (unity gain). 

The available Line Gain range is adopted from API VIsion Console’s dedicated Line input functions and is not present on the original 212L hardware module.

#### Unison Interaction

Apollo’s hardware preamp knob can be used to adjust this parameter when Input Select is set to Mic, and/or when this parameter is selected in Gain Stage Mode.

### 212L Pad

PAD can be engaged to reduce signal levels when undesirable overload distortion is present at low preamp gain levels. PAD is engaged when its red LED is lit. Click the PAD button or its LED to toggle the setting.

#### Mic Pad

When PAD is enabled with mic input, the input signal level is attenuated (lowered) by -20 dB. 

#### Line Pad

PAD is unavailable when a LINE or HI-Z input is selected.

### 212L Phase

The Phase (ø) button inverts the polarity of the signal. The polarity is inverted when the button is depressed (inline view) or when the button’s green LED is lit (expanded view). Leave the button off (unlit) for normal polarity.

#### Unison Interaction

Software and hardware control is mirrored and can be changed within the module interface, with Console/LUNA software controls, or with Apollo’s hardware button.

### 212L Cut Filter

This button activates a 50 Hz low cut filter that has a slope of 6 dB per octave. This rumble filter is adopted from the API Vision console’s dedicated Line input functions and is not present on the original 212L hardware module.

#### Unison Interaction

Software and hardware control is mirrored and can be changed with LUNA software controls or with Apollo’s hardware button.

### 212L Meter (inline view)

The LED next to the gain control knob lights green, yellow, or red to indicate the signal level at the output of the 212L preamp module. The LED is unlit below -27 dB, green from -27 dB to -6 dB, amber from  -6 dB to below 0 dB, and red  when the converter is clipping.

### 212L Meter (expanded view)

The LED ladder VU Meter indicates the signal level at the output of the 212L preamp module.

## 215L High/Low Sweep Filters

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-215l-sweep-filter.png" file-size="35019" data-height="205" data-id="f1cc5d5f-e5f9-4552-abb5-175f7d501358" node-type="media" data-type="file" data-width="85" title="Attachment">

![avc-215l-sweep-filter.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/e3fcab45dc0e191315de975a069a4bd9ac84822e.png)

</div>

</div>

The 215L offers two sweepable cut filters, one each for low and high frequencies. The original hardware is transformer coupled and uses a passive filter circuit design for smooth tone.

### 215L Lo-Pass

The Lo-Pass (high cut) filter has a continuous range of 643 Hz to 40.8 kHz. The slope of this filter is 6 dB per octave. The default value is 40 kHz.

### 215L Hi-Pass

The Hi-Pass (low cut) filter has a continuous range of 12 Hz to 596 Hz. The slope of this filter is 12 dB per octave. The default value is 12 Hz.

### 215L SC (Dynamics Side Chain)

The SC button enables the 215L side chain filtering for the dynamic processors. Click the SC button or its LED to toggle the setting. The default value is Off.

For related information, see <a href="#h_01F9EWE3J8GEJWRB82MTAV85B2" rel="undefined" target="_self">215L Side Chain (SC)</a>.

### 215L On

This button enables the 215L module. The filters module is active when the button’s green LED is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processing load is reduced when this module is inactive.

 

## 235L Gate/Expander

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-235l-gate-exp.png" file-size="57594" data-height="207" data-id="15c3419f-c4fb-4632-90c0-0b74934b1885" node-type="media" data-type="file" data-width="86" title="Attachment">

![avc-235l-gate-exp.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/41389893c043c325726271e9c46a0c6a7431920f.png)

</div>

</div>

The 235L Gate/Expander module operates in either gate or expansion mode. Two attack speeds and a continuously variable release time are available in both modes.

### 235L Threshold

Threshold defines the input level at which expansion or gating occurs. The available range is from +25 dB to -47 dB. The default value is -47 dB.

Signals below the threshold level are processed by the module. Signals above the threshold are unaffected. Rotate this control counterclockwise to increase the gate/expand effect.

### 235L Depth

Depth controls the gate/expansion amount, or more technically, the difference in gain between the gated/expanded and non-gated/expanded signal. Higher values increase the attenuation of signals below the threshold. When set to zero, no gating or expansion occurs. The available range is 0 dB to -80 dB. The default value is -80dB.

#### Scaled Control

Although the Depth control has a full range of -80 dB, the scale is expanded in the first half of rotation so 0 to -9 dB is available for fine tuning of subtle, undetectable gating. The second half of rotation is from -10 to -80 dB for more drastic noise reduction.

### 235L Attack

This two-position switch determines how quickly the onset of gating/expansion occurs when the signal exceeds the threshold. Normal (25 milliseconds) and Fast (100 microseconds) settings are available. The default setting is Normal.

### 235L Release/Hold Knob

The function of Release/Hold knob (R/H) depends on the setting of the Release/Hold switch (Rel/Hld). With both switch settings, the available range of the knob is 50 milliseconds to 3 seconds. The default value is 0.5 seconds.

**Note:** Hold mode is only available when the 235L module is set to Gate mode with the Gate/Expander switch.

#### Release

When the input signal drops below the threshold level and the Release/Hold switch is set to Release, this knob sets the amount of time it takes for signals to decay to the Depth level.

Slower release times can smooth the transition that occurs when the signal dips below the threshold, which is especially useful for material with frequent peaks.

Fast release times are typically only suitable for certain types of percussion and other instruments with very fast decays. Using fast settings on other sources may produce undesirable results.

#### Hold

When the input signal drops below the threshold level and the Release/Hold switch is set to Hold, this knob sets the amount of time that signals are held at normal levels before signals return to the Depth level.

**Note:** When set to Hold, the release time is fixed at 100 milliseconds.

### 235L Release/Hold Switch

This two-position switch (REL/HLD) determines the behavior of the Release/Hold knob when the 235L module is set to Gate mode with the Gate/Expander switch. The default value is Release.

**Note:** This switch is locked in the Release position when the module is in Expander mode (Hold mode is unavailable in Expander mode).

### 235L Gate/Expander Switch

This switch (GTE/EXP) toggles the module between Gate and Expander modes. The default value is Expander.

#### GTE

When set to Gate mode, signals below the threshold are attenuated by the Depth amount.

#### EXP

When set to Expander mode, the gate applies downward expansion at a fixed 1:2 ratio, with the amount of gain reduction determined by the Depth control.

Expansion allows the signal to “sneak up” to the full signal level without any loss of “under threshold” nuances.

### 235L Meter

This meter displays, in dB, the amount of gain attenuation (downward expansion) occurring in the 235L module.

### 235L On

This button enables the 235L module. The module is active when the button’s green LED is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processing load is reduced when this module is inactive.

 

## 225L Compressor/Limiter

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-225l-comp-lim.png" file-size="58504" data-height="205" data-id="c2f1f529-a367-4066-953c-9db3c729443c" node-type="media" data-type="file" data-width="86" title="Attachment">

![avc-225l-comp-lim.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/a1bcd2f78d9f8c476da87dcb8dcac9ded81e5840.png)

</div>

</div>

The 225L Compressor/Limiter offers a continuously variable ratio between 1:1 (no compression) and infinity:1 (limiting). Three attack speeds and continuously variable release times are available. A hard/soft knee setting and a unique new/old setting are also available in the module.

### 225L Threshold

Threshold defines the input level at which compression begins. The available range is +13 dB to -18 dB. The default value is 13 dB.

Signals that exceed the threshold are processed by the Ratio value. Signals below the threshold are unaffected. Rotate this control clockwise to increase the compression effect. Double-click to type a precise value.

**Note:** The 225L compressor automatically increases makeup gain to compensate for levels that are reduced during compression (aka reciprocal gain). However, as with the original hardware, the compensated makeup gain levels are not perfectly linear.

### 225L Ratio

Ratio defines the amount of gain reduction applied to signals above the threshold. For example, a value of 2 (expressed as a 2:1 ratio) reduces the signal level above the threshold by half, with an input signal level of 20 dB being reduced to 10 dB.

A value of 1 yields no gain reduction. When the control is at maximum (∞), the ratio is effectively infinity to one, yielding the limiting effect. The available range is 1:1 to infinity. The default value is 4:1. 

Rotate this control to change the ratio. Double-click to type a precise value.

### 225L Attack

This three-position switch defines the attack time of the compressor. Available values are Fast (2 milliseconds), Medium (18 milliseconds), and Slow (75 milliseconds). The default value is Medium.

### 225L Release

Release sets the amount of time it takes for processing to cease once the input signal drops below the threshold level. The available control range is 50 milliseconds to 3 seconds. The default value is 0.5 seconds.

**Note:** Actual release times are program dependent.

Slower release times can smooth the transition that occurs when the signal dips below the threshold, which is especially useful for material with frequent peaks. However, if the release is too long, compression for sections of audio with loud signals may extend to sections of audio with lower signals.

Fast release times are typically only suitable for certain types of percussion and other instruments with very fast decays. Using fast settings on other sources may produce undesirable results.

Rotate this control to change the release time. Double-click to type a precise value.

### 225L Knee

The knee (onset) characteristic of the compressor/limiter can be set to Soft (SFT) or Hard (HRD) with this two-position switch. The default value is Hard.

Soft provides a more subtle compression resulting in a very natural, less compressed sound. Hard results in a more typical, sharp knee type compression that has a more severe limiting effect.

### 225L Type

The Type control switches the 225L compressor’s control side chain signal to use either a feed-back (OLD) or feed-forward (NEW) design, providing two types of gain reduction. The default value is Old.

Compressors typically have a side chain control signal based on either feed-back or feed-forward designs. NEW feed-forward gain reduction is typical of newer VCA type compressors that rely on RMS detectors for the side chain circuit. The OLD feed-back method is what most classic compressors use for the side chain circuit.

**Note:** Unlike the original hardware, side chain processing via the 215L and EQ modules can be performed with this switch in the OLD position (the hardware cannot use side chain filtering with feedback compression).

### 225L Meter

This meter displays, in dB, the amount of gain attenuation occurring in the 225L module.

### 225L On

This button enables the 225L module. The module is active when the button’s green LED is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processing load is reduced when this module is inactive.

 

## 550L Four-Band Equalizer

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-550l-para-eq.png" file-size="101880" data-height="411" data-id="759a35ca-bd66-452a-9449-ba36ce103c37" node-type="media" data-type="file" data-width="85" title="Attachment">

![avc-550l-para-eq.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/9f34ff83564591e2d488ea3afa8f243e497bbe86.png)

</div>

</div>

The 550L EQ is divided into four frequency bands: High Frequency (HF), High Midrange Frequency (HMF), Low Midrange Frequency (LMF), and Low Frequency (LF).

The 550L features API’s “Proportional Q” which continuously narrows the bandwidth of the filter as band gain is increased, providing (as stated by API) “an uncomplicated way to generate acoustically superior equalization.” The boost and cut characteristics are identical, allowing previous actions to be undone if desired.

### Band Controls

The four EQ bands (HF/HMF/LMF/LF) are controlled by dual-concentric rotary switches. The inner knob controls the band frequency (values in blue text) and the outer knob controls the band gain (values in white text). Available values for these controls are listed in the table below.

 

#### 550L Frequency and Gain Values

<table data-autosize="false" data-layout="default" data-number-column="false" style="margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p><strong>Band</strong></p></td>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p><strong>Frequency Values</strong></p></td>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p><strong>Gain (±dB)</strong></p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>High Frequency</p>
<p>(HF)</p></td>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>20, <strong>15</strong>, 12.5, 10, 7, 5, 2.5 (kHz)</p></td>
<td rowspan="4" class="pm-table-cell-content-wrap" data-colwidth="226.67" style="text-align: center; vertical-align: middle;"><p><strong>0</strong></p>
<p>2</p>
<p>4</p>
<p>6</p>
<p>9</p>
<p>12</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>High Mid Frequency</p>
<p>(HMF)</p></td>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>12.5, <strong>10</strong>, 8, 5, 3, 1.5 (kHz), 800 (Hz)</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>Low Mid Frequency</p>
<p>(LMF)</p></td>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>1000, <strong>700</strong>, 500, 240, 180, 150, 75 (Hz)</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>Low Frequency</p>
<p>(LF)</p></td>
<td class="pm-table-cell-content-wrap" data-colwidth="226.67"><p>400, <strong>300</strong>, 200, 100, 50, 40, 30 (Hz)</p></td>
</tr>
<tr>
<td colspan="3" class="pm-table-cell-content-wrap" data-colwidth="226.67,226.67,226.67"><p>Default Values are indicated in <strong>bold</strong></p></td>
</tr>
</tbody>
</table>

 

### Frequency

Frequency determines the center frequency of the band when the band is in peak mode (all bands) and the cutoff frequency when the band is in shelf mode (available with HF/LF bands only). The frequency for the band can be set using any of these methods:

- Drag the inner concentric knob to the desired value

- Click directly on the frequency value label to switch to that value

- Double-click or right-click the inner concentric knob to select the value from a list

### Gain

The gain for each band can be set using any of these methods:

- Drag the outer concentric knob handle to the desired value

- Double-click or right-click the outer concentric knob to select the value from a list

### Peak/Shelf Switches

The HF and LF bands are in shelf mode by default (switches in “down” position). When the Peak/Shelf switch is engaged for the band (in “up” position), the band is changed to peak mode. 

### PREDYN (EQ Pre-Dynamics)

By default, the audio signal is routed into the EQ after dynamics processing. When PREDYN is enabled (when its green LED is lit), this routing is swapped, and the EQ precedes the dynamics modules instead. For related information, see <a href="#h_01F9EWF95A1GSYG404JFSCXEFM" rel="undefined" target="_self">EQ Pre-Dynamics (PREDYN)</a>.

**Note:** PREDYN has no effect when the EQ’s DYN SC button is active.

### DYN SC (Dynamics Sidechain)

When DYN SC is active (when its green LED is lit), signal output from the EQ module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules. For related information, see <a href="#h_01F9EWETHRRNZBXY81YX2JA93K" rel="undefined" target="_self">EQ Dynamics Side Chain (DYN SC)</a>.

### EQ Type

The 550L EQ module is active when the TYPE button’s green LED is unlit. Click the TYPE button or its LED to switch to the 560L EQ module. 

**Tip:** The values are stored in both EQ modules, allowing for convenient comparisons of both EQ types or other creative uses.

### EQ On

This button enables the EQ module. The module is active when the button’s green LED is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processing load is reduced when this module is inactive.

 

## 560L Ten-Band Equalizer

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-560l-para-eq.png" file-size="61144" data-height="412" data-id="47050b99-61db-400d-8929-65bddfe53954" node-type="media" data-type="file" data-width="87" title="Attachment">

![avc-560l-para-eq.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/e8770e5bd6746f844dc90ba2210f2a7d7616d82c.png)

</div>

</div>

With ten bands of graphic EQ, the 560L EQ is ideal for shaping your mix with surgical precision. API’s proprietary “Proportional Q” intuitively widens bandwidth at lower boost/cut levels and narrows it at higher levels, giving you more musical control over precise bands of your mix.

**Note:** As with the original 560L hardware, the signal is boosted by approximately 0.4 dB even when all gain sliders are set to 0 dB.

### Gain Sliders

Each of the 10 sliders controls the gain for one frequency band. Each band can be adjusted to boost or cut the frequency by up to ±12 dB. The band center frequencies are listed below.

#### 560L Frequencies

|       |       |        |        |        |       |       |       |       |        |
|-------|-------|--------|--------|--------|-------|-------|-------|-------|--------|
| 31 Hz | 63 Hz | 125 Hz | 250 Hz | 500 Hz | 1 kHz | 2 kHz | 4 kHz | 8 kHz | 16 kHz |

**Tip:** To return a slider to the 0 dB position, click the slider’s frequency text label, or Option-click the slider. To reset all sliders to 0 dB, click the “0” text label above the sliders.

### PREDYN (EQ Pre-Dynamics)

By default, the audio signal is routed into the EQ after dynamics processing. When PREDYN is enabled (when its green LED is lit), this routing is swapped, and the EQ precedes the dynamics modules instead. For related information, see <a href="#h_01F9EWF95A1GSYG404JFSCXEFM" rel="undefined" target="_self">EQ Pre-Dynamics (PREDYN)</a>.

**Note:** PREDYN has no effect when the EQ’s DYN SC button is active.

### DYN SC (Dynamics Sidechain)

When DYN SC is active (when its green LED is lit), signal output from the EQ module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules. For related information, see <a href="#h_01F9EWETHRRNZBXY81YX2JA93K" rel="undefined" target="_self">EQ Dynamics Side Chain (DYN SC)</a>.

### EQ Type

The 560L EQ module is active when the TYPE button’s green LED is lit. Click the TYPE button or its LED to switch to the 550L EQ module.

**Tip:** The values are stored in both EQ modules, allowing for convenient comparisons of both EQ types or other creative uses.

### EQ On

This button enables the EQ module. The module is active when the button’s green LED is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processing load is reduced when this module is inactive.

 

## Global Controls

<div layout="center" node-type="mediaSingle" data-width="31">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-power-sc-link.png" file-size="11556" data-height="47" data-id="26f945d6-4acd-4644-a00d-5477bfdfcf93" node-type="media" data-type="file" data-width="171" title="Attachment">

![avc-power-sc-link.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/a488afa132e056d7bd3d3d6e8d9a522dce54e8a6.png)

</div>

</div>

SC Link (Side Chain Link)

When the module is used on a stereo signal, this button links the side chains of the left and right channels of the 225L and 235L dynamics modules so both channels are compressed by the same amounts. SC Link is active when the button’s green LED is lit. The default value is ON.

Linking the side chains prevents signals which appear on only one channel from shifting the stereo image of the output. For example, any large transient on either channel will cause both channels to compress, and the amount of compression will be similar to the amount of compression for a transient which appears on both channels at the same time.

**Note:** The SC Link button only appears on stereo tracks.

### Power

The module is active when one or more LEDs are lit. When power is off, all LEDs are unlit and processing is disabled.

#  

 

------------------------------------------------------------------------

# API 2500 Bus Compressor Parameters

API 2500 Bus Compressor in LUNA presents a reduced set of controls in the channel strip view, and the full set of controls in the console browser.

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-bus-2500-inline.png" file-size="117785" data-height="494" data-id="8cd422e5-8d91-4697-ba76-d03907611e3e" node-type="media" data-type="file" data-width="94" title="Attachment">

![avc-bus-2500-inline.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/eed178206bb533cfffc5e09b51cfc37c5a4a7606.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Channel strip view*

</div>

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-bus-main-modules.png" file-size="224651" data-height="417" data-id="3126cd02-38b1-44eb-b36f-33b4891a9f7e" node-type="media" data-type="file" data-width="258" title="Attachment">

![avc-bus-main-modules.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/899e17208c6861a87feeef72717cfca42e922299.png)

</div>

</div>

<div class="fabric-editor-block-mark fabric-editor-align-center" data-align="center">

*Console browser view*

</div>

 

**Note:** Some knob settings, when compared to the graphical user interface silkscreen numbers, may not match the actual parameter values. This behavior is identical to the original hardware, which is modeled exactly. When you right-click on a control or double-click a control to select or type a value, the actual settings can be specified

## Compressor Section

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-compressor.png" file-size="65625" data-height="312" data-id="08edd3be-bf2f-4bc3-862d-7ab4b2ccda1f" node-type="media" data-type="file" data-width="82" title="Attachment">

![avc-2500-compressor.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/720a02fa3bed4a07384098f3539026dd70621cb5.png)

</div>

</div>

THRESHOLD

This continuously variable knob determines the amount of compression to be applied to the input signal. Rotate THRESHOLD clockwise to lower the threshold and increase compression. Signals below the threshold are not compressed. The available range is +10 to -20 dB.

#### THRESHOLD LED

The red LED above the THRESH knob indicates when gain reduction is occurring in the compression circuit. The LED glows brighter as compression increases.

### ATTACK

The ATTACK knob sets the amount of time that must elapse after the input signal reaches the THRESHOLD level before compression is applied.

Seven fixed rates are available. The faster the attack, the more rapidly compression is applied to signals above the threshold. Slower attacks allow a signal’s attack transients (for example, the pluck of a string) to pass without compression, which can produce a punchier sound.

#### Available Attack Times

|       |        |        |      |      |       |       |
|-------|--------|--------|------|------|-------|-------|
| 30 μs | 100 μs | 300 μs | 1 ms | 3 ms | 10 ms | 30 ms |

 

### RATIO

The RATIO knob defines the amount of gain reduction to be processed by the compressor. For example, a value of 2 (expressed as a 2:1 ratio) reduces the signal above the threshold by half, with an input signal of 20 dB being attenuated to 10 dB.

**Note:** Signals must exceed the THRESHOLD value before they are attenuated by the RATIO amount.

Seven ratios are available. Higher ratios produce a more compressed sound. When the control is at maximum (∞), the ratio is effectively infinity to one, producing a limiting effect.

#### Available Ratio Values

|       |     |     |     |     |      |     |
|-------|-----|-----|-----|-----|------|-----|
| 1.5:1 | 2:1 | 3:1 | 4:1 | 6:1 | 10:1 | ∞:1 |

 

### RELEASE (fixed)

The first RELEASE knob (to the left of variable knob) sets the amount of time that must elapse after the input signal drops below the THRESHOLD before compression processing is ceased.

Six rates are available. When this control is set to the fully clockwise position, continuously variable release times can be adjusted with the RELEASE (variable) knob.

#### Available Fixed Release Times

|       |        |        |        |       |       |          |
|-------|--------|--------|--------|-------|-------|----------|
| 50 ms | 100 ms | 200 ms | 500 ms | 1 sec | 2 sec | Variable |

 

### RELEASE (variable)

The second RELEASE knob (rightmost knob in compressor section) continuously adjusts the compressor’s release time if the RELEASE (fixed) knob to the left of this control is at the fully clockwise position. The available range is 50 milliseconds to 3 seconds.

**Note:** This control has no effect unless RELEASE (fixed) is set to the fully clockwise position.

 

## Tone Section 

<div layout="center" node-type="mediaSingle" data-width="31">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-tone.png" file-size="20068" data-height="118" data-id="e72c778c-d22e-4ecb-9526-fa4a38d65327" node-type="media" data-type="file" data-width="85" title="Attachment">

![avc-2500-tone.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/3da4885d7b62e05acd5cbbc67db653d38f889f6b.png)

</div>

</div>

KNEE

The threshold knee (the compression onset characteristic) of the API 2500 can be set to SOFT, MEDIUM, or HARD. To change the KNEE setting, click the desired value or click the KNEE button to cycle through the available values.

#### Available KNEE Values

- SOFT – Provides a subtle transition into compression, resulting in a less obvious effect. 

- MEDIUM – Provides a slight “fade-in” transition into compression.

- HARD – Provides a more typical, sharp transition into compression.

 

### THRUST

THRUST can be set to NORMAL, MEDIUM, or LOUD. To change the THRUST setting, click the desired value or click the THRUST button to cycle through the available values.

THRUST is an API-patented circuit that inserts a high-pass filter in the control sidechain at the input of the RMS detector, limiting its response to lower frequencies.

The THRUST filter has a slope of 10 dB per decade, which is the inverse of the pink noise energy curve. THRUST adjusts the sidechain frequency response so each octave has the same amount of energy, creating a unique compression effect that reduces pumping and maintains punch.

<div layout="center" node-type="mediaSingle" data-width="">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-thrust.png" file-size="90758" data-height="284" data-id="819a3a33-bd04-48d0-b72c-6991b9f62ecf" node-type="media" data-type="file" data-width="1534" title="Attachment">

![avc-2500-thrust.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/dc454b82be3306385e145a29b939fd810b72e047.png)

</div>

</div>

Available THRUST Values

- NORMAL – The sidechain is unfiltered and compression response is uniform across the frequency spectrum. Behaves as most compressors do.

- MEDIUM – The sidechain is slightly attenuated at low frequencies and slightly boosted at high frequencies. Midrange frequencies are unfiltered and remain flat. Reduces low frequency pumping and increases compression on upper frequency peaks.

- LOUD – A gradual, linear filter is applied to the sidechain. Frequencies are attenuated 15 dB at 20 Hz and boosted 15 dB at 20 kHz, equalizing the energy entering the RMS detector. Noticeably increases low frequency punch.

### TYPE

TYPE changes the routing of the control sidechain signal within the compressor circuit. To change the TYPE setting, click a value or click the TYPE switch to cycle through the available values.

![avc-2500-tone-type-old.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/8e01877a4aa4a6726c7487687c3a08071c19ffa9.png)

![avc-2500-tone-type-new.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/90f1591e9dbb3cd7da68f58a40c7643587b7e850.png)

 

#### Available TYPE Values

- NEW – Feed-forward sidechain routing typical of modern VCA-based compressors. The control sidechain input signal is tapped from the uncompressed audio signal. Harder compression with more transparency.

- OLD – Feed-back sidechain routing typical of vintage compressors such as the API 525. The control sidechain input signal is tapped from the compressed audio signal. Smoother compression with more character.

**Note:** Unlike typical compressors, when tone TYPE is set to OLD (feed-back), the gain circuit is within the control sidechain. In this state, gain adjustments (whether automatic or manual), can change the compression amount.

 

### STEREO LINK Section 

<div layout="center" node-type="mediaSingle" data-width="31">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-stereo-link.png" file-size="21114" data-height="120" data-id="8bbc8b58-134c-4cdb-8547-15c4ede8b1ba" node-type="media" data-type="file" data-width="85" title="Attachment">

![avc-2500-stereo-link.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/72e4ee08dda4713f25ac8e48de1e70ef270d19e4.png)

</div>

</div>

L/R LINK

When the API 2500 is used on a stereo bus or the Main track, the stepped LINK knob allows the dynamics processors of both channels (left and right) to always be compressed in equal amounts (100%, fully linked), completely independently (0%, unlinked), or blended with a mix percentage (e.g., 50%, partially linked).

By de-linking the sidechains, dynamic interaction between the channels can be reduced or eliminated, enabling greater control of movement within the stereo field.

**Note:** When the API 2500 Bus Compressor used in a mono-in configuration, this switch is locked in the IND (independent) position.

#### Available L/R LINK Values

- 100% – The sidechains are stereo linked and the amount of compression is always the same for both channels. Stereo imaging at the input is maintained by preventing left- right shifting at the output when one channel has higher signal peaks compared to the other channel.

- IND (0%) – The sidechains are not linked and the amount of compression occurring is completely independent in both channels. If one channel has higher signal peaks than the other channel, the left-right imaging may shift.

- 50% – 90% – The sidechains are partially linked and the amount of compression occurring is a mixed blend of the left and right channels. The amount of blend can be set to 50, 60, 70, 80, or 90%.

#### STEREO LINK SHAPE

The SHAPE switch adjusts filtering of the control signal used by the L/R LINK parameter. Two SHAPE filters are available: HP (high pass/low cut) and LP (low pass/high cut). By enabling both filters, a bandpass filter shape is created.

By excluding frequencies from the L/R LINK control signal, sounds in only one channel that contain those frequencies will not cause the other channel to compress, while still linking the preferred frequency range.

To change the SHAPE setting, click a value or click the green SHAPE switch to cycle through the available values. The filter(s) is active when its LED indicator is lit.

**Note:** When the API 2500 Bus Compressor is used in a mono-in configuration, this switch has no effect.

## Output Section

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-power-output.png" file-size="41270" data-height="311" data-id="d416ccb4-49f9-4df0-a3da-0b93262231c3" node-type="media" data-type="file" data-width="82" title="Attachment">

![avc-2500-power-output.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/e73aba79d3d71ebe6d3db5ea8bec784113e512c2.png)

</div>

</div>

IN

The IN switch enables the compression circuit. The compressor is active when the green LED above the IN switch is lit. To toggle the IN/OUT state, click the IN switch, label, or LED.

When IN is disengaged, the compression circuit is bypassed while still routing the signal through the rest of the circuitry. With this “soft” bypass control, the signal is no longer compressed but the sound of the amplifiers, transformers, and other components are heard.

**Note:** If the BYP switch is engaged, the IN switch has no effect. 

### BYP (BYPASS)

The BYP button bypasses all hardware circuitry. In the original hardware unit, this switch controls a relay that hard-wires the inputs directly to the outputs.

The compressor is bypassed when the yellow LED above the BYP button is lit. To toggle the BYPASS state, click the BYP button, label, or LED.

**Tip:** To disable the API 2500 Bus Compressor and conserve processor resources, use the POWER switch. 

### GAIN

The API 2500 has automatic or manual make-up gain to compensate for the lowered output levels that result from signal compression. To toggle between automatic and manual make-up gain, click the red make-up GAIN switch, label, or LED.

**Note:** Unlike typical compressors, when tone TYPE is set to OLD (feed-back), the gain circuit is within the control sidechain. In this state, gain adjustments (whether automatic or manual), can change the compression amount.

#### AUTO GAIN

Automatic make-up gain is active when the red MAKE-UP GAIN switch is in the “out” position and the red LED above the switch is unlit.

When automatic make-up gain is active, the compressor’s output level is increased reciprocally as the compression amount increases, and decreases reciprocally as the compression amount decreases.

Automatic make-up gain facilitates easier adjusting and auditioning of the processor’s sound by keeping the output volume consistent as the compressor’s THRESHOLD and RATIO controls are adjusted. This function is especially useful in situations where adjustments need to be made without disturbing the output level to a recording or broadcast system.

#### MANUAL GAIN

When manual make-up gain is active, the red dB GAIN knob continuously adjusts the compressor’s output level. The available range is 0 to +24 dB.

**Tip:** Click the “0” text label to return the value to 0 dB.

Manual make-up gain is active when the red MAKE-UP GAIN switch is in the “in”position and the red LED above the switch (below the “man” text label) is lit.

**Note:** This control only operates when the make-up GAIN switch is engaged.

## Other Controls

### POWER

<div layout="center" node-type="mediaSingle" data-width="15">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-power-output.png" file-size="41270" data-height="311" data-id="d416ccb4-49f9-4df0-a3da-0b93262231c3" node-type="media" data-type="file" data-width="82" title="Attachment">

![avc-2500-power-output.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/e73aba79d3d71ebe6d3db5ea8bec784113e512c2.png)

</div>

</div>

The POWER switch determines whether the API 2500 Bus Compressor is active or not. To change the power state, click the yellow POWER switch or the POWER text label.

When set to off (switch unlit), the VU meters go dark to indicate signal processing has ceased. In this state, API 2500 Bus Compressor processing is disabled.

### MIX

<div layout="center" node-type="mediaSingle" data-width="16">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-mix.png" file-size="12749" data-height="73" data-id="979b5e49-d37d-4f61-9ff6-fe8f72a35419" node-type="media" data-type="file" data-width="85" title="Attachment">

![avc-2500-mix.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/f99b43db10346dbef5aab6f340af7faacebf422d.png)

</div>

</div>

A blended output balance between the signal processed by the API 2500 Bus Compressor and the original dry source signal can be adjusted with the MIX control. Mix facilitates parallel compression techniques without having to create additional routings in the DAW.

**Note:** The MIX control does not exist in the original hardware.

When MIX is set to 0%, only the unprocessed (dry) source signal is output. When set to 100% (the default value), only the processed (wet) signal is output. When set to 50%, an equal blend of both the dry and wet signals is output. The balance is continuously variable, and phase accurate, throughout the control range.

**Tip:** Click the 0 text label to set the control to the minimum position. Click the 100% text label to set the control to the maximum position.

### VU METERS

<div layout="center" node-type="mediaSingle" data-width="50">

<div collection="contentId-1249771548" context-id="1249771548" file-mime-type="image/png" file-name="avc-2500-vu-hr.png" file-size="62244" data-height="105" data-id="71110ab3-b72b-4a7f-83c3-cf17686103d1" node-type="media" data-type="file" data-width="256" title="Attachment">

![avc-2500-vu-hr.png](LUNA%20API%20Vision%20Console%20Extension%20Manual_assets/677620de792d64f3258e561cc16cd8e2d48ba104.png)

</div>

</div>

The calibrated VU Meters can display either input levels, output levels, or gain reduction levels. The levels being displayed are determined by the VU METER SOURCE switch.

Each channel (left and right) has its own VU Meter. When the API 2500 is used in a mono-in configuration, both meters display the same levels.

**Note:** The VU Meters display average loudness and do not display signal peaks. 

#### METER SCALES

The VU Meters have two different text scales printed on the meter background. The active scale is set with the VU METER SOURCE switch.

- IN/OUT Scale – The upper scale (ranging from -20 dB to +3 dB) is used to display input and output levels. With this scale, 0 VU represents +4 dBu.

- GR Scale – The lower scale (ranging from 20 dB to 0 dB) is used to display gain reduction levels.

### VU METER SOURCE

This switch determines what is displayed by the VU Meters. To change the VU Meters source setting, click a value, or click the METER switch to cycle through the available values.

#### Available METER SOURCE Values

- GR – The VU Meters display the amount of gain reduction occurring in each channel.

- OUT – The VU Meters display signal levels at the output of the API 2500 Bus Compressor.

- IN – The VU Meters display signal levels at the input of the API 2500 Bus Compressor.

### HEADROOM (HR)

The Headroom control is a UA-only feature that is not available in the original hardware. Headroom enables adjustment of the internal operating reference level for the API 2500 Bus Compressor so that the API 2500 Bus Compressor is not “pushed” into gain reduction as much. Headroom enables best practice operating level matching, or it can be used creatively to expand the sonic range of the processor.

By fine-tuning Headroom, the nonlinear I/O distortion and compression response characteristics can be tailored independently of signal input levels. Increasing Headroom (by rotating the control counter-clockwise) allows signals at the input to be pushed higher before they compress.

Headroom can be set (in dB) to 4, 8, 12, 16, 20, 24, or 28. The default value is 16 dB (when the set screw “dot” is in the straight up 12 o’clock position). Note that Headroom is increased as the dB value decreases.

**Tip:** Option-click the “HR” knob to return the control to the default value.

At higher dB values (clockwise rotation), signals will push the API 2500 Bus Compressor into gain reduction (and more non-linearity and “good” harmonic distortion color) more easily. Set the control to a lower value (counter-clockwise rotation) when less gain reduction and less color is desired.

**Note:** To avoid the temporary gain increases that can result when adjusting Headroom, automating this control is not recommended.

HR replaces the L/R TILT control that is available on the original hardware. Because L/R TILT is used to compensate for analog component tolerances and drift, it is not needed with the API 2500 Bus Compressor.

 

