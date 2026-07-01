---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041911811-LUNA-ARP-MIDI-Arpeggiator-Extension-Manual.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'LUNA ARP MIDI Arpeggiator Extension Manual'
word_count: 1608
---

# LUNA ARP MIDI Arpeggiator Extension Manual


 

# Welcome

Thanks for checking out ARP. This feature rich arpeggiator is a powerful tool that can help you discover new and interesting musical note patterns while composing and performing. It can bring excitement and life to your synthesizers and we hope it will help your musical creativity.

This article includes:

- <a href="#h_b9845b5a-b2d9-4d48-a972-4a024773118a" target="_self">Quick Start</a>
- <a href="#h_564c2f2d-fd62-4d12-b83f-b6a9dcf7b8eb" target="_self">ARP Controls</a>

# Quick Start

#### *Tip: If a MIDI controller is not available, you can program notes into the LUNA track containing Shape and play the track, or use LUNA’s onscreen keyboard when MIDI workflow mode is active. *

Let’s take ARP for a quick test drive before diving into the details. We can use it with LUNA’s included Shape instrument. After Shape is loaded and input-enabled (see LUNA application documentation for these details):

<div class="fabric-editor-block-mark fabric-editor-indentation-mark" level="1">

1.  Click the MIDI FX on the instrument track that contains Shape.
2.  Choose ARP from LUNA’s focus browser.\
    \
    ![arp-arp-shape-track.png](LUNA%20ARP%20MIDI%20Arpeggiator%20Extension%20Manual_assets/1df38d87f40416c9d874280e86c9e822f9dc7329.png)\
    \
3.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">Hold one or more notes on your MIDI controller and you will hear those notes being played in an arpeggiated pattern. \
    </span>*Note: ARP always plays notes monophonically (one at a time), even if a chord is played.\
    \
    ![arp-arp-annotated.png](LUNA%20ARP%20MIDI%20Arpeggiator%20Extension%20Manual_assets/7950e3885651980c1613c6b274b70f875f9e9cb7.png)\
    \*
4.  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">Change the ARPEGGIATION TYPE by clicking one of the 12 available options.</span>
5.  Adjust the RATE controls (drop menu and radio buttons) to select the time division at which the arpeggiator advances to the next note in the pattern.
6.  Change the GATE TIME parameter to shorten or lengthen each note in the pattern.
7.  The SWING parameter injects some metronomic swing into the arpeggiated pattern.
8.  Finally, the four RATE PRESETS provide quick access to stored rate settings. You can learn how to set the four presets in the Arpeggiation Controls section of this guide.

</div>

The Quick Start only scratches the surface of what ARP can do. Read on to learn about all its various features and how they work together.

# ARP Controls

<div layout="align-start" node-type="mediaSingle" data-width="58">

<div collection="contentId-212336645" context-id="212336645" file-mime-type="image/png" file-name="arp-arp-basic.png" file-size="405809" data-height="593" data-id="b02f219d-5a8c-49ab-9d37-ad0e3e6b5d71" node-type="media" data-type="file" data-width="354" title="Attachment">

![arp-arp-basic.png](LUNA%20ARP%20MIDI%20Arpeggiator%20Extension%20Manual_assets/79a8df45c06f26994ca27294a1ddb1071ef03164.png)

</div>

</div>

 

ARP has a simple user interface and all of its controls are located on one screen. The on-screen controls can be subdivided into three logical groups: Synchronization and Tempo, Arpeggiation, and Keyboard.

 

## Synchronization and Tempo Controls

<div layout="align-start" node-type="mediaSingle" data-width="58">

<div collection="contentId-212336645" context-id="212336645" file-mime-type="image/png" file-name="arp-arp-sync-controls.png" file-size="400565" data-height="593" data-id="de6d4490-37af-415f-8a11-fdec96ebd1a5" node-type="media" data-type="file" data-width="354" title="Attachment">

![arp-arp-sync-controls.png](LUNA%20ARP%20MIDI%20Arpeggiator%20Extension%20Manual_assets/e2f447a56b4a8a64f576d680959d08b7a73c4809.png)

</div>

</div>

 

### Sync

This button synchronizes ARP to the master tempo of your session. The button is illuminated when synchronization is enabled.

#### *Note: When this feature is activated, the TEMPO and TAP buttons are deactivated since ARP receives tempo information from LUNA. When SYNC is disabled, the TEMPO and TAP controls become active and can be used. *

### Start Grid

When the LUNA transport is running and SYNC is enabled, this drop menu determines when an arpeggiation will start playing back relative to the master transport of LUNA. For example, setting the start grid to 1/1 causes an arpeggiation to only begin playback when LUNA’s transport control reaches the beginning of the next bar, even if you play notes ahead of the start point. Setting this to 1/4 causes an arpeggiation to play back at the start of the next quarter note.

#### *Note: This control is only active when SYNC is enabled and LUNA’s transport is running. If the transport is stopped, notes trigger the arpeggiator immediately.*

### Tempo

When SYNC is disabled, the tempo of the arpeggiator is displayed here and it can be modified by dragging the number up or down or by double clicking it and entering a value directly. When SYNC is enabled, the tempo of the arpeggiator is locked to the master tempo track of the session and cannot be changed.

#### *Tip:  Tempo can be automated for interesting rhythmic effects.*

### Tap

This button lets you enter a tempo by tapping the button. Note that this button is only active when SYNC is disabled. When SYNC is enabled, this button does not change ARP’s tempo.

## Arpeggiation Controls

<div layout="align-start" node-type="mediaSingle" data-width="58">

