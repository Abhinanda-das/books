---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Softube Vocoder Manual.pdf
converted_at: 2026-06-03T09:41:18Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 2916
---

# **SOFTUBE VOCODER** 

Rev. Sep 25, 2018 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0002-00.png>)


## **Softube User Manual** 

© 2007-2018. Amp Room, Softube are a registered trademarks of Softube AB, Sweden. Rock n’ Roll Scientists is a trademark of Softube AB, Sweden. All visual and aural references to Marshall, Super Lead, Plexi, 1959, Bluesbreaker, JMP 2203, Silver Jubilee 2555 and associated logos are trademarks of Marshall Amplification UK used under license. The Valley People Dyna-mite, Tonelux and Tilt are trademarks of PMI Audio used with written permission from PMI Audio. The Tonelux and Tilt logo, the Valley People, Dynamite and associated logos, are trademarks of PMI Audio Group, used under license. Summit Audio Inc. is a trademark by Baltic Latvian Universal Electronics, LLC, used under license. Chandler Limited and associated logos are trademarks of Chandler Limited used under license. Abbey Road Studios, EMI, TG, RS, Zener Limiter and their associated logos are trade marks of EMI (IP) Limited.  All specifications subject to change without notice. All Rights Reserved. 

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

|**1**|_Softube Vocoder_|_4_|
|---|---|---|
||Overview                                                                     5||
||Resynthesis Control|6|
||Carrier Synth|6|
||Unvoiced                                                                      7||
||Freeze section                                                              7||
||Output section                                                             7||
||Parameters|8|
||In Use/Tips & Tricks                                                     11||
||Shift-linking|13|
||Credits|13|
|**2**|_General Settings_|_14_|
||Menu Row                                                                 14||
||Key Commands|15|



**4** | 

## 1 

## Softube Vocoder 

The term vocoder is a portmanteau of voice encoder, a device originally developed by Bell Labs as part of a military device used for scrambling and encoding of voiced messages during World War II. A Vocoder usually consists of a transmitting, analysis part and a receiving, re-synthesis part. The signal input into the vocoder analyzer is called a modulator and the signal modulated in the re-synthesis part is called a carrier. The analyzer part breaks down the input signal to a number of frequency bands. Each analyzer band sends information about its state to a corresponding band in the re-synthesis part where this information is applied. 

SOFTUBE USER’S GUIDE | **5** 

This old military device was picked up by the music technology business in the late 60s and spawned a multitude of different hardware and software versions used and made famous by artists like Herbie Hancock, Jean-Michel Jarre, Phil Collins, Laurie Andersson and Africa Bambaataa just to name a few. 

In the Softube Vocoder, the input audio signal is the modulator which affects the built-in carrier synth which can be controlled via the on-screen chord keyboard or via MIDI. The intention with Softube Vocoder is to provide an easy-to-use, limited but yet flexible vocoder within the UAD-2/Apollo framework. 

## **Overview** 

The Softube Vocoder is an audio effect, designed to be controlled via a MIDI keyboard or by entering basic pitch information via the on-screen keyboard (and being able to transpose that via MIDI). Softube Vocoder listens to all MIDI channels at once (i.e. MIDI omni mode). The audio fed through the Vocoder will be interpreted to be the modulation signal while the carrier signal, the carrier synth sound source, is built into the plugin. 

**1.** Unvoiced 

**2.** Freeze section 

**3.** Output section 

**4.** Carrier synth 

**5.** Resynthesis control 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0005-10.png>)


**----- Start of picture text -----**<br>
1 2 3<br>**----- End of picture text -----**<br>



![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0005-11.png>)



![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0005-12.png>)


**----- Start of picture text -----**<br>
4<br>**----- End of picture text -----**<br>



![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0005-13.png>)


**----- Start of picture text -----**<br>
5<br>**----- End of picture text -----**<br>


**6** | SOFTUBE VOCODER 

## **Carrier Synth** 

