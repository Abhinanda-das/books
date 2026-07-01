---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Chandler Limited Zener Limiter Manual.pdf
converted_at: 2026-06-03T09:43:17Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 2949
---

**®** 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0001-01.png>)


**User’s Guide ®** 

Rev. Oct 24, 2016 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0002-00.png>)


## **Softube User Manual** 

© 2007-2016. Amp Room, Softube are a registered trademarks of Softube AB, Sweden. Rock n’ Roll Scientists is a trademark of Softube AB, Sweden. All visual and aural references to Marshall, Super Lead, Plexi, 1959, Bluesbreaker, JMP 2203, Silver Jubilee 2555 and associated logos are trademarks of Marshall Amplification UK used under license. The Valley People Dyna-mite, Tonelux and Tilt are trademarks of PMI Audio used with written permission from PMI Audio. The Tonelux and Tilt logo, the Valley People, Dynamite and associated logos, are trademarks of PMI Audio Group, used under license. Summit Audio Inc. is a trademark by Baltic Latvian Universal Electronics, LLC, used under license. Chandler Limited and associated logos are trademarks of Chandler Limited used under license. Abbey Road Studios, EMI, TG, RS, Zener Limiter and their associated logos are trade marks of EMI (IP) Limited.  All specifications subject to change without notice. All Rights Reserved. 

Other company and product names mentioned herein are trademarks of their respective companies. Mention of third-party products is for informational purposes only and constitutes neither an endorsement nor a recommendation. Softube assumes no responsibility with regard to the performance or use of these products. 

Softube products are protected by patents SE526523 and SE525332, and related patents/patent applications, including WO06054943, US11/667360, US2004 0258250, EP1492081, EP1815459, and JP2004 183976. 

Your rights to the software are governed by the accompanying software license agreement (End User License Agreement). 

## Acknowledgements and Licenses 

**zlib.h** interface of the ‘zlib’ general purpose compression library version 1.2.8, April 28th, 2013. Copyright © 1995-2013 Jeanloup Gailly and Mark Adler.  Portions of this software are copyright © 2006 **The FreeType Project** (www.freetype.org).  All rights reserved. **WonderGUI** used under commercial license © Tord Jansson. **Libpng** versions 1.2.6, August 15, 2004, through 1.6.12, June 12, 2014, are copyright © 2004, 2006-2014 Glenn Randers-Pehrson, and are distributed according to the same disclaimer and license as libpng-1.2.5.  Some code copyright © 2008 **The NetBSD Foundation** , Inc. **VST** is a trademark and software of Steinberg Media Technologies GmbH.  Mac OS X headers are covered under the **Apple Public Source License** (APSL) and available at http://www. publicsource.apple.com/apsl/ 

## Disclaimer 

Every effort has been made to ensure that the information in this manual is accurate. However, there are a chance that we have made mistakes, and we hope that you understand that we are only humans. Please let us know about the mistake, and we’ll fix it in the mix (or in the next version of this manual). 

## Support 

On the Softube website (www.softube.com) you will find answers to common questions (FAQ) and other topics that might interest you. 

Support questions can be posted at http://www.softube.com, where we will help you as fast as we can! 

Web: www.softube.com E-mail: info@softube.com Phone: +46 13 21 1623 (9 am – 5 pm CET) 

SOFTUBE USER’S GUIDE | **iii** 

## Contents 

|**1**|_User Interface_<br>_5_|
|---|---|
||Menu Row  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 5|
||Key Commands .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  6|
|**2**|_Chandler Limited_**®**_Zener Limiter_**®**<br>**7**|
||Center Section Controls   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  8|
||Compressor Controls.   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   10|
||Linked vs. Unlinked Channels.   .   .   .   .   .   .   .   .   .   .   .   .   13|
||Linking Input and Output Controls   .   .   .   .   .   .   .   .   .   .   13|
||Mono Mode   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   13|
||In Use  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  13|
||Credits .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  14|



| **5** 

1 User Interface 

Softube plug-ins are “what you see is what you get” products. You should be able to intuitively learn the products within minutes, so that you can work fast and efficient with them. There are a couple of things that remain the same for all of our plug-ins, such as the menu row. These will be explained in this chapter. For detailed information of a particular plug-in, please see its chapter. 

