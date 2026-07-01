---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Oxford Dynamic EQ Manual.pdf
converted_at: 2026-06-03T09:30:09Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 3484
---

## **Contents** 

|**1**|**What is dynamic EQ?**|**What is dynamic EQ?**|**What is dynamic EQ?**||**4**|
|---|---|---|---|---|---|
||1.1|Multi-band dynamics vs. dynamic EQ . . . . . . . . . . . . . . . . . . .|||5|
|**2**|**EQ Controls**||||**7**|
||2.1|Ofset Gain . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|7|
||2.2|Target Gain . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|8|
||2.3|EQ Enabled . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|8|
||2.4|EQ Listen . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|8|
||2.5|EQ Channel . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|9|
||2.6|EQ Type . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|9|
||2.7|EQ Frequency|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|10|
||2.8|EQ Q . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|10|
||2.9|EQ Colour Fill .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|10|
||2.10 EQ Graph Zoom|||. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|11|
||2.11 FFT Display . .||.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|11|
|**3**|**Side Chain Controls**||||**12**|
||3.1|What is the side|chain?<br>. . . . . . . . . . . . . . . . . . . . . . . . . . .||12|
||3.2|SC Enabled . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|12|
||3.3|SC Drag handle|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|12|
||3.4|SC Listen . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|13|
||3.5|SC Channel . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|13|
||3.6|SC Type . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|13|
||3.7|SC Frequency|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|14|
||3.8|SC Q . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|14|
|**4**|**Dynamics Controls**||||**15**|
||4.1|Detect . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|15|
||4.2|Trigger . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|15|
||4.3|Threshold . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|16|
||4.4|Dynamics . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|17|
||4.5|Attack . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|17|



||4.6|Release . . . . . . . . . . . . .|. . . . . . . . . . . . . . . . . . . . . . .|18|
|---|---|---|---|---|
|**5**|**Output controls**|||**19**|
||5.1|Output Trim . . . . . . . . . . .|. . . . . . . . . . . . . . . . . . . . . . .|19|
|**6**|**Tech**|**Notes**||**20**|
||6.1|DSP load<br>. . . . . . . . . . . .|. . . . . . . . . . . . . . . . . . . . . . .|20|
||6.2|Gain-Q Dependency . . . . . .|. . . . . . . . . . . . . . . . . . . . . . .|20|
||6.3|Dynamic Transfer Function<br>. .|. . . . . . . . . . . . . . . . . . . . . . .|21|
|||6.3.1<br>Downwards Compression . . . . . . . . . . . . . . . . . . . . . .||22|
|||6.3.2<br>Upwards Expansion . .|. . . . . . . . . . . . . . . . . . . . . . .|23|
|||6.3.3<br>Upwards Compression|. . . . . . . . . . . . . . . . . . . . . . .|24|
|||6.3.4<br>Downwards Expansion|. . . . . . . . . . . . . . . . . . . . . . .|24|
|**7**|**Preset Manager Toolbar**|||**26**|
|**8**|**Copyright and Acknowledgements**|||**27**|



_1 WHAT IS DYNAMIC EQ?_ 

## **1 What is dynamic EQ?** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0004-02.png>)


Equalisation is the audio engineer’s most widely used processing tool. However, the equalisation applied is usually static – it remains the same over time. 

This is often undesirable! For example, a presence boost which was appropriate during one section of a performance may become harsh during another section. 

The two most common solutions are automation and multi-band dynamics processing. Automation is only convenient when the spectral changes occur over a long period of time, and aren’t repetitive. Typical multi-band dynamics processors work to some extent, but with inconvenient downsides. 

_Go to contents_ 

4 

_www.sonnox.com_ 

_1.1 Multi-band dynamics vs. dynamic EQ_ 

_1 WHAT IS DYNAMIC EQ?_ 

## **1.1 Multi-band dynamics vs. dynamic EQ** 

Multi-band compressors/expanders and dynamic EQs work in a similar way. They both split the input signal into multiple parallel paths. Each path is filtered to restrict its frequency range, then sent into a compressor or expander. 

A dynamic EQ applies the gain reduction/expansion to the gain parameter of a parametric equaliser which processes the original input signal. 

Multi-band compressor/expanders apply their gain reduction directly to each filtered signal, then combine them to reconstruct the original wide-band input signal. This reconstruction approach has some downsides: 

## **Static phase shift** 

When the band-limited signals are combined to reconstruct the input signal, a static phase shift is present at their cross-over point. The band-limiting can be achieved using linear-phase filters, however these incur high latency and can degrade transient response at lower frequencies. 

## **Spectral shape** 

