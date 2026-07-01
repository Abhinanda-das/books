---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/39319582758676-Using-LUNA-Assistant-Features.html'
converted_at: 2026-05-31T13:44:57Z
tool: htmlq+pandoc
title: 'Using LUNA Assistant Features'
word_count: 1159
---

# Using LUNA Assistant Features


## In this article:

- [LUNA Voice Control](#h_01K05J86E5NTCDHN5RCGD0Q20K)
- [LUNA Instrument Detection](#h_01K05J86ECSSYD58SGPAAWFJA6)

LUNA now includes Assistant features: Voice Control and Instrument Detection. These features leverage AI and machine learning to perform basic voice commands in LUNA, and to analyze your tracks for instrument types.

**Note:** Voice Control and Instrument Detection run locally on your host computer. No cloud processing is required to use these features, and no audio data is collected at any time. Your data remains private, and your data is not used to train LUNA AI features.

## **Enabling LUNA Assistant features**

When LUNA starts for the first time, you are presented with an informational LUNA Feature Preview screen. To enable or disable LUNA Feature Previews, scroll to the bottom of the screen and click Turn On Feature Preview or Turn Off Feature Preview.

When you enable Feature Previews, you are prompted to complete a brief survey. After you complete the survey, LUNA opens and the feature previews are enabled when you open a session.

### **To enable or disable LUNA Assistant**

After you have made a choice on the LUNA Feature Preview screen, the screen closes. To enable or disable LUNA Assistant again, select or deselect Assistant from the Assistant menu.  

------------------------------------------------------------------------

# **LUNA Voice Control**

LUNA Voice Control\* enables you to start, stop, and record in LUNA without pressing any keys. This allows for hands-free transport control for play and record functions.

1.  Enable the Assistant (Assistant \> Assistant from the LUNA menus).
2.  In a session, hover over the LUNA Assistant icon in the bottom right corner of the timeline.\
    ![analysis-voice-hover.png](Using%20LUNA%20Assistant%20Features_assets/a219719a5f84113f85d4fcc1dfa87ecb47b62aa0.png)
3.  Click Voice Control and switch the feature On.\
    ![analysis-voice-on.png](Using%20LUNA%20Assistant%20Features_assets/cd6eece86b030c47f0cd17d76bf1b20f911be19e.png)
4.  Allow the machine learning model data to be downloaded.
5.  To configure the input source, click the Gear icon. By default, LUNA responds to voice commands that are audible at the monitor outputs of your audio interface. In practice, this means voice control will respond to any input-monitored microphone. However, you may have better results if you set Voice Control to monitor a specific input.\
    See **Voice Control Settings** below for more information.
6.  To issue a voice command, say "Hey LUNA" (or your custom wake up phrase), then the command. LUNA indicates that it is listening when it hears the wake up phrase. Commands must be issued shortly after you issue the wake up phrase (within a few seconds).

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 44.86%;">
![luna-listening.png](Using%20LUNA%20Assistant%20Features_assets/f2aea3386f864bfa6c857d268531a1934898a131.png)
</figure>

\*Available on Apple silicon Macs and in English only.

## **Voice Control Settings**

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 82.97%;">
![voice-settings.png](Using%20LUNA%20Assistant%20Features_assets/f7161bbe28fc554e03937db2a1dd7ab27eb84d03.png)
</figure>

### **Wake Up Phrase**

When enabled, the wake up phrase is used and LUNA begins listening after it hears this phrase. When disabled, LUNA is always listening for commands, and no wake up phrase is required.

- To specify a different wake up phrase, you can type a phrase here, then press Return.
- You can also click in this field and begin speaking to dictate a phrase. After dictating a phrase, press Return.

The default Phrase is "Hey LUNA." Other phrases may not work, depending on how clearly LUNA can decipher the command. If your phrase doesn't work, replace it with “Hey LUNA.”

### **Listen To**

You can specify the input to listen to in the Listen To list. By default, LUNA listens to the Monitor Output. Other audio elements in your mix can make it difficult for LUNA to hear your voice commands when Monitor Output is the Listen To source.

To make LUNA more responsive when recording in denser mixes, specify an input for Voice Control. For example, if you only issue voice commands on Mic/Line/HiZ1, set this as the Voice assistant input. Note that when you specify an input other than Default (Monitor Output), you do not have to record-enable or input-enable that input to issue voice commands.

**Talkback note:** On an Apollo with Talkback, you can specify the talkback mic as the source. Note that you will have to manually hold the talkback button, or latch talkback, for this inout source to work.

## **Commands supported with Voice Control**

Currently, LUNA can respond to the following commands. Please submit feedback with your requests for basic commands you'd like to be able to perform with your voice.

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized" style="margin-left: 0px; margin-right: auto;">
<colgroup>
<col style="width: 40%" />
<col style="width: 60%" />
</colgroup>
<tbody>
<tr>
<td><strong>LUNA Command</strong></td>
<td><strong>Phrases</strong></td>
</tr>
<tr>
<td>Play</td>
<td>"Start playback," "Start," "Play," "Playback"</td>
</tr>
<tr>
<td>Stop</td>
<td>"Stop playback," "Stop"</td>
</tr>
<tr>
<td>Start Recording</td>
<td>"Start recording," "Record"</td>
</tr>
<tr>
<td>Stop Recording</td>
<td>"Stop recording," "Stop"</td>
</tr>
<tr>
<td>Go to Next Marker</td>
<td>"Go to next marker," "Next marker"</td>
</tr>
<tr>
<td>Go to Previous Marker</td>
<td>"Go to previous marker," "Previous marker"</td>
</tr>
<tr>
<td>Toggle Click On/Off</td>
<td>"Click," "Toggle click," "Toggle the click," "Metronome,""Toggle metronome," "Toggle the metronome"</td>
</tr>
<tr>
<td>Toggle Count In On/Off</td>
<td>"Toggle count in," "Count in"<br />
(make sure to clearly separate the words "count" and "in" when speaking this command)</td>
</tr>
<tr>
<td>Toggle Pre Roll and Post Roll On/Off</td>
<td>"Pre roll," "Toggle pre roll"</td>
</tr>
</tbody>
</table>
</figure>

</div>

------------------------------------------------------------------------

# **LUNA Instrument Detection**

LUNA's AI instrument detection can optionally color-code, assign warp algorithms, name your tracks based on the instruments you record or import. When Instrument Detection is enabled, automatic track colors and warp algorithm assignments are enabled. 

## **To start using Instrument Detection**

1.  Click the Turn On Feature Preview button at the bottom of the LUNA Feature Previews page and restart LUNA, or enable Assistant from the Assistant menu.
2.  In a session, hover over the LUNA Assistant icon in the bottom right corner of the window.\
    ![assistant-hover.png](Using%20LUNA%20Assistant%20Features_assets/6d8a2f2fd893d4cd47829650174e43120af101bb.png)
3.  Click Instrument Detection and switch the feature On.\
    ![assistant-open-hover.png](Using%20LUNA%20Assistant%20Features_assets/13be7a91fffde366e5d8f00a083569a060ae0af4.png)
4.  To configure settings for detected instruments, click the the Gear icon.
5.  To automatically color tracks and assign instrument icons, enable the Auto-Color by Instrument Type option.
6.  To automatically name tracks, enable the Auto-Name by Instrument Type option.
7.  To automatically assign warp algorithms, enable the Auto-Assign Warp Algo by Instrument Type option.
8.  You can configure settings for track names and track colors here. Click a color square and use the color picker to assign a color.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![instrument-detection-options.png](Using%20LUNA%20Assistant%20Features_assets/83da203124b751748a11e2b03fad3ea467c89e5b.png)
</figure>

## **Instrument Detection in use**

When Instrument Detection is enabled, after recording or importing tracks, LUNA applies track analysis after a recording pass completes, or after you import a track or clip. Any options that are selected in Instrument Detection settings are applied.  

**Note:** Drum and percussion tracks are all named Drums: there is no distinction between percussion instruments. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 80.86%;">
![auto-colored-tracks.png](Using%20LUNA%20Assistant%20Features_assets/6852d42447961be96cc9c7c214b168fb0d8cca9f.png)
</figure>

### To change the detected instrument for a track

If you want to change the detected instrument for a track, click the instrument icon in the track header and choose a new instrument type. You can open instrument detection settings by clicking Detection Settings.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 39.56%;">
![instrument-detection-change.png](Using%20LUNA%20Assistant%20Features_assets/66bc7247b7c90037b9b0b1903411dd9b77ded508.png)
</figure>

 

<span class="wysiwyg-font-size-small">251217</span>

