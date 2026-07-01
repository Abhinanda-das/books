---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/25403573794836-Hardware-Settings-Panel.html'
converted_at: 2026-05-31T13:44:49Z
tool: htmlq+pandoc
title: 'Hardware Settings Panel'
word_count: 4434
---

# Hardware Settings Panel


The Hardware panel is where Apollo's system-level audio interface I/O settings such as sample rate, clock source, and output reference levels are configured. These settings are used by DAW applications when they are configured to use Apollo as the audio interface. Even when UAD Console is not open, these settings are stored by the Apollo drivers for use by other host applications.

![](Hardware%20Settings%20Panel_assets/e3a8087aa0709e2d6b826b85e3aa3fb8a896eb75.png)

*The Hardware panel as displayed with multiple Apollo devices*

# Sample Rate & Clock Settings

Behavior and control of these two settings depend on the operating environment:

**Without a DAW –** Sample Rate and Clock Source settings define the active sample rate and clock source for Apollo when a DAW is not used (when UAD Console is the only host application).

**With a DAW –** These settings are usually changed within the DAW application's audio preferences.

**Tip:** These settings can also be viewed and changed via UAD Console's Info Bar.

# Sample Rate

This setting defines the sample rate that is used for Apollo A/D and D/A conversion and UAD Plug-Ins processing. When using UAD Plug-Ins, higher sample rates require more UAD DSP resources.

**Important:** When the Clock Source parameter is set to use any external clock source, the sample rate must be manually set to match the sample rate of the external clock.

**Note (Apollo Twin/Twin X, x4, 8p, x8p Gen 1 and Gen 2):** If the current digital input setting is S/PDIF and the sample rate is changed to a rate higher than 96 kHz, the clock source is changed to Internal and the S/PDIF inputs are no longer available.

## Hardware Clicks

When the sample rate is changed, hardware relays that mute the outputs are temporarily engaged to prevent audio artifacts. This action causes an acoustic clicking sound that can be heard within the hardware. These clicks are by design and can be safely ignored.

**Note:** Hardware clicks when changing samples rates are not heard with first-generation (silver) Apollo models, which do not feature hardware relay muting.

# Clock Source

This setting determines the master clock source for A/D and D/A conversion. The available values are:

**Apollo Solo –** Internal only

**Apollo desktop models –** Internal clock or external clock from S/PDIF or ADAT

**Apollo rack models with preamps –** Internal clock or external clock from S/PDIF, ADAT, or Word Clock

**Apollo 16 / x16 –** Internal clock or external clock from AES/EBU or Word Clock

If the Clock Source setting is not set to Internal and the external clock signal is not detected, then the text in the Clock Source display is RED (if this occurs, verify connections and external clock device settings).

**Note:** Only one device in a system can be the master clock. This setting must match the host DAW setting or audio glitches and/or distortion could occur.

# Digital Mirror

This setting configures the S/PDIF outputs (Apollo, x4, 8/x8, 8p/x8p Gen 1 and Gen 2) or AES/EBU outputs (Apollo 16) to mirror the Monitor 1 & 2 outputs. This feature is typically used when connecting to the stereo inputs of other devices with digital inputs such as a speaker system, stereo recorder, or external D/A converter.

When Digital Mirror is ON, the Monitor Level knob controls both the digital output level and the analog monitor output level (these digital outputs are post-fader when mirrored).

This setting is unavailable with Apollo Twin, which does not feature digital outputs.

## Digital Mirror Notes

- When Digital Mirror is ON, any DAW outputs and/or UAD Console aux outputs that are routed to these digital ports will not be heard, because these digital ports are switched to output the signals at the monitor outputs instead.
- When ALT monitoring is active, the ALT outputs are not routed to these digital ports (the monitor outputs are mirrored, not the monitor bus).

# Buffer Size (Windows)

**Note:** This setting is available on Windows systems only. On Mac systems, the hardware I/O buffer size is set within the DAW application.

This setting determines the hardware I/O buffer size used by a DAW. As values are decreased, DAW throughput latency decreases, but the computer's CPU load increases. Conversely, as values are increased, DAW throughput latency increases, and the computer's CPU load is reduced. For related information, see Latency Basics.

Available buffer size values are dependent on the current Sample Rate value. If values in the Buffer Size menu are gray and cannot be selected, change the Sample Rate value.

