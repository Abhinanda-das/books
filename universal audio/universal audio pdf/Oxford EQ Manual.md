---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Ошибки/2026-06-03_113837_Oxford EQ Manual/Oxford EQ Manual.pdf
converted_at: 2026-06-03T12:25:57Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 3659
---


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0001-00.png>)



![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0001-01.png>)


## Sonnox **Oxford EQ & Filters** 

## **Operation Manual** 

Version 1.0   12[th] February 2012 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0001-05.png>)


1 

## **1. Introduction** 

The Oxford EQ and Filters plug-in draws on the considerable experience in professional audio and studio systems earned by the Oxford Team, the team that designed the OXF-R3 console system. The Oxford EQ plug-in is based on the OXF-R3 EQ section and provides a truly professional EQ processor for Pro Tools, VST and Audio Units users. 

The Oxford EQ is a fully functional 5-band application with selectable shelf settings on LF and HF sections. Additionally, separate variable slope low pass and high pass filters are provided. The EQ also features four different selectable EQ types that cover most of the EQ styles currently popular amongst professional users, including some legacy styles, which are renowned for their artistic capability. The use of novel coefficient generation and intelligent processing design provides unparalleled performance that surpasses analogue EQ in both sound quality and artistic freedom. 

2 

## **2. Operation** 

## **2.1 Equaliser Design** 

Programme equalisers have expanded beyond their original use as distance correction devices for film and vision, into highly creative tools that represent a leading part of the sound engineer’s artistic palette.  A great many EQ designs have been developed over the years that have been attributed with qualities that lend themselves to particular uses and sounds. The Oxford EQ plug-in is designed to be flexible enough to address as many of these generic types as possible from a single application, by presenting a variety of types to the user. The following pages are presented as a general explanation of many of the factors that affect EQ performance, and to illustrate how we have addressed these issues with the Oxford EQ plug-in. 

Many types of EQ exist with many differences. One of the most important areas is the issue of control ranges and interaction. Whilst it is true that with a parametric unit with continuous controls (ie. not quantised) any response could be obtained by matching their curves, many of the popular EQs have control dependencies that err towards specific application. One of the main areas where EQs differ is Gain / Q dependency. Most analogue EQs have Gain / Q dependency as a result of the circuits used. This factor can greatly affect the artistic style that an EQ presents by facilitating certain parameter settings and encouraging particular uses when the unit is operated. 

In the Oxford EQ plug-in we have covered this situation by providing three different styles of EQ that take account of Gain / Q dependency as well as overall control ranges. 

3 

## **2.2 ‘Front Panel’ Controls** 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0004-01.png>)


The EQ and Filter controls are presented in a user-friendly layout, and the function of most of the knobs and switches should be immediately obvious. Full information on each control is provided in a later section of this manual: **Description of Controls** . 

Note the numeric displays for each rotary control. These provide instant feedback of your EQ and Filter settings, in addition to the graphic ‘response display’ provided at the top of the plug-in layout. The numeric displays can either be activated when an EQ or Filter section is switched **IN** (as shown in the example above), or may be left on permanently. The choice is made in an option menu available via the **Sonnox** button (in the top left of the plug-in); more on this later. 

Note also the ‘on/off’ button in the top right, above the response display. This provides a Master Bypass function so that all EQ and Filter sections can be switched in/out with one simple click. 

4 

## **2.3 Response Display** 

The upper area of the Oxford EQ plug-in is taken up by the EQ and Filter response display: 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0005-02.png>)


In addition to more conventional knob control, the EQ can be controlled from this graph if the ‘drag handles’ option is selected via a drop-down options menu that appears when you click the **Sonnox** button in the top left of the display. 

By default, the drag handles will be shown on the graph. Each drag handle corresponds to the EQ band or filter section knob caps that match the colour of the drag handle. For example, the dark blue drag handle controls the LF section, the red the MF section, the dark grey the low filter, etc. If not currently active, a band is automatically enabled when you drag its corresponding drag handle. 

