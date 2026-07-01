---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Oxford Inflator Manual.pdf
converted_at: 2026-06-03T09:38:51Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 3624
---

## **Contents** 

|**1**|**Introduction**|**Introduction**|||**3**|
|---|---|---|---|---|---|
|**2**|**Operation**||||**5**|
||2.1|Input Clipping . . . . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . .|5|
||2.2|Direct and Band Splitting Modes . . . . . . . . . . . . . . . . . . . . . .|||6|
||2.3|Basic Loudness Enhancement|Procedure . . . . . . . . . . . . . . . . .||7|
||2.4|Metering and Overload Indication<br>. . . . . . . . . . . . . . . . . . . . .|||8|
||2.5|Curve Modifcation . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . .|9|
||2.6|Mixing with the Oxford Infator||. . . . . . . . . . . . . . . . . . . . . . .|10|
||2.7|Distortion Generation<br>. . . .|.|. . . . . . . . . . . . . . . . . . . . . . .|11|
|**3**|**Description of Controls**||||**12**|
||3.1|Input Section . . . . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . .|12|
||3.2|Efect Section . . . . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . .|13|
||3.3|Output Section . . . . . . . .|.|. . . . . . . . . . . . . . . . . . . . . . .|14|
|||3.3.1<br>Sonnox Menu Button|.|. . . . . . . . . . . . . . . . . . . . . . .|14|
|**4**|**Specifcations**||||**15**|
||4.1|Pro Tools | HDX – Instances per||chip . . . . . . . . . . . . . . . . . . . .|15|
|**5**|**Preset Manager Toolbar**||||**15**|
|**6**|**Copyright and Acknowledgements**||||**16**|



_1 INTRODUCTION_ 

## **1 Introduction** 


![](<Oxford Inflator Manual_assets/Oxford_Inflator_Manual.pdf-0003-02.png>)


The Sonnox Oxford Inflator plug-in is designed to address the current preference to produce the maximum apparent loudness from popular music mixes. Many 

processes are already in use, which are variously reliant on compression and limiting to produce maximum modulation and try to give an impression of excitement to the sound of the programme. The Inflator plug-in goes further than these methods and can increase the loudness of almost any programme material, regardless of the levels of prior compression or remaining dynamic range. It will even make full level white noise sound louder! The Inflator plug-in can also be used to create much of the warmth, character and dynamic excitement of analogue systems within the digital domain. 

_Go to contents_ 

3 

_www.sonnox.com_ 

_1 INTRODUCTION_ 

The Inflator process functions by changing the relative probability of samples in the programme material such that there is a greater probability of larger values than the original signal. The Inflator does not employ signal compression, so there is no ‘pumping’, dynamic level change, loss of presence or flattening of percussive attacks. The full dynamic information of the music content is largely preserved despite the increase in average modulation density. 

In addition to loudness enhancement, the Inflator can create a harmonic profile in the signal spectrum that not only increases the apparent dynamic impact of instruments and performances, but also provides ’warmth’ to the programme, reminiscent of good valve systems. When used in this way, the Inflator even has the ability of good valve systems to produce great sounding programme when significantly overdriven, and can therefore be used as an artistic enhancement tool on single performances within a mix. 

_Go to contents_ 

4 

_www.sonnox.com_ 

_2 OPERATION_ 

## **2 Operation** 

## **2.1 Input Clipping** 


![](<Oxford Inflator Manual_assets/Oxford_Inflator_Manual.pdf-0005-03.png>)


The Inflator process develops internal signal levels that are notionally greater than digital maximum. For instance, with the **EFFECT** level at maximum and the **Clip 0dB** off, signal peaks above notional digital maximum can be accommodated, and much of their harmonic information can be included in the output signal, even though the peak output level will not rise above digital maximum. The presence of this extra signal range is displayed on the upper sections of the **INPUT** level meter, and represents a range of up to +6dBr of useable overdrive before hard clipping occurs. 

