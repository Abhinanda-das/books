---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/17949313152532-Using-an-External-Sidechain-with-UAD-Plug-Ins.html'
converted_at: 2026-05-31T13:44:45Z
tool: htmlq+pandoc
title: 'Using an External Sidechain with UAD Plug-Ins'
word_count: 1072
---

# Using an External Sidechain with UAD Plug-Ins


## In this article

- <a href="#h_01H7BND8BVK7FHHE3CS96S8ZKM" target="_self">Sidechain source and destination</a>
- <a href="#h_01H7BNDKTYHMPD0ZBGTK1BC311" target="_self">Configuring a sidechain in your DAW</a>
- <a href="#h_01H7BNDTDJEEWHENGJKJYMCN3E" target="_self">Configuring an external sidechain with UADx plug‑ins in FL Studio</a>

Sidechaining allows you to use the audio output from one source to key, or trigger, an effect such as a compressor on another source. Sidechaining is generally used with compression, but any processor (typically a dynamically-triggered processor) that supports sidechaining can be used. For example, a gate can be triggered to silence a tom channel when the snare is hit, or an expander can be triggered to bring up room tone on a snare hit. 

Currently, the following native UADx processors support external sidechain:

- API 2500 Bus Compressor
- API Vision Channel Strip
- Capitol Mastering Compressor
- SSL 4000 E Channel Strip
- SSL 4000 G Bus Compressor 

# Sidechain source and destination

Sidechaining requires a source and destination: typically a source track (the audio source that will trigger the processor), and a destination (the audio processor on a track that will be triggered by the source audio). 

- The sidechain *source* can be any audio, instrument, or bus track, depending on what your DAW supports, and does not require any plug-ins.
- The sidechain *destination* depends on your DAW. In some DAWs (for example, FL Studio), you route the source to the destination track, then configure the sidechain behavior in plug-in options. In LUNA, you route the sidechain directly to the source track, using the plug-in and LUNA browser.

# Configuring a sidechain in your DAW

Each DAW handles external sidechaining differently. In this article, we include a sidechain example for FL Studio. 

You can find other external sidechain examples on our support site.

