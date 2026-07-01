---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/25349509957396-Input-Channel-Strips.html'
converted_at: 2026-05-31T13:44:48Z
tool: htmlq+pandoc
title: 'Input Channel Strips'
word_count: 475
---

# Input Channel Strips


Each UAD Console channel input strip, as illustrated below, controls a corresponding Apollo hardware input. The output of all UAD Console channel inputs are always routed to UAD Console’s monitor outputs (except when muted). Inputs can be optionally routed to other outputs via Flex Routing (rack models only) or the Cue Outputs window.

![input-strip-callouts.png](Input%20Channel%20Strips_assets/387173a2bf2dfd7dba4920e44452996f8cd237ce.png)

UAD Console’s channel input strips are essentially the same for all inputs, however there are some differences among the analog and digital inputs as noted below.

# Signal Flow

Audio signals in a UAD Console channel flow through the inserts serially from top to bottom. Therefore, if more than one plug-in is inserted in a channel, the location of a plug-in within the inserts can impact the sound of the channel. Plug-ins can be reordered by dragging them to change the serial processing order.

# Input Types

UAD Console has analog, digital, and virtual inputs. The controls that are available in each strip depend on the type of input.

## Analog Inputs

### <span style="color: #434343;">Preamp Inputs (except Apollo 16, x16)</span>

Each of Apollo’s preamp channels have multiple analog inputs (mic, line, and/or Hi-Z) that can be selected with the preamp controls.

The preamp channels are switched between mic and line inputs manually via UAD Console or Apollo’s front panel. Channels are automatically switched to Hi-Z inputs when a ¼” mono (tip-sleeve) cable is connected to Apollo’s front panel Hi-Z input jacks.

### <span style="color: #434343;">Line Inputs</span>

The analog line inputs reflect the number of A/D conversion channels that are available on the connected Apollo model(s).

## Digital Inputs

**Note:** Apollo Solo does not feature digital inputs.

### <span style="color: #434343;">Apollo, Apollo 8, x8, x6, x4</span>

The eight ADAT (TOSLink) and two S/PDIF (coaxial stereo left/right) input channels work just like the analog inputs, except they don’t have the extra preamp and reference level settings that are only available on the analog inputs.

### <span style="color: #434343;">Apollo 8p, x8p, Twin</span>

The digital TOSLink inputs can accept ADAT or S/PDIF. The number of input channels change to reflect the digital input type currently in use (the digital input preference is set in the UAD Console Settings window).

The digital inputs work just like the analog inputs, except they don’t have the extra preamp and reference level settings that are only available on the analog inputs.

### <span style="color: #434343;">Apollo 16, x16</span>

UAD Console has two AES/EBU inputs (left and right). MADI inputs, if present on the hardware, are not functional.

### <span style="color: #434343;">Virtual Inputs</span>

The virtual input channels in UAD Console do not reflect Apollo’s hardware inputs. Instead, they receive digital signals from DAW outputs via Apollo’s device drivers, enabling Realtime UAD Processing on any DAW output. This feature is especially useful when playing virtual software instruments live through UAD plug-ins because it reduces I/O buffering latency.

