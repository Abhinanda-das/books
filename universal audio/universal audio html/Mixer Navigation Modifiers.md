---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/25348282201364-Mixer-Navigation-Modifiers.html'
converted_at: 2026-05-31T13:44:48Z
tool: htmlq+pandoc
title: 'Mixer Navigation Modifiers'
word_count: 929
---

# Mixer Navigation Modifiers


Modifiers add several controls to UAD Console that make common workflow tasks much faster and easier to accomplish. With modifiers, you can easily power items on and off, remove items, copy and paste items, isolate channels, and set controls to their defaults. When you click a mixer modifier button, the control latches, and flashes to indicate it is active. 

![](Mixer%20Navigation%20Modifiers_assets/c88cb50f2f365cb7db213af76e85d8a60fb13821.png) 

# Modifier Latch

![](Mixer%20Navigation%20Modifiers_assets/4f2c0a2bfe61974dc606bd59c71b6226f8895503.png)

*Power option latched*

When a Modifier switch is clicked, the switch flashes yellow, indicating that the function is latched and ready to be applied.

# Modifier Unlatch

The latched option is unlatched (the switch stops flashing) when:

- The Modifier switch, or another Modifier switch, is clicked
- No Modifiers are applied within the Modifiers Timeout period

## Modifiers Timeout

![](Mixer%20Navigation%20Modifiers_assets/fbbaedaee80d510ba51ec0d970328bfe640cd950.png)

When a modifier is latched, it is automatically unlatched (times out) after the Modifiers Timeout period to prevent inadvertent modifications.

The Modifiers Timeout is a preference set in the Settings \> Options panel. The default Modifiers Timeout period is six seconds/flashes.

## Swiping Across Modifiers

Modifiers can be adjusted quickly across many items in the mixer by swiping. When a Modifier switch is latched, click and hold the mouse, then drag vertically and/or horizontally across highlighted items to perform the function on multiple items.

**Tip:** Modifier swipe shortcuts are the fastest way to perform the same function on multiple items.

![](Mixer%20Navigation%20Modifiers_assets/1d68c37d83db75942ab0fac6513f7f94439568e6.png)

# Power Modifier

This option toggles a plug-in, send, or cue’s power state, or all plug-ins, sends, or cues on a channel. When disabled, plug-ins no longer use UAD DSP resources, and sends or cues are disabled.

![](Mixer%20Navigation%20Modifiers_assets/f1689608b75076c7f2af24bc54976e4e05857d50.png)

#### To power items on/off

1.  Click the Power button on the Modifiers panel. Power modifier icons appear on all items that can be powered off or on. 
2.  Click individual power modifiers, or swipe horizontally or vertically across multiple modifiers, to toggle power on or off. 
3.  To power on/off all items of the same type for a channel, click the power button next to the item name (Inserts, Sends, or Cues). 

**Note:** Toggling power for all inserts on a channel does not toggle power to the Unison insert. 

# Remove Modifier

The Remove Modifier removes a plug-in or all plug-ins from a channel. 

![](Mixer%20Navigation%20Modifiers_assets/6b5aa3bbce82c5d3b5155f3bf35af445a9c78e85.png)

#### To remove plug-ins with the Remove Modifier

1.  Click the Remove button on the Modifiers panel. Remove modifier icons appear on plug-ins that can be removed.
2.  Click individual remove modifiers, or swipe horizontally across multiple modifiers, to remove plug-ins. To remove all plug-ins from a channel, click the remove icon next to the Inserts label. 

# Copy / Paste Modifier

The Copy and Paste Modifiers copy a plug-in, send, cue, or channel and paste it where you choose. 

![](Mixer%20Navigation%20Modifiers_assets/a33c127ea8af6d72edde1410ba64f0bb7c85c6f9.png)

#### To copy and paste items

1.  Click the Copy button on the Modifiers panel. Copy modifier icons appear on all items that can be copied and pasted, including plug-ins, sends, cues, and entire channels.
2.  Click the individual copy modifie for the item you want to copy. After the  modifier is copied, the copy modifier turns to a red Paste modifier. Destinations to which the copied item can be pasted are highlighted. 
3.  Click individual paste modifiers, or swipe across multiple modifiers to paste multiple items. 

#### To copy and paste entire Channel Strips

1.  Click the Copy button on the Modifiers panel. Copy modifier icons appear at the bottom of each channel strip.
2.  When Copy is latched, click the copy modifier at the bottom the channel strip you want to copy. The Copy button switches to Paste.
3.  Click one or more channel strip destination icons to paste to available channel locations. 

**Note:** You cannot swipe across multiple channels when pasting a channel strip. To paste multiple channel strips, click each destination individually.

![](Mixer%20Navigation%20Modifiers_assets/2a71e6d62b639c0841322c6833cc493037c6dd33.png)

# Isolate Modifier

The Isolate modifier allows you to quickly Isolate channels. Isolate allows you to seamlessly monitor live hardware inputs with Realtime UAD Processing, even when changing UAD Console and LUNA sessions. Isolated channels always retain their current settings when different UAD Console and LUNA sessions are loaded. Isolated channels are also not controlled by LUNA. 

![](Mixer%20Navigation%20Modifiers_assets/e39afcbca7fb48c43d35901569872573d992f4c6.png)

**Tip:** To quickly isolate an individual channel, right-click a channel’s input label then choose Isolate from the Input Label Menu.

# Set Default Modifier

The Set Default modifier returns a parameter to its default value.

![](Mixer%20Navigation%20Modifiers_assets/ac6274edc466d9aa845dfb5c10fdfb4c607826ea.png)

**Note:** The Set Default modifier is primarily for knob and fader values. It does not apply to any preamp settings, plug-in inserts, SOLO/MUTE switches, monitor levels, customized input names, and similar functions.

1.  Click the Set Default switch on the Modifiers panel. The Set Default button blinks.
2.  Click a control to return the control to its default value. 

# Settings Switch

![](Mixer%20Navigation%20Modifiers_assets/40f14945005049a87df6cb02529c5860524ebbee.png)

The SETTINGS switch is located at the bottom of the Mixer Navigation column. Click to open the UAD Console Settings window, where many global settings are defined. For complete details, see [UAD Console Settings](https://help.uaudio.com/hc/en-us/articles/25403524417812).

# Clear Switches

![](Mixer%20Navigation%20Modifiers_assets/9604cb633bc1caf07f149dbfc40499eaec747922.png)

The Clear switches are located near the bottom of the UAD Console screen, in the Options column.

## Clear Solo

Whenever Solo is engaged on any channel input, the Clear Solo switch is highlighted. Click the Clear Solo switch to deactivate Solo on any channel inputs.

**Tip:** Click Clear Solo again to return all channels to their previous Solo states.

## Clear OL

This switch clears all over limit (clip) indicators and peak hold indicators on all meters.

You can also clear individual meters or all meters by right-clicking/Ctrl-clicking in the meter display, and choosing Meter or All Meters under Clear.

![clear-meters.png](Mixer%20Navigation%20Modifiers_assets/9b2bb97829e836591d458962ade7506ce55d4885.png)

