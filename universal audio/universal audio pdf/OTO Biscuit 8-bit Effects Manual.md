---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Ошибки/2026-06-03_112956_OTO Biscuit 8-bit Effects Manual/OTO Biscuit 8-bit Effects Manual.pdf
converted_at: 2026-06-03T12:25:42Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 3897
---


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0001-00.png>)


# OTO BISCUIT 8-BIT EFFECTS 

Rev. Feb 16, 2017 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0002-00.png>)


## **Softube User Manual** 

© 2007-2017. Amp Room, Softube are a registered trademarks of Softube AB, Sweden. Rock n’ Roll Scientists is a trademark of Softube AB, Sweden. All visual and aural references to Marshall, Super Lead, Plexi, 1959, Bluesbreaker, JMP 2203, Silver Jubilee 2555 and associated logos are trademarks of Marshall Amplification UK used under license. The Valley People Dyna-mite, Tonelux and Tilt are trademarks of PMI Audio used with written permission from PMI Audio. The Tonelux and Tilt logo, the Valley People, Dynamite and associated logos, are trademarks of PMI Audio Group, used under license. Summit Audio Inc. is a trademark by Baltic Latvian Universal Electronics, LLC, used under license. Chandler Limited and associated logos are trademarks of Chandler Limited used under license. Abbey Road Studios, EMI, TG, RS, Zener Limiter and their associated logos are trade marks of EMI (IP) Limited.  All specifications subject to change without notice. All Rights Reserved. 

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

|**1**|_OTO Biscuit 8-bit Efects_<br>_5_|
|---|---|
||Overview .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  6|
||Top Panel Controls .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  7|
||Brain/Efects Panel   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  9|
||Linking Parameters  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  17|
||Tips  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  17|
||Credits .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  17|
|**2**|_General Settings_<br>_19_|
||Menu Row  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  19|
||Key Commands .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  20|




![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0005-00.png>)


**----- Start of picture text -----**<br>
 |  5<br>**----- End of picture text -----**<br>


## 1 OTO Biscuit 8-bit Effects 

OTO Biscuit came out in 2010 and was the first product by French audio wizards **Denis Cazajeux** and **Stéphane Briat** . Denis had started out building stompboxes and synths for his brand _Cazatronics_ already in the mid-2000s. One of the many boxes he built was the Biscuit, an effect housed in a plastic butter dish. 

The original idea for the Biscuit was to simulate the sound of an old **Fairlight CMI** sampler. An 8-bit analog to digital converter was set up with a parallel output to an 8-bit digital to analog converter, and the sampling frequency could be set with a dedicated knob. A 12 dB per octave low-pass filter with a Q control was added to the prototype, 

**6** | OTO BISCUIT 8-BIT EFFECTS 

as well as switches for muting and inverting the bits in the eight lines between the AD and DA converters. 

But it wasn’t until several years later, when Denis teamed up with producer/engineer Stéphane in a studio near Paris, that the two started expanding the Biscuit concept and turning it into a commercial product. 

## **Overview** 

OTO Biscuit is a useful tool for all sorts of noise experiments. It’s particularly useful with electronic sounds, but don’t let that stop you from trying it on any sound source you can think of. At its core, 

the Biscuit is a bitcrusher, but some clever additions extends its use far beyond that. 

It produces distortion by reducing the resolution and bandwidth of digital audio data. The resulting quantization noise can be varied from adding the familiar warm 8-bit character and lo-fi digital artifacts, to harsh numeric distortion. The “bitcrusher” section of the Biscuit is followed by an analog multimode filter (with low pass, high pass and band pass modes) and a simple mixing section (dry/wet). Furthermore, each of the eight data bits can be removed or inverted for more variation to the character, and there are four on-board digital effects—waveshaper, delay, pitch shifter and step filter. 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0006-07.png>)


**----- Start of picture text -----**<br>
Top Panel<br>Brain/Effects<br>Panel<br>**----- End of picture text -----**<br>



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0006-08.png>)


SOFTUBE USER’S GUIDE | **7** 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0007-01.png>)


**----- Start of picture text -----**<br>
Drive Naked Dressed Q<br>Bypass Clock Brain Freq Filter<br>LSB  Biscuiting  MSB<br>(Least Significant Bit) Switches (Most Significant Bit)<br>**----- End of picture text -----**<br>


## **Top Panel Controls** 

~~Drive Input gain knob. With a normalized signal gained above a certain level, the emulated~~ diode clipping will be noticeable in the audio-chain and the **Bypass** button will flash red. 

~~Naked Sets the amount of the dry signal mix, from silent up to 0 dB.~~ 

~~Dressed Te amount wet signal mix, from silent up to 0 dB.~~ 

~~Q Resonance of the multi mode flter~~ 

**8** | OTO BISCUIT 8-BIT EFFECTS 

