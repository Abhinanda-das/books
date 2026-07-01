---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/26793892701460-Using-LUNA-in-Windows.html'
converted_at: 2026-05-31T13:44:50Z
tool: htmlq+pandoc
title: 'Using LUNA in Windows'
word_count: 556
---

# Using LUNA in Windows


<span style="color: #3f3f3f;">LUNA in Windows supports most of the same features as LUNA on macOS. </span>

## LUNA session compatibility

LUNA sessions are cross-platform compatible. However, because LUNA on macOS can use the Audio Units plug-in format for third party plug-ins, third-party Audio Units plug-ins do not load when you open a session in Windows that was created on a Mac.

All VST 3, UAD-2 and UADx plug-ins and all LUNA Extensions load on both platforms.

**Note**: Spitfire LUNA Instruments are not available on Windows systems.<span style="color: #3f3f3f;"> </span>

## Opening LUNA sessions on Windows

Because LUNA sessions use a package format that is not supported on Windows, there is currently no way to double-click a session to open it in Windows.

#### To open an existing LUNA session that is not in the Recent list in LUNA’s create page:

- Use Open From Disk… button or the File \> Open menu item, locate the session folder and click Open.
- Navigate to the session folder in File Explorer, and double-click the shortcut Open Session in the folder.

When you open the session folder with either of these methods, LUNA loads the session.

## Apollo Thunderbolt feature support on Windows

All but one feature of the advanced LUNA integration with Apollo works identically between macOS and Windows. On Windows ARM (Accelerated Realtime Monitoring) mode for virtual instruments is not implemented. On macOS, virtual instruments automatically run at a lower buffer size in ARM mode. On Windows, this feature is not currently supported. To achieve the lowest latency with virtual instruments in ARM mode on Windows, manually reduce the ASIO buffer size.<span style="color: #3f3f3f;"> </span>

## Windows system requirements

Windows 10 and Windows 11 are supported. For other general LUNA and UA hardware system requirements, <a href="360041532932-LUNA-System-Requirements.html" rel="noopener noreferrer" target="_blank"><strong>view this page</strong></a>.

## LUNA file locations

The file paths of all LUNA-related files are listed here.

- **LUNA Application:** C:\Program Files\LUNA

- **UADx Plug-ins / LUNA Instruments:** C:\Program Files\Common Files\Universal Audio\\

- **Sessions Default:** Documents\LUNA Sessions

- **User Presets, Favorites:** Documents\Universal Audio

- **Log Files:** C:\Users\[user_name\]\AppData\Local\UniversalAudio\Logs

- **Preferences:** C:\Users\[user_name\]\AppData\Roaming\LUNAPrefs.json

- **Workspace Cache:** C:\Users\[user_name\]\AppData\Local\Universal Audio\workspace

- **Plug-in Cache folder:** C:\Users\[user_name\]\AppData\Local\Universal Audio\workspace\plugin_cache

<div>

## Known issues with LUNA on Windows

Here is a list of notable issues we are currently aware of:

- LUNA should be installed and used on an **Administrator user account**.
- Various third-party VST3 Plug-ins demonstrate key passthrough issues, which prevents the Space bar from starting or stopping the transport while such a plug-in is in focus, and may cause odd behavior when starting or stopping the transport
- Graphical issues can occur in LUNA and third-party VST3 plug-in GUIs at scaling settings greater than 100%. It is currently recommended to run LUNA at 100% scaling
- Using the Apollo Thunderbolt driver as an ASIO playback/recording device in a DAW, as the WDM system audio device simultaneously can cause severe audio integrity issues. This is not a LUNA-specific issue. If using Apollo Thunderbolt for ASIO playback/recording in a DAW, use a different audio device for WDM system audio.
- There are some key commands that we were unable to implement in LUNA for Windows, because of the lack of available modifier keys. To see available key commands, choose Help \> Show Keyboard Shortcuts, or visit [this article](26788810000788-Default-LUNA-Keyboard-Shortcuts-and-Menu-Reference-Windows.html).

<span class="wysiwyg-font-size-small">260324</span>

</div>

