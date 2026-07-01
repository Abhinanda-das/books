---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/4419513327124-API-Vision-Channel-Strip-Manual.html'
converted_at: 2026-05-31T13:45:00Z
tool: htmlq+pandoc
title: 'API Vision Channel Strip Manual'
word_count: 6223
---

# API Vision Channel Strip Manual


## The iconic color of API's flagship analog console, with expanded EQ.

From Stevie Wonder's Innervisions to Radiohead's In Rainbows, API desks have shaped hit albums with unmistakable punch, presence, and color for over 50 years.

In 2013, Universal Audio released the API Vision Channel Strip plug-in, artfully capturing API's flagship analog console. Today, the updated API Vision Channel Strip Collection gives you more authentic API tone, now with switchable EQ modules and expertly modeled output section, plus all the critical recording and mixing functions of API's iconic compression, gating, and filter modules.

- Track and mix through a stunning emulation of API's flagship analog console
- Sculpt sources with new 560L series 10-band graphic EQ module and beloved 550L parametric EQs
- Punch up signals through the API 212L preamp with famed 2520 API op-amp and custom API transformers, with added features from API's flagship Vision console
- Reshape ambience and create dynamic effects with the 235L Gate/Expander
- Tame transients and craft bold new textures with API's legendary 225L compression circuit
- Mix with artist presets from Joe Chiccarelli, Neil Dorfsman, David Isaac, and more

## Sculpt with Parametric and New Graphic EQs

With a click of the new EQ Type button, the API Vision Channel Strip Collection lets you choose between the revered 550L 4-band parametric EQ and API's famous 560L series 10-band graphic EQ. The new 560L EQ emulation captures the complex band interactions, clip points, and musical filter amp distortions of API's coveted hardware, letting you quickly sweeten and shape guitars, add aggression to drums, and push vocals forward with analog punch, low-end transparency, and ultra-tight imaging.

## Shape Dynamics with the 225L Compressor

A versatile compressor teaming with character, the 225L thrives on any instrument, in any genre — from a single track to an entire mix. Plus, use selectable "New" and "Old" functions for two delicious brands of compression, from mild to severe.

## Get Creative with API Gate/Expander and Filters

The ultra-fast 235L Noise Gate/Expander lets you easily shape ambience and attack on individual sources like kick drums or bass synth, and also clamp down on noisy drum kit rattles and gnarly guitar amp noise. Plus, the passive, fully sweepable 215L's Hi and Lo pass filters are perfect for broad stroke EQ sculpting, letting you expertly craft your source material, while preserving its original tone.

 

![avcs.png](API%20Vision%20Channel%20Strip%20Manual_assets/4d01c7e6acf5d6e24f4c1eded2bd8309dfab5477.png)

*API Vision Channel Strip*

![api-vision-legacy.png](API%20Vision%20Channel%20Strip%20Manual_assets/01ac85d788bba2d9cc443af4bce228cec1311643.png)

*API Vision Channel Strip Legacy*

------------------------------------------------------------------------

# Operational Overview

## API Vision Channel Strip Collection plug-ins

The API Vision Channel Strip Collection for UAD DSP consists of two separate plug-ins: API Vision Channel Strip and API Vision Channel Strip Legacy. The controls for these two plug-ins are nearly identical; all differences are noted. API Vision Channel Strip native (UADx) does not include the API Vision Channel Strip Legacy.

### API Vision Channel Strip

The updated API Vision Channel Strip has all the features of the original API Vision Channel Strip Legacy, with the following additions and enhancements:

#### 212L Preamp

- Independent mic and line gain controls
- Independent PAD values for the mic and line inputs
- Low cut rumble filter

#### EQ

- Selectable 550L or 560L modules

#### Other

- Modeled channel output fader
- Modeled output buffer amp clipping

**Note:** The features listed above are unavailable with API Vision Channel Strip Legacy.

### API Vision Channel Strip Legacy (UAD-2 DSP only)

The original API Vision Channel Strip Legacy offers most of the features and sonics of the updated API Vision Channel Strip. Because output fader and amp clipping is not modeled and the 560L EQ is not included, the legacy version offers a less colored sound and uses less UAD DSP.

API Vision Channel Strip Legacy can be quickly differentiated from the updated version by its LEGACY badge and its output knob (versus fader) in the global controls section.

## Modular Design

As with the original hardware, the API Vision Channel Strip has a modular design. Each module controls a different signal processing function, and associated controls are grouped within each module. The following modules are contained in the API Vision Channel Strip:

- 212L Microphone Preamplifier
- 215L High/Low Sweep Filters
- 235L Gate/Expander
- 225L Compressor/Limiter
- 550L Four-Band Equalizer
- 560L Ten-Band Graphic Equalizer