Multi-band processors typically afford less precise frequency adjustment than a parametric equaliser. If steeper filtes are used to provide greater precision, phase shift at the crossover points increases. 

## **Bands cannot overlap** 

Some multi-band processors get around the phase response issue, but are still left with a problem – the bands cannot be overlapped! This can pose significant problems when a combination of gentle character modification and precise correction is required. 

But Multi-band processors do have an advantage over most dynamic EQs. As a boost or cut increases, the width reduces. This is similar to the proportional Q response or gain / Q depenency of many well loved analogue EQ processors. 

When using an EQ which does not have this gain / Q dependent response, gain changes often require Q changes to maintain the desired effect. Of course, this is highly undesirable if the gain is being modulated dynamically! See Gain-Q Dependency for details. 

_Go to contents_ 

5 

_www.sonnox.com_ 

_1.1 Multi-band dynamics vs. dynamic EQ_ 

_1 WHAT IS DYNAMIC EQ?_ 

The Oxford Dynamic EQ combines the benefits of dynamic EQ with the Oxford EQ’s Type 3 gain / Q dependency, giving you the best of both! 

_Go to contents_ 

6 

_www.sonnox.com_ 

_2 EQ CONTROLS_ 

## **2 EQ Controls** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0007-02.png>)


## **2.1** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0007-04.png>)


The Offset Gain determines the resting, or static gain of each equaliser section. 

_Go to contents_ 

7 

_www.sonnox.com_ 

_2.2 Target Gain_ 

_2 EQ CONTROLS_ 

## **2.2 Target Gain** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0008-03.png>)


The Target Gain determines the gain which the EQ band will attempt to reach dynamically. 

This means that each equaliser section’s gain is constrained between these two settings, preventing accidental over-processing which can occur with other dynamic equalisers. 

When multiple EQ sections overlap, their combined response can exceed the range defined by each section’s Offset and Target Gain settings. 

## **2.3 EQ Enabled** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0008-08.png>)


Enable and Disable all processing for this band. 

## **2.4 EQ Listen** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0008-11.png>)



![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0008-12.png>)


**----- Start of picture text -----**<br>
Go to contents<br>**----- End of picture text -----**<br>


8 

_www.sonnox.com_ 

_2.5 EQ Channel_ 

_2 EQ CONTROLS_ 

Listen to just the frequency range which will be processed. This can help when fine tuning your EQ settings. 

## **2.5 EQ Channel** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0009-04.png>)


Select the output channel to apply this band’s EQ to. 

You can select to process: 

- Stereo (both channels equally) 

- Left only 

- Right only 

- Mid only 

- Side only 

## **2.6 EQ Type** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0009-13.png>)


Select the EQ type which is applied to the output signal. 

The available types are: 

- Low Shelf 

- Bell 

- High Shelf. 

_Go to contents_ 

9 

_www.sonnox.com_ 

_2.7 EQ Frequency_ 

_2 EQ CONTROLS_ 

## **2.7 EQ Frequency** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0010-03.png>)


Set the centre frequency (Bell EQ type), or corner frequency (Shelf EQ types) for this band. 

## **2.8 EQ Q** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0010-06.png>)


Set the Q (width) of this band’s Bell EQ type. The Q control is disabled for the Shelf EQ types. 

## **2.9 EQ Colour Fill** 

Drag up/down to set the Target and Offset Gains, retaining their relative levels. 

Drag left/right to set the centre frequency of this band. 

_Go to contents_ 

10 

_www.sonnox.com_ 

_2.10 EQ Graph Zoom_ 

_2 EQ CONTROLS_ 

## **2.10 EQ Graph Zoom** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0011-03.png>)


Toggle the graph dB scale between -/+4 dB, -/+6 dB, -/+12 dB and -/+20 dB scales. 

## **2.11 FFT Display** 

This shows the spectrum of the processed output signal. When a Listen button is enabled, it shows the filtered side chain signal. 

When used in the UAD Console, the Oxford Dynamic EQ runs in realtime mode. When running in realtime mode, the FFT Display is automatically disabled for maximum efficiency. 

_Go to contents_ 

11 

_www.sonnox.com_ 

_3 SIDE CHAIN CONTROLS_ 

## **3 Side Chain Controls** 

## **3.1 What is the side chain?** 

The ‘side chain’ is the signal path which controls the dynamics processor. 

The original input signal is copied and filtered to focus on a narrow frequency range. This filtered signal is fed into the band’s dynamics processor, which controls the EQ gain applied by that band. 

By default the side chain filter matches the EQ band, using the same type, frequency and Q. This provides the easiest way to apply dynamic EQ only when it’s needed. 

