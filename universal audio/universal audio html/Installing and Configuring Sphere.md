---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12233094069140-Installing-and-Configuring-Sphere.html'
converted_at: 2026-05-31T13:44:42Z
tool: htmlq+pandoc
title: 'Installing and Configuring Sphere'
word_count: 1709
---

# Installing and Configuring Sphere


## In this article

- <a href="#h_01GPDAKJ5PQQ82V5S6DQZTRE3Z" target="_self">Sphere system requirements</a>
- <a href="#h_01GPDAKRG0R12NT9TQBMDTAC1Z" target="_self">Getting your UA Sphere plug-ins</a>
- <a href="#h_01GPDAKXBMQZEC5MRMPBQD406Z" target="_self">Connecting your Sphere mic</a>
- <a href="#h_01GPDAM5H9QZS3PM7CKH0W26VN" target="_self">Getting started with UA Sphere plug-ins</a>
- <a href="#h_01GPDAMDCZ32ADRJHFQ3Q4VPXX" target="_self">Selecting your source mic</a>
- <a href="#h_01GPDAMXW4RV0KD9W5WWJD49C3" target="_self">Calibrating a preamp with continuous gain</a>
- <a href="#h_01GPDAN7JFQB4JW19XRT7V6RSA" target="_self">Selecting a mic model in the Sphere plug-in</a>

# Sphere system requirements

For complete system requirements, please visit [this article](11035939427476-Sphere-System-Requirements.html).

# Getting your UA Sphere plug-ins

Visit [this article](13181557495572-UA-Connect-with-UA-Microphones.html) to learn how to get your Sphere plug-ins with the UA Connect app.

# Connecting your Sphere mic

To use the features of the Sphere plug-ins, you must connect your Sphere mic to two separate channels on your audio interface, preferably a linked left and right input pair. 

#### To connect the Sphere to your preamp channels

1.  Connect the 5-pin side of the included breakout cable to your Sphere mic.\
    This cable separates the two signals from Sphere’s dual mic capsules into two conventional 3-pin XLR cables that you connect to the XLR inputs on your preamp channels.
2.  Connect the Sphere’s white XLR output (labeled 1-Front) to the first of a pair of mic connectors on your mic preamp (for example, 1/Left).
3.  Route the Sphere’s red XLR output (labeled 2-Rear) to the second of a pair of mic connectors on your mic preamp (for example, 2/Right).\
    **Tip:** Use consecutive, linkable channels if available.
4.  Enable Channel Linking for the pair of channels on your mic preamps (if available).\
    This automatically keeps both preamp channels set to the same level when either is adjusted.
5.  Disable all filters, pads, EQ, and other processing on both mic preamp channels.
6.  Enable 48V phantom power on both mic preamp channels.

The LEDs inside the headbasket illuminate when phantom power is applied to both mic channels.

![sphere-connections.png](Installing%20and%20Configuring%20Sphere_assets/e4f28d0290e0116afcbfb276e2b66ccd0d4b354f.png)

*Connecting a Sphere mic to an audio interface*

 

## Understanding digital gain control and levels

If your audio interface has digital gain control (for example, a Universal Audio Apollo), you can easily calibrate each channel to the same precise level. We recommend that you enable stereo linking for the channels so the gain for both channels can be adjusted simultaneously.

If your preamp does not have digital gain control or precision analog stepped gain adjustment, <a href="#h_01GPDAMXW4RV0KD9W5WWJD49C3" target="_self">calibrate your preamp</a>.

# Getting started with UA Sphere plug-ins

To get your system running quickly, use the following instructions. For full details on how to configure particular monitoring scenarios, see <a href="12241582040084-Using-Sphere-Mics.html#h_01GPD87N6XAG5J8PRD7ZE4BKVR" target="_self">Understanding your DAW signal flow</a>.

## Using a Sphere plug-in in your DAW

1.  Create a stereo track in your DAW.
2.  Assign your mic preamp channels to the stereo track inputs.
3.  Select a Sphere plug-in as the first track insert.

