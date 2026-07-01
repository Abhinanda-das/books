---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/34757792026004-A-Type-Multiband-Enhancer-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'A-Type Multiband Enhancer Manual'
word_count: 3120
---

# A-Type Multiband Enhancer Manual


## Add air and excitement to your mixes with the only end-to-end A-Type emulation.

Unlock vintage effects used for decades by pro engineers and producers with the UAD A-Type Multiband Dynamic Enhancer "compansion" processor. Use it to add air and sparkle to vocals, push the punch and bite of drums or guitars, enhance the sub frequencies of basses, and sweeten acoustic guitars and strings.

Five simple modes are available. You can deep dive into circuit mods not available on the original hardware, including multiband gain and crossover control, sidechain filtering, attack, knee, release, and ratio, and more.

- Includes Excite and Air modes employed on countless classic recordings
- Expand mode reduces noise and brings new life to overly squashed tracks, all in vintage multiband style
- New Crush and Gated single-band modes for explosive room sounds
- Use for real time encoding with analog tape sessions or perfectly decoded tape transfers

![](A-Type%20Multiband%20Enhancer%20Manual_assets/8a4a407aff59534acf2c26358aae2a003dbeac43.png)

*A-Type Multiband Dynamic Enhancer (Circuit Mods closed)*

![](A-Type%20Multiband%20Enhancer%20Manual_assets/fb71b717ec2156e7c5855901ac73a305d511a726.png)

*A-Type Multiband Dynamic Enhancer (Circuit Mods open)*

------------------------------------------------------------------------

# Technical Overview

The original A-Type hardware processors operate as multiband companders (compressors and expanders) that reduce tape hiss. These units dynamically emphasize high frequencies during the encoding stage (recording), and then attenuate those same frequencies during the decoding stage (playback) to reduce tape noise. 

On input, the original signal is split into four bands, with the highest bands overlapping, then the multiband signal is compressed and summed back with the original signal, and decoded through a downward expander. 

The plug-in can be used to encode and decode signals to and from tape just like the original hardware, and for accomplishing tape-to-digital transfers of existing recordings.

#### [<span style="color: #1155cc;">Learn more about how we made the A-Type Multiband Dynamic Enhancer plug-in</span>](https://www.uaudio.com/blogs/ua/making-of-uad-a-type).<span style="color: #666666;"></span>

![](A-Type%20Multiband%20Enhancer%20Manual_assets/c1d471fcf3f64ac2cd8a67a165b78daac0869d9c.png)

While A-Type noise reduction was widely used for decades, the processing was also repurposed as a creative enhancement tool: 

- **Encoding (Excite)** applies compression on each band that is inversely proportional to the level of the material, so quieter sounds are made brighter, while louder sounds remain almost unchanged. This effect adds excitement and clarity without generating new harmonic content or distortion, resulting in more pleasant and natural enhancement when compared to later harmonic-based exciters. 
- **Decoding (Expand)** produces results similar to a traditional expander, but with audible noise reduction benefits.
- **Mods** were developed by modifying the processor's cards or cartridges. The famous "Air" mod disables the circuit's two lower bands so that only the high-frequency portion of the signal is processed, giving a unique bright sheen that is particularly well-suited to vocals.

## A-Type Processor Modes

### Excite

Use Excite mode (also known as Stretch or the John Lennon\* Trick) to push key mix elements forward with ease. A-Type "encode" has long been employed as a secret studio enhancement trick on countless hit records. This unique multiband dynamic effect pre-dates later "exciter" technology, and dynamically increases excitement without introducing artifacts or altering the harmonic content.

- All four bands are active, and the compressor outputs are summed with the output.
- The original hardware has a fixed direct/wet blend. The Mix option provides much greater flexibility when dialing in the Excite effect. 
- Click the virtual grease pencil marks on both Amount and Mix, or load the **A-Type EXCITE Stock HW Encode** preset, for an accurate match to the A-Type hardware sound.

*\*Use of an artist's name does not constitute an official endorsement of UA products and services.*

### Expand

Use Expand mode to apply a creative blend of dynamic expansion, transient shaping and noise reduction. Expand also provides full support for decoding A-Type encoded tapes, for analog-to-digital transfers. 

-  All four bands are active. The compressor outputs are fed back and then subtracted from the input.
- Direct path signal is present, and persistent regardless of the Mix setting, as on the original hardware. For A-Type encoded tape transfers, set Mix to 100%. 
- Gains for all four bands are reflected in the multiband display, but these gain controls apply only to the source that is fed into the feedback loop; when the sliders are all at minimum there is no processing.
- Louder signals sound less processed than quieter signals. This is due to the processor behavior: significant gain reduction is applied to louder signals, reducing the processed feedback signal. With very loud material, the output signal will be very similar to the input signal. 
- Click the virtual grease pencil marks on Amount and Mix or use the **A-Type EXPAND Stock HW Decode** preset, for an accurate match to the A-Type hardware sound.

