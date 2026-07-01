---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041911651-Spitfire-Audio.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'Spitfire Audio'
word_count: 2382
---

# Spitfire Audio


Spitfire Audio makes inspiring sounds and film scoring tools in collaboration with the world’s best composers, musicians and engineers. Recorded in stunning spaces including AIR Studios, the home of blockbuster scores, Spitfire Audio captures and develops the sounds of Hans Zimmer, BBC Symphony Orchestra, Olafur Arnalds and many more, showcased within beautifully crafted interfaces for maximum detail, control and expression.

There are a number of different UAD Instruments available from Spitfire Audio. This manual applies to all Spitfire Audio UAD instruments.

This article includes:

- <a href="#h_4e114a00-d08d-4a6d-999f-e9c1fa6263c9" target="_self">System Requirements</a>
- <a href="#h_2b4f0331-7025-4b76-a6ac-65a4348b232f" target="_self">The Interface</a>
- <a href="#h_8cb53a70-aea8-4ee3-90dd-bafef6f1fcaf" target="_self">Glossary of Articulations</a>
- <a href="#h_8cb53a70-aea8-4ee3-90dd-bafef6f1fcaf" target="_self">Glossary of Articulations</a>

 

------------------------------------------------------------------------

 

# System Requirements

In addition to overall LUNA Recording System requirements, Spitfire Audio UAD Instruments have the following requirements:

- SSD drive with available storage (varies per instrument):
  - 16 GB for Spitfire Chamber Strings Collection
  - 11 GB for Spitfire Symphonic Brass Collection
  - 11 GB Spitfire Symphonic Woodwinds Collection
- SSD drive must be formatted as APFS (Apple File System)
- External SSD must be within USB 3.0, USB 3.1, PCIe, or Thunderbolt enclosure

Note:

- Spinning hard drives and macOS Fusion drives are unsupported
- SSD drives formatted as ExFAT, FAT, and Mac OS Extended are unsupported

 

------------------------------------------------------------------------

 

# The Interface

<div layout="align-start" node-type="mediaSingle" data-width="90">

<div collection="contentId-214728735" context-id="214728735" file-mime-type="image/png" file-name="spitfire-annotated-ui.png" file-size="93543" data-height="1000" data-id="0d241900-375a-4e46-bd9f-2aae7f6f345e" node-type="media" data-type="file" data-width="1155" title="Attachment">

![spitfire-annotated-ui.png](Spitfire%20Audio_assets/2d60fbbf28c6c2b24eaca72485345139ac53fc20.png)

</div>

</div>

 

## 1. Top Menu

### Patch name: 

This shows the name of the loaded instrument.

### Master Tune: 

This allows you to tune everything (all articulations) ±12 semitones. Cmd+Click resets to default of 0 semitones.

### Master Pan: 

This allows you to pan everything (all articulations). Cmd+Click resets to default (centre).

### Master Volume: 

This adjusts the overall volume of the instrument. Range -inf - +12dB. Cmd+Click resets to default of 0dB.

## 2. Controllers

### Greyed-out controllers: 

Depending on the articulation selected, some controllers do not have any effect. When a controller doesn’t have any effect it becomes greyed out.

### Expression: 

Instrument trim that adjusts the volume within the dynamics. 

Expression is mapped to MIDI CC11.

### Dynamics: 

Moving this crossfades the different dynamics between loud and soft. 

Dynamics is mapped to the modwheel, MIDI CC1.

### Vibrato: 

Where appropriate this crossfades from no (or senza) to lots (molto) vibrato. 

Vibrato is mapped to MIDI CC21.

### Attack: 

For some articulations this can be used to vary the start of the note. For example, with shorts it can be used to increase the tightness of the performance; with the Rips articulation it will change the length of the run up to the note. 

Attack is mapped to MIDI CC22.

### Release: 

For some articulations this can be used to vary the end of a note. This is

mainly used on Longs articulations to allow control over the tail: at low release values the note will stop more abruptly and at high values the note will stop more gradually (useful for creating smooth transitions between notes/chords).

Release is mapped to MIDI CC23.

## 3. Technique Selector

### Articulation icons: 

These icons can be clicked to allow you to change the articulation currently being played by the instrument. When selected, the icon becomes highlighted.

### Purge: 

The small “memory” icon below the technique allows you to remove an articulation from memory. This can be useful when using a lot of instances of an instrument. By default all techniques are preloaded into memory. When the technique is purged, the technique will not sound if it is purged and the icon becomes grey, as shown below:

Not purged – The articulation is preloaded into memory.

<div layout="align-start" node-type="mediaSingle" data-width="25">