The **CLIP 0dB** function suppresses this extra range and restricts the Inflator process to the normal digital maximum range. Therefore, you will note that, with **CLIP 0dB** selected, the input level meter will not rise above 0dB, however much input gain is employed. Because the potential applications of this process are so varied, you are encouraged to experiment with **CLIP 0dB** on and off, to obtain the best results depending on your intentions. Here are some general guidelines: 

Generally it is better to start by selecting **CLIP 0dB** on (the default) for most loudness enhancement purposes including direct mode (non-band split) since the control of peak levels, settings and sound character is more readily achieved when a maximum reference level is imposed on signals before the Inflator process. 

In certain cases better results may be obtained by de-selecting any input limiting. In particular, the extra useable range can then be used to accommodate short-term overshoot sounds produced by compression functions, where they are generated to enhance attack and presence. Since these peaks are mostly short duration, they can 

_Go to contents_ 

5 

_www.sonnox.com_ 

_2.2 Direct and Band Splitting Modes_ 

_2 OPERATION_ 

often be accommodated effectively in the overdrive ranges without excessive reduction of sound quality or loss of average modulation. Please note that in this case it is important to ensure that the peaks from any prior compression are not clipped between plug-ins, by making sure that the output signal from the compressor does not quite hit peak levels _**before**_ applying it to the Inflator plug-in. 

When using **BAND SPLIT** modes for loudness enhancement, using the Inflator with **CLIP 0dB** _**off**_ may produce a reduction in unwanted intermodulation side effects when pushing for absolute maximum loudness, regardless of possible output clipping etc. 

When using direct mode (without band splitting) for distortion generation, the results will be quite different with or without input clipping, and may produce useful artistic effects in either circumstance. The Inflator is able to soften clips that occur, either because of the **CLIP 0dB** setting, or even those that happen before its own processing in prior plug-ins. Therefore overdriving the Inflator with the **CLIP 0dB** function both on and off, or even applying the Inflator to the output of other plug-ins driven into overdrive, can produce a vast range of artistic effects. To explore the full range of possibilities, the importance of experimentation cannot be overstressed. 

## **2.2 Direct and Band Splitting Modes** 

The Inflator application can run in either direct or band splitting modes. In normal operation, the complete frequency range of the programme material is processed simultaneously. This is usually the best way to run the process under most conditions. One significant advantage of using this mode is that the output relative peak level will not get larger than peak level, however much Effect is applied. Therefore more overall enhancement is possible before clipping the output, and louder more powerful results are possible. Also, when used for distortion generation, the relative phase of the distortion harmonics are better preserved when band splitting is not used, so accurate clip rounding is possible, thus producing a much more pleasing effect. 

_Go to contents_ 

6 

_www.sonnox.com_ 

_2 OPERATION_ 

_2.3 Basic Loudness Enhancement Procedure_ 


![](<Oxford Inflator Manual_assets/Oxford_Inflator_Manual.pdf-0007-02.png>)


The **BAND SPLIT** function is offered as an additional mode that may be useful under some specific conditions. When band splitting is selected, the processing is split into three frequency bands to avoid intermodulation distortion between parts of the programme signal spectrum. This mode is occasionally advantageous when going for maximum loudness enhancement where there is a significant predominance of specific frequency ranges in the programme content. However it should be noted that, depending on programme and settings, operation in this mode produces output levels that are beyond the relative input peak level. This means that the signal is more likely to clip at the output, which may produce an increased harshness to the sound. If this becomes obtrusive, reducing the input or output levels to avoid clipping will obviously somewhat negate the purpose of the exercise! 

## **2.3 Basic Loudness Enhancement Procedure** 

For basic loudness enhancement, the procedure is to get the programme up to maximum normalised level at the input (0dB) in order to fully benefit from the Inflator process, apply the Inflator processing to get the desired effect, and then adjust the output level to maintain desired maximum modulation. 

Start with the **CLIP 0dB** function selected to limit the range of the Inflator to normal digital maximum. 

Using the **INPUT** level control and input meter, set the level such that the red **0 db** over indicator flashes occasionally to indicate the presence of max peak sample values. 