Each band or filter can be toggled between its in and out state by double clicking on the drag handle that corresponds to that band or filter. Dragging the handle to the left or right will change the centre frequency of the band or filter. Dragging horizontally with the keyboard ‘alt’ key pressed down will change the ‘Q’ value for parametric EQ band sections. If you have two buttons on your mouse, right click and drag to change the ‘Q’; a mouse scroll wheel can also be used to modify the ‘Q’. Moving a drag handle vertically up or down will boost or cut the gain of EQ sections. For filter sections, dragging the handle vertically will increase or decrease the slope of the filter. 

If the drag handles are moved vertically with the ‘shift’ key pressed down, then the centre frequency is fixed and is not allowed to change. This allows you to change the amount of boost or cut without accidentally changing the centre frequency of the EQ band. This nifty trick can also be useful for cutting out annoying frequencies that you first have to find by boosting. 

5 

By default the vertical scale of the graph automatically adjusts itself to contain the yellow response line or all active handles, whichever is the bigger. The ‘ **+** ’ and ‘ **-** ’ buttons on the left hand side of the graph can be used to increase or decrease the scale of the graph. The default graph scale, and other options, can be changed by clicking the **Sonnox** button and selecting the **Graphs** entry on the drop-down menu. 

Note that the response graph setup is saved and restored across instantiations. 

## **2.3.1 Tips for Using the Response Display** 

The graph display is designed to be as intuitive as possible, but studying the following paragraphs will definitely help to increase your workflow: 

**Click on a graph handle to move it** – This means click on the handle with the left mouse button, drag the handle with the pointer, and then unclick. Moving a handle will automatically enable the corresponding section. 

**If the graph handle you want to use is hidden behind another handle –** Use click + Control key to grab the hidden handle ready for dragging. 

Whenever a handle is being used, the numeric readout displays of the corresponding section will provide immediate feedback of which section is being used, and the precise values of your adjustments. 

6 

## **2.3.2 Switching a Section In or Out** 

**Double clicking on a graph handle will toggle the section IN button** – You can also 

double click and drag without having to click a third time. 

– **Double clicking with the Control Key down** This will apply the toggle to the handle hidden behind the top one, if there is one. 

Notice that when a section is switched out, the handle remains true to the gain position of the control as shown below: 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0007-05.png>)


**----- Start of picture text -----**<br>
IN:  OUT:<br>**----- End of picture text -----**<br>


Also note that moving a handle will automatically enable that section, ie. switch the section **IN** button on. 

## **2.3.3 Changing the Frequency** 

Drag the handle right or left to increase or decrease the frequency. For finer resolution, use drag + Shift key. 

## **2.3.4 Changing the Gain or Slope** 

Drag the handle up or down to increase or decrease the gain. For finer resolution, use drag + Shift key. 

On the low and high filter sections, dragging a handle down increases the slope, and dragging a handle up decreases the slope. 

7 

## **2.3.5 Changing the Q or Overshoot** 

There are three ways to do this: 

If your mouse features a scroll wheel, scroll up or down to broaden or tighten the Q or overshoot. For finer resolution, use scroll + Shift key. 

If there is a right button on your mouse, drag the handle up or down with the right button. For finer resolution use right button drag + Shift key. 

Otherwise, use left button drag + ‘alt’ key up or down to broaden or tighten the Q or overshoot. For finer resolution use drag + Shift key + ‘alt’ key. 

## **2.3.6 Returning Entire Sections to Default** 

To set all controls in a section back to their default values (except for the **IN** button), use click + Control key + ‘alt’ key + Shift key. You can remember this by thinking of three keys for the three controls in the section. 

## **2.3.7 Configuring the Graph for Personal Preference** 

There are two options in the menu accessed via the **Sonnox** button that allow you to configure the graph display for your preferred way of working: 

– **Use Drag Handles** You can disable the graph handles for a cleaner look if you prefer to use the more traditional knob and button controls, and don’t want to be tempted to use the handles: 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0008-10.png>)