<div collection="contentId-214728735" context-id="214728735" file-mime-type="image/png" file-name="spitfire-highlighted.png" file-size="2249" data-height="162" data-id="25a9d393-d637-4577-ba27-02715886e540" node-type="media" data-type="file" data-width="128" title="Attachment">

![spitfire-highlighted.png](Spitfire%20Audio_assets/ccdc06e8ff9c20a4cd12f7d753a1987e21f18140.png)

</div>

</div>

 

Purged – The articulation is removed from memory and the “memory” icon is greyed out.

<div layout="align-start" node-type="mediaSingle" data-width="25">

<div collection="contentId-214728735" context-id="214728735" file-mime-type="image/png" file-name="spitfire-not-highlighted.png" file-size="2242" data-height="162" data-id="f41ad935-327e-449d-a6ee-6f2be171edc9" node-type="media" data-type="file" data-width="128" title="Attachment">

![spitfire-not-highlighted.png](Spitfire%20Audio_assets/fb447b08f1469b9539cd2c5083088e42aaaaddef.png)

</div>

</div>

 

## 4. Keyboard

This ranges from C0 to E8 and reflects the keys currently being received via MIDI/ pressed by the user.

### Key switches:

On the bar above the keyboard the key switches are shown by the left section of white. All keys under this white section are key switches and can be used to change articulation without clicking the UI. The order of the key switches are reflected by the order of the articulation icons (from left to right, top to bottom).

### Playable range:

The right hand section of white shows the playable range. This will vary depending on the articulation and instrument selected.

 

------------------------------------------------------------------------

 

# Glossary of Articulations

The following is an explanation of all of the terms used when naming our ‘articulations’ in the library. The available articulations will be displayed when an instrument is loaded.

### Long

The most vanilla of the long notes that we record, a standard sustained note. This is the basic playing style, often recorded with and without vibrato.

### Spiccato

This articulation can vary! For us, our Spiccato aims to capture a very nice ‘tight’ sound, with the bow bouncing off the string. This creates a sound that can be used either as a nice short staccatissimo, but also as a sequence of fast short notes or an ostinato.

### Staccato

Staccato in notation refers to a ‘shortened and detached’ style of playing. In the case of samples, this usually refers to a single but defined short note.

### Pizzicato

Plucking the strings with the finger.

### Short Marcato

Marcato in our samples refers to the longest of our short notes, and has a slightly harder attack whilst maintaining a round shape to the note start. Think of this as the longest note in a fanfare passage. 

### Short Tenuto

The intermediate short length - literally it means ‘hold the note for its full duration or even slightly longer’ and implies some form of accent. We think of this as a nice rounded attack.

### Short Col Legno

Col Legno means ‘with wood’. This style of playing is to turn the bow over and hit the string with the wood of the bow. Usually players will bring a practice of less expensive bow for this, as their main bows can cost thousands!

### Short 0'5

This is a staccato played to the length of approximately half a second.

### Long Sul Pont

Short for ‘sul ponticello’, meaning to play on the bridge. Here the players bow very close to the bridge, which produces a brittle and edgy sound. Always reminds us of nails on a chalkboard!

### Long Harmonics

If a player holds down lightly on the string a perfect fourth interval up from the note they are fingering, you hear what is called an ‘artificial harmonic’ sound - two octaves up from the note being fingered. This is called ‘artificial’ to distinguish it from the natural harmonic series of the open string. These ‘natural’ harmonics can be heard by moving the finger up and down the string while lightly bowing. Note that the playable range is different to the Long articulation.

### Tremolo

A tremolo is where a player rapidly moves the bow whilst keeping the left hand on the same notes. The effect is a shimmering one when played soft, and a very aggressive and tense sound when played loud. 

### Trills

A trill is where a player alternates between two notes. These work great as accented performance embellishments, or you can play them very softly to create unique and interesting textures. 

### Rips & Falls

Either a sweep ‘up’ to the target note, or a fall down to the target note. Sometimes there are different speeds for this, varied with the Attack knob.

### Runs, Disco Falls & FX

A collection of various FX, from slides through to unusual ‘chattering’ and ‘cluster’ sounds, to runs slides and ‘disco falls’. Have an explore through these patches!

 

------------------------------------------------------------------------

 

# Spitfire Audio UAD Instruments

## Spitfire Chamber Strings – LUNA Collection

We handpicked 16 of the finest string players to perform an encyclopaedia of articulations and techniques, expertly recorded in the world famous Hall at AIR Studios, London. This smaller section gives you more detail and focus than our Symphonic range, while still capturing the beautiful resonance of the hall. This is our definitive chamber range – a hugely versatile classic that will enhance your film, TV and game scores and pop records.

### Instruments

