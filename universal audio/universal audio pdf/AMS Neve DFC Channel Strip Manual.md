---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Ошибки/2026-06-03_121809_AMS Neve DFC Channel Strip Manual/AMS Neve DFC Channel Strip Manual.pdf
converted_at: 2026-06-03T12:26:39Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 5227
---


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0001-00.png>)


## **AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual** 

UAD2 AMS NEVE DFC Channel Strip Plugin 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0001-03.png>)


The AMS Neve DFC (Digital Film Console) is the standard among the world’s premier motion picture facilities at the cutting edge of content creation and is designed specifically for multiformat film dubbing and TV post production at the highest level. 

The AMS Neve DFC (Digital Film Console) 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0001-06.png>)


AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0002-00.png>)


At the heart of the DFC console is the world’s most powerful DSP engine, capable of delivering the legendary Neve sound across 1000 audio signal paths at 96kHz. 

These DSP algorithms are the favourite tools of the world’s most renowned re-recording mixers delivering OSCAR winning film sound tracks. 

This plugin brings DAW users unprecedented access to those exact same DSP algorithms that have been used on thousands of feature films and TV dramas over the last 20 years. 

DFC uses floating-point DSP processors as does the UAD2 platform and so the DSP is mapped exactly, instruction for instruction even down to the interpolation processing used for co-efficient transition. 

The plugin was developed at AMS Neve Headquarters in England by the DFC software development team; David Critchley, Stewart Wonnacott and David Hawkins (AKA Jack). 

This plugin provides a fully featured and comprehensive channel strip, which includes all of the channel strip DSP elements available on the DFC console. The channel strip plugin DSP comprises: 

- 4 Bands of fully parametric EQ 

- 2 Bands of 4[th] order Filtering 

- Compressor 

- Limiter 

- Expander 

- Gate 

- Dynamics EQ (Sidechain Equalisation) 

- Input and Output gain 

- Phase and width control 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **The plugin comprises two main elements** 

1. A DFC ‘Chan-Quad Panel’ comprising 16 assignable rotary controls with alpha-numeric displays, 4 process ‘On’ buttons and 5 Process Selection buttons. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0003-02.png>)


2. A DFC ‘TFT Meter Panel’ comprising Interactive Graphs for EQ and Dynamics, Interactive Process Order display, Interactive Process In/Out display, Bypass and Output Meter. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0003-04.png>)


AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Chan-Quad Panel** 

In total the DFC channel strip plugin has 74 controls, these are accessed on the Chan-Quad panel in 5 pages of Process Selection. 

Each Control comprises two Alpha-numeric displays (known as ‘Alphas’ on DFC) one for Parameter Name and the other Parameter Value, and one rotary control (known as a ‘Logicator’ on DFC) 

Pressing one of the 5 Process Selection Buttons assigns the processes to the controls and to the ‘On’ buttons. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0004-04.png>)


Processes are assigned in horizontal ‘Strips’ comprising Process Name, 4 Controls and an ‘On’ button. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0004-06.png>)



![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0004-07.png>)


**----- Start of picture text -----**<br>
Process Name<br>Control 1<br>Control 2<br>Control 3<br>Control 4<br>                         Process On<br>**----- End of picture text -----**<br>


Holding the command key for mac or ctrl key for the PC and clicking on the Process selection buttons will default the settings of all the controls on that page. Doing the same with the ‘On’ buttons will default the settings of the individual bands. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Process Assignments Table** 

EQ (4 Band Equaliser) 

||Strip1|Strip2|Strip3|Strip4|
|---|---|---|---|---|
|Control 1|EQBand 1 Frequency|EQBand 2 Frequency|EQBand 3 Frequency|EQBand 4 Frequency|
|Control 2|EQBand 1 Level|EQBand 2 Level|EQBand 3 Level|EQBand 4 Level|
|Control 3|EQBand 1 Shape|EQBand 2 Shape|EQBand 3 Shape|EQBand 4 Shape|
|Control 4|EQBand 1 ‘Q’|EQBand 2 ‘Q’|EQBand 3 ‘Q’|EQBand 4 ‘Q’|
|On Button|EQBand 1 On/Off|EQBand 2 On/Off|EQBand 3 On/Off|EQBand 4 On/Off|



