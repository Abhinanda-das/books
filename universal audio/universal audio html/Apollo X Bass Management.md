---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/30920209088404-Apollo-X-Bass-Management.html'
converted_at: 2026-05-31T13:44:51Z
tool: htmlq+pandoc
title: 'Apollo X Bass Management'
word_count: 1413
---

# Apollo X Bass Management


# Bass Management Overview

With Bass Management and your Apollo X Series interface, you can configure low frequency content filtering for your monitor speakers and LFE channel. You can configure bass management for all satellite channels at once, or for individual channel pairs, and the LFE channel in a surround monitoring system. 

Bass Management allows for smaller studio monitors and satellite speakers in stereo and surround arrays to operate more accurately in their correct frequency ranges, while low frequency information below the crossover point is reproduced by a dedicated subwoofer. 

In stereo monitor mode, you can add a subwoofer to your speaker system, define its low frequency content, and adjust all speaker levels simultaneously with UAD Console's level and mute controls. In stereo mode, an additional segment appears for S (sub) in the output level meter when bass management is enabled.

Bass management is applied before UAD Console’s level meters, so you can see the results of the filters in the meter output. Satellite crossover filters and the LFE low pass filter are variable 12 or 24 dB per octave Linkwitz-Riley filters.

**Note:** Bass management is not applied to ALT monitors, and is unavailable in LCR, LCRS, and QUAD Surround modes.

# Configuring Bass Management

Bass management is configured in UAD Console's Monitor Controller floating window. To open the Monitor Controller floating window:

1.  If the Monitor column isn’t visible, select  Section \> Monitor from the View menu.\
    \
    ![](Apollo%20X%20Bass%20Management_assets/a039526d48a5656e928395c651068def37e56294.png)\
    \
2.  Click the Monitor Controller button in the Monitor Column. 

**Note:** The Monitor Controller button only appears with Apollo X Series interfaces.  

![mon-controller-open-callout-2x.png](Apollo%20X%20Bass%20Management_assets/90fa54909480cf5bfde47340a20f5f74218b7ebf.png)

## Bass routing for Apollo X models

Bass management routes low frequency content to an Apollo X hardware output. Connect this hardware output to your low frequency monitor (for example, a subwoofer). 