### Air

Use Air mode (also known as the Air Hack, Vocal Trick, or Vocal Stressor) to create an airy, hyped sound that shines on vocals and solo instruments. Use the Mix control to blend in the effect. A little Air goes a long way.

- Low and Low Mid bands are disabled, and the compressor signals are summed with the dry signal.
- Signals below the compression threshold get a pre-emphasis 10 dB shelf boost, which flattens as compression kicks in, similar to a dynamic EQ.
- The original hardware's direct/wet ratio was fixed according to the specific hardware modification. With the Mix control, you have much greater flexibility to dial in the effect. Three famous versions of the effect, and their Mix values, are included as presets (these preset names are in bold below).
  - **A-Type AIR Sound City Circuit Mod** has the most dry signal, as per Sound City's own cartridge modification method. Mix amount is 12%, which you can also set by clicking the virtual grease pencil mark on the Mix knob.
  - **A-Type AIR A301 Circuit Mod** has less dry signal. This effect was achieved by sliding the lower band card out on the earliest A301 unit, or modifying an A-Type cartridge. Mix amount is 16%.
  - **A-Type AIR Simple Circuit Mod** includes the least dry signal. This method was originally achieved by clipping two resistor leads in the A-Type cartridge to disable the lower bands. This preset sets the Mix amount to 22%.

### Crush

Use Crush mode for an explosive room crush effect. Crush is a unique, single-band hardware modification developed by Universal Audio, that expands the functionality of the A-Type circuit beyond its original design. With lower Amount and Mix settings, Crush can also function as an excellent general purpose compressor. 

A-Type's [Side Chain Filter](#h_01JTV2DJK4G2KA343PFR9Y8VYK) options allow more control over the Crush effect.

### Gated

Use Gated mode for dramatic '80s-style gated room effects, most commonly applied to drums. Gated mode places a simple gate in front of the Crush compressor for gated room effects. 

The Amount knob controls both the gate threshold and the Crush compressor threshold. The Mix knob sets the dry/wet compression blend, but not the amount of gating. Set Mix to 0% for gating without compression. 

#### Gated Circuit Mod tips

