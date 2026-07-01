---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041440692-Accelerated-Realtime-Monitoring-ARM-in-Apollo-Mode.html'
converted_at: 2026-05-31T13:44:53Z
tool: htmlq+pandoc
title: 'Accelerated Realtime Monitoring (ARM) in Apollo Mode'
word_count: 1561
---

# Accelerated Realtime Monitoring (ARM) in Apollo Mode


## In this article

- <a href="#h_2bc302ea-5bdb-477e-8037-5d621d35a8fb" target="_self">Enabling ARM</a>
- <a href="#h_c744824b-2051-4b17-ac20-a10fc9ecb174" target="_self">Using ARM with Audio Tracks</a>
- <a href="#h_5537915a-ac9c-4af7-932a-0c7a20ec39d9" target="_self">Using ARM with Instrument Tracks</a>
-  <a href="#h_9668d65a-f3ff-4382-9a3e-687877cf57bf" target="_self">Using ARM with Bus Tracks</a>
- <a href="#h_af393a7a-3493-4636-bce8-bac01c103366" target="_self">LUNA Buffers, Latency, and Delay Compensation</a>
- <a href="#h_649674df-65c4-4728-94ff-b0a3386f2cf5" target="_self">Components Affected by ARM (Apollo Mode Only)</a>
- <a href="#h_02003871-f8b3-4fe1-bb0e-7c317a821a07" target="_self">Available ARM Resources</a>

Accelerated Realtime Monitoring™ (ARM) is a deep hardware, DSP, and software integration feature inside LUNA that allows you to achieve the lowest possible latency while recording with UAD plug-ins in real time. ARM is supported in Apollo mode only.

If you are familiar with UAD Console software, ARM eliminates the need to use UAD Console altogether, while providing all of the same features and benefits such as low latency plug-ins, input routing, cue mixing, and more. 

You can enable ARM globally. Use ARM to achieve the lowest possible input monitoring latency when you monitor input signals through LUNA outputs, including monitors, headphones, and cues.

**Note:** ARM is not supported at 4x sample rates (176.4 kHz, 192 kHz).

For a video overview of ARM, see LUNA Basics: Accelerated Realtime Monitoring (ARM).

------------------------------------------------------------------------

# Enabling ARM

ARM is enabled system-wide. When you enable ARM, all ARM components are affected, including audio tracks, instrument tracks, and ARM Aux-enabled buses.

## To enable ARM

- Click the Toggle ARM Mode button in the Global settings at the top of the LUNA window, or
- Click the ARM toggle in Mixer view to the left of the track record/input enable controls, or
- Choose Transport \> Accelerated Realtime Monitoring from the LUNA menus, or
- Click the ARM button in the Record Workflow (see <a href="360041440592-Using-LUNA.html#using-workflows" target="_self">Using Workflows</a>).

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="arm-button.png" file-size="109964" data-height="325" data-id="b4b42ba7-6e9a-4a13-809d-ccbcd1a7ae6b" node-type="media" data-type="file" data-width="335" title="Attachment">

</div>

</div>

<div layout="center" node-type="mediaSingle" data-width="100">

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="workflow-recording-arm.png" file-size="29939" data-height="47" data-id="09ce2fce-b968-412f-a677-7588ecc509c3" node-type="media" data-type="file" data-width="634" title="Attachment">

![arm-button.png](Accelerated%20Realtime%20Monitoring%20%28ARM%29%20in%20Apollo%20Mode_assets/db70ec6b85ad25b9d54e2ba1c081f8857064c77d.png)

</div>

</div>

 

![workflow-recording-arm.png](Accelerated%20Realtime%20Monitoring%20%28ARM%29%20in%20Apollo%20Mode_assets/28126fbb9ceada6e9188469bc6a562dcac0db328.png)

## To enable a bus to use an ARM Aux

1.  Enable ARM. 
2.  On the Bus track in Mixer view, click the ARM button. 
3.  From the Accelerated Realtime Monitoring drop menu, select an ARM Aux to assign the bus. 
4.  To bypass an ARM Aux for the bus, select None.

<div layout="align-start" node-type="mediaSingle" data-width="55">

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="arm-aux-selecting.png" file-size="201831" data-height="394" data-id="5209f2cd-db81-4974-b65f-403fa4dd6de6" node-type="media" data-type="file" data-width="316" title="Attachment">

