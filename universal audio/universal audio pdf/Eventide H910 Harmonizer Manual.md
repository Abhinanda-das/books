---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Eventide H910 Harmonizer Manual.pdf
converted_at: 2026-06-03T10:05:13Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 2839
---


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0001-00.png>)



![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0001-01.png>)


**eventideaudio.com** 

**Original Marketing Material circa 1976** 

**eventideaudio.com** 

3 

## Model H910 Harmonizer[® ] 

## **Introduction** 

The H910 Harmonizer was pro audio’s first digital audio effects unit. The ability to manipulate time, pitch and feedback with just a few knobs and switches made it easy to alter audio in ways that otherwise required at least a couple of tape machines and, often, rearranging furniture. Suddenly anyone could be Les Paul (recording engineer not guitar player). 

The H910’s electronics were primitive and the processing almost entirely analog. The digital bits of the design did “as little as necessary.” Only delay was digital. Everything else - filtering, feedback, mixing, pitch modulation, etc. - was analog. And it sounded it. 

The H910 was also just a tiny bit unstable. And it showed. In a time long before CDs, MIDI, or any standards for sample rate or bits, Light Emitting Diodes (LEDs) had just become “the latest, greatest thing” and the H910’s iconic, flickering display was the first ‘digital readout’ to appear in many studios. And that flickering readout belied a secret – the H910 was inherently ‘jittery’. The H910’s master clock wasn’t crystal-based but, instead, it was a tuned LC (inductor/capacitor) oscillator. The result is that the system was not locked to a specific frequency and the entire system’s clocking would drift slightly, slowly and unpredictably. In fact, all of the oscillators in the H910 are of the ‘free-running’ sort and this randomness adds to the sound (and the fun). 

The H910 was groundbreaking when introduced and now the circuitry, the functionality and the ‘sonic behavior’ of the original has been modeled in software and is available in your DAW for the first time. Note that while presets are a good starting point, you’ll get the most out of the H910 if you push buttons and turn knobs - just as you would when searching for a sound using the hardware. That was always, and is now, once again, the fun of it. 

## **Genesis of the H910** 

Prior to 1970 there were no digital audio products of any kind, in any studio, anywhere. The first digital audio product to appear was a one-trick-pony, the DDL (Digital Delay Line). First introduced in 1971, DDLs from Eventide and Lexicon were as simple as simple can be - audio goes in now and comes out a bit later. Eventide’s 1745, was a big, costly box full of shift registers with a front panel dominated by big ‘wafer’ switches. Designed in 1972, during the very early days of ICs (Integrated Circuits), the only chips with enough memory (storage) to be dangerous/useful were 1K bit shift registers. RAMs were expensive and teeny. Each 1kbit shift register could delay audio by ~2 mS, so that, by filling a box with ‘only’ 100 of these chips an amazing 200 mS of delay became possible! 

Studios bought Eventide’s 1745 to use as a pre-delay for a plate reverb or for ADT (automatic double tracking). Eventide’s audio design sounded ‘good enough’ to satisfy even the most critical ears (some early digital audio products sounded awful) thanks, in large part, to Eventide’s custom designed ADC (analog to digital converter). And so, fueled by the sales of a handful of 1745s, Eventide took the next step and developed the successor to the 1745, the 1745M. The 1745M was also a simple DDL but it was modular DDL and used RAM instead of shift registers making fine control of delay possible for the first time. And it had 7 segment numerical LED readouts! The introduction of a “pitch change” module for the 1745M set the stage for the development of the H910. By 1974, most of the pieces needed to design a “Harmonizer” were in place. 

## **The Rack Mount H910** 

The H910 was conceived as a box that a vocalist might use to create real-time harmonies and reverb. In fact, the prototype sported a keyboard for selecting musical pitch intervals. (An optional keyboard controller was offered in production.) Much of the H910’s analog circuitry is borrowed from the DDLs. RAM storage was used for delay. By giving the user real time, interactive control of pitch, delay and feedback, the H910 ushered in the digital effects era and became a key instrument allowing engineers and producers to shape sounds in new ways. In a pre-software world, the H910 achieved its groundbreaking effects through the judicious application of analog circuitry, custom converters, and digital logic gates. 

## **The H910 Plug-in** 

This plug-in models the hardware to the best of our ability. It even emulates the randomness of the hardware (not that you can copy ‘random’ with any degree of exactitude). The controls have the same range and characteristics as the front panel controls of the hardware. The pitch change splicing method is the same as the hardware’s – the glitch is back! 