<div collection="contentId-212336645" context-id="212336645" file-mime-type="image/png" file-name="arp-arp-arpeggiation-controls.png" file-size="396912" data-height="593" data-id="23df8f9d-68a6-48b5-8404-91aec9dd2a60" node-type="media" data-type="file" data-width="354" title="Attachment">

![arp-arp-arpeggiation-controls.png](LUNA%20ARP%20MIDI%20Arpeggiator%20Extension%20Manual_assets/6c370773075b58e82a1a1b2943de32a3507d8c37.png)

</div>

</div>

 

### Arpeggiation Type

ARP allows for 12 different methods of arpeggiation:

- **UP:** Notes are played from the lowest note to the highest note and repeated.
- **DOWN:** This setting provides the reverse of the *UP* option.
- **UP DOWN:** Notes are played from the lowest note to the highest note and back down to the lowest note before repeating. 
- **DOWN UP:** This setting provides the reverse of the *UP DOWN* option.
- **UP HOLD DOWN:** Notes are played from the lowest note to the highest note and back down to the lowest note before repeating. The highest and lowest notes are played two times.
- **DOWN HOLD UP:** This setting provides the reverse of the *UP HOLD DOWN* option.
- **IN OUT:** Notes are arpeggiated  “inside out” starting with the note nearest to the center of the notes played and progressing to the outer notes before repeating.
- **OUT IN:** This setting provides the reverse of the IN OUT option.
- **ALT LOW:** This setting alternates between the lowest note played and progressively higher notes in the pattern before repeating.
- **ALT HIGH:** This setting provides the reverse of the ALT LOW option.
- **AS PLAYED:** Notes are arpeggiated in the order they were played.
- **RANDOM:** Notes are arpeggiated in random order.

### Gate Time

This knob sets the length of the arpeggiated notes in the sequence, from 1–200%. A 100% setting means that each arpeggiated note is the length set in the RATE drop menu. For example: Notes at 1/4 rate and 100% gate time play as original 1/4 notes, but notes at 1/4 rate and 50% gate time play as 1/8 notes (one-half as long). 

#### *Note: GATE TIME settings greater than 100% result in an overlap of subsequent notes. This can have interesting (and sometimes unexpected) results when working with monophonic synthesizers.*

### Rate

This drop menu determines the rate at which the arpeggiator advances to the next note in a pattern. Note that the values displayed in this menu will vary depending on whether *whole note*, *dotted* or *triplet* is selected from the Note Division buttons.

### Note Division

These three radio buttons let you choose from *whole note*, *dotted* or *triplet* beat divisions in your arpeggiation pattern.

### Swing

This knob sets the amount of metronomic swing, from 0–100%. Swing changes the rhythmic feel of the pattern.

### Rate Presets

ARP has four presets that let you quickly change between various RATE settings. The currently selected preset is highlighted and you can select a different preset by clicking on it. Making any change to the RATE settings (the drop menu or the radio buttons) automatically save that new value to the currently selected preset.

#### *Note: Rate presets are only for storing the RATE and NOTE parameters. *

## Keyboard Controls

<div layout="align-start" node-type="mediaSingle" data-width="58">

<div collection="contentId-212336645" context-id="212336645" file-mime-type="image/png" file-name="arp-arp-keyboard-controls.png" file-size="398706" data-height="593" data-id="4ec8f384-bd47-4ca9-99cd-df2387e72184" node-type="media" data-type="file" data-width="354" title="Attachment">

![arp-arp-keyboard-controls.png](LUNA%20ARP%20MIDI%20Arpeggiator%20Extension%20Manual_assets/adc10403fe0262d7104399698d8c3fa4c21b124e.png)

</div>

</div>

 

### Octaves

This drop menu lets you automatically repeat notes or chords in octave bands above what you have played. At the default setting (1), played notes are arpeggiated exactly as played. At higher values (2-5), your played notes are repeated 1 to 4 octaves above where you have played before the pattern repeats.

#### *Note: Certain instruments (such as Minimoog) have limited note ranges by design. With these instruments, selecting high or low octave ranges may result in occasional silences as ARP plays the extended notes. These silences are normal and expected. They can be eliminated by reducing the Octave value. *

### Latch

When latching is engaged, the arpeggiator continues to run when keys are released. The exact behavior of the latching is set by the LATCH MODE menu.

### Latch Mode

This drop menu determines the behavior of the latching function.

- **RESET:** Notes are latched and continue repeating until latching is disabled or different notes are played.
- **TRANSPOSE:** Notes are latched and continue repeating until latching is disabled or different notes played. If notes are being arpeggiated, playing a single note will cause the pattern to be transposed and the lowest note of the arpeggiated pattern becomes the note played.
- **NOTE ADD:** Notes are latched and continue repeating until latching is disabled. While the arpeggiator is running, playing more notes will add those new notes to the arpeggiated pattern.
- **LIVE ADD:** Notes are latched and continue repeating until latching is disabled. While the arpeggiator is running, playing more notes will temporarily add those new notes to the arpeggiation pattern as long as those notes are held. Releasing the held notes will cause the arpeggiator to revert back to its original pattern.
- **THRU:** Notes are latched and continue repeating until latching is disabled. While an arpeggiated pattern is playing back, any new notes played are not arpeggiated, letting you play along with the arpeggiated pattern.

### Key Range

This parameter sets the key range in which ARP is active. Notes that fall inside the low and high limits are arpeggiated whereas notes that fall outside of this range bypass the arpeggiator and playback as normal (non-arpeggiated) notes. You can adjust the ranges by dragging the vertical handles or double-clicking the low and high note values and entering new values directly. Held notes are shown in the display area for visual reference. 

 