### Using native or DSP plug-ins

- To run the native version of the plug-in on your computer’s CPU, choose Sphere Mic Collection (without the UAD prefix). 
- To run the DSP version of the plug-in on UAD hardware, choose UAD Sphere Mic Collection, UAD Ocean Way Mic Collection, or UAD Putnam Mic Collection.
- To run the AAX DSP version of the plug-in with Pro Tools HDX hardware, switch the Pro Tools track to DSP mode.

### Checking cable orientation

The left and right channels correspond to the front and rear capsules, respectively. When speaking into the front capsule and monitoring the track, you should hear (and see on the meter) significantly more level from the left channel. If that is not the case, swap the inputs on the mic preamps.

![sphere-interface.png](Installing%20and%20Configuring%20Sphere_assets/fad204a2356dc142a41f0f5e99bf32202b30ac73.png)

*Main window — Sphere Mic Collection*

## Using a UA Sphere plug-in in Apollo Console

If you are using your Sphere mic with a Universal Audio Apollo recording interface, you can use Realtime UAD Processing with Apollo’s Console to monitor and/or record the Sphere system without apparent latency.

#### To instantiate a Sphere plug-in in Console

1.  Open Console, locate the channel pair connected to the Sphere mic, and confirm that the chan­nels are linked and 48V phantom power is enabled.
2.  Select the UAD Sphere Mic Collection, UAD Putnam Mic Collection, or UAD Ocean Way Mic Collection plug-in as the first channel insert (see the screenshot below).

### Choosing UAD REC or UAD MON

Console allows you to choose whether to monitor or record the Sphere plug-in output. 

#### To commit Sphere plug-in processing to disk when recording

- Enable the UAD REC button (to commit all plug-in processing on all channels)
- Click the small LED to the right of the INSERTS label so it is red (to commit all plug-ins only on one channel). 

See the [Apollo Thunderbolt Software Manual](13445960631700-Apollo-Software-Manuals.html) for details.

![console-strip-with-plug-uad-rec.png](Installing%20and%20Configuring%20Sphere_assets/2dc4abf45d25259d797627d31bbb12e08d633fbc.png)

*Console with Sphere plug-in as first channel insert, 48V active, UAD REC button enabled*

**Note:** We generally recommend placing the Sphere plug-in first in the signal chain, or using only a clean (not overloaded) Unison plug-in before the Sphere plug-in.\
To use a preamp plug-in to add obvious distortion or saturation, we recommend placing the color plug-in after the Sphere plug-in. See <a href="12241582040084-Using-Sphere-Mics.html#h_01GPD87N6XAG5J8PRD7ZE4BKVR" target="_self">Understanding your DAW signal flow</a> for details.

# Selecting your source mic

When you first open a Sphere plug-in, the Select Your Source Mic screen prompts you to select the physical mic that you want to use. Double-click the mic you want to use. If you want to change the physical mic selection, follow these steps. 

#### To select a Sphere source mic

1.  Click the **DLX** button next to **Source Mic** at the bottom left of the Sphere plug-in**.**\
    DLX is the default selection.
2.  Choose Sphere DLX, Sphere LX, or Sphere L22.
3.  Double-click the mic selection, or click the X at the top right of the screen to close the mic selection screen.

This setting is stored in your Preferences so future Sphere sessions bypass this process and display the main Sphere plug-in window.

# Calibrating a preamp with continuous gain

Use this procedure to calibrate two mic preamp channels that have continuous instead of stepped gain adjustment (for example, a Universal Audio Volt). 

**Tip:** If your audio interface has stepped gain controls, you can skip this procedure.

#### To calibrate the input channels on a mic preamp with continuous gain 

