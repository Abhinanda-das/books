---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Vertigo VSM-3 Manual.pdf
converted_at: 2026-06-03T09:19:13Z
tool: marker
tool_version: 1.10.2
word_count: 1405
---

![](<Vertigo VSM-3 Manual_assets/_page_0_Picture_0.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_0_Picture_1.jpeg>)

**The Vertigo Sound VSM-3 plugin is modeled faithfully by Brainworx after the VSM-2 a.k.a The Mix Satellite hardware by VERTIGO SOUND.**

*The basic idea and concept of the VSM-3*

The VSM-3 is a creative mix and mastering tool. The VSM-3 offers two sophisticated coloration generators, M/S processing, and unique controls for blending added harmonics in with the original signal.

## **The VSM-3 provides a bunch of tools for Recording, Mixing and Mastering**

- ü Fast input and output metering plus various level LEDs
- ü MS de- and encoding
- ü AFL Solo for M, S- and generator-signals
- ü Two independent stereo coloration circuits
- ü Stereo and M or S generation of pure 2nd and 3rd harmonics
- ü Coloration is independently switchable to M, S or LR
- ü Serial or parallel operation of generator units
- ü Cross-fade between 2nd and 3rd harmonics

You can "Crush or Blend" your master, "Search and Rescue" lost instruments or just enhance individual tracks like vocals, drums or whatever your creativity comes up with.

### **Differences between the hardware and the plug-in version**

The insert sections of the VSM-2 hardware have been replaced by two new modules, namely the "THD Mixer" and the "Monitoring" section. That's why we decided to call the plug-in emulation VSM-3. The new features are described in detail below.

#### **Meter reference levels**

A level of 0dBFS in the digital domain results in a readout of +22dBU on any of the peak program meters in the plug-in's user interface.

#### **Here's an overview of the various sections of the plug-in**

![](<Vertigo VSM-3 Manual_assets/_page_0_Figure_22.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_1_Picture_0.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_1_Picture_1.jpeg>)

#### *The Input*

Start with the Input Knob in the 12 o'clock position. You can use the Input pot to trim the stereo level for all following stages. The "Global System" switch is a bypass for all stages of the VSM-3 processing chain.

## *2nd Harmonic FET Crusher*

The tube sound is often subjectively described as having a "warmth" and "richness". It may be due to the nonlinear clipping that occurs with tube amps, or due to the higher levels of second-order harmonic distortion. The VSM-3 "FET Crusher" circuitry produces pure 2nd harmonics emulating a Class A and triode tube stage. This versatile coloration, saturation or distortion circuitry is adaptable, easily.

![](<Vertigo VSM-3 Manual_assets/_page_1_Picture_8.jpeg>)

#### **Here are the controls**

#### System In

With this switch the harmonic generator can be engaged or bypassed.

#### Drive

Sets the Input level or threshold to "What" and "How much" is going into the distortion stage. The Green / Red LED shows how much gain is used at the moment. If the LED is lighting red the distortion will produce quite a drastic effect on the music.

#### Input Filter

With the Input Filter you can define what frequency **range is passed** into the harmonic generator. See the table on the next page for the frequency range of each setting of the Input Filter. Note: "Track" mode is designed to process individual instruments. In this Mode the THD Mix control is disabled. The Shape control filters the output of the affected signal only. The original, or dry, portion of the signal is unaffected by the Shape control.

![](<Vertigo VSM-3 Manual_assets/_page_2_Picture_0.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_2_Figure_1.jpeg>)

| The filter modes |                   |
|------------------|-------------------|
| Low              | 10 Hz –<br>120 Hz |
| Mid              | 120 Hz –<br>1.5 k |
| HiMid            | 800 Hz –<br>4 k   |
| High             | 4 k –<br>20 k     |
| Full             | 120 –<br>20 k     |
| Track            | 10 Hz –<br>20 k   |

## LR and M or S Selector

This toggle switch defines if either LR, M or S is sent to the harmonic generator. (You can e.g. generate harmonics only onto the High frequencies of the S part of your program material). Note: This switch is grayed out when the plug-in is inserted on a mono track.

#### Shape

Shape is a Hi Cut filter designed to get rid of distortion byproducts and to prevent a harsh and gritty "too brilliant" result. Note: Shape hicuts the distortion band but leaves the frequency content of the dry signal unaffected (if THD Mix is used to blend in the dry signal)