## FLTR/ DYN-EQ (2 Band Filter & Dynamic EQ) 

||Strip1|Strip2|Strip3|Strip4|
|---|---|---|---|---|
|Control 1|Filter Band 1 Freq|Filter Band 2 Freq|Dyn EQFrequency|Side Chain Listen|
|Control 2|Filter Band 1 Order|Filter Band 2 Order|Dyn EQLevel||
|Control 3|Filter Band 1 Shape|Filter Band 2 Shape|Dyn EQShape||
|Control 4|||Dyn EQ‘Q’||
|On Button|Filter Band 1 On/Off|Filter Band 2 On/Off|Dyn EQOn/Off||



## COMP/ LIM (Compressor and Limiter) 

||Strip1|Strip2|Strip3|Strip4|
|---|---|---|---|---|
|Control 1|Compressor Threshold|Compressor Knee|Limiter Threshold|Limiter Knee|
|Control 2|Compressor Ratio|CompMakeupGain||Limiter MakeupGain|
|Control 3|Compress Attack Time|CompMakeupAuto|Limiter Attack Time|Limiter MakeupAuto|
|Control 4|Compress DecayTime||Limiter DecayTime||
|On Button|Compressor On/Off||Limiter On/Off||



## EXP/ GATE (Expander and Gate) 

||Strip1|Strip2|Strip3|Strip4|
|---|---|---|---|---|
|Control 1|Expander Threshold|Expander Knee|Gate Threshold|Gate Hysteresis|
|Control 2|Expander Ratio|Expander Depth||Gate Depth|
|Control 3|Expander Attack Time||Gate Attack Time||
|Control 4|Expander DecayTime||Gate DecayTime||
|On Button|Expander On/Off||Gate On/Off||



## I/O (Input and Output) 

||Strip1|Strip2|Strip3|Strip4|
|---|---|---|---|---|
|Control 1|Input Level Trim||Output Level Trim||
|Control 2|Input Phase||||
|Control 3|Stereo Width||||
|Control 4|||||
|On Button|||||



AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **TFT Meter Panel** 

The TFT Meter Panel comprises several key sections. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0006-02.png>)


## **1. Interactive EQ & Filter graph** 

Currently selected node 

The response of the EQs and Filters are displayed in graphical form on this graph, the individual bands are displayed in colour coded lines, with a key at the bottom to confirm the colours for the different 

bands. All the bands are displayed even if they are switched off, the collective response of the bands that are switched on is displayed in the shaded red areas. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0006-07.png>)


Key for coloured bands 

6 nodes are displayed on the graph indicating the selected frequency and level of the 4 bands of EQ and 2 Bands of filter. A left mouse click on a node switches that band on, a right mouse click switches the band off. 

Moving a node up and down changes the ‘Level’ control of the associated band (or ‘Slope’ control for a filter shape). Moving a node left and right changes the ‘Frequency’ control of the associated band. For any BELL or NOTCH shaped band the ‘Q’ control of the last node selected will be altered when clicking away from the node and dragging the mouse up and down, the Q control is also controlled from the mouse wheel. 

The EQ and Filter ‘Shape’ controls are only accessible from the Chan-Quad panel; however, the ChanQuad panel is switched to the EQ or Filter page when any node is selected and the controls for that current band are highlighted. 

A left mouse click on a band in the coloured key area will also switch that band on, a right mouse click switches the band off. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

Currently selected node 

## **2. Interactive Dynamics Graph** 

The response of the Compressor, Limiter, Expander and Gate 

are displayed in graphical form on this graph. 

4 nodes are displayed on the Dynamics graph, one for each of Compressor, Limiter, Expander and Gate, indicating the threshold of those processes. 

A ‘left click’ on a node switches that process on, a right click switches the process off. 

