---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041465732-Mixing-in-LUNA.html'
converted_at: 2026-05-31T13:44:54Z
tool: htmlq+pandoc
title: 'Mixing in LUNA'
word_count: 3845
---

# Mixing in LUNA


## In this article

- <a href="#h_1a8bb825-a857-42ad-a668-b5bf8115813f" rel="undefined" target="_self">About Mixer View</a>
- <a href="#h_162a267c-e4f6-46b2-b157-36f75a6aca75" rel="undefined" target="_self">Mixing Audio</a>
- <a href="#h_4d2ecd5a-f7ec-431e-9779-cc0f43e9e43d" rel="undefined" target="_self">Mixing Down Session Audio</a>
- <a href="#h_01H3FG40RYSH7ZGT2QFNDE234A" target="_self">Bypassing Processing</a>
- <a href="#h_96014da1-1e9b-490f-beff-82d1c663fa08" rel="undefined" target="_self">Using Sends</a>
- <a href="#h_1062e9e6-5476-4fa1-9911-eea9e8ec6dc8" rel="undefined" target="_self">Using Cues</a>
- <a href="#h_0a39db8f-85bd-4ddf-b991-1afa194d4f04" target="_self">Changing Track Output</a>

------------------------------------------------------------------------

# About Mixer View

Mixer view presents an analog console-like layout of your audio, instrument, and bus tracks, and the main track. You can use mixer view to:

- Mix audio levels and pan tracks
- Adjust trim, polarity, and track delay on a track
- Arrange tracks
- Assign track inputs
- Use tape emulation on an audio or Instrument track
- Using master tape emulation on a bus or Main track
- Use Neve or API summing emulation on a bus or the Main track
- Use API Console Emulation on tracks
- Use insert effects on a track
- Configure sends from a track
- Send track audio to cues
- Change a track's output
- Record enable, mute, and solo a channel
- Monitor a channel's input
- Configure a bus and view the sources for that bus

------------------------------------------------------------------------

# Mixing Audio

<div>

<div>

Mixing is the process of balancing multiple audio and instrument tracks into a final output—usually a stereo file or a set of stems. To achieve a professional sound, you adjust several key elements for each track:

</div>

</div>

<div>

- **Balance:** Setting volume levels.
- **Space:** Placing sounds in the stereo field (panning).
- **Tone:** Shaping frequency content with EQ.
- **Dynamics:** Controlling volume peaks and consistency.
- **Creativity:** Adding effects like reverb, delay, or distortion.

</div>

## Balancing volume levels

To balance audio levels in LUNA's mixer, you can use:

- Clip gain (Timeline)
- The volume fader (Mixer/Focus track)
- The volume fader in the track controls (Timeline)
- Text entry in Timeline track controls or Mixer channel

### To balance levels with the Mixer or a Focus channel

1.  Play the session.
2.  Move the volume fader up to increase volume, and down to decrease volume. The level is indicated by the value at the bottom of the volume meter.
3.  To set a precise value for the volume fader, double-click the value at the bottom of the volume meter and type a value in dB, then click OK. You can type whole values, decimal values, and negative. For example 5, 1.6, and -3.7 are all valid values.

<div class="wysiwyg-text-align-center" title="Attachment">

![volume-with-fader.png](Mixing%20in%20LUNA_assets/ffb8a32a4160bbcc29dc0f6a64a651bb7dbebbc5.png)

</div>

### To balance levels with the Timeline track controls

1.  Play the session.
2.  Move the volume fader left or right on the track controls in the Timeline. Move the fader left to reduce volume, and right to increase volume.
3.  To set a precise value for the volume, click the displayed volume and type a value in dB, then press Return. You can type whole values, decimal values, and negative. For example 5, 1.6, and -3.7 are all valid values.

Note that after entry, the value in the track controls shows the nearest whole value, even though the correct decimal value is applied to the fader.

<div class="wysiwyg-text-align-center" title="Attachment">

![volume--track-controls-slider.png](Mixing%20in%20LUNA_assets/e4d4f4ea365697f8ff11b5004fa30e5e7a11fde8.png)

</div>

### To balance levels with the clip gain control

1.  Hover the mouse cursor over the gain control icon at the top of an audio clip to show the Gain Control Editing Tool.
2.  Move the slider up and down to increase or reduce the gain of a clip, without altering the gain of other clips on the track.
3.  To enter a precise value, double-click the gain control, type the value in the popover, and press OK.