Your purchase of the Spitfire Chamber Strings LUNA Collection includes the individual UAD Instruments below: 

- Chamber Strings - Violins 1
- Chamber Strings - Violins 2
- Chamber Strings - Violas
- Chamber Strings - Celli
- Chamber Strings - Basses
- Chamber Strings - Ensembles

### Articulations

Spitfire Chamber Strings for LUNA includes the following articulations. 

 

<table style="width:100%;" data-autosize="false" data-layout="default" data-number-column="false">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<tbody>
<tr>
<td class="pm-table-cell-content-wrap"><p><strong>Chamber Strings</strong></p>
<p><strong>Articulations</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Violins 1</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Violins 2</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Violas</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Celli</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Basses</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Ensembles</strong></p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Long</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Long Harmonics</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Long Sul Pont</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Short Pizzicato</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Short Spiccato</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Short Staccato</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Tremolo</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Trill (Major 2nd)</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Trill (Minor 2nd)</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Runs</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Disco Falls</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
</tr>
</tbody>
</table>

 

## Spitfire Symphonic Brass – LUNA Collection

Half a decade in the making, this encyclopaedic compendium is our definitive collection of orchestral brass. The UK's finest brass players have been expertly recorded at the world-famous Hall at AIR Studios, London — the same inimitable acoustic as Symphonic Strings and Symphonic Woodwinds, for that highly sought-after blockbuster sound. Symphonic Brass LUNA Collection offers you 46 articulations, adding power and punch to your orchestral scores.

### Instruments

Your purchase of the Spitfire Symphonic Brass LUNA Collection includes the individual UAD Instruments below: 

- Symphonic Brass - Horn Solo
- Symphonic Brass - Horns a2
- Symphonic Brass - Tenor Trombone Solo
- Symphonic Brass - Tenor Trombones a2
- Symphonic Brass - Bass Trombones a2
- Symphonic Brass - Trumpet Solo
- Symphonic Brass - Trumpets a2
- Symphonic Brass - Tuba Solo

### Articulations

Spitfire Symphonic Brass for LUNA includes the following articulations. 

 

|  |  |  |  |  |  |  |  |  |
|----|----|----|----|----|----|----|----|----|
| **Symphonic Brass** | **Horn Solo** | **Horns a2** | **Tenor Trombone Solo** | **Tenor Trombones a2** | **Bass Trombones a2** | **Trumpet Solo** | **Trumpets a2** | **Tuba Solo** |
| Long | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ |
| Short Marcato | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ |
| Short Staccato | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ |
| Short Tenuto | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ |
| Falls | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | NO | ✔︎ | ✔︎ |
| Rips | ✔︎ | ✔︎ | ✔︎ | ✔︎ | ✔︎ | NO | ✔︎ | ✔︎ |

 

## Spitfire Symphonic Woodwinds – LUNA Collection

Spitfire Audio has taken its decade of experience recording woodwind instruments, expertly sampling the UK's finest players at one of the most sought-after locations in the world: The Hall at AIR Studios, London. This library offers you a wide range of instruments and articulations, from guttural depths of the bass clarinet to the gleaming sound of the piccolo. An essential part of your orchestral palette, the woods are your secret weapon to adding real power to your scores.

### Instruments

Your purchase of the Spitfire Symphonic Woodwinds LUNA Collection includes the individual UAD Instruments below: 

- Symphonic Woodwinds - Piccolo Flute
- Symphonic Woodwinds - Flute Solo
- Symphonic Woodwinds - Flutes a2
- Symphonic Woodwinds - Clarinet Solo
- Symphonic Woodwinds - Clarinets a2
- Symphonic Woodwinds - Bass Clarinet
- Symphonic Woodwinds - Oboes a2
- Symphonic Woodwinds - Bassoon a2

### Articulations

Spitfire Symphonic Woodwinds for LUNA includes the following articulations. 

<table data-autosize="false" data-layout="default" data-number-column="false">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr>
<td class="pm-table-cell-content-wrap"><p><strong>Symphonic </strong></p>
<p><strong>Woodwinds</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Piccolo Flute</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Flute Solo</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Flutes a2</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Clarinet Solo</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Clarinets a2</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Bass Clarinet</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Oboes a2</strong></p></td>
<td class="pm-table-cell-content-wrap"><p><strong>Bassoons a2</strong></p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Long</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Short Staccato</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Trill (Major 2nd)</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Trill (Minor 2nd)</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Short Tenuto</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
<tr>
<td class="pm-table-cell-content-wrap"><p>Short Marcato</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>NO</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
<td class="pm-table-cell-content-wrap"><p>✔︎</p></td>
</tr>
</tbody>
</table>

 

