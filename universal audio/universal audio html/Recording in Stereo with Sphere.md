---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12241922517012-Recording-in-Stereo-with-Sphere.html'
converted_at: 2026-05-31T13:44:43Z
tool: htmlq+pandoc
title: 'Recording in Stereo with Sphere'
word_count: 975
---

# Recording in Stereo with Sphere


## In this article

- <a href="#h_01GPDASAJR89MD82P3C4HRCXEW" target="_self">Recording in stereo with a single Sphere mic</a>
- <a href="#h_01GPDASGYT5T71AABGR17K0W8V" target="_self">Recording in stereo with two Sphere mics</a>

The Sphere DLX and L22 mics provide numerous options for stereo recording. Any stereo micing technique, such as XY, spaced pair, MS, and ORTF, can be used effectively with a pair of Sphere microphones, just as you would with conventional mics. But it’s also possible to record in stereo with a single Sphere mic, by using the Sphere 180 plug-ins. You even can record 4- or 5-channel surround with two Sphere mics.

**Note:** To use a Sphere 180 plug-in, you must use a Sphere DLX or L22 mic.

# Recording in stereo with a single Sphere mic

Recording stereo with a single Sphere mic is simple. A Sphere microphone can create two virtual mics with one pointing forward and the other pointing backward. For stereo recording, rotate the mic 90°, so the front output becomes the left channel, and the rear output becomes the right channel. This provides a 180° (back-to-back) capsule arrangement. To use the microphone in stereo mode, use a Sphere 180 plug-in to provide discrete left and right outputs.

Because the left and right diaphragms are coincident, perfect phase coherence is always maintained, even when the channels are summed to mono. For a coincident mic technique, this produces the widest stereo spread possible, but leaves a space in the center of the stereo field. This occurs because the center of the stereo field corresponds to 90° off-axis from each capsule, which is where the high frequency response is typically lowest. This technique creates a wide-panned stereo recording with space in the middle for centered information. The best results are usually achieved by setting the polar pattern to somewhere between cardioid and supercardioid, with supercardioid providing a wider stereo field.

**Note:** Hypercardioid patterns can widen the stereo field further, but can also create phase prob­lems.

It is also possible to have independent mic models applied to the left and right outputs. For acoustic guitar recording, pickup from the sound holes is often bass heavy, so the bridge side ends up being boomy and the neck side too bright. You can compensate for this by choosing a bridge side mic model that has less bass, and a neck side model that has more bass (for example, use an SD-451 small diaphragm condenser on the neck, and an LD-67 large diaphragm condenser mic on the sound hole).

# Recording in stereo with two Sphere mics

If you have two Sphere mics, you can record with a wider range of stereo techniques. In general, you can use the same stereo techniques that you use with standard mics, although there are some advanced features, such as Off-Axis Correction, which can provide more flexibility.

With two Sphere mics you can even go beyond stereo to mic in quad, or 5.0 surround. To do this,  set the mics up in an XY configuration, with each mic positioned coincidently 90° off-axis from the other. From this you can capture front left and rear right outputs from one mic and the front right and rear left outputs from the other mic. Cardioid patterns are typically used for all mics in this application.

To create a center channel for 5.0 surround, the simplest option is to sum the left and right virtual mic outputs. This creates a center-panned virtual cardioid mic (assuming left and right outputs are cardioid). Another option is to sum the raw unprocessed outputs of both mics and send them to a stereo bus with another Sphere plug-in. This lets the user set the center channel polar pattern independently. Set the pattern to super- or hypercardioid to produce better separation of the center from the left and right channels. Since there are many possibilities, experiment to figure out what sounds best for your application.

## Using Off-Axis Correction with stereo recordings

Consider a stereo recording of a double bass, where the low frequency fundamentals will be perceived more towards the center than the high frequency harmonics. Instead of occupying one point in the stereo field, this single instrument will be spread out. 

You can specify the distance to the source using the Off-Axis Correction controls to manage the frequencies of such an instrument. 

- Use the ON-AXIS DISTANCE to specify the distance from the source to the mic.
- Use the OFF-AXIS DISTANCE to specify the distance from the off-axis source material to the mic.

You do not need to set these controls exactly, but can instead dial in the sounds by ear. To adjust for multiple sources, use or estimate an average distance, or tune these settings by ear.

## Using Off-Axis Correction with mid/side and other configurations

Off-Axis Correction can be useful in mid-side and other stereo and surround configurations that use heterogeneous mic configurations. For example, with mid-side, the mid channel is either a cardioid or omni mic and the side channel is a figure-8 mic. Because of the inherent pattern response, the figure-8 mics always have a different frequency response than omni and cardioid mics, so the mid-side encoding has frequency dependent errors in the response. To some degree this is unavoidable, but with Off-Axis Correction you can correct for some of the differences in frequency and polar response, resulting in a better mid-side recording.

## Adjusting Proximity Effect for stereo recordings

When recording in stereo with directional mics, the distance from the sources are often far enough to cause the bass response to drop significantly, due to the proximity effect. For many directional mics, the flattest bass response is approximately 0.5 m from the source.

In a Sphere plug-in, adjust the PROXIMITY control in the positive direction to correct for the loss of proximity effect. This can create a much fuller sounding recording.