**Fill in EQ Bands** – determines whether you display the coloured infill under each section: 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0008-12.png>)


8 

The following sections provide a description of each EQ type: 

## **2.4 Bandpass Sections** 

## **2.4.1 EQ Type 1** 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0009-03.png>)


This style has minimal Gain / Q dependency, smaller amounts of boost or cut still have relatively high Q, and it is therefore precise and well defined in use. 

However it is sometimes difficult to obtain overall EQ fill on combined sources and subtle EQ on vocals and the like, as the user needs to adjust the Q control to maintain an effect when the gain is changed. Failure to understand this fact has often added to the reputation of this type of EQ for sounding ‘hard’ or ‘harsh’. However, because the user retains separate control of all its parameters, this EQ is still the most flexible for users that have the time and patience to spend when using it. 

It is most like the original SSL 4000 Series, and other ‘clinical’ styles of EQ that became popular in the 1980’s. 

9 

## **2.4.2 EQ Type 2** 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0010-01.png>)


Type 2 EQ is exactly similar in boost as Type 1, but has constant Q responses in cut. This is the only type of EQ offered in the Oxford plug-in that has unsymmetrical curves. Therefore EQ applied in a boost cannot be readily reversed by cutting afterwards. The EQ resembles some speciality legacy units, and lends itself well to resonance control for percussion instruments such as drums, since relatively high Q is available at low gain settings, whilst fairly subtle ‘fill EQ’ can be achieved using boost settings at the same time. 

10 

## **2.4.3 EQ Type 3** 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0011-01.png>)


This style of EQ has a moderate amount of Gain / Q dependency whereby the Q reduces with gain. This provides the EQ with a softer characteristic as EQ is progressively applied and since the effective bandwidth is increased for low gain settings, it sounds louder and more impressive when used at moderate settings. The gentler Q curve also lends itself better to overall EQ fills and more subtle corrections in instrument and vocal sources. Turning the Gain control seems to produce the effect that the ear is expecting, without needing to adjust the Q control too often. Therefore EQs of this type are often dubbed as ‘more musical sounding’. 

This EQ most resembles the older and well-loved Neve types, their modern derivatives and the later SSL G Series. Also many of the more popular outboard EQs have this dependency to some extent. 

11 

## **2.4.4 EQ Type 4** 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0012-01.png>)


EQ Type 4 builds on Type 3, using a far greater Gain / Q dependency which maintains an almost equal area under the curve in the boosted region with gain control operation. It is extremely soft and gentle in use and is most suited to overall EQ fill and character modification for mixed parts (and completed mixes) where subtle changes in overall impressions are required. Therefore it will also prove useful in mastering situations where there is requirement to match the sounds of tracks from different sources on a common production release. 

12 

## **2.5 Shelving Sections** 

In the Oxford EQ, the highest and lowest bandpass sections can be independently switched to provide a shelving function. Although shelving functions are often considered elementary, they are by no means all the same, and their importance to the sound engineer should not be underestimated. Various types in common use are considered to favour certain types of use or are considered preferable by users of differing persuasions. 

Our analysis of common shelving EQs has shown that one of the most important differences in the sound of the shelving EQ is the response around the band immediately below the HF section (and above the LF section). Many of the most loved classical EQs have a degree of ‘undershoot’ in this region (when in boost), either by design or as a result of circuit limitations in legacy units. Therefore most units can be characterised by control within this region of the frequency response. In appreciation of the importance of this parameter, the Oxford EQ provides the facility to modify the response in this region, and so provide differing styles of shelving EQ. 

13 

## **2.5.1 Shelving Overshoot Control** (HF shelf Q control) 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0014-01.png>)


When the HF shelving function is selected, the Q control provides control of the ‘overshoot’ function. 

With the Q control set to minimum (yellow plot) the section has no overshoot and performs a basic and accurate shelving function. This is most like the responses provided by the original SSL 4000 EQs and many other outboard units often described as ‘clean’ EQs. Although these are still very popular units, some engineers complain that they can sound harsh and overbearing in comparison with legacy EQs. 