**Note:** If audio artifacts occur during DAW playback (clicks, pops, stuttering, etc), the buffer size may need to be increased.

**Important:** Buffer Size applies to use with a DAW only. It has no effect on UAD Console's hardware monitoring features or Realtime UAD Processing within UAD Console.

# Input Delay Compensation

<div>

<table style="margin-right: auto; margin-left: auto;">
<tbody>
<tr>
<td colspan="2" style="text-align: center;"><strong>Input Delay Compensation Values</strong></td>
</tr>
<tr>
<td style="text-align: center;"><strong>Setting Name</strong></td>
<td style="text-align: center;"><strong>Extra Delay (samples)</strong></td>
</tr>
<tr>
<td style="text-align: center;">Off</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">Short</td>
<td style="text-align: center;">100</td>
</tr>
<tr>
<td style="text-align: center;">Medium</td>
<td style="text-align: center;">200</td>
</tr>
<tr>
<td style="text-align: center;">Medium-Long</td>
<td style="text-align: center;">300</td>
</tr>
<tr>
<td style="text-align: center;">Long</td>
<td style="text-align: center;">1000</td>
</tr>
</tbody>
</table>

</div>

Input Delay Compensation maintains phase alignment across UAD Console's analog and digital inputs when certain UAD plug-ins are used. 

When enabling Input Delay Compensation, it's usually best to start with the Short value (100 samples) to minimize latency. The default value is Medium.

**Note:** Changes to this setting do not take effect until the DAW is quit.

### Input Delay Compensation Exceeded Dialog

![](Hardware%20Settings%20Panel_assets/e62e651e395f3dad6fe33ab2c30a13b329ba4a53.png)

A dialog will appear in UAD Console if the compensation amount is exceeded on a channel. If this occurs, either increase the IDC value or reduce upsampled plug-ins usage on the channel to maintain phase alignment.

# Cue Bus Count

The number of active cue mix buses is changed with this setting. Increasing the Cue Bus Count increases the number of cue mix buses (and associated cue sends and returns) available within UAD Console and the DAW.

Between two and four cue buses can be set. The default value is two with Apollo and four with Apollo 16. This setting is unavailable with Apollo Twin, which always features two cue mix buses (HP and Line 3/4).

**Note:** Cue buses 3 and 4 are unavailable at sample rates of 176.4 kHz and 192 kHz.

# ALT Count

This setting determines the number of ALT (alternate) monitor outputs that are available within UAD Console. Between zero and two ALT outputs can be set (one maximum with Apollo Twin / Twin X). The default value is zero.

**Important:** Increasing the ALT count overrides any other assignments using Line outputs 1, 2 (ALT count of 1) and Line outputs 1, 2, 3, 4 (ALT count of 2).

# FCN Switch Assign

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">Apollo X rack models and Apollo 8/8p feature an assignable function (FCN) switch on the hardware front panel that can be configured to control one of three monitoring functions. The FCN switch LED illuminates when the function is active.</span>

The function of the switch is configured with this menu. The available functions are:

**ALT 2 –** Selects the Alternate 2 monitor speakers. The monitor signals are routed to outputs 3 & 4 instead of the main monitor outputs, and the monitor level indicator ring is yellow instead of green when ALT 2 is active.

**Note:** ALT COUNT must be set to 2 to use the FCN switch for ALT 2 switching.

**MONO –** Sums the left and right channels of the stereo monitor mix into a monophonic signal. The monitor level indicator ring flashes when MONO is active.

**DIM –** Attenuates the signal level at the monitor outputs by the dB amount set in UAD Console's Control Room strip. The monitor level indicator ring flashes when DIM is active.

**TALKBACK –** Activates the talkback mic and the DIM function. Talkback is active when the button is lit. Press and release the button quickly to latch talkback ON. To momentarily activate the function and deactivate when the button is released, press for longer than 0.5 seconds. The Monitor Level Indicator ring flashes when talkback is active.

**NONE –** The FCN switch is unassigned.

**Note:** When more than one Apollo interface is connected in a multi-unit configuration, the FCN switch is operable on the designated monitor unit only.

**Note:** FCN Switch Assign is available on these Apollo models.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; vertical-align: top;"><p>Apollo 8<br />
Apollo 8p<br />
Apollo x6<br />
Apollo x6 Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x8<br />
Apollo x8 Gen 2<br />
Apollo x8p<br />
Apollo x8p Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x16<br />
Apollo x16 Gen 2<br />
Apollo x16D</p></td>
</tr>
</tbody>
</table>

