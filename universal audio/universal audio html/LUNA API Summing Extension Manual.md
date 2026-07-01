---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360052390811-LUNA-API-Summing-Extension-Manual.html'
converted_at: 2026-05-31T13:44:56Z
tool: htmlq+pandoc
title: 'LUNA API Summing Extension Manual'
word_count: 1078
---

# LUNA API Summing Extension Manual


 

- [API Summing Features](#h_01EPD01YJSCK981E0E07Q2RVKK)
- <a href="#h_01EPD02RSZWNDPB4D5GTX0K188" target="_self">Genuine API Summing for your Mixes</a>
- <a href="#h_01EPD02ZWBZFFYKXB86479F2CJ" target="_self">Why API Summing?</a>
- <a href="#h_01EPD03KV6BF5QSJWVWDSABMAM" target="_self">Getting it Right</a>
- <a href="#h_01EP5MG5QGGF35N8AYX3S0XCP2" target="_self">Get API Summing</a>
- <a href="#h_01EP5MGAZ74FV1SAT6H45ANP6N" target="_self">Using API Summing</a>
- <a href="#h_01EP5MH6VFVFGP19QHSQRZCPAX" target="_self">Console Summing fader taper</a>

The sound behind five decades of landmark albums, API® consoles are legend for good reason. From Stevie Wonder's *Talking Book* and Fleetwood Mac's *Rumours*, to The Cure's *Pornography* and Radiohead's *Hail to the Thief* — the mid-forward punch of API's classic analog consoles breathe aggressive, multi-dimensional color into your mixes.

Developed in partnership with API, exclusively for LUNA Recording System, the API Summing Extension emulates the 2520 op-amp and custom output transformers found in legendary API consoles over the past 50 years — giving your LUNA mixes all the attitude and tone of API's esteemed analog desks.

# API Summing Features

Easily add power, clarity, and mid-forward punch to your mixes with the first authentic emulation of API analog summing

- Sum individual channels or your entire mix through API's hallowed bus or master summing modules

- Harness the complex nonlinearities and musical clipping that define the API sound 

- Use per-bus Headroom and Trim controls for subtle tone sculpting over your entire mix

# Genuine API Summing for your Mixes

Taking you beyond any summing plug-in, the API Summing Extension is built into LUNA's mixer, capturing the sonic detail of API's iconic bus channels. This workflow eliminates the need to manage multiple plug-in windows. Simply push up faders and use the per-bus Headroom control to add character and dynamic enhancement.

# Why API Summing?

When audio sources flow through an API console — specifically the 2520 op-amp and custom output transformer — random analog nonlinearities work together, producing complex, musical harmonics and transient clipping. These summed signals add punch, depth, and character for a mid-forward, lively mix.

# Getting it Right

UA dissected and studied multiple API consoles — pouring over original service manuals and gaining crucial insight into their discrete Class A operation and hybrid voltage/current summing circuitry — in contrast to the Neve 80 series pure current summing. UA's team of engineers throughly emulated all of the nonlinearities and clipping characteristics, plus API console fader taper and pan law, giving you the same chart-topping results as API's flagship consoles.

![api-summing-overview.png](LUNA%20API%20Summing%20Extension%20Manual_assets/5d174c91f16c2f1c451416eb4d4c11e8aaae53f4.png)

# Get API Summing

You can purchase the optional API Summing LUNA Extension from the UA store. Click the [Store](https://www.uaudio.com/collections/uad-plugins) link in LUNA's Manage panel. After purchasing, there is nothing to download, as the extension is built into the fabric of LUNA.

# Using API Summing

API Summing imparts the sound and headroom characteristics of an API console bus channel directly into the LUNA summing buses. You can add API Summing to Bus and Main tracks.

#### To add API Summing:

- In the Input row of a bus or the Main track, click the Summing button, and choose API Summing.
- If desired, set the controls for Headroom (HR) and Trim.

![summing-select.png](LUNA%20API%20Summing%20Extension%20Manual_assets/94fed44ea11f872e951f4acce3bc7abdac0a6509.png)

To adjust controls on multiple tracks, select multiple tracks, then change the controls on one track. A Track Group (Command+G) or Selection Grouping (Track \> Selection Grouping, or Control+G) must be enabled to adjust API Summing settings on multiple tracks at one time.

# API Summing Controls

## Headroom (HR)

The headroom setting increases or decreases the amount of headroom in the channel, and the amount of saturation. You can rotate the knob or double-click it to choose a value from the drop menu. The Headroom control is gain-compensated, so the volume changes are minimal when changing the headroom control. Headroom enables adjustment of the internal operating reference level for API Summing so that the signal is not “pushed” into processing as much. Headroom enables best practice operating level matching, or it can be used creatively to expand the sonic range of the summing processor.

By fine-tuning Headroom, the nonlinear I/O distortion and compression response characteristics can be tailored independently of signal input levels. Headroom can be set in 2 dB steps from 4 dB to 28 dB by rotating the HR knob. When the HR knob is in the 12 o’clock noon position (the default position), the HR value is 16 dB.

At higher dB values (clockwise rotation), signals will push into nonlinearity more easily. Set the control to a lower value (counter-clockwise rotation) when less color is desired.

**Tip:** Headroom is *increased* as the dB value *decreases*.

**Note**: The headroom control value is maintained when you switch between console summing models (from API Summing to Neve Summing and vice versa). 

## Trim

The trim setting allows you to compensate for gain changes introduced by the summing headroom and allows you to increase or decrease the overall level of the summing bus. You can rotate the knob or double-click it to type a value. This continuous knob lets you adjust the level at the output from the line amplifier. The available range is ±6 dB.

**Note**: The trim control value is maintained when you switch between console summing models (from API Summing to Neve Summing and vice versa). 

## Bypass

The Bypass button (labeled IN) allows you to toggle API summing on and off to audition the audio effects, for comparing the processed signal to the original, unprocessed signal. Click the IN switch to toggle the bypass state. When bypassed, the VU meter is unlit and native CPU resources are conserved.

**Note**: The Bypass state is maintained when you switch between console summing models (from API Summing to Neve Summing and vice versa). 

## Metering

The API Summing LUNA Extension VU meters are calibrated to register 0 at -12dBFS.

# Console Summing fader taper

Console Summing LUNA Extensions change the behavior and appearance of the LUNA buses and Main track to display accurate fader tapers. When you route tracks to a bus with a summing model enabled, the fader tapers of the bus or Main track and the source tracks change. 

When you change the summing model selection for a bus, the faders for the bus and for all tracks that feed the bus will change position because of the difference in fader taper between the LUNA native summing bus and Main channels and API Summing bus and Main channels.

**Note:** When you assign a bus to another bus, the taper of the source bus is retained and not overwritten by the summing model of the destination bus. 

![summing-bus-source-track-taper.png](LUNA%20API%20Summing%20Extension%20Manual_assets/078f75ed3b8b9413a79ea7efe391780340b7effc.png)

\
\

