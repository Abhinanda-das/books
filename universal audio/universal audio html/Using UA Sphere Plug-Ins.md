---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12237363559316-Using-UA-Sphere-Plug-Ins.html'
converted_at: 2026-05-31T13:44:42Z
tool: htmlq+pandoc
title: 'Using UA Sphere Plug-Ins'
word_count: 3247
---

# Using UA Sphere Plug-Ins


## In this article

- <a href="#h_01GPCMRAA5HTFVH72Q2E5V188N" target="_self">Understanding UAD, AAX DSP, and native Sphere plug-ins</a>
- <a href="#h_01GPCMSFK1BM5M5E4F4NPAJWVD" target="_self">Extending UAD Sphere plug-ins</a>
- <a href="#h_01GPCMSQTFGA9SCW9G9TTZ1GVC" target="_self">Understanding Sphere plug-in interfaces</a>
- <a href="#h_01GPCMTAG25HFHZ5ZKTR41KWV7" target="_self">Selecting microphone types</a>
- <a href="#h_01GPD6SKSYTAK9RE8DJ6PZ6DNY" target="_self">Using Sphere plug-in controls</a>

The Sphere plug-ins are an essential part of the Sphere microphone system. The plug-ins perform all signal processing in the system during monitoring, recording, or when post-processing tracks that were previously recorded with a Sphere mic.

# Understanding UAD, AAX DSP, and native Sphere plug-ins

- **If you have UAD Apollo hardware**, you can use a UAD Sphere plug-in to monitor your Sphere microphone in real time without apparent latency. 
- **With Pro Tools AAX DSP hardware**, you can monitor your Sphere mic with an AAX DSP plug-in without apparent latency. 
- **On native systems**, you can monitor your Sphere mic directly with your audio interface’s hardware monitoring feature, or monitor through the native plug-ins with buffer latency as low as your system will allow with software monitoring. 
- With all DSP and native Sphere plug-ins, you can apply mic models and other processing after the recording is complete. 

See <a href="12241582040084-Using-Sphere-Mics.html#h_01GPD87N6XAG5J8PRD7ZE4BKVR" target="_self">Understanding your DAW signal flow</a> for details.

 

# Extending UAD Sphere plug-ins

In addition to the Sphere Mic Collection plug-in or plug-ins included with your Sphere mic, with UAD hardware you can extend your mic collection by purchasing two additional UAD plug-ins. Note that purchasing and using either mic collection allows access to all 34 mic models in the Sphere Mic Collection for any Sphere mic, including Sphere LX.

## UAD Ocean Way Mic Collection

The Ocean Way Mic Collection plug-in expands the capabilities of the acclaimed Sphere microphone system with 12 ultra-precise emulations of the “best of the best” vintage mics from esteemed recording engineer Allen Sides’ world-renowned vintage mic locker. 

## UAD Bill Putnam Mic Collection

The Bill Putnam Mic Collection plug-in adds nine vintage mic emulations, modeled from Bill Putnam Sr.’s renowned collection, to the Sphere system. These mic emulations nail the classic timbres of iconic mics used by Bill Putnam to track Ray Charles, Frank Sinatra, and more.

# Understanding Sphere plug-in interfaces

The screenshots below show the mono (Dual View disabled) version of each plug-in on top, and the 180 version below it. Although each plug-in has a unique appearance, they employ the same adjustable parameters and can record in mono or stereo.

**Note:** This article refers to the Sphere Mic Collection plug-ins, but the same information applies to the UAD Ocean Way Mic Collection and UAD Putnam Mic Collection plug-ins.

Both the Sphere Mic Collection (with Dual View enabled) and Sphere Mic Collection 180 plug-ins contain two mic models that can be blended together as if recording with two mics. Each mic model has its own Pattern, Filter, Axis, and Solo controls. The other plug-in parameters control both mics.

The Sphere Mic Collection 180 plug-in outputs each mic model on a separate channel, which lets you create stereo recordings.

![sphere-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/fad204a2356dc142a41f0f5e99bf32202b30ac73.png)

![sphere-180-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/725da66a13019b6dd91c9538d6b6fa522b780309.png)

