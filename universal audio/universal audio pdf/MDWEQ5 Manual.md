---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/MDWEQ5 Manual.pdf
converted_at: 2026-06-03T09:25:03Z
tool: marker
tool_version: 1.10.2
word_count: 1734
---

# Massenburg DesignWorks®

![](<MDWEQ5 Manual_assets/_page_0_Figure_1.jpeg>)

## MDW®EQ5-UAD Parametric EQ

## Plug-in Guide

Version 1.0

![](<MDWEQ5 Manual_assets/_page_0_Picture_5.jpeg>)

#### Copyright Information

This guide is copyrighted ©2014 by Massenburg DesignWorks®, LLC (hereafter "MDW"), with all rights reserved. Under copyright laws, this guide may not be duplicated in whole or in part without the written consent of MDW. MDW, the MDW logo, and IsoPeak® are trademarks or registered trademarks of Massenburg DesignWorks, LLC. Universal Audio, the Universal Audio "diamond" logo, UAD, UAD Series, UAD-1, UAD-2, UAD-2 SOLO, UAD-2 DUO, UAD-2 QUAD, UAD-2 OCTO, "Powered Plug- Ins", 1176LN, 1176SE, Teletronix, LA-2A, LA-3A, LA- 610, LA-610MkII, 2-1176, 2-610, 6176, 710 Twin-Fin- ity, 2192, 4-710d, Cambridge EQ, DreamVerb, Plate 140, Precision Limiter, RealVerb Pro, Precision Buss Compressor, Precision De-Esser, Precision Maximizer, Satellite DUO, Satellite QUAD, Apollo, Apollo 16, Apollo Twin, and "Analog Ears | Digital Minds," are trademarks or registered trademarks of Universal Audio, Inc. Other company and product names mentioned herein are trademarks of their respective owners. All features and specifications subject to change without notice.

## Table of Contents

| Chapter 1. Introducing MDW®EQ-UAD<br>Introduction!<br>!<br>!<br>!<br>!<br>!<br>! | !<br>4  |
|----------------------------------------------------------------------------------|---------|
| Chapter 2. Using MDW®EQ-UAD                                                      |         |
| The MDW®EQ 5-Band Plug-In Window !!<br>!<br>!<br>!                               | !<br>5  |
| The MDW®EQ 3-Band Plug-In Window                                                 | 6       |
| MDW®EQ Controls!!<br>!<br>!<br>!<br>!<br>!                                       | !<br>7  |
| Adjusting MDW®EQ Parameters!<br>!<br>!<br>!<br>!                                 | !<br>8  |
| Copying and Pasting Band Parameters within a plug-in!<br>!<br>!                  | !<br>9  |
| Using ISO Peak® Mode!<br>!<br>!<br>!<br>!<br>!                                   | !<br>10 |

### Chapter 1: Getting Started with MDW®EQ5-UAD Parametric EQ

The Massenburg DesignWorks Hi-Res EQ (MDW®EQ) plug-in for UA systems was developed by a team led by the renowned recording engineer and producer George Massenburg. The MDW®EQ features internal double-precision 48-bit processing which provides unprecedented clarity and resolution, superlative smoothness, and excellent high-frequency response. Also, when working at 44.1 & 48kHz sampling rates, the MDW®EQ upsamples to 88.2 & 96kHz respectively to do all EQ processing, resulting in unprecedented high-frequency smoothness.

#### **Features**

- ◆ Double-precision 48-bit processing
- ◆ High-resolution processing, from 44.1kHz to 192kHz
- ◆ Industry standard, constant-shape reciprocal curves
- ◆ Selectable bands
- ◆ IsoPeak® function eases frequency selection
- ◆ Wide frequency selection from 10 Hz to 41 kHz
- ◆ Professional interface designed for speed and accuracy

#### The MDW®EQ 5-Band Plug-In Window

![](<MDWEQ5 Manual_assets/_page_4_Figure_2.jpeg>)

The Massenburg DesignWorks 5-Band High Resolution Equalizer has five independent filter bands connected in series. EQ Bands 1 - 4 can be individually set to one of seven filter types as follows:

- peak/dip
- high-frequency shelf
- low-frequency shelf
- high-pass 6 (6 dB/octave slope)
- low-pass 6 (6 dB/octave slope)
- high-pass 12 (12 dB/octave slope)
- low-pass 12 (12 dB/octave slope)

Filter Band 5 can be individually set to one of eleven filter types as follows:

- peak/dip
- high-frequency shelf
- low-frequency shelf
- high-pass 6 (6 dB/octave slope)
- low-pass 6 (6 dB/octave slope)
- high-pass 12 (12 dB/octave slope)
- low-pass 12 (12 dB/octave slope)
- high-pass 18 (18 dB/octave slope)
- low-pass 18 (18 dB/octave slope)
- high-pass 24 (24 dB/octave slope)
- low-pass 24 (24 dB/octave slope)

### The MDW®EQ 3-Band Plug-In Window

![](<MDWEQ5 Manual_assets/_page_5_Figure_1.jpeg>)

The Massenburg DesignWorks 3-Band High Resolution Equalizer has three independent filter bands connected in series. All EQ bands can be individually set to one of seven filter types as follows:

- peak/dip
- high-frequency shelf
- low-frequency shelf
- high-pass 6 (6 dB/octave slope)
- low-pass 6 (6 dB/octave slope)
- high-pass 12 (12 dB/octave slope)
- low-pass 12 (12 dB/octave slope)
- high-pass 18 (18 dB/octave slope) \* Band 3 Only
- low-pass 18 (18 dB/octave slope) \* Band 3 Only
- high-pass 24 (24 dB/octave slope) \* Band 3 Only
- low-pass 24 (24 dB/octave slope) \* Band 3 Only

A scalable display shows the overall EQ frequency response curve. All filter parameters can be independently automated.

## MDW®EQ5-UAD Controls

These controls let you edit the parameters of an MDW®EQ plug-in inserted on a track.

**Spectrum Display Scale -** Click and hold anywhere within spectrum display to view the Spectrum Display Scale pop-up menu and choose the desired vertical scale of the display. The available choices are ±6, ±12 or ±24 dB. Selecting a ±6 dB scale is useful for viewing more subtle equalizer adjustments. Changing the scale of the display has no effect on the equalizer's audio output.

**Power** - The Power button determines whether the EQ processing is active. The EQ is active when the Power button is engaged (blue), and bypassed when disengaged (grey). You can use this switch to compare the processed settings to that of the original signal.

**Input Attenuator – The Input Attenuator** adjusts the audio input to the plug-in from –24 dB to +6 dB. Drag or double-click and enter numerical data to adjust this parameter.

**Phase Reverse Switch –** Click the Phase Reverse button to reverse the absolute phase of the audio. If the EQ is linked to other channels, it will invert the phase of those as well - maintaining the phase relationship between them, but reversing their relationship to the audio in the rest of the session.

**Snapshot A/B Select** - The A & B snapshot feature allows you to compare two snapshot settings. Toggle between the two snapshots settings by pressing the A/B Snapshot Button.

**Copy Snapshot A->B (Copy Snapshot B->A)** While **Snapshot A** is selected you may duplicate all settings to **Snapshot B**.

**Filter Bands** Provide precise filtering of the audio signal in series. Filter type for each band is individually selectable.

**Frequency Selector** Sets the frequency of the selected filter band. Frequency range is from 10 Hz to 41 kHz.

**Filter Q Selector** Sets the Q of the Peak/Dip filter of the selected filter band .

**Cut/Boost** Provides up to ±24 dB of frequency cut or boost.

**Filter Type Selector** Provides a choice of high-pass (6 or 12 dB/oct), low-pass (6 or 12 dB/oct), highshelf, low-shelf, peak/dip, or bypass operation. For the MDW 5-Band EQ, Band 5 and Band 3 of the MDW 3-Band EQ offer additional filter choices which include high-pass 18 and high-pass 24 (18 or 24 dB/oct), and low-pass 18 and low-pass 24 (18 or 24 dB/oct).

**Filter In/Out – The In/Out button allows you** to switch a filter band on or off.