![api-callouts-main.png](API%20Vision%20Channel%20Strip%20Manual_assets/aadb79438cf79a87947c6087119b10886cc88d2d.png)

## Selectable EQ

### API Vision Channel Strip

The EQ module can be switched between the 550L and 560L equalizers with the TYPE button in the EQ module. In these operating instructions, "EQ" represents the 550L/560L EQ module in API Vision Channel Strip.

The plug-in stores the current settings in both EQ modules, allowing for convenient comparisons of both EQ types or other creative uses.

**Note:** The 560L EQ module is unavailable with API Vision Channel Strip Legacy.

### API Vision Channel Strip Legacy

In these operating instructions, “EQ” represents the 550L EQ module in API Vision Console Channel Strip Legacy. The 560L EQ module is unavailable with API Vision Channel Strip Legacy.

## Signal Flows

A simplified view of the default signal flow routing within the plug-in is illustrated in the diagram below. The audio path is shown with solid lines, and the side chain control keys for the 235L and 225L dynamics modules are shown with dashed lines.

![API-Vision-SignalFlow.png](API%20Vision%20Channel%20Strip%20Manual_assets/1e7d7f01148acee3bf88699ced44d30ba4b0d398.png)

*Simplified default API Vision signal flow*

Signal flows can be re-routed via options in the plug-in. The EQ module can be placed before the dynamics modules via the PREDYN (pre-dynamics) button, and the sweep filters and/or EQ can be moved out of the audio path and into the dynamics side chain path via the SC (side chain) buttons in those modules.

Note that the side chains for the dynamics modules are in series by default (as in the diagram above). However, when the sweep filters and/or EQ are moved into the side chain via their SC buttons, the side chain inputs for the dynamics modules are in parallel, as shown in the diagram below with 215L SC enabled.

![API-Vision-SignalFlow2.png](API%20Vision%20Channel%20Strip%20Manual_assets/2fc360c34a6b72e8b95dc85e5d35da842c9cca7b.png)

*Simplified signal flow illustrating parallel side chain inputs with 215L SC enabled*

### 215L Side Chain (SC)

The SC button in the 215L module routes the sweep filters into the dynamics processing side chain. Click the SC button or its LED to toggle the setting.The default value is Off.

When the 215L side chain is active, signal output from the 215L module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules in parallel as shown in the diagram below. To listen to the 215L side chain key, simply disengage 215L SC to hear the equalized signal.

**Note:** The 215L module must be enabled for the 215L side chain to function.

![API-Vision-SignalFlow2.png](API%20Vision%20Channel%20Strip%20Manual_assets/2fc360c34a6b72e8b95dc85e5d35da842c9cca7b.png)

*Signal flow with 215L Sweep Filters SC enabled*

### EQ Pre-Dynamics (PREDYN)

The Pre-Dynamics button (PREDYN) in the EQ module re-routes the EQ. By default, the audio signal is routed into the EQ after dynamics processing. When PREDYN is enabled, this routing is swapped, and the EQ precedes the dynamics modules instead.

When PREDYN is active, the dynamics side chain is always tapped after the EQ module, regardless of the state of the 215L module's SC function. The effect of the PREDYN button is shown in the diagrams below.

**Note:** PREDYN has no effect when the EQ's DYN SC button is active.

![API-Vision-SignalFlow3.png](API%20Vision%20Channel%20Strip%20Manual_assets/a986364eaf7125a358f13c315a78f375c2365899.png)

*PREDYN routes the EQ before the dynamics modules*

![API-Vision-SignalFlow4.png](API%20Vision%20Channel%20Strip%20Manual_assets/5bbc0353b26e152cbd992b457170c87a5f13d67a.png)

*EQ always precedes the side chain tap when PREDYN is active*

### EQ Dynamics Side Chain (DYN SC)

The DYN SC button in the EQ module routes EQ into the dynamics processing side chain. When the EQ side chain is active (when the DYN SC LED is lit), signal output from the EQ module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules.

**Note:** In API Vision Console Channel Strip Legacy, this button is labeled SC.

![API-Vision-SignalFlow5.png](API%20Vision%20Channel%20Strip%20Manual_assets/761f68e3b9dc8e77ea20253a786a7117a2fc31ee.png)

*Signal flow with EQ SC enabled*

Note that both the EQ and 215L modules can both be routed simultaneously to the dynamics side chain. In this case, the 215L precedes the EQ in the side chain path, as shown below.

![API-Vision-SignalFlow6.png](API%20Vision%20Channel%20Strip%20Manual_assets/12735e4607ca7badc92879586323c6b62bf95c6f.png)

*Signal flow with SC enabled in both 215L and EQ modules*

## Displayed Values

