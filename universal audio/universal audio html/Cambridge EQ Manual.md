---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/33030796802068-Cambridge-EQ-Manual.html'
converted_at: 2026-05-31T13:44:51Z
tool: htmlq+pandoc
title: 'Cambridge EQ Manual'
word_count: 2156
---

# Cambridge EQ Manual


## Overview

Cambridge EQ is a mastering-quality, no-compromise equalizer that enables powerful tonal shaping of any audio source. Its algorithm was modeled from various high-end analog filters, providing a sonically rich foundation for timbral manipulation. Special attention was given to the handling of higher frequencies, resulting in a much smoother and more satisfying high-end response than is found in most digital filters.

Cambridge EQ is highly flexible, offering a broad spectrum of options facilitating surgical precision and delivering superior aural results in every application. This may be the most satisfying, full-featured equalizer in your arsenal of creative tools.

<div class="wysiwyg-text-align-center">

![Cambridge-zoom.png](Cambridge%20EQ%20Manual_assets/2b31862f8ea011f1c46e9bc142724a3abd302885.png)

</div>

*Cambridge EQ*

------------------------------------------------------------------------

# Cambridge EQ Controls

Each feature of the Cambridge EQ interface is detailed below.

## EQ Response Curve Display

The EQ Response Curve Display plots the frequency response of the current Cambridge EQ settings. It provides instant visual feedback of how audio is being processed by the equalizer.

The entire audio spectrum from 20 Hz to 20 kHz is displayed along the horizontal axis. Gain and attenuation of frequencies (up to ±40 dB) are displayed along the vertical axis. The vertical resolution of this display can be modified with the Zoom buttons.

## Response Curve Color

The color of the response curve depends on the value of the \[A/B Selector Button\]. When A is active, the curve is yellow. When B is active, the curve is green. When Cambridge EQ is disabled, the response curve is grey.

## Zoom Buttons

The vertical scale of the Curve Display can be increased or reduced with the Zoom buttons. This function allows the resolution of the Curve Display to be changed for enhanced visual feedback when very small or very large amounts of boost or cut are applied. Four vertical ranges can be selected with the Zoom buttons: ±5, ±10, ±20, and ±40 dB.

<div>

</div>

<div>

<div>

</div>

<div class="wysiwyg-text-align-center">

![cambridgezoomout.png](Cambridge%20EQ%20Manual_assets/c14dd53defe78b0d340bdb4970601b28bdde52c6.png)

</div>

<div class="wysiwyg-text-align-center">

![cambridgezoomin.png](Cambridge%20EQ%20Manual_assets/623d14f9bfed98148360086de1b6087718beab16.png)

</div>

<div class="wysiwyg-text-align-center">

![cambridgezoom.png](Cambridge%20EQ%20Manual_assets/beabe35db01b84557923047571f32bca5cd32bdf.png)

</div>

</div>

*Vertical resolution of the Response Curve can be changed with the Zoom buttons*

## Curve Control Bats

There are five control “bats” on the curve display. Each bat is color coded and corresponds to each of the five EQ bands. The position of the bat on the curve display reflects the frequency and gain of its corresponding band, even if the band is disabled.

The gain and frequency of an EQ band can be modified simultaneously by dragging its bat with the mouse. If a band is disabled when its bat is touched for the first time, the band is enabled.

**Note:** To modify the Q of a band with its bat, hold down the Control key while dragging vertically.

When a band is enabled, the EQ curve usually touches the bat. However, because the EQ curve always displays the actual frequency response of Cambridge EQ, if two bands are close together in frequency and/or at extreme gain values, the bat may not touch the curve itself.

## Master Level Knob

This control adjusts the signal output level of Cambridge EQ. This may be necessary if the signal is dramatically boosted or reduced by the EQ settings. The available range is ±20 dB.

## A/B Selector Button

The A/B Selector switches between two separate sets of Cambridge EQ plug-in values. This feature enables easy switching between two completely independent EQ curves which can be useful for comparison purposes or for automating radical timbre changes. Both the A and B curves reside within a single Cambridge EQ preset.

Click the A/B Selector button to switch between the two curves. When A is displayed, the button and the EQ response curve is yellow. When B is displayed, the button and the curve is green.

**Note:** To reset the A or B curve to a null (flat) response, control-click the A/B Selector button. The active curve will be nulled.

**Note:** To copy one curve to another, shift-click the button. The active curve will be copied to the inactive curve.

## EQ Enable Button

