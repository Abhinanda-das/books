---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/43105954567956-USB-MIDI-with-UAFX-Pedals-Manual.html'
converted_at: 2026-05-31T13:44:58Z
tool: htmlq+pandoc
title: 'USB MIDI with UAFX Pedals Manual'
word_count: 2868
---

# USB MIDI with UAFX Pedals Manual


With UAFX 2.0 and newer firmware, you can use your MIDI controller to control MIDI program changes, MIDI control changes (CCs), and tempo sync with MIDI Beat Clock on compatible pedals.

**Note:** USB MIDI CC is currently in open beta.

## In this article

- [MIDI-Controllable Pedals](#h_01K9H0KF045ZJ6YR70W6MZH2FJ)
- [What You Need](#h_01K9H0KF0SZNB27FPTRQSE4CH4)
- [Using USB MIDI with your UAFX pedals](#h_01K9H0KF12TMGX7RJCN6JAYMTE)
- [Using MIDI Program Changes (PCs)](#h_01K9H0KF1EXSDX3KPTRN54F96W)
- [Using MIDI Control Changes (CCs)](#h_01K9H0KF1M42KFJ3Y7PH0ACABZ)

------------------------------------------------------------------------

# MIDI-Controllable Pedals

The following UAFX pedals are MIDI capable.

**Note:** All MIDI-capable UAFX pedals have full control change (CC) maps, available in the UAFX Control app, and in the individual UAFX pedal manuals.

- ANTI 1992 High Gain Amp \| [manual](29168125904532-UAFX-ANTI-1992-High-Gain-Amp-Manual.html)
- Astra Modulation Machine \| [manual](360058636191-UAFX-Astra-Modulation-Machine-Manual.html)
- Del-Verb Ambience Companion \| [manual](13621234251284-UAFX-Del-Verb-Ambience-Companion-Manual.html)
- Dream '65 Reverb Amplifier \| [manual](6432520866068-UAFX-Dream-65-Reverb-Amplifier-Manual.html)
- Enigmatic '82 Overdrive Special Amp \| [manual](30088097713428-UAFX-Enigmatic-82-Overdrive-Special-Amp-Manual.html)
- Galaxy '74 Tape Echo & Reverb \| [manual](13621305898132-UAFX-Galaxy-74-Tape-Echo-Reverb-Manual.html)
- Golden Reverberator \| [manual](360058140232-UAFX-Golden-Reverberator-Manual.html)
- Knuckles '92 Rev F Dual Rec Amplifier \| [manual](30849255964436-UAFX-Knuckles-92-Rev-F-Dual-Rec-Amplifier-Manual.html)
- Lion '68 Super Lead Amp \| [manual](18615951320596-UAFX-Lion-68-Super-Lead-Amp-Manual.html)
- MAX Preamp & Dual Compressor \| [manual](13621367271188-UAFX-MAX-Preamp-Dual-Compressor-Manual.html)
- OX Stomp Dynamic Speaker Emulator \| [manual](13621362465300-UAFX-OX-Stomp-Dynamic-Speaker-Emulator-Manual.html)
- Ruby '63 Top Boost Amplifier \| [manual](6433175606420-UAFX-Ruby-63-Top-Boost-Amplifier-Manual.html)
- Starlight Echo Station \| [manual](360058186472-UAFX-Starlight-Echo-Station-Manual.html)
- Woodrow '55 Instrument Amplifier \| [manual](6433549160212-UAFX-Woodrow-55-Instrument-Amplifier-Manual.html)

## MIDI Program Change-capable pedals

To switch programs with your MIDI controller, the UAFX pedal must have presets that can be assigned to MIDI Program Change (PC) slots in UAFX Control. The supported pedals are:

- ANTI 1992 High Gain Amp
- Astra Modulation Machine
- Dream '65 Reverb Amplifier
- Golden Reverberator
- Enigmatic '82 Overdrive Special Amp
- Knuckles '92 Rev F Dual Rec Amplifier
- Lion '68 Super Lead Amp
- OX Stomp Dynamic Speaker Emulator
- Ruby '63 Top Boost Amplifier
- Starlight Echo Station
- Woodrow '55 Instrument Amplifier

<span id="h_01K9H0KF0D8D1HQ24THXRJN7G0"></span>

## MIDI Beat Clock-capable pedals

UAFX pedals that can sync with MIDI Beat Clock are: 

- Astra Modulation Machine
- Del-Verb Ambience Companion
- Galaxy '74 Tape Echo & Reverb
- Starlight Echo Station

<span id="h_01K9H0KF0QD41B8WX13KEJ6CBC"></span>

### MIDI Beat Clock Follower / Leader

You have three options for the MIDI Beat Clock setting on a UAFX pedal:

- **Follower:** The pedal will receive tempo from another device.
- **Leader:** The pedal will send tempo to other devices (this is the one you send tap tempo or tempo changes to).
- **Off:** The pedal will not respond to MIDI Beat Clock.

**Important:** When using multiple UAFX pedals with MIDI Beat Clock, you must set one pedal as the Leader. All other pedals should be configured as Followers.

------------------------------------------------------------------------

# What You Need

In its simplest form, a MIDI setup including UAFX pedals requires a MIDI controller and a MIDI-compatible UAFX pedal. This section details the requirements. 

<span id="h_01K9H0KF0SSP4NA57Q3NJFKY13"></span>

## MIDI controller

A MIDI controller sends control signals to UAFX pedals and other devices, allowing you to switch presets, adjust parameters, and synchronize time, by sending MIDI messages from one or more footswitches or control pedals. You can use a MIDI controller with a USB Host port, or a standard 5-pin MIDI DIN controller with a USB Host MIDI interface. 

<span id="h_01K9H0KF0T5VA5Z7D28TZKWCQM"></span>

### Connection Options

There are two main ways to connect a MIDI controller to one or more UAFX pedals:

- **Direct USB Host Port:** Use a MIDI controller that features a USB Host port.
- **5-Pin MIDI DIN:** Use a standard 5-pin MIDI DIN controller, which must be connected via a USB Host MIDI interface.

### Device Compatibility

Most MIDI controllers are compatible with UAFX pedals.

- In most cases, standard MIDI controllers will require a USB Host MIDI interface and a standard USB hub to support multiple devices (typically a maximum of four or eight devices).
- Some advanced MIDI controllers, such as the Morningstar MC6 Pro and MC8 Pro, feature built-in MIDI host ports. 

## USB Host MIDI interfaces

For controllers with a 5-pin MIDI DIN connection, you must use a USB Host MIDI interface. A USB Host MIDI interface can connect to a single UAFX pedal directly, or to up to eight devices with a standard USB hub. For a list of USB Host MIDI interfaces that are known to work with UAFX pedals, see [this support article](43191950601620-Getting-started-with-UAFX-2-0-USB-MIDI.html).

## Multi-FX processors

Many guitar multi-effect processors can send MIDI messages and MIDI Beat Clock to UAFX pedals by connecting them via a USB Host MIDI interface. For example, multi-effect pedals from Fractal Audio, Line 6, Fender, and Neural DSP work with UAFX pedals. 

<span id="h_01K9H0KF0XTBAAN4V8T2PFENHS"></span>

## Example connection diagrams

This section illustrates various setup configurations with example diagrams.

![uafx-interface.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

*Controlling a single UAFX pedal with a MIDI Controller and USB Host MIDI interface*

 

![uafx-interface-multi.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

*Controlling multiple UAFX pedals with a MIDI Controller, USB Host MIDI interface, and USB hub*

 

![uafx-host-controller.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

*Controlling a single UAFX pedal with a MIDI Controller with built-in USB Host*

 

![uafx-host-controller-multi.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

*Controlling multiple UAFX pedals with a MIDI Controller with built-in USB Host and a USB hub*

------------------------------------------------------------------------

<span id="h_01K9H0KF12TMGX7RJCN6JAYMTE"></span>

# Using USB MIDI with your UAFX pedals

1.  [Update your UAFX pedals](#h_01K9H0KF1378WRRZMK9V08XNSJ) to UAFX 2.0 firmware or newer with the UA Connect app.
2.  Download v3 or newer of the [<span class="wysiwyg-underline">UAFX Control mobile app</span>](https://www.uaudio.com/pages/download-uafx-pedals).
3.  [Connect your pedal](#h_01K9H0KF187MS73C5SXABZQS1S) to the app.
4.  [Assign presets to MIDI Program Change slots](#h_01K9H0KF1EXSDX3KPTRN54F96W) in UAFX Control.
5.  [View and update MIDI CCs with MIDI Learn](#h_01K9H0KF1M42KFJ3Y7PH0ACABZ) in UAFX Control.

## Update your UAFX pedals

UAFX pedal firmware updates are installed with the UA Connect app ([get it here](https://www.uaudio.com/pages/download-uafx-pedals)). Firmware updates are installed over a USB connection to a computer, using a USB-C data cable (not included).

Your pedal's presets are retained when you update the firmware.

To update your pedal to UAFX 2.0 firmware:

- Connect the pedal's USB-C port to your computer and start UA Connect to check for available updates. Make sure the pedal is connected to 9VDC power (400 mA minimum).

  **Note:** The pedal's USB-C port can be connected to any type of USB port on the computer, but you may need an adapter.

- Click on the UAFX Pedals tab in UA Connect. The connected pedal is highlighted with a green dot below the pedal name and serial number.

- When an update is available for your pedal, the pedal tile includes an UPDATE banner and the Update button appears in the firmware area.

- Click the Update button to update your pedal's firmware. Make sure that the pedal remains connected to 9VDC power, and connected via USB to your computer, while the update is in progress.

When the update is complete, the pedal restarts. After the pedal restarts, UA Connect shows that the firmware is up-to-date. After the update is complete, you can disconnect the USB-C port.

1.  Connect the pedal's USB-C port to your computer and start UA Connect to check for available updates. Make sure the pedal is connected to 9VDC power (400 mA minimum).\
    **Note:** The pedal's USB-C port can be connected to any type of USB port on the computer, but you may need an adapter.
2.  Click on the UAFX Pedals tab in UA Connect. The connected pedal is highlighted with a green dot below the pedal name and serial number.
3.  When an update is available for your pedal, the pedal tile includes an UPDATE banner and the Update button appears in the firmware area.\
    ![new-firmware.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
    \
     
4.  Click the Update button to update your pedal's firmware. Make sure that the pedal remains connected to 9VDC power, and connected via USB to your computer, while the update is in progress.\
    ![uafx-update-progress.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

<span id="h_01K9H0KF17EHM81H2H0XJZR1P5"></span>

## Download UAFX Control

MIDI features are available in UAFX Control app v3 or newer. [Download it here](https://www.uaudio.com/pages/download-uafx-pedals).

<span id="h_01K9H0KF187MS73C5SXABZQS1S"></span>

## Connect your pedal to the app

- To connect to your pedal via Bluetooth, see [Logging in and Connecting to your UAFX Pedals (Bluetooth mode)](360058187832-UAFX-Control-Manual.html#h_01G3VKPBVMVPSYNP387D5M9VD0)
- To connect to a pedal via USB, see [Logging in and Connecting to your UAFX Pedal (USB mode)](360058187832-UAFX-Control-Manual.html#h_01K9GDBTQXCG4G6DBFMVTAVHR7)

## Understanding MIDI PC and CC channels

You can assign a specific MIDI channel (1-16) or the Omni channel to your UAFX pedal, so it can receive MIDI messages. By default, the MIDI PC and CC channels are disabled, so no MIDI channel is assigned and the pedal does not respond to MIDI PC or CC messages. 

<span id="h_01K9H0KF18MTX71DSPGQ678FKA"></span>

### Using the Omni Channel (Omni Mode ON)

Use the Omni channel to send the same message to multiple pedals simultaneously. This is ideal for Program Changes (PC). When managing a rig with multiple pedals, you usually want to switch presets simultaneously. Setting the MIDI Program Change channel to Omni on a group of pedals allows a single PC message to switch all their presets or Rigs at once.

**Note:** You can program a preset to be bypassed when recalled via a Program Change. This gives you easy control over the bypass or active state across multiple pedals with a single command from your controller.

### Using a Specific MIDI Channel (1-16)

Use a specific MIDI channel to send messages to a single pedal or a specific subgroup of pedals for isolated control.

Specific MIDI channel assignments are especially useful with MIDI CCs. This channel-specific approach lets you adjust parameters like gain, boost, or the speaker cabinet on one amp pedal without affecting others. Similarly, you can control the feedback amount on one delay pedal without changing the settings on another. By specifying the MIDI channel, you guarantee that each message only reaches its intended destination.

**Note:** Using separate MIDI channels helps avoid control collisions when using standard UAFX pedal Control Change numbers across multiple devices. (While you can reassign CCs on each pedal, using channels is often simpler if you don't want to manually reassign CCs.)

## Assigning a MIDI PC channel

1.  Open UAFX Control and tap USB or Bluetooth to get the list of pedals. 
2.  Tap the pedal tile for the pedal you want to adjust. 
3.  When the pedal screen opens, tap the MIDI icon in the upper right corner.\
    ![midi-button-knuckles.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
4.  Tap MIDI Program Change.\
    ![midi-pc-knuckles.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
5.  Tap the menu ▾ at the top to open the list of MIDI Program Change channels, then choose Omni, Disabled, or a channel from 1-16. 

The pedal now responds to MIDI PC messages according to your selection.  

## Assigning a MIDI CC channel

1.  Open UAFX Control and tap USB or Bluetooth to get the list of pedals. 
2.  Tap the pedal tile for the pedal you want to adjust. 
3.  When the pedal screen opens, tap the MIDI icon in the upper right corner.\
    ![midi-button-knuckles.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
4.  Tap MIDI CC. \
    **Note:** On pedals without presets, the MIDI CC screen opens when you tap the MIDI icon.\
    ![midi-cc-highlight-knuckles.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
5.  Tap the menu ▾ at the top to open the list of MIDI CC channels, then choose Omni, Disabled, or a channel from 1-16. 

The pedal now responds to MIDI CC messages according to your selection.  

------------------------------------------------------------------------

# Using MIDI Program Changes (PCs)

MIDI Program Changes allow you to switch entire programs (presets or OX Stomp Rigs) by sending a MIDI message to your UAFX pedal. You can program complex MIDI program changes with your MIDI controller and switch multiple pedals with one PC message.

<span id="h_01K9H0KF1FCA2QS4BKSAFHW68Z"></span>

### What is the Bypass Pedal setting?

When you assign a preset or Rig to a MIDI PC, you can also assign the Bypass state. In this way, you can use MIDI PCs to switch between presets on different UAFX pedals, and bypass or activate presets or Rigs.

### What does a MIDI PC message do?

A MIDI PC message loads a preset or Rig. This is the easiest way to send an entire configuration change to one or multiple UAFX pedals. You can configure any preset or Rig on one or multiple UAFX pedals to load when the pedal receives a specific MIDI PC message. In this way, you can configure multiple pedals to switch sounds at once. 

### What happens when I save a preset assigned to a Program Change?

When you save a preset that is assigned to a Program Change, the new saved preset is automatically assigned to that PC. In this way, any changes you make in real time to your sounds stay synchronized with your PC assignments.  

<span id="h_01K9H0KF1FR5XCAGE8KTRSBV98"></span>

### MIDI PC example

For example, with one MIDI PC message, you can:

- Load an active amp preset on Knuckles
- Load a bypassed amp preset on ANTI (to bypass a pedal that was previously active)
- Load a Rig on OX Stomp
- Load a reverb on Golden
- Load a delay on Starlight

![multi-program-change.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

## Assigning a preset or Rig to a MIDI PC slot

1.  Open UAFX Control and tap USB or Bluetooth to get the list of pedals. 
2.  Tap the pedal tile for the pedal you want to adjust. By default, pedals with presets open to the User Presets screen, and OX Stomp opens to the Rig Assignment screen. On OX Stomp, tap a rig assignment to view the User Rigs screen.
3.  Tap a preset or Rig category.
4.  Tap ••• next to a preset or Rig. The Options screen opens. \
    ![options-assign-pc.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
    \
     
5.  Tap Assign to PC Slot. The Program Change Slot screen opens. \
    ![assign-pc-slot.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
6.  Select a PC slot where you want to assign the preset or Rig. Drag up and down to scroll the list of PC slots. 
7.  To bypass the preset when loading the preset or Rig, tap yes on the Bypass Pedal control. 
8.  Tap Confirm.

The preset or Rig is now assigned to the MIDI PC slot.

------------------------------------------------------------------------

# Using MIDI Control Changes (CCs)

MIDI CCs are listed in the UAFX Control app when connected to your pedal, and in the UAFX pedal's [manual](../sections/360012250151-UAFX-Manuals.html). You can reassign MIDI CCs for your own setup using MIDI Learn, or restore one or all MIDI CCs to their defaults. 

<span id="h_01KD3YVJWGVSEAEZGXS504NEEE"></span>

## MIDI Control Change order

This section outlines the recommended order for sending multiple MIDI Control Change messages to ensure proper pedal response.

**Note:** If you are sending multiple CCs or a Program Change followed by multiple CCs, in order to make multiple changes to a sound, send MIDI messages in the following order. 

- Bypass / Unbypass
- Program Change
- Effect select (for example, the delay selection on Del-Verb)
- All other changes

Sending the Program Change or effect selection first allows the pedal to load the initial algorithm, then make the changes to the CCs you specify. If messages are sent out of order, the pedal may not reflect your intended changes. 

<span id="h_01K9H0KF1MY4FR7B6929YSAKT9"></span>

## Viewing MIDI CCs and assigning a MIDI channel

1.  Open UAFX Control and tap USB or Bluetooth to get the list of pedals. 
2.  Tap the pedal tile for the pedal you want to adjust. 
3.  When the pedal screen opens, tap the MIDI icon in the upper right corner.\
    \
    ![midi-button-galaxy.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
4.  Tap MIDI CC. \
    **Note:** On pedals without presets, the MIDI CC screen opens when you tap the MIDI icon.
5.  The list of MIDI CCs appears. Drag to scroll the list. \
    ![midi-cc-knuckles.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
     
6.  To assign a MIDI channel for CCs, tap the menu ▾ at the top then choose Omni, Disabled, or a channel from 1-16. 

## Reassigning a MIDI CC with Learn

1.  Tap a MIDI CC, and tap Learn. \
    ![midi-cc-seelcted-galaxy.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
2.  The Learn function is activated, and the Listening label appears.\
    ![midi-cc-listening-galaxy.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
3.  Send a CC message from your controller (for example, a button tap or controller move).
4.  The pedal assigns the selected CC to that controller number, and the Assigned label appears.\
    ![midi-cc-assigned-galaxy.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

## Disabling and Resetting MIDI CCs

You can disable a MIDI CC so the pedal does not respond to messages (for example, when sending pedal controls to several pedals on the same MIDI channel or on the Omni channel). 

You can also reset one CC or all CCs on the pedal to their factory defaults. 

To disable or reset MIDI CCs, tap a CC, then tap •••. The CC options screen opens.

- To reset the current CC to the factory default assignment, tap Reset CC to Factory Default.
- To reset all CCs on the pedal to their factory defaults, tap Reset ALL CC to Factory Default.
- To ignore messages to the CC on this pedal, tap Disable. A disabled CC appears with a dash in the CC number column. 
- To re-enable a disabled CC, either assign a CC using the Learn function, or reset the CC or all CCs to their factory defaults.

![cc-options-screen.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

- To reset the current CC to the factory default assignment, tap Reset CC to Factory Default. 
- To reset all CCs on the pedal to their factory defaults, tap Reset ALL CC to Factory Default. 
- To ignore messages to the CC on this pedal, tap Disable. A disabled CC appears with a dash in the CC number column. \
  ![galaxy-disabled-cc.png](USB%20MIDI%20with%20UAFX%20Pedals%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
- To re-enable a disabled CC, either assign a CC using the Learn function, or reset the CC or all CCs to factory defaults. 

<span class="wysiwyg-font-size-small">v260407</span>