Knob settings, when compared to the interface silkscreen numbers, may not match the actual parameter values. For example, in the 215L Sweep Filters module, the highest value shown in the interface is 20 kHz. However, the actual value when the knob is at maximum is 40 kHz.

This behavior is identical to the original hardware, which is modeled exactly. When the plug-ins are viewed in parameter list mode (controls and/or automation views), the actual parameter values are displayed.

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

|                  |                |                |
|------------------|----------------|----------------|
| Ann Mincieli     | Jeff Balding   | Nathan Feler   |
| Brendan Morawski | John Paterno   | Sage Skolfield |
| Butch Walker     | Kez Khou       | Sean Solymar   |
| Dave Isaac       | Michael Ilbert | Tommy Rush     |
| Ian Boxill       | Mike Dean      | Tony Platt     |

*Artists who provided presets for API Vision Channel Strip Collection*

<table style="border-collapse: collapse; width: 100%;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: left; width: 7.42861%; vertical-align: middle; height: 0px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 88.0001%; height: 0px"><h2 id="h_01HZ00QNX74W6ZHXZQY7P9F9DV">Unison Integration (UAD-2 DSP only)</h2></td>
</tr>
</tbody>
</table>

The API Vision Channel Strip Collection plug-ins feature Unison technology for integration with the mic preamp hardware in Universal Audio’s Apollo audio interfaces. With Unison interfaces, the ultra-transparent mic preamps inherit all of the unique sonics, input characteristics, and features of emulated preamps.

**Note:** Unison is active only when the plug-in is placed in the dedicated UNISON insert within UAD Console or LUNA. For complete details, see [Unison](26485044036756-Unison.html).

With Unison, the hardware preamp adapts to the modeled preamp’s physical input impedance. Combined with UA’s transparent analog amplification, this provides the plug-in’s full gain and tone range from clean to clipped — with broad, musical sweet spots in-between.

### Realistic Tandem Control

Unison facilitates seamless interactive control of plug-in settings using both the digitally- controlled panel hardware on Apollo audio interface and the graphical UAD plug-in interface. All equivalent preamp controls (gain, cut filter, polarity, pad) are mirrored and bidirectional. The preamp controls respond to adjustments with precisely the same interplay behavior as the modeled preamp, including gain levels and clipping points.

### Hardware Input Impedance

All Unison mic preamps feature variable input impedance in the analog hardware that can be physically changed by Unison-enabled UAD plug-ins for physical, microphone-to-preamp resistive interaction. This impedance switching enables Unison preamps to match the input impedance of the emulated hardware, which can significantly impact the sound of a microphone. Because the electrical loading occurs on input, prior to A/D conversion, the realism is faithful to the emulated hardware preamp.

### Tactile Gain Staging

Apollo’s hardware preamp knob can independently adjust the gain and level parameters available within the Unison plug-in via Gain Stage Mode. The gain stage being adjusted can be remotely switched via the interface hardware, so the gain levels and their associated colorations can be tuned from the hardware knob for precise physical tactile control, all without using the Unison plug-in’s software interface.

|  |  |  |
|:--:|:--:|:--:|
| ![api-vcs-unison-1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a2925b30f93d167a57c6491856af17f35e4d6fd1.png) | ![api-vcs-unison-2.png](API%20Vision%20Channel%20Strip%20Manual_assets/afdeffb06e25d495e50bfb4d86586b8aeb4c4601.png) | ![api-vcs-unison-3.png](API%20Vision%20Channel%20Strip%20Manual_assets/e05f613646c429264cb4352ad22510827a2631b8.png) |

*The outlined gain controls as they appear when in Unison Gain Stage Mode*

------------------------------------------------------------------------

# 212L Microphone Preamplifier

|  |  |
|:--:|:--:|
| ![api-vision2.png](API%20Vision%20Channel%20Strip%20Manual_assets/c53291096b69cdc115c298b24add2acf03777bd7.png) | ![api-vision-legacy2.png](API%20Vision%20Channel%20Strip%20Manual_assets/85063dd758d663f1b455446d603feb52bcd329e7.png) |

*212L Microphone Preamplifier standard (left) and legacy (right)*

## 212L Input Select

The INPUT button switches between the mic and line input gain knobs. Press the button to toggle the active selection.

**Tip:** Click an input selection LED (at left of the MIC/LINE gain knobs) to select the input.

The active setting is indicated by an LED next to the input's gain knob. When the mic input is active, the red LED at left of the MIC gain knob is lit. When the line input is active, the green LED at left of the LINE gain knob is lit.

