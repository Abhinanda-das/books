---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12241698003732-Using-Sphere-Off-Axis-Correction.html'
converted_at: 2026-05-31T13:44:42Z
tool: htmlq+pandoc
title: 'Using Sphere Off-Axis Correction'
word_count: 2189
---

# Using Sphere Off-Axis Correction


## In this article

- <a href="#h_01GPD96MF3MZEA302VWX9PX7GZ" target="_self">Overview of polar patterns and frequency response</a>
- <a href="#h_01GPD96YM3QE5XTTYBENP6JH64" target="_self">Understanding the technical details</a>
- <a href="#h_01GPD974SW03CYDSS898EYWT76" target="_self">Understanding proximity effect</a>
- <a href="#h_01GPD97BMN3EQMF152JCE4XNW7" target="_self">Configuring Off-Axis Correction</a>
- <a href="#h_01GPD97J7BRM81MXDRRDVYHSBY" target="_self">Capturing more room ambience</a>
- <a href="#h_01GPD97RZS8CYX0FAN6R0W9VQP" target="_self">Understanding applications for Off-Axis Correction</a>

# Overview of polar patterns and frequency response

Frequency-dependent polar response is part of what gives each mic its special character. However, this polar response can also cause problems, such as increased bleed, coloration of the room response, and susceptibility to feedback. Off-Axis Correction can reduce all of these problems, while still maintaining the on-axis frequency response characteristics. The direct sound is not affected. 

The polar patterns for virtually all conventional cardioid mics vary substantially with frequency. A typical large diaphragm condenser mic might be cardioid in the range from 1–2 kHz, omnidirectional below 150 Hz, and figure-8 (or other non-cardioid patterns) at higher frequencies. These variations from an accurate cardioid response are important factors that characterize the sound of every microphone, and even the best have such properties. However, when acoustics are not ideal or other instruments bleed into the coverage area of the mic, this polar response can cause problems. Sphere’s Off-Axis Correction feature improves the mic’s polar response by applying DSP compensation to create a more consistent off-axis response across the frequency spectrum.

Most mics are designed to have excellent sounding cardioid and omni polar patterns. Although a mic may have hypercardioid and other polar pattern options, these patterns may not always have the best sound, as is the case with the AKG 414 and Neumann TLM-170. The change in the sound of a mic between its polar patterns can often be quite dramatic, and hypercardioid and figure 8 patterns are often not useful for vocals. Additionally, a cardioid mic gives the best frequency balance, but also exhibits greater proximity response effects. 

Sphere’s Off-Axis Correction can adjust a mic’s inaccurate cardioid pattern into a more accurate cardioid pattern across its full audible spectrum. This creates better off-axis rejection and a less colored off-axis response. More importantly, Off-Axis Correction lets you set the mic model, and consequently its on-axis response and entire polar pattern independently. This means you can take any mic model, such as a cardioid 87 type mic, and apply a different pattern, such as hypercardioid, that is not found in the original mic, while still maintaining the overall sonic character.

# Understanding the technical details

This section provides a brief technical explanation of Off-Axis Correction, which can help you understand how to best use it. 

## Understanding microphone polar frequency response

The illustration below shows the published polar pattern of a Neumann U87ai in the cardioid setting at 125 Hz (blue), 1 kHz (red), and 4 kHz (green). Notice that the pattern is actually cardioid only at 1 kHz. The pattern approaches omnidirectional at 125 Hz, and is roughly hypercardioid at 4 kHz.

![polar-pattern-u87ai.png](Using%20Sphere%20Off-Axis%20Correction_assets/cc8ab292da247ed0df1dcaa1a251a5b995c7cbe4.png)

*U87ai cardioid polar pattern*

 

The graph below compares the frequency response from directly behind a U87ai mic (180° off-axis, 1 m from the source, with 1/6-octave smoothing) with a Sphere mic (same position) with Off-Axis Correction enabled. The green line shows the frequency response of a Neumann U87ai; the blue line shows the response of the Sphere mic. 

The Sphere (corrected) polar response is much flatter. The U87 response varies by as much 16 dB, whereas the Sphere mic varies by about 6 dB with smoother overall fluctuations. Not surprisingly, the U87ai’s audio output from 180° off-axis sounds very colored, while the Sphere produces a smoother sound consisting mostly of natural room ambience.