~~Bypass Tis button bypasses~~ ~~**Biscuit when unlit** , green light means that Biscuit is active and~~ processing. The button flashes red to indicate that the emulate drive circuit is clipping. It is usually desired to have some clipping happening. 

~~Clock Sets the internal sample rate from 250 Hz up to 30 kHz. Changing the internal~~ sample rate introduces additional gritty sonic artifacts as side-effects. This is a very recognizable effect that can be heard on many records. ~~Brain Toggles the Efects section on and of and thereby engages the last selected efect~~ when lit. ~~Freq Cutof frequency of the multi mode flter Filter Sets the flter type. Its color indicates which type is selected:~~ Green: low pass Yellow: band pass Red: high pass. 

Biscuiting Switches ~~1-8 Tese switches mute or invert the 8 bits of audio stream through the Biscuit.~~ White (lit) means that the **Bit** is on Red means that the **Bit** is inverted Grey (unlit) indicates that the **Bit** is muted. 

Inverting or muting bits of data can result in very harsh and loud noise, please be careful. 

Inverting or muting the MSB (most significant bit), the bit furthest to the right, will result in more dramatic changes in sound, while doing the same to the LSB (least significant bit) yields more subtle results. 

Shift-clicking on a switch will change all switches to the same value at once. 

SOFTUBE USER’S GUIDE | **9** 

## **Brain/Effects Panel** 

Biscuit contains four different effects, of which one at a time can be used with the sample rate reduction, bit-crushing and analog filter: 

**1.** Wave shaping 

delay. Pitch shift your melodies to add chorus or harmonies, or use the step sequencer to add DAW synchronized filter movement on your sounds. 

The **Brain** button engages the last used effect when lit, and turns it off when unlit. The effect section can also be engaged by clicking on the desired effect button below the Effect Display. 

**2.** Delay 

**3.** Pitch shifting 

**4.** 8 step sequencer for the filter 

Use the wave shapers to transform your sound, from crazy distortion to sub-octave effects. Add a gentle lo-fi delay or a screaming 100% feedback 

Wave Shaper 

Pitch Shifter 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0009-12.png>)



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0009-13.png>)



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0009-14.png>)



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0009-15.png>)


Delay 

Step Filter 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0010-00.png>)


**----- Start of picture text -----**<br>
10  | OTO BISCUIT 8-BIT EFFECTS<br>Effect<br>Effects<br>Dependent<br>Display<br>Parameters<br>**----- End of picture text -----**<br>



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0010-01.png>)


**----- Start of picture text -----**<br>
Wave Delay Pitch Step DAW  Tempo<br>Tempo Tap<br>**----- End of picture text -----**<br>


~~Efect Display Shows the user information on the currently active efect and its related parameters~~ that are linked to the Effect Knobs to the right of the display. 

~~DAW Tempo Syncs the tempo to the DAW tempo for the Delay and Step Filter efects.~~ 

~~Tap Tempo Tapping this button sets the tempo for the Delay and Step Filter when~~ ~~**DAW**~~ **Tempo** button is disabled. 

~~Wave Turn on the Waveshaping mode~~ 

~~Delay Turn on the Delay mode~~ 

~~Pitch Turn on the Pitch Shifter~~ 

~~Step Turn on the Step Filter mode.~~ 

Each mode has one to four "soft parameters" that are specific for the different modes. For a description of those parameters, see the section corresponding to the effect mode. 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0011-00.png>)


## Wave 

The waveshaper effect can be used to distort, alter or dynamically track and filter your signal. Engage it by pressing **Wave** . 

~~Wave Type Select the 8 diferent wave~~ shapers. Shapers 1 to 5 will create distortion, shapers 6 to 8 synthesize a wave form. 

**1.** Rectifying: the negative parts of the incoming signal is inverted and added to the positive part. This creates an octave up effect similar to a fuzz octave pedal. 

**2.** Alternate Rectifying: only positive parts of the incoming signal is used. Creates a distorted "octave down" effect. 

**3.** Bat Fuzz: the input above a threshold gets folded. 

**4.** Biscuit: "Fifth down" effect with some additional crunchy distortion. 

**5.** Swap: Bits 1 to 4 are swapped with bits 5 to 8 creating some radical distortion with a lot of high harmonics. 

Waveshapers 6 to 8 in the Biscuit are small synthesizers, creating waveforms that track to the incoming signal frequency. These three waveshapers work best on bass synth sounds but can lead to exciting new sounds on other sources. 

To allow proper tracking, crank up the drive knob properly so that the bypass button shows red to obtain a stable sound. 

**6.** SawTOOTH: Tracking Sawtooth waveform. 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0011-12.png>)



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0011-13.png>)


**----- Start of picture text -----**<br>
Wave Type<br>VCF/ENF<br>**----- End of picture text -----**<br>



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0012-00.png>)


