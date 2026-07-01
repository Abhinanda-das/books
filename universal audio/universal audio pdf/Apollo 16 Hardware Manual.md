---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Apollo 16 Hardware Manual.pdf
converted_at: 2026-06-03T06:39:38Z
tool: marker
tool_version: 1.10.2
word_count: 11127
---

![](<Apollo 16 Hardware Manual_assets/_page_0_Picture_0.jpeg>)

![](<Apollo 16 Hardware Manual_assets/_page_0_Picture_1.jpeg>)

# **Apollo 16 Hardware Manual**

Manual Version 180508

![](<Apollo 16 Hardware Manual_assets/_page_0_Picture_4.jpeg>)

# <span id="page-1-0"></span>**A Letter from Bill Putnam Jr.**

Thank you for deciding to make an Apollo High-Resolution Interface part of your music making experience. We know that any new piece of gear requires an investment of time and money — and our goal is to make your investment pay off. The fact that we get to play a part in your creative process is what makes our efforts meaningful, and we thank you for this.

In many ways, the Apollo family of audio interface products represent the best examples of what Universal Audio has stood for over its long history; from UA's original founding in the 1950s by my father, through our current vision of delivering the best of both analog and digital audio technologies.

Starting with its high-quality analog I/O, Apollo's superior sonic performance serves as its foundation. This is just the beginning however, as Apollo products are the only audio interfaces that allow you to run UAD plugins in real time. Want to monitor yourself through a Neve® console channel strip while tracking bass through a classic Fairchild or LA-2A compressor? Or how about tracking vocals through a Studer® tape machine with some added Lexicon® reverb?\* With our growing library of more than 90 UAD plug-ins, the choices are limitless.

At UA, we are dedicated to the idea that this powerful technology should ultimately serve the creative process — not be a barrier. These are the very ideals my father embodied as he invented audio equipment to solve problems in the studio. So as you begin to incorporate Apollo into your creative process, we hope that the excitement and pride that we've built into it comes through. We believe Apollo will earn its way into your creative workflow by providing stunning fidelity, great ease-of-use, and rock-solid reliability for years to come.