Clip gain allows a wide range of adjustment, from -144 dB to +48 dB. As you adjust clip gain, the waveform display shows the resulting changes to the audio level. If you select multiple clips and adjust the gain slider on one clip, the gain change is applied to all selected clips. To reset the clip gain control to 0 dB, Option-click the control.

**Note:** Tracks must be at the Medium (Default) size or larger to see the clip gain control on the track.

<div class="wysiwyg-text-align-center" title="Attachment">

![clip-gain-slider-text.png](Mixing%20in%20LUNA_assets/b9cd42381cd3235a07f13aff415e9d053acebcad.png)

</div>

## Panning tracks

You pan a track to locate the track in the stereo field. In LUNA, a track can be mono or stereo, and you can pan tracks differently based on the track format. Use the pan knobs to pan the tracks to the left or right of the stereo image. A mono track has a single pan knob, while a stereo track has two pan controls–one for the left track, and one for the right track.

![panning.png](Mixing%20in%20LUNA_assets/66b1d239d78fffa7489c0536ae6fb0a018837e42.png)

### To pan a track in the mixer

- Click and drag the pan control at the top of the channel strip.
- To type a precise value for the pan knob, double-click and type a positive or negative pan value from 0-100, then press Enter. When you type a pan value, use the prefix minus (-) for left and no prefix for right. You can also include the letter L for left or the letter R for right. For example, -24, L24, and 24L both pan a pan control 24% left. 33, R33, and 33R all pan a control 33% right.
- To simplify panning for a stereo track, you can right-click the pan control, and choose Simple under Stereo Pan Mode. The Simple stereo pan mode option allows you to pan both stereo tracks with one control to achieve the stereo image you want.

<div class="wysiwyg-text-align-center" title="Attachment">

![simple-stereo-pan.png](Mixing%20in%20LUNA_assets/73cde6366be66378f6520d3b56f3193d49579bac.png)

</div>

### Panning in Timeline view

You can also pan tracks in the Timeline view.

In the track controls for each track, you can double-click and drag on the pan setting, or click the pan value and type a value from 0-100, then press Enter. When you type a pan value, you can use the prefix minus (-) for left and no prefix for right. You can also type L for left or the letter R for right. For example, -24 and 24L both pan the audio 24% left.

<div class="wysiwyg-text-align-center" title="Attachment">

![pan-controls-timeline.png](Mixing%20in%20LUNA_assets/d4e71262f4e36c9c0e2374289bfced8c180d7386.png)

</div>

## Muting and soloing

When you mute a track it goes silent in the mix, and in any sends to which it is routed (unless they are assigned pre-fader). When you mute a track, it goes silent in the session for the duration that the mute is applied. You can also automate mutes.

Soloing a track isolates it, or plays it without the other mix elements. When you solo a track, any bus to which it is sent also continues to sound in the session; however only the soloed tracks sound through the bus. You can solo multiple tracks by default in LUNA. You can also configure LUNA to allow only one track to be soloed at a time (see <a href="360041440592-Using-LUNA.html#mix-workflow" target="_self">The Mix Workflow</a> for the X-Or Solo setting).

## Bus Spill

The Bus Spill control is a feature on a bus track and the Main track that allows you to see only the bus track and all the bus sources (all tracks routed to the bus) in the Mixer and Timeline. To enable Bus Spill, click the Spill button on a bus or the Main track. When Bus Spill is enabled, the Timeline and Mixer show only the source tracks that feed the bus, and the Main track. The Spill button flashes on the bus or Main track when Bus Spill is enabled.

<div class="wysiwyg-text-align-center" title="Attachment">

![bus-spilled.png](Mixing%20in%20LUNA_assets/e6692e2b87d69c085294b97cf86c296cc11d95a5.png)

</div>

## Compacting Mixer faders

You can click at the top of the mixer fader section to compact the mixer faders, and allow more space to work with the mixer slots. Click again to expand the mixer faders to full height. You can also toggle this setting with the menu item View \> Compact Monitor Faders.

![compact-mixer-faders.png](Mixing%20in%20LUNA_assets/6433e35763ace8b78fcd1f6ccb17289ae5c0cd3e.png)

## Showing or hiding Mixer faders

You can toggle faders in the mixer to show more of LUNA's controls when screen area is limited. Select or clear the FADERS item in the Mixer Navigation area to show or hide the faders.

