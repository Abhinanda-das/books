---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/25351484855828-Monitor-Mix-Controls.html'
converted_at: 2026-05-31T13:44:49Z
tool: htmlq+pandoc
title: 'Monitor Mix Controls'
word_count: 1755
---

# Monitor Mix Controls


The monitor mix controls within each input channel strip are for adjusting the signals at Apollo’s monitor outputs.

![](Monitor%20Mix%20Controls_assets/694993f423ab4229f8115c7afeb552b06ca9fec4.png)

*The Monitor Mix Controls*

# Input Pan

This control adjusts the input’s position in the stereo panorama of the monitor mix bus.

## Stereo Input Pan

When the input is stereo linked, two pan knobs appear for the channel enabling independent panning for both the left and right channels. When stereo link is activated, the default position of the dual pan knobs are hard left/right.

![](Monitor%20Mix%20Controls_assets/4ff84daf938724d87983b1d5b4c21a30392c0024.png)

*Pan with channels unlinked (left) and linked (right)*

# Input Solo

Solo mutes all input signals, except for any inputs in solo mode. Solo is used to hear individual channels in the monitor mix without having to modify other channels.

**Note:** Input solo does not affect the channel’s cue sends, which are pre-fader.

Click the switch to toggle the solo state. The channel is in solo mode when its solo switch is highlighted in yellow. Note that activating mute has no effect if the channel is in solo mode.

![](Monitor%20Mix%20Controls_assets/be2fb45f14242e60e5960eb8f501dcafde4ac300.png)

*Inactive solo and mute switches*

# Input Mute

Mute prevents the input channel’s signal from being routed to the monitor mix bus (and aux buses that are in POST mode), but not the cue mix buses.

Click the button to toggle the mute state. The channel is muted when its mute switch is highlighted in red.

**Tip:** Option-click (macOS) or Alt-click (Windows) the mute button to toggle mute on all input channels.

If you enable pre-fader metering in Settings \> Options, the input meter remains active when the channel is muted for a visual reference that there is still a signal coming into the channel, even though it isn’t heard in the monitor mix. When post-fader metering is enabled, you do not see meter levels on muted tracks.  

**Note:** Input mute does not affect the channel’s cue sends, which are pre-fader. All cue sends have their own mute switch.

# Input Fader

This is the channel’s main signal level control for the monitor mix. Changes to this control are reflected in the channel’s level meter.

The input fader adjusts the channel’s level in the monitor mix bus (the monitor outputs) and the aux mix buses (when set to POST mode), but not the cue mix buses.

**Tip:** For finer control resolution, hold the Shift key while adjusting faders.

## Fader Scale

The numerical labels next to the fader represent the amount of gain or attenuation applied by the fader. Up to 12 dB of gain above 0 dB is available. A value of 0 dB represents unity gain (no gain or attenuation).

## Fader Value

The input fader’s current setting is displayed beneath the input meter. 

**Tip:** Double-click the fader setting to open the volume popover. To specify a fader value, type the value, then click OK.

![](Monitor%20Mix%20Controls_assets/b1d2fdbba693700137df1f756d6181efce11ed7e.png)

# Copy Mix

All channel fader and pan values for all inputs (the entire monitor mix) can be copied simultaneously to any send or cue mix bus.

To copy the monitor mix to a send mix bus, right-click (or Ctrl-click) any channel fader to display the copy mix menu, then select a destination bus for the mix.

![](Monitor%20Mix%20Controls_assets/ef53e124b75ed04c7f766972b36c7c9f1c090a2e.png)

# Input Meter

![](Monitor%20Mix%20Controls_assets/96418e4ea3f9b46255b61c64aae49c223b7a6a8b.png)

Pre/Post metering preference

The input meter displays the signal level of the channel after UAD plug-in processing in the inserts. Depending on the state of the METERING option in the Display panel in Settings \> Options (either pre-fader or post-fader), this meter will display the level going into the monitor mix bus (post-fader/post-inserts), or the level at the channel’s hardware input (pre-fader/post inserts).

**Tip:** When recording into a DAW, it’s typically best to set metering to pre-fader so meters accurately represent the signal level at the DAW inputs.

You can also set pre-fader or post-fader metering by right-clicking/Ctrl-clicking in the meter display, and choosing Pre-Fader or Post-Fader under Metering.

![](Monitor%20Mix%20Controls_assets/23b4dbe283058678439c4de7cbb5dd8f78a89e76.png)

 

## Input Level Scale

The numerical labels represent digital signal levels. “0” represents 0 dBFS (digital full scale, the maximum level before undesirable A/D clipping). If the level at the Apollo input exceeds 0 dBFS, the meter’s clip indicator illuminates. 

**Important:** If clipping occurs, reduce the preamp gain, the output level of the device feeding the input, or the output gain(s) of UAD plug-in processing in the inserts to eliminate undesirable A/D clipping distortion.

## Peak Hold

The input meters also have a peak hold feature, which holds signal peak values for a specified period of time. The clip and peak hold times can be adjusted in the Display panel in Settings \> Options.

# Rename/Link Popover

The Rename/Link popover is used for customizing input labels and stereo linking adjacent channels. Click the channel name at the bottom of the UAD Console window to open the popover for a channel or linked pair. 

![](Monitor%20Mix%20Controls_assets/a909fbc7d5741afd86031cdf64e90a37e0fb72d3.png)

*The Rename/Link popover*

# Input Label

The input labels are displayed beneath the channel’s fader and meter. Each label can be customized for convenient input identification. By default, the name of the Apollo hardware input.

