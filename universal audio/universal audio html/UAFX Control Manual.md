---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360058187832-UAFX-Control-Manual.html'
converted_at: 2026-05-31T13:44:56Z
tool: htmlq+pandoc
title: 'UAFX Control Manual'
word_count: 5463
---

# UAFX Control Manual


For MIDI setup and configuration instructions, including MIDI channel assignment, MIDI Program Change assignment, and MIDI CC assignment, see the [USB MIDI with UAFX Pedals Manual.](43105954567956-USB-MIDI-with-UAFX-Pedals-Manual.html)

The UAFX Control mobile app is the companion for UAFX pedals. To get UAFX Control, [go here](https://www.uaudio.com/pages/download-uafx-pedals).

Use UAFX Control to get free bonus effects, speaker cabinets, and voicings, and to configure global settings such as footswitch modes and EQ settings. You can also manage presets on supported pedals with UAFX Control, assign MIDI Program Changes on pedals with presets, and configure MIDI CCs.

**Tip:** You may need to update your pedal's firmware to get the latest UAFX Control app features. To use USB MIDI and control features, you must update to firmware version 2.0 or later. To update your firmware, use the UA Connect app. To learn how to use UA Connect,  <a href="14594248433812-UA-Connect-with-UAFX-Pedals.html" target="_self">go here</a>.

**Note:** UA Connect replaces the UAFX Control desktop app, which has been discontinued. 

This article includes:

- [Installing the UAFX Control Mobile App and Connecting to UAFX Pedals](#h_01G3VKP448WCJZ4PRF5WS8JAT7)
- <a href="#h_01G3VKPJZW23P0F0Z59XAGNDEY" target="_self">Registering your UAFX Pedal</a>
- <a href="#h_01G3VKPWJN448QSAXFA5RT4XPJ" target="_self">Using UAFX Control</a>
- <a href="#h_01G3VKQ8QFRAEQV264M2MKE402" target="_self">Managing Presets</a>
- [Backing up Presets and Rigs](#h_01K9GZS88EDC6JTGADQYNCJZW9)
- <a href="#h_01G3VKQMKPM4QV2K0TBKSAT9KB" target="_self">Managing Pedal Settings</a>
- <a href="#h_01G3VKR5DF5CC04TM7NPYXWK9B" target="_self">Live/Preset Switch</a>
- <a href="#h_01G3VKRPKVCVWB6KNV5CW9B96F" target="_self">4-Cable Mode (UAFX Amp Pedals Only)</a>

 

------------------------------------------------------------------------

 

# Installing the UAFX Control Mobile App and Connecting to UAFX Pedals

## iOS

Search for and install “UAFX Control” from the App Store, or [go here](https://www.uaudio.com/pages/download-uafx-pedals) for direct links.

**Important:** When you open UAFX Control for the first time, iOS prompts you to allow Bluetooth. You must tap OK and allow Bluetooth to use UAFX Control. If you don’t, UAFX Control cannot connect to your UAFX pedals. To manually allow the app to use Bluetooth (if you choose Don't Allow when prompted), open the Settings app, choose UAFX Control from the list, and enable Bluetooth.

<span id="h_01H91JFQ16JGQSTKW297FK9V32"></span>

![uafx-control-mobile-allow-bluetooth.png](UAFX%20Control%20Manual_assets/22105dfbb84e401984a1c2d6ff2521bc3a8338de.png)

## Android

Search for and install “UAFX Control” from the Google Play Store, or [go here](https://www.uaudio.com/pages/download-uafx-pedals) for direct links.

**Important:** When Android prompts you to access the device’s location, you must allow the device location. If you deny the location, UAFX Control cannot use Bluetooth, and will not be able to connect to your UAFX pedals.

### Android Device Location Notes

- Device location is an Android requirement that allows an app to use Bluetooth. Universal Audio does not use UAFX Control to track location in any way.
- If you deny app access to the device location, you will need to remove and reinstall the app.
- Your Android device may present a different dialog to allow location information.

![allow-location-android.png](UAFX%20Control%20Manual_assets/e1fb38efa9654ee9108363ae1ea801f9359bd481.png)

 

## USB and Bluetooth Modes

UAFX Control can be used with your UAFX pedals in USB mode or Bluetooth mode. All the same pedal control functions are available in USB or Bluetooth mode.

- **USB mode –** You can connect your pedal in USB mode. Use a USB-C data cable to connect the pedal to your device, then click USB at the top of the app. Your mobile device may require an adapter to connect to a USB-C cable.
- **Bluetooth mode –** You can connect to multiple pedals in Bluetooth mode. A Bluetooth connection requires pairing with each device separately. Though you can maintain a Bluetooth connection to multiple devices at one time, you can only view settings for one pedal at a time, and there will be a short pause when switching pedals. Click Bluetooth at the top of the app to use the app in Bluetooth mode.

<span id="h_01G3VKPBVMVPSYNP387D5M9VD0"></span>

![usb-bluetooth-modes.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

 

## Logging in and Connecting to your UAFX Pedals (Bluetooth mode)

**Note:** Connecting a UAFX pedal to more than one mobile device at the same time is not supported.

1.  Confirm your UAFX pedal is powered on.
2.  Open UAFX Control on your mobile phone. The Log In screen appears.\
    ![login.png](UAFX%20Control%20Manual_assets/66c097a9b736ad2584e63c754620b0ce1caedbf0.png)\
     
3.  Log in to your UA account, or create a new account if you don’t already have one. The app screen opens. 
4.  Select Bluetooth mode. Any unpaired UAFX pedals in range appear. If your pedal doesn't appear, press the Pair button on the rear of the pedal so the blue LED flashes.\
    ![pedal-found.PNG](UAFX%20Control%20Manual_assets/4abc98e47d53ee3c4b37feb54b319dd79754c104.png)\
     
5.  Tap the tile for a UAFX pedal to open its configuration screen. The Bluetooth pairing request appears on your screen.\
    ![bt-pairing-request.PNG](UAFX%20Control%20Manual_assets/9dcd48c6780c85e91fbc08c3af3cde11bbf9bca2.png)\
     
6.  Accept the pairing request to pair your phone with the UAFX pedal.\
     

### After the UAFX pedal is paired

- If the pedal is not registered to your account, the pedal registration screen opens. See \[Registering your UAFX Pedal\](#h_01G3VKPJZW23P0F0Z59XAGNDEY) below.
- If the pedal is already registered to your account, its presets, voicings, or settings screen opens.

**Note:** You may be prompted to pair your pedal with Bluetooth again if you update the pedal’s firmware using the UA Connect app.

<span id="h_01K9GDBTQXCG4G6DBFMVTAVHR7"></span>

## Logging in and Connecting to your UAFX Pedals (USB mode)

**Note:** UAFX Control supports a single direct USB connection. Connecting to multiple UAFX pedals over USB with a USB hub is untested.

1.  Confirm your UAFX pedal is powered on.
2.  Open UAFX Control on your mobile phone. The Log In screen appears.\
    ![login.png](UAFX%20Control%20Manual_assets/66c097a9b736ad2584e63c754620b0ce1caedbf0.png)
3.  Log in to your UA account, or create a new account if you don’t already have one. The app screen opens. 
4.  Select USB mode. The USB mode screen appears with instructions on how to power your pedal, and how to connect via USB-C.\
    ![usb-mode-unconnected.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
     
5.  Connect your pedal to your mobile device with a USB-C data cable. After a few seconds, the pedal tile appears. \
    ![uafx-mobile.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
     
6.  Tap the tile to open the pedal.
7.  After you make your changes in the app, disconnect the USB-C cable.

**Notes**

- For optimum results, it is best to connect the USB-C cable after the UAFX Control app is opened, and to disconnect the USB-C cable before you close the app. 
- Connecting to an Apple mobile device that has a Lightning port requires the Apple Lightning to USB 3 Camera Adapter.

## After your UAFX pedal is paired or connected

- If the pedal is not registered to your account, the pedal registration screen opens. See Registering your UAFX Pedal below.
- If the pedal is already registered to your account, its presets, voicings, or settings screen opens.

## To return to the pedal list

- On a pedal configuration screen, tap the pedal icon in the upper left corner to return to your list of pedals.\
  ![return-home.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
- On a pedal MIDI screen, tap the**〈** to return to the configuration screen, then tap the pedal icon to return to your list of pedals. \
  ![return-from-midi.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

## Logging out of UAFX Control

If you log out of UAFX Control, the app removes your pedals. If you log back in to the app, tap Add New in the upper-left corner of the app and press the Pair button on the pedal to reconnect.

<span id="h_01H91JFQ16MKSESEMAGPMH072F"></span>

#### Log out of UAFX Control

- At the top of the UAFX Control app screen, tap •••, then near the bottom of the screen tap Log Out.

![logout.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

UAFX Control returns to the Log In screen.

 

------------------------------------------------------------------------

 

# Registering your UAFX Pedal

If your pedal is not registered to your UA account, you can register it with UAFX Control.

**Note:** Any time the pedal is registered, any bonus effect(s), voicings, or speaker cabinets are added to your pedal, if applicable. If the pedal is subsequently registered by a different user, registration is transferred automatically.

Tap the pedal tile on the home screen to open your pedal’s configuration. The tile animates while the app connects, and the Register Pedal screen appears if the pedal is not currently registered to your UA account.

![register-pedal.png](UAFX%20Control%20Manual_assets/e14dd64329cf9145edc153a3658e755c3c88c921.png)

Tap the Register Pedal button to register your UAFX pedal. After the pedal is registered, the app shows the Registration Complete screen and information about how to select the bonus effect(s) or speaker cabinets. Tap OK to see the pedal’s User Presets screen (if available).

 

------------------------------------------------------------------------

 

# Using UAFX Control

**Note:** Global settings apply to all UAFX pedals. Preset management features are available on: 

- Anti
- Astra
- Dream
- Enigmatic
- Golden
- Knuckles
- Lion
- OX Stomp (Rigs)
- Ruby
- Starlight
- Woodrow

4-cable mode settings apply only to UAFX amp pedals (Anti, Dream, Enigmatic, Knuckles, Lion, Ruby, and Woodrow). Settings that are unique to individual pedals are described in the respective pedal manuals.

![presets-settings-tap.png](UAFX%20Control%20Manual_assets/6d6e9fb07f480b5b079827a1b7c3fff97f5a0585.png)

## Presets/Rigs screen

**Note:** On OX Stomp, preset sounds are called Rigs. Rigs are managed slightly differently than presets, and those differences are noted in this article. 

The pedal’s User Presets screen is displayed after registration on all pedals that include presets (except OX Stomp, which shows the Rig Assignments screen). The User Presets screen shows every preset you have stored on your UAFX pedal. If you do not have any user presets stored, the screen explains how to add one. If the app is on the Settings screen, tap the Presets area at the bottom left of the pedal's main screen to open the Presets screen.

## Settings screen

Tap Settings at the bottom right of the screen to access the settings for a pedal. You may need to scroll down on this screen to see all available settings.

![settings-presets-dream.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

Settings and preset screens (Dream)

 

------------------------------------------------------------------------

 

# Managing Presets

The UAFX Control app allows you to view, audition, and manage the presets on your UAFX pedal. In addition to the UA factory and artist presets that are added to your pedal by the app, every user preset on the pedal can be recalled and managed. Presets you select in the app can be recalled from several footswitch settings or via MIDI.

**Note:** Presets and Rigs are available only on Anti, Astra, Dream, Enigmatic, Golden, Knuckles, Lion, OX Stomp, Ruby, Starlight, and Woodrow.

For information on Del-Verb Voicings, see [Selecting Del-Verb Voicings](#h_01H91JFQ173MDANP5QPPW5JCSB).

For information on managing OX Stomp Rigs, see [Managing OX Stomp Rigs](13621362465300-UAFX-OX-Stomp-Dynamic-Speaker-Emulator-Manual.html#h_01H93QG35MFJJYDFVKXWAN18FC) in the OX Stomp Dynamic Speaker Emulator Manual.

## Viewing the preset management screen

To open the preset management screen, first tap your pedal’s tile on the app’s initial view. If the app is in Settings view, tap the Presets area at the bottom left of the pedal’s main screen to switch into Presets view.

![preset-screen-callouts.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

 

## Viewing Rigs (OX Stomp)

To open the Rigs screen, first tap your pedal’s tile on the app’s initial view. The app opens on the Rig Assignments screen. Tap the selection triangle to the right of any Rig to open the Rigs screen. 

![ox-stomp-rig-assign-callouts.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)**Important Preset/Rig and Backup Notes**

- **Pedal presets** - Individual presets you see in the app are stored on the pedal, not in the app. If UAFX Control is disconnected from your mobile device, or if you delete the app, all presets remain on the pedal.
- **Pedal backups** - Backups created in the mobile app are stored in the app, not on the pedal. If UAFX Control is deleted from your mobile device, the preset backups in the app are permanently lost.

## Factory and artist presets

The first time you connect your pedal to UAFX Control, the app installs UA factory and artist presets on the pedal. The factory and artist presets are read-only and cannot be modified, but after loading an artist or factory preset, you can adjust the pedal’s settings, then store it (using the pedal’s Store switch) as your own user preset.

<span id="h_01H91JFQ16A9WDQFGY2XS0439Y"></span>

### Special features in factory and artist presets

Some factory and artist presets include features that are not accessible with the pedal controls. These features may include speaker cabinets, microphones, room changes, and effect configurations. These presets can also include custom control mappings, so knobs and switches might not work as expected.

Preset and voicing descriptions are available [here](8272165765012-UAFX-Preset-and-Voicing-Lists.html). To see a description of each factory or artist preset and any custom settings within the UAFX Control app, tap ••• to view preset info.

You can edit a custom factory or artist preset and save it as your own preset by holding down the pedal’s Store switch, which allows you to utilize these custom settings. You can also save a copy from the preset info overlay, then edit the sound with the knobs and switches, and save it on the pedal by holding down the Store switch.

![preset-custom-description.png](UAFX%20Control%20Manual_assets/68548ec2ee4296a0bb6e1ca5d719a7911c125211.png)

To configure a new sound with available, non-custom sounds and knob settings, switch to Live mode and save a new preset.

<span id="h_01H91JFQ165XCJMYB6B5M1NQW4"></span>

## Viewing and selecting presets

To view and select presets, tap a category at the top of the screen (User, Factory, Artist, or Favorite).

- **User** includes all presets you have stored on the pedal. Note that there are no user presets until you store them.
- **Factory** includes presets made by UA sound designers as useful tonal starting points.
- **Artist** includes presets made by select UA artists.
- **Favorite** includes presets that you have swiped as favorites. Note that there are no Favorite presets until you favorite them.

Tap a preset to  immediately load it into the pedal's current slot, and hear the sound right away.

If the pedal is in a multi-preset footswitch mode, selecting the preset assigns it to the active slot.

**Note:** If the pedal is in Live mode when a preset is loaded, the pedal switches to Preset mode. If the pedal is currently bypassed, loading a preset unbypasses the pedal.

### Assign a preset to a footswitch

On an amp pedal, you can assign presets to footswitches in any of the multi-preset footswitch states. These states are:

- Live/Off \| A/B
- A/Off \| B/Off
- A/B \| C/D

<span id="h_01KA5X7CJQZKG78B6J661030FS"></span>

#### To assign a preset to a footswitch slot

1.  The User Presets screen opens automatically when you open your pedal in UAFX Control. If the User Presets screen is not open, tap Presets at the bottom of the screen.
2.  Tap the footswitch you want to assign until the correct color (red or green) is lit.
3.  On any Preset screen, tap the preset you want to assign. The preset is immediately assigned to the footswitch slot, and an indicator with the footswitch LED color and letter A, B, C, or D appears below the preset name. \
    \
    ![presets-assigned-footswitches.png](UAFX%20Control%20Manual_assets/3a9588c9340b5905e8659f15ea797ba4f39cc16f.png)

 

## To favorite a preset

Swipe a preset to the right to make it a favorite. To unfavorite a preset, swipe the preset to the right again. The preset is starred when it is a favorite.

**Tip:** You can also favorite a preset by opening preset options, then tapping Favorite.

![presets-favorite-unfavorite.png](UAFX%20Control%20Manual_assets/5670242feacd6c696d4251a89c613bb4e636ebd6.png)

## To delete a preset

- Swipe to the left to delete a User preset, then tap the X.

![preset-swipe-delete.png](UAFX%20Control%20Manual_assets/b6780c2933c4ef8f90575ec5c2081d8da729e9fa.png)

## To store a preset

To store a sound as a preset on the pedal, hold down the Store toggle switch on the pedal until the Preset LED blinks rapidly.

## Preset options

Tap ••• next to the active preset to open the preset options.\
![preset-edit-dots.png](UAFX%20Control%20Manual_assets/069bc5865735556346a29906df293a2d1de25a85.png)\
![preset-options-callouts.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

Tap ••• next to the active preset to open the preset options.

- To change the name of the preset, tap the pencil next to the name, and type the desired name for the preset, then tap Save. Note that factory and artist presets cannot be renamed.
- To favorite or unfavorite a preset, tap Favorite or Unfavorite.
- To save a copy of the preset, tap Save a Copy. A preset with the same name, and “Copy” appended, is saved to the top of the User list.
- To assign a preset to a MIDI Program Change slot, tap Assign to PC Slot.
- To delete a preset, tap Delete, then tap Confirm Delete when prompted. You can also swipe a user preset in the User and Favorite lists to the left to delete. Note that factory and artist presets cannot be individually deleted.
- Deleted user presets can be restored using the app’s backup/restore features.

<span id="h_01K9GEPCR7ZASE5714C4C8K140"></span>

## Editing presets

After you load a preset, you can edit it by changing the knob and switch settings. When a preset has been changed, the EDITED label appears next to the name in the preset list.

You can save the preset from the pedal by holding down the pedal’s Store switch until the Preset LED blinks rapidly. The preset is saved with a generic name (for example, “Dream 5”) in the User Presets list.

You can also save the edited preset from the UAFX Control app, by tapping ••• next to the active preset, then tapping Save.

To restore an edited preset to the pre-edited state, tap ••• next to the active preset, and tap Restore.

<span id="h_01H91JFQ16Z4RARM0H643PBFK5"></span>

![preset-edited.png](UAFX%20Control%20Manual_assets/bccb5a4288e810bf81a4ec908e87b2e06f9268d6.png)

## Preset Notes

- You can save a new preset on a pedal by holding down the Store switch on the pedal, until the Preset LED blinks rapidly. You can also save an edited preset from the preset options menu.
- The following global settings can make presets on your UAFX pedal appear as edited, if the global settings are different from when the preset was saved:
  - 4-cable mode (UAFX amp pedals)
  - Preamp coloration mode on/off (Galaxy, Starlight)
  - Tap tempo on/off (Astra, Galaxy, Starlight)
  - Changes made with MIDI CCs

------------------------------------------------------------------------

<span id="h_01K9GZS88EDC6JTGADQYNCJZW9"></span>

# Backing up Presets and Rigs

The Presets/Rigs Backup feature retrieves all user presets from the UAFX pedal and saves them as a single batch in the UAFX Control app. You might want to do this before you reset your pedal or before you delete presets or Rigs to maintain a copy of the current state. The backup is retained in the app even after you reset your pedal, so you can restore presets or Rigs at a later time.

**Important:** If you delete the UAFX Control app from your mobile device, your backups are permanently lost.

<span id="h_01K9GZS88GB4VEJD6ZR054SA8V"></span>

#### **To back up your presets/Rigs**

1.  At the bottom of the UAFX Control app, tap Settings.
2.  Scroll down if needed, then tap Save New Backup.\
    ![save-new-backup.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

The backup is stored in the UAFX Control app.

### Replacing the backup

You can replace the backup before you apply a firmware update or reset your pedal, or after you have changed presets or Rigs (storing, adding, deleting, and renaming) and you want to store the current state of your pedal's presets or Rigs.

**Important:** When you replace the backup, the pedal’s previously saved backup in the app is overwritten and permanently lost.

<span id="h_01K9GZS88K2BV7ZWK8Q186CJXN"></span>

#### **To replace your backup**

1.  Tap Save New Backup.\
    ![replace-restore-backup.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)\
    \
     
2.  In the warning popup, tap Update.\
    ![overwrite-backup.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

The backup in UAFX Control is replaced with the presets or Rigs from the pedal.

## Restore Backup

When you restore a backup from the app to the pedal, you have the option to either Replace Presets/Rigs or Merge Presets/Rigs.

- **Replace Presets/Rigs** – All presets or Rigs on the pedal are deleted and replaced with all presets in the backup. **Important:** User presets or Rigs on the pedal that are not in the UAFX Control backup are permanently lost.
- **Merge Presets/Rigs** – All presets or Rigs in the UAFX Control backup are added to the presets or Rigs on the pedal. Note that merge can result in duplicate user presets and Rigs, because presets or Rigs with the same name are added and not replaced.

<span id="h_01K9GZS88QY0CDBG2K0VX8XMPS"></span>

#### **To restore your presets/Rigs**

1.  In the Preset Backups section, tap Restore. The Restore options appear.\
    ![restore-backup.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
2.  Tap Replace Presets/Rigs or Merge Presets/Rigs.

The presets or Rigs are restored to the pedal.

 

## Viewing and restoring presets/Rigs from another pedal

If you connect two pedals of the same type to UAFX Control on the same mobile device, and save backups from both pedals in the app, UAFX Control allows you to restore the user presets or Rigs from one pedal to another.

#### To restore presets/Rigs from another pedal

1.  In the Preset/Rigs Backups section, tap the pedal backup from which you want to restore.\
    ![backup-from-another-pedal.png](UAFX%20Control%20Manual_assets/1304e730033cda634082e36e0316413a7cb9cbe1.png)
2.  Tap Restore. The Restore options appear.\
    ![backup-restore-info.png](UAFX%20Control%20Manual_assets/f7ee5986399902e69713fd4b6b0b2fe6abe6b85b.png)
3.  Tap Replace Presets/Rigs or Merge Presets/Rigs.

The presets or Rigs are restored to the pedal.

 

------------------------------------------------------------------------

 

# Managing Pedal Settings

Tap Settings at the bottom right of the screen to access the settings for a pedal. You may need to scroll down on this screen to see all available settings.

## Removing a pedal

You can remove a pedal from the tile display in the UAFX Control app. Removing a pedal does not delete any information on the pedal, remove the registration, or change any Bluetooth settings.

#### **To remove a pedal from UAFX Control:**

1.  Swipe the pedal tile to the left. The red Remove area appears.
2.  Tap Remove to delete the pedal from the UAFX Control app.

![remove-pedal.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

## Adding a previously removed pedal

When a pedal has been removed, you can add it back to the UAFX Control app.

#### **To add a previously removed pedal:**

1.  Press the PAIR button on the back of the UAFX pedal once.
2.  Tap the Add New button in UAFX Control.\
    \\![add-new-pedal.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

The pedal tile appears in UAFX Control.

\
Getting Context Help
--------------------

You can get contextual help in UAFX Control by tapping the ⓘ symbol next to a section. The context help is built into the app and doesn’t require an internet connection.

![context-help.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

## Getting Online Help

To access the UAFX pedal manuals and get other details such as individual effect control maps, tap the Online Help button at the bottom of the screen to visit the UAFX Knowledge Base. Online help requires an internet connection.

![online-help.png](UAFX%20Control%20Manual_assets/d7b7e1d2df76a38fb0b590c53bb024c99e90a1a0.png)

## Resetting your UAFX Pedal

Reset your pedal to restore your UAFX pedal to the factory defaults.

### Important Notes:

- You must remove the pedal tile from UAFX Control, and remove the pedal from your phone’s Bluetooth settings if you want to reconnect your mobile device after you reset the pedal defaults.
- Resetting your pedal deletes any user presets, bonus speaker cabinets, bonus effect(s), and registration. Customized preset settings are permanently lost. (You can backup and restore your user presets *before* you reset the pedal).
- To get the bonus speaker cabinets or bonus effect(s) after resetting the pedal, register the pedal again with UAFX Control software.

<span id="h_01H91JFQ16T3CWG83S3GYDQ6TG"></span>

#### To reset the pedal:

1.  Tap the Reset Pedal button at the bottom of the UAFX Control screen.\
    ![reset-pedal-button.png](UAFX%20Control%20Manual_assets/3019845d76475349f6910f5e2bca05fce6005148.png)\
    \
    ![reset-warning.png](UAFX%20Control%20Manual_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)
2.  Read the warnings, then tap Reset Pedal to continue. The pedal restarts.
3.  Remove the pedal tile from the UAFX Control app.
4.  Remove the pedal from your phone’s Bluetooth settings.

 

------------------------------------------------------------------------

 

# Live/Preset Switch

**Note:** Live and Preset modes are available only on Anti, Astra, Dream, Enigmatic, Golden, Knuckles, Lion, Ruby, Starlight, and Woodrow.

You can choose to listen to the preset sound or the live sound with the app, instead of using the pedal’s footswitches. After you use the app to change to a footswitch mode that requires the pedal sound to be always on, you can choose whether the Live sound or a Preset sound is active.

<span id="h_01G3SAHK7Q2WCK7WAWZA9524ND"></span>

## Assigning the preset or live sound

At the bottom of the app, tap the Live/Preset buttons to switch between the live and preset sounds. Your choice will persist on the pedal until you switch to another sound, either with a footswitch on the pedal or with this switch in the app.

![uafx-control-live-preset-slider.png](UAFX%20Control%20Manual_assets/6916805fd01d43feea94f7074f7ab92eebc81cf6.png)

**Important:** This setting is retained when the pedal is powered off. This means that, when the active footswitch mode doesn’t allow switching between Live and Preset modes:

- You won’t be able to switch between Live mode and Preset mode without the mobile app, and
- You won’t be able to tell by looking at the pedal whether you’re in Live mode or Preset mode.

### Example 1

The footswitch mode on Dream is set to Boost \| Vibrato and the app’s Live/Preset switch is set to Preset when the pedal is powered off. When the pedal is powered back on: 

- The stored preset loads
- The pedal is in Preset mode
- You can’t switch to Live mode without the app

This example allows your preset to always load as soon as the pedal is powered, but controls may not match the sound initially.

### Example 2

The footswitch mode on Dream is set to Boost \| Vibrato and the app’s Live/Preset switch is set to Live when the pedal is powered off. When the pedal is powered back on: 

- The pedal is in Live mode
- You can’t switch the pedal to Preset mode without the app. 

This example ensures your knob and switch settings are heard when initially powered, but you can’t load a stored preset without the app.

**Tip:** To retain the ability to switch between Live mode and Preset mode without the app, set the footswitch mode to one of these values before powering off:

- Live \| Preset
- Boost \| Live/Preset
- Vibrato \| Live/Preset
- Reverb \| Live/Preset
- Live/Off \| A/B
- A/Off \| B/Off

 

------------------------------------------------------------------------

 

# 4-Cable Mode (UAFX amp pedals only)

4-cable mode with UAFX amp pedals lets you add another switchable channel to any real guitar amplifier that has an effects loop. This special mode lets you switch between your guitar amplifier’s built-in preamp section and the sounds in your pedal.

**Warning:** Turn off your amplifier before wiring the pedal and enabling 4-cable mode. If you enable 4-cable mode with incorrect wiring, you can cause extreme feedback.

## How 4-cable mode works

- When a UAFX amp pedal is on, the amp emulation is heard, and the real amp’s preamp section is bypassed.
- When a UAFX amp pedal is off, the real amp’s preamp section is heard, and the pedal is bypassed with analog dry-through.

## 4-cable mode notes

- 4-cable mode is only available on UAFX amp pedals (Anti, Dream, Enigmatic, Lion, Knuckles, Ruby, and Woodrow).
- If the pedal is not already in Live \| Preset mode when you enable 4-cable mode, a confirmation appears, and the pedal automatically switches to Live \| Preset mode after you confirm.
- When you’re playing through a real guitar amplifier and speaker cabinet, you might want to disable the pedal’s speaker cabinet emulation by pressing the pedal's Speaker switch until the LED is unlit.
- You may need to adjust the UAFX pedal’s Output knob lower than you normally would, because the effects loop return on your amp is unattenuated.
- If you are using other pedals in your effects loop, place them between the first UAFX amp pedal’s 2/Stereo output and the Return input on your amp’s effects loop. With this wiring, the other pedals in the effects loop still process audio, even when the pedals are bypassed.
- Front-of-amplifier effects, such as distortion and overdrive pedals, should be placed between the instrument and the first pedal’s 1/Mono input.
- The Room control does not have any effect in 4-cable mode.

<span id="h_01H91JFQ17TX1ENWQVDR7SBNS9"></span>

## Multiple UAFX amp pedals

To use multiple UAFX amp pedals in 4-cable mode, see the examples below. With multiple pedals configured in 4-cable mode, you can switch between preset and live sounds on the amp pedals and the sounds in your real amplifier for even more available sounds. When you use multiple amp pedals in 4-cable mode, the earliest amp pedal enabled in the chain is the amp pedal you hear.

**Tip:** To switch between sounds on different UAFX amp pedals with multiple pedals in 4-cable mode, enable sounds on multiple pedals. The first pedal that is enabled is the pedal you hear. When you bypass a pedal that is earlier than another enabled pedal, you will hear the next enabled pedal. In this way you can switch between sounds on multiple pedals.

## To enable 4-cable mode

1.  Power off your real amplifier.
2.  Configure the cables as illustrated and described below.
3.  Connect to the pedal with the UAFX Control app, and open the pedal Settings screen.
4.  In the UAFX Control app, under 4-Cable Mode, tap On. A confirmation is displayed.
5.  Tap Enable 4-Cable Mode in UAFX Control. The pedal enters 4-cable mode.
6.  Turn your amplifier on.

You can now hear the UAFX amp pedal when Live mode or Preset mode is enabled, and your real amplifier’s preamp channel when the pedal is disabled.

## 4-cable mode connections

See the diagrams and sections below for 4-cable mode connections with one, two, or three UAFX amp pedals.

### One UAFX amp pedal

Use 4-cable mode with one UAFX amp pedal to add another switchable channel to your real effects-loop equipped guitar amplifier.

1.  Connect your instrument to the 1/Mono input on your UAFX amp pedal.
2.  Connect the 1/Mono output from the UAFX amp pedal to the main input on your amplifier.
3.  Connect the effects loop Send output on your amplifier to the 2/Stereo input on your UAFX amp pedal.
4.  Connect the 2/Stereo output from the pedal to the effects loop Return input on your amplifier.
5.  Place any front-of-amplifier effects between your instrument and the UAFX amp pedal, and place any other effects loop effects between the pedal’s 2/Stereo output and the effects loop return input on your amplifier.

#### UAFX amp pedal enabled

This diagram shows the signal flow when the UAFX amp pedal is enabled. Your signal is colored with the full amp tone from the pedal and routed to your real amplifier’s effects loop return, bypassing your real amplifier’s input jack and preamplifier section. Any effects placed in your amplifier’s effects loop return are heard.

![4-Cable-Active-Diagram.png](UAFX%20Control%20Manual_assets/cf3ab904f817343afe582877d91bc7f67173cbfd.png)

#### UAFX amp pedal bypassed

This diagram shows the signal flow when the UAFX amp pedal is bypassed. Note that your signal passes through the pedal with no pedal amp tone, and into the main input on your real amplifier. Any effects placed before your amplifier’s effects loop return are heard.

![4-Cable-Bypass-Diagram.png](UAFX%20Control%20Manual_assets/821e2b01a3357830e901f93964d9c859e60d7764.png)

### Two UAFX amp pedals

To connect two UAFX amp pedals in 4-cable mode, you need a total of six cables. Wire the pedals as described and shown in the diagram below. In this mode, the earliest enabled UAFX amp pedal is the one you hear, even when the other UAFX amp pedal is enabled. Looking at your pedals from the top, this would be the UAFX amp pedal furthest to the right. Any effects placed before your amplifier’s effects loop return are heard.

1.  Connect your instrument to the 1/Mono input on your first UAFX amp pedal.
2.  Connect the 1/Mono output from the first pedal to the 1/Mono input on the second pedal.
3.  Connect the 2/Stereo output from the first pedal to the effects loop Return input on your amplifier.
4.  Connect the 1/Mono output from the second pedal to the main input on your amplifier.
5.  Connect the 2/Stereo output from the second pedal to the 2/Stereo input on the first pedal.
6.  Connect the effects loop Send output on your amplifier to the 2/Stereo input on the second pedal.
7.  Place any front-of-amplifier effects between your instrument and the first UAFX amp pedal, and place any other effects loop effects between the first pedal’s 2/Stereo output and the effects loop return input on your amplifier.

![6-Cable-Diagram.png](UAFX%20Control%20Manual_assets/ce6057005c097ec55c85e0f3508be9d83a7e1a27.png)

### Three UAFX amp pedals

To connect three UAFX amp pedals in 4-cable mode, you need a total of eight cables. Wire the pedals as described and shown in the diagram below. In this mode, the earliest enabled pedal is the one you hear, even when one or both of the other two pedals are enabled. Looking at your pedals from the top, this would be the pedal furthest to the right. Any effects placed before your amplifier’s effects loop return are heard.

1.  Connect your instrument to the 1/Mono input on your first UAFX amp pedal.
2.  Connect the 1/Mono output from the first pedal to the 1/Mono input on the second pedal.
3.  Connect the 1/Mono output from the second pedal to the 1/Mono input on the third pedal.
4.  Connect the 2/Stereo output from the first pedal to the effects loop Return input on your amplifier.
5.  Connect the 2/Stereo output from the second pedal to the 2/Stereo input on the first pedal.
6.  Connect the 2/Stereo output from the third pedal to the 2/Stereo input on the second pedal.
7.  Connect the 1/Mono output from the third pedal to the main input on your amplifier.
8.  Connect the effects loop Send output on your amplifier to the 2/Stereo input on the third pedal.
9.  Place any front-of-amplifier effects between your instrument and the first UAFX amp pedal, and place any other effects loop effects between the first pedal’s 2/Stereo output and the effects loop return input on your amplifier.

![8-Cable-Diagram.png](UAFX%20Control%20Manual_assets/2313e7249b12b584e1df3600e8c0957121bff7f2.png)

 

v260407

