---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12241600280468-Sphere-Mic-Preamp-Requirements.html'
converted_at: 2026-05-31T13:44:42Z
tool: htmlq+pandoc
title: 'Sphere Mic Preamp Requirements'
word_count: 683
---

# Sphere Mic Preamp Requirements


## In this article

- <a href="#h_01GPD8HFZ0NHXEZ5CN7ZGDBGFM" target="_self">About mic preamps</a>
  - <a href="#h_01GPD8HQ5P3AFJEW6ADG13K0SS" target="_self">Understanding your mic inputs</a>
  - <a href="#h_01GPD8HXT70TCM5D4VPCNQASPE" target="_self">Using digitally controlled mic preamps</a>
  - <a href="#h_01GPD8J351W39TD1768E5TT0W5" target="_self">Using stepped-gain mic preamps</a>
  - <a href="#h_01GPD8J92BZS55FAWHE8Y2TVCF" target="_self">Using continuous gain mic preamps</a>
  - <a href="#h_01GPD8JFPPMV4R8DF85XCHY5CR" target="_self">Understanding input impedance</a>
  - <a href="#h_01GPD8JP8K5TWNDNA71MR2D6XP" target="_self">Using phantom power</a>
  - <a href="#h_01GPD8JZ78TR996XPB54DYYDCY" target="_self">Using preamp modeling plug-ins</a>
  - <a href="#h_01GPD8K871KGY1V447PRTJE6XQ" target="_self">Using Unison preamp models</a>

# About mic preamps

## Understanding your mic inputs

- With Sphere, both mic preamp channels must be set to the same gain level, and this level must be maintained all the way to the input of the Sphere plug-in.\
  We recommend enabling gain linking for both channels (if your preamp supports it) to conveniently maintain equal gain.

<!-- -->

- Route the front and rear mic capsule outputs to the left and right inputs of the plug-in, respectively. The rear mic output is marked with a red label.

**Note:** We generally recommend placing the Sphere plug-in first in the signal chain, or using only a clean (not overloaded) Unison plug-in before the Sphere plug-in.

## Using digitally controlled mic preamps

Although a Sphere microphone can work with virtually any two-channel mic preamp with 3-pin XLR inputs and 48V phantom power, we recommend preamps with precision digital gain control or analog stepped gain adjustment so the channel levels can be easily matched.

Preamps with digitally controlled gain include those found in Universal Audio’s Apollo series interfaces with mic inputs. Digitally controlled preamps have the additional advantage of linking channels so their levels move together when one preamp is adjusted.

## Using stepped-gain mic preamps

Preamps with stepped analog gain adjustment, such as a Neve 1073, work well with Sphere. Since the mic modeling assumes some of the character of the preamp used, great results can be obtained from devices with more vintage color. However, for best results with Sphere, set your preamp gain to avoid clipping and disable all the preamp’s filters, pads, phase switches, and EQ.

Some analog stepped gain preamps also have a continuous fine adjustment knob, which must be set properly. Usually the maximum or middle position works best to easily match levels between channels. We recommend <a href="12233094069140-Installing-and-Configuring-Sphere.html#h_01GPDAMXW4RV0KD9W5WWJD49C3" target="_self">calibrating the preamp</a>, especially if the preamp has a fine adjust knob, to verify that the levels are properly matched.

## Using continuous gain mic preamps

It is possible to use Sphere with preamps that have continuously adjustable gain, such as those from API, Midas or SSL, although it is necessary to <a href="12233094069140-Installing-and-Configuring-Sphere.html#h_01GPDAMXW4RV0KD9W5WWJD49C3" target="_self">recalibrate the mic</a> to match levels each time the gain is adjusted.

## Understanding input impedance

We recommend a preamp with a 2000-ohm (or higher) input impedance, although the mic is designed to work down to about 1000 ohms. If your preamp has variable impedance, we recommend setting it to the highest value because that generally allows for the best gain matching between channels.

## Using phantom power

The preamp must provide 48V phantom power in accordance with the IEC 61938 specification and must be able to deliver up to 8 mA of current per channel. The mic draws about 8 mA at maximum sound pressure level and about 5 mA at more typical levels.

## Using preamp modeling plug-ins

If you use a software preamp modeling plug-in, such as those from Universal Audio, we typically recommend placing it directly after the Sphere plug-in to match the virtual signal chain with the corresponding physical signal chain. In this case, it usually makes sense to use a clean, transparent hardware preamp, so preamp coloration is only applied once. However, if you like the sound created by combining the coloration of hardware and software pre­amps, feel free to use it that way.

### Using Unison preamp models

We generally recommend placing the Sphere plug-in first in the signal chain, or using only a clean (not overloaded) Unison plug-in before the Sphere plug-in.

If you want to use  a preamp modeling plug-in for obvious saturation, we recommend using the preamp plug-in in a standard insert after the Sphere plug-in.