## **Menu Row** 

In the bottom of the plug-in interface, you will see a thin black row with some buttons. We’ll use the Chandler Limiter Zener Limiter plug-in as an example, but the same goes for all Softube plug-ins. 

~~Enable Enable/Activate the plug-in.~~ Set to off for bypass. 

~~Setup Changes global options for all~~ instances of that plug-in. 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0005-07.png>)



![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0005-08.png>)


## Enable 

~~About Box Opens the “About” Box with~~ version info. 

When the **Enable** switch is set to on (I), the plugin is active and will process audio. When set to off (0), it will be bypassed and not process any audio. 

~~Value Display Displays the knob value when~~ the mouse is hovering over a control. 

“About” Box Value Display 

Enable Setup 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0005-15.png>)


**6** | USER INTERFACE 

## Setup 

In the Setup window you can change settings that will affect all instances of that particular plug-in. If you, for example, de-select the “Show Value Display” option in the plug-in, the value display will be off for all instances of that plug-in on your system until you select that option again. 

The different options vary between Windows and Mac, and also different formats and plug-ins. The most common options are: 

Show Value Display: Enables the parameter and value display in the bottom row of the plug-in. 

Reverse Mouse Wheel Direction: (Mac OS Only) Changes if the a knob is turned up or down when the mouse wheel is turned up or down. _(Mac OS Only)_ 

You need to restart your host software (DAW) before the changes to fully take effect! 

If you messed something up and manually need to set these options, you’ll find them in text format in the following locations: 

Mac OS: ~/Library/Application Support/ Softube 

Windows: username\Application Data\ 

## **Key Commands** 

All numbers and labels in the plug-in are clickable. This allows you to easily select a setting by clicking on the wanted value. Hovering above a label will turn the mouse pointer into a pointing hand. 

## Mouse 

## Up/Down or 

~~Mouse Wheel Change a parameter, such as a~~ knob or a switch. 

## Keyboard 

~~Fine Adjust ⌘ (Mac) or Ctrl (Win),~~ while changing the parameter value. 

~~Reset to Default Alt, while clicking on the~~ knob or fader. 

~~Link Parameters Shift, while clicking on a~~ button or a knob. 

Some plug-ins have linked parameters, such as the two mics in Metal Amp Room, or the Input and Output volume in Zener Limiter. In order to change both knobs at once, adjust one of the knobs while holding shift. 

| **7** 

## Chandler Limited **®** 2 Zener Limiter **®** 

The Chandler Limited Zener Limiter is the ultimate TG limiter, issued in celebration of the 75th birthday of **Abbey Road Studios** . The Zener Limiter was conceived by Chandler Limited founder and Chief Designer, **Wade Goeke** , and is based on the vintage EMI circuits used to record **The Beatles** and **Pink Floyd** . 

Chandler Limited’s Zener Limiter continues the tradition of EMI Limiters started in 1954 with the **RS114** tube limiter and the 1968 **RS168 Zener Limiter** . Zener Limiters were also part of the 1969 **TG12345** console channels and the 1974 **TG12410** mastering desk. This newest version, reimagined to work in a modern context, borrows 

Abbey Road Studios, EMI, TG, RS, Zener Limiter and their associated logos are trade marks of EMI (IP) Limited. 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0008-00.png>)


**----- Start of picture text -----**<br>
8 | CHANDLER LIMITED® ZENER LIMITER®<br>**----- End of picture text -----**<br>


## **Center Section Controls** 

from the RS168 and TG12345 console channel strip limiter to make a new fully featured and flexible unit. 

Wade Goeke added many new controls including switchable input impedance for hard or soft driving of the unit, 11-position attack, 21-position release, side chain filtering, and Comp 1, Comp 2, and limit settings. 

The Chandler Limited Zener Limiter adds features and flexibility to the powerful and vintage sounding TG limiter circuits of a bygone era. 

~~In Left/Mid Activates or bypasses Ze-~~ ner’s processing of the Left or Mid channel (depending on the position of the **Mid/ Side Processing** button) to facilitate direct comparison of the processed and unprocessed sound. 