As the Q control is increased, the overshoot factor is also increased. For example, the red plot shows a slight dip in the response at around 1.5KHz for a boosted HF setting of 6KHz. This has the effect of suppressing the perceived mid range boost that occurs with the previous ‘clean’ variety, reducing the apparent ‘hardness’ of the sound. This, along with the increased slope rate, provides more apparent definition to the EQ in the band of interest. 

14 

The purple plot shows the effect of the Q control in its mid position. This produces a gain loss of around 10% (of the boost gain) in the overshoot region and further defines the effect described above. This setting provides a response most like the legacy Neve designs and their derivatives, and the later SSL G Series EQs. This response produces an optimum effect by providing what the ear expects to hear as the gain control is operated, and can explain the enduring popularity and renowned musical qualities attributed to EQs of this type. 

At maximum (blue plot), the Q control provides an overshoot of half the total boosted gain, ie. for +20dB total HF boost the maximum loss in the overshoot region will be -8dB. The curves are symmetrical in cut and boost gain settings. 

15 

## **3. Description of Controls** 

The plug-in’s user interface consists of two sections for EQUALISATION and FILTERING functions. 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0016-02.png>)


## _**Response Display**_ 

Displays the currently active EQ and filter response curves. The graph will rescale to match the current sample rate. 

16 

## _**LF and HF Filter Sections**_ 

The **LF** and **HF** buttons switch the relevant filter in/out. The numeric button above determines the slope of each filter from 6dB – 36dB/octave in 6dB/octave steps. The rotary control determines the filter turnover frequency. 

## _**LF, HF, LMF, LMF Sections**_ 

The **FREQ** control sets the centre frequencies for bandpass or turnover frequencies for shelf curves. The **Q** control determines the bandwidth of EQ curves, and sets the amount of overshoot function for shelving sections. 

Two buttons to the left and right of the **LF** and **HF** gain controls select the shelving function for these sections. 

The **+** / **-** rotary controls set boost or cut gains for each section. If your host supports scrollwheel operation to the knob controls, then each increment or decrement of the scroll wheel will increase/decrease the gain value by exactly 0.5dB, thus allowing for an accurate incremental step. 

The **IN** buttons enable individual sections of the EQ to be switched in/out. 

## _**A and B Buttons**_ 

Two complete EQ / filter settings can exist simultaneously. The **A** and **B** buttons allow you to toggle between them for comparison purposes. 

## _**Main Gain Control**_ 

This sets the attenuation level of the complete EQ section to avoid clipping signals when in boost. 

## _**EQ Type Selection**_ 

The **+** / **-** buttons increment through the available EQ types, as shown in the character display above. 

17 

## _**Master IN button**_ 

Applies the EQ function type selected as described above The **IN** button light will go out if another EQ type is selected, indicating that the EQ remains unchanged until the **IN** button is selected again. 

## _**Master Bypass button**_ 

This ‘on/off’ style button (located in the top right of the plug-in display) provides a Master Bypass function so that all sections of the EQ and Filters can be simultaneously switched in/out of the assigned signal path. 

## _**Overload Indicator**_ 

This (just above the EQ Type window) displays any signal overload (red) at the output of the EQ and Filter sections. This can be disabled via the **Sonnox** button menu (see below). When active, the default mode for this function is latching, requiring a click to reset. The options menu provides a mechanism to select the duration of the overload indicator. 

## _**Options Menu**_ 

Clicking the **Sonnox** button produces a drop-down options menu (see right). 

**Over Light** – Determines the approximate time that the over light will stay on for when the plug-in has detected a full-level sample at either its input or output. 

**Enable Sonnox Toolbar** – displays or hides the Sonnox Preset Manager Toolbar. 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0018-10.png>)


**Show Preset Name Path** – Shows the hierarchical directory path for Presets that are stored in sub-folders of the default Preset folder. 

18 

**Always Display Numeric Values** – When this option is selected, the EQ and Filters’ numeric parameter displays are permanently shown. With this option de-selected, the numeric displays are only shown for EQ and Filter sections that are **IN** . 

