---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/13210238444948-Using-LUNA-with-Core-Audio.html'
converted_at: 2026-05-31T13:44:43Z
tool: htmlq+pandoc
title: 'Using LUNA with Core Audio'
word_count: 1480
---

# Using LUNA with Core Audio


LUNA can run on native computer hardware on macOS with Core Audio. You can configure one or more Core Audio devices to provide LUNA's audio inputs and outputs. 

**Note:** With a Volt interface, Core Audio mode appears as VOLT in the LUNA info area. 

## In this article

- [Why Choose Core Audio Mode or Apollo Mode?](#h_01GS927MQT8KJN5K5EGFYAA5V8)
- [Configuring LUNA Core Audio Hardware Settings](#h_01GS91YPNYNCAM2SG5MFY7ZMJ4)
- [Renaming Core Audio Inputs and Outputs](#h_01GS9285QZBZK6E1WCK82AKZPM)
- [Using LUNA in Core Audio Mode with Apollo](#h_01GS928KRRXPJX888EPD8PNJX5)

------------------------------------------------------------------------

# Why Choose Core Audio Mode or Apollo Mode?

If you have Thunderbolt (not USB) Apollo, LUNA in Apollo mode will still give you the lowest latency for recording inputs and recording through plug-ins. However, there are many scenarios where it is convenient to use Core Audio mode. Some examples are:

- Using LUNA with a non-Apollo Thunderbolt or USB audio interface, or with built-in audio
- Using LUNA with an Apollo, while controlling plug-ins and routing in Apollo’s Console
- Mixing or recording on the go with a bus-powered device like a Universal Audio Volt
- Recording and monitoring through native plug-ins
- Other configurations that are not possible with Apollo mode, including hybrid devices with multiple Core Audio devices

This list details the differences when LUNA is running in Apollo mode and Core Audio mode.

- **ARM (Accelerated Realtime Monitoring)**

  - **Apollo mode:** Realtime UAD Processing available in Unison and REC FX inserts.

  - **Core Audio mode:** Realtime UAD Processing in UAD Console only. ARM features unavailable in Core Audio mode.

- **Unison inserts**

  - **Apollo mode:** Unison inserts available in LUNA.

  - **Core Audio mode:** Unison inserts available in UAD Console.

- **UAD Record FX inserts**

  - **Apollo mode:** On an ARM-enabled audio track, effects are recorded (printed) when inserted in one of the RECORD FX inserts.

  - **Core Audio mode:** To record (print) through UAD plug-ins, use UAD Console’s UAD REC option.

- **ARM-enabled bus tracks**

  - **Apollo mode:** Two ARM-enabled, assignable bus tracks available.

  - **Core Audio mode:** No ARM buses. Hardware-accelerated sends and buses available in UAD Console.

- **Converting between Native and DSP plug-ins**

  - **Apollo mode:** Native (UADx) plug-ins automatically convert to DSP (UAD-2) plug-ins when a track is record- or input-enabled in ARM mode, and vice versa.

  - **Core Audio mode:** Native and DSP plug-ins do not automatically convert.

- **Inactive plug-ins in ARM mode**

  - **Apollo mode:** Audio Units and VST3 plug-ins (and native UAD plugins with no DSP counterpart) inactive when a track is record- or input-enabled in ARM mode.

  - **Core Audio mode:** Audio Units, VST3 plug-ins, and native UAD plug-ins active when a track is record- or input-enabled.

- **Lowest possible record and monitoring latency**

  - **Apollo mode:** In Apollo Mode with ARM enabled, record- or input-enabled tracks are always at the lowest latency, regardless of the Buffer Size setting. ARM-enabled tracks have less latency than Native tracks, at any buffer size.

  - **Core Audio mode:** For lowest possible native latency on record- or input-enabled inputs in Core Audio mode, set LUNA's buffer size to 32–128 samples. A smaller buffer requires more computer resources.

- **Multitrack and Master Tape Extensions**

  - **Apollo mode:** Multitrack and Master Tape enabled for playback (non-ARM), but ARM-enabled tracks bypass tape extensions.

  - **Core Audio mode:** Tracks are monitored through any Multitrack and Master Tape Extensions.

- **Summing Extensions**

  - **Apollo mode:** Summing Extensions bypassed on ARM-enabled buses.

  - **Core Audio mode:** Summing Extensions always active.

- **Main track plug-ins**

  - **Apollo mode:** Tracks in ARM mode bypass Main track plug-ins. ARM-enabled tracks routed directly through hardware, bypassing Main track processing.

  - **Core Audio mode:** Tracks routed to Main track are routed through Main track plug-ins and Extensions.

- **Console Tracking Mode**

  - **Apollo mode:** Available.

  - **Core Audio mode:** Use UAD Console.

- **Talkback**

  - **Apollo mode:** Talkback available directly in LUNA.

  - **Core Audio mode:** Talkback available in UAD Console.

------------------------------------------------------------------------

# Configuring LUNA Core Audio Hardware Settings

The following settings are available on the Hardware tab in Core Audio mode. 

**Important:** When you finish configuring LUNA Core Audio hardware settings, click the Apply button at the bottom of the audio devices list.

![native-hardware-settings.png](Using%20LUNA%20with%20Core%20Audio_assets/f64ea300a16c1ff7dd8a855ee8a40c30732c0b6e.png)

## Audio Device

The Audio Device drop-down allows you to choose Apollo or Core Audio mode. If you have an Apollo interface connected, you can choose either Apollo mode or Core Audio mode. If you do not have an Apollo connected, you can only choose Core Audio mode. Core Audio mode uses Core Audio drivers to enable input and output routing for your devices. 

You can also set Apollo or Core Audio mode from the Audio Device menu at the bottom of the LUNA window, by clicking in the Info area to open the Audio Settings popover. If the Info section is not visible, choose View \> Section \> Info from the LUNA menus.

## Buffer Size

Set your buffer size according to your current LUNA working mode. Buffer size can be set from 32 samples to 2048 samples.  

- Small buffer sizes (32–128 samples) are good for recording live instruments and playing live virtual instruments.
- Medium buffer sizes (256-512 samples) are good for most mixing, and for recording if your hardware offers direct hardware monitoring.
- Large buffer sizes (1024–2048) are good for larger mixes with more plug-ins and LUNA Extensions, and for recording if your hardware offers direct hardware monitoring.

You can also set the buffer size from the Audio Settings popover at the bottom of the LUNA window, by clicking in the Info area. If the info area is not visible, choose View \> Section \> Info from the LUNA menus.

## Record Mute

Record Mute automatically mutes your input in the LUNA outputs when the track is record-enabled or input-enabled. This is useful if you are using a built-in mic for recording and monitoring with built-in speakers (for example, the built-in MacBook Pro microphone and speakers) and you don’t want to create feedback. You can also mute the input manually in your software to prevent feedback, but this setting simplifies that workflow.

## Main Outputs

Choose a Main output pair for LUNA with this setting. The signal to these outputs is controlled by the LUNA Monitor volume knob. 

## Cues

Choose a Cue output pair for LUNA with this setting. After you configure Cue outputs, they appear in the LUNA mixer, and you can send separate cue mixes to those outputs. More cues are available when you connect multiple devices, or have more pairs of available outputs.

In the following example, the Volt 276 monitor outputs are configured as the main outputs, and two cue buses are configured on Volt 476 Line outputs 1-2 and 3-4.

![setting-cues-outputs-multiple-devices.png](Using%20LUNA%20with%20Core%20Audio_assets/f929b605e9088a3004df5c8a6db117659408eab8.png)

## Devices list

Enable and disable your audio devices from this list. You can enable or disable multiple audio devices and Core Audio will aggregate them automatically.

### To enable devices

1.  Start LUNA. 
2.  Open the LUNA Sidebar by clicking the three dots on the left of the screen, then click Settings, or choose LUNA \> Settings from the app menu.
3.  In the Hardware panel, select the devices you want to enable by clicking their boxes. Enabled devices are highlighted orange.
4.  Click Apply.

![multiple-devices-enabled.png](Using%20LUNA%20with%20Core%20Audio_assets/ea8e29806279941d05c7bab7e89f9dc6ea9a14c5.png)\
 

### Device Notes

- You can configure LUNA to use the System Settings option, which specifies that LUNA uses the settings configured for macOS Sound settings. When this option is selected, you cannot select multiple audio devices.
- If you do not select an audio device, any connected Volt or Apollo interfaces are automatically selected. Automatically selected devices appear highlighted in white.

![automatic-volt-selection.png](Using%20LUNA%20with%20Core%20Audio_assets/86c96fd534fb98acead8bf9cd1fa70712a1a89a1.png)

------------------------------------------------------------------------

# Renaming Core Audio Inputs and Outputs

On the I/O Settings screen, you can rename inputs and outputs.

## To rename Core Audio inputs and outputs 

1.  Start LUNA. 
2.  Open the LUNA Sidebar by clicking the three dots on the left of the screen, then clicking Settings, or choose LUNA \> Settings from the app menu.
3.  Click the I/O Settings tab.
4.  Click and type in the Custom Name field for any input or output to rename it, then press Return.

![native-io-settings.png](Using%20LUNA%20with%20Core%20Audio_assets/de601a8218b0d26e32817a7ec2e36656a96fe9f9.png)

------------------------------------------------------------------------

# Using LUNA in Core Audio Mode with Apollo

If you start LUNA without an Apollo connected, LUNA automatically starts in Core Audio mode. If you have an Apollo connected, but want to use LUNA in Core Audio mode, follow this procedure. 

**Note:** You can only switch between Core Audio and Apollo mode when playback is stopped. 

## To enable LUNA Core Audio mode 

1.  Start LUNA. 
2.  Open the LUNA Sidebar by clicking the three dots on the left of the screen, and clicking Settings, or choose LUNA \> Settings from the app menu.
3.  From the Audio Device drop-down, choose Core Audio. 
4.  Click Apply.
5.  <a href="#h_01GS91YPNYNCAM2SG5MFY7ZMJ4" rel="undefined" target="_self">Configure your hardware settings</a> on the Hardware tab.

<span class="wysiwyg-font-size-small">260108</span>

