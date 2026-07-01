---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/38338846512276-Using-MIDI-Learn-in-UAD-Plug-Ins.html'
converted_at: 2026-05-31T13:44:57Z
tool: htmlq+pandoc
title: 'Using MIDI Learn in UAD Plug-Ins'
word_count: 1498
---

# Using MIDI Learn in UAD Plug-Ins


MIDI Learn lets you quickly map your MIDI controller's knobs, faders, and other continuous controllers (CCs) to controls within UAD plug-ins and UAD instruments.

Each plug-in or instrument instance has its own unique MIDI mappings. You can only assign one MIDI CC to one control within a single plug-in. If you reassign a CC, the previous mapping for that plug-in is automatically removed. However, you can use the same MIDI CC to control parameters across multiple plug-ins or instruments simultaneously.

**Note:** MIDI Learn is not available in LUNA. 

## Compatible MIDI controllers

Any general MIDI controller hardware that is compatible with your DAW can be used. You’ll first want to make sure your MIDI controller is sending MIDI to your plug-in. See [MIDI Learn Setup for DAWs](#h_01JXG4WRPVVQM0MHVJ01YNT6PW) for more information on specific setup in various DAWs.

 

------------------------------------------------------------------------

# MIDI Learn Quick Start

The basic process for mapping a plug-in or instrument control to a physical control (a MIDI CC) is described here.

The MIDI indicator illuminates when a controller is being moved, to confirm that the plug-in or instrument is receiving input from your MIDI controller and ready to learn.

![](Using%20MIDI%20Learn%20in%20UAD%20Plug-Ins_assets/16904106bd290b6819612f6b416b93da39d6508d.gif)

## Create a MIDI mapping

1.  In a UAD plug-in or UAD instrument, click **MIDI Learn** in the top bar. The message "Touch a control to begin" appears.\
    ![](Using%20MIDI%20Learn%20in%20UAD%20Plug-Ins_assets/1fd3cab2e194733aedd7b9fec0763dbe029747d0.png)
2.  Touch a plug-in control to map. In this example, the Feedback knob is touched.\
    ![](Using%20MIDI%20Learn%20in%20UAD%20Plug-Ins_assets/30c5c277b4960a6da45e6701904f2868e383ffca.png)
3.  Move a knob or slider on your controller. The MIDI controller is instantly mapped to the plug-in control. In this example, CC 36 is moved and now controls Feedback.\
    ![](Using%20MIDI%20Learn%20in%20UAD%20Plug-Ins_assets/3b34020247dc3ce0f153b55aaff478d008c76e36.png)

Repeat these steps to map additional controls. Each control is instantly mapped and saved with the plug-in.

## Default assignments

To save you time, UAD Instruments support a common general MIDI map by default. You can replace any default assignments with your own custom mappings using MIDI Learn. Clearing a custom MIDI mapping will reset the control to its default assignment.

**Tip:** Default mappings apply only to UAD Instruments. UAD plug-in effects do not have default assignments.

## Replace a MIDI mapping

You can easily replace a MIDI mapping. Simply click **MIDI Learn**, touch the control in the plug-in or instrument, and then move a different control on your controller. The new mapping automatically replaces the old mapping.

## Clear a MIDI mapping

You can clear a MIDI mapping by clicking the control, or by using the Options menu in the plug-in. From the Options menu, you can clear all mappings or a single mapping.

### Clear a MIDI mapping by clicking the control

To clear a MIDI mapping, simply click **MIDI Learn**, click the control that is mapped in the plug-in, then click the X to the left of the CC.

![](Using%20MIDI%20Learn%20in%20UAD%20Plug-Ins_assets/d417469b3a3a977a4021c33a40ff47699b21334c.png)

### View your custom MIDI mappings from the Options menu

![](Using%20MIDI%20Learn%20in%20UAD%20Plug-Ins_assets/468ffb7adfac6665862d3f0b22220900cb746663.png)

To clear MIDI mappings from the Options menu, click ••• in the plug-in toolbar.

- To clear a single MIDI mapping, select MIDI \> MIDI Mappings \> \[the MIDI Mapping\] \> Clear.
- To clear all MIDI mappings for the plug-in or instrument, select MIDI \> Clear all MIDI Mappings.

## Save and Load MIDI Mappings

You can save MIDI Mappings to a file that includes all current custom MIDI assignments for the plug-in or instrument. You can then load your custom MIDI assignments in other instances of the same plug-in or instrument. Use the menu to save mappings to load later.

**Note:** Your current MIDI Mappings are always automatically saved with the current plug-in or instrument instance in your DAW project or session.

#### *To save MIDI Mappings*

1.  Click ••• in the plug-in toolbar to open the Options menu.
2.  Choose MIDI \> Save MIDI Mappings and click Save.

Note that MIDI Mappings are automatically saved to the MIDI Mappings folder for the current plug-in or instrument.

#### *To load MIDI Mappings*

1.  Click ••• in the plug-in toolbar to open the Options menu.
2.  Choose MIDI \> Load MIDI Mappings.
3.  Choose the MIDI Mappings file to load, and click Open.

The MIDI Mappings are applied to the current plug-in or instrument.

### MIDI Mappings folder location

MIDI Mappings are saved to these folders by default.

**macOS:** Users/\[username\]/Documents/Universal Audio/Plug-Ins/MIDI Mappings/\[plug-in ID\]

**Windows:** \[drive\]:\Users\\username\]\Documents\Universal Audio\Plug-Ins\MIDI Mappings\\plug-in ID\]

