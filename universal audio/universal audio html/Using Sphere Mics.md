---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12241582040084-Using-Sphere-Mics.html'
converted_at: 2026-05-31T13:44:42Z
tool: htmlq+pandoc
title: 'Using Sphere Mics'
word_count: 1095
---

# Using Sphere Mics


## In this article

- <a href="#h_01GPD87N6XAG5J8PRD7ZE4BKVR" target="_self">Understanding your DAW signal flow</a>
- <a href="#h_01GPD87X4DJYKXEEPAEVVZ4F9Y" target="_self">Monitoring your Sphere mic</a>
- <a href="#h_01GPD889Y3SFKGJM6W1537TM5B" target="_self">Positioning your Sphere mic</a>
- <a href="#h_01GPD8CZZS4GME68N6RY8E7WJP" target="_self">Using your Sphere mic with a single preamp channel</a>

In many ways using a Sphere microphone is like using any conventional microphone. However, a Sphere mic offers advanced features that a standard mic does not. This article includes some  basic concepts that will help you when using your Sphere microphone system.

# Understanding your DAW signal flow

The illustration below shows the signal flow using a mono Sphere plug-in. In most cases we recommend routing the outputs from the Sphere mic directly to the Sphere plug-in without any intermediate processing, such as EQ, compression, or panning. Place any additional signal processing, including other plug-ins or analog outboard gear, after your Sphere plug-in.

**Note:** We generally recommend placing the Sphere plug-in first in the signal chain, or using only a clean Unison plug-in before the Sphere plug-in. 

![sphere-audio-diagram-basic.png](Using%20Sphere%20Mics_assets/19804ea6780dc0a4cc441d179e05df14d93e0e3d.png)

*Basic Sphere signal chain *

Sphere (non-180) plug-ins output a dual-mono signal out of your stereo track (the same signal on both channels), just like a conventional mic. However, the Sphere 180 plug-ins route the left and right mic models to left and right stereo outputs.

# Monitoring your Sphere mic

There are three recommended workflows for monitoring Sphere:

- Real time monitoring with Apollo Console and UAD Sphere plug-in
- Software monitoring native Sphere plug-in using your DAW
- Hardware monitoring the direct microphone output

## Monitoring in real time with Apollo Console

When monitoring with Console, UAD plug-ins provide ultra-low latency processing and deterministic real-time performance. See the [Apollo Software Manual](13445960631700-Apollo-Software-Manuals.html) for information about how to create monitoring paths.

![sphere-apollo-connections-basic.png](Using%20Sphere%20Mics_assets/5f1e22f4554bb9f682c2178cc2d035bde38cc50b.png)

*Sphere signal chain using Console for monitoring*

#### To monitor your Sphere mic in real time with Console

1.  In your DAW, disable software input monitoring.
2.  In the Universal Audio Console application, click one of the mic preamp channels connected to the mic, and enable Stereo Link mode.\
    This links the two channels into one stereo channel.
3.  Instantiate the UAD Sphere Mic Collection, UAD Putnam Mic Collection, or UAD Ocean Way Mic Collection plug-in on the first insert of this stereo channel.
4.  Set the Console channel output to the appropriate monitor destination.

**Tip:** You can activate UAD MON to monitor only UAD effects, or UAD REC to record and monitor UAD effects.

## Monitoring the native plug-in with your DAW

You can monitor the Sphere mic live in your DAW from the Sphere plug-in output. You might prefer this if you normally use your DAW and native plug-ins to manage mon­itoring. With this method, you will incur some monitoring latency associated with I/O buffering, and this latency will be greater than when monitoring using Apollo Con­sole, the direct microphone output, or a hardware monitoring option.

![sphere-daw-connections-diagram-native.png](Using%20Sphere%20Mics_assets/8cb2b193f4cab1f1e4de37fd52d4282bb9eb4196.png)

*Sphere signal chain using DAW software monitoring*

#### To monitor your Sphere mic in your DAW with the native plug-in

1.  Disable low-latency processing mode in your DAW (if it has that option).
2.  Instantiate the Sphere Mic Collection, UAD Putnam Mic Collection, or UAD Ocean Way Mic Collec­tion plug-ins on an input-enabled stereo track.
3.  Route the output of this stereo track to your headphones or other monitoring outputs.

## Monitoring the direct analog microphone output

If you cannot monitor in real time or with usably low latency through the Sphere plug-in on your system, you can monitor the front capsule of the Sphere mic without any processing, then apply plug-in processing to the recording later.

Your interface may include a “direct monitoring” or “hardware monitoring” option, or a hardware routing matrix in the included interface software. See your audio interface’s user manual for more information about how to create direct monitoring paths.

![sphere-daw-connection-direct-out.png](Using%20Sphere%20Mics_assets/713571b5479ebe901b1c246b5dcc4fe9450559c1.png)

*Sphere signal chain with direct monitoring of front capsule*

#### To monitor the direct analog output from your Sphere mic

1.  Connect the front and rear mic outputs to your mic preamp (either standalone or as part of your audio interface).
2.  Route the front output of the Sphere mic to your monitor destination.
3.  Route the front and rear mic outputs to your audio interface.

This enables you to monitor the mic’s front output, while recording both outputs, which you can then process via the Sphere plug-in after tracking is completed.

# Positioning your Sphere mic

To get results that compare accurately with a modeled microphone, it is essential that you properly position the Sphere mic. Even a few millimeters difference in mic position can have a significant effect on the sound.

For example, let’s say you found a great setup for a Neumann U67 on a guitar amp, but do not want to risk taking your prized U67 on the road. Instead you can use the Sphere DLX and leave the U67 in the studio. To obtain the same sound as your U67, you must place the Sphere DLX in precisely the same position as the U67.

Because it is the position and orientation of the capsules that must be precisely aligned, not the mic bodies, this is not as simple as it seems. It is often difficult to see exactly where the capsules are located behind the grill.

**Tip:** Use a high intensity flashlight to see where mic capsules are positioned.

The illustration below compares the Sphere DLX capsule alignment to a Neumann U67/U87. The crossed dashed lines show the center position of the capsules. As you can see, aligning the mic bodies misaligns the capsules. 

![align-sphere-u67.png](Using%20Sphere%20Mics_assets/f0f89963c6b2319766576f2d743f92adf6a10adf.png)

*Lining up capsule centers for Sphere and Neumann U67/U87 *

The illustration below shows a close-up view of the Sphere DLX from the front and side, so you can easily see where to align the microphone.

![sphere-capsule-front-side.png](Using%20Sphere%20Mics_assets/84f25cf6211416f6b16c2559e84fe346823c77c2.png)

*Close-up view of Sphere capsule from front (left) and side (right)*

# Using your Sphere mic with a single preamp channel

A Sphere microphone is actually two independent, high-quality, back-to-back, cardioid condenser mics, but it can be used as a conventional single channel mic without microphone modeling. Each output has a cardioid pattern so you can use the microphone as you would any large diaphragm cardioid condenser mic.

When only one output of the microphone has phantom power applied, only that corresponding chan­nel is enabled. The sound quality of the front mic output is equivalent to the rear output, so you can use either side. In single channel mode the mic’s 48V indicator LEDs do not illuminate.

**Note:** Sphere plug-ins are not designed for use with a single Sphere mic capsule channel.

