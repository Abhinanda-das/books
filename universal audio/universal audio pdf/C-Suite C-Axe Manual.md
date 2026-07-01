---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/C-Suite C-Axe Manual.pdf
converted_at: 2026-06-03T10:48:42Z
tool: marker
tool_version: 1.10.2
word_count: 2626
---

![](<C-Suite C-Axe Manual_assets/_page_0_Picture_1.jpeg>)

# Guitar Noise Suppressor

This page left blank.

# Table Of Contents

| Getting Started              | 5  |
|------------------------------|----|
| The Problem                  | 6  |
| The Controls                 | 7  |
| The Display                  | 9  |
| Guitar Noise Reduction       | 11 |
| Licence and Limited Warranty | 12 |

This page left blank.

# 1

# Getting Started

Welcome to C-Suite Audio plug-ins. Working in collaboration with the Academy Award and Emmy winning developer CEDAR Audio, C-Suite provides world-class processes for Universal Audio users. C-Axe runs on all Universal Audio platforms and is available exclusively from Universal Audio.

# Installation

Please follow the usual installation procedure for your UA plug-ins.

# Automation

C-Axe can be automated in the usual fashion.

# Saving and reloading presets

You can save and load presets in the usual fashion.

# Contact and support

Should you experience difficulties with C-Axe, please contact Universal Audio with a precise description of the problem.

# The Problem 2

You know the problem... whether you're playing or recording guitar in your bedroom, on stage, in a home or small project studio, or even in a world-class facility, your performances can be marred by buzzes and hum. You can try to correct these problems using general purpose denoisers and EQ, but why not use a dedicated, zero-latency processor designed specifically to reduce or even eliminate them?

# The solution…

… is C-Axe. Designed as an in-line processor that can sit between your guitar and whatever follows, or as a post-processor that can clean up existing recordings, it will give your mix the best possible chance to shine.

![](<C-Suite C-Axe Manual_assets/_page_6_Picture_1.jpeg>)

# The Controls

![](<C-Suite C-Axe Manual_assets/_page_6_Picture_3.jpeg>)

### **50Hz/60Hz**

Choose 50Hz when the electrical mains frequency where you're playing or recording is 50Hz.

Choose 60Hz when the electrical mains frequency where you're playing or recording is 60Hz.

C-Axe will then detect the fundamental frequency of the buzz/hum and track this in the range ±1%.

![](<C-Suite C-Axe Manual_assets/_page_6_Picture_8.jpeg>)

### **Dynamic / Static / Learn**

Choosing Dynamic mode tells C-Axe that you want it to calculate the spectral distribution of the unwanted noise continuously. The process will calculate the fundamental frequency and the strengths of the harmonics, and allow you to attenuate them appropriately.

Choosing Learn tells C-Axe when to learn the spectral distribution of the unwanted noise. When you release this, the switch will select Static mode, and C-Axe will use the learned spectrum as the basis of the noise reduction. The measured spectral distribution won't be updated unless you Learn again or return to Dynamic mode.

![](<C-Suite C-Axe Manual_assets/_page_6_Picture_12.jpeg>)

# **Attenuation**

On most occasions, you will want to remove all of the noise. Unlike conventional dehissers and denoisers, C-Axe tends not to damage the wanted signal or create artefacts when processing at high values, so the default position for the Attenuation in 100%. If you would like to retain a little buzz or hum for a 'live' feel, or you feel that the sound is slightly over-processed, you can reduce the value to find the balance that you want.

![](<C-Suite C-Axe Manual_assets/_page_6_Picture_15.jpeg>)

## **Bypass**

Use this to bypass C-Axe's processing and make before/after comparisons.

# Shortcuts

The following shortcuts will speed your use and precision when using C-Axe.

| Mouse wheel                  | Turning the mouse wheel while hovering over the ATTEN knob<br>will modify the value.      |
|------------------------------|-------------------------------------------------------------------------------------------|
| SHIFT key                    | Holding SHIFT while dragging the ATTEN knob will adjust its<br>value in finer increments. |
| CTRL-click &<br>double-click | CTRL-left-clicking and double-left-clicking will reset the ATTEN<br>to its default value. |
| Cursor keys                  | Pressing the Right and Up keys will increase the ATTEN by 1.                              |
|                              | Pressing the Left and Down keys will decrease the ATTEN by 1.                             |
|                              | Pressing the Page Up key will increase the ATTEN by 5.                                    |

Pressing the Page Down key will decrease the ATTEN by 5.

![](<C-Suite C-Axe Manual_assets/_page_8_Picture_1.jpeg>)

Although the vertical (Y) axis represents signal amplitude and the horizontal (X) axis represents frequency, the C-Axe display is unconventional and it may not be immediately apparent what it represents.