![arm-aux-selecting.png](Accelerated%20Realtime%20Monitoring%20%28ARM%29%20in%20Apollo%20Mode_assets/8426f79f03a079f48f44c45626a7d6ea63758cef.png)

</div>

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="arm-aux-selecting.png" file-size="201831" data-height="394" data-id="5209f2cd-db81-4974-b65f-403fa4dd6de6" node-type="media" data-type="file" data-width="316" title="Attachment">

</div>

</div>

------------------------------------------------------------------------

# Using ARM with Audio Tracks

LUNA and ARM control the muting and unmuting of Apollo input channels used on audio tracks. Apollo input channels that are used on record-enabled or input-enabled tracks are unmuted, and all other Apollo input channels are muted. 

- **Near-zero latency:** When ARM is enabled, record or input-enabled audio tracks are accelerated through Apollo’s DSP, which provides near-zero latency. 

- **Plug-in compatibility:** Only UAD DSP plug-ins can be used for monitoring while ARM is active. All Audio Unit (AU) or VST3 plug-ins are automatically disabled/bypassed until ARM is turned off or the track is taken out of record/input mode.

- **Insert behavior:**

  - **Record FX slots and Unison:** These slots are active while recording or monitoring in ARM mode.

  - **Standard Inserts:** Only the first four standard insert slots are active when a track is record/input enabled.

  - **Full Access:** All eight insert slots become available when ARM is disabled or the track is no longer record/input enabled.

------------------------------------------------------------------------

# Using ARM with Instrument Tracks

ARM forces instruments (UAD, AU, or VST3) to run at a lower buffer setting on macOS. On Windows, instruments run at the host buffer setting, but are still routed through Apollo for optimized processing.

- **Native plug-in support:** Unlike audio tracks, you can use Audio Unit (AU) or VST3 plug-ins on instrument tracks while ARM is enabled.

- **Fastest response:** ARM ensures that UAD plug-in processing on the instrument track provides the lowest possible latency during recording.

- **Multi-out plug-ins note:** Adding multi-out channels to an instrument track disables ARM mode for that track and all its associated outputs. If ARM is disabled (due to multi-outs), you must use only UAD DSP plug-ins or bypass all other plug-ins on those tracks and the Main track to avoid audible delay.

------------------------------------------------------------------------

# Using ARM with Bus Tracks

ARM supports up to two dedicated auxiliary (AUX) buses for real-time monitoring of time-based effects (like reverb or delay) with near-zero latency.

- **Hardware integration:** These two declared buses utilize the UAD Console DSP-accelerated auxes rather than the standard host processing.

- **Phase alignment:** ARM Aux buses are not phase-aligned. Because of this, they should only be used for parallel effects (reverb/delay) rather than serial processing or phase-sensitive grouping (like drum buses).

- **Enabling an ARM Aux:**

  - Enable **ARM** in LUNA.

  - Click the **ARM button** on your chosen bus track.

  - Choose either **Aux 1** or **Aux 2** from the dropdown menu.

- **ARM bus behavior:** When ARM is enabled, only the two designated ARM-enabled buses will receive audio from tracks that are currently record-enabled or input-enabled.

- **Tracks routed to buses:** Any record/input-enabled tracks routed directly to a standard bus will skip that bus and play through the Main out instead when ARM is active.

------------------------------------------------------------------------

# LUNA Buffers, Latency, and Delay Compensation

You can set the buffer size for LUNA to maximize performance. 

- **Range:** You can set the buffer size from 32 – 2048 samples.

- **Use a** **low buffer:** For recording (tracking) when ARM is not enabled to minimize latency, or on Windows when recording instruments.

- **Use a high buffer:** For large mixes with many plug-ins, instruments, and Extensions, to maximize processing power.

- **ARM mode and buffers:** When ARM is active on a track (or an ARM AUX bus), the buffer for that audio becomes near zero. This allows you to keep your global buffer high for processing power while still enjoying low-latency monitoring.

- **Automatic delay compensation:** LUNA automatically aligns all audio and instrument tracks during playback to ensure they sync perfectly with existing material.

------------------------------------------------------------------------

# Components Affected by ARM

The following components are affected when you enable or disable Accelerated Realtime Monitoring, on input/record-enabled tracks.

## **Audio tracks (Apollo hardware inputs)**

- **ARM disabled:** LUNA manages all signal flow natively.

- **ARM enabled:** Tracks use Apollo's DSP to achieve near-zero latency for Monitor and CUE outputs.