*UA Sphere Mic Collection plug-ins (UA Sphere 180 on bottom)*

![ocean-way-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/8a546373c402b5e091662d8881f5688dbb1d7643.png)

![ocean-way-180-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/a36d991bd164c80d47c7d22d224e613e19a4e16f.png)

*Ocean Way Microphone Collection plug-ins (Ocean Way 180 on bottom)*

![putnam-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/8a116da8656b068eb836b88584fe79614a7e5cf8.png)

![putnam-180-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/78d6849c1c5716d9c7a83669bca288adc6c42024.png)

*Bill Putnam Microphone Collection plug-in (Bill Putnam 180 on bottom)*

 

# Selecting microphone types

#### To select a microphone type

- Click on the mic name. An overlay displays the available mic types. Click a tab at the top to change the mic category (Large Condenser, Hybrid, or Custom). If you are using the UAD Putnam Mic Collection or UAD Ocean Way Mic Collection plug-ins, you see categories for the Putnam and Ocean Way Mic Collections, in addition to the full Sphere Mic Collection. Double-click any mic, or select and click the "X" to exit mic selection.

This is a useful way to see the overview of a group of mics and compare between them.\
\
**Tip:** When <a href="#h_01GPEHZET2YTN1D6FQSZ4BD1RX" target="_self">Tool Tips are enabled</a>, hover your mouse over a mic to see information about that mic. 

- Click on the arrows at the bottom of the mic image, or anywhere on the right or left of the mic image, to select the next or previous mic. Right-click or Ctrl-click on the mic image to display the previous mic.
- Clicking on the mic image or type, then use the up/down/left/right arrows on your computer keyboard to navigate between mics.
- Tool Tips do not appear in the UAD-2 Sphere plug-ins, on Apple silicon Macs.