As always, please feel free to reach out to us via our website [www.uaudio.com](http://www.uaudio.com), and via our social media channels. We look forward to hearing from you, and thank you once again for choosing Universal Audio.

Sincerely,

Bill Putnam Jr.

*<sup>\*</sup>All trademarks are recognized as property of their respective owners. Individual UAD Powered Plug-Ins sold separately.*

# **Table Of Contents**

| A Letter from Bill Putnam Jr.      | i  |
|------------------------------------|----|
| Introduction                       | L  |
| What is Apollo 16?                 |    |
| Apollo 16 Features                 |    |
| About Realtime UAD Processing      | 7  |
| Combining with other UAD-2 devices |    |
| About Apollo 16 Documentation      |    |
| Technical Support                  |    |
| Front Panel                        | 10 |
| Rear Panel                         | 13 |
| Analog I/O                         |    |
| Digital I/O                        |    |
| Host I/O                           |    |
| Installation & Configuration       |    |
| System Requirements                |    |
| Software Installation              |    |
| Registration and Authorization     |    |
| System Configuration               |    |
| Multi-Unit Cascading               |    |
| Interconnections                   |    |
| Installation Notes                 |    |
| FireWire Basics                    |    |
|                                    |    |
| Digital Clocking Basics            |    |
| Specifications                     |    |
| Hardware Block Diagram             | 31 |
| DB25 Wiring                        | 32 |
| Troubleshooting                    | 33 |
| Notices                            | 34 |
| Important Safety Information       |    |
| Warranty                           |    |
| Maintenance                        | 35 |
| Repair Service                     | 35 |
| Index                              | 37 |

## <span id="page-3-0"></span>**Introduction**

### **What is Apollo 16?**

Apollo 16 is a high-resolution audio interface with Realtime UAD Processing onboard that gives recording engineers a no-compromise monitoring, tracking, and mixing solution. The combination of Apollo 16's high quality converters, cue mixing, and digital signal processing help you achieve the goal of making music without the common latency and potential processor shortcomings of an all-native system. Apollo 16 leverages Universal Audio's expertise in DSP acceleration, UAD Powered Plug-Ins, and analog hardware design by integrating the latest cutting edge technologies in high-performance A/D-D/A conversion, DSP signal reconstruction, and host connectivity. Apollo 16 acts as both an audio interface with integrated DSP effects for tracking and monitoring as well as a fully integrated UAD-2 DSP accelerator for mixing and mastering.

Apollo 16 has four SHARC™ DSPs for running UAD Powered Plug-Ins during tracking or mixing. You have an amazing sounding interface that can achieve the professional sound quality of any era in recording history by using UAD Powered Plug-Ins.

Apollo 16 uses FireWire or Thunderbolt for computer connectivity. FireWire 800 doubles the performance of FireWire 400 and ensures the ability to use all of Apollo 16's I/O as well as its DSP processing. Thunderbolt is a high-speed data transmission protocol that provides faster throughput than FireWire. The Thunderbolt Option Card (sold separately) can be easily installed in Apollo 16's expansion bay allowing Apollo 16 to connect with Thunderbolt-equipped computers.

To fully realize the low latency potential of Apollo 16, the Console application is included, providing a familiar analog mixing console interface where you can load your favorite combination of realtime UAD plug-ins. Configuring up to four unique cue mixes is quick and intuitive and you can also set up reverbs and delays (or any other UAD effects) on two auxiliary buses for comfortable tracking of live microphones and instruments.

Achieving deep integration of Apollo 16's features with your favorite audio workstation software is simple thanks to the Console Recall plug-in that is compatible with VST, Audio Units, RTAS, and AAX 64 host software. Simply place the Console Recall plug-in into any session and you have instant control over Apollo 16's monitoring options. A single "Sync" button on the plug-in will automatically recall the Console configuration within the DAW session without having to manage separate Console preset files, so you can be sure that the Console mix you are working with today will be accurately recalled tomorrow.

Done tracking? Use Apollo 16 just like any other UAD-2 device for mixing in the DAW. The full UAD Powered Plug-Ins library works with Apollo 16, offering the best analog emulation plug-ins available from the best companies in pro audio such as Neve, SSL, Pultec, Teletronix, Studer, Lexicon, DBX, MXR, Harrison, Empirical Labs, Manley, Ampex, and many more.\* A single button in the Console lets you decide to "print" or "monitor" Realtime UAD Processing – so if you want the sound of your favorite console and tape machine committed into your DAW, you can print those effects on the way in.

Quite simply, Apollo 16 delivers the sound, feel, and flow of analog recording with all the conveniences of modern digital equipment.

*\*All trademarks are recognized as property of their respective owners. Individual UAD Powered Plug-Ins sold separately.*

## <span id="page-4-0"></span>**Apollo 16 Features**

- Superior-sounding 18 x 20 audio interface with uncompromising UA analog design
- Realtime monitoring and tracking with premium UAD Powered Plug-Ins
- Additional mixing and mastering DSP horsepower for your sessions
- FireWire 800 built-in; user-installable Thunderbolt Option Card (sold separately)

### **Audio Interface**

- Sample rates up to 192 kHz at 24-bit word length
- 16 x 18 simultaneous analog input/output channels:
  - 16 channels of analog-to-digital conversion via line inputs on dual DB25 connectors
  - 18 channels of digital-to-analog conversion:
    - 16 line outputs via dual DB25 connectors
    - Stereo monitor outputs via dual XLR connectors
- Adjustable reference levels for all analog I/O (+4 dBu or -10 dBV)
- Two channels of AES/EBU digital I/O with optional sample rate conversion on input
- Front panel pre-fader metering of analog signal input or output levels
- Two FireWire 800 ports for daisy-chaining other FireWire devices
- Multiple Apollo 16 units can be cascaded for increased simultaneous I/O

### **Monitoring**

- Independently-addressable stereo monitor outputs (in addition to 16 line outputs)
- Digitally-controlled analog monitor outputs maintains highest fidelity
- Front panel control of monitor levels and muting
- Front panel pre-fader metering of monitor bus levels
- Digital AES/EBU outputs can be set to mirror the analog monitor outputs

### **UAD-2 QUAD Inside**

- Four SHARC DSP processors
- Realtime UAD Processing on all of Apollo 16's analog and AES/EBU inputs
- Same features and functionality as other UAD-2 products when used with DAW
- Can be combined with other UAD-2 devices for increased mixing DSP
- Includes UAD Powered Plug-Ins "Realtime Analog Classics Plus" bundle
- Complete UAD Powered Plug-Ins library is available online

### <span id="page-5-0"></span>**Software**

- Console application:
  - Enables Realtime UAD Processing
  - Controls Apollo 16's DSP mixer for realtime monitoring and/or tracking with UAD plug-ins
  - Four independent stereo Cue buses
  - Two independent stereo Auxiliary buses
  - Remote control of Apollo 16 features and functionality
- Console Recall plug-in:
  - Saves Apollo 16 configurations inside DAW sessions for easy recall
  - VST, RTAS, AAX 64, and Audio Units plug-in formats
- UAD Meter & Control Panel application:
  - Configures global UAD-2 and UAD Powered Plug-Ins settings and monitors system usage

### **Other**

- Easy firmware updates
- 1U rack-mountable form factor
- One year warranty includes parts and labor

### <span id="page-6-0"></span>**About Realtime UAD Processing**

Apollo 16 has the ability to run UAD Powered Plug-Ins in realtime. Apollo 16's groundbreaking DSP + FPGA technology enable UAD Powered Plug-Ins to run with latencies in the sub-2ms range, and multiple UAD plugins can be "stacked" in series without incurring additional latency. Realtime UAD Processing facilitates the ultimate sonic experience while monitoring and/or tracking.

*Note: Apollo 16, like other UAD-2 devices, can only load UAD Powered Plug-Ins which are specifically designed to run on UAD-2 DSP accelerators. "Native" plug-ins cannot run on the UAD-2 DSP.*

### **Console**

Realtime UAD Processing is a special function that is available only within the Console application. All of Apollo 16's analog and AES/EBU inputs can perform Realtime UAD processing simultaneously, and Console inputs with (or without) Realtime UAD Processing can be routed into the DAW for recording.

For complete details about Console and Realtime UAD Processing, refer to the Apollo Software Manual (see ["About Apollo 16 Documentation" on page 8\)](#page-7-1).

### **UAD plug-ins in the DAW**

UAD Powered Plug-Ins can also be used within the digital audio workstation without the use of Console. UAD Powered Plug-Ins loaded within the DAW operate like other (non-UAD) plug-ins, except the processing occurs on the Apollo 16 DSP instead of the host computer's processor. In this scenario, UAD plug-ins are subject to the latencies incurred by I/O buffering.

For complete details about using UAD Powered Plug-Ins in the DAW, refer to the UAD System Manual (see ["About Apollo 16 Documentation" on page 8\)](#page-7-1).

## **Combining with other UAD-2 devices**

<span id="page-6-1"></span>Apollo 16 can be used simultaneously with UAD-2 devices in the same host computer system. Apollo 16 simply adds to the DSP availability when used with other UAD-2 devices, increasing the DSP processing power so more UAD Powered Plug-Ins can be used. Up to six UAD-2 devices can be combined in the same system.

## <span id="page-7-1"></span><span id="page-7-0"></span>**About Apollo 16 Documentation**

Documentation for all Apollo 16 components is extensive, so instructions are separated by area of functionality, as detailed below. All documentation is copied to the computer during software installation. Documentation can also be downloaded from our website: [www.uaudio.com/support/manuals.html](http://www.uaudio.com/support/manuals.html)

*Note: All manuals are in PDF format. PDF files require a free PDF reader application such as Adobe Reader (Windows and Mac) or Preview (Mac).*

### **Apollo 16 Hardware Manual**

The Apollo 16 Hardware Manual contains complete information about the audio interface hardware. Included are detailed descriptions for all Apollo 16 hardware features, control functions, and connections. Refer to this hardware manual to learn about interfacing the hardware with other devices, operating the panel controls, clocking, specifications, and related information.

### <span id="page-7-2"></span>**Apollo Software Manual**

The Apollo Software Manual is the companion guide to the Apollo Hardware Manuals. It contains detailed information about how to configure and control the software features of all Apollo models using the Console application and Console Recall plug-in. Refer to the Apollo Software Manual to learn how to operate the software tools and integrate Apollo's audio interface functionality into the DAW environment.

*Note: Each Apollo connection protocol (Thunderbolt, FireWire, USB) has its own unique software manual.*

### **UAD System Manual**

The UAD System Manual is the complete operation manual for Apollo 16's UAD-2 functionality and applies to the entire UAD product line. It contains detailed information about installing and configuring UAD devices, the UAD Meter & Control Panel application, how to use UAD Powered Plug-Ins within a DAW, obtaining optional plug-in licenses at the UA online store, and more. It includes everything about UAD except Apollo-specific information and individual UAD Powered Plug-In descriptions.

### **UAD Plug-Ins Manual**

The features and functionality of all individual UAD Powered Plug-Ins is detailed in the UAD Plug-Ins Manual. Refer to this document to learn about the operation, controls, and user interface of each UAD plug-in that is developed by Universal Audio.

### **Direct Developer Plug-Ins**

UAD Powered Plug-Ins includes plug-ins from our Direct Developer partners. Documentation for these 3rd-party plug-ins are separate files that are written and provided by the plug-in developers themselves. The filenames for these plug-ins are the same as the plug-in title names.

### **Host DAW Documentation**

Each host DAW application has its own particular methods for configuring audio interfaces and using plug-ins. Refer to the host DAW company's documentation for specific instructions about using audio interface and plugin features within the DAW[.](http://www.uaudio.com/support)

## <span id="page-8-1"></span><span id="page-8-0"></span>**Technical Support**

### **UA Website & Knowledge Base**

The Universal Audio Knowledge Base is your complete technical resource for configuring, operating, and troubleshooting UA products.

You can watch helpful support videos, search the Knowledge Base for answers, find updated technical information that may not be available in other publications, and more.

• [help.uaudio.com](http://help.uaudio.com)

### **YouTube Support Channel**

The Universal Audio Support Channel at youtube.com includes helpful support videos for setting up and using UA products.

• [Universal Audio YouTube Support Channel](https://www.youtube.com/channel/UC0D0ABJ_HDBzifOvCaeKP5A)

### **UAD Community Forums**

The unofficial UAD discussion forums are a valuable resource for all Universal Audio product users. This website is independently owned and operated.

• [www.uadforum.com](http://uadforum.com/forum.php)

### **Contact UA Support**

Universal Audio provides free technical support to registered product owners. Support specialists are available to answer technical inquiries via email and telephone.

• [help.uaudio.com](http://help.uaudio.com)

## <span id="page-9-0"></span>**Front Panel**

This section describes the features and functionality of all controls and visual elements on the Apollo 16 front panel. Note that most front panel functions can be controlled remotely with the Console software application.

![](<Apollo 16 Hardware Manual_assets/_page_9_Picture_2.jpeg>)

### **(1) Meter**

The METER button determines which signals, either input or output, are displayed by the Channel Meters (4). Push the switch to toggle the meter display state between Input and Output. The current meter state is displayed by the METER indicators (2).

### **(2) Status Indicators**

These indicators display the status of the host computer connection, clock, and signal meters, as described below.

### *Host*

The HOST indicator displays the status of the connection to the host computer system. The indicator is illuminated when Apollo 16 is connected to, and properly communicating with, the host computer system via FireWire or Thunderbolt. The indicator is off when the host computer is not detected.

The Apollo 16 software must be properly installed and configured on the host computer to enable communication, and the HOST indicator must be illuminated to use Apollo 16 with all computer operations. The only time the HOST link is not required is when Apollo 16 is used without a computer (see ["" on page 7\)](#page-6-1).

### *Clock*

The CLOCK indicator displays the status of the Apollo 16 clock. When Apollo 16 is using its internal clock as the master clock source, the INT indicator is illuminated.

When Apollo 16 is set to use an external clock as the master clock source and a valid clock signal is detected at the specified port, the EXT indicator is illuminated and white.

If the EXT indicator is illuminated and red, Apollo 16 is configured to use an external clock but it cannot lock to the specified source, and the internal clock remains active instead. In this situation, if/when the specified external clock becomes available, Apollo 16 switches back to the external clock, and the EXT indicator is illuminated and white.

*Note: Apollo 16 can be configured to use its internal clock, or an external clock from the Word Clock or AES/EBU inputs. The clock setting is configured in the Interface panel of the Console Settings window; see the Apollo Software Manual for details.*

### <span id="page-10-0"></span>*Meter*

The METER indicator reflects the state of the Channel Meters (4). The I/O state of the Channel Meters is switched with the METER button (1).

When IN is illuminated, the Channel Meters display levels at the analog inputs. When OUT is illuminated, the Channel Meters display levels at the analog outputs.

### **(3) Sample Rate Indicators**

The Apollo 16 sample rate is indicated in this area. The active sample rate is illuminated.

### **(4) Channel Meters**

The sixteen 10-segment LED meters display the signal peak levels for analog channels 1 – 16. The Channel Meters can display either the input or output levels, as determined by the METER button (1).

Signal levels are displayed at the input to the A/D converters (IN mode) or the output of the D/A converters (OUT mode). The dB values of the meter LEDs are indicated between the meters for channels 4 & 5 and 12 & 13.

"0" indicates a level of 0 dBFS. When digital clipping occurs, the red "C" LED illuminates. Avoid digital clipping at the channel's A/D converter by reducing the channel's level at its source.

### **(5) Power Indicator (UA Logo)**

The Universal Audio logo illuminates when the external power supply is properly connected to an AC outlet and the power input on the rear of the unit, and the POWER switch (9) is in the up position.

### **(6) Monitor Output Level Meters**

These dual 10-segment LED meters display the signal peak output levels for the monitor outputs at the output of the D/A converters. These meters are before the Monitor Level control (pre-fader) and reflect the D/A converter levels regardless of the current Monitor Level knob setting (7).

The dB values of the monitor meter LEDs are indicated between the left and right channel meters. "0" indicates a level of 0 dBFS. When digital clipping occurs, the red "C" LED illuminates. Avoid clipping at the monitor D/A converters by reducing the monitor bus output level and/or the channels feeding the monitor output bus.

### **(7) Monitor Level and Mute Knob**

This "endless" rotary encoder serves two functions. Rotating the knob adjusts the monitor output level, and pushing the knob mutes the monitor outputs, as described below.

### *Monitor Level*

The control knob adjusts the signal level at monitor outputs on the rear panel. Although this is a digital control, the monitor volume is attenuated in the analog domain, after D/A conversion (digitally-controlled analog volume). This method provides the utmost monitoring fidelity, in contrast to digital volume controls that reduce levels by truncating the word length ("dropping bits"). The available range is from -INF dBFS (no output) to 0 dBFS.

### <span id="page-11-0"></span>*Monitor Mute*

Pushing the Monitor knob toggles the mute state of the signals at monitor outputs on the rear panel. When the monitor outputs are muted, the Monitor Level Indicator (8) is red. When the monitor outputs are not muted, the Monitor Level Indicator is green.

### **(8) Monitor Level Indicator**

The signal level at the rear panel monitor outputs is displayed with the illuminated indicator ring surrounding the Monitor Level knob (7). The ring is green when the monitor outputs are active, and red when the monitor outputs are muted. This level indicator is after the Monitor Level control (post fader).

*Note: This feature indicates relative levels only and is not calibrated to any specific dB values.*

### **(9) Power Switch**

This switch applies power to Apollo 16. When the unit is powered on, the Universal Audio logo is illuminated. The external power supply must be properly connected for this switch to function.

As with any sound system, to avoid audio spikes in your speakers, the following steps are recommended:

- Apply power to the speakers last, after all other devices (including Apollo 16) are powered on.
- Turn off the speakers first, before all other devices (including Apollo 16) are powered off.

## <span id="page-12-0"></span>**Rear Panel**

This section describes the features and functionality of all connectors and controls on the Apollo 16 rear panel.

### **Analog I/O**

![](<Apollo 16 Hardware Manual_assets/_page_12_Picture_3.jpeg>)

### **(1) Monitor Outputs 1 & 2**

These balanced XLR jacks are line-level analog outputs typically used for connection to a stereo loudspeaker monitoring system. The signal levels at these outputs are controlled with the Monitor Level knob (7).

The Monitor Outputs can be configured to use an operating level of 14 dBu or 20 dBu. This option is set in the Hardware panel within the Console Settings window.

The Monitor Outputs are completely independent from the 16 analog line outputs. By default, the "1–2" or "Main" outputs from a DAW are routed to these outputs. Stereo panning of input signals routed to these outputs is defined within the Console and/or DAW applications.

*NOTE: The AES/ABU outputs can be configured to mirror the Monitor Outputs. See ["\(8\) AES/EBU Ports"](#page-14-0)  [on page 15](#page-14-0) for details.*

### **(2) Line Outputs 1 – 16**

The 16 analog outputs are accessed via dual female DB25 connectors. Each DB25 jack carries eight balanced line-level channel outputs using standardized Tascam wiring.

The Line Outputs can be configured in adjacent pairs to use -10 dBV or +4 dBu reference levels. This function is configured in the Outputs panel of the Console Settings window in the Console application.

### **(3) Line Inputs 1 – 16**

The 16 analog inputs are accessed via dual female DB25 connectors. Each DB25 jack carries eight balanced line-level channel inputs using standardized Tascam pinouts.

The Line Inputs can be configured to use -10 dBV or +4 dBu reference levels. This function is configured within the input channel strips in the Console application.

*Note: See ["DB25 Wiring" on page 32](#page-31-1) for DB25 connector pinout diagrams.*

### <span id="page-13-0"></span>**(4) Power Input**

The included 80-watt external power supply plugs into this 4-pin locking XLR jack. Apollo 16 requires 12 volts DC power and draws approximately 40 watts. During typical operation when a bus-powered Thunderbolt peripheral is attached to the Thunderbolt Option Card, the system can draw up to 55 watts.

To eliminate risk of circuit damage, connect only the factory-supplied power supply. Use the Power switch on the front panel to power the unit on and off.

*Important: Do not disconnect the power supply while Apollo 16 is in use, and confirm the Power switch is in the "off" position before connecting or disconnecting the power supply.*

### **Digital I/O**

![](<Apollo 16 Hardware Manual_assets/_page_13_Figure_5.jpeg>)

### **(5) Word Clock Out**

This BNC connector transmits a standard (1x) word clock when Apollo 16 is set to use its internal clock. The clock rate sent by this port matches the current system sample rate, as specified in the Interface panel of the Console Settings window within the Console application.

When Apollo 16 is set to use external word clock as its clock, Apollo 16 is a word clock slave. If the incoming external word clock is within ±0.5% of a supported sample rate (44.1 kHz, 48 kHz, 88.2 kHz, 96 kHz, 176.4 kHz, 192 kHz), Word Clock Out will mirror Word Clock In with a slight phase delay (about 40ns).

### **(6) Word Clock In**

Apollo 16's internal clock can be synchronized (slaved) to an external master word clock. This is accomplished by setting Apollo 16's clock source to Word Clock in the Interface panel of the Console Settings window within the Console application, connecting the external word clock's BNC connector to Apollo 16's word clock input, and setting the external device to transmit word clock. If Apollo 16 is the last device in the clock chain, the Termination switch (7) should be engaged.

*Note: Apollo 16 can be synchronized to an external "1x" clock signal only. Superclock, overclocking, and subclocking are not supported.*

### <span id="page-14-1"></span>**(7) 75 Ohm Word Clock Termination Switch**

This pushbutton switch provides internal 75-ohm word clock input signal termination when required. Word clock termination is active when the switch is engaged (depressed).

Apollo 16's termination switch should only be engaged when Apollo 16 is set to sync to external word clock and it is the last device at the receiving end of a word clock cable. For example, if Apollo 16 is the last "slave" unit at the end of a clock chain (when Apollo 16's word clock out port is not used), termination should be active.

*Note: For more information, see ["Digital Clocking Basics" on page 26.](#page-25-1)*

### <span id="page-14-0"></span>**(8) AES/EBU Ports**

The AES/EBU ports provide two channels of digital I/O with resolutions up to 192 kHz via XLR connectors. For optimum results, use only high-quality 110-ohm XLR cables specifically designed for AES/EBU digital audio.

### *SR Convert*

Sample rate conversion can be enabled on the AES/EBU input. This function is set in the AES/EBU input channel strips in the Console application. When sample rate conversion is enabled and the sample rate of the incoming AES/EBU signal does not match the sample rate specified in the Console application, the AES/EBU signal is converted to match Apollo 16's sample rate.

*Note: When Apollo 16 is set to use AES/EBU as the master clock source, sample rate conversion is inactive.*

### *Mirror Monitor Outputs*

The AES/EBU output can be configured to mirror the Monitor outputs, for routing the stereo Monitor signal to the stereo AES/EBU input of other devices. This function is configured in the Interface panel of the Console Settings window in the Console application.

### <span id="page-15-0"></span>**Host I/O**

*Important: Connect only one Apollo 16 FireWire or Thunderbolt port to the host computer.*

### **(9) Expansion Bay**

The expansion bay is where the Universal Audio Thunderbolt Option Card is installed, providing access to all of Apollo 16's features and functionality via Thunderbolt-equipped computers.

Refer to the Installation & Setup Guide included in the Thunderbolt Option Card package and our website for complete details about installation, configuration, and use of Thunderbolt with Apollo 16.

### **(10) FireWire 800 Ports**

Apollo 16 uses FireWire to communicate with the host computer system when the Thunderbolt Option Card is not in use. When Apollo 16 is properly connected and configured, the HOST indicator (#2 on front panel) is illuminated.

Apollo 16 has two FireWire 800 ports. Only one port is used to connect to the host computer; the second port can be used for daisy-chaining multiple FireWire devices such as external FireWire hard drives. For more FireWire information and recommended interconnections, see [""FireWire Basics" on page 22.](#page-21-1)

*Note: Apollo 16 cannot be bus powered and it does not supply bus power from its FireWire ports to other devices.*

### **(11) MADI Optical Ports**

The MADI I/O ports use the MADI (Multichannel Audio Digital Interface) optical protocol for Apollo 16 interconnections. The MADI ports relay the Monitor, Cue, and Auxiliary buses between two Apollo 16 units when multiunit cascading via FireWire for increased simultaneous I/O.

*Note: The MADI ports support Apollo 16 interconnections when multi-unit cascading via FireWire only. Connections to other MADI devices is not supported.*

# <span id="page-16-0"></span>**Installation & Configuration**

*Note: Items on this page are detailed in the Apollo Software Manual (see ["About Apollo 16 Documen](#page-7-1)[tation" on page 8](#page-7-1)).*

### **System Requirements**

All system requirements must be met for Apollo 16 to operate properly. Before proceeding with installation, see the system requirements in the Apollo Software Manual.

### **Software Installation**

The software must be installed to use the hardware and UAD plug-ins. The UAD Powered Plug-Ins software installer contains the Apollo 16 software and drivers.

To obtain the latest UAD Powered Plug-Ins software installer, visit:

• [www.uaudio.com/downloads](http://www.uaudio.com/downloads)

### **Registration and Authorization**

Apollo 16 must be registered and authorized at my.uaudio.com to unlock UAD plug-ins that are bundled with the product. Registration and authorization via a web browser is triggered automatically by the UAD software the first time the device is connected.

## **System Configuration**

Complete details about setting up the Apollo 16 system, including how to integrate with a DAW and related information, are included in the Apollo Software Manual.

## **Console Application**

The included Console application is the software interface for the Apollo 16 hardware. Console controls Apollo 16 and its digital mixing, monitoring, and Realtime UAD Processing features. Console is also used to configure Apollo 16's I/O settings such as sample rate, clock source, and reference levels.

For complete details about how to operate Console, refer to the Apollo Software Manual.

## **Multi-Unit Cascading**

When more I/O and/or DSP is needed, two Apollo 16's can be cascaded together via FireWire in a multiple-unit configuration. For examples, see ["Interconnections" beginning on page 18.](#page-17-1) For complete details about multiunit cascading, refer to the Apollo Software Manual.

*Note: Up to for Apollo interfaces can be cascaded together with Apollo Expanded v8 software if all Apollo units are connected via Thunderbolt. See www.uaudio.com/support/thunderbolt for complete details.*

### <span id="page-17-1"></span><span id="page-17-0"></span>**Installation Notes**

- 1. Apollo 16 may get hot during normal operation if it doesn't receive adequate airflow circulation around its chassis vents. For optimum results when mounting Apollo 16 in a rack, we recommend leaving at least one empty rack space above the unit to allow adequate airflow for cooling.
- 2. As with any sound system, to avoid audio spikes in your speakers, the following steps are recommended:
  - Apply power to the speakers last, after all other devices (including Apollo 16) are powered on.
  - Turn off the speakers first, before all other devices (including Apollo 16) are powered off.

### **Typical Setup**

This diagram illustrates a basic Apollo 16 system. In this example, only analog devices are connected; digital I/O is not used.

#### *Key points for this example:*

- Either FireWire port can be used for the host computer connection
- The Monitor outputs are connected to powered monitors (or an amp+speaker system)
- DB25 audio snakes are used for connections to line-level audio gear
- Although this example uses XLR connectors, DB25 snakes that terminate to XLR, TRS, or other DB25 connectors can be used

![](<Apollo 16 Hardware Manual_assets/_page_17_Picture_13.jpeg>)

### <span id="page-18-1"></span><span id="page-18-0"></span>**Thunderbolt Setup**

This diagram illustrates how Apollo 16 can be connected to a host computer with the Thunderbolt Option Card.

#### *Key points for this example:*

- The Thunderbolt Option Card (not included) must be installed in Apollo 16 to connect via Thunderbolt
- Either Thunderbolt port can be used for the host computer connection
- Monitors with AES/EBU input are connected to AES/EBU output
- The "AES/EBU Mirrors Monitor 1-2" option is enabled in Console Settings so Apollo 16's front panel MONITOR knob can control the volume level of the speakers with AES/EBU input

*Note: The FireWire ports are disabled with Apollo Thunderbolt software.*

![](<Apollo 16 Hardware Manual_assets/_page_18_Picture_8.jpeg>)

### <span id="page-19-0"></span>**Multi-Unit Cascading Setup – FireWire Host Connection**

This diagram illustrates how two Apollo 16 units are connected together into an aggregated interface for 32 simultaneous analog inputs and 32 simultaneous analog outputs using FireWire 800 to connect to the host computer.

*Important: For complete details about system operation when multi-unit cascading, see the [Apollo](#page-7-2)  [Software Manual.](#page-7-2)*

### *Cables Required:*

- One FireWire 800 cable for connecting to the host computer
- One FireWire 800 Cable for connecting between the two interfaces
- One MADI optical cable for connecting between the two interfaces (single or dual MADI cables can be used)

### *Key points for this example:*

- One unit is designated as the "Monitor" (the master unit where monitor connections are made)
- One unit is the "Expander" (the slave unit with higher numbered I/O)
- The Monitor unit is connected to the host computer via FireWire 800 (either Apollo 16 FireWire port can be used for this connection)
- The Expander unit is *not* connected to the host computer
- One FireWire 800 cable must be connected between the Expander and Monitor units (either Apollo 16 FireWire port can be used for this connection)
- One MADI optical cable must be connected from the MADI OUT of the Expander unit to the MADI IN of the Monitor unit
- Monitor and cue outputs are connected to the Monitor unit only

#### POWER OUT IN 75 OHM TERM UNIVERSAL AUDIO, INC. MON OUT (R) 2 MON OUT (L) 1 LINE OUT 1-8 LINE IN 1-8 LINE IN 9-16 MADI OUT MADI IN AES/EBU OUT AES/EBU IN LINE OUT 9-16 1394 800 (1) 1394 800 (2) POWER OUT IN 75 OHM TERM WORD CLOCK UNIVERSAL AUDIO, INC. MON OUT (R) 2 MON OUT (L) 1 LINE OUT 1-8 LINE IN 1-8 LINE IN 9-16 MADI OUT MADI IN AES/EBU OUT AES/EBU IN LINE OUT 9-16 1394 800 (1) 1394 800 (2) **Expander Unit Monitor Unit FireWire 800 Computer** IMPORTANT: Connect speakers and cue outputs to **monitor unit only Apollo 16 Multi-Unit Wiring FireWire Host Connection**

#### Apollo Expanded: Multi-Unit Wiring - Thunderbolt Host Connection

The diagram below illustrates how to interconnect multiple Apollo units and the host computer via Thunderbolt when using Apollo Expanded software (UAD v8 or higher) for Thunderbolt systems.

**Important:** For complete details about system operation when multi-unit cascading, see the Apollo Software Manual.

#### Cables Required

• One Thunderbolt cable for each Apollo unit

**Note:** All Apollo rack units require Thunderbolt connections.

### Apollo Expanded Wiring Notes

- A single Thunderbolt cable is required for all device interconnections. Connect one cable to the host computer and one cable between Apollo units.
- Thunderbolt 1 or 2 ports may be mixed and used for any/all connections.
- The computer and all Apollo units must be connected to the same Thunderbolt bus.
- The Apollo device ordering and the Thunderbolt ports used (second port on Apollo vs. second port on computer, placement in daisy chain, etc) is not important.
- In the wiring example diagram, the lower Apollo 8 is designated as the monitor (master) unit. Connect speakers (including ALT speakers) to the monitor unit only.
- Do not connect more than one Thunderbolt cable between they same two devices (the Thunderbolt protocol is bidirectional).
- Do not interconnect any Word Clock, FireWire, ADAT, or MADI ports between any Apollo units.

**Note:** The FireWire ports are disabled with Apollo Thunderbolt software.

![](<Apollo 16 Hardware Manual_assets/_page_20_Picture_15.jpeg>)

# <span id="page-21-1"></span><span id="page-21-0"></span>**FireWire Basics**

FireWire (also known as "IEEE 1394" and "i.Link") is a high-speed serial data interconnection protocol that is used to transfer digital data between devices. FireWire is commonly used to interconnect computer systems to hard drives, audio interfaces, and digital camcorders. A complete discussion of FireWire is beyond the scope of this manual, but some of the main points and how they apply to Apollo 16 are covered below.

*Important: On Windows systems, Apollo 16 requires a qualified PCIe-to-FireWire adapter card. For details, see www.uaudio.com/support/apollo*

### **FireWire vs. USB**

FireWire is considered superior to USB for audio purposes because it does not rely on the host processor to manage low-level data housekeeping (among other reasons). FireWire typically outperforms USB at the same rated speeds.

### **FireWire Bus**

FireWire devices are connected to a FireWire "bus" which is comprised of all devices in the serial data stream. The FireWire specification supports up to 63 devices per FireWire bus.

Many FireWire devices and host computers have more than one FireWire connector, but these connectors almost always attach to the same FireWire bus (most computers do not have more than one FireWire bus). It is possible to add another FireWire bus to a computer, typically by adding a PCIe-to-FireWire or ExpressCard-to-FireWire adapter card.

### **Bus Power**

Some FireWire devices can be "bus powered" which means the device derives its operating electricity from the FireWire bus itself without a power supply of its own. Apollo 16 cannot be bus powered and it does not supply bus power from its FireWire ports to other devices.

### **Powering Down**

Powering down or disconnecting Apollo 16 when UAD plug-ins are loaded could cause session data loss and/ or unpredictable behavior. Quit all UAD host applications (DAW, Console, UAD Meter & Control Panel) before disconnecting Apollo.

### **FireWire 800 vs. FireWire 400**

The most common FireWire devices are available in two speeds: FireWire 400 (IEEE 1394a), which supports transfer speeds up to 400 megabits per second, and FireWire 800 (IEEE 1394b), which supports up to 800 megabits per second. It's usually possible to determine the speed of the FireWire device by the type of FireWire connector it uses. Apollo 16 is a FireWire 800 device.

#### **FireWire Connectors**

FireWire 800 and FireWire 400 devices use different connectors, as illustrated below. This helps to differentiate between the two device speeds (the connectors are not interchangeable).

![](<Apollo 16 Hardware Manual_assets/_page_22_Picture_2.jpeg>)

#### FireWire 400 connectors

FireWire 400 devices typically have two types of connector: 4-pin and 6-pin. The small 4-pin FireWire 400 connector is common on digital camcorders and Windows notebook computers. The 6-pin connector is more common with hard drives and audio devices.

#### FireWire 800 connector

FireWire 800 devices use a 9-pin connector. 9-pin to 6-pin FireWire adapter cables are available to connect FireWire 800 devices to a FireWire 400 bus (with half the bandwidth).

Apollo 16 has two FireWire 800 ports to facilitate easy daisy chaining with other FireWire devices.

#### FireWire Repeaters and Chains

FireWire devices can be connected to each other serially in a "daisy chain," connected to a central device such as a computer with multiple FireWire ports or a peripheral FireWire repeater, or any combination of the two in a "tree chain" topology.

Apollo 16 can function as a FireWire repeater, by using the unused port on the unit to connect other FireWire devices. Note that Apollo 16 does not supply FireWire bus power to downstream devices.

The examples below show a few of the many interconnection possibilities using daisy chains and repeaters.

![](<Apollo 16 Hardware Manual_assets/_page_22_Picture_12.jpeg>)

![](<Apollo 16 Hardware Manual_assets/_page_22_Picture_13.jpeg>)

FireWire bus connections via repeater

<span id="page-23-0"></span>![](<Apollo 16 Hardware Manual_assets/_page_23_Picture_0.jpeg>)

FireWire bus connections via repeater and daisy chain in a "tree chain"

### **Mixing FireWire Speeds**

Although FireWire 400 and FireWire 800 devices can be connected to the same FireWire bus via a repeater or daisy chain, special precautions must be observed to maximize bandwidth in these situations.

#### FireWire 800 devices on a FireWire 400 bus

FireWire 800 devices are backwards-compatible and can be connected to a FireWire 400 bus using a 9-pin to 6-pin FireWire cable or adapter. However in this scenario any 800 megabit-capable devices on the bus (including Apollo 16) will operate at a maximum of 400 megabits because FireWire bandwidth cannot exceed the maximum bus speed of the host computer.

![](<Apollo 16 Hardware Manual_assets/_page_23_Picture_6.jpeg>)

#### FireWire 400 devices on a FireWire 800 bus

FireWire 400 devices can be connected to a FireWire 800 bus using a 6-pin to 9-pin FireWire cable or adapter. However, if the FireWire 800 devices are located after the FireWire 400 devices in the daisy chain, all FireWire devices will operate at a maximum of 400 megabits because the FireWire 400 devices force all subsequent devices to run at FireWire 400 speeds.

![](<Apollo 16 Hardware Manual_assets/_page_23_Picture_9.jpeg>)

#### <span id="page-24-0"></span>Combining FireWire 400 and 800 devices on a FireWire 800 bus

It is possible to configure a FireWire bus to run at both FireWire 400 and FireWire 800 speeds simultaneously if the host computer bus is FireWire 800, supporting maximum throughput with a combination of FireWire 400 and FireWire 800 devices. This is accomplished by putting any/all FireWire 400 devices AFTER any/all FireWire 800 devices in a daisy chain or tree chain. If (and only if) FireWire 400 devices are attached to a FireWire 800 bus after the end of all FireWire 800 devices in a daisy chain or tree chain, the FireWire 800 devices will operate at 800 megabits while the FireWire 400 device operates at 400 megabits. The diagram below illustrates the recommended configuration when Apollo 16 is sharing a FireWire 800 bus with FireWire 400 devices.

#### Recommended Mixed Speed Setup

![](<Apollo 16 Hardware Manual_assets/_page_24_Picture_3.jpeg>)

The example above shows the correct method of interconnecting FireWire 800 and FireWire 400 devices to a FireWire 800 computer bus. Any mixture of daisy chains, repeaters, and/or tree chains may be used, as long as all the FireWire 400 devices are placed after all the FireWire 800 devices.

#### FireWire with Thunderbolt

When Apollo 16 is connected to the computer via the Thunderbolt Option Card, both of Apollo 16's FireWire ports remain active and they can be connected to FireWire peripheral devices such as hard drives. For an illustration of this configuration, see "Thunderbolt Setup" on page 19.

# <span id="page-25-1"></span><span id="page-25-0"></span>**Digital Clocking Basics**

Digital clocking can be a complicated issue, with a number of important aspects that are often not very well understood.

First and foremost, a digital clock is used to maintain synchronization between different digital devices. There are two primary purposes for clock synchronization:

- Digital Conversion. Analog-to-digital (A/D) conversion and digital-to-analog (D/A) conversion need extremely accurate clocking in order to correctly process the digital data. A low-quality clock can degrade the signal in many ways, including loss of transparency, clarity, imaging and transient response, as well as increased noise and distortion.
- Digital Transmission. All digital devices need accurate clocking in order to properly transfer digital data between interconnected devices. A low-quality clock can cause data reception errors, which add distortion and noise, and if the clock isn't synchronized correctly, samples may be dropped or repeated, resulting in audible clicks or dropouts.

Clock quality is defined two ways: First, the sample rate must match the signal. This is referred to as "sample rate synchronization." Second, the clock signal must be stable over both short-term and long-term clocking intervals. "Jitter" refers to short-term clock accuracy, and "stability" or "drift" refers to long-term clock accuracy. These terms are discussed in more detail below.

Sample rate synchronization is required for proper digital transmission, and is relatively easy to maintain. Basically, there must be one and only one "clock master" for all interconnected digital devices. This is done by setting one device to "master" mode (where it synchronizes to its internal clock and transmits that clock signal) and setting every other device to "slave" mode (where it receives and synchronizes to external clock), with the appropriate clock signal routed between the master and slave devices. Keep in mind that any device, whether it's the clock master or a slave, can send or receive data once everything is synchronized correctly.

When doing digital conversion, it's best to have the converter serve as the clock master. For example, if you're recording, clock everything off the A/D converter. Likewise, if you're mixing, clock everything off the D/A converter. If you're running multiple converters, use the device with the best quality clock as master.

For all-digital transfers, e.g., a digital transfer from one DAW or storage device to another, clock synchronization is maintained by simply setting up the proper master-slave relationship between devices. Digital transfers can be affected by clock jitter, but not in the same way clock jitter affects analog conversion. This is a widely misunderstood concept we'll discuss in detail below.

Clock jitter is short-term variations in the timing of edges of a clock signal, as opposed to clock drift, which is long-term variation in the clock rate. A clock could be very stable over the long term, but still have jitter, and vice versa. Timing variations are caused by noise and/or interference. If the noise/interference is a highfrequency signal, the result is jitter, and if the noise/interference is a low-frequency signal, the result is drift. As an analogy, a car with an out of balance wheel may drive straight, but you'll get lots of vibration (jitter); conversely, a car with a loose steering wheel might have a smooth ride, but it will drift all over the road.

Clock drift affects long-term synchronization, like sound to picture, and can introduce slight pitch variations in the audio. Usually however, the drift is so slow that these pitch variations are only tiny fractions of a cent, and thus unnoticeable.

Clock jitter affects digital transmission and digital conversion differently, as follows:

- Clock jitter in digital transmission can be caused by a bad source clock, inferior cabling or improper cable termination, and/or signal-induced noise (called "pattern-jitter" or "symbol-jitter"). Digital signal formats like AES/EBU, S/PDIF, and ADAT all embed a clock in the digital signal so the receiving device can synchronize to the transmitted data bits correctly. The clock used for data recovery is extracted from the signal using a clock synchronization circuit called a phase-locked-loop (PLL). This data-recovery PLL must be designed to respond very quickly to attenuate high-frequency jitter and avoid bit errors during reception. This clock from the data-recovery PLL cannot be used to generate the clocks used for digital conversion without further clock conditioning! This is a very common design flaw in most low- and mid-range digital converters.
- Clock jitter in digital conversion is what most people refer to when they discuss jitter. It's easily observed in a digital signal by looking at its spectrum in the frequency domain. A jittery signal will have "side-lobes" around each frequency and/or spurious tones at random, inharmonic frequencies. Usually, the jitter will be worse with higher signal frequencies. You can test your converters by sampling a high-quality 10 kHz sine wave, and viewing it in the frequency domain (available with any good wave editing software package).

All modern over-sampling digital converters require a clock (called "m-clock") that is many times (typically several megahertz) higher than the sample clock. M-clock is easy to generate when the converter is the clock master, but quite difficult to generate correctly when the converter needs to sync to an external clock.

External clock typically comes from a dedicated word clock input, or is extracted from an incoming digital AES/ EBU, S/PDIF, or ADAT signal. Word clock cannot be used by the converters until it is multiplied up to the m-clock rate. This requires a PLL or other frequency multiplier circuit which will either be cheap and jittery, or expensive and clean, depending on who makes the converter. As we said earlier, the clock recovered from the digital inputs is unsuitable for use as the converter's m-clock, but because it's conveniently at the same frequency, many designers don't bother cleaning up this signal.

Since the clock recovery, clock multiplier, and clock conditioning circuitry define the jitter for analog conversion, no external clock source can clean up the jitter introduced by these circuits, regardless of how perfect the external source clock is. The best they can do is avoid making it any worse, but this is hardly worth the cost: It's much better (and less expensive) to use a good converter like Apollo than it is to try and fix a bad one with an expensive master clock. The only reason to spend money on a high-quality master clock is to ensure that multiple devices are synchronized correctly. This is essential for working with audio for film/video, or when synchronizing multiple high-quality converters. A poor master clock can also affect imaging and clarity in a multi-track environment.

Apollo 16 provides high-quality A/D and D/A conversion for recording and/or playback. With its pristine audio path and high-quality clocking, it makes a great master or slave audio interface for every digital studio, and thus provides a very cost effective way to improve overall sound quality.

# <span id="page-27-0"></span>**Specifications**

All specifications are typical performance unless otherwise noted, tested under the following conditions: 48 kHz internal sample rate, 24-bit sample depth, 20 kHz measurement bandwidth, with balanced output.

| SYSTEM                                                                                           |                                                            |
|--------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| I/O Complement                                                                                   |                                                            |
| Analog Line Inputs                                                                               | 16                                                         |
| Analog Line Outputs                                                                              | 16                                                         |
| Analog Monitor Outputs                                                                           | Two (one stereo pair)                                      |
| AES/EBU                                                                                          | One stereo input, one stereo output                        |
| FireWire 800 (IEEE 1394b)                                                                        | Dual ports                                                 |
| Thunderbolt (via Thunderbolt Option Card, sold separately)                                       | Dual ports                                                 |
| Word Clock                                                                                       | One input, one output                                      |
| MADI Optical Ports                                                                               | One input, one output                                      |
| A/D – D/A Conversion                                                                             |                                                            |
| Supported Sample Rates (kHz)                                                                     | 44.1, 48, 88.2, 96, 176.4, 192                             |
| A/D Bits Per Sample                                                                              | 24                                                         |
| Simultaneous A/D conversion                                                                      | 16 channels                                                |
| Simultaneous D/A conversion                                                                      | 18 channels                                                |
| Analog Round-Trip Latency                                                                        | 1.1 milliseconds @ 96 kHz sample rate                      |
| Analog Round-Trip Latency with up to four serial<br>UAD Powered Plug-Ins via Console application | 1.1 milliseconds @ 96 kHz sample rate                      |
| ANALOG I/O                                                                                       |                                                            |
| Analog Inputs 1 – 16                                                                             |                                                            |
| Dynamic Range                                                                                    | 119 dB (A–weighting)                                       |
| Signal-to-Noise Ratio                                                                            | 119 dB (A–weighting)                                       |
| Total Harmonic Distortion + Noise                                                                | -112 dB @ -1 dBFS                                          |
| Common-Mode Rejection Ratio                                                                      | -75 dB                                                     |
| Frequency Response                                                                               | 20 Hz – 20 kHz, ±0.05 dB                                   |
| Channel Separation (Crosstalk)                                                                   | -138 dB                                                    |
| Input Impedance                                                                                  | 10 Kilohms                                                 |
| Gain Settings                                                                                    | +4 dBu or -10 dBV (reference level is selectable in pairs) |
| Max Input Voltage (Reference Level @ +4 dBu, Balanced)                                           | 20.22 dBu (18 dBV, 7.94 VRMS, 0 dBFS)                      |
| Max Input Voltage (Reference Level @ -10 dBV, Balanced)                                          | 14.22 dBu (12 dBV, 3.98 VRMS, 0 dBFS)                      |
| Max Input Voltage (Reference Level @ -10 dBV, Single-Ended)                                      | 8.22 dBu (6 dBV, 2 VRMS, 0 dBFS)                           |
| Stereo Level Balance                                                                             | ±0.01 dB                                                   |
| Connector Type                                                                                   | Two Female DB25, Tascam wiring                             |

*(continued)*

<span id="page-28-0"></span>

| ANALOG I/O                                                   |                                                            |
|--------------------------------------------------------------|------------------------------------------------------------|
| Analog Outputs 1 – 16                                        |                                                            |
| Dynamic Range                                                | 118.5 dB (A–weighting)                                     |
| Signal-to-Noise Ratio                                        | 118.2 dB (A–weighting)                                     |
| Total Harmonic Distortion + Noise                            | -107.5 dB @ -1 dBFS                                        |
| Connector Type                                               | Two Female DB25, Tascam wiring                             |
| Monitor Outputs 1 – 2                                        |                                                            |
| Dynamic Range                                                | 115 dB (A–weighting)                                       |
| Signal-to-Noise Ratio                                        | 115 dB (A–weighting)                                       |
| Total Harmonic Distortion + Noise                            | -105.5 dB @ -1 dBFS                                        |
| Gain Range (Monitor Knob)                                    | -INF to 0 dBFS                                             |
| Connector Type                                               | Two Male Balanced XLR (pin 2 hot)                          |
| All Analog Outputs                                           |                                                            |
| Frequency Response                                           | 20 Hz – 20 kHz, ±0.05 dB                                   |
| Channel Separation (Crosstalk)                               | -120 dB                                                    |
| Output Impedance                                             | 600 Ohms                                                   |
| Stereo Level Balance                                         | ±0.01 dB                                                   |
| Gain Settings                                                | +4 dBu or -10 dBV (reference level is selectable in pairs) |
| Max Output Voltage (Reference Level @ +4 dBu, Balanced)      | 20.2 dBu (18 dBV, 7.94 VRMS, 0 dBFS)                       |
| Max Output Voltage (Reference Level @ -10 dBV, Balanced)     | 14.2 dBu (12 dBV, 3.98 VRMS, 0 dBFS)                       |
| Max Output Voltage (Reference Level @ -10 dBV, Single-Ended) | 8.2 dBu (6 dBV, 2 VRMS, 0 dBFS)                            |
| DIGITAL I/O                                                  |                                                            |
| AES/EBU                                                      |                                                            |
| Connector Type                                               | XLR                                                        |
| Format                                                       | IEC 60958 Type I                                           |
| MADI (not implemented)                                       |                                                            |
| Connector Type                                               | Dual Optical SC-Plug (ISO/IEC 9314-3)                      |
| Word Clock                                                   |                                                            |
| Connector Type                                               | BNC                                                        |
| Lock Range                                                   | ±0.5% of any supported sample rate                         |
| Word Clock Input Termination                                 | 75 Ohms, switchable                                        |
| Syncronization Sources                                       |                                                            |
| Internal, Word Clock, AES/EBU                                |                                                            |
|                                                              |                                                            |

*(continued)*

<span id="page-29-0"></span>

| Power Supplies<br>External AC to DC Power Supply<br>AC Connector Type<br>IEC Male<br>AC Requirements<br>100V – 240V AC, 50 – 60 Hz<br>DC Connector Type<br>XLR 4-Pin Locking Male (Neutrik P/N NC4MDM3-H)<br>DC Requirements<br>12 VDC, ±5%<br>Maximum Power Consumption<br>50 Watts<br>ENVIRONMENTAL<br>Operating Temperature Range<br>0º Celsius to 40º Celsius<br>Storage Temperature Range<br>-40º Celsius to 80º Celsius<br>Operating Humidity Range<br>10% – 95% Non-Condensing<br>MECHANICAL<br>Dimensions<br>Width<br>19"<br>Height<br>1.75" (1U rack space)<br>Depth, Chassis Only<br>12.125"<br>Depth, Including Knob & Jack Protrusions<br>13.75"<br>Shipping Box (Width x Depth x Height)<br>24" x 17" x 8"<br>Weight<br>Shipping Weight (with box & accessories)<br>18 pounds<br>Weight (bare unit)<br>8.7 pounds<br>Package Contents<br>Apollo 16 Audio Interface<br>External Power Supply<br>Apollo Hardware Manual<br>15' FireWire 800 cable<br>(2) IEC AC Power Cables (USA & Europe)<br>Set of (4) Rack-Mount Screws<br>Universal Audio Product Catalog | ELECTRICAL |  |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--|
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |            |  |

Apollo 16 Hardware Manual 30 Specifications

<span id="page-30-0"></span>![](<Apollo 16 Hardware Manual_assets/_page_30_Figure_1.jpeg>)

# <span id="page-31-1"></span><span id="page-31-0"></span>**DB25 Wiring**

Apollo 16's analog I/O is accessed via 25-pin D-sub female connectors. Each DB25 jack carries eight balanced line-level audio channels on the standardized Tascam pinouts also used with Digidesign and Avid products.

### **DB25 Connector Pin Numbers**

The pin numbers for female DB25 connectors are shown in the diagram below. When facing the Apollo 16 rear panel, pin 1 is the upper rightmost pin.

![](<Apollo 16 Hardware Manual_assets/_page_31_Figure_4.jpeg>)

*Apollo 16 female DB25 pin numbers*

### **DB25 Connector Wiring**

The signals carried on the female DB25 connector pins are listed in the table below. Two channels are listed for each pin. The first is for the connector carrying channels 1 – 8; the second is for the connector carrying channels 9 – 16 (pinouts are identical for inputs and outputs).

|     | APOLLO 16 DB25 CONNECTOR PINOUTS |        |     |          |            |     |          |        |
|-----|----------------------------------|--------|-----|----------|------------|-----|----------|--------|
| Pin | Channels                         | Signal | Pin | Channels | Signal     | Pin | Channels | Signal |
| 1   | 8, 16                            | Hot    | 9   | 3, 11    | Cold       | 17  | 6, 14    | Cold   |
| 2   | 8, 16                            | Ground | 10  | 2, 10    | Hot        | 18  | 5, 13    | Hot    |
| 3   | 7, 15                            | Cold   | 11  | 2, 10    | Ground     | 19  | 5, 13    | Ground |
| 4   | 6, 14                            | Hot    | 12  | 1, 9     | Cold       | 20  | 4, 12    | Cold   |
| 5   | 6, 14                            | Ground | 13  | –        | No Connect | 21  | 3, 11    | Hot    |
| 6   | 5, 13                            | Cold   | 14  | 8, 16    | Cold       | 22  | 3, 11    | Ground |
| 7   | 4, 12                            | Hot    | 15  | 7, 15    | Hot        | 23  | 2, 10    | Cold   |
| 8   | 4, 12                            | Ground | 16  | 7, 15    | Ground     | 24  | 1, 9     | Hot    |
|     |                                  |        |     |          |            | 25  | 1, 9     | Ground |

## <span id="page-32-1"></span><span id="page-32-0"></span>**Troubleshooting**

If Apollo 16 isn't behaving the way you expect it to, here are some common troubleshooting items to confirm. If you are still experiencing issues after performing these checks, contact technical support (see ["Technical Sup](#page-8-1)[port" on page 9](#page-8-1)).

| SYMPTOM                                                                   | ITEMS TO CHECK                                                                                                                                                                                                                                                                                                                                        |
|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Unit won't power on                                                       | •Confirm power supply connections at power supply input and back of unit<br>•Confirm Power switch is not in "OFF" position<br>•Confirm AC power is available at wall socket by plugging in a different device                                                                                                                                         |
| No monitor output                                                         | •Confirm UAD Powered Plug-Ins software is properly installed and configured<br>•Confirm connections, power, and volume of monitoring system<br>•Confirm monitor knob is turned up<br>•Confirm monitor outputs are not muted (push monitor knob - green = not muted, red = muted)<br>•Confirm monitor level meter LEDs are active (check signal flows) |
| Monitor output level range is<br>too loud or too quiet                    | •Monitor output reference levels can be switched between -10 dBV and +4 dBu in the Outputs<br>panel in the Console Settings window within the Console application                                                                                                                                                                                     |
| Input levels are too high or too<br>low                                   | •Input reference levels can be switched between -10 dBV and +4 dBu in the input channel<br>strips of the Console application                                                                                                                                                                                                                          |
| Can't fine tune input signal<br>levels                                    | •Signal levels for all inputs, including digital inputs, are adjusted at the device connected to<br>those inputs                                                                                                                                                                                                                                      |
| Output levels are too high or<br>too low                                  | •Output reference levels for adjacent pairs can be switched between -10 dBV and +4 dBu in the<br>Outputs panel in the Console Settings window within the Console application                                                                                                                                                                          |
| Audio glitches and/or dropouts                                            | •Increase audio buffer size setting in DAW<br>•Confirm clocking setups (check cable connections and confirm all device clocks are synchro<br>nized to one master clock device)                                                                                                                                                                        |
| Undesirable echo/phasing                                                  | •Confirm input monitoring is not enabled in both Console and DAW                                                                                                                                                                                                                                                                                      |
| HOST indicator is not lit                                                 | •Confirm FireWire or Thunderbolt connections<br>•Confirm Apollo 16 software (UAD Powered Plug-Ins) is installed<br>•Restart computer and power cycle Apollo 16<br>•Reinstall Apollo 16 software<br>•Try a different FireWire or Thunderbolt cable                                                                                                     |
| Faint static and/or white<br>noise is heard when nothing is<br>plugged in | • Mute unused inputs<br>•Some UAD plug-ins model the noise characteristics of the original equipment. Defeat the noise<br>model in the plug-in GUI or mute the channel containing the plug-in to temporarily mute the<br>noise                                                                                                                        |
| Various LEDs inside the unit are<br>blinking                              | • This is normal operational behavior that can be safely ignored                                                                                                                                                                                                                                                                                      |
| Apollo 16 is behaving unexpectedly                                        | • As a last resort, perform a hardware reset on the unit by following these steps:<br>1. Power off Apollo 16<br>2. Press and hold the METER and MONITOR controls<br>3. Power on Apollo 16 while continuing to hold both controls<br>4. After all front panel LEDs flash rapidly (after several seconds), release the controls                         |

### <span id="page-33-0"></span>**Important Safety Information**

Before using this unit, be sure to carefully read the applicable items of these operating instructions and the safety suggestions. Afterwards, keep them handy for future reference. Take special care to follow the warnings indicated on the unit, as well as in the operating instructions.

- 1. Water and Moisture Do not use the unit near any source of water or in excessively moist environments.
- 2. Object and Liquid Entry Care should be taken so that objects do not fall, and liquids are not spilled, into the enclosure through openings.
- 3. Ventilation When installing the unit in a rack or any other location, be sure there is adequate ventilation. Improper ventilation will cause overheating, and can damage the unit.
- 4. Heat The unit should be situated away from heat sources, or other equipment that produces excessive heat.
- 5. Power Sources The unit should be connected to a power supply only of the type described in the operating instructions, or as marked on the unit.
- 6. Power Cord Protection AC power supply cords should be routed so that they are not likely to be walked on or pinched by items placed upon or against them. Pay particular attention to cords at plugs, convenience receptacles, and the point where they exit from the unit. Never take hold of the plug or cord if your hand is wet. Always grasp the plug body when connecting or disconnecting it.
- 7. Grounding of the Plug This unit is equipped with a 3-wire grounding type plug, a plug having a third (grounding) pin. This plug will only fit into a grounding-type power outlet. This is a safety feature. If you are unable to insert the plug into the outlet, contact your electrician to replace your obsolete outlet. Do not defeat the purpose of the grounding-type plug.
- 8. Cleaning Follow these general rules when cleaning the outside of the unit:
  - a. Turn the power off and unplug the unit
  - b. Gently wipe with a clean lint-free cloth
  - c. Do not use aerosol sprays, solvents, or abrasives
- 9. Nonuse Periods The AC power supply cord of the unit should be unplugged from the AC outlet when left unused for a long period of time.
- 10. Damage Requiring Service The unit should be serviced by a qualified service personnel when:
  - a. The AC power supply unit has been damaged; or
  - b. Objects have fallen or liquid has been spilled into the unit; or
  - c. The unit has been exposed to rain; or
  - d. The unit does not operate normally or exhibits a marked change in performance; or
  - e. The unit has been dropped, or the enclosure damaged.
- 11. Servicing The user should not attempt to service the unit beyond that described in the operating instructions. All other servicing should be referred to qualified service personnel.

### <span id="page-34-0"></span>**Warranty**

Universal Audio provides a warranty on all hardware products. To learn more, please visit [www.uaudio.com/support/warranty.html](http://www.uaudio.com/support/warranty.html) or contact [Technical Support.](#page-8-1) This limited warranty gives you specific legal rights. You may also have other rights which vary by state or country.

### **Maintenance**

Apollo 16 does not contain a fuse or any other user-replaceable parts. The unit is internally calibrated at the factory. No internal user adjustments are available.

### **Repair Service**

If you are having trouble with Apollo 16, the first check all system setups, connections, software installations, and the [Troubleshooting](#page-32-1) chart. If that doesn't help, contact [Technical Support.](#page-8-1) To learn more about repair service, please visit:

• [www.uaudio.com/support/rma-faq.html](http://www.uaudio.com/support/rma-faq.html)

### **Federal Communications Commission Compliance**

This equipment has been tested and found to comply with the limits for a Class B digital device, pursuant to part 15 of the FCC Rules. These limits are designed to provide reasonable protection against harmful interference in a residential installation. This equipment generates, uses and can radiate radio frequency energy and, if not installed and used in accordance with the instructions, may cause harmful interference to radio communications. However, there is no guarantee that interference will not occur in a particular installation. If this equipment does cause harmful interference to radio or television reception, which can be determined by turning the equipment off and on, the user is encouraged to try to correct the interference by one or more of the following measures:

- Reorient or relocate the receiving antenna.
- Increase the separation between the equipment and receiver.
- Connect the equipment into an outlet on a circuit different from that to which the receiver is connected.
- Consult the dealer or an experienced radio/TV technician for help.

### **European Commission Compliance**

We hereby declare that the equipment listed herein conforms to the harmonized standards of the following European Commission Directive: 2004/108/EC

Trade Name: Apollo 16 High-Resolution Audio Interface

Model Number: Apollo 16

Test Information is contained in a report by National Technical Systems

Dated February 14, 2013

Report No: R91040

### **Disclaimer**

The information contained in this manual is subject to change without notice. Universal Audio, Inc. makes no warranties of any kind with regard to this manual, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose. Universal Audio, Inc. shall not be liable for errors contained herein or direct, indirect, special, incidental, or consequential damages in connection with the furnishing, performance, or use of this material.

### **End User License Agreement**

Your rights to the software are governed by the accompanying End User License Agreement, a copy of which can be found at: [www.uaudio.com/eula](http://www.uaudio.com/eula)

### **Trademarks**

Universal Audio, the Universal Audio "diamond" logo, Apollo, Apollo Twin, Apollo 16, Unison technology, UAD, UAD Series, UAD-1, UAD-2, UAD-2 Satellite, Powered Plug-Ins, 1176LN, 1176SE, Teletronix, LA-2A, LA-3A, LA-610, LA-610MkII, 2-1176, 2-610, 6176, 710 Twin-Finity, 2192, 4-710d, Cambridge EQ, DreamVerb, Plate 140, Precision Limiter, RealVerb Pro, Precision Buss Compressor, Precision De-Esser, Precision Maximizer, and "Analog Ears | Digital Minds," are among the trademarks, trade names, and service marks owned by UA that may appear on the Site, many of which are registered in the United States and other countries. This is not a comprehensive list of all UA trademarks. All UA trademarks inure to the benefit of UA. Other trademarks and trade names that may appear on the Site and which are not owned by UA are owned by the respective owners.

### **Copyright**

Copyright ©2017 Universal Audio, Inc. All rights reserved.

This manual and any associated software, artwork, product designs, and design concepts are subject to copyright protection. No part of this document may be reproduced, in any form, without prior written permission of Universal Audio, Inc.

Front Panel [10](#page-9-0)

<span id="page-36-0"></span>

| A                                                                                                                                                                | H                                                                                                                                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AES/EBU 29<br>AES/EBU Ports 15<br>Analog Inputs 28                                                                                                               | Host 10<br>Host I/O 16                                                                                                                                                                                                                                                 |
| Analog I/O 13                                                                                                                                                    | I                                                                                                                                                                                                                                                                      |
| ANALOG I/O 28<br>Analog Outputs 29<br>Apollo 16 Documentation 8<br>Apollo Software Manual 8<br>Audio Interface 5                                                 | Inputs 13<br>Interconnections 18<br>Introduction 4<br>I/O Complement 28                                                                                                                                                                                                |
| B                                                                                                                                                                | J                                                                                                                                                                                                                                                                      |
| Block Diagram 31<br>Bus Power 22                                                                                                                                 | Jitter 26                                                                                                                                                                                                                                                              |
|                                                                                                                                                                  | L                                                                                                                                                                                                                                                                      |
| C<br>Channel Meters 11<br>Clock 10<br>Clocking Basics 26<br>Combining with other UAD-2 devices 7                                                                 | Letter from Bill ii<br>Level Indicator 12<br>Level Meters 11<br>Line Inputs 13<br>Line Outputs 13                                                                                                                                                                      |
| Compliance 35                                                                                                                                                    | M                                                                                                                                                                                                                                                                      |
| Connector Wiring 32<br>Console 6, 7<br>Contents 30                                                                                                               | MADI 29<br>MADI Optical Ports 16                                                                                                                                                                                                                                       |
| D                                                                                                                                                                | Mechanical 30<br>Meter 10, 11                                                                                                                                                                                                                                          |
| DB25 connectors 13<br>DB25 Wiring 32<br>Digital Clocking Basics 26<br>Digital I/O 14<br>DIGITAL I/O 29<br>Dimensions 30<br>Documentation 8<br>E<br>Electrical 30 | Meters 11<br>Mirror Monitor Outputs 15<br>Mixing FireWire Speeds 24<br>Monitoring 5<br>Monitor Level 11<br>Monitor Level Indicator 12<br>Monitor Mute 12<br>Monitor Output Level Meters 11<br>Monitor Outputs 13, 29<br>Multi-Unit Setup – FireWire 20<br>Mute Knob 11 |
| Expansion Bay 16                                                                                                                                                 |                                                                                                                                                                                                                                                                        |
| F                                                                                                                                                                | N                                                                                                                                                                                                                                                                      |
| Features 5<br>FireWire 800 Ports 16<br>FireWire 800 vs. FireWire 400 22<br>FireWire Basics 22<br>FireWire with Thunderbolt 25                                    | Notices 34<br>O<br>Outputs 13, 29                                                                                                                                                                                                                                      |

### **P**

Pin Numbers [32](#page-31-0) Power Consumption [30](#page-29-0) Power Indicator [11](#page-10-0) Power Input [14](#page-13-0) Power Switch [12](#page-11-0)

### **R**

Realtime UAD Processing [7](#page-6-0) Rear Panel [13](#page-12-0)

### **S**

Safety Information [34](#page-33-0) Software [6](#page-5-0) Specifications [28](#page-27-0) Standalone Use [7](#page-6-0) Status Indicators [10](#page-9-0) Syncronization [29](#page-28-0) SYSTEM [28](#page-27-0)

### **T**

Technical Support [9](#page-8-0) Thunderbolt [25](#page-24-0) Thunderbolt Option Card [9](#page-8-0) Thunderbolt Setup [19](#page-18-1) Troubleshooting [33](#page-32-0) Typical Setup [18](#page-17-0)

### **U**

UAD-2 [5](#page-4-0) UAD Powered Plug-Ins [7](#page-6-0) UAD System Manual [8](#page-7-0)

### **W**

Weight [30](#page-29-0) Welcome [ii](#page-1-0) Word Clock [29](#page-28-0) Word Clock In [14](#page-13-0) Word Clock Out [14](#page-13-0) Word Clock Termination Switch [15](#page-14-1)

### **X**

XLR [13](#page-12-0)

![](<Apollo 16 Hardware Manual_assets/_page_38_Picture_0.jpeg>)