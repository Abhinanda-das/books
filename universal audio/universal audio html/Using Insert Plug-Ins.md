---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/34498519722132-Using-Insert-Plug-Ins.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'Using Insert Plug-Ins'
word_count: 3101
---

# Using Insert Plug-Ins


<div layout="align-start" node-type="mediaSingle" data-width="50">

## In this article

- [Plug-Ins Overview](#h_01KDRCZRRFA86RF2B93BN9GSWB)
- [Managing Plug-Ins](#h_01JK6SPMPAEQCVYC7SD28NK08R)
- [Adding plug-Ins](#01JK6SG39JJMPRYCZJ5HNG3CBN)
- [Bypassing Plug-Ins](#h_01HER0R6KKBDVAR8YC5ZJGJ6E9)
- [Filtering Plug-Ins by Categories](#h_01HER0R6KKXABPY1DMWR97951M)
- [Searching for Plug-Ins](#h_01HER0R6KKMDR0CMS4S2FXVQNQ)
- [Hiding, Showing, and Closing Plug-In Windows](#h_01HER0R6KKHTDHK6Z7FT7DPZVC)
- [Using Plug-In Presets](#h_01HER0R6KK68EJFBE1CBKDH1E2)
- [Showing Large Plug-In Icons](#h_01HER0R6KKKK56CEH0CT2RD1SD)
- [Adding an Icon for a Plug-In](#h_01HER0R6KKFYT4CXEH8SBZ8XER)
- [Resizing UAD Plug-Ins](#h_01HA56KJQWFYBE84BMMGC2JV2N)
- [Converting Between Native and DSP Plug-Ins](#h_01H3FEJ44GEF7XST034XP81FDV)

------------------------------------------------------------------------

<div class="wysiwyg-text-align-center" collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="mixer-track-insert-plugins.png" file-size="21163" data-height="114" data-id="bb343b34-0a87-48f7-9bd1-fa2de557bf7b" node-type="media" data-type="file" data-width="239" title="Attachment">

 

</div>

</div>

# Plug-Ins Overview

You use inserts to add UAD DSP (UAD -2), UAD Native (UADx), Audio Unit (AU), and VST3 plug-in processing to audio, bus, instrument, and main tracks. Click an available insert to open the list of available plug-ins in the browser, and click a plug-in from the panel to insert it.

## Insert types

- **Standard inserts:** Standard inserts appear in the input row. processing from standard insert plug-ins is not recorded to disk. You can expand the Inserts row to view the standard inserts. 

<figure class="wysiwyg-image">
![mixer-track-insert-plugins.png](Using%20Insert%20Plug-Ins_assets/231f33906890bb4e55b261a5ca9a490c5db85cbb.png)
</figure>

- **Unison insert & Record FX inserts:** When LUNA is in Apollo mode, the unison insert and Record FX inserts appear in the Input row, when a track is Input or Record enabled.  Note that only UAD DSP plug-ins can be used in Record FX inserts. Only Unison-capable UAD DSP plug-ins can be used in Unison inserts.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 33%;">
![unison-record-fx-inserts.png](Using%20Insert%20Plug-Ins_assets/2a42023cb0c47d35e456bc083a265ccce06b79f4.png)
</figure>

## Plug-in states

Plug-in states are indicated with colors and outlines.

- A gray plug-in plate indicates a powered-on and authorized plug-in.
- A red plug-in plate indicates that a plug-in is not authorized.
- A dimmed plug-in plate indicates that a plug-in is soft-bypassed with the IN button.
- A further dimmed plug-in plate with italicized text indicates that the plug-in is disabled with the Power button.
- A blue plug-in plate indicates that the plug-in is focused in the browser.
- A yellow outline around a plug-in plate indicates that the plug-in window is open in LUNA. 

![plug-in-states.png](Using%20Insert%20Plug-Ins_assets/d3c4169dc95da3c4dec35ecf04369cdbd136e6a2.png)

------------------------------------------------------------------------

# Managing Plug-Ins

You manage your plug-ins in LUNA's settings. To see the plug-in manager, click the three dots at the top left of the LUNA window to open the LUNA sidebar, and click Manage Plug-Ins, or choose Settings from the LUNA menus, and click the Plug-Ins tab. 

![user-panel-annotated.png](Using%20Insert%20Plug-Ins_assets/64a0f3c26347190f99e34d41ae798e52cd27dc54.png)

The Plug-In Manager allows you to enable or disable plug-in formats, and manage all of your Audio Units (macOS) and VST3 (macOS and Windows) plug-ins. 

![plug-in-manager-callouts-2x.png](Using%20Insert%20Plug-Ins_assets/66b62796963ed3d2aec10b4733d763664f895f8e.png)

## Enable plug-ins

VST3 plug-ins are not automatically enabled on macOS. VST3 plug-ins are enabled on Windows systems. You can enable or disable a plug-in format. 

### Windows and macOS plug-in formats

On Windows, VST3 plug-ins are enabled by default. On macOS, Audio Units plug-ins are enabled by default. To transfer LUNA sessions seamlessly between macOS and Windows systems, enable VST3 plug-ins in LUNA on macOS, and use those plug-ins in your sessions. 

Toggle the Enable switch for a plug-in format to enable or disable that plug-in format. Plug-in formats are enabled when they are highlighted.

**Tip:** To prevent plug-in format issues when transferring between platforms, you can deactivate Audio Units plug-ins on macOS. 

## Find plug-ins

The Plug-In Manager includes a search bar that you can use to find plug-ins. Click in the search area and type your text to search. The Plug-In Manager finds plug-in by plug-in Format, Name, and Manufacturer only. 

## Plug-in information columns

The Plug-In Manager lists information about each plug-in in columns. You can sort the list of plug-ins by clicking on any column name. 

![plug-in-manager-columns-2x.png](Using%20Insert%20Plug-Ins_assets/a80c8d77791acac5710bbadac65f5b8599c26fe5.png)

Plug-in information includes:

- **Format:** Whether the plug-in is AU (Audio Units) or VST3 format.
- **Manufacturer:** The manufacturer name for the plug-in.
- **Name:** The plug-in name.
- **Category:** whether the plug-in is an instrument, or the type of effect. Some plug-ins have multiple categories, and some may have no category. You can right-click on the Category to add or remove categories from a plug-in. 
- **Version:** The installed version of the plug-in.
- **Status:** whether the plug-in is new (not scanned yet), scanned (usable), or rejected (not usable by LUNA for some reason).
- **Ignore:** Select Ignore to ignore a plug-in. This removes it from the LUNA plug-in browser. 

## Scan plug-ins

When you first enable a plug-in format, or you first launch LUNA, VST3 and Audio Units plug-ins are not scanned and will not appear in LUNA. You must manually scan new plug-ins or rescan all plug-ins to enable the plug-ins. You can also manually scan or rescan a single plug-in. 

### Scan all plug-ins

In the Plug-In Manager, click the Rescan All button in the Scan area. If you want to scan all plug-ins. you must click this button the first time you enable a plug-in format, or if you have never scanned for plug-ins of the format enabled in LUNA. 

If a LUNA session is open, you will be prompted to close that session. 

### Scan new and updated plug-ins

In the Plug-In Manager, click the New Plug-Ins button in the Scan area. This will rescan all plug-ins that have been updated since the last scan, and scan any newly installed plug-ins since the last scan.

### Scan or rescan a single plug-in

If you want to scan or rescan a single plug-in, in the far right column of the Plug-In Manager, click Scan or Rescan.

### Add an alternate plug-in location

If you have installed VST3 plug-ins in an alternate folder on your system, you can click the button under Scan Alternate Location, and then click in the location area to choose a folder from the Finder or File Explorer.

## Ignore a plug-in

To prevent a plug-in from appearing in LUNA, toggle the switch in the Ignore column for the plug-in. The plug-in is ignored when the switch is illuminated. 

## Manage UAD plug-ins (in UA Connect)

To manage your native UAD plug-ins in UA Connect, click the Open UA Connect button. See [UA Connect with Native UAD Plug-Ins](5085235532052-UA-Connect-with-Native-UAD-Plug-Ins.html) for more information. 

## Shop for plug-ins

To shop for UAD plug-ins, click the Plug-In Store button. 

------------------------------------------------------------------------

# Adding Plug-Ins

Click on a Unison insert, Record FX insert, or standard Insert insert to add a plug-in. Note that you can only add a Unison-enabled UAD DSP plug-in in the Unison insert, and UAD DSP plug-ins in the Record FX inserts, and those inserts are only active when a track is record-enabled or input-enabled.

When you click on an insert, your list of supported plug-ins opens in the Plug-Ins browser. The list of plug-ins in the browser changes depending on the context. As an example, only Unison plug-ins appear when you click a Unison insert. On audio tracks, only UAD DSP plug-ins appear in the Record FX insert. When LUNA is ARM-enabled in Apollo mode, any plug-in type can be added to a record-armed or input-enabled track, but non UAD DSP plug-ins are bypassed while the track is armed.

Plug-ins are organized by manufacturer, and you can click a manufacturer’s name to show or hide the list of plug-ins. In addition, UAD plug-ins are sorted into four folders:

- **UADx** includes your installed UADx plug-ins that are licensed either through a UAD Spark subscription or demo, or licensed perpetually, because you own a license for the UAD DSP version.

- **Universal Audio** includes your UAD DSP plug-ins, including plug-ins that are licensed and plug-ins that still have available demos.

- **Universal Audio Sphere** includes your native Sphere plug-ins.

- **Universal Audio \[inactive\]** includes plug-ins that are not licensed and no longer have an available demo.

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div class="wysiwyg-text-align-center" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="uad-folders-plug-in-browser.png" file-size="85611" data-height="500" data-id="29515b10-ba09-473d-94ec-0aa248fe77ce" node-type="media" data-type="file" data-width="506" title="Attachment">

![uad-folders-plug-in-browser.png](Using%20Insert%20Plug-Ins_assets/dad556706073e8bf1abb74625d5852d6aeda443e.png)

</div>

<div class="wysiwyg-text-align-left" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="uad-folders-plug-in-browser.png" file-size="85611" data-height="500" data-id="29515b10-ba09-473d-94ec-0aa248fe77ce" node-type="media" data-type="file" data-width="506" title="Attachment">

</div>

<div collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="uad-folders-plug-in-browser.png" file-size="85611" data-height="500" data-id="29515b10-ba09-473d-94ec-0aa248fe77ce" node-type="media" data-type="file" data-width="506" title="Attachment">

</div>

<div collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="uad-folders-plug-in-browser.png" file-size="85611" data-height="500" data-id="29515b10-ba09-473d-94ec-0aa248fe77ce" node-type="media" data-type="file" data-width="506" title="Attachment">

------------------------------------------------------------------------

# Bypassing Plug-Ins

LUNA includes the ability to soft bypass UADx plug-ins, most UAD plug-Ins, and many third party plug-ins. This allows you to bypass and re-enable a plug-in in the least audible way possible. If a plug-in supports soft bypass, the plug-in includes an IN button that is illuminated when the plug-in is active, and unlit when the plug-in is soft-bypassed.

In addition, all plug-ins include a power button, which allows hard bypass, but is more audible when switched. Both bypass types can free processing power, though the Power button generally frees more processing power.

<div layout="center" node-type="mediaSingle" data-width="83">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="soft-bypass-plugin.png" file-size="1221960" data-height="405" data-id="9814ff9c-c8f1-4f08-a6a2-cbe2c1f0e3ed" node-type="media" data-type="file" data-width="585" title="Attachment">

![soft-bypass-plugin.png](Using%20Insert%20Plug-Ins_assets/1be1de4e4dd916fd155bc6bfdfe15f2783ca3f55.png)

</div>

</div>

Plug-ins that are soft bypassed (with the IN button) and disabled (with the Power button) appear differently in the LUNA mixer. Soft bypassed plug-in tiles are dimmed. Disabled plug-in tiles are dimmed further, and the plug-in name is italicized.

<div layout="center" node-type="mediaSingle" data-width="66">

<div class="wysiwyg-text-align-center" data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="soft-bypass-appearance.png" file-size="45889" data-height="192" data-id="cbe3b177-e95b-4e92-96aa-ade365d78ad0" node-type="media" data-type="file" data-width="360" title="Attachment">

![soft-bypass-appearance.png](Using%20Insert%20Plug-Ins_assets/af2dc7e0b03424bfcf8d426e14e4e2bd5244ff0a.png)

</div>

</div>

- Command+Click (macOS) / Ctrl+Click (Windows) to soft bypass or re-enable a soft-bypassed plug-in (IN button).
- Command+Control+Click (macOS) / Alt+Ctrl+Click (Windows) to enable or disable a plug-in (Power button).

**Note:** LUNA attempts to soft-bypass a plug-in when you Command+Click / Ctrl+Click it, but if the plug-in cannot be soft-bypassed, the plug-in is disabled with the Power button.

------------------------------------------------------------------------

# Filtering Plug-Ins by Categories

You can filter the lists of UADx, UAD (DSP), Audio Units, and VST3 plug-ins by categories. Categories allow you to narrow the list of available processors by the type of processor.

You can add or remove categories from Audio Units/VST3 plug-ins (many popular plug-ins have already been categorized). UADx and UAD DSP plug-ins are pre-categorized and those categories cannot be changed.

Categories are displayed by default. To see a plug-in category, expand the Categories area above the list of plug-ins. To close or expand plug-in categories, click on Categories.

![plugin-categories-expand.png](Using%20Insert%20Plug-Ins_assets/91f0a4fd16a0461103000c8307a8e45d24a61c35.png)

\
To filter the list of plug-ins
------------------------------

- Under the list of Categories, choose a category. The list of plug-ins is filtered by that category.

![plugin-categories-selected.png](Using%20Insert%20Plug-Ins_assets/8e94ec824c42fbd7cb113aa88e2b48b8fcb50c94.png)

\
To stop filtering the list, click the **X** next to Categories.

You can select multiple categories by Command+Clicking (macOS) / Ctrl-Clicking (Windows). Note that this will show all plug-ins that match any of the selected categories.

## To categorize Audio Units/VST3 plug-ins

1.  Add an Audio Units/VST3 plug-in to an insert. After the plug-in window opens, click the three dots near the upper left corner.
2.  Click Categories... The Categories screen opens.\
    ![categorize-plug-ins-open.png](Using%20Insert%20Plug-Ins_assets/e594287d6ea09ead0524049bda64a932eb7c39f8.png)
3.  On the Categories screen, select the category or categories in which the plug-in belongs. You can click categories to select them, and click again to clear them. A plug-in can be listed in multiple categories.\
    ![categorize-plug-ins-categories.png](Using%20Insert%20Plug-Ins_assets/dbbe4dd8f0111c87652779ab27a3a3c74777b838.png)\
     
4.  Click Done when you have finished assigning categories.

------------------------------------------------------------------------

</div>

</div>

# Searching for Plug-Ins

You can easily search for and choose plug-ins in the plug-ins browser. To search for a plug-in, after you click on an insert to open the plug-in browser, begin typing. As you type the browser shows the search results.

You can navigate through the list of plug-ins and apply plug-ins using the up and down arrow keys.

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div class="wysiwyg-text-align-center" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="plug-in-browser-search.png" file-size="251694" data-height="618" data-id="ec5c497f-2ee2-4e97-96f3-f3bc3e7626c9" node-type="media" data-type="file" data-width="376" title="Attachment">

![plug-in-browser-search.png](Using%20Insert%20Plug-Ins_assets/438d1a9bd9f7daf2cc4cd9777d400edaa3fc24c2.png)

</div>

</div>

------------------------------------------------------------------------

# Hiding, Showing, and Closing Plug-In Windows

When one or more plug-ins are open in LUNA, you can use key commands to hide or close them.

- To hide all floating windows, press Shift+W. This temporarily closes all floating windows (plug-ins, cue outputs, and others). 
- Restore hidden windows by pressing Shift+W again. When you hide windows, then open a new window (for example, when adding another insert plug-in), any previously hidden windows reappear.
- To close windows, press Command+W (macOS) / Ctrl+W (Windows). This closes the topmost floating window. 
- Press Command+W (macOS) / Ctrl+W (Windows) repeatedly to close additional floating windows.

------------------------------------------------------------------------

# Using Plug-In Presets

Plug-in presets are selected and saved using the Presets Browser. You can favorite presets, filter presets by categories, search presets by name, and set a default preset that is loaded each time you instantiate a plug-in.

**Note:** You use the same plug-in presets with UAD plug-ins in Standard, Record FX, or Unison inserts, and they function identically. UADx plug-ins have their own presets.

## To apply a plug-in preset

1.  Click the preset name on the plug-in title bar, or on the plug-in icon in the Insert rack, right-click, and choose Presets… The Presets Browser opens.
2.  Click a preset to select it. 

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div class="wysiwyg-text-align-center" collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="plug-in-open-presets.png" file-size="232033" data-height="470" data-id="b3e1d315-61c0-4fd8-a8c2-18e706a5f327" node-type="media" data-type="file" data-width="430" title="Attachment">

![plug-in-open-presets.png](Using%20Insert%20Plug-Ins_assets/3363dac7f5f0ff0e494f3f594e1b9cbb1e1fee44.png)

</div>

</div>

You can use the Up and Down arrows to navigate through presets. To search for a preset, click next to the magnifying glass at the top of the browser, and begin typing. 

## To save a plug-in preset

1.  Select a preset from the Preset Browser.
2.  Make changes to the plug-in as required. 
3.  Click Save. The Save Preset As dialog opens.
4.  Click Save to save the changes to the existing preset, or type a name for the preset to save a new preset, then click Save. 

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div class="wysiwyg-text-align-center" collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="save-plugin-preset-as.png" file-size="15726" data-height="103" data-id="03978b40-278f-4b77-8894-5b852e9ca126" node-type="media" data-type="file" data-width="245" title="Attachment">

![save-plugin-preset-as.png](Using%20Insert%20Plug-Ins_assets/5eb538473629d49acf76704219ff20c3d09b024e.png)

</div>

</div>

 

You can delete or rename presets that you have created. If you save changes to a system preset, the preset is saved as a User preset with the same name. 

## To favorite a plug-in preset

1.  Click the preset name on the plug-in title bar, or on the plug-in icon in the Insert rack, click •••, and choose Presets… The Presets Browser opens.
2.  Click the star to the right of a preset name to favorite or unfavorite a preset. 

![presets-favorite.png](Using%20Insert%20Plug-Ins_assets/96748dce977dd119eda28beaf4f9c1e967d00d1b.png)

 

## To show only favorite presets

1.  Click the preset name on the plug-in title bar, or on the plug-in icon in the Insert rack, click •••, and choose Presets… The Presets Browser opens.
2.  Click Favorites under Presets. When Favorites is highlighted, only favorited presets are shown.

![presets-show-favorite.png](Using%20Insert%20Plug-Ins_assets/eba2e32041309f3f4b76df4f024716c49e91f632.png)

 

## To set a default plug-in preset

1.  Select a preset from the Preset Browser.
2.  Right-click or Control-click on the preset and select Set Default Preset to '*preset*'.

The default preset is now set. When you load the plug-in in the future, this default preset is loaded in the plug-in.

![plug-in-default-preset.png](Using%20Insert%20Plug-Ins_assets/066ff498a83c7b3ea68cf54fac9783dfffe1e53b.png)

------------------------------------------------------------------------

# Showing Large Plug-In Icons

In the Inserts section, click on the Large View icon to show expanded inserts. This shows icons that represent the plug-ins loaded in the inserts.

<div layout="align-start" node-type="mediaSingle" data-width="50">

<div class="wysiwyg-text-align-center" collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="mixer-view-plugins-large.png" file-size="78924" data-height="191" data-id="087fc20a-3dff-4d51-beb8-eff2a409f40c" node-type="media" data-type="file" data-width="239" title="Attachment">

![mixer-view-plugins-large.png](Using%20Insert%20Plug-Ins_assets/3cb6fa925f008c24a117cf687bcecb9645c94b7e.png)

</div>

</div>

------------------------------------------------------------------------

# Adding an Icon for a Plug-In

By default, third party Audio Unit, VST3, MIDI FX, and instrument plug-ins have a generic icon. You can add a plug-in icon at any time. The plug-in icon takes a snapshot of the current user interface of the plug-in. 

## To create a plug-in icon

1.  Click on a plug-in in an Instrument, MIDI FX, or Insert row in Mixer View or on a Focus track.
2.  Arrange the window of the plug-in as you would like it to appear in the icon.
3.  Click the plug-in Name bar at the top of the plug-in window, and choose Create Plug-In Icon.

The icon is created from the current plug-in settings.

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div class="wysiwyg-text-align-center" collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="create-plugin-icon.png" file-size="176338" data-height="230" data-id="a95c18b2-9adc-4728-be48-78cc000d6955" node-type="media" data-type="file" data-width="393" title="Attachment">

![create-plugin-icon.png](Using%20Insert%20Plug-Ins_assets/fc0f880fd82c194a25b891fe0596880079aae52b.png)

</div>

<div collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="create-plugin-icon.png" file-size="176338" data-height="230" data-id="a95c18b2-9adc-4728-be48-78cc000d6955" node-type="media" data-type="file" data-width="393" title="Attachment">

</div>

<div collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="create-plugin-icon.png" file-size="176338" data-height="230" data-id="a95c18b2-9adc-4728-be48-78cc000d6955" node-type="media" data-type="file" data-width="393" title="Attachment">

</div>

<div collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="create-plugin-icon.png" file-size="176338" data-height="230" data-id="a95c18b2-9adc-4728-be48-78cc000d6955" node-type="media" data-type="file" data-width="393" title="Attachment">

------------------------------------------------------------------------

# Resizing UAD Plug-Ins

UAD plug-ins can be resized in LUNA. Resizing plug-ins to a larger size might be useful on a high resolution monitor, to view very small details, or when you are looking at the monitor from a distance. 

- **Global resizing:** When you resize a plug-in, the change applies to every instance of that specific plug-in, in LUNA and in any other DAW.

- **Resizing all plug-ins:** You can use the Apply to All menu item to instantly set every UAD plug-in (native and DSP) to the current size.

## To resize a UAD plug-in

1.  Click the ••• in the toolbar above the plug-in’s controls.
2.  Choose a resize level, from 75–200%.

The UAD plug-in is resized system-wide.

## To resize all UAD plug-ins

1.  Click the ••• in the toolbar above the plug-in’s controls.
2.  Choose a resize level, from 75–200%.
3.  From the same menu, choose Apply to All.

All UAD plug-ins are resized system-wide.

## To reset all UAD plug-ins to the default size

1.  Click the ••• in the toolbar above the plug-in’s controls.
2.  Choose the 100% option.
3.  From the same menu, choose Apply to All.

All UAD plug-ins are resized to their original size, system-wide.

</div>

</div>

<span id="sends"></span>

 

------------------------------------------------------------------------

# Converting Between Native and DSP Plug-Ins

If you are using LUNA in Apollo mode, LUNA can convert between native (UADx) and UAD DSP (UAD-2) versions of available plug-ins, seamlessly. You do not need to configure anything to use this functionality; simply insert UADx plug-ins on tracks as you usually do. If LUNA needs to convert to a UAD DSP version of the plug-in when the track goes into ARM mode, the UAD DSP version of the plug-in is loaded automatically. When you take the track out of ARM mode, the plug-in converts back to native (UADx) mode.

**Note:** You can only convert a plug-in between DSP and native (UADx) when the track on which the plug-in is inserted is not in ARM mode. To use a UADx plug-in on a record-enabled or input-enabled track in LUNA, disable ARM mode or switch LUNA to Core Audio or ASIO mode.

## To convert a single UAD plug-in to native or DSP

1.  Insert a UAD DSP or UADx plug-in in a standard insert in LUNA. Note that you cannot insert a UADx plug-in in a Record FX or Unison insert, which are reserved for UAD DSP plug-ins.
2.  Click the three dots on the left of the plug-in control bar.
3.  Under Processing, choose UADx or UAD-2.

![convert-plug-uadx-uad.png](Using%20Insert%20Plug-Ins_assets/766b2313570204c032ff337fd2ae5fe1bae7222a.png)

## To convert all available UAD plug-ins to native or DSP

- From the LUNA menus, choose Mixing \> Convert UAD-2 Plug-Ins to UADx, or Mixing \> Convert UADx Plug-Ins to UAD-2.

<span class="wysiwyg-font-size-small">251230</span>

