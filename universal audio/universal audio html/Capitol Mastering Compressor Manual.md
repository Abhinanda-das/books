---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/15388033304724-Capitol-Mastering-Compressor-Manual.html'
converted_at: 2026-05-31T13:44:45Z
tool: htmlq+pandoc
title: 'Capitol Mastering Compressor Manual'
word_count: 2919
---

# Capitol Mastering Compressor Manual


## Get the legendary tube compressor from Capitol Studios. 

Capitol Mastering Compressor gives you the rich sound of the CM5511 — a legendary handbuilt tube mastering compressor designed and used by Capitol Studios on historic catalogs and thousands of hit records. Exclusively modeled by UA, now you can get the same professional finishing touch previously only available at Capitol Studios.

- Give your tracks the velvet touch of Capitol's handbuilt mastering compressor, the CM5511
- Get the pro sonics of the same hardware used on catalogs from Capitol, Blue Note, Motown, Verve, and more
- Easily increase perceived loudness and texture in your productions with Saturator, Mix, and Headroom controls 
- Tighten your low end and expand your stereo width using simple Mono Fold and Mid/Side features

## Get the Exclusive Sound of Capitol Mastering

The CM5511 compressor has mastered entire catalogs from Capitol, Motown, Geffen, Blue Note, Def Jam, and dozens more, as well as modern records by Black Sabbath, Demi Lovato, and Selena Gomez.\* Inspired by vintage Fairchild 670 and Gates Sta-Level tube limiters — and designed for consistent results across Capitol's four mastering rooms — Capitol Mastering Compressor is an exacting emulation of this "spare no expense" hardware, giving you the modern tube-based sound of this custom-made dynamics masterpiece.

*\*Use of artist names does not constitute official endorsement of Capitol Mastering Compressor software.*

## Expanded Controls for Complete In-The-Box Mastering

Easily tighten low end, add subtle saturation, and tweak the stereo field with easy-to-use "plug-in only" controls. Plus, comprehensive dBFS and LUFS metering and sidechain filter means you have a full-featured, modern mastering tool at your fingertips.

## Add Expensive Sound to your Instrument Groups

Not just for the 2-bus, Capitol Mastering Compressor will add its tube-based magic to your drum bus, synths, background vocals, and more, giving you the gorgeous dynamics control only achievable with this one-of-a-kind, hit-proven hardware.

## Key Benefits

- Give your tracks the velvet touch of Capitol's handbuilt mastering compressor
- Get the pro sonics of the same hardware used on catalogs from Capitol, Blue Note, Motown, Verve, and more
- Easily increase perceived volume and texture to your productions with Saturator, Mix, and Headroom controls  
- Tighten your low end and expand your stereo width using simple Mono Fold and Mid/Side features
- Use with any audio interface, no UA hardware required

![capitol-mastering-compressor.png](Capitol%20Mastering%20Compressor%20Manual_assets/570160d21edc0be2c9756a1bc5cd0fd03a588344.png)

*Capitol Mastering Compressor*

------------------------------------------------------------------------

# Operational Overview

The CM5511 Capitol Mastering Compressor gives you access to one of the rarest mastering tools ever created. The four units built for Capitol Studios mastering engineers provide essential tube compression and limiting, with familiar, easy to use controls and lots of extras. Designed expressly for mastering but useful on a variety of sources, the CM5511 includes stepped controls for easily repeatable results, with familiar input, threshold/attack/release controls, an internal sidechain to filter out low bass in the compressor detector, and extra features included with the mastering engineer in mind. 

You can compress your mix in stereo, or switch to mid/side operation to independently adjust the center and sides of the stereo image. The CM5511 plug-in adds a mix control to adjust the amount of processed/dry source material, and a post-compression mono fold feature to reduce the stereo width of low bass signals, followed by a saturation control to increase the heft of your mix. A gain control allows you to add gain before the saturator for more push. VU meters for input/gain reduction, and LED ladder-style output meters with two metering modes round out the feature set. In addition, the plug-in captures the circuit design differences between two CM5511 units.

## Controls Overview

- For all compressor controls, click a text label to set the control to that value. 
- Option-click (macOS) or Alt-click (Windows) to set a control to its default value.
- Shift-click a control for finer adjustment.

## Signal Flow

The diagram below represents how signals are processed in Capitol Mastering Compressor.

![cmc-flow.png](Capitol%20Mastering%20Compressor%20Manual_assets/2907916e35faf247d080729ae89d17e5126be057.png)