**Note:** If you switch Apollo Monitor Modes between Stereo and Surround modes, the subwoofer output channel will change, and you will have to make the correct hardware connections. See [<span class="wysiwyg-underline" style="color: #1155cc;">Apollo X Rack Surround Sound</span>](https://help.uaudio.com/hc/en-us/articles/26817449653012) for surround channel routing details. 

### Stereo monitor mode

In Stereo monitor mode, bass content is routed to a specific output on each Apollo X model. Note that because one hardware output is used for bass content, features that require that output pair are limited. See the table below for more information. 

### Surround monitor modes

In a surround system, the LFE channel is routed to a specific hardware output already. See [<span class="wysiwyg-underline" style="color: #1155cc;">Apollo X Rack Surround Sound</span>](https://help.uaudio.com/hc/en-us/articles/26817449653012) for details. 

### Bass channel routing table (Stereo monitor mode)

<div>

<table style="width: 100%;">
<tbody>
<tr>
<td style="text-align: center; width: 33%;"><strong>Apollo X model</strong></td>
<td style="text-align: center; width: 33%;"><strong>Sub output channel</strong></td>
<td style="text-align: center; width: 34%;"><strong>Bass Management notes </strong></td>
</tr>
<tr>
<td style="text-align: center; width: 33%;"><p>Apollo Twin X<br />
Apollo Twin X Gen 2<br />
Apollo Twin X USB</p></td>
<td style="text-align: center; width: 33%;">4</td>
<td style="text-align: center; width: 34%;">ALT monitoring unavailable</td>
</tr>
<tr>
<td style="text-align: center; width: 33%;"><p>Apollo x4<br />
Apollo x4 Gen 2</p></td>
<td style="text-align: center; width: 33%;">4</td>
<td style="text-align: center; width: 34%;">ALT 2 unavailable</td>
</tr>
<tr>
<td style="text-align: center; width: 33%;"><p>Apollo x6<br />
Apollo x6 Gen 2</p></td>
<td style="text-align: center; width: 33%;">6</td>
<td style="text-align: center; width: 34%;"> </td>
</tr>
<tr>
<td style="text-align: center; width: 33%;"><p>Apollo x8<br />
Apollo x8 Gen 2<br />
Apollo x8p<br />
Apollo x8p Gen 2<br />
Apollo x16<br />
Apollo x16 Gen 2<br />
Apollo x16D</p></td>
<td style="text-align: center; width: 33%;">8</td>
<td style="text-align: center; width: 34%;"> </td>
</tr>
</tbody>
</table>

</div>

 

## Managing bass with the Bass Management panel

![](Apollo%20X%20Bass%20Management_assets/fe40e153b01bd64a57bf4ac3e1c56a964360f565.png)

*Bass Management panel in the Monitor Controller floating window* *\
(7.1 surround mode shown)*

## Enabling bass management

1.  In the Monitor Controller floating window, click the Bass Management tab. 
2.  Toggle bass management on/off with the ENABLE button. When bass management is enabled, the button is lit. 

## Adjusting crossover filter slopes

Filter crossover slopes can be set for the satellite speakers and for the LFE channel in a surround mode. Crossover filter slopes are configured for bass management system-wide, and not per-channel.

1.  From the Satellite Filter menu, select the crossover slope (12 dB or 24 dB per octave).
2.  (Surround modes only) From the LFE Filter menu, select the filter slope (12 dB or 24 dB per octave).

## Adjusting the crossover frequency for satellite speakers

Satellite speaker crossover frequencies can be set for each speaker pair, or for all speakers at once in a surround monitor mode. 

**Tip:** If you set the Satellite Crossover to OFF, no bass content is sent to the subwoofer channel. 

1.  In the Bass Management panel, select a satellite speaker or satellite speaker pair by clicking a speaker icon in the speaker display, or by selecting from the Channel menu. In Stereo mode the L/R speaker pair is selected, and is the only available pair. 
2.  From the Satellite Crossover menu, select the filter crossover frequency, The available satellite crossover values are OFF, 80 Hz, 100 Hz, or 120 Hz. 
3.  Repeat steps 1–2 for all channels. 

**Tip:** To adjust the Satellite Filter crossover for all satellite speakers, click SELECT ALL in the speaker display, or select ALL from the Channel menu. 

![](Apollo%20X%20Bass%20Management_assets/61f5ce452ec3480e988706eb1b8b60ed70461f00.png)

*Example L/R channel bass management settings*

## Adjust bass management features for the LFE channel (surround modes)

The LFE low pass filter (LPF) frequency can be set independently when any surround monitoring mode with an LFE channel is selected (surround modes without an LFE channel do not support bass management). The LFE Filter is applied to the signal from your audio source (DAW) to your LFE channel, and does not affect the signal to your satellite speakers. 

The Bass Management panel also allows you to add 10 dB of gain to the LFE channel, for the film mixing standard.

1.  In the Bass Management panel, select the LFE channel by clicking the LFE icon in the speaker display, or by selecting it from the Channel menu 
2.  From the LFE LPF menu, select the low pass filter frequency. The available LFE LPF values are OFF, 80, 100 Hz, 120 HZ, and 150 Hz. 
3.  Enable the LFE +10 dB button if you are mixing to the standard that allows 10 dB of extra headroom for the LFE channel.

![](Apollo%20X%20Bass%20Management_assets/00a29a65ca7c0437974a604f461b476f610e8130.png)

*Example LFE channel bass management settings*

## Additional Monitor Controller features for bass management

The Monitor Controller floating window includes other controls that can be used with bass management features. 

### Monitor mode

The Monitor Controller window provides easy access to the Monitor mode switch, so you can switch between stereo monitoring and supported surround modes for your Apollo X. Select a monitor mode from the drop menu to the left of the monitor level knob. Your Apollo X output routing is updated, and the speaker layout image is adjusted accordingly. For more information on surround modes, see [<span class="wysiwyg-underline" style="color: #1155cc;">Apollo X Rack Surround Sound</span>](https://help.uaudio.com/hc/en-us/articles/26817449653012), 

**Note:** Surround functionality is available with Apollo X rack models only.

### Monitor Level

This is the level control for Apollo’s monitor outputs. It performs the same function as the MONITOR hardware knob on Apollo X.

### SRND switch

Switches to the current surround monitoring mode. 

**Note:** This switch appears only when a surround monitoring mode is selected.  

### STR switch

Switches to stereo fold down. Click SRND to return to surround monitoring mode.

When stereo fold down is active, the bass management crossover follows the Stereo L/R speaker settings. When stereo fold down is active, center channels (including LFE/SUB) are attenuated by -3 dB and surround side channels by -1.5 dB. The main Left and Right channels are not attenuated. 

**Note:** This switch appears only when a surround monitoring mode is selected.  

### MONO switch

Switches to mono fold down. When mono fold down is active, the bass management crossover follows the Center channel crossover frequency, or the Stereo L/R speaker settings in 2.1 mode. When mono fold down is active, center channels (including LFE/SUB) are attenuated by -3 dB, surround side channels are attenuated by -7.5 dB, and the main Left and Right channels are attenuated by -6 dB.

### MUTE switch

Mutes all audio output. 

# Apollo DSP and Bass Management

Bass Management uses a small amount of DSP for filtering. 

The system incurs the following additional latency when Bass Management is enabled: 

- 1.5 ms at 44.1 kHz and 48 kHz
- 0.75 ms at 88.2 kHz and 96 kHz
- 0.7 ms at 176.4 kHz and 192 kHz