**Note:** Input Select is unavailable with API Vision Channel Strip Legacy.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JE6ZAMW2XZQ9P2DGBYGN9QE9">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p>Software and hardware control is mirrored and can be changed within the plug-in interface, with Console/LUNA software controls, or with Apollo’s hardware button (MIC/LINE on Apollo rackmount models, or INPUT on Apollo Twin models).</p></td>
</tr>
</tbody>
</table>

## 212L Mic Gain

This knob adjusts the amount of gain applied to the mic input signal. The available range is 30 dB to 65 dB. The default value is 40.5 dB (unity gain).

**Tip:** Click the API logo atop the 212L module to return mic gain to its default value.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHJS0KBGSNW2VX68A11166Q">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p>Apollo’s hardware preamp knob can be used to adjust this parameter when Input Select is set to Mic, and/or when this parameter is selected in Gain Stage Mode.</p></td>
</tr>
</tbody>
</table>

## 212L Line Gain

This knob adjusts the amount of gain applied to the line input signal. The available range is 0 dB to 12 dB. The default value is 0 dB (unity gain).

The available Line Gain range is adopted from API VIsion Console's dedicated Line input functions and is not present on the original 212L hardware module.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHJTQS5G5YGBJ98J4Z7XH2N">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p>Apollo’s hardware preamp knob can be used to adjust this parameter when Input Select is set to Line, and/or when this parameter is selected in Gain Stage Mode.</p></td>
</tr>
</tbody>
</table>

## 212L Gain (Legacy)

This knob adjusts the amount of gain applied to the mic and line input signals. The available range is 30 dB to 65 dB. The default value is 40.5 dB.

Because the original 212L hardware module is a mic preamp only, the signal is attenuated by -32 dB at the plug-in module’s input to reduce the signal to line level.

## 212L Pad

PAD can be engaged to reduce signal levels when undesirable overload distortion is present at low preamp gain levels. PAD is engaged when its red LED is lit. Click the PAD button or its LED to toggle the setting.

## Mic Pad

When PAD is enabled with mic input, the input signal level is attenuated (lowered) by -20 dB.

## Line Pad

When PAD is enabled with line input, the input signal level is attenuated by -6 dB. The Line Pad is adopted from API VIsion Console's dedicated Line input functions and is not present on the original 212L hardware module.

**Note:** With API Vision Channel Strip Legacy, the PAD value is -20 dB with both Mic and Line input selections.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHK5AJ2E284P9NHZG51K5MZ">Unison Interactions</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><ul>
<li>PAD is unavailable when LINE input is selected.</li>
<li>Software and hardware control is mirrored and can be changed within the plug-in interface, with Console/LUNA software controls, or with Apollo’s hardware button.</li>
</ul></td>
</tr>
</tbody>
</table>

## 212L Phase

The Phase (ø) button inverts the polarity of the signal. The polarity is inverted when the button's green indicator is lit. Leave the button off (unlit) for normal polarity.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHKR3A8SE4QTS1NGGG42RQ0">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p>Software and hardware control is mirrored and can be changed within the plug-in interface, with Console/LUNA software controls, or with Apollo’s hardware button.</p></td>
</tr>
</tbody>
</table>

## 212L Cut Filter

This button activates a 50 Hz low cut filter that has a slope of 6 dB per octave. This rumble filter is adopted from the API Vision console's dedicated Line input functions and is not present on the original 212L hardware module.

**Note:** The 212L cut filter is unavailable with API Vision Channel Strip Legacy.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHKS761HX0NPRKM6NV8V6N5">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p>Software and hardware control is mirrored and can be changed within the plug-in interface, with Console/LUNA software controls, or with Apollo’s hardware button.</p></td>
</tr>
</tbody>
</table>

## 212L Meter

The LED ladder VU Meter indicates the signal level at the output of the 212L preamp module.

------------------------------------------------------------------------

# 215L High/Low Sweep Filters

![api-vision3.png](API%20Vision%20Channel%20Strip%20Manual_assets/565079f6e2749080d0f939819c84b487c57ead12.png)

The 215L offers two sweepable cut filters, one each for low and high frequencies. The original hardware is transformer coupled and uses a passive filter circuit design for smooth tone.

## 215L Lo-Pass

The Lo-Pass (high cut) filter has a continuous range of 643 Hz to 40.8 kHz. The slope of this filter is 6 dB per octave. The default value is 40 kHz.

## 215L Hi-Pass

The Hi-Pass (low cut) filter has a continuous range of 12 Hz to 596 Hz. The slope of this filter is 12 dB per octave. The default value is 12 Hz.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHKWA0Q507YDQYYAR4SFCEW">Unison Interaction (Legacy)</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p>With API Vision Channel Strip Legacy, enabling the preamp low cut filter in Console/LUNA software controls or with Apollo’s hardware button enables the 215L. (With API Vision Channel Strip, the Unison low cut filter is within the 212L module.)</p></td>
</tr>
</tbody>
</table>

