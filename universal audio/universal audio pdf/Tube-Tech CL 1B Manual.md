---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Tube-Tech CL 1B Manual.pdf
converted_at: 2026-06-03T08:58:10Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 2466
---


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0001-00.png>)


# **User Manual Tube-Tech CL 1B** 

Rev. Feb 19, 2015 


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0002-00.png>)


## **Softube User Manual** 

© 2007-2015. Amp Room is a registered trademark of Softube AB, Sweden. Softube is a registered trademark of Softube AB, Sweden. All visual and aural references to the Valley People Dyna-mite, Tonelux and Tilt are trademarks being made with written permission from PMI Audio. The Tonelux and Tilt logo, the Valley People, Dyna-mite and associated logos, are trademarks of PMI Audio Group, used under license.Summit Audio Inc. is a trademark by Baltic Latvian Universal Electronics, LLC, used under license. All specifications subject to change without notice. All Rights Reserved. 

Other company and product names mentioned herein are trademarks of their respective companies. Mention of third-party products is for informational purposes only and constitutes neither an endorsement nor a recommendation. Softube assumes no responsibility with regard to the performance or use of these products. 

Softube products are protected by patents SE526523 and SE525332, and related patents/patent applications, including WO06054943, US11/667360, US2004 0258250, EP1492081, EP1815459, and JP2004 183976. 

Your rights to the software are governed by the accompanying software license agreement (End User License Agreement). 

## Acknowledgements and Licenses 

**zlib.h** interface of the ‘zlib’ general purpose compression library version 1.2.8, April 28th, 2013. Copyright © 1995-2013 Jeanloup Gailly and Mark Adler.  Portions of this software are copyright © 2006 **The FreeType Project** (www.freetype.org).  All rights reserved. **WonderGUI** used under commercial license © Tord Jansson. **Libpng** versions 1.2.6, August 15, 2004, through 1.6.12, June 12, 2014, are copyright © 2004, 2006-2014 Glenn Randers-Pehrson, and are distributed according to the same disclaimer and license as libpng-1.2.5.  Some code copyright © 2008 **The NetBSD Foundation** , Inc. **VST** is a trademark and software of Steinberg Media Technologies GmbH.  Mac OS X headers are covered under the **Apple Public Source License** (APSL) and available at http://www. publicsource.apple.com/apsl/ 

## Disclaimer 

Every effort has been made to ensure that the information in this manual is accurate. However, there are a chance that we have made mistakes, and we hope that you understand that we are only humans. Please let us know about the mistake, and we’ll fix it in the mix (or in the next version of this manual). 

## Support 

On the Softube website ( `www.softube.com` ) you will find answers to common questions (FAQ) and other topics that might interest you. 

Support questions can be posted at `http://www.softube.com` , where we will help you as fast as we can! 

Web: `www.softube.com` E-mail: `info@softube.com` Phone: +46 13 21 1623 (9 am – 5 pm CET) 

SOFTUBE USER’S GUIDE | **iii** 

## Contents 

|**1**|_User Interface_<br>_5_|
|---|---|
||Menu Row  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 5|
||Key Commands .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  6|
|**2**|_Tube-Tech CL 1B Compressor_<br>_7_|
||Foreword by John G. Petersen   .   .   .   .   .   .   .   .   .   .   .   .   .  7|
||About the CL 1B.   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  7|
||User Interface .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  8|
||Suggested Applications  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  10|
||Mono and Stereo Operation   .   .   .   .   .   .   .   .   .   .   .   .   .   10|
||Credits .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  10|



| **5** 

1 

## User Interface 

Softube plug-ins are “what you see is what you get” products. You should be able to intuitively learn the products within minutes, so that you can work fast and efficient with them. There are a couple of things that remain the same for all of our plug-ins, such as the menu row. These will be explained in this chapter. For detailed information of a particular plug-in, please see its chapter. 

~~Enable Enable/Activate the plug-in.~~ Set to off for bypass. 

~~Setup Changes global options for all~~ instances of that plug-in. 


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0005-06.png>)


## **Menu Row** 


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0005-08.png>)


In the bottom of the plug-in interface, you will see a thin black row with some buttons. We’ll use the Dyna-mite plug-in as example, but the same goes for all plug-ins. 

## Enable 

~~About Box Opens the “About” Box with~~ version info. 

~~Value Display Displays the knob value when~~ the mouse is hovering over a control. 

When the **Enable** switch is set to on (I), the plugin is active and will process audio. When set to off (0), it will be bypassed and not process any audio. It will take considerably less CPU when it is bypassed. 

“About” Box Value Display 


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0005-15.png>)


**----- Start of picture text -----**<br>
Enable Setup<br>**----- End of picture text -----**<br>



