---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/30088622351636-Using-Multi-Output-Plug-Ins-in-LUNA.html'
converted_at: 2026-05-31T13:44:50Z
tool: htmlq+pandoc
title: 'Using Multi-Output Plug-Ins in LUNA'
word_count: 1689
---

# Using Multi-Output Plug-Ins in LUNA


## In this article

- [Multi-Output Plug-Ins Overview](#h_01KDRGR9JY1TX43WS0W99QWPPA)
- [Understanding the Multi-Output Mixer](#h_01J6ZQTXY25PC0VMNDGKEQ3AXS)
- [Adding Multiple Output Channels from Within a Plug-In](#h_01J6ZQTXY2HZMFRKJ127Y1YJVC)
- [Adding Multiple Output Channels from the LUNA Mixer](#h_01J6ZQTXY2D9JPCKH2ERQGQENW)
- [Working with Multiple MIDI Channels in a Multi-Out Instrument](#h_01J6ZQTXY2TPP6NR4KJNZY7HCK)

# Multi-Output Plug-Ins Overview

Multi-output plug-in instruments include the ability to route audio output from additional channels beyond the plug-in's main output. LUNA's multi-output plug-in capabilities afford you expanded mixing and music production opportunities, and give you greater flexibility and control of the audio output from your plug-ins. LUNA's multi-output mixer is integrated directly within the plug-in interface and the LUNA timeline and mixer, and provides an extremely simple and intuitive multi-out workflow. 

**Important:** When you add multi-out channels to an ARM-enabled instrument track, that instrument track and all associated multi-out tracks are switched out of ARM mode. Therefore, any plug-ins on the instrument tracks or on the Main track must be either UAD-2 DSP plug-ins or completely bypassed (powered off) to prevent latency. 

------------------------------------------------------------------------

# Understanding the Multi-Output Mixer

LUNA allows you to configure multiple outputs with a multi-out plug-in directly in the plug-in's interface. You can also configure and work with multi-out channels in the LUNA mixer or timeline. 

You can add as many mixer channels as your creative needs require.

 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/a72eecc3ae59d9d8c81df24de99ea38d79ca4dcc.png)
</figure>

*Multi-output plug-in channels in a multi-output plug-in* 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/c8b4dedcdfef8dbc8640518e11aba32f66349b12.png)
</figure>

*Multi-output plug-in channels in the LUNA timeline*

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/0d99a481fb7b2170596c67d40e9400f7515c470c.png)
</figure>

*Multi-output plug-in channels in the LUNA mixer*

------------------------------------------------------------------------

# Adding Multiple Output Channels from Within a Plug-In

You can very simply add multiple channels from inside a multi-output plug-in.

1.  Add your multi-output plug-in on an instrument track. The plug-in window opens. 
2.  In the plug-in window, If MULTI-OUT MIXER is not highlighted, click it to open the multi-out mixer at the top of the plug-in window.
3.  Click the plus symbol (**+**) to the left of output 1-2 to add more channels.\
    \
     ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/023bc18990c862b74c2d2333c981b39a34c606fc.png)
4.   The Add Multi-Output floating window opens.\
    \
     ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/703e2bbd646bc951193a203fef805139945760f9.png)
5.  Select the format for the channels to add. Some plug-ins only allow stereo channels, and some include the ability to create both mono and stereo channels. If you are creating both mono and stereo channels, you must add them separately. 
6.  Specify the number of tracks to create.
7.  Type a name for the channel (for example, "drums" or "strings"). The names for each channel created are prepended with this name.
8.  Click More Settings to configure more settings for the multi-out channels you create.\
    ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/b7b3ea25eefb30cc7d339579cc58ea1edaffa445.png)
9.  If desired, select a multi-track tape machine and a Console to automatically add on each channel.
10. In More Settings, to choose which multi-out channel to create as the first track, select the channel from the Multi-Out list. 
11. In More Settings, to choose the MIDI output channel for created channels, choose a channel from the MIDI Out list. 
12. In More Settings, to cascade the MIDI outputs with the created channels, click Cascade MIDI Output. 
13. To add tracks, click ADD. To close the window without adding tracks, click DONE. 