Clicking on the nodes also assigns the relevant page to the ChanQuad panel and highlights the controls associated with the selected node. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0007-07.png>)


Moving the node up and down modifies the threshold. 

Key for process 

For the Compressor, Limiter and Expander the ‘Knee’ control of the currently selected node will be altered when clicking away from the node and dragging the mouse up and down, or operating the mouse wheel. 

The Dynamics displays also features a combined gain reduction meter for Compressor and Limiter and gain expansion meter for the Expander and Gate. 

A left mouse click on a process in the coloured key area will switch that process on, a right mouse click switches the process off. 

## **3. Process Order display** 

The 7 processes are displayed in the order the signal will be processed through the channel strip. Clicking and dragging on the processes allows the order to be changed. The Dynamic EQ (Side Chain EQ) can be dragged to feed any dynamics process in the chain. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0007-15.png>)


## **4. Process In/ Out** 

The In/ Out state of the 7 processes is shown in the Process In/ Out 

display, in the case of the Filter and EQ a ‘Half Lit’ display is shown if only some of the Bands are turned on. Clicking on the elements of the display will switch the In/ Out states. For the EQ and Filter a left 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0007-19.png>)


mouse click with switch the currently active bands only, a right mouse click will switch all the bands. A red LSTN indication appears over the EQ4 and D-EQ as a reminder if either of those processes has a Listen control set. 

The listen control is operated from the Chan-Quad panel. 

N.B. For the EQ and Filters In/ Out the active bands are respected, so that whatever bands are ‘In’ when the In/ Out button is pressed only those bands will be switched back on with the next press of the button. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **5. Output meter** 

The output meter level is displayed as a peak meter in dBFS, with the same ballistic meter response found on the DFC console. Signals down to -80 dBFS are represented. 

For the mono instance a single meter bar is displayed. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0008-03.png>)


## **6. Bypass** 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0008-05.png>)


A Bypass control is also included, when activated all controls can still be accessed although the plugin is not processing the audio. The Bypass indicator will light and the plugin controls will become dim. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Signal Processing** 

## **EQ** 

EQ, short for ‘Equalisation’ also known as ‘Tone Control’ is the process of reducing or increasing the level of regions of the signal in the frequency spectrum. With DFC the frequency selection for all 4 bands is from 12Hz to 20kHz, allowing each band to action anywhere in the audio frequency spectrum. 

The 4 Bands of EQ are all ‘shape’ selectable. 

There are 6 different shaped responses available, the shape is selected on the third control in each EQ strip when assigned to the Chan-Quad Panel. 

|Shape|Filter Type|Controls|Range|
|---|---|---|---|
||High Pass Filter|Frequency (Freq)<br>Order (dB8v)<br>Band On (On button)|12Hz – 20kHz<br>Flat, 6dB/oct, 12dB/oct<br>On/Off|
||High Pass Shelving filter|Frequency (Freq)<br>Level (Levl)<br>Band On (On button)|12Hz – 20kHz<br>-24dB – +24dB<br>On/Off|
||Bell|Frequency (Freq)<br>Level (Levl)<br>Q (Q)<br>Band On (On button)|12Hz – 20kHz<br>-24dB – +24dB<br>0.1Q – 10Q<br>On/Off|
||Low Pass Shelving Filter|Frequency (Freq)<br>Level (Levl)<br>Band On (On button)|12Hz – 20kHz<br>-24dB – +24dB<br>On/Off|
||Low Pass Filter|Frequency (Freq)<br>Order (dB8v)<br>Band On (On button)|12Hz – 20kHz<br>Flat, 6dB/oct, 12dB/oct<br>On/Off|
||Notch|Frequency (Freq)<br>Q (Q)<br>Inverted Listen (Lstn) *<br>Band On (On button)|12Hz – 20kHz<br>On/Off<br>NORM/ LSTN<br>On/Off|