Set the **OUTPUT** level control to maximum initially, so that the input and output meters have similar readings when the music is played. 

_Go to contents_ 

7 

_www.sonnox.com_ 

_2.4 Metering and Overload Indication_ 

_2 OPERATION_ 

Set the **CURVE** control initially to its mid position (default) and deselect the **BAND SPLIT** button. 

Start with the **EFFECT** level control at 100% to obtain the maximum increase in perceived volume without extra peak output level. 

The object of the exercise is to get the input level as high as possible without excessive distortion or deterioration in the sound. The type of programme material and taste will determine the extent of the enhancement that can be achieved. If it is found that the programme material is not significantly degraded at normal peak input levels, further gain in loudness may be achieved by de-selecting the **CLIP 0dB** button and pushing the input level into the Inflator overload region. 

## _**to maximum position (100%).**_ 

In general the best results are most likely to be obtained by operating the Inflator **EFFECT** level at maximum, and adjusting the **INPUT** level and **CURVE** control to produce the best sonic compromise. 

Further user modifications to the Inflator process can be invoked to gain either greater loudness or different characteristics in sonic detail, as described below. 

## **2.4 Metering and Overload Indication** 

For most workstation applications, the metering overload warning indicator is intended to correspond to digital maximum modulation. Different software host applications (and different versions of those applications) may present varying interpretations of what this actually represents numerically. Because the Inflator requires a very accurate and independent internal representation of numerical maximum, differences in overload indication may arise between the Inflator and host applications. However since the Inflator overload indication is set to respond to full level samples very precisely, it will produce legal programme if overloads are not being recorded on the plug-in GUI, even if overload indications are being triggered within the host mixer application. 

Further user modifications to the Inflator process can be invoked to either gain greater loudness or different characteristics in sonic detail, as described below. 

_Go to contents_ 

8 

_www.sonnox.com_ 

_2.5_ 

_2 OPERATION_ 

## **2.5** 

The **CURVE** modification control subtly affects the characteristic of the Inflator process to affect both the perceived loudness and tonal character of the signal. 

With the **CURVE** control set at its minimum position (-50), the Inflator produces the most subtle changes to the sound. Overall loudness enhancement is minimal but significant harmonic content is added to produce a richer overall sonic character. When applied to composite mixes, the predominantly loud parts of the mix will apparently be accentuated over the background and reverberant parts of the programme, producing the effect of dynamic expansion (without a time constant). 

This setting is particularly useful when treating drums and percussion instruments, when the impression of dynamic presence needs to be enhanced, or the contribution to the mix needs to be ‘tightened up’. This kind of setting is also useful when used on single instruments (such as acoustic guitars) where a softening of percussive aspects or ‘highs’ is needed without loss of apparent dynamic range. 

Settings of the curve control between -50 and around zero have varying degrees of this behaviour and style of overall impression, but with increasing ‘fatness’ and volume as the curve control is advanced. 

The **CURVE** control at its mid position (default zero) produces a special behaviour, which in many respects may give the best results in most situations. The overall loudness of the signal is considerably enhanced whilst retaining good dynamic balance between loud and soft portions of the programme, with a minimum of intermodulation effect. The sonic character has a much enhanced warmth and harmonic detail, adding presence and texture to instruments, especially in the low frequency register. The highs and peaks in the programme are softened in character without loss of apparent presence, attack or ‘bite’. Occasional peak programme overloads are softened and become less intrusive and can therefore be tolerated more readily. With the **CURVE** control in this position, the Inflator produces a gentle and forgiving behaviour, which has many aspects in common with the character of good valve amplification systems, including a natural tolerance to overload conditions. For example, when used in direct mode (band splitting de-selected) with **CLIP 0dB** selected and the **EFFECT** level set to 100%, even clipped programme 

_Go to contents_ 

9 

_www.sonnox.com_ 

_2.6 Mixing with the Oxford Inflator_ 

_2 OPERATION_ 