New plug-in channels appear in the MULTI-OUT MIXER area, and separate tracks are created in LUNA for each multi-out channel.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/b3c30ecaf5e42feec48fe6a401365178e694822c.png)
</figure>

 

**Note:** <span style="color: #1d1c1d;">By default, your plug-in internally routes audio to the plug-in's main mono or stereo output. To route audio to the LUNA multi-out mixer, you must </span>[<span style="color: #1d1c1d;">assign audio to additional outputs within the plug-in</span>](#h_01J6ZQTXY2EAYV8NJYHJM7A2ZZ)<span style="color: #1d1c1d;">.</span>

------------------------------------------------------------------------

# Adding Multiple Output Channels from the LUNA Mixer

1.  Add your multi-output plug-in on a LUNA instrument track.
2.  In the LUNA mixer, right-click or Ctrl-click on the name of the channel with the multi-output plug-in.
3.  From the menu, choose Add Multi-Output.\
    \
    ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/c6540159582459e762477ab6b82e04eb86f78249.png)
4.  The Add Multi-Output floating window opens.\
    ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/703e2bbd646bc951193a203fef805139945760f9.png)\
     
5.  Select the format for the channels to add. Some plug-ins only allow stereo channels, and some include the ability to create both mono and stereo channels. If you are creating both mono and stereo channels, you must add them separately. 
6.  Specify the number of tracks to create.
7.  Type a name for the channel (for example, "drums" or "strings"). The names for each channel created are prepended with this name.
8.  Click More Settings to configure more settings for the multi-out channels you create.\
    ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/b7b3ea25eefb30cc7d339579cc58ea1edaffa445.png)
9.  If desired, select a multi-track tape machine and a Console to automatically add on each channel.
10. In More Settings, to choose which multi-out channel to create as the first track, select the channel from the Multi-Out list. 
11. In More Settings, to choose the MIDI output channel for created channels, choose a channel from the MIDI Out list. 
12. In More Settings, to cascade the MIDI outputs with the created channels, click Cascade MIDI Output. 
13. To add tracks, click ADD. To close the window without adding tracks, click DONE. 

New plug-in channels appear in the MULTI-OUT MIXER area within the instrument plug-in, and separate tracks are created in LUNA for each multi-out channel.

**Note:** <span style="color: #1d1c1d;">By default, your plug-in internally routes audio to the plug-in's main mono or stereo output. To route audio to the LUNA multi-out mixer, you must </span>[<span style="color: #1d1c1d;">assign audio to additional outputs within the plug-in</span>](#h_01J6ZQTXY2EAYV8NJYHJM7A2ZZ)<span style="color: #1d1c1d;">.</span>

## Assigning additional audio outputs within a plug-in

In general, multi-output plug-ins include a mixer or other method to assign audio to separate plug-in outputs. 

For example, in Toontrack's EZ Drummer, on the Mixer page, you click the output for a mixer channel and select an output pair. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/08d9acbe9ecce1640f413a506e065768b1de513d.png)
</figure>

Refer to your plug-in documentation for more information on how to assign channels to additional outputs within the plug-in. 

## Working with multi-output tracks

Multi-output tracks behave like standard instrument tracks. You can

- Rename, reorder, and color tracks in the Timeline or Mixer.

- Mix with all standard LUNA mixer features, including Solo, Mute, and plug-ins or LUNA Extensions.

- Record MIDI to one track at a time or across multiple tracks using a multi-timbral controller.

### Multi-output track differences

There are two main rules that distinguish multi-output tracks from standard tracks:

- **Deleting tracks:** If you delete the main multi-out instrument track, all associated multi-output tracks are deleted automatically.

- **Input monitoring:** You cannot enable Input Monitoring directly on a multi-output track. Instead, you must enable it on the **main** instrument track.

- **Manage tracks in the multi-output mixer:** You can manage the multi-output track layout directly within the multi-out mixer to quickly reorder or delete specific outputs.

## Multi-output track operations