- For sidechaining with LUNA, [go here](4838035578516-Sidechaining-in-LUNA.html). 
- For sidechaining with Ableton Live, <a href="https://www.youtube.com/watch?v=Emyt-hEDllw" target="_self">go here</a>.
- For sidechaining with Cubase, <a href="https://www.youtube.com/watch?v=r-wjJSZOshM" target="_self">go here</a>.
- For sidechaining with Logic, <a href="https://www.youtube.com/watch?v=yaMrPR3AH2A" target="_self">go here</a>.
- For sidechaining with Pro Tools, [go here](18479403068820-FAQ-How-do-I-use-external-sidechain-in-my-DAW.html#h_01H8CKV769RESWJRBGJD7BFP5P).

## About external sidechain configuration

Each sidechain-capable UADx plug-in includes a Sidechain switch on the control bar. In most instances, you cannot enable this switch unless the correct sidechain routing is configured in the DAW. This switch is usually enabled automatically when the DAW sidechain routing to the plug-in is configured. 

  ![fl-sc-sidechain-ui.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/e752add6e9a8807d2bb147a48455950f97240e8a.png)

## About DAW sidechain configuration

In your DAW, you typically need the following configuration items to enable external sidechain with a plug-in.

- A source track that will provide the key to the sidechained plug-in
- A destination track that includes the plug-in to be keyed from the source, and the destination audio track or instrument plug-in to be effected
- Mixer routing or sidechain routing
- Some DAWs require further key input or source routing within the plug-in interface to complete the sidechain configuration

# Configuring an external sidechain with UAD plug‑ins in FL Studio

In FL Studio, sidechaining is accomplished by configuring a sidechain route in the FL Studio mixer, then configuring the plug-in options to accept audio from the sidechain source.

In this example, we use the output of a kick drum track to trigger an API 2500 compressor on a synth track. This can add movement and "pumping" to the destination track. 

**Note:** You can use any combination of Mixer tracks that you like, and any supported UADx processor. For this example, we are using Mixer tracks 1 and 2, and the API 2500 Bus Compressor plug-in. 

#### Configure mixer tracks for external sidechain

1.  Assign the source channel in FL Studio's Channel Rack to a Mixer track. In this example, we've assigned a kick channel to Mixer track 1.\
    To assign a mixer track, click in the Mixer track routing box and drag up or down to choose a Mixer track. 
2.  Assign the destination channel (the channel that will include your plug-in and the source to be modified by the sidechain input) to a separate Mixer track. In this example, we've assigned a PolyMAX synth channel to Mixer track 2. 
3.  Assign any other channels to separate mixer tracks that will not interfere with the sidechain.\
    \
    ![fls-sc-mixer-assignments.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/a8da915f6023ff4e3af69e6a2ea5a057d785bab8.png)\
    \
4.  Double-click the Mixer track routing slot to open the Mixer, or choose View \> Mixer from the FL Studio menus.\
    The Mixer opens.

#### Create the mixer sidechain routing connection

In FL Studio, you assign the mixer sidechain routing connection from one channel to another by selecting the source first, then right-clicking to assign the sidechain on the destination.

1.  Double-click the Mixer track routing slot to open the Mixer, or choose View \> Mixer from the FL Studio menus.\
    The Mixer opens.
2.  Select the sidechain source mixer track.\
    This track contains the audio output that you want to use to trigger the sidechain.
3.  On the sidechain destination track (the track with the plug-in you want to be triggered by the sidechain source), right-click the triangle under the track fader, and choose Sidechain to this track.\
    \
    ![fl-sc-sidechain-configure.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/b0810faabb2a49a8bc994fa582f3457e0b95536c.png)\
    \
    ![fl-sc-routing-created.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/e561e5b4a961cde2f52424c2e3d96dc00959dd84.png)

The sidechain routing is created.

#### Configure the plug-in sidechain

1.  On the sidechain destination mixer track, assign the UAD plug-in. In this example, we use the UADx API 2500 Bus Compressor.\
    \
    ![fl-sc-assign-plug-in.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/7e23e73e206ea2e8310487d7c06be9534d8bdbe8.png)\
    \
    The plug-in interface opens. If the plug-in is not open, click the plug-in name in the mixer to open the interface. 

<!-- -->

2.  On the plug-in, click the gear icon to open the plug-in's detailed settings.\
    \
    ![fl-sc-plug-in-detailed-settings.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/a8df2b8171a12818ac09e9c5d5e9de190e1fb072.png)\
    \
3.  Click the combined plug and gear icon to open the plug-in wrapper settings.\
    \
    ![fl-sc-wrapper-settings.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/107562722cc7b3ee1b197d95fb695aa1b16259de.png)\
    \
4.  Under Connections, next to the label "2.sidechain", click the circle to enable the sidechain. Click in the field to the left of label "2.sidechain" and drag to select the Mixer track that is the sidechain source. In this example, the sidechain source is Mixer track 1.\
    **Note:** In the Audio Units version of the plug-in, the primary and sidechain connections are labeled "Node 0" and "Node 1".\
    \
    ![fl-sc-processing-tab-connections.png](Using%20an%20External%20Sidechain%20with%20UAD%20Plug-Ins_assets/b58e1fffdd540dc7d2c37b3c50ea46a05870b40f.png)
5.  The plug-in now receives key input from the sidechain source Mixer track. Click the plug icon again to return to the plug-in interface, and configure the plug-in settings.
6.  Start playback to audition the effect, and adjust the Threshold control of the plug-in to adjust sensitivity to the sidechain input.
7.  Toggle the Sidechain switch in the plug-in toolbar to enable or disable the sidechain for quick comparison.