signals can be rendered musical in nature. This can be used to produce artistic distortion effects on single instruments within a mix or produce dynamic ‘breaking up’ effects, much like that possible with valve amplifiers. Or you may just want to obtain an overall valve-like character and warmth to the sound. 

At positions between 0 and +50 the **CURVE** control provides increasing ‘fatness’ and volume enhancement at the partial expense of dynamic precision, producing the loudest and most exciting effects at +50. In this position the sound becomes most powerful with a harmonic profile reminiscent of systems under great stress and running to their very limits. The music will take on an ‘in your face’ quality, creating the maximum excitement yet fine detail and subtleties within the mix will be retained. Despite rendering the signal significantly louder, the impression of considerable dynamic range is retained even though the output peak level range is largely unchanged. The low level and background parts of the mix will become enhanced and more audible and extreme LF contributions from instruments such as basses will stand out more readily on smaller reproduction systems. Programme treated with this process will produce louder sounds on all reproduction equipment, and in particular it will produce unsuspected volume and power from small domestic and portable systems. 

## **2.6** 

The Inflator can bring added benefit to the mixing process if it is inserted on the main output buss throughout the mixing session. In this case it is possible to use the valve-like harmonic characteristics and the extra overload area to greater advantage, because these form part of the sound of the mix as it is built up. In some respects this process is reminiscent of analogue mixing where line-up operating levels may be breached by transients without actual signal clipping, and the sonic character of the signal chain is to some degree dependent on balance and instrument contribution levels. 

It is suggested that, in this case, the best initial settings are with the Inflator set to direct mode (ie. not band split), with the **CURVE** control set to the mid position (0) and with **CLIP 0dB** de-selected. The input gain should be set somewhat above unity (+6dB) to allow the mixer to operate without clipping overshoots prior to the Inflator, 

_Go to contents_ 

10 

_www.sonnox.com_ 

_2.7 Distortion Generation_ 

_2 OPERATION_ 

and the output should be set to max (0db) to provide full output modulation. These settings will establish a virtual operating level at –6dBr within the mixing environment, with a possible overload area provided by the Inflator process for short-term level peaks to be accommodated without clipping. The Inflator input and output meters can then be used as main output buss level reference monitors during the mix session. 

## **2.7 Distortion Generation** 

For distortion generation, it is best to proceed initially with the **EFFECT** level set to maximum so that the nature of any distortion can be assessed. The idea is to increase the input level with the Inflator fully operational, and the **OUTPUT** control reduced somewhat to avoid output clipping, whilst listening to the results with various degrees of deliberate and significant signal overdrive. The **CURVE** control and **CLIP 0dB** selector will both affect the sound of the results, depending on the programme material being processed. However, the best results are most likely to be obtained with the **CURVE** control set to its mid (0) position, as this produces the least higher order harmonic levels and most resembles the dynamics behaviour of valve systems. In general, it is best to avoid band-splitting mode if aiming for natural warmth and valve overdrive sounds. Input clipping will dramatically change the nature of the distortion in overdrive situations and you are encouraged to experiment with the **CLIP 0dB** selector both on and off, and changing the order of plug-ins in the signal path. 

_Go to contents_ 

11 

_www.sonnox.com_ 

_3 DESCRIPTION OF CONTROLS_ 

## **3 Description of Controls** 


![](<Oxford Inflator Manual_assets/Oxford_Inflator_Manual.pdf-0012-02.png>)


## **3.1 Input Section** 

## **INPUT fader** 

sets the input level to the Inflator process. For full level input signals, maximum peak input is obtained with the fader set to 0dB. Further gain beyond is 

provided to allow lower level programme to be boosted to full modulation, and allows the Inflator to be deliberately overdriven to produce distortion effects. 

## **INPUT value** 

shows the value in dB of the parameter set by the input fader. The value can be modified by clicking in the window. 

_Go to contents_ 

12 

_www.sonnox.com_ 

_3.2 3 DESCRIPTION OF CONTROLS_ 

## **INPUT meter** 