*Inverted Listen (Lstn) routes the part of the signal that the notch is removing to the output of the EQ module, allowing the user to ‘hunt’ for the signal they wish to filter out. This is not an automated control as it is only a monitoring function, once the signal is identified the Listen control should be returned to ‘NORM’. A ‘LSTN’ display is shown above the EQ in/out display when any band of EQ is set to listen as a reminder. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## Controlling the EQ parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0010-01.png>)


To access the EQ controls, select the EQ Process Selection button, the four strips of the Chan-Quad are then assigned to the EQ Controls and the ‘On’ buttons assigned to the EQ bands In/Out. 

To turn all 4 EQ bands On and Off together click on the EQ4 Process In/Out control with the **Right Mouse Button.** Clicking with the left mouse button will turn On and Off just those bands that are currently active. 

The Frequency and Level of the EQ Bands can be altered by clicking and moving the Nodes on the interactive EQ Graph. 

For Notch and Bell shapes the ‘Q’ control is accessible by clicking away from the highlighted node and dragging the mouse up and down, the mouse wheel also alters the ‘Q’ control. 

The bands can be switched on and off with Left and Right mouse clicks on the nodes and colour key. 

Clicking on an EQ node also assigned the EQ controls to the Chan-Quad panel and highlights the controls of that band. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Filters** 

The 2 Filter Bands are shape selectable, they are 4[th] order filters (selectable as Flat, 6dB, 12dB, 18dB and 24dB/octave). Note - the Filter shapes available in the EQ processes are only 2[nd] order filters. 

There are 2 different shaped responses available, Low Pass Filter and High Pass Filter, the shape is selected on the third control in each Filter strip when assigned to the Chan-Quad Panel. 

|Shape|Filter Type|Controls|Range|
|---|---|---|---|
||High Pass Filter|Frequency (Freq)<br>Order (dB8v)<br>Band On(On button)|12Hz – 20kHz<br>Flat, 6dB, 12dB, 18dB & 24dB/oct<br>On/Off|
||Low Pass Filter|Frequency (Freq)<br>Order (dB8v)<br>Band On(On button)|12Hz – 20kHz<br>Flat, 6dB, 12dB, 18dB & 24dB/oct<br>On/Off|



Controlling the Filter parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0011-05.png>)


To access the Filter controls, select the Filter/ Dyn-EQ Process Selection button, the first two strips of the Chan-Quad are then assigned to the Filter Controls. The first two ‘On’ buttons are assigned to the Filter bands In/Out. 

To turn both Filter bands On and Off together click on the FLT2 Process In/Out control with the **Right Mouse Button.** Clicking with the left mouse button will turn On and Off just the bands that are currently active. 

The Frequency and Slope of the Filter Bands can be altered by clicking and moving the Nodes on the interactive Graph. 

The Filter bands can be switched on and off with Left and Right mouse clicks on the nodes and colour key. 

Clicking on a Filter node also assigns the Filter controls to the Chan-Quad panel and highlights the controls of that band. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Dynamics EQ** 

The Dynamics EQ (or Side Chain EQ) is a single band of Equalisation, applied to the Side Chain trigger signal of the Dynamics Process it is associated with. In the ‘Process Order’ section you can drag the DynEQ block as required to use the Dynamics EQ on any of the Dynamics Processes. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0012-02.png>)


Dynamics EQ is used to cut or boost a region of frequencies in the Side-Chain triggering signal. This will in turn alter the behaviour of the dynamics process it is associated with, causing it to be more or less responsive in that area of the frequency spectrum. 

Dynamics without Dynamic EQ 

Dynamics with Dynamic EQ 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0012-06.png>)


**----- Start of picture text -----**<br>
Dynamics  Dynamic  Dynamics<br>Controller  EQ  Controller<br>Gain Control  Gain Control<br>Signal  Signal<br>Gain  Gain<br>Input  Output  Input  Output<br>Multiplier  Multiplier<br>**----- End of picture text -----**<br>


There are three different shaped responses available for this single band of Dynamic EQ, Low Pass Shelf, Bell and High Pass Shelf, the shape is selected on the 3[rd] control of the 3[rd] strip when assigned to the Chan-Quad Panel. 