![luna-hiding-faders.png](Mixing%20in%20LUNA_assets/82e76350a0a9dd957ad4a0935993286131b15b1e.png)

*Faders hidden in the Mixer*

![luna-showing-faders.png](Mixing%20in%20LUNA_assets/f85ebe4e2a2801e40ce9d5a2acc0f8a3a0b4421f.png)

*Faders shown in the Mixer*

## Scrolling the Mixer

You can scroll in the Mixer view using the arrow keys.

- To scroll one track to the left or right, use the left/right arrow keys.
- To scroll up or down in the mixer, use the up/down arrow keys.
- Command (macOS) /Ctrl (Windows) + left/right arrow keys scrolls the mixer an entire "page" or screen of faders.
- Command+Option (macOS) / Ctrl+Alt (Windows) + left/right arrow keys scrolls the mixer to the first or last fader.

## Adjust trim, polarity and track delay

You can use the Utility row tools on any LUNA channel to trim the track after console summing, and before tape, plug-ins, or channel faders by as much as +12 dB or -144 dB. In the Utility row and on the channel fader you can invert polarity 180º for any track. You can delay a track by .1–1000 milliseconds. You can adjust linked stereo channels or unlink them to invert polarity or adjust trims independently.

![utility-row-callouts.png](Mixing%20in%20LUNA_assets/f4bb1667a12922c1748b342b0875df397da0eaa2.png)

<div title="Attachment">

Polarity invert is also available at the track fader.

</div>

<div class="wysiwyg-text-align-center" title="Attachment">

![invert-polarity-fader.png](Mixing%20in%20LUNA_assets/da17a78dad2f981835c5f80c9b89bbf2eff28e6b.png)

</div>

### To adjust track trim

1.  Show and expand the Utility row in the mixer, if it is not already visible.

    <div title="Attachment">

    ![utility-row-show-expand.png](Mixing%20in%20LUNA_assets/9efcb1e720fcbfb2cbdabc111a4fe67aa8565cc2.png)

    </div>

2.  Click and drag up or down under TRIM to adjust the trim level. To adjust trim level more accurately, double-click and type the value, then click OK.

    <div title="Attachment">

    ![trim-value-set.png](Mixing%20in%20LUNA_assets/86a95cf17d5bba82b2eb3d6030f2c4e5d79d1ca2.png)

    </div>

To reset the Trim value, Option-click the Trim level.

### To adjust track polarity

1.  Show and expand the Utility row in the mixer, if it is not already visible.

    <div title="Attachment">

    ![utility-row-show-expand.png](Mixing%20in%20LUNA_assets/9efcb1e720fcbfb2cbdabc111a4fe67aa8565cc2.png)

    </div>

2.  Click the polarity button to reverse polarity. Polarity is reversed 180º when the button is highlighted.

    <div title="Attachment">

    ![reverse-polarity-utility-row.png](Mixing%20in%20LUNA_assets/18dfada3fbbed7cd3b1187c286b978f9479ace64.png)

    </div>

3.  Alternatively, you can reverse polarity on the track's fader. On the track fader in the Mixer view or on the focus channel, press the Polarity invert button to reverse polarity.

    <div title="Attachment">

    ![invert-polarity-fader.png](Mixing%20in%20LUNA_assets/da17a78dad2f981835c5f80c9b89bbf2eff28e6b.png)

    </div>

#### To adjust trim or polarity on stereo tracks independently

1.  Show and expand the Utility row in the mixer, if it is not already visible.

    <div title="Attachment">

    ![utility-row-show-expand.png](Mixing%20in%20LUNA_assets/9efcb1e720fcbfb2cbdabc111a4fe67aa8565cc2.png)

    </div>

2.  Hover over the TRIM area on a stereo track. UNLINK appears. Click to unlink the stereo tracks.

    <div title="Attachment">

    ![hover-utility-unlink.png](Mixing%20in%20LUNA_assets/9ca6a02f644a63106dc97528e1c94cf10c00f92e.png)

    </div>

When a stereo track is unlinked, you can adjust the trims and polarity separately for each channel.

Hover over the TRIM area again and click LINK to relink the tracks.

#### To delay a track

1.  Show and expand the Utility row in the mixer, if it is not already visible.

    <div title="Attachment">

    ![utility-row-show-expand.png](Mixing%20in%20LUNA_assets/9efcb1e720fcbfb2cbdabc111a4fe67aa8565cc2.png)

    </div>