**IsoPeak®** - **IsoPeak®** provides a function in Peak/Dip filter mode whereby this band is soloed, and a sharp peak is temporarily set. Click on the colored band number button to initiate IsoPeak for that band. Click and hold on the background area of the band to reveal a pop-up menu allowing you to adjust the IsoPeak Q value..

**Band Pop-up Menu** - Click and hold on the background area of each band to reveal a pop-up menu allowing you to adjust the IsoPeak® Q value as well as the option to copy and paste individual band settings.

## Adjusting MDW® EQ Parameters

The best way to use MDW®EQ is to insert it on a track and adjust its parameters during playback to hear the changes in real time.

You can edit MDW®EQ knob parameters by dragging or by double-clicking and then typing a value into the knob's text display.

#### Editing Parameters with a Mouse

When using a mouse, MDW®EQ knob controls are adjusted by dragging horizontally or vertically. Values increase as you drag upward or to the right. Values decrease as you drag downward or to the left.

To edit a parameter with a mouse:

- **1** Begin audio playback so that you can hear parameter changes in real time.
- **2** From the Filter Type selector pop-up menu on the desired band, select the filter type.
- **3** Drag the parameter knob vertically or horizontally to adjust the parameters for the effect you want.

![](<MDWEQ5 Manual_assets/_page_7_Picture_9.jpeg>)

![](<MDWEQ5 Manual_assets/_page_7_Picture_10.jpeg>)

![](<MDWEQ5 Manual_assets/_page_7_Picture_11.jpeg>)

#### **Keyboard Shortcuts**

- For finer adjustments, Mac: Command-drag the control. Windows: Control-drag the control.
- To return a control to its default value, Mac: Option-click the control. Windows: Alt-click the control.

#### Editing Parameters with a Keyboard

Knob controls display their current value. You can edit this value by double-clicking and entering a value with your computer keyboard.

#### **To edit a parameter with a computer keyboard:**

- **1** Double-click the numerical text you want to edit.
- **2** Type the desired value. For negative values, type a minus sign in front of the number.
- or Press the Up Arrow on your keyboard to increase a value. Press the Down Arrow to decrease a value.

*Tips: In fields that support values in kilohertz, typing "k" after a number value will multiply the value by 1000. For example, type "1.2k" to enter a frequency of 1200 Hz.*

![](<MDWEQ5 Manual_assets/_page_8_Picture_1.jpeg>)

*Editing a control manually (after double-clicking)*

- **3** Press Enter on the numeric keyboard after typing a value to input the value without leaving the selected text box.
- or –

Press Return on the alpha keyboard to enter the value and leave keyboard editing mode.

## Copying and Pasting Band Parameters within a plug-in

To Copy Band Parameters

■ In the background of the band you wish to copy, click and hold down mouse button until pop-up appears. Then choose Copy band settings.

![](<MDWEQ5 Manual_assets/_page_8_Picture_9.jpeg>)

#### To Paste Band Parameters

■Click and hold anywhere on the background of the band you wish to paste. Then choose Paste band settings.

![](<MDWEQ5 Manual_assets/_page_9_Figure_0.jpeg>)

## Using ISO Peak® Mode

![](<MDWEQ5 Manual_assets/_page_9_Figure_2.jpeg>)

- **1** Choose a band on which to use IsoPeak® by clicking on the band number.
- **2** You'll hear only that band selected for IsoPeak® and only the absolute peak that the band generates (which will sound very narrow). The spectrum display will show that peak being monitoring.
- **3** The Q of this peak can be selected from the band's pop up menu (click and hold down the mouse button on the background of the band until the pop up appears). The default value is a Q of 8. !
- **4** "Sweep" the frequency listening to the effect of the peak boost to find the artifact or area of interest.
- **5** Click the band button to exit the IsoPeak® mode and return to normal operation. If you intend to remove a frequency, you'll now have to adjust the Q and the Boost/Cut, but your Frequency value will be that which you found sweeping in IsoPeak®.

**For More information please visit:** [www.massenburgdesignworks.com](http://www.massenburgdesignworks.com)

www.uaudio.com