~~In Right/Side Activates or bypasses Zener’s~~ processing of the Right or Side channel (depending on the position of the **Mid/ Side Processing** button) to facilitate direct comparison of 

SOFTUBE USER’S GUIDE | **9** 

the processed and unprocessed sound. 

~~Mid/Side Processing Enables MID/SIDE processing.~~ When in Mid/Side mode, the Left channel of the limiter controls the Mid channel, and Right channel controls the Side channel. 

With unlinked channels you get a true dual channel processing with completely independent compressors. Link channels to get a more "normal" stereo compressor mode. 

## Center Section 

Please note that you need to unlink the channels to get true, independent mid/side processing. 

~~Link Channels Links the left and right~~ channels in stereo mode, and Mid and Side in Mid/ Side mode. When the channels are linked, any adjustments made to one channel will be automatically reflected in the other. 

In In Left/Mid Right/Side Mid/Side Link Processing Channels 

Left/Mid Center Section Section 

Right/Side Section 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0009-10.png>)


**10** | CHANDLER LIMITED® ZENER LIMITER® 

## Left/Mid and Right/Side Section 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0010-02.png>)


**----- Start of picture text -----**<br>
Input Gain THD<br>Input Attack<br>Output Release<br>Comp 1  Side<br>Comp 2  Chain<br>Limit<br>**----- End of picture text -----**<br>


## **Compressor Controls** 

~~Input Gain Te Zener has selectable~~ input gain and input impedance via the input gain toggle on the top left of the control panel. This was added so the Limiter could more easily replicate different versions of the RS168 and TG12413 limiters. The high gain setting is 12dB higher and is similar to the “Vanderlism” setting of the RS168 Zener prototype 

(please refer to the book “Recording the Beatles” for more). The low gain position is closer to the TG12345 console input, however, still hotter than the unity gain input of the TG12413 mastering console version. Input impedance is 300 ohm in High and 1200 ohm in Low. 

SOFTUBE USER’S GUIDE | **11** 

~~Input Tis is a 21-position gold~~ contact audio taper switch that controls the level going into the compressor/limiter. Simply turn it up to drive the unit into harder limiting. 

~~THD Te THD (total harmonic~~ distortion) toggle on the top right of each channel disengages the limiter’s threshold so that the channel will stop limiting, however, the signal still runs through the entire audio path and sidechain. The effect is a smooth pleasing distortion, featuring a high frequency bump caused by the discrete amplifiers and zener diode limiting circuit. Use the **Input** control switch to drive the signal for more or less distortion, as marked in white on the front panel. Interestingly, the THD function takes a clean sine wave signal and gradually triangulates it as you increase the input control, however importantly, it does not clip the signal in any way. It is possible to drive the THD past the 2% marking on the control panel by increasing the signal into the Zener from an outside source. 

~~Output Another 21-position gold con-~~ tact switch, set for +/-10 dB of gain control in 1 dB steps. Use 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0011-04.png>)


this for gain make up when hard limiting or to drive the second channel into a higher THD range when in THD mode as described above. 

Hold SHIFT while adjusting either the **input** or **Output** to adjust both simultaneously. Increasing **input** will decrease the **Output** , and vice versa. 

## ~~Comp 1/Comp 2/Limit A very important control,~~ 

used for tailoring the overall tone of the Zener Limiter. COMP 1 is a 2:1 ratio with slower time constants that was originally designed by EMI technical engineers to emulate Abbey Road’s RS124 Compressor. LIMIT is much faster and designed to emulate the response curves of the studio’s Fairchild 660s. COMP 2 is an modern setting placing the limiter halfway between the two original settings and essentially giving you the compression curve of COMP 1 with faster release times similar to LIMIT. 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0012-00.png>)


~~Sidechain Sidechain fltering was added~~ to the Zener as part of the effort to make an ultimately flexible TG Limiter. In situations where a TG1 may be too aggressive, the sidechain filter, combined with other Zener modifications, makes this new TG limiter useable in nearly every situation. 