Note that the area above the horizontal axis represents the first channel presented to the process, while the area below it represents the second. If a single channel is presented, the upper and lower areas will be mirror images of one another (simply because it looks nicer).

When processing is bypassed the display will be shown in grey.

# The display elements

![](<C-Suite C-Axe Manual_assets/_page_8_Figure_6.jpeg>)

The outer halo of the signal display shows the incoming signal spectrum.

The white line within this shows the spectrum of the calculated buzz/hum. In Dynamic mode this will be animated; in Static mode it will show a fixed spectrum.

The inner, more intense area shows the amount of buzz/hum reaching the output. With the Attenuation set to 100%, this should be a narrow line that shows that little or no audible noise is passing. As you decrease the Attenuation, this line will increase in width to indicate the increased amount of noise that is passing through the process.

The left-hand edge of the display shows the fundamental frequency of the buzz/hum, either in the range 50Hz ±1% or 60Hz ±1% as determined by the frequency switch. The intensity and width of the bright band at this edge represents the confidence with which the fundamental frequency has been identified. In most cases, this band will become whiter and wider over the course of a few seconds when you first present the signal to the process.

# History

The display shows a short history of the changes in the audio signal. The fainter the representation, the further in the past that it lies. The history is displayed for around 0.5s before the current moment; beyond this point, its intensity drops below 5% of the 'current' intensity.

# 5

# Guitar Noise Reduction

Two processing modes are provided. The difference between them is how C-Axe determines the spectral distribution of the components that comprise the buzz/hum.

# Dynamic mode

In Dynamic mode, C-Axe continuously tracks the fundamental frequency of the buzz/hum and the spectral distribution of the components within it. Use this mode when you can hear the buzz/hum for much or all of the duration of the signal to be cleaned.

To reduce the noise, select the electrical mains frequency in your area (or, if cleaning existing material, the location where the recording was made) and check that the Attenuation is set to its default value of 100%. This will be the correct setting in the majority of cases. If you feel that the sound is a little over-processed, or if you wish to retain a 'live' feel by allowing some of the noise to pass through the process, reduce the Attenuation to the value that feels most appropriate.

# Static mode

In Static mode, C-Axe continuously tracks the fundamental frequency of the buzz/hum; it will only calculate the spectral distribution when you ask it to do so. This allows you to determine a fixed amount of noise reduction. You should select it if the wanted signal often obscures the buzz/hum.

To reduce the noise, select the electrical mains frequency in your area (or, if cleaning existing material, the location where the recording was made) and set the Attenuation to 0% to pass the original signal to the output. Now select a period of music during which the noise is audible. While this is playing, move the mode switch to the Learn position. The noise estimate in the display will tend toward a steady shape. When you are happy that you have measured the noise correctly, allow the switch to return to the Static position.

Now increase the Attenuation to 100% so that the processed signal is sent to the output. This will be the correct setting in the majority of cases. You can reduce the Attenuation if you feel that the sound is a little over-processed or if you wish to retain a 'live' feel by allowing some of the noise to pass through the process.

![](<C-Suite C-Axe Manual_assets/_page_11_Picture_1.jpeg>)

# Licence and Limited Warranty

#### 1 DEFINITIONS

In this Licence and Limited Warranty the following words and phrases shall bear the following meanings:

'the Company' is CEDAR Audio Limited of 20 Home End, Fulbourn, Cambridge, CB21 5BS, UK; 'the System' means any instance of a C-Suite product developed by the Company; 'this Document' means this Licence and Limited Warranty.

#### 2. ISSUE AND USE OF THE SYSTEM

- 2.1 The terms and conditions of this Document are implicitly accepted by any person or body corporate who shall at any time use or have access to the System, and are effective from the date of supply of the System by CEDAR Audio Limited to its immediate customer.
- 2.2 The Company hereby grants to the Licensee and the Licensee agrees to accept a non-exclusive right to use the System.

#### 3. PROPERTY AND CONFIDENTIALITY

- 3.1 The System contains confidential information of the Company and all copyright, trade marks, trade names, styles and logos and other intellectual property rights in the System including all documentation and manuals relating thereto are the exclusive property of the Company. The Licensee acknowledges that all such rights are the property of the Company and shall not question or dispute the ownership of any such rights nor use or adopt any trading name or style similar to that of the Company.
- 3.2 The Licensee shall not attempt to reverse engineer, modify, copy, merge or transcribe the whole or any part of the System or any information or documentation relating thereto.
- 3.3 The Licensee shall take all reasonable steps to protect the confidential information and intellectual property rights of the Company.

#### 4. LIMITED WARRANTY AND POST-WARRANTY OBLIGATIONS

