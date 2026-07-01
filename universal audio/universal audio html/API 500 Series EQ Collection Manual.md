---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/32524771071636-API-500-Series-EQ-Collection-Manual.html'
converted_at: 2026-05-31T13:44:51Z
tool: htmlq+pandoc
title: 'API 500 Series EQ Collection Manual'
word_count: 1535
---

# API 500 Series EQ Collection Manual


## The world's most accurate emulations of API's legendary EQs.

The API 500 Series EQ Plug-In Collection for UAD-2 hardware and Apollo interfaces faithfully captures the punch, low-frequency transparency, and ultra-tight imaging of API’s iconic 550A and 560 Series EQs.

With unique filter shapes, complex band interactions, and musical filter amp distortions, the 550A and 560 Series EQs left an indelible stamp on legendary recordings of the ’60s and ’70s. Painstakingly modeled on pristine early-’70s units provided by Ross Hogarth and Capitol Studios, the API® 500 Series EQ Collection gives you stunningly accurate, end-to-end modeling of these revered EQs.

- Track and mix with full-circuit emulations of API's iconic 550A and 560 EQs
- Harness API's musical filter amp distortions and musical clipping behaviors
- Use API's proprietary "Proportional Q" for more precise control over your sources
- Mix with artist presets from Ross Hogarth (Van Halen, Mötley Crüe), Darrell Thorp (Beck, Radiohead), and Vance Powell (Jack White, Kings of Leon)

## 550A Parametric EQ

Introduced in 1971, the 550A was the standard channel EQ module on API's first consoles. Its three overlapping bands of parametric EQ, independent 50 Hz to 15 kHz band-pass filter, and individually selectable peaking or shelving modes make it the perfect tool for getting drums and guitars to stand out in the mix.

## 560 Graphic EQ

With ten bands of graphic EQ, the 560 EQ is ideal for shaping your mix with surgical precision. API's proprietary "Proportional Q" intuitively widens bandwidth at lower boost/cut levels and narrows it at higher levels, giving you more musical control over precise bands of your mix.

|  |  |
|:--:|:--:|
| ![API-550A.png](API%20500%20Series%20EQ%20Collection%20Manual_assets/cbd4650e8a0a48b7b73152954c3a87a7ae5ceaeb.png) | ![API-560.png](API%20500%20Series%20EQ%20Collection%20Manual_assets/1bf7dc053524722cd327dce73e449e24e34ce7be.png) |

*API 550A EQ (left) and API 560 EQ (right)*

# Operational Overview

## API 500 Series Collection

The API 500 Series EQ Collection includes the API 550A and API 560 plug-ins, which are officially licensed from and endorsed by Automated Processes Inc. Both plug-ins meticulously model the entire electronic path, including custom API 2520 op-amps, transformers, band interactions, and internal clipped filter nonlinearities.

## API 550A

The API 550A provides reciprocal equalization at 15 points in five steps of boost or cut to a maximum of ±12 dB of gain at each point. The fifteen fixed equalization points are divided into three overlapping band ranges. The high and low frequency bands are individually selectable to function as either peaking or shelving filters. A bandpass filter may be inserted independently of all other selected equalization settings.

## API 560

The 10 precision EQ bands make the 560 ideal for signal sweetening and mix tuning. The boost and cut characteristics are identical, allowing previous actions to be undone if desired.

## Proportional Q

The 550A and 560 filters feature API's "Proportional Q" which continuously narrows the bandwidth of the filter as band gain is increased, providing (as stated by API) "an uncomplicated way to generate acoustically superior equalization."

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

# API 550A Controls

## Band Controls

The three EQ bands (HF/MF/LF) are controlled by dual-concentric switches. The inner knob controls the band frequency and the outer knob controls the band gain. Available values for these controls are listed in the table below.

<table style="border-collapse: collapse; width: 80%; margin-right: auto; margin-left: auto;">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr>
<th style="width: 33.3333%">Band</th>
<th style="width: 33.3333%">Frequency Values</th>
<th style="width: 33.3333%">Gain Values (±dB)</th>
</tr>

<tr>
<td style="width: 33.3333%">High Frequency</td>
<td style="width: 33.3333%">5, 7, <strong>10</strong>, 12.5, 15 (kHz)</td>
<td rowspan="3" class="wysiwyg-text-align-center" style="width: 33.3333%">0<br />
2<br />
4<br />
6<br />
9<br />
12</td>
</tr>
<tr>
<td style="width: 33.3333%">Mid Frequency (MF)</td>
<td style="width: 33.3333%">0.4, 0.8, <strong>1.5</strong>, 3, 5 (kHz)</td>
</tr>
<tr>
<td style="width: 33.3333%">Low Frequency (LF)</td>
<td style="width: 33.3333%">50, 100, <strong>200</strong>, 300, 400 (Hz)</td>
</tr>
<tr>
<td colspan="3" class="wysiwyg-text-align-center" style="width: 33.3333%"><em>Default values are in <strong>bold</strong></em></td>
</tr>
</tbody>
</table>