This is the built in carrier sound source in Softube Vocoder. It is a six voice polyphonic synth that outputs one of four different waveform chosen for their rich harmonic spectra. The more overtones, the richer the output from the Vocoder will sound. The Waveforms are sawtooth, square wave, white noise and pulse wave with adjustable built in pulse width modulation. Each voice is controlled by an attack-hold-decay envelope and can also be pitch-modulated for additional vibrato. 

The Carrier Synth can be controlled polyphonically via MIDI or be set to hold one or multiple notes in the Transpose Chord mode (where MIDI can be used for transposition of chords). When controlled via MIDI, it receives MIDI notes on all channels (omni mode). 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0006-04.png>)


## **Resynthesis Control** 

The Resynthesis controls are the heart of the Softube Vocoder. This is where the user controls the levels of the separate bands of the bandpass filters that synthesize the speech. All bands also have common controls for emphasis (resonance) and shape of their envelope followers. 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0006-07.png>)


SOFTUBE USER’S GUIDE | **7** 

## **Unvoiced** 

The unvoiced section of the Softube Vocoder reacts to, and synthesizes high frequency plosive sounds such as “s”, “t”, “r”, “th” and similar sounds. The sensitivity knob controls the behavior of the high frequency filter and gate, while the volume knob sets the mix level of the synthesized noise that replaces the unvoiced parts in your speech. 

## **Freeze section** 

The Freeze section lets the user capture a particular syllable or vocal formant in the resynthesis filters and hold it. This can be done via MIDI or in sync with your DAW (every bar, 1/2 bar, 1/4[th] note, 8[th] note or 16[th] note). 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0007-05.png>)



![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0007-06.png>)


## **Output section** 

The Output section features controls of the stereo width, wet/dry mix and overall output volume. 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0007-09.png>)


| SOFTUBE VOCODER 

**8** 

## **Parameters** 

|**Pt**||||
|---|---|---|---|
|**arameers**|||~~Parallel Blend Tis knob controls the output~~<br>mix balance between the wet,|
|~~Unvoiced Sensitivity ~~|~~Tis knob controls the gate~~<br>level of the high frequency<br>detector for the unvoiced part.||vocoded signal, and a repre-<br>sentation of the dry, unafected<br>signal input. Use this knob|
||Adjust this knob in order to||to blend in some portion of|
||optimize the perfect transmis-||your original signal with the|
||sion of plosive sounds such as||vocoded signal. However, “dry|
||“s”, “t”, “th” and similar.||signal” here is not equal to|
||||the one bypass functionality|
|~~Unvoiced Volume ~~|~~Tis control sets the volume~~<br>mix level of the noise source<br>that is substituting the high||and will be out of phase (but<br>in phase with the Vocoded<br>signal).|
||frequency in sound and un-<br>voiced plosives in speech.||~~Output Volume Tis is the overall output~~<br>volume knob. Use this to|
|~~Freeze ~~|~~Te Freeze function makes the~~<br>Vocoder “sample” the current<br>frequency state of the analy-<br>sis flters. Tis can be done<br>manually (ON), via external||increase or reduce output<br>volume if desired or if sharp<br>transients that might occur<br>with high emphasis values clip<br>the output.|
||midi note on (MIDI) or auto-|||
||matically clocked by the DAW<br>tempo (1 bar / 1/2 bar / 1/4||~~Master Tune Te Master Tune knob~~<br>controls the nominal pitch|
||bar / 1/8 bar / 1/16 bar).||of the built-in carrier synth.|
||||With this knob at 12 o'clock,|
|Note: A saved preset with this function used to “capture”|||the carrier synth is tuned to a|
|a formant via ON only|will recall the “capturing behavior”||standard 440Hz for A4. Fully|
|not resulting formant|||counter-clockwise the pitch|
||||can be lowered 2 semitones|
|~~Stereo Width ~~|~~Tis knob sets the amount of~~||and fully clockwise raised 2<br>semitones.|



~~Stereo Width Tis knob sets the amount of~~ spread between the even and odd bands. Odd bands are panned right and even bands left to the extremes when this knob is turned fully clockwise. 