We’ve done exhaustive listening tests and compared it to the best relics that we could find. This plug-in models the quirkiness of one vintage H910. In fact, we’ve tweaked the plug-in to sound as close to the ‘golden’ relic as possible. (If this plugin sounds different from your H910, you may want to get your hardware adjusted.) 

## **eventideaudio.com** 

## Model H910 Harmonizer[® ] 

**H910 Controls** 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0004-03.png>)


The H910 user interface consists of two parts. The top half of the interface is the front panel of the original H910 2U rack mount unit. All controls function in the same way as the original.  The bottom half of the interface enables features originally available through external connections or options. 

**Front Panel Controls:** 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0004-06.png>)


**LINE button** : This control switches the Harmonizer in and out of an audio circuit. When the switch is in the OUT position, the unit is completely bypassed but the algorithm is still running in the background. This allows you to store audio in the feedback patch and modify its contents using the pitch controls, then to hear these differences when you revert to LINE IN. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0004-08.png>)


**INPUT LEVEL knob and LIMIT indicator** : This control varies the level of the audio input to the Harmonizer. Users of the original hardware would always be tweaking this pot! The plug-in models the hardware analog input audio circuitry of the H910 and, let’s just say that, the level of the input audio will change the effect of the other parameters, especially when making use of the feedback control.  We recommend that you play with this parameter and listen. 

**eventideaudio.com** 

5 

Model H910 Harmonizer[® ] 

Input Level should be adjusted to take advantage of the maximum dynamic range of the digital and analog circuitry by setting the control as far clockwise as possible before excessive distortion becomes apparent on the output signal. 

The LIMIT indicator is used as an aid in setting the INPUT LEVEL control. It is adjusted to give a brief flash each time the maximum dynamic range is even momentarily exceeded. 

## NOTE: 

Because the LIMIT indicator is peak responding, and because of the characteristics of the internal signal processing circuitry, it is desirable for the indicator to flash occasionally during normal operation. 

The amount of flashing is strongly dependent upon the nature of the input signal. As an aid to the operator, a general guide is provided: 

|<br>operator, a general guide is provided:||
|---|---|
|SIGNAL SOURCE|LIMIT INDICATOR DUTY CYCLE|
|Integrated program(radio)|once pertwo seconds|
|Integrated program (live)|once per second|
|Voice(talking)|onceper two seconds|
|Piano|2-3 persecond|
|Guitar, acoustic|2persecond|
|Guitar, fuzz|1 per second|
|Synthesizer|infrequent|
|Organ|infrequent|
|Drums|onceper beat|



Remember, the above is a general guideline! The ear is the best measuring instrument around, and the best setting is one at which the output level is maximum and distortion is not yet evident. 

Additionally right clicking on the INPUT knob will turn it to - dB, muting the input.  Right clicking again will toggle the INPUT knob back to its previous value. 

**eventideaudio.com** 

## Model H910 Harmonizer[® ] 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0006-02.png>)


## **DELAY ONLY button and LED:** 

This switch determines the mode of operation of the Harmonizer’s main output. When it is depressed, the pitch change function is defeated, and the Harmonizer acts strictly as a digital delay line. In this mode, the LED next to the DELAY ONLY button becomes illuminated and the legends beneath the ADD’L DELAY switch group become relevant. 

When the DELAY ONLY switch is in the out position, the LED adjacent to the PITCH CONTROL SELECT switch group becomes illuminated, and only the two right hand buttons in the ADD’L DELAY group are active. In this case, the legends above the switches are relevant. 

## **ADD'L DELAY switch group:** 

This switch group controls the delay of the main output. In the DELAY ONLY mode, the delay is the sum of the delays of the individual switches depressed, as read out on the bottom of the switch group. Maximum delay is 7.5+15+30+60 milliseconds (112.5 mS), and any intermediate setting can be achieved in 7.5ms steps by combining buttons. 

In the PITCH CHANGE mode, the additional delay is the sum of the delays of the two right hand switches depressed. Maximum additional delay is 60 mS (30+30). Note that in the PITCH CHANGE mode, pitch change is achieved by a delay that is continuously varying over an approximate 30 mS range, and so a precise delay is not achievable. So even without both ADD'L DELAY buttons pressed there will still be an audible delay when in PITCH CHANGE mode. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0006-09.png>)