|Shape|Filter Type|Controls|Range|
|---|---|---|---|
||High Pass Shelf|Frequency (Freq)<br>Order (dB8v)<br>Dyn EQ On (On button)|12Hz – 20kHz<br>Flat, 6dB/oct, 12dB/oct<br>On/Off|
||Bell|Frequency (Freq)<br>Level (Levl)<br>Q (Q)<br>Dyn EQOn(On button)|12Hz – 20kHz<br>-24dB – +24dB<br>0.1Q – 10Q<br>On/Off|
||Low Pass Shelf|Frequency (Freq)<br>Order (dB8v)<br>Dyn EQ On (On button)|12Hz – 20kHz<br>Flat, 6dB/oct, 12dB/oct<br>On/Off|



AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

There is also a **Listen** Control, when selected the Dynamic EQ’d signal is routed to the output of the module, allowing the Side-Chain trigger signal to be monitored while adjusting the parameters. The Listen Control acts to **bypass** the Dynamics module to enable the EQ settings to be auditioned without that Dynamics module acting on the signal, leaving the Listen set could cause confusion and so there is a Red listen display set in the Process In/Out display area to warn that the listen is set. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0013-01.png>)


**----- Start of picture text -----**<br>
Dynamics Process<br>Dynamic  Dynamics<br>EQ  Controller<br>Listen<br>Gain Control  Switch<br>Signal<br>Gain  Output<br>Input<br>Multiplier<br>**----- End of picture text -----**<br>


Controlling the Dynamics EQ parameters 

Drag the DynEQ process to be associated with any of the Dynamics Processes as required. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0013-04.png>)


To access the Dynamics EQ controls, select the Filter/ Dyn-EQ Process Selection button, the 3[rd] and 4[th] strips of the Chan-Quad are then assigned to the Dynamics EQ Controls. The 3[rd] ‘On’ button is assigned to the Dynamics EQ In/ Out control. 

The Dynamics EQ can also be turned on and off from the Process In/Out section 

The Red LSTN display is a reminder that the Dynamics EQ Listen is engaged. 

When clicking on or around any of the Dynamics EQ controls the EQ graph is re-tasked to display the response of the Dynamics EQ in the place of the EQ and Filter responses. The Frequency, Level and Q can be controlled from the graph. 

This display will continue showing the Dynamics EQ response until either the EQ or Filter/ Dyn-EQ page is selected, then it will revert to displaying the response of the EQ and Filters 

With DFC one common use of the Dynamic EQ is to set a ‘Bell’ Shape EQ to exaggerate the sibilance in the Side Chain of a dialogue channel, usually 5kHz - 8kHz, to make the compressor apply more gain reduction when loud sibilance occurs and so reducing the level of the signal through the compressor. Hollywood mixers often prefer the results of DFCs compressor configured like this over the results of multi-banding as with a de-esser. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Compressor** 

A Compressor is used to reduce the dynamic range of a signal, the span between the loudest and quietest parts of the signal. 

This dynamic range reduction is achieved by automatically reducing the gain when the signal is higher in level than the current threshold setting. 

The Ratio Control sets the Ratio of the gain of Input Signal vs Output Signal, for signals above the threshold level. With the ratio at 1:1 no change will take place, with a ratio of ∞:1 the effect of ‘Limiting’ will take place, a value of 2:1 is commonly used. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0014-04.png>)


**----- Start of picture text -----**<br>
1:1 Ratio<br>Signals above the<br>2:1 Ratio<br>threshold are reduced<br>Threshold<br>∞:1 Ratio<br>Signals below the<br>threshold are not altered<br>Input Level<br>Output Level<br>**----- End of picture text -----**<br>


Setting a higher knee value (softer knee) allows the signal to pass from uncompressed to compressed more subtlety, offering a less pronounced transition. 

Hard Knee (set at minimum) Softer Knee (set at 10dB) with ratio at ∞:1 with ratio at ∞:1 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0014-07.png>)