**Copy A to B** and **Copy B to A** – These provide a quick mechanism to copy A and B EQ settings between each other. 

**Use Drag Handles** – Enables or disables the use of the EQ curve drag handles on the graphic display. 

**Fill in EQ Bands** – A colour infill can be used to shade the areas beneath the curve in the response display, to aid visibility of an individual section’s contributions. 

**Auto Scale Graph** – The graphic display can be re-sized using the ‘ **+** ’ and ‘ **-** ’ buttons. Alternatively, the graph can auto-scale, depending on the amount of EQ gain employed. 

**Scale Factor** – The scale can also be selected from these four fixed options. The scale is automatically saved between instantiations of the plug-in. 

**Ears Only Mode** – This option will blank the graphic display so you can work the traditional way! 

**About Sonnox Oxford EQ…** – displays the date, version and build number of the plug-in. 

19 

## **4. Preset Manager Toolbar** 

The Oxford EQ plug-in comes equipped with its own onboard Preset Manager, which is displayed as a toolbar at the top of the plug-in window, just as if the host created it (see right). The reasoning behind this is to allow increased portability of your presets across all the host applications, while also providing a consistent and versatile interface. Although most host platforms allow the creation and loading of presets, those host-created preset files are not portable 


![](<Oxford EQ Manual_assets/Oxford_EQ_Manual.pdf-0020-02.png>)


between different host applications. With the Oxford plug-ins’ preset manager, you can create a named preset in one host application and load it when using an alternative application. 

The **Sonnox** Preset Manager is fully described in a companion document — ‘Sonnox Toolbar and Preset Manager Operation Manual’. 

20 

## **5. Specifications** 

## **5.1 Oxford EQ Specifications and Control Ranges** 

|Section|Section|Gain|Gain|Frequency|Q/Slope|Q/Slope|Overshoot|
|---|---|---|---|---|---|---|---|
|LF Filter<br>LF Peak/Shelf<br>LMF<br>MF<br>HMF<br>HF Peak/Shelf<br>HF Filter||6dB/Oct steps<br>+/-20dB<br>+/-20dB<br>+/-20dB<br>+/-20dB<br>+/-20dB<br>6dB/Oct steps||20Hz - 500Hz<br>20Hz - 400Hz<br>30Hz - 600Hz<br>100Hz - 6KHz<br>900Hz - 18KHz<br>2KHz - 20Khz<br>1KHz - 20KHz|<br> <br> <br> <br> <br> <br>|0 –36dB/Oct<br>0.5 – 16<br>0.5 – 16<br>0.5 – 16<br>0.5 – 16<br>0.5 – 16<br>0 –36dB/Oct|0 – 50%  (Q adjust in Shelf)<br>0 – 50%  (Q adjust in Shelf)|
|||||||||
||Total dynamic|range|> 138dB*(RMS unweighted)|||For anysingle section,includingfilters||
||Harmonic Distortion||Undetectable|||UsingFFT analysis down to –160dBr||
||Control induced noise||< -95dBr(peak)|||Duringadjustment of anysingle control||



* Excluding excess noise produced by the EQ applying gain to a 24-bit dithered but silent input, or cascaded EQ applying gain to previous sections. 

21 

## **6. Copyright and Acknowledgements** 

Trademarks and content copyright © 2007-Present Sonnox Ltd. All rights reserved. 

This Product is manufactured and supplied by Sonnox Ltd. under licence from Sony UK Ltd. 

The following patents protect this Product: GB2330747, GB2350505, GB2350956, US6581080 

DIGIDESIGN, AVID, and PRO TOOLS are trademarks or registered trademarks of Digidesign and / or Avid Technology, Inc. 

VST is a Trademark of Steinberg AG. 

All other product and company names are Trademarks or Registered Trademarks of their respective holders. 

## **7. Manual Revision History** 

Version 1.0 date 12[th] February 2012 — First Sonnox for UA version 

22 