1.  Connect the microphone connectors to the preamp channels, and enable phantom power.
2.  Place the mic with the front pointing at your sound source.
3.  Create a stereo track in your DAW, and assign the preamp channels to which your Sphere mic is connected as its inputs.
4.  Instantiate a Sphere plug-in on the track. 
5.  Adjust the preamp’s Mic 1 channel gain to an appropriate level for your intended sound source, and adjust the gain for the second channel to approximately the same setting.\
    **Note:**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> When speaking into the front capsule and monitoring that track, you should hear significantly more level on the channel connected to the Mic 1 connector. If that is not the case, swap the inputs on the preamps.</span>
6.  Set the CAL/ON switch on the Sphere mic to the CAL position.\
    ![cal-switch.png](Installing%20and%20Configuring%20Sphere_assets/88b4241d3be605d4efb1713d5cc4d09a43ca9bf9.png)\
    \
7.  Click the SETUP button on the bottom-right of the plug-in to display the calibra­tion dialog.\
    ![sphere-calibration.png](Installing%20and%20Configuring%20Sphere_assets/f2532807cc745b35988d07afaa4c75b3d10ae8fb.png)
8.  Adjust the gain of the Mic 2 channel to match the gain of Mic 1 using the Level Calibration Meter.
9.  If you cannot match the levels within 0.1 dB, press the AUTO button on the Setup page to better match the levels.
10. When finished, set the CAL/ON switch on the mic to the ON position.

The Sphere mic LEDs illuminate to indicate the mic is ready for normal use.

# Selecting a mic model in the Sphere plug-in

You select a mic model to make your Sphere mic sound like one of the modeled mics included with your Sphere plug-in. 

You can change between mic models by clicking the arrows near the bottom-left and right of the mic picture to navigate to the previous or next mic model, respectively.\
![mic-left-right-arrows.png](Installing%20and%20Configuring%20Sphere_assets/928ea073bbb466d663d998a3ca4464f160c6b538.png)\
\

#### To display all available mic models in the plug-in

1.  Click the mic model name.\
    An overlay with the available mic models is displayed. Tabs at the top organize the mic models into Large Condenser, Hybrid, and Custom categories.\
    ![sphere-select-mic-models.png](Installing%20and%20Configuring%20Sphere_assets/58d0fdf0b8dc5d31eaacdbc55ebb6966171ee1bd.png)\
    \
2.  If <a href="12237363559316-Using-UA-Sphere-Plug-Ins.html#h_01GPEHZET2YTN1D6FQSZ4BD1RX" target="_self">Tool Tips are enabled</a>, hover over the mic model to display helpful information about that mic’s history and usage.
3.  Click the **X** or double-click the mic to exit the mic model selection window.

**Note:** Sphere LX has fewer mic models than Sphere DLX and Sphere L22.

## Orienting your Sphere mic to an audio source

- To record a source in mono, point the front of the microphone (denoted by the circle inside a circle icon and the Universal Audio badge) at the desired sound source.
- To record a source in stereo (Sphere DLX and Sphere L22 only), orient the microphone so the overlapping circles point towards the sound source.

![sphere-front-and-side-view.png](Installing%20and%20Configuring%20Sphere_assets/beb0bb08e9bcd708f26e1c16834d7d5d82894717.png)

*Point front of mic (left) to source for mono; point side of mic (right) to source for stereo*

## Using the pad switch on your Sphere mic (DLX and L22 only)

The pad switch on the Sphere DLX and L22 mics increase the available headroom so the mics can handle louder levels without clipping or distortion. The pad switch on each mic should typically be set to 0 dB for most sources, which can handle sound pressure levels (SPLs) in excess of 120 dB. 

When close-micing a loud source, such as a guitar amp or drum kit:

- set the pad switch to the -20 dB setting to handle up to 140 dB SPL
- set the pad switch set to -10 dB (L22 only) to handle up to 130 dB SPL

## Using the shockmount or stand mount

All Sphere microphones include a microphone stand mount. With Sphere DLX or L22, you can use the supplied shockmount to reduce unwanted rumble and low frequency noise. 

## Storing your mic when not in use

When the mic will not be used for a prolonged period, it is important to store it in the supplied carrying  case. Do not store or use the mic in conditions of extreme temperature and/or humidity.