## Artist Presets

Presets from prominent Universal Audio artists are included. You can access the artist presets using the UAD preset browser.

This plug-in includes presets from:

- Evren Goknar
- Niko Bolas
- Nick Rives
- Chandler Harrod
- Gavin Lurssen
- Rik Simpson

------------------------------------------------------------------------

# Capitol Mastering Compressor Controls

## INPUT

The INPUT stepped control offers five input gain settings, in approximately 2.5 dB steps. The actual gain for each stepped position matches the original hardware.

## SC (switch)

The SC switch activates a 6 db/octave sidechain filter to reduce the amount of bass signal before the compressor’s detector. The sidechain switch has three positions; from right to left, these are Off, 1 (365 Hz), and 2 (700 Hz). These filter options are modeled from two different CM5511 hardware units.

The SC filter reduces compression and “pumping” on bass-heavy audio signals, without reducing the bass content of the audio signal itself.

## THRESHOLD

The THRESHOLD stepped control sets the level at which the compressor begins to act in approximately 1 dB steps. Rotate THRESHOLD clockwise to lower the threshold and increase compression. Signals below the threshold are not compressed.

**Note:** A parallel high-ratio, fixed threshold limiter is applied to very loud signals to prevent excessive clipping in the output amplifier. There are no controls for this portion of the circuit.

## ATTACK

The ATTACK stepped control sets the time before onset of the compressor. Available values are Slow, mS (Medium Slow), Med (Medium), mF (Medium Fast), and Fast. 

## RELEASE

The RELEASE stepped control sets the recovery time, or how long the compressor continues to reduce gain after reaching the threshold. Available values are Slow, mS (Medium Slow), Med (Medium), mF (Medium Fast), and Fast. The default value is Medium.

## RATIO

The RATIO stepped control sets the amount of gain reduction that is applied by the compressor. For example, a 2:1 ratio reduces the signal above the threshold by two times, with an input signal of 20 dB being attenuated to 10 dB. Higher ratios produce a more compressed sound. 

**Tip:** Click the + or - text labels to step through the ratio values. 

This control is not available on the original hardware, however the 3:1 and 4:1 ratios are modeled from two different CM5511 hardware units. Five ratio settings are available: 2:1, 3:1, 4:1, 6:1, and 10:1. 

**Note:** Signals must exceed the THRESHOLD value before they are attenuated by the RATIO amount.

## OUTPUT

The OUTPUT control provides compensation for the gain added by the compressor. This is a 24-position stepped control that reduces the output level in approximately 0.5 dB steps. Actual gain settings are modeled from the original hardware. 

**Note:** This control only reduces gain. To increase output gain, use the <a href="#h_01H0GKRMHJ0DRF3A2NYJGS4EM9" target="_self">GAIN</a> knob.  

## OUTPUT LED

The output LED for each channel lights to indicate output amplifier clipping.  

Amplifier clipping can be desirable for a certain sonic result, so as always, use the meters and your ears to find the right balance for your program material. If a minimally colored sound is desirable,the LEDs should illuminate only on transients. With sustained clipping (and continually lit LEDs), distortion will be audible.

## CHANNEL IN

The CHANNEL IN switches toggle processing on the compressor channels. The orange LEDs encircling the switches are lit when channels are enabled. 

**Note:** When CTRL LINK is enabled, pressing either switch toggles the state of both switches.

## CTRL LINK

The CTRL LINK switch links or unlinks channel controls. The orange LED encircling the switch is lit when controls are linked. 

### CTRL Link Notes 

- If you switch from unlinked to linked controls, the settings from the LEFT/MID channel are applied to both channels.
- When the plug-in is used on a mono track, the controls are always linked.

## LEFT-RIGHT / MID-SIDE 

The Capitol Mastering Compressor is arranged with two independent channels for compression. The controls for each channel can be linked or unlinked with the CTRL LINK switch. Channels can be configured for left/right or mid/side operation with the MID-SIDE/LEFT-RIGHT switch. 

**Tip:** The labels to the left of the INPUT knobs indicate the active channel configurations. 

**LEFT-RIGHT –** Allows you to compress the left and right side of the stereo program either independently or with the controls linked. In this configuration, the top channel controls apply to the left stereo channel, and the bottom channel controls apply to the right stereo channel. 