~~Carrier Octave Tis set of buttons controls the~~ octave register in which the notes entered on the keyboard in Transpose Chord Mode are played. 

Note: When using the mono version of the plugin, increasing the stereo width will have the side-effect that only even band will be heard 

SOFTUBE USER’S GUIDE | **9** 

~~Carrier Attack Te Carrier Attack knob~~ controls the attack/raise time in which the carrier synth responds when controlled over MIDI. The further clockwise this knob is set, the longer attack time. Fully clockwise, attack time will be approximately 4 seconds. 

~~Carrier Decay Te Carrier Decay knob~~ controls the decay/fall time in which the carrier synth responds when controlled over MIDI. The longer decay time, the longer the carrier synth notes will linger when a key on your MIDI control keyboard is released (whether this is heard or not depends of course on the input modulator signal). When this knob is set at fully clockwise, decay time will be approximately 4 seconds. 

~~Carrier Waveform Tese buttons set the carrier~~ synth waveform used, all of which are chosen for their harmonic-rich properties. The top one, the sawtooth shape contains all harmonic overtones, while the square wave only contain odd overtones in its harmonic spectra. The noise waveform contain all frequencies and is inharmonic by its nature. It works great as carrier for rhythmic content that is intended to remain inharmonic. 

The bottom waveform is a bit special. It is a narrow pulse wave with its pulsewidth modulated by a built in modulation. This modulation amount can be set by the PWM knob (see description below). 

~~Resynthesis Control Te Resynthesis window~~ shows all active bands and their response to the input signal in the vocoder. It also act as volume control for each band. Click on a band and drag up or down to increase or decrease the relative volume level of that band. The number of bands currently active will each be reflected in the Resynthesis Control window by a moving meter (except when freeze is engaged, see below). When fewer bands than 20 are selected via the Bands select buttons fewer moving meters will be present in the Resynthesis window (of course most obvious when only 4 bands are selected). 

~~Pitch Modulation Tis knob sets the amount~~ of fast pitch-modulation on the carrier synth, also called vibrato. 

## Transpose Chord 

is short for Pulse Width Modulation and this pulsewave's width is being swiftly modulated by an built in modulation. This knob sets the amount of this modulation. ~~Emphasis Emphasis is how steep the~~ response of each band in the Resynthesis part is. Increasing this knob makes the vocoder sound more hollow and “cold”. 

~~Mode Transpose Chord Mode is~~ activated by default. Transpose chord activates the on-screen keyboard where pitch can be entered to form the basis of the carrier synth sound. When midi information is entered above C3, the chord entered via on screen keyboard will be transposed accordingly. This means that the lowest note in that chord will be the root so that, for example, a C-minor chord (C-Ds-G) transposed by a E3 will play a E-minor chord, while a E-minor chord (E-G-B) transposed by the same offset, E3, will play a Gs-minor. Softube Vocoder uses last midi note high priority, which means that a MIDI note played after another takes priority if it is higher in pitch. ~~Keyboard C to B Tis is where the you enter~~ the pitch information for the Transpose Chord Mode. When more than six keys are entered, adding more keys will start to “cross out” the old keys indicating voices being stolen. This is due to the six voice limitation. ~~Carrier PWM Te bottom waveform that~~ can be selected by the Carrier Waveform buttons described above is a pulse-wave. PWM 

~~Spectral Tilt Tis knob is for swiftly setting~~ the spectral weight of the vocoder output. The Spectral Tilt knob goes from weight on low frequency bands at counter-clockwise to flat at 12 o'clock, to spectral weight on high frequency bands at fully clockwise. ~~Shape Tis is the envelope control of~~ the Resynthesis part. At fully counter-clockwise, the attack and decay both stay fairly short, while increasing this knob to fully clockwise gives a much longer response with an added “sloppy” effect. Great for vintage vocoding sounds! ~~Bands Tis is the number of bands~~ currently in use. The Bands buttons selects between 4,8,12,16 or 20 bands. Generally speaking, the more bands used, the easier it is to hear the vocal message conveyed through the vocoder. 

## **In Use/Tips & Tricks** 