## 215L SC (Dynamics Side Chain)

This button enables the 215L side chain filtering for the dynamic processors. Click the SC button or its LED to toggle the setting. The default value is Off. For related information, see "Signal Flows" earlier in this guide.

## 215L On

This button enables the 215L module. The filters module is active when the button's green indicator is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processor usage is reduced when this module is inactive. UAD DSP load is reduced when this module is inactive, unless DSP LoadLock is enabled in the UAD Meter & Control Panel.

------------------------------------------------------------------------

# 235L Gate/Expander

![api-vision4.png](API%20Vision%20Channel%20Strip%20Manual_assets/8b3aef74920a4913cdac9cce6a6a9c42ad39890f.png)

The 235L Gate/Expander module operates in either gate or expansion mode. Two attack speeds and a continuously variable release time are available in both modes.

## 235L Threshold

Threshold defines the input level at which expansion or gating occurs. The available range is from +25 dB to -47 dB. The default value is -47 dB.

**Note:** With API Vision Channel Strip Legacy, the default value is 0 dB.

Signals below the threshold level are processed by the module. Signals above the threshold are unaffected. Rotate this control counterclockwise to increase the gate/expand effect.

**Tip:** Click the "0" label to return Threshold to 0 dB.

## 235L Depth

Depth controls the gate/expansion amount, or more technically, the difference in gain between the gated/expanded and non-gated/expanded signal. Higher values increase the attenuation of signals below the threshold. When set to zero, no gating or expansion occurs. The available range is 0 dB to -80 dB. The default value is -80dB.

### Scaled Control

Although the Depth control has a full range of -80 dB, the scale is expanded in the first half of rotation so 0 to -9 dB is available for fine tuning of subtle, undetectable gating. The second half of rotation is from -10 to -80 dB for more drastic noise reduction.

## 235L Attack

This two-position switch determines how quickly the onset of gating/expansion occurs when the signal exceeds the threshold. Normal (25 milliseconds) and Fast (100 microseconds) settings are available. The default setting is Normal.

## 235L Release/Hold Knob

The function of Release/Hold knob (R/H) depends on the setting of the Release/Hold switch (Rel/Hld). With both switch settings, the available range of the knob is 50 milliseconds to 3 seconds. The default value is 0.5 seconds.

**Note:** Hold mode is only available when the 235L module is set to Gate mode with the Gate/Expander switch.

## Release

When the input signal drops below the threshold level and the Release/Hold switch is set to Release, this knob sets the amount of time it takes for signals to decay to the Depth level.

Slower release times can smooth the transition that occurs when the signal dips below the threshold, which is especially useful for material with frequent peaks.

Fast release times are typically only suitable for certain types of percussion and other instruments with very fast decays. Using fast settings on other sources may produce undesirable results.

## Hold

When the input signal drops below the threshold level and the Release/Hold switch is set to Hold, this knob sets the amount of time that signals are held at normal levels before signals return to the Depth level.

**Note:** When set to Hold, the release time is fixed at 100 milliseconds.

## 235L Release/Hold Switch

This two-position switch (REL/HLD) determines the behavior of the Release/Hold knob when the 235L module is set to Gate mode with the Gate/Expander switch. The default value is Release.

**Note:** This switch is locked in the Release position when the module is in Expander mode (Hold mode is unavailable in Expander mode).

## 235L Gate/Expander Switch

This switch (GTE/EXP) toggles the module between Gate and Expander modes. The default value is Expander.

**GTE** – When set to Gate mode, signals below the threshold are attenuated by the Depth amount.

**EXP** – <span class="CharOverride-3">When set to Expander mode, the gate applies downwards expansion at a fixed 1:2 ratio, with the amount of gain reduction determined by the Depth control. Expansion allows the signal to "sneak up" to the full signal level without any loss of "under threshold" nuances. </span>

## 235L Meter

This meter displays, in dB, the amount of gain attenuation (downward expansion) occurring in the 235L module.

## 235L On

This button enables the 235L module. The module is active when the button's green indicator is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processor usage is reduced when this module is inactive. UAD DSP load is reduced when this module is inactive, unless DSP LoadLock is enabled in the UAD Meter & Control Panel.

------------------------------------------------------------------------

# 225L Compressor/Limiter

![api-vision5.png](API%20Vision%20Channel%20Strip%20Manual_assets/fdd1ca0b50cf5b4f71bcd63aac59fe08855ffdf8.png)

The 225L Compressor/Limiter offers a continuously variable ratio between 1:1 (no compression) and infinity:1 (limiting). Three attack speeds and continuously variable release times are available. A hard/soft knee setting and a unique new/old setting are also available in the module.