2.  Click and drag in the Delay area to adjust the track delay.

    <div title="Attachment">

    ![utility-track-delay-drag.png](Mixing%20in%20LUNA_assets/be6f37db49c6e43e23512636b624ed7126548331.png)

    </div>

3.  To type the track delay, double-click the Delay area and type the value, then click OK.

<div class="wysiwyg-text-align-center" title="Attachment">

![utility-track-delay-text.png](Mixing%20in%20LUNA_assets/54760723eea6dbe49afc0564a0907b6c4b05d3d0.png)

</div>

The track is delayed on playback by the number of samples you set.

------------------------------------------------------------------------

# Mixing Down Session Audio

LUNA offers a full suite of mixdown options, including the ability to export any combination of raw tracks and bus outputs from a session, in stereo or mono as required, with or without effects applied. LUNA can also export MIDI tracks as a multitrack MIDI file with tempo.

For a simple stereo mixdown, LUNA mixes down either the entire range of audio and MIDI, or a selected range, at any sample rate supported by the hardware, and bit depths from 8 to 24. You can mix down a file as WAV, AIFF, MP3, or AAC (.m4a).

**Note:** If you do not select a range, a mixdown begins at the beginning of the session and continues until all audio is complete. Mixdown does not start from the playhead.

## Custom dither

A custom dither algorithm is applied when exporting tracks to a format that requires it.

## To mix your LUNA session down to a stereo audio file

1.  In Timeline view, select the length on the timeline or in the rulers that you want to mix down. **Note:** if you do not select a range of audio to mix down, mixdown starts from the beginning of the session, and ends after the end of all clips. \
    ![mixdown-range.png](Mixing%20in%20LUNA_assets/4470e622710389a06b17dcfb6c33e040de594f58.png)
2.  Select File \> Export \> Mixdown. The Mixdown browser appears. ![mixdown.png](Mixing%20in%20LUNA_assets/6b34b715f12e3e7318458f6d1635aaa79f5dec7c.png)
3.  Choose the file type for the mixdown file.
4.  For WAV or AIFF, choose the sample rate and bit depth for the mixed file. For an MP3 or AAC file, select VBR (variable bit rate) and quality, or CBR (continuous bit rate) and the bitrate in kbps.
5.  To listen to your session during mixdown, choose the Real-Time Mixdown option. Note that the session will mix down faster if you deselect Real-Time Mixdown.
6.  Click Export to mix down the file.

Files are automatically named with the name of the session, and the name of the output (for example, **session - MAIN.wav** ). Double-click the mixdown file name to change it. By default, files are mixed down to the Exported Files folder in the LUNA session folder.

## To mix down tracks and buses from a LUNA session

1.  Define the range. In the Timeline view, highlight the section you want to export. If no range is selected, LUNA will mix down the entire session from the beginning.\
    ![mixdown-range.png](Mixing%20in%20LUNA_assets/4470e622710389a06b17dcfb6c33e040de594f58.png)

2.  Open the Mixdown Dialog. Go to **File \> Export \> Mixdown** to open the settings window.![mixdown.png](Mixing%20in%20LUNA_assets/6b34b715f12e3e7318458f6d1635aaa79f5dec7c.png)

3.  Configure settings & sources. Adjust your preferences in the dialog:\
    **Format:** Choose your file type (WAV, AIFF, or AAC) and set the sample rate/bit depth.\
    **Processing:** Toggle Bypass Effects (for dry stems) or Preserve Mono Tracks (to keep mono files from becoming stereo). To export the MIDI from the session as a multitrack MIDI file with tempo data, choose Include MIDI file for tempo map and instruments.\
    **Real-Time:** Check Real-Time Mixdown if you are using hardware inserts or want to listen while exporting.\
    **Sources:** Under the Sources list, seleect the specific tracks or buses you wish to export.\
    To export the MIDI from the session as a multitrack MIDI file with tempo data, choose Include MIDI file for tempo map and instruments.

4.  Click **Export** to mix down files.

5.  ![export-more-sources.png](Mixing%20in%20LUNA_assets/cd90b69ed615698c48c35ee492e59a9dfe6caf46.png)

**Tip:** Click and drag to select multiple source checkboxes.

### Export file naming

Files are automatically named with the name of the session, and the names of the outputs appended (for example, **session - MAIN.wav** , **session - verb.wav** ). Double-click the name of any mixdown file to rename it. By default, files are mixed down to the Exported Files folder in the LUNA session folder.

 