# Headroom

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">Headroom sets the maximum analog signal level for the line inputs, line outputs, and monitor outputs of connected Apollo X rack models. The available values are +20 dBu (the default value) or +24 dBu.</span>

+24 dBu operation is typically used when interfacing with professional audio equipment such as large format consoles, analog tape machines, and similar devices that require higher analog I/O signal levels.

When set to +24 dBu, the line inputs require 4 dB more input signal to achieve 0 dBFS A/D conversion. Similarly, the line and monitor outputs are 4 dBu hotter when Headroom is set to +24 dBu.

### +24 dBu Compatibility with +20 dBu Sessions

When a DAW session is created and/or saved with +20 dBu headroom and that DAW session is subsequently played back when Apollo X is set to +24 dBu headroom, any previously-recorded tracks, and UAD plug-ins applied to those tracks, will sound identical as when set to +20 dBu headroom; the signal output levels will simply be 4 dBu hotter.

However, when recording new tracks with +24 dBu headroom using Realtime UAD Processing through UAD Console into a DAW session that was previously saved with +20 dBu headroom, the UAD plug-ins in UAD Console (but not the DAW) may need to be adjusted to achieve the same sound. For example, the UAD plug-ins in UAD Console may need an input level that is 4 dBu hotter for the same "pushed" sound.

## Headroom Notes

- The Headroom menu is visible only when one or more Apollo X rack units are connected to the system.
- The Headroom setting does not change Mic, Hi-Z, or digital signal levels.
- The operating headroom for all Apollo models except Apollo X rack models is always +20 dBu. The operating headroom for Apollo X rack models can be switched between +20 dBu and +24 dBu.

**Note:** Headroom is available on these Apollo models.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; vertical-align: top;"><p>Apollo x6<br />
Apollo x6 Gen 2<br />
Apollo x8</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x8 Gen 2<br />
Apollo x8p<br />
Apollo x8p Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x16<br />
Apollo x16 Gen 2<br />
Apollo x16D</p></td>
</tr>
</tbody>
</table>

# Monitor Mode

**Note:** Monitor Mode is available on these Apollo models.