**FEEDBACK knob:** The FEEDBACK control is used to add reverb in controlled amounts to the delayed output of the Harmonizer. The control attenuates the signal coming from the main output and reapplies it to the input where it is mixed with the incoming signal. The reverb period is controlled by the DELAY setting and the decay time is varied by adjustment of the FEEDBACK control. Clockwise rotation of the control increases decay time, until the feedback gain exceeds unity, at which time the system will begin to oscillate. The control is also operative in the PITCH CHANGE mode, and may be used to create numerous special effects. 

**eventideaudio.com** 

Model H910 Harmonizer[®] 

7 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0007-02.png>)


**PITCH RATIO readout:** An LED readout gives the numerical pitch ratio of the Harmonizer. As this is a true digital readout, it is not subject to miscalibration and may be used as a precise reference. 

For musical applications, our optional keyboard will allow setting to precise intervals automatically. These same intervals can be set using the readout, and referring to the chart showing PITCH RATIO READOUTS FOR VARIOUS MUSICAL RELATIONSHIPS. 

## **PITCH RATIO READOUTS FOR VARIOUS MUSICAL RELATIONSHIPS** 

The figures in this table are accurate to four decimal places. For use with the Model H910 Harmonizer, round off the figure two decimal places. 

|-3/4|-1/2|-1/4|NOTE|RELATIONSHIP|RELATIONSHIP|NOTE|+1/4|+1/2|+3/4|
|---|---|---|---|---|---|---|---|---|---|
|0.9576|0.9715|0.9857|1.0000|**UNISON**||1.0000|1.0145|1.0293|1.0443|
|0.9039|0.9170|0.9303|0.9439|-1|+1|1.0595|1.0749|1.0905|1.1064|
|0.8531|0.8655|0.8781|0.8909|-2|+2|1.1225|1.1388|1.1554|1.1722|
|0.8052|0.8170|0.8288|0.8409|-3|+3|1.1892|1.2065|1.2241|1.2419|
|0.7601|0.7711|0.7823|0.7937|-4|+4|1.2599|1.2782|1.2968|1.3157|
|0.7174|0.7278|0.7384|0.7492|-5|+5|1.3348|1.3543|1.3740|1.3939|
|0.6771|0.6870|0.6970|0.7071|-6|+6|1.4142|1.4348|1.4557|1.4768|
|0.6391|0.6484|0.6579|0.6674|-7|+7|1.4983|1.5201|1.5422|1.5646|
|0.6033|0.6120|0.6209|0.6300|-8|+8|1.5874|1.6105|1.6339|1.6577|
|0.5694|0.5777|0.5861|0.5946|-9|+9|1.6818|17063|1.7311|1.7563|
|0.5374|0.5453|0.5532|0.5621|-10|+10|1.7818|1.8077|1.8340|1.8607|
|0.5073|0.5147|0.5221|0.5297|-11|+11|1.8877|1.9152|1.9431|1.9713|
||||0.5000|**OCTAVE**||2.0000||||




![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0007-08.png>)


**OUTPUT 2 delay buttons:** This switch group controls the delay of the second output. It is operative regardless of the setting of the DELAY ONLY switch. Delay 2 is fed from the sum of the input to the H910 and the main feedback path.  Delay 2’s input is connected before the input to the pitch shifter 

**eventideaudio.com** 

Model H910 Harmonizer[®] 

8 

so pitch change at Delay 2's output will only be heard when feedback is turned up.  The total delay of Delay 2 is the sum of the buttons depressed. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0008-03.png>)


**MANUAL knob:** The MANUAL control is operative in the PITCH CHANGE mode only and when the PITCH CONTROL SELECT is set to MAN mode. It is used to change the pitch ratio between the input and the output. When centered, the ratio is unity. When fully clockwise, the ratio is 2, and the output pitch is increased by one octave. When fully counter-clockwise, the ratio is .5, and the output pitch is decreased by one octave. Intermediate settings produce fractional octave ratios, and the control is “band-spread” around unity to make small ratio adjustments easier. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0008-05.png>)


**PITCH CONTROL SELECT switch group and LED indicator:** When the PITCH CONTROL mode is activated, the LED INDICATOR immediately to the left of the PITCH CONTROL SELECT switch group becomes illuminated, and the four switches assume control of the pitch change function. 

- **Manual:** This switch selects the MANUAL control, as described above. 

- • **A-F:** Depressing the Anti-Feedback switch selects the ANTI-FEEDBACK control, as described below. 

• **KYBD:** Allows controlling the H910 Pitch Ratio using by the HK 941 ‘piano style’ keyboard and/or MIDI Note On/Off messages between C3 and C5. The HK 941 Keyboard is available in the bottom half of the H910 plug-in. 

