---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/5085501350932-Using-UAD-Plug-Ins-Manual.html'
converted_at: 2026-05-31T13:45:01Z
tool: htmlq+pandoc
title: 'Using UAD Plug-Ins Manual'
word_count: 3023
---

# Using UAD Plug-Ins Manual


## In this article

- [About UAD Plug-Ins](#h_01FZ1PDHMQEANPXRV7HEXJ9QDH)
- [UAD Plug-In System Requirements](#h_01FZ1PDQSQWT1A5NDEAFEKW2ZT)
- [Instantiating UAD Plug-Ins](#h_01FZ1PEF5P69J8Y4RA852HKB5Z)
- [UAD Toolbar](#h_01HGGZQM7BFXBWTJXHSC5JB5XX)
- [Using UAD Plug-In Presets](#h_01GRYZV42VRAQVHMQE9CCMBPMY)
- [UAD Plug-In and Preset Install Locations](#h_01FZ1PEY7Z1ZVAT7HQY0WFVW9E)

------------------------------------------------------------------------

# About UAD Plug-Ins

UAD plug-ins run on your computer’s processor (UADx native) or on your Apollo DSP (UAD-2 DSP).

DSP and native plug-ins sound the same, and offer the ability to copy and paste settings between the versions. In addition, with LUNA v1.4 and higher, switching between native and DSP plug-in versions can be done automatically.

## Native (UADx) plug-ins

- No UA hardware is required.
- Native UAD plug-in licenses can be purchased on their own as perpetual licenses.
- Native UAD plug-ins may be included or offered at a reduced cost for corresponding UAD-2 or LUNA plug-ins you own.
- Native UAD plug-ins can also be purchased on subscription with UAD Spark [here](https://spark.uaudio.com).
- To learn how to install and activate native UAD plug-ins, see <a href="5085235532052-UA-Connect-with-Native-UAD-Plug-Ins.html" target="_self">UA Connect with Native UAD Plug-Ins</a>.

### NKS Compatibility

<table style="border-collapse: collapse; width: 100%;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; width: 130px; vertical-align: middle;">![NKS-logo-black.png](Using%20UAD%20Plug-Ins%20Manual_assets/bc3d1f07dfec34c44528c3edae60214c01b881dc.png)</td>
<td style="text-align: left; vertical-align: top;"><p>All native UAD plug-ins and instruments are NKS-compatible, for deep integration with Native Instruments KOMPLETE KONTROL and MASCHINE series hardware and software. Presets and sound previews appear in NI’s powerful tag-based browsers, and all parameters are intelligently pre-mapped across the control knobs on supported NKS hardware.</p>
<p>For more details, see <a href="41807112025364-FAQ-How-to-Use-UAD-Native-Plug-Ins-with-NKS-Compatible-Controllers.html">this article</a>.</p></td>
</tr>
</tbody>
</table>

## DSP (UAD-2) plug-ins

- Apollo or UAD-2 accelerator hardware is required.
- UAD-2 plug-in licenses can be purchased on their own as perpetual licenses.
- Existing DSP plug-in licenses may entitle you to free or reduced-cost native licenses of the corresponding native plug-ins.

## MIDI Learn

UAD plug-in parameters are available for external MIDI control by default. You can override these default assignments with [MIDI Learn](38338846512276-Using-MIDI-Learn-in-UAD-Plug-Ins.html).

------------------------------------------------------------------------

# UAD Plug-In System Requirements

- [Native (UADx) plug-in system requirements](5172379808276-UAD-Native-Plug-ins-UADx-and-UAD-Spark-System-Requirements.html)
- [Native (UADx) plug-in DAW compatibility](5172457309716-DAW-Compatibility-with-UAD-Native-Plug-Ins-UADx.html)
- [DSP (UAD-2) plug-in system requirements](26451589148564-Universal-Audio-System-Requirements.html)
- [DSP (UAD-2) plug-in DAW compatibility](360050583152-DAW-Compatibility-with-UAD-DSP-Plug-Ins.html)

 

------------------------------------------------------------------------

# Instantiating UAD Plug-Ins

Follow the procedures in your DAW’s documentation to load plug-ins.

Native plug-ins are located in a folder called **Universal Audio (UADx)** or **UADx,** and DSP plug-ins are located in a folder called **Universal Audio**, though your DAW may not sort plug-ins by folders. In UAD Console, you can only insert DSP (UAD-2) plug-ins.

## Using UAD plug-ins in your DAW

UAD plug-ins can be instantiated as mono, stereo, or multi-mono inserts.

- An effect plug-in processes audio and is inserted in an effects slot on a track or bus in your DAW.\
  ![uadx-la-2.png](Using%20UAD%20Plug-Ins%20Manual_assets/70eb165c152c713aa2ec4eb3aca9e4286e2dfb0c.png)\
   
- A virtual instrument (native-only) generates sound from MIDI input, and is inserted on an instrument or MIDI track in your DAW.\
  ![uadx-waterfall.png](Using%20UAD%20Plug-Ins%20Manual_assets/2ae9a12e9ccc1d10ef52d95ed6c056cce1fc636c.png)\
   
- A Unison plug-in is a special type of UAD-2 plug-in that is instantiated in the Unison insert slot in UAD Console or LUNA only.
- In addition, UAD Console and LUNA support Record FX inserts, which record the output of the UAD effect to a track when recording. Only DSP (UAD-2) plug-ins can be inserted in Record FX slots. 

 

------------------------------------------------------------------------

# UAD Toolbar

The UAD Toolbar is located at the top of every UAD plug-in window. This toolbar contains convenient features that you can use with every UAD plug-in. The toolbar includes different controls for native and DSP plug-ins. 

 

![uadx-plug-in-header-bar.png](Using%20UAD%20Plug-Ins%20Manual_assets/2006ed8e49fc8e6e1c29e153339b558333fc3860.png)

*Native (UADx) plug-in toolbar elements*

 

 

![plug-in-toolbar-callouts.png](Using%20UAD%20Plug-Ins%20Manual_assets/9945f3151cebad3079cc009e3846b551c66bb228.png)

*DSP (UAD-2) plug-in toolbar elements*

 

## Previous / next preset

Use the **\< \>** buttons to quickly select the previous or next preset in the Preset Browser without opening the browser window.

## Preset title

The active preset title is displayed here. Click this area to open the Preset Browser. If the preset settings have been modified, the title is displayed in *italics*.

## IN / bypass (native UADx plug-Ins)

Use the IN button to compare plug-in processing with the original sound. To enable or disable audio processing, click IN above the plug-in’s controls. When IN is highlighted, the plug-in is enabled and processing audio. When IN is not highlighted, the plug-in is bypassed.

IN is a soft bypass, equivalent to toggling the power button in the plug-in. This allows you to bypass and re-enable the plug-in in the most glitch-free way possible.

**Note:** In/bypass is not available with Opal Morphing Synthesizer, Ravel Grand Piano, or Waterfall B3 Organ.

## Power / bypass (DSP UAD-2 plug-ins)

Use the power button to compare plug-in processing with the original sound. To enable or disable audio processing, click the button above the plug-in’s controls. When power is highlighted, the plug-in is enabled and processing audio. When not highlighted, the plug-in is bypassed.

Power is a soft bypass, equivalent to toggling the power button in the plug-in. This method keeps the plug-in loaded on DSP to prevent audio interruptions when toggling. When the plug-in is bypassed with the DAW’s bypass control, the plug-in is unloaded from DSP which can cause playback glitches.

## A/B Compare (native UADx plug-ins)

Use the A and B buttons to compare two sounds. For example, you can compare two different presets, or an edited version of a sound with its original.

To copy sounds from one slot to the other, click the ••• options menu and choose Copy A To B (when A is active) or Copy B To A (when B is active).

### Notes

- The A and B settings are stored in the plug-in instance, not in preset files.
- A/B compare is not available in LUNA.

## Copy / paste settings

Use Copy and Paste to copy settings from the plug-in and paste them to a different instance of the same plug-in. You can use this to copy and paste settings between instances of the same plug-in in a session, or to copy and paste settings between the UAD-2 and native (UADx) versions of a plug-in.

**Note:** For plug-ins with narrow header bars (for example, Lexicon 224), the Copy and Paste functions are located in the Options menu.

## Options menu

![options-menu.png](Using%20UAD%20Plug-Ins%20Manual_assets/cd91b9e9ace0f6ddcb1171c35b96db938083a83c.png)

## Resizing UAD plug-ins

You can resize plug-ins to see the plug-in controls larger or smaller on your screen. When you resize a plug-in in your DAW, the plug-in window, toolbar, preset browser, and help windows are all resized). In UAD Console, only the plug-in controls are resized.

The menu command Apply to All allows you to immediately apply the current plug-in's resize level to all plug-in titles.

**Note:** Some DAWs limit the maximum window size for plug-ins at certain screen resolutions. If your DAW does not support a selected plug-in size, the previously selected size remains selected.

### Resizing behavior

- **Native UAD plug-ins and instruments –** Plug-ins and instruments are resized system-wide, per plug-in. When you resize a plug-in, that resize level is shared immediately between all instances of that plug-in, and all plug-in formats, in all DAWs on your system. The resize setting is shared between AAX, VST3, and Audio Units formats.
- **DSP (UAD-2) plug-ins –** Plug-ins are resized per plug-in within the DAW or UAD Console (not system-wide). 

#### Resize a UAD plug-in

1.  Click the ••• in the toolbar above the plug-in’s controls.
2.  Choose a resize level, from 75–200%.

The UAD plug-in is resized system-wide (UADx) or in your DAW or UAD Console (UAD-2).

#### Resize all plug-ins

1.  Click the ••• in the toolbar above the plug-in’s controls.
2.  Choose a resize level, from 75–200%.
3.  From the same menu, choose Apply to All.

All UAD plug-ins are resized system-wide (UADx) or in your DAW or UAD Console (UAD-2).

#### Reset all UAD plug-ins to the default size

1.  Click the ••• in the toolbar above the plug-in’s controls.
2.  Choose the 100% option.
3.  From the same menu, choose Apply to All.

All UAD plug-ins are resized system-wide (UADx) or in your DAW or UAD Console (UAD-2).

## Submitting feedback

To submit feedback about a UAD plug-in, click the ••• options menu in the toolbar above the plug-in’s controls, then select Submit Feedback. You can submit feature requests, bugs, or general feedback. You can include any relevant details in the feedback submission form, and automatically include your current log files and system information files. You can also attach files (for example, a screenshot).

**Note:** Thanks for your feedback. We are unable to reply to the feedback submission form directly, but all submissions are reviewed. To contact UA Customer Care for support, please [go here](../p/contact.html).

## View the documentation

Click the **•••** in the toolbar above the plug-in’s controls, then select Help & Video, to access documentation and tips for the plug-in. You can then choose to open the online documentation page or a short video. The video gives quick tips on the operation of the plug-in, and the documentation page details the operation and controls of the plug-in.

![uadx-plug-in-more-menu.png](Using%20UAD%20Plug-Ins%20Manual_assets/870a5c565f02282ed750c0860e41ea563d5bbaa4.png)

## UAD plug-in shortcuts

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 34%" />
</colgroup>
<tbody>
<tr>
<td style="width: 33%">Keyboard/mouse action</td>
<td style="width: 20%">Result</td>
<td style="width: 47%">Notes</td>
</tr>
<tr>
<td style="width: 33%"><p>Option+Click (macOS)</p>
<p>Control+Click (Windows)</p></td>
<td style="width: 20%">Return to control default</td>
<td style="width: 47%"><p>Note that this doesn't return the control to the setting for a preset, but to the default setting for the plug-in.</p>
<p>With Studer A800 Tape Recorder, changing the Tape Type causes the plug-in defaults for Secondary Controls to change.</p></td>
</tr>
<tr>
<td style="width: 33%">Shift + Drag</td>
<td style="width: 20%">Fine control</td>
<td style="width: 47%"> </td>
</tr>
<tr>
<td style="width: 33%">Hover + Mousewheel</td>
<td style="width: 20%">Adjust control</td>
<td style="width: 47%"> </td>
</tr>
</tbody>
</table>

 

------------------------------------------------------------------------

# Using UAD Plug-In Presets

UAD plug-ins include a preset browser that provides deep and comprehensive ways to work with presets.

Click the preset name (for example, Default) in the UAD Toolbar to open the preset browser. When the preset browser is open, the search bar takes keyboard focus so you can find presets and tags. With virtual instruments, some DAW keyboard controls and commands still function when the preset browser is open.

To close the preset browser, press the Esc key.

![presets-list-callouts.png](Using%20UAD%20Plug-Ins%20Manual_assets/ed131ecb5d486301b6145467a6350def076a8469.png)

## Using a preset

Click a preset to load it.

## Navigating presets

Press the up and down arrow keys to navigate through, and load, presets.

## Searching for a preset

To search for a preset by name or tag, type in the search bar. The list of presets is filtered as you type. Press Enter to use the first preset in the list, or navigate up/down with the arrow keys, then press Enter.

![type-to-filter.png](Using%20UAD%20Plug-Ins%20Manual_assets/83abfa14fde68b13b84f02c1782dc61e2bde5d80.png)

## Using Tags to find a preset by characteristics

The Tags feature allows you to find presets based on descriptive terms, genres, and other categories.

**Note:** Tags are unavailable in UAD Console. 

- To show the list of tags, click TAGS.
- To close the list of tags, click TAGS again.
- To filter the list of presets by a tag, click the tag. Click one or more tags to narrow the list of plug-in presets. Each tag you add narrows the list of results further, and also reduces the list of tags.
- To remove a tag, click one of the selected tags.
- To stop filtering by tags, click the X next to TAGS.

**Note:** You cannot add new tags, or add existing tags to plug-in presets.

![presets-filter-by-tags.png](Using%20UAD%20Plug-Ins%20Manual_assets/93aede5616a5e46971847cd20fc7bd2b14039740.png)

### Tag categories

UAD plug-ins include preset tag categories. Categories run across the top of the tags list, and allow you to view a subset of tags.

As an example, Opal Morphing Synthesizer includes the tag categories Genre, Type, and Description, as well as a category for all tags.

![tag-categories.png](Using%20UAD%20Plug-Ins%20Manual_assets/d19e3f589dfce05d81567c5b2e76a09674f442a0.png)

Click a category to see tags for that category. Click All to see all tags.

You can sort tag categories by category name, or by the number of presets in the category, from most to least, and you can show the number of presets in each tag category.

#### To sort tag categories:

1.  Right-click or control-click on TAGS.
2.  Under Sort Tags By, choose Name or Number of Presets.
3.  To show the number of presets in each tag category, under Show, select Number of Presets. Deselect Number of presets to stop showing the number of presets in each category.

![sort-show-tags.png](Using%20UAD%20Plug-Ins%20Manual_assets/5b59b3c6a6d746f6f8f8e15ea7c7299a7b721dff.png)

## Setting a default preset

You can set a default preset that will load automatically when you instantiate a UAD plug-in.

![set-default-preset.png](Using%20UAD%20Plug-Ins%20Manual_assets/ae2c65997055dfea5625a84eaf91e765388dbad7.png)

- To set a default preset, right-click the preset name and choose Set as Default Preset. The current default preset includes \[DEFAULT\] after the preset name.
- To clear the default preset, right-click the preset name and choose Clear Default Preset.

**Tip:** Refer to <a href="360041465732-Mixing-in-LUNA.html" target="_self">LUNA documentation</a> to set a default preset in LUNA.

## Favoriting presets

You can favorite presets, and filter the list of presets by your favorites.

![preset-favorites.png](Using%20UAD%20Plug-Ins%20Manual_assets/6c5f055ad0d672bae1ffffb26d5030bc9dbeffef.png)

- To favorite a preset, hover over the preset name, and click the star to the right of the preset name, or right-click the preset name and choose Favorite.
- To unfavorite a preset, hover over the preset name, and click the favorite star again, or right-click the preset name and choose Unfavorite.
- To show only favorites in your preset list, click Favorites in the Tags bar.

![favorites-list.png](Using%20UAD%20Plug-Ins%20Manual_assets/a126433a69e9f0beebe42caf42aa844829372f49.png)

## Working with user presets

You cannot edit, delete, or move factory presets. However, you can edit a factory preset and save it as a user preset. You can organize user presets into folders, import user presets, and locate and share user presets from your system. Preset files can be shared between macOS and Windows operating systems. When you load a preset into the system, it is automatically added to the user preset list in the plug-in preset manager.

**Note:** macOS allows some characters in file names that are not allowed in Windows. To create preset names that can be shared across platforms, avoid using the following characters: **/ : \* ? " \< \> \|**

## Editing presets

You can edit a preset you have loaded in a UAD plug-in, and save that preset with the Preset browser.

You can also delete and rename presets that you have created. If you save changes to a factory preset, the preset is saved as a user preset with the same name. Factory presets cannot be edited.

#### To save a UAD plug-in preset:

1.  Select a preset.
2.  Make changes to the plug-in as required. The preset name changes to italic text to indicate that it has been edited. **Note:** Reopen the preset browser if it closes after adjusting settings in the plug-in window.
3.  Click Save. The Save dialog opens.\
    ![preset-save-dialog.png](Using%20UAD%20Plug-Ins%20Manual_assets/69bd9a2731eee01ca9481020897933c196a5325e.png)\
     
4.  Click Save to save the changes to the existing preset, or type a name for the preset to save with a new name, then click Save.

If you save a preset that is based on a factory preset, the preset is saved in the User Presets list. You cannot overwrite factory presets.

#### To rename a preset:

1.  Select a preset from the User Presets list, and click Rename, or right-click on the user preset and choose Rename. The rename dialog opens.\
    ![preset-rename.png](Using%20UAD%20Plug-Ins%20Manual_assets/e1596dce904070098f2affbe8a294130024a05ac.png)\
     
2.  Type a new name for the preset and click Rename.

The preset is renamed. Factory presets cannot be renamed.

#### To delete a preset:

1.  Select a preset from the User Presets list, and click Delete, or right-click on the user preset and choose Delete.
2.  The Delete dialog appears. Click Delete again.\
    ![preset-delete.png](Using%20UAD%20Plug-Ins%20Manual_assets/0ddd3b40cd1c9b82040fa1c6aa602b88f2f6f1be.png)

The preset is deleted from the User Presets list. Factory presets cannot be deleted.

## Sharing user presets between systems

UAD plug-ins make it easy to find and share user presets. You can locate a user preset on the file system, and easily import a preset from another system or another user into your plug-in presets. You can use this feature to share presets with another user or between machines. To share presets between native and DSP plug-ins, use Copy and Paste in the plug-in editor windows.

**Note:** Locating and importing user presets is currently not supported in LUNA.

#### To locate a user preset:

- Right-click on the user preset and choose "Show in Finder" (Mac) or "Show in Explorer" (Windows). A window opens with the preset selected. UAD plug-in presets can be freely shared between macOS and Windows systems.

#### To import (load) a preset:

1.  Click the **•••** in the toolbar above the plug-in’s controls, then select Load a Preset...
2.  Select the preset on your file system, and click Open.

The preset is imported and opened in the plug-in, and automatically stored in the user presets location on your system.

**Note:** You cannot import presets in UAD Console or LUNA. 

## Organizing user presets

You can organize user presets into folders.

**Note:** You must have created one or more user presets to create a preset folder.

![presets-new-folder.png](Using%20UAD%20Plug-Ins%20Manual_assets/0d56ed87c04fe064312ff62c5b3a6102a50ac634.png)

#### To create a user preset folder:

1.  Right-click on a user preset or on the user presets folder, and choose New Folder.
2.  Type a name for the folder, and click New Folder.

You can save presets from within folders, or organize the presets into the folders on your computer operating system's file system, and they will appear with the folder organization within the plug-in.

**Note:** Creating preset folders is currently not supported in LUNA.

 

 

------------------------------------------------------------------------

# UAD Plug-In and Preset Install Locations

## UAD-2 DSP plug-ins

When UAD software is installed, UAD-2 plug-ins are copied to the following default locations:

### Windows

VST3 (64-bit)\
C:\Program Files\Common Files\VST3

VST2 (64bit)\
C:\Program Files\Steinberg\VstPlugins\Universal Audio\\

AAX64\
C:\Program Files\Common Files\Avid\Audio\Plug-Ins\\

## macOS

VST3\
Macintosh HD/Library/Audio/Plug-ins/VST3

VST2\
Macintosh HD/Library/Audio/Plug-Ins/VST/Universal Audio

Audio Units\
Macintosh HD/Library/Audio/Plug-Ins/Components

AAX64\
Macintosh HD/Library/Application Support/Avid/Audio/Plug-Ins

## UAD-2 DSP plug-in presets

### macOS

Macintosh HD/Library/Application Support/Universal Audio/Presets/\[plugin name\]

### Windows

C:\Program Files (x86)\Universal Audio\Powered Plugins\Presets\\plugin name\]

## UADx native plug-ins

### macOS

VST3\
Macintosh HD/Library/Audio/Plug-ins/VST3

Audio Units\
Macintosh HD/Library/Audio/Plug-Ins/Components

AAX 64\
Macintosh HD/Library/Application Support/Avid/Audio/Plug-Ins

### Windows

VST3 (64-bit)\
C:\Program Files\Common Files\VST3

AAX64\
C:\Program Files\Common Files\Avid\Audio\Plug-Ins\\

## UADx native plug-in presets

### macOS

/Users/\[username\]/Documents/Universal Audio/Presets/Plug-Ins

### Windows

**Factory Presets –** C:\Program Files\Common Files\Universal Audio\Plug-Ins\\plug-in name\].lunacomponent\algo.bundle\Contents\Resources\presets

**User Presets –** C:\users\\username\]\Documents\Universal Audio\Presets\Plug-Ins

 