## 225L Threshold

Threshold defines the input level at which compression begins. The available range is +13 dB to -18 dB. The default value is 13 dB.

Signals that exceed the threshold are processed by the Ratio value. Signals below the threshold are unaffected. Rotate this control clockwise to increase the compression effect.

**Note:** The 225L compressor automatically increases makeup gain to compensate for levels that are reduced during compression (aka reciprocal gain). However, as with the original hardware, the plug-in's compensated makeup gain levels are not perfectly linear.

## 225L Ratio

Ratio defines the amount of gain reduction applied to signals above the threshold. For example, a value of 2 (expressed as a 2:1 ratio) reduces the signal level above the threshold by half, with an input signal level of 20 dB being reduced to 10 dB.

A value of 1 yields no gain reduction. When the control is at maximum (∞), the ratio is effectively infinity to one, yielding the limiting effect. The available range is 1:1 to infinity. The default value is 4:1.

## 225L Attack

This three-position switch defines the attack time of the compressor. Available values are Fast (2 milliseconds), Medium (18 milliseconds), and Slow (75 milliseconds). The default value is Medium.

## 225L Release

Release sets the amount of time it takes for processing to cease once the input signal drops below the threshold level. The available control range is 50 milliseconds to 3 seconds. The default value is 0.5 seconds.

**Note:** Actual release times are program dependent.

Slower release times can smooth the transition that occurs when the signal dips below the threshold, which is especially useful for material with frequent peaks. However, if the release is too long, compression for sections of audio with loud signals may extend to sections of audio with lower signals.

Fast release times are typically only suitable for certain types of percussion and other instruments with very fast decays. Using fast settings on other sources may produce undesirable results.

## 225L Knee

The knee (onset) characteristic of the compressor/limiter can be set to Soft (SFT) or Hard (HRD) with this two-position switch. The default value is Hard.

Soft provides a more subtle compression resulting in a very natural, less compressed sound. Hard results in a more typical, sharp knee type compression that has a more severe limiting effect.

## 225L Type

The Type control switches the 225L compressor's control side chain signal to use either a feed-back (OLD) or feed-forward (NEW) design, providing two types of gain reduction. The default value is Old.

Compressors typically have a side chain control signal based on either feed-back or feed-forward designs. NEW feed-forward gain reduction is typical of newer VCA type compressors that rely on RMS detectors for the side chain circuit. The OLD feed-back method is what most classic compressors use for the side chain circuit.

**Note: **Unlike the original hardware, side chain processing via the 215L and EQ modules can be performed with this switch in the OLD position (the hardware cannot use side chain filtering with feedback compression).

## 225L Meter

This meter displays, in dB, the amount of gain attenuation occurring in the 225L module.

## 225L On

This button enables the 225L module. The module is active when the button's green indicator is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processor usage is reduced when this module is inactive. UAD DSP load is reduced when this module is inactive, unless DSP LoadLock is enabled in the UAD Meter & Control Panel.

------------------------------------------------------------------------

# 550L Four-Band Equalizer

![api-vision-550.png](API%20Vision%20Channel%20Strip%20Manual_assets/a67ac00e02960e4a01b161fb5131a47436132f94.png)

The 550L EQ is divided into four frequency bands: High Frequency (HF), High Midrange Frequency (HMF), Low Midrange Frequency (LMF), and Low Frequency (LF).

The 550L features API's "Proportional Q" which continuously narrows the bandwidth of the filter as band gain is increased, providing (as stated by API) "an uncomplicated way to generate acoustically superior equalization." The boost and cut characteristics are identical, allowing previous actions to be undone if desired.

## Band Controls

The four EQ bands (HF/HMF/LMF/LF) are controlled by dual-concentric rotary switches. The inner knob controls the band frequency (values in blue text) and the outer knob controls the band gain. Available values for these controls are listed in the table below.

#### 550L Frequency and Gain Values

