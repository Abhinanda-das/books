---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/43460658366612-Managing-Latency-in-UAD-Console-for-Apollo-the-DAW.html'
converted_at: 2026-05-31T13:44:59Z
tool: htmlq+pandoc
title: 'Managing Latency in UAD Console for Apollo & the DAW'
word_count: 7065
---

# Managing Latency in UAD Console for Apollo & the DAW


- [**Considerations with Auto-Tune**](#h_01KAAM0RQGDZFVXZWCDF3XRHMB)
- [**Input Delay Compensation in UAD Console**](#h_01KAAM0RQJA6YPZYZFNX719MY8)
- [**Note on Aux channel usage in UAD Console**](#h_01KAAM0RQWHJWS1AM1J5X99D0V)
- [**Latency context from a player's perspective**](#h_01KAAM0RQWD450B8VJA6S7ZM98)
- [**Calculating latency over Dante with Apollo x16D, e1x, and e2m**](#h_01KAAM0RQW1MA33FDFZQYD1K8Z)
- [**Additional Plug-In Latency and Plug-In Specific Information**](#h_01KAAM0RR1SADEETZ6VS8FET2Q)\
   

To achieve sonic design goals, some UAD plug-ins introduce additional latency in addition to the existing hardware I/O latency. When these plug-ins are used in a DAW or UAD Console, enabling delay compensation keeps your tracks synchronized in the timeline. Plug-in delay compensation also helps maintain phase alignment when using multiple sources in a session.

The latency added by UAD plug-ins is negligible, typically between 0-100 samples, depending on the plug-in and session sample rate. The additional latency of all UAD plug-ins is listed, in samples, in the tables below for reference.

For related information, see the “Latency & Delay Compensation” chapter in the <a href="13444697234196-UAD-System-Manual.html" rel="noopener noreferrer" target="_blank"><strong><span class="wysiwyg-underline">UAD System Manual</span></strong></a>, and the “Latency & Apollo” chapter in the <a href="13445960631700-Apollo-Software-Manuals.html" rel="noopener noreferrer" target="_blank"><strong><span class="wysiwyg-underline">Apollo Software Manuals</span></strong></a>.

## Considerations with Auto-Tune

Auto-Tune dynamically adjusts latency depending on the settings used. It’s important to note that due to the dynamic nature of Auto-Tune’s latency, it is not compensated for by delay compensation in your DAW or UAD Console. For this article, we are looking at Auto-Tune Realtime X and Auto-Tune Realtime Advanced specifically.

**Classic Mode** has the lowest latency, with 1-2 ms of additional latency at 44.1 kHz (approximately 50-100 samples). This additional latency time halves when you double the sample rate, so for live sound processing, running at 96 kHz can further minimize the latency added.

In Classic Mode, the lowest latency options are Soprano, Low Male, and Instrument. The Alto-Tenor option has a marginally higher latency.

**Modern Mode** has slightly higher latency, with 4-7ms of additional latency at 44.1 kHz (approximately 175-300 samples). Again, the latency time is halved if you double the sample rate.

In Modern Mode, the latency varies from lower to higher as follows: Soprano, Low Male, Alto-Tenor, and then Instrument.

## Input Delay Compensation in UAD Console

Input Delay Compensation aligns all inputs up to a prescribed total latency in samples, and is enabled by default. You will want to enable Input Delay Compensation if you are using more than one mic to record the same source or adjacent sources. This ensures the input signals remain phase-aligned.  

### In UAD Console

In UAD Console, which is the direct monitoring path, the amount of delay added by Input Delay Compensation is automatic. To maintain the lowest possible latency for phase alignment at all times, only the minimum amount of delay required to align an input is applied, up to the maximum value of the setting.

For example, when set to Short (100 samples) and 31 samples are required for compensation, then only 31 samples of delay are applied to the other UAD Console inputs.

### In your DAW

In your DAW, which is the record path, the Input Delay Compensation amount is always added to all inputs, even if no active plug-ins require it. This additional input latency is reported by Apollo’s drivers, so it is automatically compensated by the DAW. Short and Medium delay compensation is generally not noticeable from a player performance standpoint. The latency is halved by doubling the sample rate.

### Input Delay Compensation Values in UAD Console

<div>

 

<figure class="wysiwyg-table wysiwyg-table-align-left" style="width: 56.74%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized" style="margin-left: 0px; margin-right: auto;">
<colgroup>
<col style="width: 39%" />
<col style="width: 61%" />
</colgroup>
<tbody>
<tr>
<td style="border-style: none"><strong> Setting </strong></td>
<td style="border-style: none"><strong> Delay Compensation (samples)</strong></td>
</tr>
<tr>
<td style="border-style: none"> Off</td>
<td style="border-style: none"> 0</td>
</tr>
<tr>
<td style="border-style: none"> Short</td>
<td style="border-style: none"> 100</td>
</tr>
<tr>
<td style="border-style: none"> Medium</td>
<td style="border-style: none"> 200</td>
</tr>
<tr>
<td style="border-style: none"> Medium-Long</td>
<td style="border-style: none"> 300</td>
</tr>
<tr>
<td style="border-style: none"> Long</td>
<td style="border-style: none"> 1000</td>
</tr>
</tbody>
</table>
</figure>

</div>

### Input Delay Compensation Exceeded Dialog

# ![](Managing%20Latency%20in%20UAD%20Console%20for%20Apollo%20%26%20the%20DAW_assets/1576671445c71e282018967963ec7f67c9a4be5c.png)

The “Input Delay Compensation Exceeded” dialog appears in UAD Console when the maximum compensation amount for a given setting is exceeded on a channel. If this occurs, to maintain phase alignment, you can either increase the Input Delay Compensation value or reduce the number of latency-introducing plug-ins on the channel. 

In some cases, having misaligned tracks may be acceptable, or you may desire minimum latency regardless of the misalignment it can introduce. For example, when monitoring single or isolated sources, and not using multiple mics on the same source. In these cases, delay compensation can be set to Off. Hence, the dialog is just a warning and not an error.

Some mastering-grade UAD plug-ins have higher than typical latency, and we do not recommend monitoring live inputs in UAD Console with these plug-ins: 

- Precision Multiband - Approximately 15,000 samples
- C-Suite C-Max - Approximately 630 samples
- Ampex ATR-102 - Approximately 2200 samples

Please note that the exact latency can vary depending on the sample rate being used.

## Note on Aux channel usage in UAD Console

UAD Console’s Aux returns have 72 samples of additional latency when compared to the monitor outputs. This is necessary to maintain the lowest possible latency for the channel input signals. Because they cannot be compensated, aux buses are best suited for time-based effects, such as reverbs and delays.

## Latency context from a player's perspective

Sound travels about 1.13 feet (0.34 meters) per millisecond, so 10 ms latency is the equivalent of sitting about 11.3 feet (3.4 meters) from a speaker.

## Calculating latency over Dante with Apollo x16D, e1x, and e2m

When using an Apollo x16D and Dante peripherals, you must factor in Dante transport latency. This is defined by the capabilities of the connected device.  

For Apollo x16D, the Dante latency can be set to 0.25ms, 1ms, 2ms, or 5ms.  

For Apollo e2m and e1x, the Dante latency can be set to 1ms, 2ms, or 5ms.  

All devices on the Dante network must be capable of conforming to the same Dante latency to achieve the set Dante transport latency.

<span style="color: #2F3941;">**Here’s a real-life example using an Apollo x16D and an Apollo e2m, with the Dante latency set to 1ms:**</span>

- Live keyboards are connected to an Apollo e2m’s line input. 
- Then, sent over Dante to an x16d for UAD DSP processing. 
- Finally, returned to the Apollo e2m over Dante for monitoring with headphones.

<span style="color: #2F3941;">**The latency in this example can be calculated as follows:**</span>

- Apollo e2m’s A/D conversion adds **.2ms**  
- Dante transport latency adds **1ms**  
- At 96kHz the x16D adds **.8ms** (+ any additional plug-in latency in samples)\
  *\*note - this .8ms changes to ~1.5ms at 48kHz, but at 176.4 / 192kHz it’s still ~0.8ms  *
- Dante transport latency adds another **1ms** 
- Apollo e2m’s D/A conversion adds **.2ms**

So, the total will be **3.2ms** at 96kHz (+ any additional plug-in latency in samples).

Please note that doubling the sample rate will halve the additional plug-in latency time, and changing the sample rate will not affect the Dante transport latency.  

## Additional Plug-In Latency and Plug-In Specific Information

EMT 250, Lexicon 224, and Lexicon 480L use anti-aliasing filters for their A/D and D/A conversion that are not linear-phase filters; therefore, the emulations do not have a latency that is the same at all frequencies. Thus, they cannot report to the delay compensation engines a delay that is correct for all frequencies. The reported values are accurate at low frequencies, but become inaccurate at high frequencies.

For example, when EMT 250 is in the Delay program mode and the delay time and predelay values are set to zero, the plug-in output will not be completely cancelled when mixing with inverted polarity against an unprocessed track; high frequencies will still leak through. However, the latency through the dry side of the wet/dry mix and the latency when the plug-in is bypassed via the EMT 250 Power switch do not have this behavior and will be fully compensated by the DAW.

Please see our UAD DSP table below for details of additional latency incurred by each UAD DSP plug-in.\
\
***Note:** UA-developed plug-ins are italicized.*

<div>

<figure class="wysiwyg-table" style="width: 100%;">
<table class="wysiwyg-table table--striped wysiwyg-table-resized" style="margin-left: 0px; margin-right: auto;">
<colgroup>
<col style="width: 43%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 9%" />
<col style="width: 8%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Plug-In</strong></td>
<td colspan="6" style="text-align: center;"><strong>Sample Rate (kHz)</strong></td>
</tr>
<tr>
<td style="text-align: center;"> </td>
<td style="text-align: center;"><strong>44.1kHz</strong></td>
<td style="text-align: center;"><strong>48kHz</strong></td>
<td style="text-align: center;"><strong>88.2kHz</strong></td>
<td style="text-align: center;"><strong>96kHz</strong></td>
<td style="text-align: center;"><strong>176.4kHz</strong></td>
<td style="text-align: center;"><strong>192kHz</strong></td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD 4K Buss Compressor</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD 4K Channel Strip</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD A-Type Multiband Enhancer</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD ADA Flanger</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD ADA STD-1 Stereo Tapped Delay</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD AKG BX 20</em></td>
<td style="text-align: center;">983</td>
<td style="text-align: center;">974</td>
<td style="text-align: center;">2078</td>
<td style="text-align: center;">2060</td>
<td style="text-align: center;">4156</td>
<td style="text-align: center;">4120</td>
</tr>
<tr>
<td style="text-align: center;">UAD Ampeg B15N</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Ampeg SVT3Pro</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Ampeg SVTVR</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Ampeg SVTVR Classic</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Ampex ATR-102</em></td>
<td style="text-align: center;">2262</td>
<td style="text-align: center;">2262</td>
<td style="text-align: center;">2262</td>
<td style="text-align: center;">2262</td>
<td style="text-align: center;">2262</td>
<td style="text-align: center;">2262</td>
</tr>
<tr>
<td style="text-align: center;">UAD AMS DMX 15-80 S</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD AMS Neve DFC Channel Strip</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD AMS RMX16</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD AMS RMX16 Expanded</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD API 550A</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD API 560</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD API 2500</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD API Preamp</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD API Vision Channel Strip</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD API Vision Channel Strip Legacy</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD Auto-Tune Realtime Access*</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Auto-Tune Realtime Advanced*</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Auto-Tune Realtime X*</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Avalon VT-737sp</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Bermuda Triangle</em></td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">80</td>
<td style="text-align: center;">80</td>
<td style="text-align: center;">20</td>
<td style="text-align: center;">20</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Brigade Chorus</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_digital V2</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_digital V2 Mono</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_digital V3</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_digital V3 mix</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_masterdesk</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_masterdesk Classic</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">304</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_refinement</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_saturator V2</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_subsynth</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD bx_tuner</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD C-Suite C-Axe</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD C-Suite C-Max</td>
<td style="text-align: center;">634</td>
<td style="text-align: center;">692</td>
<td style="text-align: center;">1266</td>
<td style="text-align: center;">1354</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD C-Suite C-Vox</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Cambridge</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Capitol Chambers</em></td>
<td style="text-align: center;">320</td>
<td style="text-align: center;">320</td>
<td style="text-align: center;">752</td>
<td style="text-align: center;">752</td>
<td style="text-align: center;">1504</td>
<td style="text-align: center;">1504</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Century Tube Channel Strip</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD Chandler GAV19T</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Chandler Limited Curve Bender</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Chandler Limited Zener Limiter</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Cooper Time Cube</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD CS-1</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Dangerous BAX EQ Master</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Dangerous BAX EQ Mix</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD dbx 160</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Diezel Herbert</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Diezel VH4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD DreamVerb</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Dytronics Cyclosonic Panner</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Dytronics Tri-Stereo Chorus</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Eden WT800</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">11</td>
<td style="text-align: center;">11</td>
<td style="text-align: center;">26</td>
<td style="text-align: center;">26</td>
</tr>
<tr>
<td style="text-align: center;">UAD elysia alpha master</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
<tr>
<td style="text-align: center;">UAD elysia alpha mix</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
<tr>
<td style="text-align: center;">UAD elysia mpressor</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Empirical Labs Distressor</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Empirical Labs FATSO Jr</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Empirical Labs FATSO Sr</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD EMT 140</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD EMT 250†</em></td>
<td style="text-align: center;">75</td>
<td style="text-align: center;">11</td>
<td style="text-align: center;">85</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">107</td>
<td style="text-align: center;">50</td>
</tr>
<tr>
<td style="text-align: center;">UAD ENGL E646 VS</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD ENGL E765 RT</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD ENGL Savage 120</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD EP-34 Tape Echo</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Eventide H910 Harmonizer</td>
<td style="text-align: center;">5</td>
<td style="text-align: center;">5</td>
<td style="text-align: center;">71</td>
<td style="text-align: center;">71</td>
<td style="text-align: center;">203</td>
<td style="text-align: center;">203</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Fairchild 660</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Fairchild 670</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Fairchild 670 Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Fender 55 Tweed Deluxe</em></td>
<td style="text-align: center;">87</td>
<td style="text-align: center;">87</td>
<td style="text-align: center;">169</td>
<td style="text-align: center;">169</td>
<td style="text-align: center;">284</td>
<td style="text-align: center;">284</td>
</tr>
<tr>
<td style="text-align: center;">UAD Friedman BE100</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Friedman Buxom Betty</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Friedman DS40</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Fuchs Overdrive Supreme 50</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Fuchs Train II</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Galaxy Tape Echo</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Gallien Krueger 800RB</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Harrison 32C</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Harrison 32C SE</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Helios Type 69</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Helios Type 69 Legacy</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Hemisphere Mic Collection</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Hitsville EQ</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Hitsville EQ Mastering</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Hitsville Reverb Chambers</em></td>
<td style="text-align: center;">320</td>
<td style="text-align: center;">320</td>
<td style="text-align: center;">752</td>
<td style="text-align: center;">752</td>
<td style="text-align: center;">1504</td>
<td style="text-align: center;">1504</td>
</tr>
<tr>
<td style="text-align: center;">UAD Ibanez Tube Screamer TS808</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">80</td>
<td style="text-align: center;">80</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Korg SDD-3000</em></td>
<td style="text-align: center;">87</td>
<td style="text-align: center;">87</td>
<td style="text-align: center;">119</td>
<td style="text-align: center;">119</td>
<td style="text-align: center;">344</td>
<td style="text-align: center;">344</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD LA-6176 Channel Strip</em></td>
<td style="text-align: center;">110</td>
<td style="text-align: center;">110</td>
<td style="text-align: center;">110</td>
<td style="text-align: center;">110</td>
<td style="text-align: center;">176</td>
<td style="text-align: center;">176</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Lexicon 224†</em></td>
<td style="text-align: center;">84</td>
<td style="text-align: center;">79</td>
<td style="text-align: center;">90</td>
<td style="text-align: center;">97</td>
<td style="text-align: center;">107</td>
<td style="text-align: center;">116</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Lexicon 480L†</em></td>
<td style="text-align: center;">121</td>
<td style="text-align: center;">64</td>
<td style="text-align: center;">177</td>
<td style="text-align: center;">174</td>
<td style="text-align: center;">289</td>
<td style="text-align: center;">284</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Little Labs IBP</em></td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">14</td>
<td style="text-align: center;">14</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Little Labs VOG</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Maag EQ4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Maag EQ4 MS</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Manley Massive Passive</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Manley Massive Passive MST</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD Manley Reference Mic Preamp</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Manley Variable Mu</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Manley VOXBOX</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD Marshall Bluesbreaker 1962</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">25</td>
<td style="text-align: center;">25</td>
</tr>
<tr>
<td style="text-align: center;">UAD Marshall JMP 2203</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">25</td>
<td style="text-align: center;">25</td>
</tr>
<tr>
<td style="text-align: center;">UAD Marshall Plexi Classic</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">25</td>
<td style="text-align: center;">25</td>
</tr>
<tr>
<td style="text-align: center;">UAD Marshall Plexi Super Lead 1959</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">25</td>
<td style="text-align: center;">25</td>
</tr>
<tr>
<td style="text-align: center;">UAD Marshall Silver Jubilee 2555</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">6</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">25</td>
<td style="text-align: center;">25</td>
</tr>
<tr>
<td style="text-align: center;">UAD MDWEQ5-3B</td>
<td style="text-align: center;">27</td>
<td style="text-align: center;">27</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD MDWEQ5-5B</td>
<td style="text-align: center;">27</td>
<td style="text-align: center;">27</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Millennia NSEQ-2</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Moog Multimode Filter</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Moog Multimode Filter SE</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Moog Multimode Filter XL</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD MXR Flanger-Doubler</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 88RS</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 88RS Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 1073</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 1073 Legacy</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 1073SE Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 1081</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 1081SE</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 1084</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 2254 E</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 2254 E Dual</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 31102</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 31102SE</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 33609 C</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve 33609SE</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Neve Preamp</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Ocean Way Mic Collection</em></td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">96</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Ocean Way Mic Collection 180</em></td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">96</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Ocean Way Studios</em></td>
<td style="text-align: center;">224</td>
<td style="text-align: center;">224</td>
<td style="text-align: center;">720</td>
<td style="text-align: center;">720</td>
<td style="text-align: center;">1568</td>
<td style="text-align: center;">1568</td>
</tr>
<tr>
<td style="text-align: center;">UAD OTO Biscuit 8-bit Effects</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">26</td>
<td style="text-align: center;">57</td>
<td style="text-align: center;">60</td>
<td style="text-align: center;">112</td>
<td style="text-align: center;">119</td>
</tr>
<tr>
<td style="text-align: center;">UAD Oxford Dynamic EQ</td>
<td style="text-align: center;">50</td>
<td style="text-align: center;">50</td>
<td style="text-align: center;">35</td>
<td style="text-align: center;">38</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Oxford Envolution</td>
<td style="text-align: center;">20</td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">40</td>
<td style="text-align: center;">43</td>
<td style="text-align: center;">79</td>
<td style="text-align: center;">86</td>
</tr>
<tr>
<td style="text-align: center;">UAD Oxford EQ</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Oxford Inflator</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Oxford Limiter</td>
<td style="text-align: center;">148</td>
<td style="text-align: center;">148</td>
<td style="text-align: center;">242</td>
<td style="text-align: center;">242</td>
<td style="text-align: center;">375</td>
<td style="text-align: center;">375</td>
</tr>
<tr>
<td style="text-align: center;">UAD Oxford SuprEsser DS</td>
<td style="text-align: center;">178</td>
<td style="text-align: center;">178</td>
<td style="text-align: center;">390</td>
<td style="text-align: center;">390</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Oxide Tape</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Buss Compressor</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Channel Strip</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision De-Esser</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Delay Mod</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Delay Mod L</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Enhancer Hz</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Enhancer kHz</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Equalizer</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision K-Stereo</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Limiter</em></td>
<td style="text-align: center;">64</td>
<td style="text-align: center;">69</td>
<td style="text-align: center;">129</td>
<td style="text-align: center;">140</td>
<td style="text-align: center;">259</td>
<td style="text-align: center;">281</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Maximizer</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Multiband</em></td>
<td style="text-align: center;">15360</td>
<td style="text-align: center;">16896</td>
<td style="text-align: center;">30720</td>
<td style="text-align: center;">33792</td>
<td style="text-align: center;">61440</td>
<td style="text-align: center;">66048</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Precision Reflection Engine</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Pultec EQP-1A</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Pultec EQP-1A Legacy</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Pultec HLF-3C</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Pultec MEQ-5</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Pultec-Pro Legacy</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Pure Plate</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Putnam Mic Collection</em></td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">96</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Putnam Mic Collection 180</em></td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">96</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Raw</em></td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">40</td>
<td style="text-align: center;">40</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD RealVerb-Pro</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Roland CE-1</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Roland Dimension D</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Roland RE-201</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Shadow Hills Class A Mastering Comp</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
<tr>
<td style="text-align: center;">UAD Shadow Hills Mastering Compressor</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Softube Amp Room Half-Stack</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Softube Bass Amp Room</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Softube Bass Amp Room 8x10</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Softube Metal Amp Room</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Softube Vintage Amp Room</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Softube Vocoder</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Sound Machine Wood Works</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">176</td>
<td style="text-align: center;">176</td>
<td style="text-align: center;">368</td>
<td style="text-align: center;">368</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Sphere Mic Collection</em></td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">96</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Sphere Mic Collection 180</em></td>
<td style="text-align: center;">22</td>
<td style="text-align: center;">24</td>
<td style="text-align: center;">44</td>
<td style="text-align: center;">48</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">96</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD SPL Transient Designer</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD SPL TwinTube</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
<tr>
<td style="text-align: center;">UAD SPL Vitalizer MK2-T</td>
<td style="text-align: center;">16</td>
<td style="text-align: center;">16</td>
<td style="text-align: center;">16</td>
<td style="text-align: center;">16</td>
<td style="text-align: center;">16</td>
<td style="text-align: center;">16</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD SSL E Channel Strip</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD SSL E Channel Strip Legacy</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD SSL G Bus Compressor</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD SSL G Bus Compressor Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Studer A800</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Studio D Chorus</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Suhr PT100</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Suhr SE100</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">N/A</td>
</tr>
<tr>
<td style="text-align: center;">UAD Summit Audio TLA-100A</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Teletronix LA-2</em></td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">89</td>
<td style="text-align: center;">89</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Teletronix LA-2A Gray</em></td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">89</td>
<td style="text-align: center;">89</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Teletronix LA-2A Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Teletronix LA-2A Silver</em></td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">56</td>
<td style="text-align: center;">89</td>
<td style="text-align: center;">89</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Teletronix LA-3A</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Thermionic Culture Vulture</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD Tonelux Tilt</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Tonelux Tilt Live</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD Trident A-Range</em></td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">31</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">13</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD TS Overdrive</em></td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">80</td>
<td style="text-align: center;">80</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Tube-Tech CL 1B</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Tube-Tech CL 1B mk II</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Tube-Tech ME 1B</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Tube-Tech PE 1C</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 175-B</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 176</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 610-A</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 610-B</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 1176 Rev A</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 1176AE</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 1176LN Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 1176LN Rev E</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD UA 1176SE Legacy</em></td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;"><em>UAD V76 Preamp</em></td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">55</td>
<td style="text-align: center;">88</td>
<td style="text-align: center;">88</td>
</tr>
<tr>
<td style="text-align: center;">UAD Valley People Dyna-mite</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Vertigo VSC-2</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
<td style="text-align: center;">0</td>
</tr>
<tr>
<td style="text-align: center;">UAD Vertigo VSM-3</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
<td style="text-align: center;">32</td>
</tr>
</tbody>
</table>
</figure>

*\* See the "Considerations With Auto-Tune" section*\
*† See notes in the "Additional Plug-In Latency and Plug-In Specific Information" section*

 

</div>

