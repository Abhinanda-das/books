---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/13210628963732-Importing-Session-Data.html'
converted_at: 2026-05-31T13:44:43Z
tool: htmlq+pandoc
title: 'Importing Session Data'
word_count: 1301
---

# Importing Session Data


You can import session data from a LUNA session into the currently opened session. This allows you to copy audio and MIDI, plug-ins, instruments, and buses from one session file to another, with flexible import options. 

**Note:** You can import session data while in either Timeline view or Mixer view. Both views show a preview of the imported track data before you import. However, if you are importing tracks with audio and MIDI data, Timeline view allows you to see audio and MIDI clip previews. 

## In this article

- <a href="#h_01GS93RH3FSCBES9S08FAB3EDF" target="_self">About Importing Session Data</a>
- <a href="#h_01GS93RQEC8VVR641BG3JE1N3E" target="_self">Choosing a Source Session</a>
- <a href="#h_01GS93RVTYH2JGJ26YD3PKA3WC" target="_self">Configuring Tracks to Import</a>
- <a href="#h_01GS93S17Z32V8T04W7HYDSAVM" target="_self">Configuring Import Settings</a>

# About Importing Session Data

The basic steps for importing session data are as follows. 

1.  Open a session (this is the *destination* session). 
2.  Choose File \> Import Session, or press Option+I (macOS) or Alt+I (Windows), and choose the session file from which to import session data. This is the *source* session.
3.  Choose tracks to import, and match tracks with existing destination tracks if required.
4.  Configure import settings. The data to be imported is shown as an overlay on your existing session’s tracks. 
5.  Click Import near the top of the browser to import session data.

![imported-session-overlay.png](Importing%20Session%20Data_assets/3f54918331b54630ef1c891055d319d2b0a76c38.png)

 

------------------------------------------------------------------------

 

# Choosing a Source Session

1.  From the LUNA menus, choose File \> Import Session, or press Option+I (macOS) or Alt+I (Windows), and choose the session from which to import session data. You can expand a session in the list to see session versions, by clicking the \> symbol to the left of session and/or version names.\
    ![import-session-data-dialog.png](Importing%20Session%20Data_assets/a3aae3bdb76bd235f3f27eeded8ae98249120d82.png)
2.  Click Open From Disk… to choose a session that is not in LUNA’s Recent list. 
3.  When you have selected a session, click Import Session Data. The source session tracks are populated in the Import Session Data browser.

After you have opened a session from which to import session data, you can switch to a different source session. At the top of the Import Session Data browser, click the session name.

![switch-import-session.png](Importing%20Session%20Data_assets/72a8d4a44aa67478c9693d569b94b86135882058.png)

------------------------------------------------------------------------

 

# Configuring Tracks to Import

The Import Session Data browser provides several options for how to add and match tracks from the source session to the destination session. You import tracks and session data in the Import Tracks area of the Import Session Data browser, which opens after you choose a session from which to import session data. 

You can import audio tracks, instrument tracks, bus tracks, and the main track from another session. When you import tracks, you can choose to create new tracks or import into existing tracks, on a track-by-track basis, for any combination of selected tracks, or for all tracks. The Main track plug-ins, extensions, and automation data can be replaced, but you cannot add another Main track.

## Match by Name

Click Match by Name to automatically add any tracks from the source session to the destination session, if the track names match. 

![match-by-name.png](Importing%20Session%20Data_assets/d878ebeac3acf48140511211e36e3de36bfcd4e7.png)

## Clear

Click Clear to clear any added tracks before you complete the import.

## Add

Click Add to add any unmatched import tracks to the session. Unmatched tracks are added as New tracks. The Main track is not automatically included in this import. 

![add-with-add-button.png](Importing%20Session%20Data_assets/ff83af88f3ab4d3797ed70d5d2562dc053d95391.png)

## Manually matching and importing tracks

Select one or more tracks in the Import Tracks browser, and hover your mouse over a track in the Import Tracks browser to see the New Track and Match options.

### New Track

New track adds the imported track as a new track. Click New Track to add the track or tracks to the import list as New Track. 

### Match

Match allows you to choose a track to match to the selected track, then imports track data that you specify to that track.

### To match tracks in the import track browser

1.  After you choose a session to import and open the session in the Import Session Data browser, select the tracks in the destination (current) session to which you want to import the session data.
2.  Select the source tracks you want to import to the selected tracks in the Import Tracks browser. 
3.  Hover over a selected track in the Destination column and choose Match. If a track is available with the same name or track format, the destination track name is added to the import list. If no track matches the track name or format, or there are not enough remaining tracks to match, the track is not added to the list, and the text “Bus/Track Mismatch” or “Select Track in Timeline” is displayed. \
    ![hover-import-browser.png](Importing%20Session%20Data_assets/fbaf6bf6256fc2f0e8a623585cc7d8aa79a3df7e.png)
4.  Select tracks in the timeline to which you want to match the tracks in the browser that display “Select Track in Timeline” or “Bus/Track Mismatch.” Those tracks are added to the Import Tracks browser as they are selected. Note that tracks that do not match by name are matched to tracks of the same type and format, if available. 

A preview of your matched tracks is shown in the timeline. 

When you have finished matching and adding tracks, click Import at the top of the browser. 

![imported-session-overlay.png](Importing%20Session%20Data_assets/3f54918331b54630ef1c891055d319d2b0a76c38.png)

*Previewing tracks to import*

## Selecting a session import range

You can select a range (duration) of the source session to import to the destination session.

#### To select a range to import

1.  After you configure your session import tracks, select a range on the Import Range ruler. You can drag the ruler and expand or contract either end of the ruler by clicking and dragging.
2.  Enable the import range by clicking the icon to the right of the Import Range label.

The import preview now highlights the range you are importing. Complete your import when you the range and import settings are correct.

![import-range.png](Importing%20Session%20Data_assets/a91307df45f0f1317578e658fe40515d35b4a381.png)

------------------------------------------------------------------------

# Configuring Import Settings

Configure Import Settings in the Import Session Data browser to choose what session data LUNA imports from the source session to the destination session.

![import-settings.png](Importing%20Session%20Data_assets/2b4fd03bf478b3cb317fde3a26cacb091d3bb476.png)

## Tempo & Time Signature

Choose this option to import the tempo and time signature from the imported session data. This overrides the settings in your current session. 

## Markers

Choose this option to import markers from the imported session. This replaces the markers in your current session with the markers from the imported session. 

## Global Tape Machine Settings

Choose this option to import global tape machine settings from the imported session. This replaces the tape machine settings for machines A–D with the settings from the source session, including any empty tape machine slots. 

## Track Settings

Choose this option to import all track settings from the imported session. Track settings include everything that is not audio, MIDI, automation, or playlist data:

- Inputs
- Volume
- Panning
- Plug-ins and instruments
- LUNA Extensions
- Sends
- Utility row settings
- Outputs 
- Track color

## Automation

Choose this option to import automation on tracks imported into the session. This will copy the automation onto newly created tracks, and replace the automation on existing destination tracks in your current session.

## Audio & Track Versions

Choose this option to import audio, MIDI, and versions on audio or MIDI tracks, including audio on frozen tracks.

### Replace / Merge / New Version

These mutually exclusive options control how audio and MIDI data is imported into the new tracks.

- **Replace** —  replaces any existing audio or MIDI data on a track with the source data 
- **Merge** —  merges any existing audio or MIDI data on a track with the audio or MIDI from the imported track
- **New Version**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> —  adds audio or MIDI data to the track on a new version</span>

<span class="wysiwyg-font-size-small"><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">260107</span></span>