the input meter displays the input drive levels. With the **CLIP 0dB** button (in the Effect section) de-selected, the meter displays the level of overdrive applied to the Inflator process. The meter will be mono or stereo depending on the material content. 

## **3.2** 

## **EFFECT fader** 

sets the amount of the overall Inflator effect that is applied to the programme, from 0% to 100%. 

## **EFFECT value** 

shows the value in dB of the parameter set by the **EFFECT** fader. The value can be modified by clicking in the window. 

## **EFFECT meter** 

indicates the degree of average signal modification in real time, depending on programme type and Inflator settings. 

## **CURVE fader** 

## **CURVE value** 

shows the value in dB of the parameter set by the **CURVE** fader. The value can be edited by clicking in the window. 

## **CLIP 0dB** 

when this button is selected, internal processing levels are restricted to the equivalent of normal digital maximum. When de-selected, internal processing may develop and process signals beyond the equivalent of digital maximum. 

## **BAND SPLIT** 

selects processing on the direct full band signal or invokes a band splitting function that processes the signal separately in the LF, MF and HF spectral regions. 

- **IN** 

_Go to contents_ 

13 

_www.sonnox.com_ 

_3.3 Output Section_ 

_3 DESCRIPTION OF CONTROLS_ 

## **3.3 Output Section** 

## **OUTPUT fader** 

sets the output level to allow adjustment of the signal level after processing. 

## **OUTPUT value** 

hows the value in dB of the parameter set by the output fader. The value can be modified by clicking in the window. 

## **OUTPUT meter** 

the output meter indicates 0.5 dB per segment for the top 10dB of dynamic range, and a smaller scale thereafter. The meter will be mono or stereo depending on programme content. 

## **3.3.1 Sonnox Menu Button** 

Clicking the Sonnox button produces a drop-down options menu (see right). 

## **Clip Lights Hold Times** 

## **Enable Sonnox Toolbar** 

displays or hides the Preset Manager Toolbar. 

## **Enable Tooltips** 

enables or disables pop-over Tooltips. 

## **About** 

displays the date, version and build number of the plug-in. 

_Go to contents_ 

14 

_www.sonnox.com_ 

_5 PRESET MANAGER TOOLBAR_ 

## **4** 

## **4.1 Pro Tools | HDX – Instances per chip** 

|Variant||44.1/48 kHz|88.2/96 kHz|176.4/192 kHz|
|---|---|---|---|---|
|Band Split|Mono|42|20|9|
||Stereo|21|10|4|
|Direct|Mono|84|48|22|
||Stereo|49|24|11|



## **5 Preset Manager Toolbar** 


![](<Oxford Inflator Manual_assets/Oxford_Inflator_Manual.pdf-0015-05.png>)


Sonnox Oxford plug-ins come equipped with their own onboard Preset Manager, which is displayed at the top of the plug-in window. The reasoning behind this is to allow increased portability of your presets across all the host applications, while also providing a consistent and versatile interface. While most host platforms allow creation and loading of presets, those host-created preset files are not portable between different host applications. With the Oxford plug-ins’ Preset Manager, you can create a named preset in one host application and load it when using an alternative application. 

The Sonnox Preset Manager is fully described in a companion document — Sonnox Toolbar and Preset Manager User Guide — available for download at www.sonnox.com/docs 

_Go to contents_ 

15 

_www.sonnox.com_ 

_6 COPYRIGHT AND ACKNOWLEDGEMENTS_ 

## **6 Copyright and Acknowledgements** 

Trademarks and content copyright © 2007-present Sonnox® Ltd. All rights reserved. 

Sonnox® and the five dots logo are registered trademarks of Sonnox Ltd. 

This product is manufactured and supplied by Sonnox Ltd. This product is protected by one or more European and/or US patents. 

DIGIDESIGN, AVID and PRO TOOLS are trademarks or registered trademarks of Avid Technology Inc. 

VST is a trademark of Steinberg AG. 

All other product and Company names are trademarks or registered trademarks of their respective holders. 

_Go to contents_ 

16 

_www.sonnox.com_ 