## **Instrument tracks**

- **ARM Disabled:** Supports UAD, Audio Units, and VST3 instruments, and all plug-in formats.

- **ARM Enabled:** Still supports all instrument and plugin formats (UAD, AU, VST3), but optimized for lower latency.

## **ARM Aux 1–2 and Cues**

- **ARM Disabled:** LUNA manages signal flow natively.

- **ARM Enabled:** These tracks/cues switch to Apollo DSP resources for near-zero latency monitoring.

## **UAD DSP plug-ins**

- **ARM Disabled:** Active in Unison, four Record FX, and all eight standard inserts (as DSP allows). Unison/Record FX are always recorded to disk.

- **ARM Enabled:** Active in Unison and 4 Record FX (recorded to disk). However, only the first four standard insert slots are active.

## **LUNA Extensions (tape and summing)**

- **ARM Disabled:** Active and processing audio (monitoring only; not recorded to disk).

- **ARM Enabled:** Deactivated. Processing only resumes once ARM is turned off.

## **Audio Unit, VST3, and UADx plug-ins**

- **ARM Disabled:** All plug-ins are active in standard inserts.

- **ARM Enabled:** Plug-ins are deactivated on audio and bus tracks (except for virtual instruments).

  - If a UADx plugin has a UAD DSP equivalent, LUNA automatically switches to the DSP version.

  - Otherwise, plug-ins are bypassed and show a notification until ARM is disabled or the tracks are out of ARM mode.

## **LUNA Console Extensions**

- **ARM Disabled:** Console extensions run natively using your computer's CPU.

- **ARM Enabled:** Console extensions switch to UAD DSP for lower latency.

------------------------------------------------------------------------

# Available ARM Resources

The system indicates the number of available ARM monitor channels at all times. This number changes when you enable ARM and you record-enable one or more tracks. 

ARM channels use the DSP in your Apollo interface. The number of available ARM channels depends on the physical inputs in your system.

- **Apollo Rack Models (except Silver):** 16 Channels

- **Apollo x4:** 12 Channels

- **Apollo Silver:** 10 Channels

- **Apollo Twin:** 10 Channels

- **Apollo Solo / Arrow:** 2 Channels

## How ARM resources are used

- **Record or input-enabled audio track:** Reuires one mono ARM resource per channel (one for a mono track, two for a stereo track). 
- **Bus fed by a record or input-enabled track, assigned to ARM Aux 1 or Aux 2:** Requires two mono (one stereo) ARM resources. 

### **ARM resource example**

A stereo audio track that is routed to two ARM-enabled buses requires six mono (three stereo) ARM resources, whereas a mono audio track with no ARM-enabled bus assignments consumes one mono ARM resource.

To view available ARM resources, enable ARM, and toggle the Record workflow on.

<div layout="align-start" node-type="mediaSingle" data-width="40">

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="workflows-switch-record.png" file-size="10032" data-height="61" data-id="b04e897e-e48b-41a3-901a-ca09e85bfa2f" node-type="media" data-type="file" data-width="192" title="Attachment">

![workflows-switch-record.png](Accelerated%20Realtime%20Monitoring%20%28ARM%29%20in%20Apollo%20Mode_assets/d1c341739b4e27879bf392b6a5a811f41cbc3567.png)

</div>

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="workflows-switch-record.png" file-size="10032" data-height="61" data-id="b04e897e-e48b-41a3-901a-ca09e85bfa2f" node-type="media" data-type="file" data-width="192" title="Attachment">

</div>

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="workflows-switch-record.png" file-size="10032" data-height="61" data-id="b04e897e-e48b-41a3-901a-ca09e85bfa2f" node-type="media" data-type="file" data-width="192" title="Attachment">

![workflow-recording-arm.png](Accelerated%20Realtime%20Monitoring%20%28ARM%29%20in%20Apollo%20Mode_assets/28126fbb9ceada6e9188469bc6a562dcac0db328.png)

</div>

</div>

<div layout="center" node-type="mediaSingle" data-width="100">

<div collection="contentId-194936841" context-id="194936841" file-mime-type="image/png" file-name="arm-channels-available.png" file-size="24454" data-height="54" data-id="ebc1fc7f-7ccc-41fb-a2da-80ef3508240e" node-type="media" data-type="file" data-width="630" title="Attachment">

</div>

</div>

<span class="wysiwyg-font-size-small">250106</span>