#### THD Mix

This is a dry-wet control where you can mix between the unprocessed signal and the output of the harmonic generator.

#### Level

The "Level" pot is very important if you don't work in Full or Track

mode. With this level you can adjust a new level for the processed band similar to a multiband compressor. The left yellow LED shows the original level and the right LED the new level added.

#### Style

Here you can define the attitude and style of the harmonic generator. You can select a softer or harder characteristic. This is very similar to a hard or soft knee switch on a compressor. If you use a very high "Drive" (LED Red) both characteristics will sound more and more the

same because processing occurs outside the knee.

*3rd Harmonic Zener Blender*

The "Zener Blender" creates 3rd harmonics but will also generate some higher order odd harmonics depending on the amount of Drive. It is like driving a pentode into overload. The Zener circuitry makes things sound brighter, and brings out detail, adding a subtle compression or limiting effect.

![](<Vertigo VSM-3 Manual_assets/_page_3_Picture_0.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_3_Picture_1.jpeg>)

## **Operation Manual**

# The Vertigo Sound VSM-3

![](<Vertigo VSM-3 Manual_assets/_page_3_Picture_4.jpeg>)

#### Hint

All controls are identical to the 2<sup>nd</sup> harmonic generator. Please read the above description first (2<sup>nd</sup> Harmonic FET Crusher).

![](<Vertigo VSM-3 Manual_assets/_page_3_Picture_7.jpeg>)

#### THD Mixer

#### Parallel / Serial Switch

Set this switch to "Parallel" in order to make the two distortion units work in parallel. In this mode the blend between 2<sup>nd</sup> and 3<sup>rd</sup> harmonics

can be controlled using the "THD Mixer" pot (see below). Switching to "Serial" mode overrides the mix pot setting and routes the signal to the 2<sup>nd</sup> Harmonic stage first followed by the 3<sup>rd</sup> Harmonic stage.

#### **THD Mixer**

In parallel mode the "THD Mixer" allows you to control the balance between the signals generated by the 2<sup>nd</sup> Harmonic FET Crusher and the 3<sup>rd</sup> Harmonic Zener Blender. Turning the mix pot all the way to the left is equal to only having the 2<sup>nd</sup> Harmonic FET Crusher engaged while turning it all the way to the right equals only having the 3<sup>rd</sup>. The original VSM-2 hardware operated only in serial mode, and parallel mode is a plug-in only feature. In most cases, serial mode is recommended but feel free to experiment with parallel mode!

Harmonic Zener Blender engaged. Turn it to the 12 o'clock position to obtain a 50% mix of both signals. Again, the THD Mixer has no effect when the VSM-3 runs in serial mode

![](<Vertigo VSM-3 Manual_assets/_page_4_Picture_0.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_4_Picture_1.jpeg>)

## **Operation Manual**

# The Vertigo Sound VSM-3

![](<Vertigo VSM-3 Manual_assets/_page_4_Figure_4.jpeg>)

![](<Vertigo VSM-3 Manual_assets/_page_4_Figure_5.jpeg>)

## Monitoring section

#### MS Solo

The "MS Solo" switch allows you to monitor either the mid or the side signal of the MS encoded output of the plug-in. This can be especially useful when evaluating the coloration added by a unit that's put into M or S processing using its respective M/LR/S switch. Note: This function is disabled in mono instances of the plug-in.

#### **Distortion Solo**

Use the "Distortion Solo" switch to monitor the generator signal being added to the dry input signal of each stage by either the 2<sup>nd</sup> Harmonic FET Crusher or the 3<sup>rd</sup> Harmonic Zener Blender unit, or by both units.

## The Output

The Output section allows you to compensate for a gain cut or boost caused by your selected settings. You will want to apply the same gain to the left and right output channel in most situations. That's why we added a link switch in the plug-in version which can be toggled by clicking on the green LED between the two Output gain pots labeled "Link". Note: The link control is not accessible in mono instances of the plug-in.

#### **Presets**

We have added a variety of useful factory presets that may serve as a starting point if you're still learning how to use the VSM-3. Adjust Drive, Level and Shape to work best with your program material. Please keep in mind that the benefit of using distortion presets in M or S depends on your mix and its stereo balance.