The Softube Vocoder has been developed with a quite basic feature-set, but still with enough controls to make it flexible enough to cover all your vocoding needs. 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0011-02.png>)


**1.** Use fewer bands for a more crude, vintage robotic sounding vocoder. 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0011-04.png>)


**2.** Make use of the DAW synced freeze function for creating fun and inspiring textures. 

**12** | SOFTUBE VOCODER 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0012-01.png>)


**3.** Add the vocoder to process rhythmic material in order to create interesting textures in your slow synth-pads. 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0012-03.png>)


**4.** Use a vocoded noise mix with high emphasis to create a kind of tuned “pseudo-reverb”. 

SOFTUBE USER’S GUIDE | **13** 

## **Shift-linking** 

A handy feature when adjusting the bands in the Resynthesis window is the ability to link and adjust all bands at once. Simply press and hold down the shift-button while clicking on and adjusting a band to adjust them all! 

## **Credits** 

**Jacopo Lovatello** – modeling, **Björn Rödseth** – mentoring, modeling, **Kristofer Ulfves** – product owner, user manual, testing, presets, **Maxus Widarson** – testing, **Niklas Odelholm** – graphic design, **Ulf Ekelöf** – 3D rendering, **Fanny Hökars** – user manual layout. 

**14** | 

2 General Settings 

Softube plug-ins are “what you see is what you get” products. You should be able to intuitively learn the products within minutes, so that you can work fast and efficiently with them. There are a couple of things that remain the same for all of our plug-ins, such as the menu row. These will be explained in this chapter. For detailed information on a particular plug-in, please see its chapter. 

## **Menu Row** 

In the bottom of the plug-in interface, you will see a thin black row with some buttons. We’ll use the Dytronics Tri Stereo Chorus as an example, but the same goes for all Softube plug-ins. 

~~Enable Enable/Activate the plug-in.~~ Set to off for bypass. 

~~Setup Changes global options for all~~ instances of that plug-in. 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0014-07.png>)



![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0014-08.png>)


~~About Box Opens the “About” Box with~~ version info. 

~~Value Display Displays the knob value when~~ the mouse is hovering over a control. 

## Enable 

When the **Enable** switch is set to on (I), the plugin is active and will process audio. When set to off (0), it will be bypassed and not process any audio. 

“About” Box Value Display 

Enable Setup 


![](<Softube Vocoder Manual_assets/Softube_Vocoder_Manual.pdf-0014-15.png>)


**15** | GENERAL SETTINGS 

SOFTUBE USER’S GUIDE | **15** 

## Setup 

In the Setup window you can change settings that will affect all instances of that particular plug-in. If you, for example, deselect the “Show Value Display” option in the plug-in, the value display will be off for all instances of that plug-in on your system until you select that option again. 

The different options vary between Windows and Mac, and also different formats and plug-ins. The most common options are: 

Show Value Display: Enables the parameter and value display in the bottom row of the plug-in. 

Reverse Mouse Wheel Direction: (Mac OS Only) Changes if the a knob is turned up or down when the mouse wheel is turned up or down.  (Mac OS Only) 

You need to restart your host software (DAW) for the changes to fully take effect! 

If you messed something up and manually need to set these options, you’ll find them in text format in the following locations: 

Mac OS: ~/Library/Application Support/ Softube 

## **Key Commands** 

All numbers and labels in the plug-in are clickable. This allows you to easily select a setting by clicking on the wanted value. Hovering above a label will turn the mouse pointer into a pointing hand. 

## Mouse 

## Up/Down or 

~~Mouse Wheel Change a parameter, such as a~~ knob or a switch. 

## Keyboard 

~~Fine Adjust ⌘ (Mac) or Ctrl (Win),~~ while changing the parameter value. 

~~Reset to Default Alt, while clicking on the~~ knob or fader. 

~~Link Parameters Shift, while clicking on a~~ button or a knob. 

Windows: username\Application Data\ 

Softube AB, S:t Larsgatan 9D, 582 24 Linköping, Sweden. **www.softube.com** 