*API 550A Frequency and Gain Values*

### Frequency

Frequency determines the center frequency of the band when the filter is in peak mode and the cutoff frequency when the filter is in shelf mode. The frequency for the band can be set using any of these four methods:

1.  Drag the inner concentric knob to the desired value, or
2.  Hover over the inner concentric knob then use the mouse scroll wheel, or
3.  Click directly on the frequency value label to switch to that value, or
4.  Click on the band label (HF/MF/LF) or units label (kHz/Hz) to cycle through available values.

### Gain

The gain for the band can be set using any of these four methods:

- Drag the outer concentric knob handle to the desired value
- Click the "+" or "-" text labels to increment/decrement values
- Hover over the outer concentric knob then use the mouse scroll wheel
- Click directly on the gain value label to switch to that value (this method works only when Controls Mode is set to "Circular" in the UAD Meter & Control Panel application's Configuration panel)

## Bandpass Filter (FLTR)

The FLTR switch applies a 50 Hz - 15 kHz bandpass filter to the entire signal. The bandpass filter is completely independent from the from the three main band filters.

## Bell/Shelf Switches

The HF and LF bands are normally in bell mode. When the Bell/Shelf button is engaged for the band (in the darker "down" position), the band is switched to shelving mode.

LF Shelf

When the LF Shelf button is engaged, the low frequency band is switched to shelving mode.

HF Shelf

When the HF Shelf button is engaged, the high frequency band is switched to shelving mode.

## Output

This control provides -24 dB to +12 dB of clean uncolored gain at the output of the plug-in.

**Tip:** Click the "0" text label to return Output to the 0 dB position.

## EQ In

The EQ In switch enables the three band filters and the bandpass filter. All filters are active when the switch is engaged and the "IN" LED is illuminated.

When disengaged, the filters are bypassed but other hardware circuitry is still modeled.

## Power

The plug-in is active when the POWER switch is engaged and its associated LED is illuminated. When this switch is off, all plug-in processing is disabled and UAD DSP usage is reduced (unless UAD-2 LoadLock is enabled).

# API 560 Controls

**Note:** As with the original 560 hardware, the signal is boosted by approximately 1 - 1.5 dB even when all gain sliders are set to 0 dB.

## Gain Sliders

Each of the 10 sliders controls the gain for one frequency band. Each band can be adjusted to boost or cut the frequency by up to ±12 dB. The available band frequencies are listed below.

## API 560 Frequencies

|       |       |        |        |        |       |       |       |       |        |
|-------|-------|--------|--------|--------|-------|-------|-------|-------|--------|
| 31 Hz | 63 Hz | 125 Hz | 250 Hz | 500 Hz | 1 kHz | 2 kHz | 4 kHz | 8 kHz | 16 kHz |

**Tip:** To return a slider to the 0 dB position, click the slider's frequency text label. To reset all sliders to 0 dB, click the "0" text label above the sliders.

## Output

This control provides -24 dB to +12 dB of clean uncolored gain at the output of the plug-in.

**Tip:** Click the "0" text label to return Output to the 0 dB position.

## EQ In

The EQ In switch enables the filter sliders. The EQ bands are active when the switch is engaged and the associated "IN" LED is illuminated.

When disengaged, the EQ bands are bypassed but other hardware circuitry is still modeled.

## Power

The plug-in is active when the POWER switch is engaged and its associated LED is illuminated. When this switch is off, all plug-in processing is disabled.

# Historical Background

API (Automated Processes Inc.) was formed in 1968 with Saul Walker and Lou Lindauer. API is perhaps most noted for their modular approach to equipment manufacturing and for their now legendary 2520 amplifier. To this day, the extraordinary headroom made possible with the 2520 offers consistent analog performance even when using radical EQ curves. API quickly became the leading audio broadcast console manufacturer for radio and television networks and high profile stations. Soon after, recording studios both large and small began using API. The API brand and the company's commitment to excellent audio design endures to this day.

The 550A became API's standard channel module EQ when the company began manufacturing consoles in 1971. As the industry rapidly embraced the sonic quality of the 550A, it quickly found it's way into many custom console designs by Frank DeMedio and other leading engineers. Many of these consoles are still in use today. Forty years later, the 550A remains the standard against which other EQs are measured, and it has played a major role in the recording industry for decades. With virtually all existing units spoken for, popular demand for this EQ resulted in API finally resuming production in 2004.

![API-500-HW.png](API%20500%20Series%20EQ%20Collection%20Manual_assets/dc9a34b43647a813d40dd10b4b4c1c989640d356.png)

*The API 500 Series EQ Collection Original Hardware*

 