## Exporting audio from the Timeline

You can export individual audio clips as single files, multiple audio clips on the same track as multiple files, and multiple audio clips from different tracks as separate files, directly from the Timeline.

### To export audio clips

1.  In the Timeline view, click one or multiple audio clips to export.
2.  Right-click an audio clip and select Export. You can also select one or more audio clips and press Command+Shift+K (macOS) / Ctrl+Shift+K (Windows), or choose the menu item File \> Export \> Clips. \
    ![export-clip.png](Mixing%20in%20LUNA_assets/a79bbd8d5eefe0895eeeb8f8f16d6b63aac64476.png)
3.  While the Export dialog is open, select clips in your session you want to export. Each clip is added to the export list.
4.  To remove a clip from the export list, click it again. **Tip:** you can click a clip in the Export browser to select and center that clip in the timeline.
5.  Under Save To in the export browser, select the location where you want to export the clips by clicking the folder icon and choosing a location from the Finder.
6.  Under Audio File Settings, specify the settings for File Type, Sample Rate and Bit Depth.
7.  Click Export to export your clips.

------------------------------------------------------------------------

# Bypassing Processing

You can easily bypass processing of LUNA Extensions, insert plug-ins, or both. On the Monitor strip, under the Bypass section, click Extensions, Inserts, or All Processing to bypass those items. When a processor is bypassed, the button for the bypassed item flashes.

Click the button for the bypassed item again to restore processing.

To view the Monitor section, choose View \> Section \> Monitor from the LUNA menus.

![monitor-column.png](Mixing%20in%20LUNA_assets/14462772e9f68c4c33c659f8f045a03f78162d9c.png)

------------------------------------------------------------------------

# Using Sends

You can use the send slots to send audio from a track to a bus track, the main output, or any available physical output on your Apollo. Note that multiple sends can send to the same physical output. They are mixed together before being sent to the physical output.

Click on the send slot to open a list of send destinations in the Focus Browser on the left, to which you can route the send.

![send-slots.png](Mixing%20in%20LUNA_assets/09f90f1f3b49704aa226e5f11e2fcedd62aeb46a.png)

You can also send from a single send slot on a track to multiple buses. To assign a send slot to multiple outputs, click the Send assignment slot, then in the Sends browser, Shift-click or Command-click the outputs to assign. The send is then labeled with "Multiple."

After you add a send, the send appears in the mixer track, with a small set of send controls displayed. These include the Send level, the Pre-fader button (P), and the Mute button (M).

<div class="wysiwyg-text-align-center" title="Attachment">

![send-single-multiple.png](Mixing%20in%20LUNA_assets/63ff5c22df1bed4cda193ef273a7c8458625a605.png)

</div>

## To use sends

- Expand the Sends row in Mixer View, or on a Focus track in Timeline view.
- Turn the Send knob to control the level of audio that you want to send to the destination. You can double-click the Send knob to type a value. When audio is playing on the track, the Send knob indicates the audio level on the track with a circular meter.
- Click the Pre button (P) to route audio to the send destination before the channel's main fader level. When audio is routed pre-fader, audio is sent from the disk to the destination regardless of the setting of the channel's fader and mute status. If audio is not routed to the send pre-fader, then if the channel is muted no audio is sent, and gain changes on the channel fader do affect the send.
- Click the Mute button (M) to mute audio to the send.
- To copy the main mix to a send, in Mixer view, right-click on a track's Pan knob or volume fader, and choose the send to which you want to copy the mix.

<div class="wysiwyg-text-align-center" title="Attachment">

![copy-mix-to-send.png](Mixing%20in%20LUNA_assets/82c9be2d7b3e2432514110a13ebe289acdbc7e3c.png)

</div>

<div title="Attachment">

### Send options

Hover your mouse over a send on a track to access send options. You can copy, paste, remove, mute, or unmute the current send or all sends. 

![send-context-menu.png](Mixing%20in%20LUNA_assets/10979afb2860b401740ea0953386b8741b6c8cc5.png)

</div>

 

### Large sends

Click the Large view box to to expand all sends in the selected slot in the LUNA mixer. You can also click the Large View icon on the left of the mixer window. Large view shows a Send fader instead of a knob, and also shows the Pan control or controls for the send. Use the Pan control or controls to pan the audio when routed to a stereo destination.