This button enables or disables the Cambridge EQ altogether. You can use this switch to compare the processed settings to that of the original signal, or to bypass the plug-in to reduce UAD DSP load (load is not reduced if UAD-2 DSP LoadLock is enabled).

------------------------------------------------------------------------

# Low Cut / High Cut Filters

The Low Cut and High Cut filters are offered in addition to the five parametric/shelf bands. A wide range of filter types is provided to facilitate tonal creativity. Many filters that are available are represented.

Three controls are offered: Cut Type, Enable, and Frequency. Each control is detailed below.

## Cut Type Menu

The Cut Type menu determines the sound of the low and high cut filters. To view the Cut Type menu, click and hold the green cut type button.

Four types of responses are provided: Coincident Pole, Bessel, Butterworth, and Elliptic. The numbers represent the filter order, i.e. Bessel 4 is a fourth-order filter. Each offers a different sound. To select a new cut response, drag to the desired response and release.

The responses are more gentle on filters with lower numbers, and get steeper and more aggressive as the numbers increase. The coincident-pole filters are first-order filters cascaded in series and offer gentle slopes. Bessel filters are popular because of their smooth phase characteristic with decent rejection. Butterworth filters offer even stronger rejection. The Elliptic setting is about as “brick wall” as you can get. Generally speaking, more phase shifting occurs as the response gets steeper.

**Note:** UAD DSP usage does increase some as the filters get stronger (unless UAD-2 DSP LoadLock is enabled).

## Cut Enable Button

This button activates the cut filters. The filters are enabled when the “In” button is green. UAD DSP usage is slightly reduced when the cut filters are disabled (unless UAD-2 DSP LoadLock is enabled).

## Cut Frequency Knob

This knob determines the cutoff frequency for the Cut filters. The available range is from 20 Hz – 5 kHz for the low cut filter, and 20 Hz – 20 kHz for the high cut filter.

------------------------------------------------------------------------

# EQ Bands

All five of the EQ bands can be used in parametric or shelf mode. Each band has identical controls, the only difference is the frequency range values.

The function of the controls is similar in both parametric and shelf modes. The two modes are described separately (see \[Parametric EQ\] and \[Shelf EQ\]).

<div class="wysiwyg-text-align-center">

![Cambridge-zoom-2.png](Cambridge%20EQ%20Manual_assets/88a37581f92a0ce0c19cd7ae29cc9ff6e88463c4.png)

</div>

*The EQ band controls*

## Enable Button

Each band can be individually engaged with the Enable (IN) button. The button is green when the band is enabled. All bands default to disabled. To enable any band, click the Enable button.

You can use these buttons to compare the band settings to that of the original signal, or to bypass the individual band. UAD DSP usage is slightly decreased when a band is disabled (unless UAD-2 DSP LoadLock is enabled).

## Frequency Knob

This parameter determines the center frequency to be boosted or attenuated by the Gain setting. The available range for each of the five bands is the same for both parametric and shelf modes. The ranges are shown in the table below.

### Available Band Frequency Ranges

|                            |                 |
|----------------------------|-----------------|
| Low Frequencies (LF)       | 20 – 400 Hz     |
| Low-Mid Frequencies (LMF)  | 30 – 600 Hz     |
| Mid Frequencies (MF)       | 100 Hz – 6 kHz  |
| High-Mid Frequencies (HMF) | 900 Hz – 18 kHz |
| High Frequencies (HF)      | 2 kHz – 20 kHz  |

## Gain Knob

This parameter determines the amount by which the frequency setting for the band is boosted or attenuated. The available range is ±20 dB.

## Q (Bandwidth) Knob