![u87ai-cardioid-180-off-axis-vs-sphere.png](Using%20Sphere%20Off-Axis%20Correction_assets/4877fe8497f7fa0e9c714461c8cbfe26d4ec41f7.png)

*U87ai Cardioid 180° off-axis vs. Sphere Off-Axis Correction*

## How frequency response changes when changing polar patterns

The on-axis frequency response of virtually all multi-pattern mics changes dramatically when adjusting the polar pattern. This can be an issue when you have a mic position and sound dialed in, but then later decide to change the pattern to reduce bleed or feedback. With Off-Axis Correction, it is now possible to adjust the polar pattern without changing on-axis frequency response.

The graph below shows the on-axis frequency response of a U87ai at its three pattern settings. At low and high frequencies, omni and figure-8 differ in response by up to 8 dB.

![u87ai-frequency-plot-measured.png](Using%20Sphere%20Off-Axis%20Correction_assets/b9ba51f4a57540dd55e7fd313f5fba0ea3d919da.png)

*U87ai measured on-axis frequency response*

### Making hybrid microphones by applying different polar patterns

You can also apply any mic frequency response to any polar pattern. For example, you can apply a cardioid pattern to a 4038 ribbon mic, which is normally figure-8, or you can make a U87 hyper-cardioid. For the ribbon mic this can be extremely useful when trying to deal with bleed from directly behind the mic, while making the U87 hyper-cardioid can reduce room pickup.

Effectively, with Sphere you can create a hybrid microphone that did not previously exist. This flexibility lets you easily obtain the precise attributes required for your recording.

## Working with acoustic treatment

Hypercardioid mics have a rear lobe in their reception pattern that picks up some sound from directly behind the mic, which may include some room reflections. However, this lobe is usually small enough that placing acoustical material behind the mic (for example, a reflection filter) can minimize it without having to treat the entire room.

Off-Axis Correction allows you to continuously dial in the best pattern for a particular room and application. Sometimes a pattern somewhere between hypercardioid and figure-8 is ideal.

Due to the proximity effect, the polar pattern of any directional mic varies with distance from the vocalist. To correct for this use the On- and Off-Axis Distance controls. 

- Adjust the On-Axis Distance control to set the distance between the mic and the vocalist.
- Adjust the Off-Axis Distance control to set the distance between the mic and the sources you are trying not to pick up, such as bleed from other instruments or reflections from floors, ceilings, and walls.

Since there is unlikely to be a single off-axis source distance, an average or approximate distance works perfectly well. For example, if the distance to the walls is 2 m and the distance to the floor is 1 m, a setting of 1.5 m is a good choice. Fine tune this control by ear.

If you already have or are considering getting a reflection filter, Sphere’s IsoSphere feature lets you get great isolation while minimizing the reflection filter’s undesirable effects. See <a href="12237363559316-Using-UA-Sphere-Plug-Ins.html#h_01GPEJJW2XHAF0KQW6ZG405YXK" target="_self">IsoSphere</a> for more information.

# Understanding proximity effect

All directional microphones have polar patterns that vary with distance at frequencies below about 1 kHz. This is an inherent consequence of the proximity effect. For example, at low frequencies a typical large dual-diaphragm cardioid condenser mic (for example, a U87 or 414) tends towards a figure-8 pattern close to the mic, and omnidirectional further away. Only at some distance in between will the mic have a cardioid response. This distance, typically 0.5 – 1.0 m, depends on the capsule design.

To illustrate the differences in low frequency response, a typical small single-diaphragm, cardioid condenser mic tends to have a figure-8 pattern close to the mic (less than 10 cm), cardioid at far distances (greater than 4 m), and hyper-cardioid at middle distances (1 – 4 m). However, this also depends on the mic capsule design.

The polar pattern you want to achieve might not be what you get because of the micing distance. For example, this can be a problem when you want to reduce kick drum mic bleed, but your cardioid mic is acting omnidirectional at the lower frequencies.

For this reason Off-Axis Correction has distance controls so you can dial in the desired polar pattern at the mic’s actual distance. The ON DIST control sets the on-axis frequency response to match the frequency response of the modeled microphone at the selected distance. The OFF DIST control sets the distance at which the Off-Axis Correction Polar Pattern control is most accurate.