<table data-align="center" style="margin-right: auto; margin-left: auto;">
<tbody>
<tr>
<td class="wysiwyg-text-align-center"><p>Band</p></td>
<td><p><span>Frequency Values </span></p></td>
<td><p><span>Gain (±dB) </span></p></td>
</tr>
<tr>
<td class="wysiwyg-text-align-center"><span>High Frequency<br />
(HF) </span></td>
<td><p><span>20, <strong>15</strong>, 12.5, 10, 7, 5, 2.5 (kHz) </span></p></td>
<td rowspan="4"><p><span>0<span><br />
2<br />
4<br />
6<br />
9<br />
12 </span></span></p></td>
</tr>
<tr>
<td class="wysiwyg-text-align-center"><p>High Mid Frequency<br />
(HMF)</p></td>
<td><p><span>12.5, <strong>10</strong>, 8, 5, 3, 1.5 (kHz), 800 (Hz) </span></p></td>
</tr>
<tr>
<td class="wysiwyg-text-align-center"><p><span>Low Mid Frequency<br />
(LMF) </span></p></td>
<td><p><span>1000, <strong>700</strong>, 500, 240, 180, 150, 75 (Hz) </span></p></td>
</tr>
<tr>
<td class="wysiwyg-text-align-center"><p><span>Low Frequency<br />
(LF) </span></p></td>
<td><p><span>400, <strong>300</strong>, 200, 100, 50, 40, 30 (Hz) </span></p></td>
</tr>
<tr>
<td colspan="3"><p>Default Values are indicated in <strong>bold</strong></p></td>
</tr>
</tbody>
</table>

### Frequency

Frequency determines the center frequency of the band when the band is in peak mode (all bands) and the cutoff frequency when the band is in shelf mode (available with HF/LF bands only). The frequency for the band can be set using any of these methods:

- Drag the inner concentric knob to the desired value
- Hover over the inner concentric knob then use the mouse scroll wheel
- Click directly on the frequency value label to switch to that value
- Click on the band label (HF/HMF/LMF/LF) to cycle through available values (shift+click to cycle in reverse)

### Gain

The gain for each band can be set using any of these methods:

- Drag the outer concentric knob handle to the desired value
- Click the "+" or "-" text labels to increment/decrement values
- Hover over the outer concentric knob then use the mouse scroll wheel

### Peak/Shelf Switches

The HF and LF bands are in shelf mode by default (switches in "down" position). When the Peak/Shelf switch is engaged for the band (in "up" position), the band is changed to peak mode.

## PREDYN (EQ Pre-Dynamics)

By default, the audio signal is routed into the EQ after dynamics processing. When PREDYN is enabled (when its green LED is lit), this routing is swapped, and the EQ precedes the dynamics modules instead. For related information, see "Signal Flows" earlier in this guide.

**Note:** PREDYN has no effect when the EQ's DYN SC button is active.

## DYN SC (Dynamics Sidechain)

