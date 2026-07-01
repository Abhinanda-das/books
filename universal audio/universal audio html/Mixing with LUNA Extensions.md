---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/44791240323860-Mixing-with-LUNA-Extensions.html'
converted_at: 2026-05-31T13:45:01Z
tool: htmlq+pandoc
title: 'Mixing with LUNA Extensions'
word_count: 2607
---

# Mixing with LUNA Extensions


Extensions provide processing that is built in to the fabric of LUNA. LUNA extensions allow you to process with analog-style tape and summing, and to use full featured API Vision Console (for EQ, compression, gating) and API 2500 bus compression on tracks, buses and the main track in LUNA.

## In this article

- [Using Neve Summing](#h_6e90a286-6c2e-4b5a-b736-d820fc44da8a)
- [Using API Summing](#h_01EPSRKRX8B728J63MBPKC4NWK)
- [Using API Vision Console Emulation](#h_01F5E4A288VDJ88C3R9BTQR8J2)
- [Using Multitrack Tape](#h_005f036c-cb1e-4e10-a39b-53298eafd224)
- [Using Master Tape](#h_01EPSRNBJQDNHD3KYVNC67EDCW)
- [Assigning Default Extensions](#h_01HER0RZX17FTCBSM3HA0YNQ4X)

------------------------------------------------------------------------

# Using Neve Summing

You can add Neve Summing to bus tracks and the main track using a LUNA Extension.

## Using the Neve Summing LUNA Extension

Neve Summing imparts the sound and headroom characteristics of a Neve console bus channel directly into the LUNA summing buses. You can purchase the optional Neve Summing LUNA Extension to add Neve summing to Bus and Main tracks.

**Note:** when you change the Neve Summing setting for a bus, the faders for the bus and for all tracks that feed the bus will change position because of the difference in fader taper between LUNA native summing bus and Main channels and Neve Summing bus and Main channels.

#### To add Neve Summing:

- In the Input row of a bus or the Main track, click the Summing button, and choose Neve Summing.
- Set the controls for Headroom (HR), Trim, and Impedance.

To adjust controls on multiple tracks, select multiple tracks, then change the controls on one track. The tracks must be in an enabled track group (Track \> New Track Group), or Selection Grouping (Track \> Selection Grouping) must be enabled to adjust Neve Summing settings on multiple tracks at one time.

<div class="wysiwyg-text-align-center" title="Attachment">

![neve-summing.png](Mixing%20with%20LUNA%20Extensions_assets/ee701184de8938b6615eac8aa04cf0d259ee1861.png)

</div>

## Neve Summing controls

Adding Neve summing modifies the fader and panning behavior of the bus or main track to accurately emulate the response of a classic Neve console.

### Headroom (HR)

Controls the balance between clean signal space and harmonic character.

- **Range:** +4 dB to +28 dB.

- **Low Settings (+4 dB):** Provides the most headroom with the least saturation.

- **High Settings (+28 dB):** Introduces saturation and audible distortion.

- **Gain Compensation:** The control is gain-compensated to keep volume levels consistent as you adjust it, though the "Low Impedance" setting may still result in a slight volume increase.

- **Operation:** Rotate the knob or double-click to select a specific value from a dropdown menu.

### Impedance

Changes the electrical character of the bus or Main channel.

- **Settings:** Toggle between **High** (default) and **Low**.

- **Effect:** Each setting offers a distinct audio character and gain level. Generally, **Low Impedance** is louder than the unprocessed signal. Choose the setting that best complements your specific audio material.

### Trim

Used to fine-tune the output level after making adjustments to headroom or impedance.

- **Range:** -6 dB to +6 dB.

- **Operation:** Rotate the knob or double-click to type in a precise value. Use this to increase or decrease the overall level of the summing bus.

### Bypass (In/Out)

Use this switch to toggle the Neve summing emulation on or off. This allows you to quickly A/B test the effect against your original audio.

------------------------------------------------------------------------

# Using API Summing

You can add API Summing to bus tracks and the main track using the LUNA Extension.

## Using the API Summing LUNA Extension

API Summing imparts the sound and headroom characteristics of an API console bus channel directly into the LUNA summing buses. You can purchase the optional API Summing LUNA Extension to add API summing to Bus and Main tracks.

**Note:** when you change the API Summing setting for a bus, the faders for the bus and for all tracks that feed the bus will change position because of the difference in fader taper between LUNA native summing bus and Main channels and API Summing bus and Main channels.

### To add API Summing

- In the Input row of a bus or the Main track, click the Summing button, and choose API Summing.
- Set the controls for Headroom (HR) and Trim.

To adjust controls on multiple tracks, select multiple tracks, then change the controls on one track. The tracks must be in an enabled track group (Track \> New Track Group), or Selection Grouping (Mixing \> Selection Grouping) must be enabled to adjust API Summing settings on multiple tracks at one time.

<div class="wysiwyg-text-align-center" title="Attachment">

![api-summing-overview.png](Mixing%20with%20LUNA%20Extensions_assets/5d174c91f16c2f1c451416eb4d4c11e8aaae53f4.png)

</div>

## API Summing controls

Adding API Summing modifies the fader and panning laws of the bus or main track to accurately emulate the response of an API console.

### Headroom (HR)

Determines the balance between clean signal clarity and harmonic saturation.

- **Range:** +4 dB to +28 dB.

- **Low Settings (+4 dB):** Offers maximum headroom and the cleanest signal with minimal saturation.

- **High Settings (+28 dB):** Pushes the emulation into rich saturation and vintage distortion.

- **Gain Compensation:** This control is gain-compensated, ensuring your monitoring levels remain consistent even as you drive the channel harder.

- **Operation:** Rotate the knob or double-click it to select a value from the dropdown menu.

### Trim

Use this to fine-tune the overall level of the summing bus or to compensate for any gain shifts caused by headroom adjustments.

- **Range:** -6 dB to +6 dB.

- **Operation:** Rotate the knob or double-click to type in a specific value.

### Bypass (In)

The **In** button toggles the API summing emulation on and off. Use this to quickly audition the effect and compare the processed signal with the original audio.

------------------------------------------------------------------------

# Using API Vision Console Emulation

![api-vision-console-overview.png](Mixing%20with%20LUNA%20Extensions_assets/4d98a52e9d592465548b33cd13ca269221d09eee.png)

The API Vision Console Emulation Bundle turns LUNA into a full API console. You can create new audio, instrument, and bus tracks with API Vision Console elements pre-assigned, building sessions within the complete Vision console emulation experience. You can assign API Vision channel strips and API 2500 Bus Compressors to all tracks in your session.

API Vision Console Emulation provides a new way to interact with the LUNA workspace. See <a href="360060691752-LUNA-API-Vision-Console-Extension-Manual.html" target="_self">API Vision Console Emulation</a> in the Extensions section for more information.

------------------------------------------------------------------------

# Using Multitrack Tape

![tape-channel-expanded.png](Mixing%20with%20LUNA%20Extensions_assets/3f9102e2726fecb798b18ca64400c96fe1b5986e.png)

## Using Tape LUNA Extensions

LUNA integrates classic multitrack tape sound directly into your workflow. Tape processing can be enabled on any audio or instrument track and is applied during playback.

### Available Tape Extensions

- **Oxide:** Provides a simple "one-knob" approach using presets and per-channel saturation.

- **Studer A800:** Offers advanced, deep control over individual tape parameters. (Note: The LUNA Extension and UAD plug-in versions are cross-licensed).

### Using multiple tape machines

LUNA allows you to run up to four virtual tape machines per session. Each machine acts as a global template for your tracks.

1.  **Configure tape machines:** Set the overall character (formula, speed, etc.) for machine 1, 2, 3, or 4.

2.  **Assign machines to tracks:** Add one of four machine to the tape slot on a track.

3.  **Adjust per-track settings:** Fine-tune the Saturation (Oxide) or individual Channel Settings (Studer) for each specific track.

### Mixing strategy

The four-machine system offers massive flexibility. For example:

- **Machine 1:** Driven hard for aggressive drums and bass.

- **Machine 2:** Set clean for clear, airy vocals.

- **Machines 3 and 4:** Used for alternative colors or special effects.

## Configuring Oxide LUNA Extension

The Oxide Extension includes presets to configure the tape machine settings. You cannot manually adjust controls for the Oxide LUNA Extension. However, if you own the UAD Oxide Tape plug-in, you can configure and save presets in the plug-in that you can then use in the LUNA Extension.

## Configuring Studer A800 LUNA Extension

The Studer A800 LUNA Extension allows you to load presets and adjust manual controls. Settings like bias, tape speed, and tape type are configured on the tape machine globally for the session, and in addition, each track has its own level (saturation) control, as well as control over the individual track's HF Driver and Repro EQ settings. You can use presets that you save in the UAD Studer A800 plug-in with the LUNA Extension.

## Using tape machines

### To configure a Tape Machine in a tape deck slot

1.  On an audio or Instrument track in Mixer view, or on a Focus track in Timeline view, click the Tape slot. The Tape browser opens. \
    ![tape-machine-browser.png](Mixing%20with%20LUNA%20Extensions_assets/12dca6c5f286f97baa1c4ae592c9c9ba1052c1ec.png)
2.  Double-click a tape slot (A-D) in which you want to configure the tape machine.
3.  From the Machine list, select a tape machine type (Oxide or Studer A800). Studer A800 is only available if you have the Studer A800 LUNA Extension licensed and installed. The tape machine configuration is displayed in the browser.
4.  Configure the tape machine through presets (Oxide, Studer A800) or configure the tape machine settings (Studer A800).

Once you have configured a tape machine in a slot, you can assign that tape machine to any number of audio or Instrument tracks. You can configure a total of four tape machines, each with unique settings, for each LUNA session.

### To assign a tape machine to a track

1.  Click the Tape insert on a track. The Tape Machine selector opens on the left of the screen.
2.  Choose the tape machine from the list in the Tape Machine browser. A tape machine Saturation knob appears on the track, along with a VU meter and a Power button. In the Mixer, with Large View enabled for the tape row, additional settings for the Studer A800 LUNA Extension appear.
3.  Use the Saturation knob to increase or decrease the amount of tape saturation applied to the track.
4.  If you are using the Studer A800 LUNA Extension, you can configure the HF Driver HF setting, Bias, Repro LF, and Repro HF settings, and enable noise on a per-track basis, in addition to the overall machine controls.
5.  Click the power button to enable or disable tape emulation on the track.

### To configure the global sound of an Oxide tape machine

1.  Click the Tape insert on a track. The Tape Machine selector opens on the left of the screen.
2.  Choose an Oxide tape machine from the list.
3.  Choose a preset to configure the global sound of the Oxide tape machine in the session.

**Tip:** If you have the UAD Oxide Tape plug-in, you can use presets you have created in the plug-in with LUNA tape tracks.

### To configure the global sound of a Studer A800 tape machine

1.  Click the Tape insert on a track. The Tape Machine selector opens on the left of the screen.
2.  Double-click the A800 tape machine that you want to configure.
3.  Choose a preset to configure the global sound of the Studer A800, or adjust the controls manually. Click Open to open the additional machine controls.

To adjust a tape control, you can click and drag on the control to rotate it to the desired position, or you can double-click the control to choose from a list of values.

To adjust controls on multiple tracks, select multiple tracks, then change the controls on one track. The tracks must be in an enabled track group (Track \> New Track Group), or Selection Grouping (Mixing \> Selection Grouping) must be enabled to adjust tape settings on multiple tracks at one time.

You can access tape controls from the tape configured on a track.

Hover your mouse over the tape slot on a track, and use the tape options to open the tape browser, open the assigned tape machine for the track, or remove tape from the track.

![tape-hover-options.png](Mixing%20with%20LUNA%20Extensions_assets/5b06de78a2f4f1244f2ad03886e1047d1cc93cb5.png)

------------------------------------------------------------------------

# Using Master Tape

The UAD Ampex ATR-102 Mastering Tape Recorder plug-in and LUNA Extension provides the final "analog polish" to your music, turning your recordings into records. Fully authenticated by the Ampex Corporation and trusted by Platinum‑selling professionals the world over, the ATR‑102 LUNA Extension faithfully captures the unique dynamics, colorful frequency response, and tape saturation of this industry‑standard Ampex machine.

## Using Ampex ATR-102

You can add Ampex ATR-102 to a Bus track or the Main track. You can configure each instance of Ampex ATR-102 Master Tape LUNA Extension with manual controls and presets.

### Assign Ampex ATR-102 to a track

1.  Click the Master Tape insert on a bus track or the Main track, and select the ATR-102.

    <div title="Attachment">

    ![atr-102-select.png](Mixing%20with%20LUNA%20Extensions_assets/b09713c295a2f2546c5f289175960cb921d7b82e.png)

    </div>

2.  The primary set of tape machine controls appear in the Master Tape slot, and the Master Tape deck appears in the browser on the left of the screen.

In the Master Tape slot, you can configure the most important features: tape formula, tape speed, and tape head width. You can also toggle the Master Tape deck on and off. You can further configure the Master Tape deck in the Browser on the left of the screen.

### Master Tape Deck controls in Browser

<div class="wysiwyg-text-align-center" title="Attachment">

![atr-102-closed.png](Mixing%20with%20LUNA%20Extensions_assets/cf2c9768d221b69326747e34f3b80ac87bf689ef.png)

</div>

### To configure Ampex ATR-102 in the Browser

1.  Hover over the Master Tape insert on a track, and click the box to open the Master Tape Deck.

    ![master-tape-hover-options.png](Mixing%20with%20LUNA%20Extensions_assets/66db8e70873a6316fb537806e3303ef47e539e29.png)

2.  The Master Tape Deck opens on the left of the screen.

3.  Adjust the controls manually, or choose a preset to configure the global sound of the Ampex ATR-102.

4.  Click the Open ( **^** ) button to open the secondary machine controls.\
    ![atr-102-open.png](Mixing%20with%20LUNA%20Extensions_assets/c7ce873a05e960696e173b4fb371849fc49f8d79.png)

To adjust a rotary tape control, you can click and drag on the control to rotate it to the desired position, or double-click the control to choose from a list of values. You can toggle through push-button controls by clicking the buttons, or toggle switches by clicking them,

## Inserting the tape deck pre fader or post fader

The Ampex ATR-102 Master Tape LUNA Extension can be configured as either a pre-fader or post-fader effect. By default, the Ampex ATR-102 is pre-fader on the Main track and post-fader on buses. On the Main track, the ATR-102 is configured pre-fader to enable modern workflows where a master brickwall limiter or other processor is positioned after it. The Master Tape machine on a bus is configured post-fader by default to apply the sound of the tape after other bus processing. The use of a Master Tape machine on buses allows for sonic exploration beyond what would normally be available with a single mixdown tape deck.

#### To configure the Ampex ATR-102 Master Tape LUNA Extension as pre or post fader:

1.  Click in the Master Tape row and assign the ATR-102 LUNA Extension to a bus or the Main track,
2.  Hover over the Master Tape slot, and click on •••.
3.  To insert the tape deck pre-fader, select Insert Pre-Fader. An indicator to the left of the option indicates that the option is enabled.
4.  To insert the tape deck post-fader, deselect Insert Pre-Fader.

<div class="wysiwyg-text-align-center" title="Attachment">

![master-tape-hover-options.png](Mixing%20with%20LUNA%20Extensions_assets/66db8e70873a6316fb537806e3303ef47e539e29.png)

</div>

You can also switch between the pre and post fader tape deck location by clicking the option in the Master Tape Browser.

![atr-102-pre-post-fader.png](Mixing%20with%20LUNA%20Extensions_assets/018fa515e6caf4589db01c23573beb3507e8c9d8.png)

------------------------------------------------------------------------

# Assigning Default Extensions

By default, LUNA assigns Extensions that you own or are currently demoing to supported tracks. For example, if you own or are demoing Studer A800 Tape, it is automatically assigned to all audio and instrument tracks.

You can change the default Extensions (on a per-session basis) by simply selecting a different Extension, or no Extension, in the New Tracks and Create Bus dialogs. You can enable or disable automatic Extension assignment in LUNA Settings, under Options \> Miscellaneous \> Assign Default Extensions.

**Note:** Extensions are not automatically assigned in a session created from a template. For full control over which Extensions are assigned on a per-track basis, create a custom template.

 

<span class="wysiwyg-font-size-small">251229</span>