# Configuring Off-Axis Correction

The Sphere plug-in’s Off-Axis Correction section has four controls and an IN button. When the IN button is engaged, the Pattern control in this section overrides the mic model’s pattern, although the mic model pattern controls continue to affect the on-axis frequency response.

![off-axis-controls.png](Using%20Sphere%20Off-Axis%20Correction_assets/9a62986156d3e289b8d1a9b30be79a0b00680bb1.png)

*Sphere plug-in’s Off-Axis Correction controls*

 

## Understanding Distance and Mode control applications

The On Dist and Off Dist controls specify the on- and off-axis distance, respectively, to the sound sources. Let’s say you have two room mics that are 2 m from a kick drum that face directly away from the kick. You might set the polar pattern to cardioid to minimize kick drum leakage into the room mics. However, conventional cardioid mics typically have a lot of leakage, especially at low frequencies, where the pattern moves towards omni or figure-8.

Enable Off-Axis Correction (IN is on) and set the corresponding Pattern control to cardioid to create a much more accurate polar pattern. In this case, set Off Dist to about 2 m. Set On Dist to a larger value because most of the sound reaching the front of the mic will have traveled further after reflecting off walls, ceiling, and floor.

The distance can be estimated by calculating the path length of the first reflection, although there is usually no need to be exact. Set the controls to the approximate distances, then dial them in by ear. The actual distance value assumes the sound originates from a single point. When the sound source is relatively large, you can think of the distance value as corresponding to the average distance to the source.

For example, with a mic on a guitar cab’s grill, some sound is picked up from the center of the cone and some from the edges. The average distance corresponds to a point somewhere in between. There is no need to take measurements; just make an estimate and dial it in by ear. Typically, when On Dist is set properly, enabling and disabling Off-Axis Correction results in a minimal change for on-axis sources. Adjust Off Dist until off-axis sounds have the highest amount of rejection. 

If in doubt, start with these default settings: 

- On Dist = 20 cm
- Off Dist = 1 m

The AUTO button essentially disables Off-Axis Correction below about 1 kHz, so the response is equal to the mic being modeled. Auto mode can be useful if there are multiple sources at different distances or the sources are moving. We normally recommend leaving Auto mode off, but use the setting that sounds best. With Auto mode on, both distance controls are disabled.

# Capturing more room ambience

Sometimes it’s desirable to intentionally record tracks with lots of room ambience to create a sense of depth in the mix. For example, background vocals can benefit from more room sound so they sit farther back, while the lead vocal may be easier to hear if left relatively dry.

## Capturing room ambience with traditional mics

Traditionally, you could achieve more room sound for background vocals by placing an omni mic farther back from the sources. While this produces excellent results, some cases might require even more ambience. Moving the mic farther back might work, but recording spaces are often small, which limits the mic position. This could also yield a sound that is too reverberant, which may not be desirable.

You can also blend close mics with room mics. While this approach can work, different arrival times at each mic may cause comb filtering due to phase cancellations between them, and this technique requires a good sounding room and multiple microphones.

A third option is to use a sub-cardioid microphone facing directly away from the sound source, also called rear micing. This approach emphasizes room pickup, and because you use a single mic, there are no phase cancellations. The downside is that the rear pickup of most directional mics is heavily colored, so the direct sound might not work for your recording. Cardioid mics tend to have the most rear coloration. 

## Capturing room ambience with a Sphere mic

Off-Axis Correction produces a response with significantly less off-axis coloration, and can be used to create such rear micing techniques. It is not necessary to physically reverse the microphone. In the plug-in, activate the REV button during or after tracking to rotate the mic’s polar pattern 180 degrees. Then, dial in the pattern control to achieve the precise ratio of room and direct sound.

# Understanding applications for Off-Axis Correction

There are many uses for Sphere’s Off-Axis Correction feature. Room micing can greatly benefit from this technology because you can often better isolate the reverb from the direct sound by using a cardioid pattern. You can also use Off-Axis Correction on room mics to produce a more accurate omni pattern, which can sound more open and airy.

You can also sometimes diagnose poor acoustics by listening to the pure reverb signal. Position the mic 180° off-axis and a couple meters away from a snare drum. Hit the snare and listen for flutter echoes and other sonic artifacts. Position and point the mic in different places until you find the right location.