------------------------------------------------------------------------

# MIDI Learn Setup for DAWs

Some DAWs require further configuration for MIDI Learn features.

## FL Studio

In FL Studio, you must set up your controller to transmit on a specific MIDI port. Enable your MIDI controller and set the MIDI Input port in Options \> MIDI Settings.\
Before you click MIDI Learn, set the MIDI input port in the plug-in or instrument that matches your controller's MIDI input port. To do this:

1.  Click the gear icon (Detailed Settings) in the top bar of the plug-in.
2.  Click the Plugin Options button
3.  Set the MIDI Input port.
4.  To return to the plug-in editor window, click the gear icon (Detailed Settings) again.

## Logic Pro Audio

In Logic Pro Audio, make sure that your MIDI controller is recognized as a MIDI input device. In Settings \> MIDI \> Inputs, select On for the device you want to enable.

MIDI Learn (for both UAD instruments and UAD plug-ins) is supported only on Software Instrument tracks in Logic Pro Audio.

## Ableton Live

In Ableton Live, make sure that your MIDI controller is enabled for track input. Open Settings \> Link, Tempo, & MIDI. In the Input Ports section enable your device for Track input.

### Instrument tracks

Before you click MIDI Learn in your UAD instrument:

1.  Instantiate a UAD instrument on an instrument track.
2.  On the track's MIDI From, select the device you wish to use, or use All Ins.
3.  Arm the track.

### Audio tracks (with VST3 plug-ins)

Before you click MIDI Learn in the plug-in:

1.  Create a MIDI Track.
2.  From the track's MIDI From menu, select the device you wish to use (or All Ins).
3.  Instantiate a UAD plug-in on an audio track or FX Send.
4.  From the MIDI track's MIDI To menu, select the plug-in you wish to control.
5.  Arm the MIDI track.

**Note:** Not all AU effects allow MIDI input in Ableton Live, for full MIDI Learn support, use VST3 UAD audio plug-ins in Ableton Live.

## Cubase

In Cubase, make sure that MIDI in for your MIDI controller is enabled. Go to Studio \> Studio Setup, select MIDI Port Setup, and make sure that MIDI In is enabled for your controller.

### Instrument tracks

Before you click MIDI Learn in the plug-in, make sure that the Instrument track is set to accept MIDI from the controller you are using, or from All MIDI Inputs.

### Audio tracks

Before you click MIDI Learn in the plug-in:

1.  Instantiate a UAD plug-in on an audio track or FX track.
2.  Create a MIDI track.
3.  From the MIDI Outputs menu, select the plug-in you want to control.
4.  Set the MIDI input to your device, or All MIDI Inputs.

## Pro Tools

In Pro Tools, make sure your MIDI Controller is set up. In Setup \> MIDI \> MIDI Input Enable, select the controller you wish to use.

### Instrument tracks

If your UAD instrument is not receiving MIDI from your controller, select View \> Edit Window Views and enable the Instruments view. Make sure the MIDI routing is mapped to the track’s instrument appropriately. MIDI routing should be assigned by default when you instantiate the Instrument, but this routing may change if the track’s instrument is changed or reassigned.

### Audio tracks

Before you click MIDI Learn:

1.  Create a MIDI track and an audio track.
2.  Add the UAD plug-in to the audio track.
3.  In Mix view, go to the MIDI track's I/O, and from the Output drop menu, select the audio track that includes your plug-in.
4.  Select the plug-in name, and assign it to MIDI channel 1.
5.  Record-arm the MIDI track.

## Studio One

Make sure your controller is recognized. When Studio One starts, MIDI devices are scanned automatically. You can add a device after startup in Preferences \> External Devices.

### Instrument tracks

Before you click MIDI Learn in your UAD instrument:

1.  Instantiate a UAD instrument on an Instrument track.
2.  From the track's Input menu, select the device you wish to use, or use All Inputs.
3.  Arm the track.

### Audio tracks (with VST3 plug-ins)

Before you click MIDI Learn in the plug-in:

1.  Create an Instrument Track.
2.  From the track's Input menu, select the device you wish to use (or All Ins).
3.  Instantiate a UAD plug-in on an audio track or FX Send.
4.  From the Instrument track's Output menu, select the plug-in you wish to control.
5.  Arm the Instrument track.

**Note:** Not all Audio Units effects allow MIDI input in Studio One, for full MIDI Learn support, use VST3 UAD plug-ins.

v20250825

