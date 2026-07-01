---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/33030899033236-DreamVerb-Manual.html'
converted_at: 2026-05-31T13:44:52Z
tool: htmlq+pandoc
title: 'DreamVerb Manual'
word_count: 3833
---

# DreamVerb Manual


## Fully customizable reverb and room modeler.

The DreamVerb Room Modeler plug-in for UAD-2 hardware and Apollo interfaces draws on the unparalleled flexibility of UA's pioneering RealVerb Pro plug-in, and adds an intuitive and powerful interface to help you craft a stunning range of spaces. DreamVerb not only lets you create a room from a huge list of different materials and room shapes. It lets you customize further by blending or "morphing" the different room shapes and surfaces with one another, while the density of the air can be changed to simulate different ambient situations.

DreamVerb also features a flexible 5-band active EQ and unique level ramping for the early and late reflections for ultra-realistic dynamic room simulation. And with Universal Audio's proprietary smoothing algorithm, all parameters can be adjusted in real-time with no "zipper-noise' or audible artifacts. DreamVerb also features lots of graphic feedback for the user to understand just how their choices affect the reverb. From a vibrantly dynamic room to a rich, deep cathedral, DreamVerb is the reverb of your dreams.

- Design the perfect acoustic space with Custom room shape settings
- Fine tune your room with different materials
- Blend between room shapes and sizes in real time
- Tweak further with separate Intensity, Timing, and Onset of Early Reflections and Late-Field Reverberation controls

<div>

![](DreamVerb%20Manual_assets/6fa3d09979c76c9e403051ad63c15a10ae2e1ebb.png)

</div>

*DreamVerb*

# Signal Flow

The signal flow for DreamVerb is illustrated below. The input signal is equalized then delay lines are applied to the early reflection and late field generators. The resulting direct path, early reflection, and late-field reverberation are then independently positioned in the soundfield.

<div class="wysiwyg-text-align-center">

![dreamverb-signal-flow-2x.png](DreamVerb%20Manual_assets/4df2f889ed35fc9d7b1a23a512590960e0c01e8a.png)

</div>

*DreamVerb signal flow*