The Attack Time Control is used to set how quickly the compressor applies the gain reduction, at its minimum (70uS) the gain reduction is applied extremely quickly with a more audible effect, at its maximum (50mS) the change in gain is more gradually applied. 

The Release Time Control sets how quickly the gain reduction is returned to zero once the signal is below the threshold level, generally this is set much longer than the Attack Time. 

**Note** – DFC allows for very short attack and decay times, in some circumstances these very short times are useful but should be used with care. For some program material (particularly with low frequencies) this extremely rapid response of the Compressor and Limiter can cause an audible distortion as the waveform is effectively being clipped. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

The compressor has the following Controls: 

|Control|Range|Function|
|---|---|---|
|Threshold (Thrs)<br>Ratio (Rtio)<br>Attack Time (Atk)<br>Release Time (Rel)<br>Knee (Knee)<br>Makeup Gain (MkGn)<br>Auto Makeup (MkUp)|-80dBFS – 0dBFS<br>1:1 – ∞:1<br>70uS – 50.0mS<br>0.0S – 5.0S<br>0.0dB – 60.0dB<br>0.0dB – +20dB<br>MAN/ AUTO|The level at which the compressor begins to act on the signal<br>The Ratio of gain of Input Signal vs Output Signal above the<br>threshold point<br>The time taken to impact the gain reduction<br>The time taken to return to zero gain reduction<br>How harshly the threshold point is applied, moving between<br>compressed and uncompressed signal<br>Adding gain back in to account for the incurred gain reduction<br>Sets the Makeup Gain automatically based on the Threshold and<br>Ratio|



The response of the compressor is displayed on the Dynamics Graph, where Threshold, Ratio and Knee are incorporated into the response curve. 

To access the Compressor Controls, select the COMP/ LIM Process Selection Button, the first two strips of the Chan-Quad are then assigned to the Compressor Controls. 

Controlling the Compressor parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0015-05.png>)


To access the Compressor controls, select the Comp/ Lim Process Selection button, the first two strips of the Chan-Quad are then assigned to the Compressor Controls. The first ‘On’ button is assigned to the Compressor In/ Out control. 

The Compressor can also be turned on and off by clicking on the CMP Process In/Out control 

The Threshold of the Compressor can be altered by clicking and moving the Node on the interactive Graph. While the compressor node is highlighted clicking and dragging the mouse elsewhere on the graph will alter the Knee control. The Mouse wheel will also alter the Knee Control. 

The Compressor can be switched on and off with Left and Right mouse clicks on the node and colour key. Clicking on the Compressor node also assigns the Compressor controls to the Chan-Quad panel and highlights those controls. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Limiter** 

The Limiter is identical to the compressor with the exception of having its ratio fixed at ∞:1. Generally, the application of a limiter is to reduce the level of a signal should it exceed a ceiling level that is imposed as a delivery requirement or such that the level would equate to digital clip when output (in the fixed-point digital domain). There are other creative uses of Limiters as well. 

The limiter has the following Controls: 

|Control|Range|Function|
|---|---|---|
|Threshold (Thrs)<br>Attack Time (Atk)<br>Release Time (Rel)<br>Knee (Knee)<br>Makeup Gain (MkGn)<br>Auto Makeup (MkUp)|-80dBFS – 0dBFS<br>70uS – 50.0mS<br>0.0S – 5.0S<br>0.0dB – 60.0dB<br>0.0dB – +20dB<br>MAN/ AUTO|The level at which the limiter begins to act on the signal<br>The time taken to impact the gain reduction<br>The time taken to return to zero gain reduction<br>How harshly the threshold point is applied, moving between<br>limited and unlimited signal<br>Adding gain back in to account for the incurred gain reduction<br>Making the Makeup Gain automatic based on the Threshold<br>setting|



**Note** – DFC allows for very short attack and decay times, in some circumstances these very short times are useful but should be used with care. For some program material (particularly with low frequencies) this extremely rapid response of the Compressor and Limiter can cause an audible distortion as the waveform is effectively being clipped. 

The response of the Limiter is displayed on the Dynamics Graph, where Threshold and Knee are incorporated into the response curve. 