## **3.2 SC Enabled** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0012-07.png>)


Enable to control the side chain filter independently of the EQ band. 

## **3.3 SC Drag handle** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0012-10.png>)


Drag the middle node left/right to set the centre frequency of this side chain filter. Drag the edge nodes left/right to set the Q of this side chain filter. 

The nodes are greyed out when the side chain is disabled. 

_Go to contents_ 

12 

_www.sonnox.com_ 

_3.4 SC Listen_ 

_3 SIDE CHAIN CONTROLS_ 

## **3.4 SC Listen** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0013-03.png>)


Listen to the side chain signal filtered using the side chain filter settings. This can help when fine tuning the frequency range to react to dynamically. 

## **3.5 SC Channel** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0013-06.png>)


Select the input signal channel to feed into this band’s side chain path. 

You can select to feed the side chain with: 

- Stereo (both channels equally) 

- Left only 

- Right only 

- Mid only 

- Side only 

## **3.6 SC Type** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0013-15.png>)


_Go to contents_ 

13 

_www.sonnox.com_ 

_3.7 SC Frequency_ 

_3 SIDE CHAIN CONTROLS_ 

Select the filter type which is applied to this band’s side chain signal. 

The available types are: 

- Low Pass 

- Band Pass 

- High Pass. 

These correspond to an EQ Type of Low Shelf, Bell, and High Shelf respectively. 

## **3.7 SC Frequency** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0014-09.png>)


Set the centre frequency (Band Pass filter type), or cutoff frequency (High and Low Pass filter types) of the side chain filter. 

## **3.8 SC Q** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0014-12.png>)


Set the Q (width) of the side chain Band Pass filter. The Q control is disabled for the Low Pass and High Pass filter types. 

_Go to contents_ 

14 

_www.sonnox.com_ 

_4 DYNAMICS CONTROLS_ 

## **4 Dynamics Controls** 

Each EQ band is controlled by a powerful dynamics processor, providing upwards and downwards compression and expansion. However, it’s not necessary to know the difference between these types of processing. See Trigger for details. 

## **4.1 Detect** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0015-04.png>)


Choose Peak to react to overall peak signal level. Choose Onsets to react only to sudden increases in signal level, while ignoring the overall peak level. 

Onset detection is useful for reacting to transients, staccato notes and even sibilance! 

## **4.2 Trigger** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0015-08.png>)


_Go to contents_ 

15 

_www.sonnox.com_ 

_4 DYNAMICS CONTROLS_ 

_4.3 Threshold_ 

In Above mode, gain changes dynamically when the signal is above the Threshold. Use Above mode for downwards compression and upwards expansion. 

In Below mode, gain changes dynamically when the signal is below the Threshold. Use Below mode for upwards compression and downwards expansion (gating). 

When selecting a Trigger mode, just ask yourself: “Do I want to start applying gain when the signal **rises above** the Threshold, or when the signal **falls below** it?”” 

See Dynamic Transfer Function for more details. 

## **4.3 Threshold** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0016-07.png>)


Set the level at which the dynamics processing becomes active (depending on the Trigger setting). 

This Threshold level is preceded by a 10dB knee to smooth the transition away from the Offset Gain. 

_Go to contents_ 

16 

_www.sonnox.com_ 

_4 DYNAMICS CONTROLS_ 

_4.4 Dynamics_ 

## **4.4 Dynamics** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0017-03.png>)


Set how reactive the band’s gain is. This is similar to a compressor’s ratio control. 

At high Dynamics settings, the band’s gain is more likely to reach the Target Gain. At 0% the band will stay at the Offset Gain. 

## **4.5 Attack** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0017-07.png>)


Set how slowly the band approaches the Target Gain. 

_Go to contents_ 

17 

_www.sonnox.com_ 

_4 DYNAMICS CONTROLS_ 

_4.6 Release_ 

## **4.6 Release** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0018-03.png>)


Set how slowly the band recovers to the Offset Gain. 

_Go to contents_ 

18 

_www.sonnox.com_ 

_5 OUTPUT CONTROLS_ 

## **5 Output controls** 

## **5.1 Output Trim** 

Set the output gain of the plug-in to avoid clipping or match the dry and processed signal levels. 

_Go to contents_ 

19 

_www.sonnox.com_ 

_6 TECH NOTES_ 

## **6 Tech Notes** 

## **6.1 DSP load** 

In order to conserve as much of your DSP resources as possible, the UAD Oxford Dynamic EQ doesn’t use DSP resources for disabled EQ bands. 