![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0005-16.png>)


**6** | USER INTERFACE 

## Setup 

In the Setup window you can change settings that will affect all instances of that particular plug-in. If you for example de-select the “Show Value Display” option in the Bass Amp Room plug-in the value display will be off for all Bass Amp Rooms on your system until you select that option again. 

The different options vary between Windows and Mac, and also different formats and plug-ins. The most common options are: 

Show Value Display: Enables the parameter and value display in the bottom row of the plug-in. 

Reverse Mouse Wheel Direction: (Mac OS Only) Changes if the a knob is turned up or down when the mouse wheel is turned up or down. _(Mac OS Only)_ 

You need to restart your host software (DAW) before the changes to fully take effect! 

If you messed something up and manually need to set these options, you’ll find them in text format in the following locations: 

Mac OS: `~/Library/Application Support/ Softube` 

Windows: `username\Application Data\` 

## **Key Commands** 

All numbers and labels in the plug-in are clickable. This allows you to easy select a setting by clicking on the wanted value. Hovering above a label will turn the mouse pointer into a pointing hand. 

## Mouse 

## Up/Down or 

~~Mouse Wheel Change a parameter, such as a~~ knob or a switch. 

## Keyboard 

~~Fine Adjust ⌘ (Mac) or Ctrl (Win),~~ while changing the parameter value. 

~~Reset to Default Alt, while clicking on the~~ knob or fader. 

## Plug-In Specific Key Commands 

In many plug-ins, you can shift-click on a knob or a switch to get some extra functionality 

## Metal Amp Room 

Shift-click and drag a mic will move both mics simultaneously. 

## All Amp Rooms 

Shift-click in the cabinet background will change cabinet (or amp) without any animations 

| **7** 

## 2 

## Tube-Tech CL 1B Compressor 

## **Foreword by John G. Petersen** 

_After several years of consideration, we decided that the time had come to introduce a plug in of our TUBE- TECH CL 1B._ 

_The development of the plug in was initialized in November 2006, as a co operation between Lydkraft, Softube and TC Electronic. Hearing the result, we found that Softube was able to reach the difficult goal of making a plug in of the CL 1B which came extremely close to the original sound and gave the user all the characteristics of the hardware. After very serious testing of the software, the plug in was released late 2007._ 

_To take this project one major step further, we decided in early spring 2009 to release a VST/AU/RTAS version of the plug in, and once again placed the developing task in the hands of Softube._ 

_We are very impressed by the skills of these young guys from Sweden and we feel excited that the quality of the CL 1B is now available for all workstation users._ 

_We hope you will enjoy the excellence of the TUBE -TECH CL 1B plug in._ 

_Yours sincerely,_ 

_John G. Petersen President, Lydkraft/Tube-Tech_ 


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0007-11.png>)


## **About the CL 1B** 

The hardware CL 1B differs from many other compressors in that the gain reduction element is made from a non semiconductor component, which in itself has a very low harmonic distortion and none of the non linearity problems involved when using most semiconductor elements. All parts of these equally important design choices have of course been painstakingly modeled when creating the CL 1B plug in. 

Another thing that is special about the CL 1B is the **Attack/Release Select** switch which allows the user to switch between a manual and a fixed attack/ release setting, but also makes it possible for the user to combine both the fixed and manual settings. This gives a feature not normally obtained in other compressors: In the combined mode the attack and release controls makes it possible to obtain complex program dependent release time slopes where a fast peak results in a fast release and vice versa. 

**8** | TUBE-TECH CL 1B COMPRESSOR 


![](<Tube-Tech CL 1B Manual_assets/Tube-Tech_CL_1B_Manual.pdf-0008-01.png>)


**----- Start of picture text -----**<br>
Gain Ratio Threshold Meter Select VU Meter<br>Attack Time Release Time Attack/Release<br>Select<br>**----- End of picture text -----**<br>


## **User Interface** 

~~Gain Te~~ ~~**Gain** control is used to “make up” for the gain loss, which takes place when the~~ unit is compressing. It is placed after the gain reduction circuit and therefore has no influence on the threshold setting. The **Gain** control is continuously variable from off to +30 dB. 

~~Ratio Te~~ ~~**Ratio** control varies the ratio by which the input signal is compressed. If the ratio~~ selected is 2:1, and the input signal increases 10 dB, the output signal is only increased by 5 dB. The **Ratio** control is continuously variable from 2:1 to 10:1. 

~~Threshold Te threshold is the point where the compressor begins its action. It is defned as the~~ point where the gain is reduced by 1 dB. The **Threshold** control is continuously variable from +20 dB to –40 dB. 

~~Meter Select Select what the VU meter should display:~~ 

Input: The meter shows the input level. 

Compression: The VU meter is showing the gain reduction. Output: The meter shows the output level. 

Please note that it does not show peak or true RMS, it is a VU meter and behaves just like the original unit. 

The meter and the plug in is calibrated so that a sine wave showing 0 VU at the output corresponds to a –18 dBFS output signal. Correspondingly, a  18 dBFS sine at the input will show 0 VU if the meter is set at showing the input signal. 

SOFTUBE USER’S GUIDE | **9** 

~~Attack Time Te~~ ~~**Attack** control chooses how fast/slow the compressor responds to an increase in~~ the input signal. It is continuously variable from 0.5 to 300 milliseconds. 

~~Release Time Te~~ ~~**Release** control sets how fast/slow the compressor responds to a decrease in the~~ input signal. It is continuously variable from 0.05 to 10 seconds. 

~~Attack/Release Select Tis switch selects how the compressor reacts to an increase (attack) or a decrease~~ (release) of the input signal. 

There are three settings of this switch: 

FIXED: Attack time: 1 millisecond Release time: 50 milliseconds. 

MANUAL: Attack time: From 0.5 to 300 milliseconds Release time: From 0.05 seconds to 10 seconds. 

FIX./MAN: This setting combines the release times of fixed and manual mode. The attack time is as it is in the fixed mode. 

The FIX./MAN. mode always has a fast attack, but it is possible to obtain a release time that depends on the input signal, for example get a fast release when the peak disappears, then superseded shortly thereafter by the release time selected by the **Release** control. 

The time the peak disappears to the point where the selected **Release** time takes over, is dependent upon the setting of the **Attack** control. That is, the **Attack** control changes function from a pure attack control to a control of the delayed release with the same time range. 

Turn the **Attack** control clock wise to increase the time before the **Release** control takes over. Decrease the **Attack** control to shorten the time before the **Release** control takes over. 

This function is valid only if the time of the peak is shorter than the setting of the **Attack** control. If the peak of the program is longer, or if the **Attack** control is set at its minimum position, it will respond just as in the MANUAL mode. 

The FIX./MAN. mode acts as an automatic release function with a constant fast attack time and fast release time for short peaks and longer release times for longer peaks. This settings is mainly intended for use on program material (overall compression). 

**10** | TUBE-TECH CL 1B COMPRESSOR 

## **Suggested Applications** 

Here you will find suggestions on various applications of the Tube -Tech CL 1B compressor plug in. They are given as a convenient guide that enables you to familiarize yourself with the different aspects of using the compressor. We have not mentioned specific settings of the **Gain** and **Threshold** as they are dependent on the input levels. Instead we have specified how much compression in dB we feel is needed for the various examples. 

_These examples were taken from the CL 1B hardware manual, and are of course just as valid for the plug-in as for the real unit._ 

## Overall Compression (Final Mix) 

Compression needed: 3- 4 dB Attack/Release Select: FIX./MAN. Attack: 2 o’clock Release: 10 o’clock Ratio: 9 o’clock 

## Standard Compression (Bass, Piano, Guitar, Keys and Vocals) 

Compression needed: 4 -5 dB Attack/Release Select: MANUAL Attack: 2 o’clock Release: 10 o’clock Ratio: 10- 2 o’clock 

Attack: – Release: – Ratio: 9- 12 o’clock 

## **Mono and Stereo Operation** 

In stereo mode, the gain reduction of the left and right channel is always linked, in order to reduce stereo image shifting. The gain reduction used will be calculated from a combination of the two channels, just as if two hardware CL 1B had been linked together using a sidechain bus. 

## **Credits** 

**Arvid Rosén** – modeling. **Oscar Öberg** – modeling and DSP programming. **Torsten Gatu** – framework and DSP programming. **Niklas Odelholm** – GUI and framework programming. **Ulf Ekelöf** – 3D rendering. Original hardware was designed by **John G. Petersen** at Lydkraft ApS. 

TUBE-TECH IS A REGISTERED TRADEMARK OF LYDKRAFT ApS, DENMARK. ALL SPECIFICATIONS SUBJECT TO CHANGE WITHOUT NOTICE. ALL RIGHTS RESERVED. 

## Heavy Compression on Instruments (Line Guitar and Piano) 

Compression needed: 10 dB Attack/Release Select: MANUAL Attack: 7 o’clock Release: 1 o’clock Ratio: 3 o’clock 

## Compression of Drums (Snare and Bass Drum) 

Compression needed: 2 -3 dB Attack/Release Select: FIXED 

**Softube AB, S:t Larsgatan 10c, 582 24 Linköping, Sweden. www.softube.com** 

