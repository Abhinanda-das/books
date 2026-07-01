---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12241850778260-Recording-Acoustic-Guitars-with-Sphere.html'
converted_at: 2026-05-31T13:44:43Z
tool: htmlq+pandoc
title: 'Recording Acoustic Guitars with Sphere'
word_count: 1708
---

# Recording Acoustic Guitars with Sphere


#### In this article

- <a href="#h_01GPDAD1576JG2ANXJJZE0EVKT" target="_self">Understanding Sphere features for acoustic instruments</a>
- <a href="#h_01GPDAD7J1G32WJCZKW55XS33M" target="_self">Placing the mic</a>
- <a href="#h_01GPDADCT6CP8626DV5QW1NANP" target="_self">Recording guitar and vocals</a>
- <a href="#h_01GPDADKYMQPPCDDZAF0NG1W5F" target="_self">Recording stereo acoustic guitar</a>

### Understanding Sphere features for acoustic instruments

Sphere mics include a number of features that let you obtain a natural, traditional acoustic guitar sound, or something more modern with a wide stereo spread. The Sphere system lets you adjust mic type and polar pattern, even after tracking, which can be extremely helpful for dialing in the right sound. Most of the techniques described here can also be applied to recording other acoustic instruments.

The pattern and off-axis settings control the amount of room sound picked up by the mic. The bass response of an acoustic guitar is often exaggerated due to the proximity effect, especially when a mic is pointed near the guitar’s sound hole. Angling the mic towards the neck or pulling it farther back from the guitar can solve the bass problem, but this changes other aspects of the sound. With Sphere technology you can independently adjust the amount of proximity effect, which provides more flexibility in mic placement. The Proximity control adjusts the amount of proximity effect in a different way than just applying EQ. In fact, this control changes the polar pattern of the mic at low frequencies, simulating what would happen if the capsule was physically modified to have a different amount of proximity effect.

### Placing the mic

Even though Sphere technology lets you adjust a wide range of parameters after recording, there is no substitute for proper mic placement. Many acoustic instruments, including acoustic guitar, have complex dispersion patterns, which means that each area of the instrument can radiate very different sounds. For example, the neck area of an acoustic guitar emits a bright, crisp sound compared to the soundhole, which produces more low frequencies. You can emphasize string and fret sound by placing the mic further up the neck and/or closer to the strings.

**Tip:** Put your finger in one ear and listen to the guitar at various potential mic locations until you find a spot you like, and place the mic there. If you are recording alone, you can monitor the guitar with isolated headphones while playing, and move the guitar around to find the best spot. 

### Recording guitar and vocals

You can record an acoustic guitar and vocals with one mic or with two mics.

#### Recording with two mics

For a guitarist who sings, it is often desirable to record the guitar and vocal at the same time to capture a live performance, instead of relying on overdubs. Typically accomplished using separate mics for the vocal and guitar, this technique can work well, but you must consider bleed from the off-axis sources. The bleed will generally be out of phase with the on-axis sound, so comb-filtering will result when the two tracks are mixed together. Even if the mics are aligned well enough to prevent comb-filtering, the high frequency response will likely be compromised due to small differences in distance. Since sound at 20 kHz has a wavelength less than 2 cm, just a difference of a few millimeters can noticeably affect the high frequency response. In most cases, it is impractical to align mics with that degree of accuracy.

All of these issues are further complicated when EQ, compression, and other processing is added to the individual tracks. Equalizing the guitar track also applies that EQ to the bleed from the vocal, and vice versa. Therefore, it can be difficult to find EQ settings that work well for both the vocal and the guitar. Compression can also increase the level of the bleed relative to the primary source, which can exacerbate phase issues.

Cardioid mics are often used in this application for their directionality, but bleed can still be a problem: at 90° off-axis, the level is only 6 dB down. Another common approach uses a mic with a figure-8 pattern, such as a ribbon or multi-pattern condenser, because the response at 90° off-axis is close to zero. This allows placing the acoustic guitar in the null of the vocal mic, while still getting good direct vocal pickup. The guitar mic is pointed directly at the guitar but oriented to reject the vocal. With proper placement, this can produce an incredible amount of isolation between the guitar and vocal, so you hear just reverb from the off-axis source, with virtually no dry signal.

The illustration below shows this technique in action. The vocal mic is on top with a polar pattern shown by the blue figure-8, and the guitar mic is below with a polar pattern shown by the magenta figure-8. Each mic is positioned to reject the other’s sound.

![acoustic-guitar-vocal-side-view.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/6a4f15bf8bbd4c6adc8699727346b5ac9bc2cdd1.png)

*Recording acoustic guitar and vocals with two mics*

One potential problem is that figure-8 mics tend to have certain sonic qualities, such as significant proximity effect, that can be great for some applications but less ideal for others. The Off-Axis Correction feature solves this problem by letting you independently select the polar pattern from the mic type. For example, to get the sound of a 47 microphone set to cardioid but with the isolation of a figure-8 pattern:

1.  Select LD-47 as the mic type with a cardioid pattern.
2.  Set the Off-Axis Correction pattern control to figure-8.