With this control you can remove low frequency information (30 to 300 Hz) feeding the limiting circuit. It is _very_ effective when you need a more gentle compression or limiting action while maintaining that special TG sound. Excellent for mixes, subgroups, bass, and even hard slamming kick drums! 

~~Attack Te~~ ~~**Attack** control combined~~ with the **Sidechain** filter is the heart of the flexibility of the Zener. The RS168 and all TG versions of the limiter had fixed attack times, until now. You will notice that setting 2 is white, this is the original attack time with the remaining positions in yellow being new settings. Since the attack times were generally quite quick, especially in LIMIT mode, most additional settings are slower. These are extremely effective on drums and bass when combined with sidechain filter. 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0012-04.png>)


~~Release A special feature of all EMI~~ limiters, from the RS114 tube limiter, RS124 compressor, RS168 Zener prototype, TG12345 console limiter, and TG12413 mastering desk limiter was that they all shared a special set of six recovery or release times. 

These settings are a very important part of the EMI and TG sound. The Zener Limiter preserves these settings in all their glory, though also greatly expands on them, adding 

SOFTUBE USER’S GUIDE | **13** 

further flexibility and tonal character. The new expanded release control features 21 positions with the original 1-6 release times marked in white among the modern additions presented in yellow, making it easy to recall the old school setting of your choice or experiment creatively with the new settings. 

Some engineers may wish to use the new release times to tune the release to match the tempo of their source material or just enjoy the great variety of sounds attainable. 

NOTE! The fastest release times, positions 1 and 2, marked in yellow, were mainly chosen for the generally slower acting COMP 1 and 2 modes. When LIMITING very hard on these settings, it may yield unpleasing artifacts and it generally is best to switch to the vintage (1) setting, presented in white; this was the standard fast setting on EMI Limiters. 

## **Linked vs. Unlinked Channels** 

Normally, a stereo compressor will have the same amount of gain reduction on both channels, regardless of the difference of the channels. This is to, for example, avoid having the entire sound field tilt to the left when a loud sound is heard in the right channel. But for mastering purposes, and lower gain reduction amounts, it is often very useful to decouple these two channels in order to preserve a "depth" to the sound. 

By engaging **Link Channels** , you'll get the "normal" stereo mode with linked gain reduction, as well as linked parameters. Set **Link Channels** to off 

and you get true, independent gain reduction. 

This feature is even more important in **Mid/Side Processing** mode, where you seldom want to link the gain reduction. 

## Linking Best Practices 

- Stereo mode: If you have lots of gain reduction,  link your channels. 

- Mid/Side mode: Unlink them. 

- Stereo mode: If you are mastering or applying small amounts of gain reduction, try to unlink them. But look out for sudden shifts in the stereo image related to the gain reduction. 

As always, trust your ears. If it sounds good, it is good! 

## **Linking Input and Output Controls** 

If you want to adjust the input gain while simultaneously compensating with the output gain, hold shift while adjusting the **Input** or **Output** knob. 

The output level will be decreased if you increase the input level, and vice versa. 

## **Mono Mode** 

When using the Zener Limiter in mono, please set it in Mid/Side mode for correct gain staging. 

## **In Use** 

At unity gain input with the **Input** control switch on full you will get about 2% THD (total harmonic distortion). If this is increased to +4–5 dB, distortion will increase to around 5%, which is many, many times that of tape and without clipping. 

Abbey Road Studios, EMI, TG, RS, Zener Limiter and their associated logos are trade marks of EMI (IP) Limited. 

**14** | CHANDLER LIMITED® ZENER LIMITER® 

One excellent use of this is to patch the two Zener channels in series, using the first to limit and the second for THD. Use the **Output** control of the first channel to drive the input of the second into higher THD percentages, while lowering the output of the second to control overall level. Very retro! 

## **Credits** 

**Björn Rödseth** - modelling. **Paul Shyrinskykh** - product owner, manual. **Niklas Odelholm** - graphic design. **Ulf Ekelöf** - 3D rendering. 


![](<Chandler Limited Zener Limiter Manual_assets/Chandler_Limited_Zener_Limiter_Manual.pdf-0015-00.png>)


**Softube AB, S:t Larsgatan 9D, 582 24 Linköping, Sweden. www.softube.com** 