• **ENV:** ENVELOPE FOLLOWER controls the pitch ratio.  When ENV is active, no input signal will result in a PITCH RATIO of 1.0 and a full scale input signal will set the PITCH RATIO according to the position of the MANUAL control.  In other words, the setting of the manual control determines the pitch range. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0008-10.png>)


**eventideaudio.com** 

Model H910 Harmonizer[®] 

**ANTI-FEEDBACK knob:** This control is operative in the PITCH CHANGE mode only, when the A-F button in the PITCH CONTROL SELECT group is depressed. Increasing clockwise rotation of the ANTI-FEEDBACK control progressively adds a small up and down frequency shift to the output signal, which serves to decrease the effect of room resonance peaks on the signal which ultimately rearrives at the microphone. Because the effect becomes more audible as the control is advanced, the optimum setting is a compromise between adequate feedback reduction and audience and/or performer disturbance.  At extreme settings this control will create a highly modulated FM like effect which can be used as a special effect. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0009-03.png>)


**POWER button and LED indicator:** The power button functions as the UA bypass switch.  When the POWER button is depressed the H910 plug-in is active.  Otherwise the button is not pressed and the DSP is unloaded. 

## **Additional Controls** 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0009-06.png>)


## **MIXER Section** 

**MIX slider:** This slider controls the relative level of the DRY signal and the WET signal comprised of the mixed MAIN OUTPUT and OUTPUT 2 based on their relative slider positions.  Right clicking on the MIX slider will activate a solo mode which will play the WET signal only.  Right clicking again will toggle back to the initial MIX position. 

**MAIN slider:** This slider controls the contribution of the MAIN output to the WET channel, whether it's set to PITCH CHANGE mode or DELAY ONLY mode.  Right clicking on the MAIN slider will enter a solo mode which plays only the MAIN output at full scale.  Right clicking again will toggle back to the original MIXER settings. 

**OUT 2 slider:** This slider controls the contribution of the delayed OUTPUT 2 signal to the WET channel.  Right clicking the OUT 2 slider will enter a solo mode which plays only the OUTPUT 2 signal at full scale.  Right clicking again will toggle back to the original MIXER settings. 

**eventideaudio.com** 

Model H910 Harmonizer[®] 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0010-02.png>)


## **ENVELOPE FOLLOWER Section** 

**ATTACK knob:** The ATTACK knob sets the ENVELOPE FOLLOWER's attack time from 1 to 100 mS. 

**RELEASE knob:** The RELEASE knob sets the ENVELOPE FOLLOWER's release time from 10 mS to 1 S. 

**SENSITIVITY knob:** The SENSITIVITY knob sets the gain of the ENVELOPE FOLLOWER allowing you to control the pitch change relative to the dynamics of the input signal.  As the SENSITIVITY knob is turned clockwise the ENVELOPE FOLLOWER will have more gain allowing quieter signals to have a greater control over the pitch change. 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0010-07.png>)


## **EVENTIDE HK941 Keyboard Section** 

**KEYBOARD:** The KEYBOARD is a two octave piano style keyboard.  The low C represents a PITCH RATIO of 0.5 representing a PITCH CHANGE of 1 octave down.  The middle C represents a PITCH RATIO of 1.0 representing a PITCH CHANGE of unison.  The high C represents a PITCH RATIO of 2.0 representing a PITCH CHANGE of 1 octave up.  Each other note represents a PITCH CHANGE equal to that number of semitones away from the middle C.  Therefore playing a note will allow you to transpose the input audio by the number of semitones selected by the note. 

**GLIDE slider:** The GLIDE slider allows you to set the speed at which the PITCH CHANGE amount will change when a new key is depressed.  This will allow you to add portamento to your transposition. 

**HOLD button and LED indicator:** If the HOLD button is depressed clicking on a key will lock the PITCH CHANGE to that number of semitones until another key is pressed.  Otherwise the PITCH CHANGE will reset to unison when you cease pressing the key. 

**eventideaudio.com** 

Model H910 Harmonizer[®] 


![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0011-01.png>)



![](<Eventide H910 Harmonizer Manual_assets/Eventide_H910_Harmonizer_Manual.pdf-0011-02.png>)


## Part #141252 Rev A 

Eventide Inc.  One Alsan Way  Little Ferry, NJ 07643  USA Eventide and Harmonizer are registered trademarks of Eventide Inc. © 2015 Eventide Inc. 

**eventideaudio.com** 