This menu enables Apollo X surround sound and specifies the surround mode. For details, see [Apollo X Surround Sound.](https://help.uaudio.com/hc/en-us/articles/26817449653012)

**Note:** Monitor Mode is available on these Apollo models.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; vertical-align: top;"><p>Apollo x6<br />
Apollo x6 Gen 2<br />
Apollo x8</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x8 Gen 2<br />
Apollo x8p<br />
Apollo x8p Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x16<br />
Apollo x16 Gen 2<br />
Apollo x16D</p></td>
</tr>
</tbody>
</table>

## Devices Column

![](Hardware%20Settings%20Panel_assets/019f1800c91f2d26c35b60894576f7c540c2a067.png)

This column lists all Apollo devices in the system. It has five functions:

1.  Selects current unit to see device-specific options
2.  Designates the monitor unit in multi-unit setups
3.  Indicates which unit(s) are currently online
4.  Indicates the Talkback unit (if available)
5.  Adds devices for offline configuration

## Select Device

Clicking a unit in the column reveals its device-specific settings in the Options Column.

## Device Letter

Each unit in the Devices list is designated with a sequential letter. These letters are used in the I/O Matrix Panel when multi-unit cascading to differentiate between Apollo devices. The device letters cannot be modified.

## Device Color

Each unit in the Devices list is color coded for enhanced identification. These colors are used in the Meter Bridge and the I/O Matrix Panel when multi-unit cascading to differentiate between devices. The device colors cannot be modified.

## Designated Monitor Unit

In multi-unit configurations, the device at the top of the column is the designated monitor (master) unit. The monitor unit is indicated by a speaker icon between the device letter and the device name. To change the monitor unit, drag a unit to the top of the device column.

For related details, see [Multi-Unit Cascading](https://help.uaudio.com/hc/en-us/articles/26817742017684).

**Note:** This operation reconfigures the system. There may be a delay before the operation is completed.

## Add Device

![](Hardware%20Settings%20Panel_assets/531b45d9b47e075fcef2bf0fb5b088c7d0004984.png)

If there are less than four devices in the column, unit(s) can be manually added for offline configuration by clicking the "+" button (below the devices in the column) to present the Add Device popover. Click a device in the menu to add it to the Device Column.

**Tip:** When a device is properly connected and powered, it is automatically detected and added to the device list.

**Note:** Add Device does not appear if you have four or more Apollo devices in the Devices column. 

## Options Column

Selecting a unit in the Devices column reveals its device-specific settings in the Options column. A device is currently selected when its text is not dim.

**Note:** Settings in the Options Column apply only to the specific unit currently selected in the Devices Column.

![](Hardware%20Settings%20Panel_assets/fc46cfd973b8dfac9ea8023793ae7543b7b09c1c.png)

![](Hardware%20Settings%20Panel_assets/91db7ee82045381ddb70189b5978a89e06065731.png)

*Device options as displayed when Apollo x8p selected (top) and Apollo x4 selected (bottom)*

## Device Name

Apollo's default device name can be changed. The device name is displayed in the "Connecting to Apollo" window that appears briefly during system connection, in the I/O Matrix panel settings, and optionally in the Meter Bridge.

**Note:** Text in this field cannot be modified when the device is offline.

## Identify

Clicking the Identify switch will cause the currently selected unit's front panel LEDs to flash in a pattern. This feature is typically used with multi-unit systems to distinguish units when making I/O connections.

**Note:** If the device is offline, this switch displays REMOVE instead.

## Remove

When a device is offline, it can be removed from the devices list. To remove an offline device, select the unit in the DEVICES column, then click the REMOVE switch in the OPTIONS column.

**Note:** If an expander unit is powered down or disconnected from the system, the expander unit must be removed before the sample rate can be changed to 176.4 kHz or 192 kHz.

## Monitor Level

This menu switches the operating level of the monitor outputs. Available values depend on which model is the designated monitor unit.

**Note:** This setting is unavailable with the original (silver) Apollo, which does not feature an adjustable monitor operating level.

**Apollo X rack models (Gen1 & Gen2) –** Available selections are +4 dBu and -10 dBV.

**Apollo models except Apollo X rack –** Available selections are 20 dBu and 14 dBu.

**Apollo x16D -** Available selection of +4 dBu and -10 dBV applies only to analog I/O and is always applied to Mon L-R analog I/O, regardless of the monitor mode.

## Output Reference Levels

These menus set the reference level for the line outputs. The number of menus displayed depends on the currently connected Apollo hardware (for example, Apollo 16, which features more outputs, will display more output menus).

The line output reference levels can be set to –10 dBV or +4 dBu in adjacent pairs. The value is usually set to match the nominal input level of devices connected to these outputs (a setting of +4 dBu outputs a higher signal level than –10 dBV).

**Tip:** Input reference levels for the analog line inputs are set in UAD Console's channel input strips.

## Digital Input

**Note:** Digital Input is available on these Apollo models.

This menu selects the digital input type (ADAT or S/PDIF) to be used by the TOSLINK optical connector and UAD Console's digital input channels.

Optical S/PDIF digital input is supported at sample rates up to 96 kHz. If the current setting is ADAT and the sample rate is higher than 96 kHz, when S/PDIF input is selected, the clock source is changed to Internal and the S/PDIF inputs are no longer available.

**Note:** Digital Input is available on these Apollo models.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; vertical-align: top;"><p>Apollo 8p<br />
Apollo x8p<br />
Apollo x8p Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo Twin<br />
Apollo Twin X<br />
Apollo Twin X Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x4<br />
Apollo x4 Gen 2</p></td>
</tr>
</tbody>
</table>

## Digital Output

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">This menu selects the digital output type (ADAT or S/PDIF) to be used by the TOSLINK optical connector and UAD Console's digital outputs channels.</span>

Optical S/PDIF digital output is supported at sample rates up to 96 kHz. If the current setting is ADAT and the sample rate is higher than 96 kHz, when S/PDIF input is selected, the clock source is changed to Internal and the S/PDIF outputs are no longer available.

**Note:** Digital Output is available on these Apollo models.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; vertical-align: top;"><p>Apollo 8p<br />
Apollo x8p<br />
Apollo x8p Gen 2</p></td>
<td style="text-align: center; vertical-align: top;"><p>Apollo x4<br />
Apollo x4 Gen 2</p></td>
</tr>
</tbody>
</table>

## Monitor Output Gain

**Note:**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> In multi-unit configurations, this setting is available for the designated monitor unit only.</span>

By default, monitor output levels are continuously variable. However, the monitor outputs can be set to completely bypass the monitor level circuitry and operate at a fixed reference level.

This feature routes the signal directly from the D/A converters to the monitor outputs when level control is not needed (for example, when connecting the monitor outputs to an external monitor controller). Two settings are available:

**On –** The monitor controls operate normally

**Bypass –** The monitor controls and associated circuitry are bypassed, and:

![](Hardware%20Settings%20Panel_assets/2b3a47979f9edf26b3fc8f018f0e5ef038aae7e0.png)

- The Monitor Level cannot be adjusted
- The Monitor Level Indicator ring is solid green
- The Monitor Level Value display changes to "BYP"
- ALT monitoring and assignable FCN switch features are unavailable
- Signals at the Monitor Outputs are output at line level (without attenuation)

**Note:** Monitor Output Gain is available on these Apollo models.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center; width: 50%;"><p>Apollo 8<br />
Apollo 8p<br />
Apollo 16 MkII</p></td>
</tr>
</tbody>
</table>

## Line Input Gain

By default, line inputs on preamp channels are routed through the channel's preamp so the line input level can be adjusted with the Gain knob. However, preamp channel line inputs can be individually set to completely bypass the channel's preamp circuitry and instead operate at a fixed reference level.

This feature routes the preamp channel's line input signal directly into the D/A converter for the purest path when additional gain is not needed (for example, when connecting external mic preamps to preamp channel line inputs). Two settings are available:

**On –** The line input is routed through the channel's preamp

**Bypass –** The preamp and associated circuitry are bypassed, and:

- The Preamp Gain Indicator ring for the channel is solid green
- If a Unison plug-in is in the channel's dedicated Unison insert, the Unison plug-in is bypassed

**Note:** Line Input Gain availability depends on the Apollo model.

<table style="border-collapse: collapse; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<tbody>
<tr>
<th colspan="2" style="text-align: center; width: 25%; vertical-align: top;"><strong>Available<br />
</strong></th>
<th colspan="2" style="text-align: center; width: 25%; vertical-align: top;"><strong>Unavailable<br />
</strong></th>
</tr>

<tr>
<td style="text-align: center; width: 25%; vertical-align: top;"><p>Apollo 8<br />
Apollo 8p<br />
Apollo x6<br />
Apollo x8<br />
Apollo x8p<br />
<br />
</p></td>
<td style="text-align: center; width: 25%; vertical-align: top;"><p>Apollo x6 Gen 2<br />
Apollo x8 Gen 2<br />
Apollo x8p Gen 2<br />
Apollo Twin X Gen 2<br />
Apollo x4 Gen 2</p></td>
<td style="text-align: center; width: 25%; vertical-align: top;"><p>Apollo FireWire<br />
Apollo 16 FireWire<br />
Apollo x16<br />
Apollo x16 Gen 2<br />
Apollo x16D<br />
Apollo Twin</p></td>
<td style="text-align: center; width: 25%; vertical-align: top;"><p>Apollo Twin X<br />
Apollo x4 <br />
Apollo Twin USB<br />
Apollo Twin X USB<br />
Apollo SOLO<br />
Apollo SOLO USB<br />
Arrow</p></td>
</tr>
</tbody>
</table>

## Channel DSP Pairing

Channel DSP Pairing allows multiple UAD plug-ins that are inserted in a single UAD Console input channel strip to span across two paired DSP cores. This feature effectively doubles the amount of Realtime UAD Processing DSP loading that is available on a single Apollo input.

**Note:** Channel DSP Pairing changes the way available DSP resources are allocated. The feature does not increase the total amount of available DSP.

When enabled (the default setting), Channel DSP Pairing is automatic. Simply insert UAD plug-ins in UAD Console inputs as usual, and input DSP resources are automatically distributed across DSP pairs as efficiently as possible.

**Note:** Individual UAD plug-ins must fit within a single DSP core, even when Channel DSP Pairing is available. A single UAD plug-in cannot span across paired DSPs.

A maximum of two DSP cores can be paired with a single Apollo input. More than one DSP pair can be allocated, so multiple Apollo inputs can take advantage of the feature. The Channel DSP Pairing concept is illustrated below.

![](Hardware%20Settings%20Panel_assets/5dcd58c02bee22a7cbf159b79e76ccb7367d4b5c.png)

 

Conceptual Channel DSP Pairing illustration. Note that the signal from an input is output from its paired DSP.

### Channel DSP Pairing Example

If an additional UAD plug-in inserted on a UAD Console input channel strip that doesn't fit on the first DSP core (if the combined DSP load exceeds 100%), the plug-in(s) will load on a paired DSP core, as illustrated below.

In this specific example, the Fender '55 Tweed Deluxe plug-in DSP core load is 70% (at 44.1 kHz). The Korg SDD-3000 is also loaded on the same input, but since its load is 35% (and the combined load exceeds 100%), Channel DSP Pairing automatically loads the second plug-in on the paired DSP.

![](Hardware%20Settings%20Panel_assets/1eaa5081f5c59f539668753bcd209c16c5c27865.png)

 

With Channel DSP Pairing, more than one DSP-intensive UAD plug-in can be loaded on the same UAD Console input

### Complex Channel DSP Pairing

Building on the previous example, the diagram below illustrates how more than one DSP pair can be used to create simultaneous plug-in chains that would not be possible without Channel DSP Pairing.

In this example, Input 1 has an electric guitar plug-in chain (Fender + Korg) using one DSP pair, while Input 2 has a vocal mic plug-in chain (Neve + Teletronix) using a second DSP pair. A third DSP pair uses the remaining DSP on core two before pairing to the third DSP core.

![](Hardware%20Settings%20Panel_assets/fe386e13a20bd28a7f3fb987b91be56f2d574186.png)

 

*Complex Channel DSP Pairing example*

### Control Elements

Channel DSP Pairing is controlled by a row of buttons beneath the control name. To change DSP allocation values, click a button in the row. The feature is active when DSP PAIRS displays a value greater than 0.

As the DSP PAIRS value is increased, the VIRTUAL CHANNELS value is decreased. This reciprocal action sets how Apollo's internal DSP resources are allocated.

 

![](Hardware%20Settings%20Panel_assets/1ef297a75c2ee33d76ed4343466c712a8984e934.png)

*Channel DSP Pairing control*

### Available DSP Pairs

The number of available DSP pairs is adjustable. Apollo rackmount models can be set to a maximum of four available DSP pairs (default value of 2), while Apollo Twin models have a maximum of two available pairs (default value of one).

**Notes**

- On all models, decreasing Virtual channels conserves DSP.
- On Apollo SOLO models, Channel DSP Pairing is not available because they contain only one DSP. 

![](Hardware%20Settings%20Panel_assets/a0f05f7d327717d3706c6aeea347c4ceae53e78f.png)

*Channel DSP Pairing control as it appears with Apollo Twin (left) and Apollo rackmount models (right)*

### Relationship to Virtual Channels

When Channel DSP Pairing is enabled (when DSP PAIRS displays a value greater than 0), the number of available Virtual I/O channels is reduced.

Virtual channels that are disabled by the DSP allocation are removed from UAD Console's main window. Disabled Virtual channels appear in gray italic text in the I/O Matrix, indicating that they are inactive.

**Tip:** Reducing the number of active Virtual I/O channels also conserves DSP used by Apollo's internal digital mixer, which can be useful when you need just a bit more DSP.

### Channel DSP Pairing Latency

When Channel DSP Pairing is active, input latency is slightly increased across all Apollo inputs. The amount of latency increase depends on the Apollo model:

- All Apollo rack and desktop models (except X Series HEXA models): 69 samples
- All Apollo X Series HEXA models: 74 samples
- If a HEXA DSP core interface model (e.g., Apollo x8) is connected in multi-unit configurations, input latency is increased by 74 samples across all connected models.

**Note:** Input latency is only increased when DSP is actually paired, even if DSP PAIRS is set to a non-zero value.

### Channel DSP Pairing Notes

- Channel DSP Pairing values are saved within individual UAD Console sessions files. Unlike other UAD Console hardware settings, it's not a global setting.
- Channel DSP pairing is unrelated to UAD plug-ins inserted in the DAW, where UAD plug-ins automatically load on any available DSP.
- In multi-unit configurations, each Apollo unit has its own Channel DSP Pairing setting, and DSP can only be paired within an individual unit.
- Channel DSP Pairing applies to internal DSP with Apollo models only. It does not apply to UAD-2 DSP Accelerator models or Apollo Solo.
- Channel DSP pairing is unavailable on Auxiliary and Talkback channels, nor at sample rates of 176.4 and 192 kHz.