**MID-SIDE –** Allows you to process program material for the middle of the stereo image (mid) and for the left and right sides (side) independently. In this configuration, the top channel controls apply to the middle of the stereo image, and the bottom channel controls apply to the sides of the stereo image. 

**Note:** When you insert the Capitol Mastering Compressor on a mono track, this switch is fixed in LEFT-RIGHT mode.

## SIDECHAIN LINK

The SIDECHAIN LINK switch provides either DUAL MONO or linked (stereo) dynamics operation. In DUAL MONO mode, stereo material is processed independently on each channel. In stereo operation mode, both compressors react to peaks in the program material together, so both channels are compressed by the same amounts. 

Linking the sidechains prevents signals which appear on only one channel from shifting the stereo image of the output. For example, any large transient on either channel will cause both channels to compress, and the amount of compression will be similar to the amount of compression for a transient that would appear on both channels at the same time.

**Note:** When you insert the Capitol Mastering Compressor on a mono track, this switch is fixed in DUAL MONO mode.

## VU METERS

The VU meter displays either the amount of gain reduction (ATTEN), or input level before any processing (INPUT), depending upon the setting of the VU Meter switch.

------------------------------------------------------------------------

# Exclusive Controls

The remaining plug-in controls are added features that do not exist in the CM5511 hardware, but are provided to give you more control over your mastering results.

## MIX

The MIX control determines the balance between the compressor’s original and processed signal, to facilitate parallel compression. The range is from 0% (no processing) to 100% (wet, processed signal only). 

## HEADROOM

The HEADROOM stepped control enables best-practice operating level matching, or it can be used creatively to expand the sonic range of the processor. For example, HEADROOM enables adjustment of the internal operating reference level so that the compressor is not “pushed” into gain reduction as much. By fine-tuning Headroom, the nonlinear I/O distortion and compression response characteristics can be tailored independently of signal input levels. Increasing headroom (by rotating the control counter-clockwise) allows signals at the input to be pushed higher before they compress.

The HEADROOM control can be set from 4 to 28 dB in 4 dB increments. The default value is 16 dB. Note that headroom is increased (and compression is reduced) as the dB value decreases. 

**Tip:** Click the + or - text labels to step through the headroom values. 

### MIX and HEADROOM notes

- The MIX control adjusts only the compressed signal; other controls such as GAIN and SATURATOR/SHAPE still process the signal, regardless of the MIX control setting. 
- HEADROOM adjusts the compressed signal only.

## MONO FOLD

The MONO FOLD control allows you to sum the signal below a specified frequency to mono, to reduce the stereo effect for bass content and increase the impact of bass frequencies. The available range is 20 to 200 Hz.

**Tip:** Click OFF to quickly toggle between the OFF setting and the last knob setting. 

**Note:** When you insert the Capitol Mastering Compressor on a mono track, this knob is inoperative. 

## GAIN

The GAIN stepped control adjusts the signal level coming from the compressor and into the SATURATOR. GAIN provides ±12 dB of gain compensation, in 1 dB steps. 

**Tip:** Click the +12 or -12 text labels to step through the gain values. 

## SATURATOR / SHAPE

The SATURATOR adds harmonic content and increases apparent loudness by changing the small-signal gain of the saturator. You can mix in saturation with the SHAPE knob, with an available range of 0-100%.

**Tip:** Use the GAIN control to push further into saturation.

## OUTPUT METERS

The horizontal LED ladder-style metering provides a visual indication of relative signal peak or loudness levels at the output of the plug-in. Output meters behavior is determined by the dBFS/LUFS switch.

## dBFS/LUFS

The dBFS/LUFS switch sets the output meters to indicate compressor output in decibels Full Scale (dBFS) or Loudness Units Full Scale (LUFS).

- dBFS measures the level of a digital audio on a linear scale relative to its maximum possible level, typically represented as 0 dBFS
- LUFS measures loudness based on how the ear perceives loudness, and provides a more consistent measure of loudness across different audio content
- In dBFS mode, the meters shows Peak/RMS in the meter ladder and left/right peak text display
- In LUFS mode, the meters show three readouts: Momentary (meter ladders), the short term value text display (ST), and the integrated value text display (INT)
- "PK" (peak) label switches to indicate  "ST" and "INT" when LUFS is enabled
- The output meter and dBFS/LUFS switch continue to operate when the processor is powered off 

**Tip:** Click anywhere in the output meter display to clear meter peaks and reset 3 second hold metering.