![](Monitor%20Mix%20Controls_assets/2d01bc1e4624c601fe732726fceb3f5feff30882.png)

Input labels showing several customized input names

## Input Label Menu

![](Monitor%20Mix%20Controls_assets/40b99433b88c524ed5c0370761518f738fddc017.png)

The Input Label Menu contains the same functions as the Rename/Link window, and also the ability to hide the input from view, Isolate the channel, and load Channel Presets. To display the Input Label Menu, right-click or Control-click any Input Label.

**Tip:** To re-show an input hidden via this menu, use the Show/Hide Inputs function.

## To customize a channel input name:

1.  Click an input label or choose “Rename” from the Input Label Menu. The Rename/Link popover window appears.
2.  Type a custom name for the input.
3.  Press Return/Enter or click the close button.

## To return to the default name:

1.  Click an input label or choose “Rename” from the Input Label Menu. The Rename/Link popover window appears.
2.  Press the Delete key to remove the customized text from the NAME field.
3.  Press Return/Enter or click the close button.

## Input label Notes

- To identify the hardware input when an input name is customized, click the input label. The hardware input name appears at the top of the popover window.
- Input labels are stored in UAD Console session files and the UAD Console Recall plug-in.
- Auxiliary return labels cannot be customized.
- Custom input labels are visible within UAD Console only.
- Input labels are not displayed within a DAW.

**Tip:** Driver I/O labels are displayed in some DAWs and can be customized separately in Settings \> I/O Matrix.

# Show/Hide Inputs

UAD Console can hide any input channel strip from view. This feature reduces the need for horizontal scrolling when the UAD Console window is narrow (when all visible channels don’t fit) and can reduce visual distractions when there is no need to see a particular input.

## How to Use Show/Hide Inputs

1.  Either choose “Show/Hide Channels” from the View Menu, or use the keyboard shortcut (Mac: ⌘+I or Win: Ctrl+I). Modifier icons appear on all Input Labels (see [Mixer Navigation Modifiers](https://help.uaudio.com/hc/en-us/articles/25348282201364) for related details).
2.  Click or swipe across the Input Labels. The modifier toggles between green and gray. The input will be shown when its modifier is green, and hidden when gray.\
    ![](Monitor%20Mix%20Controls_assets/2c5a47545312e8414bc85765e4f7522415c98fd2.png)
3.  Click the DONE switch in the Mixer Navigation area, or use the keyboard shortcut (Mac: ⌘+I or Win: Ctrl+I). The inputs with gray modifiers are hidden. To bring hidden inputs back into view, repeat the procedure.

![](Monitor%20Mix%20Controls_assets/7cdd4026c6e659327913c3c144558aab8cea5f41.png)

## Show/Hide Input Notes

- A minimum of one input channel must be shown.
- All input channels remain active even if they are hidden from view.
- Show/Hide status is stored in UAD Console session files and the UAD Console Recall plug-in.
- The Show Aux Returns switch is available to show/hide the aux return strips.

# Stereo Link

![](Monitor%20Mix%20Controls_assets/06970b712a6abca6e757eefc83d4135d724f05be.png)

Adjacent channels (1+2, 3+4, etc) can be linked to create stereo input pairs. When channels are linked as a stereo pair, any control adjustments will affect both channels of the stereo signal identically.

**Note:** Only the same type of inputs can be linked (Mic+Mic or Line+Line), and Hi-Z inputs cannot be linked.

## Stereo Link Activation

 

<div>

|  |  |
|----|----|
| ![channels-unlinked.png](Monitor%20Mix%20Controls_assets/176af6f5e0fd34c876f7c43fd7b0191299b329a6.png) | ![channels-linked.png](Monitor%20Mix%20Controls_assets/27fc0b38364dcca3c96e581200daa3245b15b8f3.png) |

</div>

*Before and after engaging stereo LINK*

Stereo pairs are created by activating LINK within the Rename/Link Popover. For preamp channels (Apollo and Apollo Twin), activating LINK performs the exact same function pressing the LINK button on Apollo’s top panel. 

**Tip:** Option-click the LINK button to stereo link all channels.

#### When Link is activated:

- The LINK switch is lit instead of gray.
- One set of controls is available for the stereo channel (except pan, as noted below).
- All current control settings of the left channel are copied to the right channel (except pan, as noted below).
- All inserted plug-ins in the left channel are converted to stereo (parameter values are retained).
- The input pan knob changes to dual pan knobs.
- Pan values are forced to hard left and hard right.
- The send pan knobs are hidden (pans are forced to hard left/right with stereo sends).
- The input level meter changes to a stereo meter.
- The custom input names revert to default input names.

## Stereo Link Deactivation

A stereo pair is separated back into individual channels by clicking the LINK switch when it is active (the LINK switch is gray when deactivated). When LINK is deactivated, all current control settings and inserted plug-ins for the stereo channel remain on the first channel (except pan, which is centered) and the second channel reverts to a default state.

### Link Constraints

- Only odd-numbered channels can be linked to the next even-numbered channel. For example, Analog 1 can be linked to Analog 2, but Analog 2 cannot be linked to Analog 3.
- Only the same type of inputs can be linked (for example, an analog input can only be linked to an analog input).
- For preamp channels, only the same input jacks can be linked (for example, a Mic input cannot be linked to a Line input).
- Hi-Z inputs cannot be linked.
- When unlinked, the second channel’s input switches to MIC, and the channel gain is returned to 0.
- When unlinked, channel pans return to the center.
- When unlinked, all stereo inserts on the track are converted to mono, and retained on the first track of the pair. UAD Console inserts are not inserted on the second track of the pair.