- The Release control adjusts the gate release time and the Crush compressor release time.
- You can adjust Headroom to set the Crush threshold separately from the gate threshold, as explained in [HR (Headroom)](#h_01JTV2DJK4CZQYSDJAX3NQS468).

## Artist Presets

Presets from prominent Universal Audio artists and A-Type hardware users are included. You can access the artist presets using the UAD preset browser. 

<div>

|                |                |
|:--------------:|:--------------:|
|   Billy Bush   | Carl Glanville |
|  Chuck Zwicky  |  John Paterno  |
| Richard Chycki |  Will Shanks   |

</div>

**Tip:** Presets with "A-Type" prefixes in the name provide the accurate settings based on the original hardware circuit or well-known modifications. Use these when you want an exact match to the A-Type hardware sound. For magnetic tape transfers, use the **A-Type TAPE TRANSFER DECODE** preset.

------------------------------------------------------------------------

# A-Type Multiband Enhancer Controls

**Tip:** You can click text labels in the plug-in to set controls to the values indicated.

## Tool tips

To show informational tool tips, click the ⓘ symbol at the upper right of the plug-in screen. When highlighted, informational text is displayed on the cartridge cover as you hover over controls in the plug-in.

Tool tips and the ⓘ symbol only appear when the Circuit Mods section is closed. 

**Note:** When tool tips are disabled, the ⓘ symbol appears only when you hover the mouse over the plug-in. 

## Mode

Click a switch to select the A-Type processing Mode. See [A-Type Processor Modes](#h_01JTV2DJK3CK2NJHG5V14W2BHR) for detailed descriptions of each mode. The mode buttons toggle between active and bypass states.

**Tip:** Click the virtual grease pencil marks on the Mix and Amount knobs in Excite, Expand and Air modes to set controls to the hardware's stock settings for those modes.

## Amount

Amount adjusts A-Type's threshold while maintaining signal level with auto-gain. Internally, this adjusts the input and output trims from the original A-Type hardware. Rotate the knob clockwise to increase the effect. 

## Mix

Mix allows you to set a continuous blend between unprocessed and processed signals. While the original A-Type hardware had a fixed direct/wet blend, Mix allows any blend for creative purposes. Rotate the knob clockwise to blend in more signal from the dynamics processor. 

## SC Filter

The SC Filter (sidechain filter) options go beyond the A-Type hardware, allowing you to filter the input signal to the dynamics detector, to control dynamics processing across the frequency range. This three-way switch has the following settings:

- **Off –** No sidechain filter is applied.
- **Low Cut –** Applies a 12 dB/octave low cut filter at 150 Hz to minimize low frequency detection and reduce "pumping" with bass-heavy content.
- **Tilt –** Applies a 3 dB/octave linear filter, for a low to high shift in the dynamic response to the signal across the frequency range. 

**Tip:** Click the switch to cycle through the settings, or click the LEDs to activate each filter mode.

## SC Link

SC Link provides linked (stereo) or unlinked (dual mono) dynamics sidechain operation. While linking was not a feature on the original A-Type hardware, SC Link provides practical and creative control for custom effects.

- When SC Link is off (unlit), the L/R dynamic processors are unlinked, and the amount of compression that occurs is completely independent for both channels, for creative effect. If one channel has higher signal peaks than the other channel, the left-right stereo image may shift.
- When SC Link is on (lit), the L/R dynamic processors are stereo linked and the amount of dynamic processing is always the same for both channels. This setting prevents left-right shifting of the stereo image that can occur when one channel has higher signal peaks than the other channel.

## Meter IN/GR

The metering switch allows you to display either the input level (IN) or the gain reduction amount (GR). 

- IN provides accurate metering for the input level to the processor. To calibrate levels for A-Type magnetic tape transfers, set magnetic tape tones to register at 0 dB on the meter.
- GR provides metering for the amount of gain reduction across all bands in the current mode, effectively displaying the band that is compressing or expanding the most.

## Power

The plug-in is active when the Power switch is engaged and the buttons are lit. Click the Power button to toggle the state.

When Power is off, the plug-in uses no processor or DSP. When the UAD-2 plug-in is off and UAD-2 DSP LoadLock is inactive, UAD DSP usage is reduced.

------------------------------------------------------------------------

# Circuit Mods

The Circuit Mods section allows you to adjust extended characteristics of A-Type's processor modes beyond the stock capabilities of the original hardware, pushing A-Type into sound design territory. These unique mods were developed by Universal Audio through circuit study and by physical experimentation on A-Type's swappable cartridge system.

Toggle the Circuit Mods area by clicking the reveal triangle below the IN / GR switch, or click the cartridge to open. Click the reveal triangle again to close.

![](A-Type%20Multiband%20Enhancer%20Manual_assets/aa94e989c4ad4f07faaa39de31686e258b1e61f2.png)

## Auto Cal

When Auto Cal is enabled, Circuit Mod parameters are reverted automatically when you switch Modes. This ensures that you don't unintentionally lose the default behavior when changing between Modes. Disable Auto Cal when you intentionally want to explore how the current settings might sound under a different Mode.

Enable Auto Cal to adjust all Circuit Mod controls for a Mode to their original settings. Mods that are reset when Auto Cal is enabled are: 

- Crossover gains
- Crossover frequencies
- Knee
- Release
- Ratio

The Auto Cal LED illuminates green when all Circuit Mod parameters are in their calibrated positions, and turns red when one or more Circuit Mod parameters are changed. Toggle Auto Cal or click the LED to revert all circuit modes back to unmodified settings.

## 4:1

When 4:1 is selected, the dynamics processor applies a custom 4:1 compression ratio. When unlit, the dynamics processor applies the A-Type hardware's unmodified variable ratio from 4:1 to approximately infinity:1. The variable ratio provides the most transparent sound, while the fixed 4:1 ratio allows deeper creative control along with the other circuit mods.

Crush and Gated modes default to the 4:1 ratio, while other modes default to the variable ratio.

Experiment with this setting for creative processing. The 4:1 setting is interactive with the extremes of the Knee and Release sliders, especially in the single-band (Crush and Gated) modes.

## Knee

"Knee" refers to the shape of the dynamic processor's response as it nears the onset threshold. A softer knee attacks more gradually as it approaches the threshold, and a harder knee attacks more abruptly. Extreme settings on Knee can create unique processed sounds. The A-Type attack knee is unique among dynamic processors, with an initial very fast attack that slows as the signal approaches the threshold. Over time, the attack knee becomes slower when the knee is reached.

This control adjusts the attack knee for all modes. Adjust this control towards the Soft range for a softer sound, with decreased transient response. Adjust this control towards the Hard range for a more aggressive, harder sound, with increased transient response.

## Release

This control adjusts the dynamic release time for all modes. 

Release is interactive with the Knee control. Extreme settings on Release can create unique processed sounds. Faster release times reduce bloom and swell in your processed sound. Slower release times emphasize room tone and note expansion.

In Gated Mode, Release controls both the compressor threshold and gate release. 

## Crossovers and Gains

![](A-Type%20Multiband%20Enhancer%20Manual_assets/78b627ea8c6db0d11c089b18f3cbf6d566619279.gif)

For Excite, Expand, and Air modes, you can individually adjust band crossover frequencies and band gain amounts. Use these controls to shape the frequency output from the plug-in for your material. Default settings feature crossover points of the original hardware.

- Four bands are available with Excite and Expand modes (Low, Low Mid, High Mid, High) 
- Two bands are available in Air mode (High Mid, High)

### Auto Cal and crossovers

- When Auto Cal is enabled, crossover gains and frequencies are reverted automatically when you switch Modes. 
- When Auto Cal is disabled, your changes to crossover frequencies and gains are retained when you switch Modes. 
- To revert crossover frequencies and gains to their settings for any Mode, click Auto Cal until the green LED shows.
- Crossover frequencies can be adjusted within the following ranges: Low (50 – 250 Hz), Mid (800 Hz – 5 kHz), High (6 kHz – 14 kHz).

### Editing crossovers in the Crossover display

- Hover over a band to highlight the band
- Drag horizontally on frequency handles or dividers to adjust its crossover frequencies

\
![](A-Type%20Multiband%20Enhancer%20Manual_assets/545e723532b9403b700b68c5b6f5d00b12045cb0.png)\
\

- Drag vertically on band handles (or within band displays) to adjust gain within a band\
  \
  ![](A-Type%20Multiband%20Enhancer%20Manual_assets/fa83714167a38c4eb59e62520f92e99c978044cc.png)

**Tip:** Click a Frequency text label to snap the crossover frequency line to that setting. Crossover frequency lines can only snap to the labels within their frequency range.

## Output

Output adjusts the overall level of the processed signal. Use this slider to compensate for volume changes in the signal after other processing.

## HR (Headroom)

Use the HR control to adjust the amount of available headroom for the plug-in. You can adjust headroom by clicking and dragging the knob, or by clicking the plus (+) or minus (-) text labels.

- Plus (counter-clockwise) sets higher headroom. This raises the threshold before compression and A-Type processing, reducing the amount of processing. Use higher headroom settings for more subtle processing.
- Minus (clockwise) reduces the processor's headroom. The lower you set the headroom, the more effect the processor has. Use lower headroom settings for more extreme processing.

**Tip:** HR does not affect gate threshold in Gated mode, and can be used as an independent gain reduction control from Amount.

------------------------------------------------------------------------

# Tape Decoding Application Notes

To decode multitrack tapes that were encoded with A-Type hardware, and that include A-Type tones, follow these steps.

1.  Instantiate the mono version of the plug-in on each track.
2.  Use the Expand mode preset **<span style="color: #141414; background-color: #fefefe;">A-Type TAPE TRANSFER DECODE</span>**.
3.  Adjust the Amount knob to register 0 dB on the Input meter while playing back A-Type tones from the tape. A-Type is calibrated to +3 tape reference level, but Amount allows the range to cover tapes above and below.

## Tips

- Use the stereo version of A-Type to decode two-track mix tapes.
- Set the level for one track, then save the setting as a custom preset, and load the preset on each channel.
- To transfer in real time, you can use the plug-in on each input channel in UAD Console (REC mode) while loading the tape, instead of using bounce to disk or as a mix plug-in in your DAW.

## Can I use A-Type for noise reduction on tape recordings that did not use Dolby A-Type encoding?

While you can’t achieve the same results as applying A-Type Encode before the signal is committed to tape, you can get noise reduction benefits by using Expand (Decode) mode with tape sources that have already been recorded. The tradeoff is that while some noise is reduced, the new processed signal is altered and the result is not as transparent: Once a recording is committed to tape, the hiss and noise is already baked in. Since the signal was not encoded before committing it to tape, the amount of noise will be unchanged relative to the existing recorded signal, and can not be separated or filtered out by encoding.

 

![Manual Gang Shot.jpg](A-Type%20Multiband%20Enhancer%20Manual_assets/7163a342099cc2b92a4c54b130ec47bbc116bcdc.jpg)

*The full collection of hardware studied in the making of the A-Type Multiband Dynamic Enhancer*

------------------------------------------------------------------------

*The A-Type Multiband Dynamic Enhancer plug-in is not affiliated with, sponsored, nor endorsed by Dolby. The Dolby name, as well as the A-Type model names, are used solely to identify the classic effects emulated by Universal Audio’s product.*

20250717