- 4.1 The Company warrants that the System will perform substantially in accordance with the appropriate section of its accompanying product manual for a period of one year from the date of supply to the Company's immediate customers.
- 4.2 The Company will make good at its own expenses by repair or replacement any defect or failure that develops in the System within one year of supply to the Company's immediate customer.
- 4.3 The Company shall have no liability to remedy any defect, failure, error or malfunction that arises as a result of any improper use, operation or neglect of the System, or any attempt to repair or modify the System by any person other than the Company or a person appointed with the Company's prior written consent.
- 4.4 In the case of any defect or failure in the System occurring more than twelve months after its supply to the Company's immediate customer the Company will at its option and for a reasonable fee make good such defect or failure by repair or replacement (at the option of the Company) subject to the faulty equipment having first been returned to the Company. The Company will use reasonable efforts to return repaired or replacement items promptly, all shipping, handling and insurance costs being for the account of the Licensee.
- 4.5 The above undertakings 4.1 to 4.4 are accepted by the Licensee in lieu of any other legal remedy in respect of any defect or failure occurring during the said period and of any other obligations or warranties expressed or implied including but not limited to the implied warranties of saleability and fitness for a specific purpose.
- 4.6 The Licensee hereby acknowledges and accepts that nothing in this Document shall impose upon the Company any obligation to repair or replace any item after a time when it is no longer produced or offered for supply by the Company or which the Company certifies has been superseded by a later version or has become obsolete.

#### 5. FORCE MAJEURE

The Company shall not be liable for any breach of its obligations hereunder resulting from causes beyond its reasonable control including, but not limited to, fires, strikes (of its own or other employees), insurrection or riots, embargoes, container shortages, wrecks or delays in transportation, inability to obtain supplies and raw materials, or requirements or regulations of any civil or military authority.

#### 6. WAIVER

The waiver by either party of a breach of the provisions hereof by the other shall not be construed as a waiver of any succeeding breach of the same or other provisions, nor shall any delay or omission on the part of either party to exercise any right that it may have under this Licence operate as a waiver of any breach or default by the other party.

#### 7. NOTICES

Any notices or instruction to be given hereunder shall be delivered or sent by first-class post to the other party, and shall be deemed to have been served (if delivered) at the time of delivery or (if sent by post) upon the expiration of seven days after posting.

#### 8. ASSIGNMENT AND SUB-LICENSING

The Licensee may at his discretion assign the System and in doing so shall assign this Licence its rights and obligations to the purchaser who shall without reservation agree to be bound by this Licence. The original Licensee and any subsequent Licensees shall be bound by the obligations of this Licence in perpetuity.

#### 9. LIMITATION OF LIABILITY

The Company's maximum liability under any claim including any claim in respect of infringement of the intellectual property rights of any third party shall be, at the option of the Company either:

- (a) return of a sum calculated as the price received for the System by the Company from its immediate customer depreciated on a straight line basis over a one year write-off period; or
- (b) repair or replacement of those components of the System that do not meet the warranties contained within this Document.

The foregoing states the entire liability of the Company to the Licensee.

#### 10. CONSEQUENTIAL LOSS

Even if the Company has been advised of the possibility of such damages, and notwithstanding anything else contained herein the Company shall under no event be liable to the Licensee or to any other persons for loss of profits or contracts or damage (whether direct or consequential) arising in connection with the System or any modification, variation or enhancement thereof and including any documentation or data provided by the Company or for any other indirect or consequential loss.

#### 11. ENTIRE AGREEMENT

The Company shall not be liable to the Licensee for any loss arising in connection with any representations, agreements, statements or undertakings made prior to the date of supply of the System to the Licensee.

#### 12. TERMINATION

This Licence may be terminated forthwith by the Company if the Licensee commits any material breach of any terms of this Licence. Forthwith upon such termination the Company shall have immediate right of access to the System for the purpose of removing it.

#### 13. SEVERABILITY

Notwithstanding that the whole or any part of any provision of this Document may prove to be illegal or unenforceable the other provisions of this Document and the remainder of the provision in question shall remain in full force and effect.

#### 14. HEADINGS

The headings to the Clauses are for ease of reference only and shall not affect the interpretation or construction of this Document.

#### 15. LAW

This Document shall be governed by and construed in accordance with English law and all disputes between the parties shall be determined in England in accordance with the Arbitration Act 1950 and 1979.

![](<C-Suite C-Axe Manual_assets/_page_13_Picture_1.jpeg>)

C-Suite Audio and CEDAR Audio Ltd, © 2022 C-Suite and C-Axe are trademarks of C-Suite and CEDAR Audio Ltd

Manual v1.00, 13 September 2022

*E&OE. Subject to revision at the Companies' sole discretion*