- To rename a channel within a plug-in, double-click the channel name, or right-click / Control-click the channel name, then choose Rename. Type a new name and any comments, then press Return, or click the X to close the dialog.\
  ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/c24b158f88ad34c17ea9958b34a946b6335a11d5.png)
- To delete a channel, right-click or Control-click the channel name, then choose Delete.\
  \
  ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/b34aa33cf3275a6ed85499b15af92f0735d45918.png)
- To reorder within the plug-in view, click and drag a channel.\
  ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/b07ec7877ca3138b58811aa5ed80196abeccb8d0.png)

------------------------------------------------------------------------

# Working with Multiple MIDI Channels in a Multi-Out Instrument

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 15px;">In the multi-out mixer, you can independently assign the MIDI input and MIDI output for each channel of an instrument. This allows you to use a multi-timbral instrument like Native Instruments' Kontakt, for example, with a single plug-in instance, while sending independent MIDI to each loaded patch, and recording MIDI for each loaded patch to independent tracks. You can configure a MIDI Input and MIDI Output for each channel, </span>

- **MIDI IN:** The MIDI Input determines what MIDI input channel sends MIDI to the channel. You might assign different MIDI IN channels if, for example, you are recording multi-timbral parts with different MIDI controllers or a multi-timbral controller. If you are recording each MIDI track separately, you can assign the same MIDI input for each channel, or leave the default All setting. 
- **MIDI OUT:** The MIDI Output specifies the MIDI channel in the plug-in to which MIDI from the channel (track) is routed. You can use MIDI OUT to record MIDI on multiple channels (multiple LUNA tracks) of a multi-out plug-in, then route that MIDI to the correct part in the multi-out plug-in. This is useful with multi-out, multi-timbral plug-ins, like Kontakt or other samplers or synths. 

## To assign MIDI inputs and outputs in the multi-out mixer within a plug-in

1.  With the multi-out mixer displayed, display the MIDI options by clicking the icon below the plus symbol.\
    \
     ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/bcc4d49389679122a4765ba6988ddc5d347396d8.png)
2.  To select a MIDI input for a channel, click the MIDI IN button. In the MIDI IN browser, select the MIDI channel.
3.  To select a MIDI output for a channel,In the MIDI OUT browser, select the MIDI channel. Usually, this is listed under the name of the track (e.g. INSTRUMENT). You may have to scroll down to find the MIDI Output channels for the instrument. 

**Tip:** You can assign MIDI Output channels automatically when you create your multi-out channels. To do this, make sure CASCADE MIDI OUTPUT is highlighted when creating multiple output channels. 

## Multi-out mixer and multi-timbral plug-in example

In the following examples, we use the Kontakt instrument, but every multi-timbral instrument has its own configuration. Refer to your instrument's documentation for specific information.

1.  Add a Kontakt plug-in to an instrument track in LUNA. 
2.  In Kontakt, assign the patches you want to include in your multi-out instrument.\
    ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/72e7735aad3c1113d2d22898a4ebaaa3feb5fad7.png)\
     
3.  If Outputs are not shown, from the Kontakt Workspace Management menu, select Outputs.\
    ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/d79eced4b0dc1142040d94a0500597f964d639ee.png)\
     
4.  Next to Outputs, click Presets / Batch Configuration. From the menu, choose Batch functions, then choose Clear output section and create one individual channel for each loaded instrument.\
    \
     ![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/752230caa209f6f5e0074fdf3ba1a82a24f01a78.png)
5.  Kontakt assigns each loaded instrument patch to a separate output pair. 
6.  Follow the instructions in [Adding multiple output channels from within a plug-in](#h_01J6ZQTXY2HZMFRKJ127Y1YJVC) to add the instrument channels in LUNA. 

 

<figure class="wysiwyg-image">
![](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/74c24860b4d61415bf4a146769396523c287adbd.png)
</figure>

*Kontakt configured for multi-channel output*

 

![multi-out-kontakt-timeline.png](Using%20Multi-Output%20Plug-Ins%20in%20LUNA_assets/6a8e40355a8e45fee62f3361ec3bb4770d857285.png)

*Kontakt multi-channel tracks with MIDI in the LUNA timeline*

 

<span class="wysiwyg-font-size-small">*251230*</span>