This means that if there are insufficient DSP resources available when it’s inserted, you’ll only be able to enable some of the EQ bands. If you would prefer to always know that, once inserted, all EQ bands will be usable, just enable the **DSP Load Lock** option in the UAD Meter & Control Panel’s Configuration tab. 

## **6.2 Gain-Q Dependency** 

Filters with some amount of gain / Q dependency are sometimes referred to as ‘proportional Q filters’. The Oxford Dynamic EQ provides gain / Q dependency which matches the R3 EQ’s Type 3 response. 

From the Oxford R3 EQ user guide: 

This style of EQ has a moderate amount of gain / Q dependency whereby the Q reduces with gain. This provides the EQ with a softer characteristic as EQ is progressively applied and since the effective bandwidth is increased for low gain settings, it sounds louder and more impressive when used at moderate settings. The gentler Q curve also lends itself better to overall EQ fills and more subtle corrections in instrument and vocal sources. Turning the Gain control seems to produce the effect that the ear is expecting, without needing to adjust the Q control too often. Therefore EQs of this type are often dubbed as ‘more musical sounding’. 

This EQ most resembles the older and well-loved Neve types, their modern derivatives and the later SSL G Series. Also many of the more popular outboard EQs have this dependency to some extent. 

This gain / Q dependency is highly important for a dynamic EQ, where the gain is modulated dynamically. A dynamic EQ with no gain / Q dependency will tend to 

_Go to contents_ 

20 

_www.sonnox.com_ 

_6 TECH NOTES_ 

_Dynamic Transfer Function_ 

_6.3_ 

sound over-processed or harsh as more gain cut/boost is applied. 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0021-04.png>)


## **Blue** 

Oxford Dynamic EQ 

## **Black** 

Standard dynamic EQ 

## **6.3 Dynamic Transfer Function** 

_Go to contents_ 

21 

_www.sonnox.com_ 

_6 TECH NOTES_ 

_6.3 Dynamic Transfer Function_ 

## **6.3.1 Downwards Compression** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0022-03.png>)


## **Settings** 

Trigger **Above** 

Target Gain **<** Offset Gain 

_Go to contents_ 

22 

_www.sonnox.com_ 

_6 TECH NOTES_ 

_6.3 Dynamic Transfer Function_ 

## **6.3.2 Upwards Expansion** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0023-03.png>)


## **Settings** 

Trigger **Above** Target Gain **>** Offset Gain 

_Go to contents_ 

23 

_www.sonnox.com_ 

_6 TECH NOTES_ 

_6.3 Dynamic Transfer Function_ 

## **6.3.3 Upwards Compression** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0024-03.png>)


## **Settings** 

Trigger **Below** Target Gain **>** Offset Gain 

## **6.3.4 Downwards Expansion** 

## **Settings** 

Trigger **Below** Target Gain **<** Offset Gain 

_Go to contents_ 

24 

_www.sonnox.com_ 

_6 TECH NOTES_ 

_6.3 Dynamic Transfer Function_ 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0025-02.png>)


_Go to contents_ 

25 

_www.sonnox.com_ 

_7 PRESET MANAGER TOOLBAR_ 

## **7 Preset Manager Toolbar** 


![](<Oxford Dynamic EQ Manual_assets/Oxford_Dynamic_EQ_Manual.pdf-0026-02.png>)


Sonnox Oxford plug-ins come equipped with their own onboard Preset Manager, which is displayed at the top of the plug-in window. The reasoning behind this is to allow increased portability of your presets across all the host applications, while also providing a consistent and versatile interface. While most host platforms allow creation and loading of presets, those host-created preset files are not portable between different host applications. With the Oxford plug-ins’ Preset Manager, you can create a named preset in one host application and load it when using an alternative application. 

The Sonnox Preset Manager is fully described in a companion document — Sonnox Toolbar and Preset Manager User Guide — available for download at www.sonnox.com/docs 

_Go to contents_ 

26 

_www.sonnox.com_ 

_8 COPYRIGHT AND ACKNOWLEDGEMENTS_ 

## **8 Copyright and Acknowledgements** 

Trademarks and content copyright © 2007-present Sonnox® Ltd. All rights reserved. 

Sonnox® and the five dots logo are registered trademarks of Sonnox Ltd. 

This product is manufactured and supplied by Sonnox Ltd. This product is protected by one or more European and/or US patents. 

DIGIDESIGN, AVID and PRO TOOLS are trademarks or registered trademarks of Avid Technology Inc. 

VST is a trademark of Steinberg AG. 

All other product and Company names are trademarks or registered trademarks of their respective holders. 

_Go to contents_ 

27 

_www.sonnox.com_ 