Selecting from the main plug-in screen allows you to view the polar response for each mic model while you listen to its sound. See [Polar Meter](#h_01HKNA171ZKNMFTPAR21T9DXEV) for more information.

## Selecting microphone types in Dual or 180 plug-in view

The same selection methods apply to the Sphere 180 plug-ins, and also the Sphere plug-ins when in Dual View mode. Both plug-in views show the names and images of two microphone types. 

### Selecting microphones in Sphere 180

In a Sphere 180 plug-in, the mics are labeled Mic L and Mic R, and the plug-in includes Pan and Width controls.\
![sphere-180-interface.png](Using%20UA%20Sphere%20Plug-Ins_assets/725da66a13019b6dd91c9538d6b6fa522b780309.png)

### \
Selecting microphones in Dual View

In a Sphere plug-in that is in Dual View mode, the plug-in shows Mic 1 and Mic 2. Dual View also adds controls to Mix and Align the two microphones.\
![sphere-dual-mode.png](Using%20UA%20Sphere%20Plug-Ins_assets/3116a15e904fad62dd1392adb63572a8003f53af.png)

 

# Using Sphere plug-in controls

The following controls are available in Sphere plug-ins.

## Link (Dual View/180 only)

When active, this setting uses Mic 1/L’s settings for Mic 2/R.

## Solo (Dual View/180 only)

When active, this setting outputs either Mic 1/L or Mic 2/R.

## Pattern

This setting adjusts the pick-up pattern of the mic model. This is equivalent to choosing a different polar pattern setting on a multi-pattern mic, but with the advantage that you can select intermediate polar patterns that the original mic did not have. For example, when modeling a mic that natively supports omni, cardioid, and figure-eight settings, the Sphere plug-ins can synthesize transitional polar patterns, such as sub-cardioid or hyper-cardioid. Each mic’s original patterns are illuminated in green.

Available patterns are:

- Omni
- Sub-Omni
- Wide-cardioid
- Sub-cardioid
- Cardioid
- Super-cardioid
- Hyper-cardioid
- Sub-8
- Figure-8

![off-axis-correction-patterns-callouts.png](Using%20UA%20Sphere%20Plug-Ins_assets/3e17ba9c5884023401cb71d14f236342fbab1e8a.png)

## Filter

This control lets you adjust the mic model’s filter type. Each mic model has three filters, even if the original microphone has fewer or no filter options. The filters vary according to those supplied with the original mic. A microphone’s original filter types are illuminated in green. Switch Off to disable the filter.

Some microphones include a high-pass filter to reduce unwanted low-frequency rumble or proximity effect. On some models, we include the pad setting on the filter control, because the pad has a characteristic sound that we modeled. Neither the mic sensitivity nor output level is affected when a mic includes such a pad setting.

**Tip:** When you adjust the filter setting, text above the filter knob indicates the mic setting, either as a frequency value (for example, 60 Hz) or as the setting from the original mic (for example, M1, HPF, or PAD).

## Axis

This control lets you adjust the tonality of the mic by virtually moving the source off-axis. For example, set Axis to 45º to adjust the frequency response of the mic as if the mic was rotated 45º.

Axis modeling differs from physically rotating the mic, which would shift both the polar and fre­quency responses. Typically, mics become darker as they move off-axis relative to the source. Axis provides you with the “beyond reality” ability to maintain the polar pattern while shifting just the tonality of the mic.

**Tip:** If you want off axis results beyond 45º, it may be preferable to simply rotate the mic.

## Proximity settings

The bass response of directional mics increases as the source gets closer to the mic. This is referred to as the proximity effect, and occurs because the mic’s low-frequency polar response pattern increases as the distance to the source decreases.

**Tip:** The Proximity control is available on all Sphere plug-in configurations. The Prox EQ setting appears only when in Dual View or 180 mode. 

### Proximity

This control sets the amount of proximity polar response at low frequencies.

**Note:** This control has no effect for purely omni-directional microphones.

### Prox EQ

This control lets you cut or boost within the proximity effect’s low frequency range. At 0, Prox EQ has no effect.

**Note:** Unlike Proximity, Prox EQ is active even with omni-directional mic models.

## IsoSphere

Isolation filters and other acoustic treatments, including reflection filters and portable vocal booths, are used to reduce coloration and improve room rejection. However, they also color the sound picked up by a mic. They often require a trade-off between reducing reflections and minimizing col­oration, and have a diminishing effect below about 1 kHz. 

The patented IsoSphereTM feature optimizes how Sphere works with commonly available isolation filters, such as the sE Reflexion Filter, Aston Halo, and Kaotica Eyeball. IsoSphere adjusts the mic response in the following ways to compensate for the isolation filter:

- produces a polar pattern with a larger rear lobe optimized for maximum overall rejection
- uses a hypercardioid pattern at low frequencies to make the mic more directional in the range of frequencies where isolation filters are less effective
- modifies the frequency response to compensate for any coloration caused by the isolation filter

As a result, IsoSphere allows you to capture better-sounding recordings with your existing reflec­tion filter. Sphere’s Proximity and Prox EQ controls already let you get closer to the mic without creating an over­whelming bass response. Using these settings with IsoSphere controls, you can produce cleaner, drier recordings in poor acoustic spaces.

Click the IsoSphere settings button to display the available IsoSphere models. Click the IN button to enable/disable IsoSphere. The button illuminates when the feature is enabled.

#### IsoSphere notes

- IsoSphere is not available in the 180 versions of the plug-ins.
- IsoSphere and Off-Axis Correction cannot be enabled at the same time.

![sphere-isosphere.png](Using%20UA%20Sphere%20Plug-Ins_assets/164103fccab8843ec661f97a4c88a92b6ce29f1d.png)

*IsoSphere controls*

### Enable

Click IN to enable/disable IsoSphere. The button illuminates when the feature is enabled.

### Source Distance

This control compensates for changes in bass response due to the proximity effect. Set Source Distance to the approximate distance of the mic from the source, or set it by ear.

### Isolation filter type

This button presents the isolation filter overlay for choosing an isolator. The currently selected filter is illuminated. Click on another filter to select a new filter type. If your filter is not in the list, select the closest type or the one that sounds best. 

To close the window, double-click the desired filter, or click the “X” at the top-right of the screen.

## Align (Dual View only)

This control adjusts the relative distance between the two mic diaphragms in Dual View. By default, the setting is 0, which means the two mic models are perfectly phase aligned.

For example, set Align to:

- **1** to adjust the relative phase of Mic 2 one centimeter farther from the source than Mic 1.
- **-1** to adjust the relative phase of Mic 2 one centimeter closer to the source than Mic 1.

**Note:** Because Align adjusts the relative phase between the two mic models, the control has no effect unless the two mics are blended with the mix control.

## Stereo Width (180 plug-in only)

This control adjusts the stereo width of the two mic channels.

- **100%** **–** Preserves the original stereo width of the selected mic models.
- **0%** **–** Reduces the width to mono.
- **200%** **–** Increases the width beyond that of the selected mic models.

## Mix (Dual View only)

This control adjusts the relative mix of Mic 1 and Mic 2.

## Pan (180 plug-in only)

This control adjusts the pan between Mic L and Mic R.

## Correcting and changing mic axis

You can use the off-axis correction tools in Sphere plug-ins to correct for a mic model’s inherent off-axis response, and reduce bleed, coloration, and room response. Off-Axis Correction is a unique DSP process that renders a more consistent off-axis response across frequency. For more information about the Off-Axis Correction feature, including technical details, see [Using Off Axis Correction](12241698003732-Using-Sphere-Off-Axis-Correction.html).

**Tip:** You can apply a different polar pattern to an existing mic. For example, you can replace the figure-8 pattern of a 4038 ribbon mic with a cardioid pattern to create a "beyond reality" mic.

### Off-Axis Correction setting

This control toggles the Off-Axis Correction feature in and out.

#### Off-Axis Correction Notes

- Off-Axis Correction is available only when Dual View is enabled, or in a Sphere 180 plug-in. 
- If IsoSphere is enabled, the Off-Axis Correction controls are unavailable. Disable Iso­Sphere to use the Off-Axis Correction controls.

### Off-Axis Correction Pattern

This control adjusts the mic pattern, to select a more idealized pattern that may suit the application better than the mic model’s original pattern. When enabled, this overrides the off-axis patterns for Mic 1 and Mic 2.

There are nine settings that range from omni (fully counter-clockwise) to figure-8 (fully clockwise). The illustration below shows the pattern names as the control is adjusted.

![off-axis-correction-patterns-callouts.png](Using%20UA%20Sphere%20Plug-Ins_assets/3e17ba9c5884023401cb71d14f236342fbab1e8a.png)

*Off-Axis Correction pattern values*

 

### On- and Off-Axis Distance

This control adjusts the on and off-axis distance of the mic from the source and from background sources. The distance range  is 1 cm–infinity.

Due to the proximity effect, directional mics achieve their specified polar pattern for low frequencies at a single distance. However, the mic’s off-axis response can be much more colored. 

- On Dist is the distance to the source being recorded.
- Off Dist is the approximate distance to background sound sources you wish to minimize, such as instrument bleed or room reflections.

### Off-Axis Correction Mode

Select an off-axis correction mode from this list. The four Off-Axis Correction modes are optimized for different soundfields:

- **FF –** Free-Field maximizes off-axis rejection while maintaining the most accurate on-axis response.

This mode is good for close-micing and reduces bleed from off-axis sources. Rear and side rejection is maximized for cardioid and figure-8 patterns, respectively.

- **DF1 –** Diffuse-Field 1 optimizes off-axis response to balance between smooth reception from all directions, accurate on-axis response, and rear/side rejection.
- **DF2 –**Diffuse-Field 2 optimizes off-axis response to attain accurate reception from all directions at the expense of rear/side rejection. This mode works well when using a 180 plug-in to make stereo recordings.
- **AUTO –** This mode disables On Dist and Off Dist and automatically corrects the low frequency response. This mode is best suited for moving sources and multiple sources located at different distances. Auto mode’s polar response tends to be less than ideal, so we recommend trying one of the other settings first.

## Output

This control adjusts the overall microphone output and phase. 

### Output Level

This control adjusts the overall master output level ±12 dB.

### Output Phase

This control reverses the polarity of the output, which can be useful to prevent phase cancellations when simultaneously using multiple microphones to record the same source.

## Reverse (Rev)

This control switches the mic output so it points backwards. When using the Sphere 180 plug-in, this control swaps the left and right outputs.

## Input/Output Meter

This meter shows the input or output levels of the plug-in. Click the Input or Output label to toggle between the two displays.

## Polar Meter

The Polar Meter™ displays the approximate amplitude and direction of sound arriving at the mic. The Polar Meter is particularly useful to determine the direction of bleed from other instruments. The moving yellow line in the Polar Meter shows the approximate amplitude and direction of the arriving sound. The green line shows the polar pattern of the currently selected microphone.

**Note:** In the UAD Ocean Way Mic Collection plug-ins, the polar meter colors are reversed: yellow for the polar pattern, and green for the amplitude of arriving sound. 

The Polar Meter in the screenshot below shows a sound source 135° off-axis, which is typically “bleed” or extraneous sound. You can create a polar pattern to reject as much of this unwanted sound as possible. The two shadowed pie wedges show where the polar pattern has the most rejection. If the desired (on-axis) sound source is muted, the off-axis bleed can be minimized by lining up the area of most rejection to cover as much of the yellow shape as possible.

![polar-meters-sphere-and-ocean-way.png](Using%20UA%20Sphere%20Plug-Ins_assets/693c83f47abed2494621465f8ddd27c1843b3043.png)

*Polar Meter showing source approximately 135° off-axis*

*(Sphere Mic Collection plug-in left, Ocean Way Collection right)*

The Polar Meter (on a non-180 plug-in) cannot differentiate between sound coming from the left, right, up, or down. In this example, sound coming from 135° to the right is displayed as coming from both 135° to left and 135° to the right. This interpolation is accurate because most microphones, including the Sphere, are bilaterally symmetric. The polar pattern is the same whether off-axis to the left or right, so there is no way to adjust the pattern to reject sound on just the left or right. In general, we recommend using the Polar Meter as a guideline, and then dialing in a pattern by ear that produces the most rejection. See [Selecting microphone types](#h_01GPCMTAG25HFHZ5ZKTR41KWV7) to easily compare mic models while viewing their response in the Polar Meter.

There are some inherent inaccuracies in the Polar Meter due to the mic’s proximity effect, and low frequency content can distort its response. If the distance to the source is known, you can compensate for this by using the Off-Axis Correction distance controls to produce a more accurate Polar Meter response.

Highly reverberant environments produce a more circular Polar Meter response (see screenshot below) showing that sound is arriving from all directions.

![PolarMeterFullCircleExample-tiny.png](Using%20UA%20Sphere%20Plug-Ins_assets/9926cd60ac1bb8e8a213e9aa2fd51b33e3c910a2.png)

*Polar Meter showing a reverberant environment*

The mono Sphere plug-in shows the combined polar response of Mics 1 and 2, when using Dual View. For example:

- If the MIX control is set to 50%, the illustrated response is an equal combination of Mics 1 and 2.
- At 0% the response is fully Mic 1.
- At 100% the response is fully Mic 2.

**Note:** When Off-Axis Correction is enabled, the selected mic model’s response patterns are overridden.

### Zooming in the Polar Meter

Click on the +/- text labels at the bottom of the polar meter display to zoom in or out, or click and drag up or down between the +/- text labels to zoom in and out. 

## Using Setup controls

Click Setup to access Rear Trim, Swap, Auto calibration, Import, and enable/disable Tool Tips.

### Rear Trim

This control adjusts the input level of the rear capsule when the preamp levels are not calibrated precisely.

### Swap

This control flips the right and left input channels for setup purposes. If the mic outputs were connected back­wards, this corrects the wiring without repatching.

### Auto

This control lets you automatically calibrate the input levels. This is achieved by adjusting the rear trim control to compensate for gain differences between the front and rear channels. When using Auto Cal, enable the CAL switch on the physical Sphere mic body to input the same signal to both the front and back mic preamp channels. See [Calibrating a preamp with continuous gain](12233094069140-Installing-and-Configuring-Sphere.html#h_01GPDAMXW4RV0KD9W5WWJD49C3) for more information.

### Import

Click to import a Sphere preset.

### Tool Tips

Click Tool Tips to toggle helpful tips when hovering the cursor over a control. This includes information about each mic type, when selecting in the mic type selection window.