**7.** LO SAWTOOTH: Tracking Sawtooth waveform one octave down below source. 

1. Rectifying 

**8.** LO SQUARE: Tracking Square waveform one octave down. 

~~VCF/ENF Sets the amount of the en-~~ velop output that will affect the filter cutoff frequency. This effect is most apparent when lowering the cutoff frequency ( **Freq** knob) on upper panel. The **VCF/ENF** knob is only active in modes 6 to 8. 

2. Alternate Rectifying 

3. Bat Fuzz 

When using both the **Biscuiting** switches (bitcrusher) and **Wave Shapers** at the same time, it might be difficult to understand how these two effects interact. In order to have a better understanding of the **Wave Shapers** , we recommend to start using them with all the 8 bits in their normal state (all the 8 switches lit up white) at first. 

4. Biscuit 

5. Swap 

6. Saw Tooth (synthesized) 

7. Lo Saw Tooth (synthesized) 

8. Lo Square (synthesized) 

SOFTUBE USER’S GUIDE | **13** 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0013-01.png>)


**----- Start of picture text -----**<br>
Time<br>Feedback<br>Delay<br>Subdivision<br>**----- End of picture text -----**<br>


## Delay 

The delay effect in Biscuit is a 8-bit stereo delay as opposed to the original hardware mono operation. 

Only the delay will be heard via the **Dressed** Knob. This means that, if you want to hear both the source signal and the delayed echo at the same time, turn up the **Naked** and **Dressed** volume knobs accordingly. 

Sample rate reduction and filtering will only apply to the delayed signal in **Delay** mode. 

~~Time Sets the delay time of a quar-~~ ter-note in free running mode. It also controls the time of the Step Filter (see below) free running mode which is using the same internal clock. 

**Time** knob is disabled in DAW sync mode (as delay time is set automatically when **DAW Tempo** is lit). 

~~Feedback Sets the amount of feedback,~~ from 0% (one echo) to 100% (infinite build). 

~~Delay Subdivision Sets the subdivision of the~~ delay time into: 

quarter notes (preset), dotted quarter notes, eighth notes, dotted eighth notes, sixteenth notes, and dotted sixteenth notes. 

The actual delay time is show to the left in the effects display. 

**14** | OTO BISCUIT 8-BIT EFFECTS 

## Pitch 

The Pitch Shifter is a 8-bit mono effect that transposes the audio signal by using a short delay buffer and sends it to both left and right outputs via the **Dressed** knob. 

~~Shift Sets the amount of pitch shift through a number of presets, ranging from -2 octaves~~ up to +1 octave. 

You can either use the knob, or click directly on the dots on the displayed keyboard to change pitch. Middle C is for creating chorus-like effects by mixing the **Naked** and **Dressed** signals. Click twice on the lowest C to alternate between -1 octave and -2 octaves pitch shift. 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0014-05.png>)


**----- Start of picture text -----**<br>
Shift<br>**----- End of picture text -----**<br>



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0014-06.png>)



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0014-07.png>)


**----- Start of picture text -----**<br>
Shift<br>**----- End of picture text -----**<br>


In the original hardware the sample rate in the pitch shifter is fixed at maximum rate to obtain as good pitch shift effect as possible. 

Using both Biscuiting and sample rate reduction will make the pitch shifting algorithm work more like a pitch shifting delay, thus creating some cool effects not obtainable in the original hardware unit. 

SOFTUBE USER’S GUIDE | **15** 

## Step 

The Step Filter is an (up to) eight steps filter sequencer where each step can be set to have its own **Filter Type** , cut off **Frequency** and **Q** value. 

In Step Filter mode the effect display will show the BPM of the sequence related to division and/or DAW sync (if selected). 

Each step in the sequence is shown in the display represented by a bar and two dots. 

- The bar height represents the **Frequency** of the filter. 

- The bar color represents the **Filter Type** (green for LP, yellow for BP and red for HP) 

- The bar light intensity represents the **Q** value of the filter. 

- The top row of dots indicates the "song position", ie. which step in the sequence that is currently playing. 

- The bottom row of dots shows the currently selected step, the step that can be edited by adjusting the filter knobs. It also shows the total length of the sequence. 

You can click directly on the display to select current step and change filter **Frequency** . To set **Filter Type** and **Q** value per step, you need to use the knobs on the upper panel. 

A sequence can be 2, 3, 4, 6 or 8 steps long. 

## ~~Step Mode Sets any of the four playback~~ modes: 

**1.** Freeze: in this mode only the selected step is played. This is convenient for setting up the step's parameters ( **Frequency** , **Q** , **Filter Type** ) in detail. 

**2.** Forward: the sequence is played from left to 

right. 

**3.** Alternating: “pendulum”, sequence alternates between playing forward and backwards. 