The DreamVerb interface is similarly organized. Reflected energy equalization is controlled with the Resonance panel. The pattern of early reflections (their relative timing and amplitudes) is determined by the room shapes in the [Shape panel](#h_01JF79N6AE4M5EA24MB0XD2QRF). Early reflection pre-delay, slope, timing, and amplitude are specified in the [Reflections panel](#h_01JF79VWWFXGQ9H9M85F5FSFPG). The [Materials panel](#h_01JF79S1FNEW0ZA4JVHMYJ60JA) is used to select relative late-field decay rates as a function of frequency. The late-field predelay, decay rate, room diffusion, slope, and level is specified in the [Reverberation panel](#h_01JF79XEERPFSKFR6T5WH9GZTD). Finally, the [Positioning panel](#h_01JF79Z7367CKG2T19JYJQMHYM) contains controls for the placement of the source, early reflections, and late-field reverberation.

# Resonance (Equalization) Panel

The Resonance panel is a five-band equalizer that can control the overall frequency response of the reverb, effecting its perceived brilliance and warmth. By adjusting its Amplitude and band Edge controls, the equalizer can be configured as shelving or parametric EQs, as well as hybrids between the two.

The EQ curve effects the signal feeding both the early reflections and the late field reverberations, but not the direct path.

Bands 1 and 5 are configured as shelving bands. Bands 2, 3, and 4 also have an Edge control for adjusting its bandwidth.

Generally speaking, a lot of high-frequency energy results in a brilliant reverberation, whereas a good amount of low-frequency content gives a warm reverberation.

**Note:** The values for the EQ parameters are displayed in the text fields at the bottom of the Resonance panel. The values can also be entered directly using the text entry method.

<div class="wysiwyg-text-align-center">

![dreamverb-resonance-panel-2x.png](DreamVerb%20Manual_assets/09ea8534f475b17425ac34b86636d3446e20247f.png)

</div>

*Resonance panel*

## Bypass

The equalizer can be disabled with this switch. When the switch is off (black instead of grey), the other resonance controls have no effect. This switch has no effect on the direct signal path.

## Band Amplitude

Each of the five bands has its own amplitude (gain) control. The amplitude range of each band is -30 dB to +20 dB.

To adjust the amplitude of bands 2, 3, and 4, grab the control bat for the band and drag vertically or use the direct text entry method. For bands 1 and 5, drag the horizontal line (these do not have a control bat).

## Band Edge

Bands 2, 3, and 4 have an Edge control. This parameter effects the bandwidth of the band. To adjust the band edge, grab its control bat and drag horizontally or use the direct text entry method.

The effect of the band edge on the filter sound can depend upon the settings of the adjacent bands. For example, the sonic effect of this parameter is more pronounced if the amplitude of adjacent bands is significantly different than that of the band whose edge is being adjusted.

## Shelving

The simplest (and often most practical) use of the equalizer is for low and/or high frequency shelving. This is achieved by dragging the left-most or right-most horizontal line (the ones without control bats) up or down, which boosts or cuts the energy at these frequencies.

<div class="wysiwyg-text-align-center">

![dreamverb-resonance-shelving-bands-2x.png](DreamVerb%20Manual_assets/311dae27700e531c21062d9453f797081ab36b9a.png)

</div>

*Resonance Shelving Bands*

# Shape Panel

The parameters in the Shape panel, in conjunction with the Materials panel, effect the spatial characteristics of the reverb.

The pattern of early reflections in a reverb is determined by the room shape(s) and the ER start and end points. Two shapes can be blended from 0-100%. All parameters can be adjusted dynamically in real time without causing distortion or other artifacts in the audio. 21 shapes are available, including various plates, springs, rooms, and other acoustic spaces.

**Note:** The Shape parameters effect only the early reflections. They have no effect on the late field reverberation.

<div class="wysiwyg-text-align-center">

![dreamverb-chape-panel-2x.png](DreamVerb%20Manual_assets/8e603a236fd4d5f46b2738eb5b8298ec0730d963.png)

</div>

*Shape panel*

## Shape Menus

DreamVerb lets you specify two room shapes that can be blended to create a hybrid of early reflection patterns. The first and second shape each have their own menu. The available shapes are the same for each of the two shape menus.

The first shape is displayed in the upper area of the Shape panel, and the second shape is displayed in the lower area.

To select a first or second shape, click its drop menu to view the available shapes, then drag to the desired shape and release.

## Shape Blending Bar

The Shape Blending Bar is used to blend the two shapes together at any ratio. The two shapes are not just mixed together with this parameter; the early reflections algorithm itself is modified by blending.

Blend the early reflection patterns of the two rooms by dragging the Blending Bar. Drag the bar to the bottom to emphasize the first shape; drag to the top to emphasize the second shape.

The relative percentages of the two rooms appear at the bottom of the Shape panel. To use only one room shape, drag the Blending Bar so a shape is set to 100%.

The resulting early reflection pattern is displayed at the top of the Reflections panel, where each reflection is represented by a yellow vertical line with a height indicating its arrival energy, and a location indicating its arrival time.

# Materials Panel

The parameters in the Materials panel, in conjunction with the Shape panel and Reverberation panel, affect the spatial characteristics of the reverb.

The material composition of an acoustical space effects how different frequency components decay over time. Materials are characterized by their absorption rates as a function of frequency--the more the material absorbs a certain frequency, the faster that frequency decays.

**Note:** While materials are used to control decay rates as a function of frequency, the overall decay rate of the late-field reverberation is controlled from the Reverberation panel.

<div class="wysiwyg-text-align-center">

![dreamverb-materials-panel-2x.png](DreamVerb%20Manual_assets/d25cadb70d020df574c6f9a91e56dee884fa7a9a.png)

</div>

*Materials panel*

24 real-world materials are provided, including such diverse materials as brick, marble, hardwood, water surface, and audience. Also included are 24 artificial materials with predefined decay rates, and seven air densities.

**Note:** The parameters in the Materials panel always effect the late-field reverberations. However, the materials parameters effect the early reflections ONLY if the "Filtering" parameter in the Reflections panel is set to a non-zero value.

## Materials Menus

DreamVerb lets you specify two room materials, which can be blended to create a hybrid of absorption and reflection properties. The first and second room material each has its own menu. The available materials are the same for each of the two materials menus.

The first material is displayed in the lower left area of the Materials panel, and the second material is displayed in the lower right area.

To select the first or second material, click its drop menu to view the available materials, then drag to the desired material and release.

In addition to the "perfect" materials marked with a K, DreamVerb provides "J" materials that are not found in RealVerb Pro. These perform the inverse of the "K" materials. The materials marked with a J preferentially absorb low frequencies; they give the selected decay time at high frequencies, and a much shorter decay time at low frequencies.

## Air Density Menu

DreamVerb allows you to specify the density of the air in the reverberant space with this menu, enabling another dimension of sonic control.

The more dense the air is, the more it absorbs high frequencies. At the top of the Air Density menu is Ideal Gas, where no frequencies are absorbed. The air quality increases in density with each selection as you go down the menu.

Inverse Air and Inverse Thick Fog absorb more low frequencies instead of high frequencies.

## Materials Blending Bars

The Materials Blending Bars are used to blend the three materials together at any ratio. The materials are not just mixed together with the bars; the reverberation algorithm itself is modified by blending.

### Materials Blending

Blend the two materials by dragging the vertical Blending Bar horizontally. Drag the bar to the right to emphasize the first material; drag to the left to emphasize the second material.

The relative percentages of the two materials appear next to each menu in the Materials panel. To use only one material, drag the Blending Bar so a material is set to 100%.

### Air Blending

Blend the air density with the materials by dragging the horizontal Blending Bar vertically. Drag the bar to the top to emphasize the solid materials; drag to the bottom to emphasize the air.

The percentage of air used appears next to the Air Density menu. To use only solid materials, drag the horizontal Blending Bar to the top so air is set to 0%. To use only air, drag the horizontal Blending Bar to the bottom so air is set to 100%.

# Reflections Panel

The Reflections panel offers control over the timing and relative energies of the reverb early reflections (ER). These parameters effect the reverb's perceived clarity and intimacy. Each early reflection is visually represented by a yellow vertical line with a height indicating its arrival energy and a location indicating its arrival time.

Unique to DreamVerb is independent control of the amplitude at the early reflection start and end points which facilitates envelope shaping of the reflections. This allows the ability to fade-in or fade-out the reflections to more accurately emulate acoustic environments or for special effects.

**Note:** The values for the Start and End bats are displayed in the text fields at the bottom of the Reflections panel. These values can also be entered directly using the text entry method.

<div class="wysiwyg-text-align-center">

![dreamverb-reflections.panel-2x.png](DreamVerb%20Manual_assets/69efdc8fefafc1b24d6acb35369ad246decfe5b7.png)

</div>

*Reflections panel*

## Bypass

The early reflections can be disabled with this switch. When the switch is off (black instead of grey), the other Reflections controls have no effect. This switch has no effect on the direct signal path.

## Reflections Start

This bat controls two early reflections start parameters. Dragging the bat horizontally controls the ER predelay (the delay between the dry signal and the onset of the ER). Dragging it vertically controls the amplitude of the reflections energy at the ER start time.

## Reflections End

This bat controls two ER end point parameters. Dragging the bat horizontally controls the ER end time (the time at which the ER is no longer heard). Dragging it vertically controls the amplitude of the reflections energy at the end point.

## Filtering

This parameter determines the amount of filtering from the Materials panel to be applied to the early reflections. The Materials effect upon the ER is most pronounced when Filtering is set to 100%.

**Note:** The parameters in the Materials panel have no effect on the early reflections unless this parameter value is above 0%.

Late-Field Relative Timing

To highlight the relative timing relationship between the early reflections and late-field reverberation components, the shape and timing of the late-field is represented as an outline in the Reflections panel.

**Tip:** The shape of the LF outline is modified by parameters in the Reverberations panel, not the Reflections panel.

# Reverberation Panel

The Reverberation panel contains the parameters that control the late-field (LF) reverb tail for DreamVerb.

The primary spectral characteristics of the late-field reverberation are determined by the parameters in the Materials panel in conjunction with the Reverberation panel settings.

**Note:** The values for the late-field controls are displayed in the text fields at the bottom of the Reverberations panel. These values can also be entered directly using the text entry method.

<div class="wysiwyg-text-align-center">

![dreamverb-reverberation-panel-2x.png](DreamVerb%20Manual_assets/756e476a31e25fdce5ca018704cfedc1292d6bc8.png)

</div>

*Reverberation panel*

## Bypass

The late-field reverberations can be disabled with this switch. When the switch is off (black instead of grey), the other Reflections controls have no effect. This switch has no effect on the direct signal path.

## Late-Field Start

This parameter defines when the late-field reverb tail begins (the delay between the dry signal and the onset of the LF) in relation to the dry signal.

## Amplitude & Slope

This bat controls two late-field parameters. Dragging the bat vertically controls the maximum amplitude of the LF reverb energy. Dragging it horizontally controls the LF slope (fade-in) time.

## Decay Time

This control effects the length of the reverb tail. Drag the bat to the left for a short decay, or to the right for a long decay.

## Diffusion

This slider effects how quickly the late-field reverberations become more dense. The higher the Diffusion value, the more rapidly a dense reverb tail evolves.

## ER Relative Timing

To highlight the relative timing relationship between the early reflections and late-field reverberation components, the shape and timing of the early reflections is represented as an outline in the Reverberation panel.

**Tip:** The shape of the ER outline is modified by parameters in the Reflections panel, not the Reverberation panel.

# Positioning Panel

DreamVerb has the ability to separately position the direct path, early reflections, and late-field reverberation. The Positioning panel provides panning controls for each of these reverb components. In addition, a proprietary Distance control adjusts perceived source distance. These controls allow realistic synthesis of acoustic spaces--for instance listening at the entrance of an alley way, where all response components arrive from the same direction, or listening in the same alley next to the source, where the early reflections and reverberation surround the listener.

**Note:** When DreamVerb is used in a mono-in/mono-out configuration, all Positioning controls except Distance are unavailable for adjustment.

<div class="wysiwyg-text-align-center">

![](DreamVerb%20Manual_assets/968abdd65033d9dc1dba5b5286c4e6a096a47c70.png)

</div>

*Positioning panel*

## Direct

These two sliders control the panning of the dry signal. The upper Direct slider controls the left audio channel, and the lower Direct slider controls the right audio channel.

A value of \<100 pans the signal hard left; a value of 100\> pans the signal hard right. A value of \<0\> places the signal in the center of the stereo field.

**Note:** If the Mix parameter is set to 100% wet or the Wet button is active, these sliders have no effect.

## Early

This slider, which contains two control handles, adjusts the stereo width of the early reflections.

## Late

This slider, which contains two control handles, adjusts the stereo width of the late-field reverberations.

### Early & Late Adjustment

The left and right slider handles are dragged to adjust the stereo width. For a full stereo spread, drag the left handle all the way to left and right handle all the way to the right. When the slider handles are not set to maximum width, the center of the slider can be dragged left or right to set the positioning of the signal.

To pan a mono signal hard left or right, drag the slider all the way to the left or right.

## Distance

DreamVerb allows you to control the distance of the perceived source with this slider. In reverberant environments, sounds originating close to the listener have a different mix of direct and reflected energy than those originating further from the listener.

Larger percentages yield a source that is farther away from the listener. A value of 0% places the source as close as possible to the listener.

# Levels Panel

This panel is where DreamVerb input/output levels, wet/dry mix, and reverb mute controls can be modified.

<div class="wysiwyg-text-align-center">

![](DreamVerb%20Manual_assets/8dbe6cf7be088b7ac552de9d4e9da90106bcda97.png)

</div>

*Levels panel*

## Input

Modifies the signal level at the input to DreamVerb. A value of zero is unity gain.

## Output

Modifies the signal level at the output of DreamVerb. A value of zero is unity gain.

## Mute

This switch mutes the signal at the input to DreamVerb. This allows the reverb tail to play out after mute is applied, which is helpful for auditioning the sound of the reverb. Mute is on when the button is gray and off when the button is black.

## Mix

The wet and dry mix of DreamVerb is controlled with this slider. The two buttons above this slider labeled "D" and "W" represent Dry and Wet; clicking either will create a 100% dry or 100% wet mix.

## Dry

When this button (labeled "D") is enabled, DreamVerb is 100% dry. It has the same effect as moving the Mix slider to 0%. Dry is on when the button is gray and off when the button is black.

## Wet

When this button (labeled "W") is enabled, DreamVerb is 100% wet. It has the same effect as moving the Mix slider to 100%. Wet is on when the button is gray and off when the button is black.

# Spatial Characteristics

## Size

The apparent size of a reverberant space is dependent on many factors. Most reverbs on the market have a "size" parameter, which usually modifies several facets of the reverb algorithm at once. You may notice DreamVerb does not have a "size" parameter. Instead, the elements that control the reverberant space are available to the user.

In DreamVerb, room size is determined by the interaction between all the parameters in the Reflections and Reverberation panels. To get a larger-sounding space, increase the T60 (reverberation time), use proportionally more air, increase the pre-delays, and slightly shift the Resonance transition frequencies to lower values.

## Pre-Delay

Intimacy and remoteness are largely controlled by the pre-delays. Generally speaking, use shorter pre-delays for more intimate spaces. Clear spaces have most of their energy in the first eighty milliseconds or so; muddy spaces have a lot of late arriving energy.

## Space

In some sense, Shape determines the spatial characteristics of the reverberator, whereas Materials effects the spectral characteristics.

# DreamVerb Presets

DreamVerb includes 100+ presets in addition to the internal factory bank. Presets are accessed via the Preset browser in UAD Console, or your DAW's preset manager.

# Preset Design Tips

Here are some practical tips for creating useful reverbs with DreamVerb. These are not rules of course, but techniques that can be helpful in designing the perfect sonic environment.

|                               |                     |
|-------------------------------|---------------------|
| ER = Early Reflections        | Hf = High Frequency |
| LF = Late-field Reverberation | Lf = Low frequency  |

*Preset Design Tips abbreviations*

## General Tips (a tour)

- Start by setting a general timing on the ER and LF graphs to give a rough reverb size. This timing ordinarily needs to be tweaked several times along the way.
- The materials and air density define the frequency decay of the LF, and also the coloration of the ER if ER filtering is used (the slider on the right of the Reflections panel).
- Typically, materials should be blended. Try blending contrasting high frequency roll-off materials with high-frequency reflecting materials or inverse materials. This tends to add nice dimension to the LF tail. Start with one useful material and experiment with blending.
- Materials can have an extreme filtering effect if no air density is used. Most presets sound better with an air blending. If you don't want the additional coloration of air, blend with "Ideal Gas" which performs no filtering.
- The room shapes define the ER pattern; they do not effect the LF. Solo the ER and choose a shape that works well for your source or environment.
- Blending shapes does not always yield desirable results. Use shape blending with discretion, or to define a more complex room.
- Start with the EQ flat, set the approximate sound with the materials, then EQ the input to cut or boost specific frequencies.
- The EQ is often most useful for a simple LF or HF roll-off/boost, or to notch out bothersome frequencies for particular sources. For full mix ambience/mastering presets, use the EQ to cut most of all LF input, which yields added ambience without mucking up the mix. This is a powerful EQ, so experiment!
- Try different diffusion settings for your preset (the slider on the right of the Reverberation panel). Diffusion radically alters the reverberation sound and is source dependent. Higher diffusion values yield a fuller sound, good for percussive sounds; lower diffusion values yield a less dense sound, good for vocals, synths, etcetera.
- When monitoring your preset, try switching from Dry solo, Wet solo, and a useful mix. Solo the reflections and reverberation, and disable/enable EQ. Try different sources and mixes. Reach for the headphones every now and then. In general just keep things moving, as ear fatigue can be particularly deceiving with reverb sounds.
- The Positioning panel is generally only needed for automation. Ignore these settings for preset design unless going for a panning effect or monitoring real-world use.
- Often when you've got a really great preset designed, all it takes are a few subtle changes to make a number of other great presets.

## Tips for designing a natural environment sound

- Make timing proportional. As the size of the simulated environment increases, the length of the pre-delay for the EF, LF, and LF tail should increase proportionally. Typically, ER and LF pre-delay should be not too far apart, with LF starting shortly after ER.
- Place the ER timing preceding/leading into the LF
- ER amplitude naturally decays. Slope the amplitude down from left to right.
- Use ER filtering, as this improves the reverb sound in almost all situations.
- Try a gradual Lf or Hf roll-off (or boost) with the EQ section. The left and right-most EQ bands are shelf filters, which are perfect for this job. The adjacent bands can be used to shape the roll-off.
- Try natural materials and air densities before the unnatural custom or inverse materials and air densities.
- Try adding onset (slope) to the LF, as many environments naturally have an LF onset.