Controlling the Limiter parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0016-07.png>)


To access the Limiter controls, select the Comp/ Lim Process Selection button, the 3[rd] and 4[th] strips of the Chan-Quad are then assigned to the Limiter Controls. The 3[rd] ‘On’ button is assigned to the Compressor In/ Out control. 

The Threshold of the Limiter can be altered by clicking and moving the Node on the interactive Graph. While the Limiter node is highlighted clicking and dragging the mouse elsewhere on the graph will alter the Knee control. The Mouse wheel will also alter the Knee Control. 

The Limiter can be switched on and off with Left and Right mouse clicks on the nodes and colour key. Clicking on the Limiter node also assigns the Limiter controls to the Chan-Quad panel and highlights them. 

The Limiter can also be turned on and off by clicking on the LIM Process In/Out control 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Expander** 

The expander works in the opposite way to the compressor, it reduces the gain of a signal that is _below_ the threshold setting. It expands the dynamic range by making signals quieter if they are lower in level than the threshold setting. A signal that is above the threshold level is allowed to pass without being altered. 

||Threshold|Threshold|Threshold||||||
|---|---|---|---|---|---|---|---|---|
|Output Level|||||||||
||Depth||1:2            1|:1|0 Ratio||||
||||||||||
||Input Lev||||||||
|||Input Lev||el|||||
||||||||||
||Control|||||Range||Function|
||Threshold (Thrs)<br>Ratio<br>Attack Time (Atk)<br>Release Time (Rel)<br>Knee (Knee)<br>Depth (Dpth)|||||-80dBFS – 0dBFS<br>1:1 – 1:10<br>70uS – 50.0mS<br>0.0S – 5.0S<br>0.0dB – 60.0dB<br>0.0dB – +20dB||The level below which the Expander begins to act on the signal<br>The Ratio of gain of Input Signal vs Output Signal below the<br>threshold point<br>The time taken to impact the gain reduction<br>The time taken to return to zero gain reduction<br>How harshly the threshold point is applied, moving between<br>expanded and unexpanded signal<br>How far to apply the gain reduction Ratio|



## Controlling the Expander parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0017-04.png>)


To access the Expander controls, select the Exp/ Gate Process Selection button, the first two strips of the Chan-Quad are then assigned to the Expander Controls. The First ‘On’ button is assigned to the Expander In/Out control. 

The Expander can also be turned on and off by clicking on the EXP Process In/Out control 

The Threshold of the Expander can be altered by clicking and moving the Node on the interactive Graph. While the compressor node is highlighted clicking and dragging the mouse elsewhere on the graph will alter the Knee control. The Mouse wheel will also alter the Knee Control. The Compressor can be switched on and off with Left and Right mouse clicks on the nodes and colour key. Clicking on the Expander node also assigns the Expander controls to the Chan-Quad panel and highlights them. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Gate** 

Audio gating (sometimes referred to as a noise gate) is the control of when, and at what level, audio is allowed to pass. 

Gating is commonly used to remove background noise (other sounds picked up by a microphone that are not wanted) in music this might be bleed from other elements of a close-miked drum kit or in post-production ‘onset’ background noise from a location recording. There are also creative uses of audio gates, such as shortening the tail of a snare drum, or creating no-linear reverb tails. 

The Gate works in a similar way to the expander, but with a fixed Ratio of 1: ∞, meaning signals below the threshold are reduced by the value of the Depth settings, or cut altogether if the Depth is set to minimum (which is the most common setting for a Gate). The Gate does not have a Knee control. 

As the gate can introduce significant steps in gain reduction by cutting signals when passing below the threshold (or down by whatever the Depth control is set to), there can be unpleasant effects known as ‘chattering’ when an audio signal is around the threshold level and changing small amounts in level, causing the signal to be cut and uncut repeatedly. To get around this the gate has a Hysteresis control with settings between 0dB (no hysteresis) and 20dB. The hysteresis value makes the ‘Gate Open’ threshold higher than the ‘Gate Close’ threshold allowing the signal to fluctuate in this range without repeatedly closing and opening the gate. 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0018-05.png>)