![large-buses-with-button.png](Mixing%20in%20LUNA_assets/875fc45090fef9a902b2f379b680e90f92962fb4.png)

## Dragging, dropping, and disabling sends

- Drag and drop a send from one track to another to move the send assignment, level, and pan information to a different track.

  <div title="Attachment">

  ![drag-send.png](Mixing%20in%20LUNA_assets/c64b5bae10faff61162aaec7308b85b6c37af528.png)

  </div>

- <div>

  <div>

  Option-click (macOS) or Alt-click (Windows) and drag and drop a send to copy that send assignment, level and pan information to a different send track.\
  ![option-drag-send.png](Mixing%20in%20LUNA_assets/a5738b549bdbeb3e43d038d8a998369fe99d0f03.png)

  </div>

  </div>

- <div>

  <div>

  Command-click (macOS) or Ctrl-click (Windows) a send to disable it.

  </div>

  </div>

## Copying all sends on a channel

Right-click at the top of the Sends row on a track, and select Copy All to copy all send assignments from a track. You can then right-click at the top of the Sends row on another track and select Paste All from "*source*" to paste the sends from the track.

![sends-copy-all.png](Mixing%20in%20LUNA_assets/82414f8a0bd1ab8801a5e81659348add38aa0205.png)

------------------------------------------------------------------------

# Using Cues

Use cue mix buses to create up to four custom stereo mixes that are separate from the main monitor mix. You can use cue mixes:

- To send performers a headphone monitoring mix that is different from the main monitor mix, or a mix of the Main track and other channels.
- To send separate mixes to other rooms or audio equipment.
- Any time you want to send an alternate mix to another destination.

<div class="wysiwyg-text-align-center" title="Attachment">

![cues.png](Mixing%20in%20LUNA_assets/c69c3475cfc462ee186af8759b4c2e985e3329a1.png)

</div>

## To use cue mixes

- Expand the Cues row in Mixer View, or on a Focus track in Timeline view.
- Turn the Cue knob to control the level of audio that you want to send to the cue destination. You can double-click the Cue knob to type a value. When audio is playing on the track, the Cue knob indicates the audio level on the track with a circular meter.
- Click the Pre button (P) to route audio to the cue destination before the channel's main fader level. When audio is routed pre-fader, audio is sent from the disk to the destination regardless of the setting of the channel's fader and mute status. If audio is not routed to the cue pre-fader, then if the channel is muted no audio is sent, and level changes on the channel fader do affect the send.
- Click the Mute button (M) to mute audio to the cue.

Click the Large view icon to expand the cues in a selected slot in the LUNA mixer. Large view shows a Cue fader instead of a knob, and also shows the Pan control for the cue. Use the Pan control to pan the cue mix when routed to a stereo destination.

<div class="wysiwyg-text-align-center" title="Attachment">

![large-cues-with-button.png](Mixing%20in%20LUNA_assets/10bedec1d0ea8898ae1a019ebc9e4b68dcb2ec56.png)

</div>

The cues that are displayed and available are dependent on your Apollo hardware. You can configure the number of available Cues in LUNA Settings \> Hardware panel \> Cue Bus Count.

## To copy the main mix to a cue

1.  In Mixer View, right-click on a pan knob or a volume fader.

2.  Choose the Cue to which you want to copy the mix.

![copy-mix-to-cue.png](Mixing%20in%20LUNA_assets/d0e33d317388bad065b25498233e71ad1d6d1e2c.png)

------------------------------------------------------------------------

# Changing Track Output

You can change the track output, for example, to send a track's output directly to a hardware output, or to route a track's output to a bus.

## To change the track output

1.  Scroll to the Output row in the Mixer, or on the Focus channel.
2.  Click the Output for the track.
3.  In the track Output browser, select the output. You can route a track's output to Main, an Aux, or a hardware or virtual output or output pair.

<div class="wysiwyg-text-align-center" title="Attachment">

![outputs.png](Mixing%20in%20LUNA_assets/29e1c4c7a79691f14c4321d863cac0b44df82cb5.png)

</div>

## Assigning a track output to multiple destinations

You can assign the output of a track to multiple destinations. To assign an output to multiple destinations, click the output assignment slot, then in the Output browser, Shift-click or Command-click the outputs to assign. The output is then labeled with "Multiple."

 

<span class="wysiwyg-font-size-small">251229</span>