**4.** Random: deterministic random, steps are played in random order. 

   - ~~Steps Te amount of active steps of~~ the sequence: 2, 3, 4, 6 or 8 steps long. Active steps are lit up and marked by white dots in the lower row beneath the display. Steps not active in the sequence are dimmed grey in the display. 

~~Select Step Select the step to be edited.~~ This can also be achieved by clicking in the display or on one of the rows of dots below the display. 

- ~~Speed Te speed division for each~~ step in the filter step sequencer. Default is that each step is a quarter note which corresponds well to BPM free running. 

When DAW sync is used division information (quarter, eighths, sixteenth and so on) is represented in the upper right corner in the effect display along with synced BPM. 

## Setting the Tempo in Free Running Mode 

When the **DAW Tempo** is inactive (unlit), the Step Filter is in a free running mode using the same internal clock as the free running delay. This means that you can set the tempo either by tapping 

**16** | OTO BISCUIT 8-BIT EFFECTS 

Frequency Select Step 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0016-02.png>)


**----- Start of picture text -----**<br>
Q<br>Freq Filter<br>Step Mode<br>Steps<br>Select Step<br>Speed<br>DAW  Tempo<br>Tempo Tap<br>**----- End of picture text -----**<br>


SOFTUBE USER’S GUIDE | **17** 

the **Tempo TAP** button or by adjusting the delay **Time** knob in the Delay effect. 

For an exact setting of tempo in the step filter, DAW sync is recommended. 

## **Linking Parameters** 

Some knobs and buttons have extra functionality (parameter linking) that can be accessed by shift clicking the knob/button. 

**Clock** knob: change the clock speed and filter cutoff simultaneously. 

**Naked** or **Dress** knobs: change both knobs at once with an inverse relationship to mirror that of a cross-fade operation. 

**Biscuit** switches (bit inverter/mute switch): change all Biscuit switches to the same value at once. 

Using pitch shift and clock rate reduction at the same time can create some interesting results not possible in hardware. 

By using clock rate reduction and high pass filtering of drums, nice additional hi-hat sounding parts can be created. 

Using a combination of the Swap wave shaper and the high pass filter mode can create nice additional high end “shakers” when applied to drum loops. 

## **Credits** 

**Björn Rödseth** – modeling. **Kim Larsson** – modeling. **Arvid Rosén** – modeling. **Kristofer Ulfves** – product owner, user manual, testing and presets. **Niklas Odelholm** – graphic design. **Paul Shyrinskykh** – quality assurance. **Ulf Ekelöf** – 3D rendering. 

**Freq** , **Q** or **Filter** in Step Mode: set all steps to the same value. This can be useful for example when you want to go from a complex sequence with a lot of different use filter modes to a simpler one. 

## **Tips** 

Mix the **Dressed** and **Naked** signals to achieve phased wave type sounds when sweeping cutoff and/or clock rate. 

Inverting and removing bits will cause more noticeable effects the more significant the bits are (that is, the further right the buttons are). 

When turning off or inverting the **MSB** , lowering the **Drive** level can act like a kind of a way to “gate” the signal and thereby dramatically alter the dynamics of the sound. Try it, you might like it! 

The step sequencer can also be used for “gating” sounds, such as pad, in sync with the DAW. Use LP mode and set **Freq** on the desired “silent” steps to 0. 

**18** | OTO BISCUIT 8-BIT EFFECTS 

| **19** 

## 2 

## General Settings 

Softube plug-ins are “what you see is what you get” products. You should be able to intuitively learn the products within minutes, so that you can work fast and efficient with them. There are a couple of things that remain the same for all of our plug-ins, such as the menu row. These will be explained in this chapter. For detailed information of a particular plug-in, please see its chapter. 

## **Menu Row** 

In the bottom of the plug-in interface, you will see a thin black row with some buttons. We’ll use the Chandler Limiter Zener Limiter plug-in as an example, but the same goes for all Softube plug-ins. 

~~Enable Enable/Activate the plug-in.~~ Set to off for bypass. 

~~Setup Changes global options for all~~ instances of that plug-in. 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0019-08.png>)



![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0019-09.png>)


## Enable 

~~About Box Opens the “About” Box with~~ version info. 

When the **Enable** switch is set to on (I), the plugin is active and will process audio. When set to off (0), it will be bypassed and not process any audio. 

~~Value Display Displays the knob value when~~ the mouse is hovering over a control. 

“About” Box 

Value Display 

Enable Setup 


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0019-17.png>)


**20** | GENERAL SETTINGS 

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


![](<OTO Biscuit 8-bit Effects Manual_assets/OTO_Biscuit_8-bit_Effects_Manual.pdf-0021-00.png>)


**Softube AB, S:t Larsgatan 9D, 582 24 Linköping, Sweden. www.softube.com** 