**----- Start of picture text -----**<br>
Threshold<br>Gate Open Threshold<br>Hysteresis<br>Gate Close Threshold<br>Depth<br>Input Level<br>Output Level<br>**----- End of picture text -----**<br>


Once the signal has dropped lower than the threshold level minus the Hysteresis level (and turned the gate off), the signal must exceed the Threshold for the gate to turn back on 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## Gate Controls: 

|Control|Range|Function|
|---|---|---|
|Threshold (Thrs)<br>Attack Time (Atk)<br>Release Time (Rel)<br>Hysteresis (Hyst)<br>Depth (Dpth)|-80dBFS – 0dBFS<br>70uS – 50.0mS<br>0.0S – 5.0S<br>0.0dB – 60.0dB<br>0.0dB – +20dB|The level below which the Gate turns off (plus amount of Hysteresis)<br>The time taken to fully impact the gain reduction<br>The time taken to return to zero gain reduction<br>The difference between Gate open and close thresholds<br>How far to apply the gain reduction|



## Controlling the Gate parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0019-03.png>)


To access the Gate controls, select the Exp/ Gate Process Selection button, the 3[rd] and 4[th] strips of the Chan-Quad are then assigned to the Gate Controls. The 3[rd] ‘On’ button is assigned to the Gate In/ Out control. 

The Threshold of the Gate can be altered by clicking and moving the Node on the interactive Graph. 

The Gate can be switched on and off with Left and Right mouse clicks on the node and colour key. 

Clicking on the Gate node also assigns the Gate controls to the Chan-Quad panel and highlights them. 

The Gate can also be turn on and off by clicking on the GATE Process In/Out control 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

## **Input Process** 

To balance the gain at the input of the plugin an Input Level Control with +/-24 dB of gain is available. This control is accessed by selecting the I/O Process Selection Button and is assigned to control 1 on strip 1 of the Chan-Quad Panel. 

## **Output Process** 

To balance the gain at the output of the plugin an output Level Control with +/-24 dB of gain is available. This control is accessed by selecting the I/O Process Selection Button and is assigned to control 1 on strip 3 of the Chan-Quad Panel. 

## **Phase Control** 

A phase control is available for both mono and stereo instances of the plugin. 

For the mono instance it is either normal (displayed ‘ɸ’) or reversed (displayed ‘Rɸ’). 

For the Stereo instance the options are for Neither Leg, Left Leg, Right Leg or Both Legs to be phase reversed. (displayed ‘ɸ’ or when Left reversed ‘RɸA’, right reversed ‘RɸB’ or for both ‘RɸAB’). 

This control is accessed by selecting the I/O Process Selection Button and is assigned to control 2 on strip 1 of the Chan-Quad Panel. 

## **Stereo Width** 

For stereo instances of the plugin there is a Stereo Width Control. 

At its mid setting the Stereo signal passes unaffected. 

When set below the middle, some of the left signal is added into the right leg and visa-versa, making the signal less wide. At zero ‘MONO’ is displayed, left and right legs are identical. 

When set above the middle, some of the left signal is inverted and added to the right leg and visa-versa, at its maximum setting the signal is pulled ‘wide’, as 100% of the left inverted signal is added to the right leg and visa-versa. Care should be taken as very wide signals like this may not result in good MONO ‘crash-downs’ particularly a consideration for TV and radio work where the mono version is regularly used. For mono instances of the plugin this control is not available, and the control will be blank 

Controlling the Input and Output parameters 


![](<AMS Neve DFC Channel Strip Manual_assets/AMS_Neve_DFC_Channel_Strip_Manual.pdf-0020-15.png>)


To access the Input and Output controls, select the I/O Process Selection button, the 1[st] and 3[rd] strips of the Chan-Quad are then assigned to the Input and Output controls. 

AMS Neve Digital Film Console (DFC) Channel Strip Plugin Manual – D Critchley 2018 