The goal is not to create an equivalent mic, but rather a hybrid specifically optimized for the current application.

#### Recording with one mic

If you don’t have two Sphere mics, you can still approximate the two-mic setup by using the front side for vocals and the rear side for guitar (see the illustration below).

1.  In your DAW, instantiate the Sphere 180 plug-in on a stereo track.
2.  Assign the left output to the vocal and right to guitar.
3.  Enable Off-Axis Correction and set the pattern to cardioid to minimize the bleed from the off-axis source.

With conventional cardioid mics, the rear sound pick up is typically very colored due to physical limitations of the capsule, which can largely be avoided using Off-Axis Correction.

![acoustic-guitar-vocal-side-view-single-mic.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/bb77225eafe3eb9d818e9139f830140da673bd5b.png)

#### *Recording acoustic guitar and vocals with one mic*

 

### Recording stereo acoustic guitar

#### Recording with one mic

For a rich, spacious sound it is often desirable to record acoustic guitar in stereo. A wonderful application of the Sphere system is recording in stereo with one mic using a Sphere 180 plug-in. By rotating the mic 90° off-axis, the front and back correspond to the left and right channel outputs, respectively.

One major benefit of this approach is that the two capsules are close enough to avoid the phase issues that can occur with non-coincident stereo mic placement. Although coincident mic techniques tend to produce a narrower stereo image than some others, the Sphere’s back-to-back capsule configuration produces the widest stereo spread of any coincident setup, and is comparable in width to spaced pairs. We recommend using a cardioid or supercardioid pattern for both outputs, with supercardioid producing a wider stereo image.

A good starting point is to place the mic around the 12th fret of the guitar. For some guitars, this may result in too much bass from the bridge or a thin trebly sound from the neck, so move the mic between them to find the sweet spot (see the illustration below).

![acoustic-guitar-single-mic-stereo.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/5eabc97a4dfc839db9e36870b554c9e7c504dd98.png)

*Recording acoustic guitar in stereo with one mic near neck*

Another option is to line the mic up with the soundhole but at roughly the height of the guitarist’s head. This can create a more balanced sound, since both capsules receive the same level from the soundhole, but without getting a direct hit. It can also give a more natural and familiar sound because the mic capsules are positioned near the guitarist’s ears.

![acoustic-guitar-single-mic-stereo-pos-2.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/2ea5b088fe6e779595e7c61701ee63140cb08eef.png)

*Recording acoustic guitar in stereo with one mic above guitar*

But even after finding a position that you like, there can still be a large timbral imbalance between channels. With conventional mics this is sometimes handled by choosing a small condenser for the bridge that is brighter, and a ribbon for the neck that is darker. The Sphere 180 plug-in lets you select different mic models for each output, so this effect can be achieved with just one physical mic.

#### Recording with two mics

With two Sphere microphones you can use any standard stereo technique (e.g., XY, spaced-pair, ORTF, mid-side, or Blumlein) but now with enhanced flexibility. The top illustration below shows a horizontal 90° XY configuration, while the bottom shows the same XY configuration oriented vertically. Either option can work well, so choose the easier setup.

![acoustic-guitar-xy-stereo.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/e614caa5bc3c92f97aeba88cf2f3a0a9a439dd54.png)

![acoustic-guitar-xy-stereo-vertical.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/6ab9fa93da32875a07282d395457900d6cf5a8c0.png)

*Recording acoustic guitar in stereo using XY technique: horizontal (top), vertical (bottom)*

Because a Sphere plug-in lets you change the mic pattern as you work (even after recording), you can switch from XY to Blumlein by simply adjusting the pattern controls from cardioid to figure-8. You can also select a sub-cardioid pattern for a narrower stereo image, or hypercardioid for a wider image without picking up as much room sound from behind the mics.

![acoustic-guitar-blumlein-stereo.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/ba2a2c95c5b4120e41f031aaf268e06b6b8fe537.png)

*Recording acoustic guitar in stereo using Blumlein technique*

Another common micing technique for acoustic guitar is the spaced-pair. Start with one mic near the bridge and the other at the neck near the 12th fret (see the illustration below).

A spaced pair can produce excellent results, but like any non-coincident technique, sound arrives at the mics at different times. This can result in comb filtering and mono incompatibility.

![acoustic-guitar-spaced-pair-stereo.png](Recording%20Acoustic%20Guitars%20with%20Sphere_assets/9466da7522e4b7163965149f190a8ec978eb9b6c.png)

*Recording acoustic guitar in stereo using a spaced pair technique*

To minimize phase issues, set the distance between mics to at least three times the distance from each mic to the guitar.

**Tip:** To verify that phase is coherent, sum the left and right channels to mono and listen for comb filtering or other artifacts.

This just scratches the surface of how to best record acoustic guitar with a Sphere mic. For more a more in depth look at this topic, see the following excellent Sound On Sound magazine article:

[How to Record a Great Acoustic Guitar Sound](http://www.soundonsound.com/sos/apr10/articles/acguitar.htm)

See <a href="https://help.uaudio.com/hc/en-us/articles/12241922517012" target="_self">Recording in Stereo with Sphere</a> to learn more about single and multiple mic stereo setups.

 