When DYN SC is active (when its green LED is lit), signal output from the EQ module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules. For related information, see [Signal Flows](#h_01FWHATFWPVJKW90ZPS06JB0CZ).

**Note:** In API Vision Console Channel Strip Legacy, this button is labeled SC.

## EQ Type

**Note:** This control is unavailable with API Vision Channel Strip Legacy.

The 550L EQ module is active when the TYPE button's green LED is unlit. Click the TYPE button or its LED to switch to the 560L EQ module.

**Tip:** The plug-in stores the current settings in both EQ modules, allowing for convenient comparisons of both EQ types or other creative uses.

## EQ On

This button enables the EQ module. The module is active when the button's green indicator is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processor usage is reduced when this module is inactive. UAD DSP load is reduced when this module is inactive, unless DSP LoadLock is enabled in the UAD Meter & Control Panel.

------------------------------------------------------------------------

# 560L Ten-Band Equalizer

![api-vision6.png](API%20Vision%20Channel%20Strip%20Manual_assets/a16d17eb9d33676762ac58d0a65f44b0b69e5ef5.png)

**Note:** This module is unavailable with API Vision Channel Strip Legacy.

With ten bands of graphic EQ, the 560L EQ is ideal for shaping your mix with surgical precision. API's proprietary "Proportional Q" intuitively widens bandwidth at lower boost/cut levels and narrows it at higher levels, giving you more musical control over precise bands of your mix.

**Note:** As with the original 560L hardware, the signal is boosted by approximately 0.4 dB even when all gain sliders are set to 0 dB.

## Gain Sliders

Each of the 10 sliders controls the gain for one frequency band. Each band can be adjusted to boost or cut the frequency by up to ±12 dB. The band center frequencies are listed below.

#### 560L Frequencies

|        |        |
|--------|--------|
| 31 Hz  | 1 kHz  |
| 63 Hz  | 2 kHz  |
| 125 Hz | 4 kHz  |
| 250 Hz | 8 kHz  |
| 500 Hz | 16 kHz |

**Tip:** To return a slider to the 0 dB position, click the slider's frequency text label. To reset all sliders to 0 dB, click the "0" text label above the sliders.

## PREDYN (EQ Pre-Dynamics)

By default, the audio signal is routed into the EQ after dynamics processing. When PREDYN is enabled (when its green LED is lit), this routing is swapped, and the EQ precedes the dynamics modules instead. For related information, see "Signal Flows" earlier in this guide.

**Note:** PREDYN has no effect when the EQ's DYN SC button is active.

## DYN SC (Dynamics Sidechain)

When DYN SC is active (when its green LED is lit), signal output from the EQ module is removed from the audio path, and is instead routed to control the 235L and 225L dynamics modules. For related information, see <a href="#h_01FWHATFWPVJKW90ZPS06JB0CZ" target="_self">Signal Flows</a>.

## EQ Type

**Note:** This control is unavailable with API Vision Channel Strip Legacy.

The 560L EQ module is active when the TYPE button's green LED is lit. Click the TYPE button or its LED to switch to the 560L EQ module.

**Tip:** The plug-in stores the current settings in both EQ modules, allowing for convenient comparisons of both EQ types or other creative uses.

## EQ On

This button enables the EQ module. The module is active when the button's green indicator is lit. Click the ON button or its LED to toggle the setting.

**Tip:** Processor usage is reduced when this module is inactive. UAD DSP load is reduced when this module is inactive, unless DSP LoadLock is enabled in the UAD Meter & Control Panel.

------------------------------------------------------------------------

# Global Module

|  |  |
|----|----|
| ![api-vision7.png](API%20Vision%20Channel%20Strip%20Manual_assets/8dff8717b98c1bbd9fe68760b96fb2b0359f0199.png) | ![api-vision-legacy3.png](API%20Vision%20Channel%20Strip%20Manual_assets/4a7f2e15d5e5a55aeeac7aa7b004f4cd4fcf7785.png) |

*Global module standard (left) and legacy (right)*

## Output Meter

The vertical LED ladder-style metering provides a visual indication of relative signal peak levels at the output of the plug-in.

## Output Fader

**Note:** This control is unavailable with API Vision Channel Strip Legacy.

This control accurately models the sound and linear behavior of the original API console fader. Up to +9 dB of gain is available. The default value is 0 dB.

**Tip:** Click the "0" text label to return Output to the 0 dB position.

Note that because the output buffer amplifier precedes the fader in signal flow, the Output Fader cannot control the modeled output buffer amp's clipping behaviors.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHNNEMD46NV2CR536CK2VYF">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 15px;">Apollo’s hardware preamp knob can be used to adjust the output fader when this parameter is selected in Gain Stage Mode.</span></p></td>
</tr>
</tbody>
</table>

## Output Knob (Legacy)

This control provides -24 dB to +12 dB of clean uncolored gain at the output of the plug-in. The default value is 0 dB.

**Tip:** Click the “0” text label to return Output to the 0 dB position.

<table style="border-collapse: collapse; width: 100%; height: 21px;">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr style="height: 21px;">
<td style="text-align: center; width: 0px; vertical-align: middle; height: 21px;">![unison-icon1.png](API%20Vision%20Channel%20Strip%20Manual_assets/a83c95ca2d4fafa148e45dfbf7534fda65b7fff5.png)</td>
<td style="width: 13.7143%; height: 21px"><h3 id="01JNHNP9JV5K5FV5KW1VM5TXA2">Unison Interaction</h3></td>
</tr>
<tr style="height: 0px;">
<td colspan="2" style="text-align: center; width: 15.1429%; height: 0px;"><p><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 15px;">Apollo’s hardware preamp knob can be used to adjust the output knob when this parameter is selected in Gain Stage Mode.</span></p></td>
</tr>
</tbody>
</table>

## SC Link (Side Chain Link)

When the plug-in is used on a stereo signal, this button links the side chains of the left and right channels of the 225L and 235L dynamics modules so both channels are compressed by the same amounts. SC Link is active when the button's green indicator is lit. The default value is ON.

Linking the side chains prevents signals which appear on only one channel from shifting the stereo image of the output. For example, any large transient on either channel will cause both channels to compress, and the amount of compression will be similar to the amount of compression for a transient which appears on both channels at the same time.

**Note:** The SC Link button cannot be engaged when the plug-in is used in a monophonic configuration.

## Power

The plug-in is active when one or more LEDs are lit. When power is off, all LEDs are unlit and all plug-in processing is disabled. Processor usage is reduced when the plug-in is powered off. UAD DSP load is reduced when the plug-in is inactive, unless DSP LoadLock is enabled in the UAD Meter & Control Panel.

![API_logo.jpg](API%20Vision%20Channel%20Strip%20Manual_assets/24f1800b6330772595d8fca4bc3531edc50ba58b.jpg)

![API_Console.jpg](API%20Vision%20Channel%20Strip%20Manual_assets/7fcde2d38c474ee0a395515fdc25ddbbc851eb20.jpg)

*API Vision Console*

All visual and aural references to the API Vision Console and all use of API's trademarks are being made with written permission from Automated Processes, Inc. Special thanks to Paul Wolff, Larry Droppa, Todd Humora, Jeffrey Richards, and Paul Wolff.