![metering-lufs-dbfs.png](Capitol%20Mastering%20Compressor%20Manual_assets/2f92a7b00902a3456e91b2d1e0c37f67fdde70d2.png)

## POWER

The POWER switch enables or disables plug-in processing. The plug-in is active when this switch is in the up position, and the interface is lighted or more LEDs are lit. When disabled, all processor usage is stopped. The output meters and dBFS/LUFS switch continue to operate when the processor is powered off.

------------------------------------------------------------------------

# Historical Information

When Capitol Studios set out to create a compressor for in-house use by their mastering department, the design goals were clear: the staff needed a unit tailored for the modern world of high-headroom, low-noise mastering, but with a sound that encapsulated the character and warmth of beloved tube-based processors from Fairchild, Gates, Universal Audio, and others. The staff also required that the compressor be usable for mastering both digital and vinyl program material, and even suitable in the studio for production. 

![cmc-proto-19.png](Capitol%20Mastering%20Compressor%20Manual_assets/e27043ae7cd0e7316f541721c1dd96bc0ce8cbf3.png)

#### *Capitol Mastering Compressor Prototype*

Capitol's in-house service department created several prototypes, evolving the design over time, with direct feedback provided by the mastering engineers. High-profile, real-world projects provided the source material for critical listening and design decisions. The ultimate goal was to equip each of Capitol’s four dedicated mastering rooms with the same custom compressor, to create consistency in mastering output across a wide range of program material.

In 2011, the design was complete for a two-channel valve compressor with the highest quality components throughout, including vintage Mullard 6BC8 gain reduction tubes, mastering-grade John Hardy 990c discrete op amps, and carefully selected Cinemag input and output transformers. As expected for a mastering tool of this caliber, the unit features high quality precision-matched stepped controls for accurate recall, and the ability to link or unlink the two channels' side chains and controls. The electronics are packaged in a solid three rack unit chassis, with beautifully engraved overlays and faceplate. Vintage Bakelite knobs and classic custom VU meters complete the design.

![cmc-3-qtr.png](Capitol%20Mastering%20Compressor%20Manual_assets/5b94c09ffedec65956d79d082afa93eb5e0498c8.png)

With the final design complete, four CM5511 units were manufactured, and immediately put to use by Capitol's recording and mixing staff. (The compressor's name, "CM5511," is an amalgam of the year Capitol Records moved into the tower, 1955, and the year the compressor was completed, 2011.) The unique sound of the CM5511 made its way into all facets of the recording, mixing, and mastering process. Over time, one of the four units was adjusted further with a different sidechain filter center frequency and larger output attenuation steps. The CM5511 plug-in adopts both of these features from the modified unit. In addition, the modded unit's compression ratio was lowered from 4:1 to 3:1. The plug-in includes these original values and adds several other extrapolated ratios (2:1, 3:1, 4:1, 6:1 and 10:1). 

Capitol Studios granted Universal Audio unprecedented access to study two out of the four existing mastering compressors. With UA's legendary deep-dive circuit analysis and relentless scrutiny of the circuitry and sound of these modern classics, we developed a stunningly accurate and faithful software recreation.

Universal Audio worked closely with Capitol staff and alumni to collect plug-in design feedback and use case information. Additional artist and user feedback led directly to the development of crucial added features, to make this plug-in a complete solution for modern in-the-box recording, mixing, and mastering workflows. We believe our dedication to the development of this unique hardware will provide you with a tool that becomes an indispensable element of your creative process.

![cmc-internal.png](Capitol%20Mastering%20Compressor%20Manual_assets/a92ca64d38ca1776c82ae85f07a11cb428e6544d.png)

### Special Thanks

Special thanks to the Capitol Studios staff, both alumni and current, for all design inputs on this remarkable tool. Thanks to Robert Vosgien for sharing years of experience with the Capitol CM5511 Mastering Compressor and enlightening memories of the development and history. Thanks to Evren Göknar for sharing your amazing experiences, and for the copy of your fantastic benchmark "Major Label Mastering" book with the CM5511 on the cover. Thanks to Ron McMaster for perspective on vinyl cutting with the CM5511. Thanks to Niko Bolas for deeper details on the infamous CM5511 prototype, and thanks to Steve Genewick for just really, really wanting this plug-in to exist. Thanks to Roey Hershkovitz for allowing us not one, but two CM5511 units for study. Extra special thanks to Ian Sefchick for a truly stellar compressor design.