The behavior of the Q parameter varies depending on the band mode and the gain. For this reason Q is detailed separately in the [Parametric Q](#h_01JF23VW1QFM6WXFEM70YSV45X) and [Shelf Q](#h_01JF23XTTPTQMQS95Z5W1P1T3C) sections.

------------------------------------------------------------------------

# Parametric EQ

A band is in parametric mode when the [Shelf Enable Button](#h_01JF23XHTE9FD6225XH3EN60AJ) is disabled. Three types of parametric EQ are available, as determined by the Parametric Type selector.

## Parametric Type Selector

The Parametric Type selector changes the response of the band controls to reflect the behavior of various analog equalizers. It is a global control for all 5 bands, and has no effect on the low and high cut filters. Click the Parametric Type display to rotate between Types I, II, and III.

The filter algorithm is the same in all three parametric types. The difference is in the dependency between the gain and Q parameters. Each parametric type has its own response characteristics.

In Type I mode, the Q remains constant regardless of the gain setting. In Type II mode, the Q increases as gain is boosted, but remains constant as gain is attenuated. In Type III mode, the Q increases as gain is boosted and attenuated.

## Parametric Q

The Q (bandwidth) knob sets the proportion of frequencies surrounding the center frequency to be affected by the gain control. The Q range is 0.25-16; higher values yield sharper slopes.

Note that the Q numeric value in relation to its knob position is warped (i.e. not linear) and varies according to the parametric type.

## Type I

When set to Type I, the bandwidth remains at a fixed Q regardless of the gain setting for the band; there is no Q/Gain interdependency. In addition, there is a finer resolution of the Q knob in the middle of its range. This makes it easier to achieve subtle bandwidth changes. Note that the Q value and knob positions do not change as the gain is modified.

![camb-typeI.png](Cambridge%20EQ%20Manual_assets/ae8db7ae26506ff31b4a77c766c08171a4351d16.png)

*Parametric Type I response*

## Type II

When set to Type II, there is a Q/Gain dependency on boost. The bandwidth increases continuously as the gain is boosted, but not when attenuated. The Q knob position determines the maximum Q at full gain.

Filter bandwidth is broader at lower boost settings and narrower at higher boost settings. This can produce a smoother, more natural response when boosting filter gain.

Note that the Q value increases as gain is boosted but the knob position does not change The Q value is approached as gain increases, and reaches the knob position at maximum gain.

<div class="wysiwyg-text-align-center">

![camb-typeII.png](Cambridge%20EQ%20Manual_assets/43899aee2f7255bfa47d01fb5ec06b17fb39e5e0.png)

</div>

*Parametric Type II response*

## Type III

When set to Type III, there is a Q/Gain dependency on boost and attenuation. The bandwidth increases continuously as the gain is boosted and attenuated. The Q knob position determines the maximum Q at full gain.

Filter bandwidth is broader at lower gain settings and narrower at higher gain settings. This can produce a smoother, more natural response when adjusting filter gain.

Note that the Q value increases as gain is increased but the knob position does not change The Q value is approached as gain increases, and reaches the knob position at maximum gain.

<div class="wysiwyg-text-align-center">

![camb-typeIII.png](Cambridge%20EQ%20Manual_assets/77833ea806402075b56cbd701d48e6df577f9851.png)

</div>

*Parametric Type III response*

------------------------------------------------------------------------

# Shelf EQ

## Shelf Enable Button

Each band can be switched from parametric mode to shelf mode by clicking the shelf enable button. The button is off by default. To enable shelving on any band, click the shelf button.

The button is green when shelving is enabled. Additionally, the control bat associated with the band has a horizontal shelf indicator line in the response curve display when shelf mode is active.

## Shelf Type Button

When a band is in shelf mode and its Q is above the minimum value, a resonant peak occurs in the filter response. The Shelf Type button affects where this resonant peak occurs in relation to the shelf frequency.

Its purpose is to emulate the response curves of classic high-end analog mixing consoles. It’s yet another tool to help you find the exact sound you are looking for.

The Shelf Type button places the resonant peak at the edge of the stopband (Shelf Type A), the edge of the passband (Shelf Type B), or at the edge of the stopband and the passband (Shelf Type C). These response curves are shown below.

<div class="wysiwyg-text-align-center">

![cambridge_shelf_a.png](Cambridge%20EQ%20Manual_assets/b2e225db9ce25ad98415c21f7a04d3751dbb889d.png)

</div>

*Shelf Type A*

<div class="wysiwyg-text-align-center">

![cambridge_shelfindline.png](Cambridge%20EQ%20Manual_assets/8a698d9bfc8a91eba55b59767a14017a014e21a6.png)

</div>

*Shelf Type B*

![shelf-c.png](Cambridge%20EQ%20Manual_assets/fcdaf174eb173b4065afa21b595e2cb8bc3a3261.png)

*Shelf Type C*

## Shelf Q

When a band is in shelf mode, the Q knob sets the resonance of the band. The range of the Q knob is 0-100% when in shelf mode.

**Note:** When a band is in shelf mode, the Gain setting will affect the Q of the band.

When the Q is at its minimum value, there is no resonant peak. The resonance increases and becomes more prominent as the Q is increased. Therefore, for the shelf type to have any effect the Q must be above its minimum value.

**Note:** In order for this button to have any affect, the band must be in shelving mode, some gain must be applied, and the Q must be above its minimum value.

