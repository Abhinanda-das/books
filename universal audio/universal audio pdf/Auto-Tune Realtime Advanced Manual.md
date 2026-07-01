---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Auto-Tune Realtime Advanced Manual.pdf
converted_at: 2026-06-03T10:18:32Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 6017
---


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0001-00.png>)


Contents 

2 

## **Contents** 

|**Contents**||
|---|---|
|Introducing Auto-Tune Realtime Advanced|4|
|What is Auto-Tune Realtime Advanced?|4|
|How Does Auto-Tune Correct Pitch?|4|
|What Type of Audio is Appropriate for Auto-Tune?|5|
|General Controls|5|
|Advanced|5|
|Input Type|5|
|Key|6|
|Scale|6|
|Classic Mode|6|
|Detune|7|
|Tracking|7|
|Basic View Controls|8|
|Retune Speed|8|
|Flex-Tune|9|
|Humanize|9|
|Natural Vibrato|10|
|Pitch Display and Pitch Change Meter|10|
|The Keyboard|11|
|Keyboard Edit|12|
|Keyboard Mode|12|
|Advanced View Controls|13|
|Targeting Ignores Vibrato|13|
|Create Vibrato Controls|14|
|Shape|14|
|Rate|15|
|Onset Delay|15|
|Onset Rate|15|
|Variation|15|
|Pitch Amount|15|
|Amplitude Amount|16|
|Formant Amount|16|



Contents 

3 

|The Edit Scale Display|16|
|---|---|
|Bypass|17|
|Remove|17|
|Cents|17|
|Set Major/Set Minor|18|
|Set All|18|
|Bypass All|18|
|Remove All|18|
|MIDI Controls|18|
|Target Notes|19|
|Learn Scale|19|
|All Octaves|19|
|MIDI Parameter Control|20|
|Settings and Preferences|21|
|Enable Auto-Key Key/Scale Detection|21|
|Detune Display|21|
|Knob Control|22|
|Select Pitch Reference|22|
|Check for Updates Automatically|22|
|MIDI Input Channel|23|
|MIDI Control Assignments|23|
|Save as default|23|
|Tutorials|24|
|Pitch Correction Basics|26|
|The Auto-Tune Effect|26|
|Flex-Tune|28|
|Targeting Ignores Vibrato|28|
|Natural Vibrato|29|
|Appendix: The Scales|30|
|Modern Equal Temperament|30|
|Historical Tunings|30|
|Non-Western Tunings|31|
|Contemporary Experimental Tunings|31|



Contents 

4 

## **Introducing Auto-Tune Realtime Advanced** 

## **What is Auto-Tune Realtime Advanced?** 

For twenty years, Auto-Tune has been the industry standard for professional pitch correction and the tool of choice for the signature vocal effect of popular music. 

Now, with Auto-Tune Realtime Advanced, we're proud to bring that technology to the UAD platform, optimized for low latency tracking and live performance. 

## **How Does Auto-Tune Correct Pitch?** 

Auto-Tune works by continuously tracking the pitch of an input sound and comparing it to a user-defined scale. The scale tone closest to the input is continuously identified. If the input pitch exactly matches the scale tone, no correction is applied. If the input pitch varies from the desired scale tone, Auto-Tune will adjust the pitch toward the target scale tone. 

## **What Type of Audio is Appropriate for Auto-Tune?** 

Auto-Tune is intended for use with a well-isolated, monophonic sound source such as a single voice, or a single instrument playing one pitch at a time. It is not intended for multiples voices or instruments recorded onto the same track, or single instruments that are playing multiple pitches at the same time. 

Noise content, or extreme breathiness in vocal performance can sometimes lead to tracking errors. However, this can often be remedied by adjusting the ​Tracking parameter. 

Contents 

5 

## **General Controls** 

## **Advanced** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0005-04.png>)


The Advanced button toggles between Basic View, which shows only the most commonly used controls, and Advanced View, which shows all available controls, including the the Edit Scale Display, and the MIDI and Create Vibrato features. 

Switching back to Basic View from Advanced View will hide the advanced controls, but will not disable them. You will still hear the results of your Advanced View settings when you return to Basic View. 

## **Input Type** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0005-08.png>)


Auto-Tune Realtime Advanced offers a selection of algorithms optimized for different types of audio. Options include : Soprano, Alto/Tenor, Low Male, and Instrument. 

For more accurate pitch detection and correction, choose the Input Type that best describes your audio. 

## **Key** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0005-12.png>)


The Key menu allows you to select the key of the track you plan to process. The Key setting is used in combination with the Scale setting to determine the set of notes that the audio will be tuned to. 

## **Scale** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0005-15.png>)


The Scale selection is used in combination with the Key selection to define the scale of the track you plan to process. 

If you're not certain of the scale or key of your track, try using Auto-Key​.  Another option is to set the Scale parameter to Chromatic, which will cause 

Contents 

6 

Auto-Tune Realtime Advanced to always tune to the closest pitch in the 12-tone chromatic scale. 

## **Classic Mode** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0006-04.png>)


Classic Mode is the long-awaited return of the classic “Auto-Tune 5 sound.” 

As we’ve added new features to Auto-Tune (such as Formant Correction, Throat Modeling, and Flex-Tune) the Auto-Tune algorithm has evolved, and its sonic qualities have undergone subtle changes, with each Auto-Tune version having its own slightly different character. 

Over the years, the sound of Auto-Tune 5 has developed something of a cult following among musicians, audio engineers and producers. Due to popular demand, we’ve made the Auto-Tune 5 sound available in Auto-Tune Realtime Advanced via the new Classic Mode. 

The difference between Classic Mode and the default sound of Auto-Tune Realtime Advanced is subtle, but if you listen carefully, you may notice a slightly brighter quality, and a more pronounced attack and transition between notes at faster Retune Speeds. 

Flex-Tune is​ disabled when Classic Mode is on. 

## **Detune** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0006-11.png>)


The Detune parameter allows you to change the pitch reference of Auto-Tune Realtime Advanced from the default A = 440Hz. This is useful when working with an instrument or track that’s tuned to a different reference frequency. 

Values can be  displayed in Cents or Hertz (you can specify this in the Settings Menu). The range of adjustment is -100 cents to +100 cents. 

## **Tracking** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0006-15.png>)


In order to accurately identify the pitch of the input, Auto-Tune Realtime Advanced requires a periodically repeating waveform, characteristic of a solo voice or solo, non-chordal instrument. The Tracking control 

Contents 

7 

determines how much variation is allowed in the waveform for Auto-Tune Realtime Advanced to still consider it periodic. 

In most cases, the Tracking should be left at its default value of 50. A noisier signal or a vocal performance that is unusually breathy may require a more 'relaxed' setting (higher Tracking value). 

If you’re hearing artifacts such as clicks or pops, try setting the Tracking to a 'choosier' setting (lower Tracking value). 

Contents 

8 

## **Basic View Controls** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0008-03.png>)


Auto-Tune Realtime Advanced features two different interface views: Basic View, which shows you only the most commonly used controls, and the more in-depth Advanced View, which includes all of the available controls. 

This chapter will cover the controls that are visible in Basic view. 

## **Retune Speed** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0008-07.png>)


Retune Speed controls how rapidly the pitch correction is applied to the incoming audio. The units are milliseconds. A zero setting will cause immediate changes from one pitch to another, and will completely suppress any vibrato or deviations in pitch. 

For the Auto-Tune Effect, set the Retune Speed to zero. A setting between 10 and 50 is typical for more natural sounding pitch 

Contents 

9 

correction. Larger values allow through more vibrato and other interpretive pitch gestures, but slow down how rapidly corrections are made. 

## **Flex-Tune** 

The Flex-Tune control allows you to preserve a singer's expressive vocal gestures, while still applying the corrective tuning that Auto-Tune is famous for. 

When Flex-Tune is set to zero, Auto-Tune Realtime Advanced is always pulling every note toward a target scale note. When Flex-Tune is engaged, it only applies correction as the performer approaches the target note. As you move the control toward higher values, the correction area around the scale note gets smaller, and more expressive pitch variation is allowed through. 

## **Humanize** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0009-07.png>)


The Humanize control allows you to add realism to sustained notes when using fast retune speeds. 

One situation that can be problematic for pitch correction is a performance that includes both short and long sustained notes. In order to get the short notes in tune, you would need to set a fast Retune Speed, but this can cause sustained notes to sound unnaturally static. 

Humanize applies a slower Retune Speed only during the sustained portion of longer notes, making the overall performance sound both in tune and natural. 

Start by setting Humanize to zero, and adjust the Retune Speed until the shortest problem notes in the performance are in tune. If sustained notes sound unnaturally static, increase the Humanize setting until they sound more natural. 

Contents 

10 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0010-02.png>)


## **Natural Vibrato** 

The Natural Vibrato control allows you to either increase or diminish the range of vibrato that is already present in your audio 

If you want to create new vibrato where it doesn’t already exist, use the​ Create Vibrato​ controls in Advanced View. 

## **Pitch Display and Pitch Change Meter** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0010-07.png>)


## **Pitch Display** 

The Pitch Display shows you the letter name of the pitch that Auto-Tune Realtime Advanced is currently outputting (e.g. C# or Bb). 

This may be different than the pitch that it is detecting, if the detected pitch is not part of the current scale. 

To see the pitch that is currently being detected in the incoming audio, look at the blue highlighted note in the Keyboard. 

## **Pitch Change Meter** 

The Pitch Change Meter (which wraps around the Pitch Display) shows you how much the pitch is being changed, measured in cents. 

For example, if the blue indicator bar has moved to the left to -50, it indicates that the input pitch is 50 cents too sharp and Auto-Tune is lowering the pitch by 50 cents to bring the input back to the desired pitch. 

## **Hold** 

Clicking and holding the word “Hold” while Auto-Tune is processing audio will freeze both the Pitch Display and the blue detected pitch indication on the keyboard for as long as you hold down the mouse button. 

Contents 

11 

## **The Keyboard** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0011-03.png>)


The Keyboard displays the currently detected pitch in real time, and also allows you to specify the target-note behavior for each note in specific octaves. 

During playback, the detected pitch will be highlighted in blue on the Keyboard. You can also use the Keyboard to set individual notes to On, Bypass, or Remove. 

The Keyboard is only enabled when using scales that have exactly 12 notes. If you want to use the Keyboard with the Major or Minor scale, choose the Chromatic scale and then click Set Major or Set Minor (in Advanced View). 

## **On** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0011-08.png>)


When a note on the Keyboard is on, it will appear white or black (depending on which note it is), and input pitches that are closest to that note will be tuned to it. 

## **Bypass** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0011-11.png>)


When a note on the Keyboard is set to Bypass it will appear orange, and input pitches that are closest to that note will be passed through with no correction. 

## **Remove** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0011-14.png>)


When a note on the Keyboard is set to Remove, it will appear grey, and any incoming pitches that are closest to that note will be tuned to the next closest scale note instead. 

Contents 

12 

## **Keyboard Edit** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0012-03.png>)


When the Keyboard Edit switch is set to Remove, clicking on a key in the Keyboard will toggle it between Remove and On. When it’s set to Bypass, clicking on a key will toggle it between Bypass and On. 

## **Keyboard Mode** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0012-06.png>)


When the Keyboard Mode switch is set to Latch, clicking on a key in the Keyboard will change its state, and it will retain the new state. 

When Keyboard Mode is set to Momentary, clicking on a key will change its state only for as long as the mouse button is held down. This is useful, for example, if you want to perform a melody on the Keyboard in real time. 

Contents 

13 

## **Advanced View Controls** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0013-03.png>)


Auto-Tune Realtime Advanced features two different interface views: Basic View, which shows you only the most commonly used controls, and Advanced View, which includes all of the available controls. 

This chapter will cover the controls that are only visible in Advanced view. 

## **Targeting Ignores Vibrato** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0013-07.png>)


The Targeting Ignores Vibrato function is is designed to help Auto-Tune identify pitches correctly when a performance includes vibrato so wide that it approaches adjacent notes (e.g  if a singer is singing a C with a vibrato so wide that it is sometimes closer to a 

C#). 

Contents 

14 

If you hear a rapid alternation between two notes when you want to be hearing a single note with a wide vibrato, try turning this on. 

## **Create Vibrato Controls** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0014-04.png>)


The Create Vibrato controls allow you to add a custom synthesized vibrato to your audio. Use them sparingly to add a touch of natural-sounding expression to a performance or more aggressively for dramatic special effects. 

## **Shape** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0014-07.png>)


The Shape menu allows you to choose the shape of the pitch modulation for your vibrato. 

The choices are: 

## **No Vibrato** 

Leave the Shape menu set to No Vibrato if you don’t want to create any vibrato. 

## **Sine Wave** 

A sine wave changes smoothly from minimum to maximum and back again. This is the best choice for natural-sounding vibrato. 

## **Square** 

Jumps to maximum where it spends half of the cycle and then jumps to minimum for the remaining half of the cycle. 

## **Sawtooth** 

Gradually rises from minimum to maximum and then drops instantaneously to minimum to start the cycle again. 

Contents 

15 

## **Rate** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0015-03.png>)


The Rate control sets the speed of the vibrato in Hz. 

## **Onset Delay** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0015-06.png>)


Onset Delay sets the amount of time (in milliseconds) between the beginning of a note and the onset of vibrato. 

## **Onset Rate** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0015-09.png>)


Onset Rate sets the amount of time (in milliseconds) between the onset of vibrato and the point at which the vibrato reaches the full amounts set in the Pitch, Amplitude and Formant Amount settings. 

## **Variation** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0015-12.png>)


Variation sets the amount of random variation that will be applied to the Rate and Amount parameters on a note to note basis. This is useful for humanizing the vibrato by adding random deviation. 

## **Pitch Amount** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0015-15.png>)


Pitch Amount sets the width of the vibrato in cents. 

Contents 

16 

## **Amplitude Amount** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0016-03.png>)


Amplitude Amount sets the amount that the loudness changes. For more realistic vibrato, the amount of amplitude change should usually be substantially less than pitch change. 

## **Formant Amount** 

Formant Amount sets the amount of formant variation in the vibrato. A sound’s formants are the resonant frequencies that result from the physical structure of whatever is producing the sound (e.g. the human mouth and vocal tract). 

## **The Edit Scale Display** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0016-08.png>)


The Edit Scale Display is used to create custom scales or to modify any of the preset scales selected in the Scale menu. It shows each of the notes of the currently selected scale, along with a Bypass and Remove button for each note (explained below). 

Each scale retains its own edits independent of the other scales. For example, if you select C Major in the Key and Scale menus and Remove or Bypass certain notes, and then change to C Minor and make other edits, when you return to C Major your previous edits associated with C Major will be restored. 

Changes made in the Edit Scale Display affect all octaves of each note in the scale, and will also be displayed on the Keyboard (in 12-note Scales only). Changes made on the 

Contents 

17 

Keyboard only affect that specific octave, and will not be reflected in the Edit Scale Display. 

## **Bypass** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0017-04.png>)


If a note is bypassed, input pitches that are closest to that note will be passed through with no correction. 

You might use Bypass if a performance has 

only one or two out-of-tune notes, and you want to only apply correction on those notes, or if it includes some expressive pitch gestures around one or more specific notes that you want to preserve with no modification. 

## **Remove** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0017-09.png>)


If the Remove button is lit, then the note is removed from the current scale, and any incoming pitches that are closest to that note will be tuned to the next closest scale note instead. 

Remove can be used to create your own custom scales from the built-in scales. For example, you can create a pentatonic (5-note) scale by removing a couple notes from the major scale. This is especially useful if you’re going for the Auto-Tune Effect, and want to create a sharp transition between notes that are relatively far apart. 

Remove is also useful in cases where a singer might be singing a pitch that is so far from the intended note that it’s actually closer to another scale note. For example, if the intended note is an F and the performer is actually singing something closer to an E, you may want to remove E from the scale, so that the singer will be tuned to F instead. 

## **Cents** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0017-14.png>)


The number under each note in the Cents row is that note’s interval, in cents, from the root note of the scale. 

Contents 

18 

## **Set Major/Set Minor** 

The Set Major and Set Minor buttons allow you to quickly generate a major or minor scale from any scale with more than 7 notes, by automatically removing the notes that don’t belong to the major or (natural) minor scale. 

## **Set All** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0018-05.png>)


The Set All  button sets all of the notes of the current scale to On, in both the Edit Scale Display and the Keyboard. This is a quick way to return the scale to its default setting. 

## **Bypass All** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0018-08.png>)


Bypass All sets all notes in the current scale to Bypass. 

## **Remove All** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0018-11.png>)


Remove All sets all notes in the current scale to Remove. 

## **MIDI Controls** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0018-14.png>)


Auto-Tune Realtime Advanced has two different functions for handling incoming MIDI 

note data: Target Notes and Learn Scale. You can also use a MIDI controller to control many of the Auto-Tune Realtime Advanced parameters. See the Settings and Preferences section for how to assign control of parameters to your MIDI controller, 

Contents 

19 

Use the ​ **Target Notes​** function if you want to use MIDI to control the specific pitch that your audio is being tuned to in real time. 

Use the ​ **Learn Scale​** function if you want to use MIDI instead of the Edit Scale Display and onscreen Keyboard to define the scale that your audio will be tuned to. 

In order to make use of the Auto-Tune Realtime Advanced MIDI capabilities, you will need to route a MIDI source to it. This could be an external controller, such as a MIDI keyboard, or it could be a MIDI track within your host application (DAW). The procedure for routing MIDI to an audio plugin will vary depending on what DAW you are using, so please see your DAW’s manual or help pages for more information. 

## **Target Notes** 

With MIDI: Target Notes, you can perform a melody in real time on a MIDI keyboard, or play it from a MIDI track, and Auto-Tune Realtime Advanced will tune your audio to whatever MIDI notes are on at any given time. 

If you’re using a MIDI keyboard, this means that your audio will be tuned to the notes corresponding to whatever keys you are currently holding down. 

If no MIDI notes are on, the audio will pass through without being tuned. 

## **Learn Scale** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0019-10.png>)


The MIDI: Learn Scale function allows you to play a melody or chords from a MIDI keyboard or MIDI track and have Auto-Tune construct a custom scale for you containing only those notes. 

Clicking the Learn Scale button will remove all notes from the current scale. Individual notes are then turned back on based on incoming MIDI data. The new scale settings will be displayed in both the Keyboard and Edit Scale Display. 

## **All Octaves** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0019-14.png>)


If All Octaves is on, any incoming MIDI notes will affect all octaves of each note. Otherwise, they will only affect the notes in the 

Contents 

20 

specific octaves in which they are played. The All Octaves button applies to both the Target Notes and Learn Scale functions. 

## **MIDI Parameter Control** 

Many of the Auto-Tune Realtime Advanced parameters can be controlled in real time with a MIDI controller. MIDI Parameter Control is configured in the Preferences window. See the MIDI Control Assignments section below for information about how to configure this. 

Contents 

21 

## **Settings and Preferences** 


![](<Auto-Tune Realtime Advanced Manual_assets/Auto-Tune_Realtime_Advanced_Manual.pdf-0021-03.png>)


## **Enable Auto-Key Key/Scale Detection** 

This setting enables Auto-Tune Realtime Advanced to receive key and scale information from ​Auto-Key 

## **Detune Display** 

The ​Detune​ control is used to tune to a reference frequency other than the standard A = 440 Hz. Select Detune Display lets you choose whether it will display the offset in cents or Hertz. 

## **Knob Control** 

Knob Control lets you select how you want to control the knobs in the Auto-Tune Realtime Advanced interface. Options include Linear, Circular, and Follow Host. 

Contents 

22 

## **Linear** 

Click on the knob and drag up or to the right to turn it clockwise, down or left to turn it counterclockwise. 

## **Circular** 

Click on the knob and drag in a circle to rotate the knob. 

## **Follow Host** 

If this option is chosen, Auto-Tune Realtime Advanced will attempt to follow the knob control behavior of the host application (DAW). If the host application does not provide that information to plugins, the behavior will default to Linear. 

## **Select Pitch Reference** 

Auto-Tune Realtime Advanced provides the ability to pitch correct stereo tracks while maintaining phase coherence between the two channels. The Select Pitch Reference setting lets you choose which of the stereo tracks will be used to analyze the pitch. If one channel is cleaner or better isolated than the other, select that channel as the pitch reference. 

When using Auto-Tune Realtime Advanced on a stereo track, both channels should feature the same source material (e.g. the same vocal performance recorded with two microphones). 

## **Check for Updates Automatically** 

Leave this item checked if you would like to check for updates every time you open Auto-Tune Realtime Advanced. 

## **MIDI Input Channel** 

Selects the MIDI channel for Auto-Tune Realtime Advanced to receive MIDI CC messages. The Omni setting will allow Auto-Tune Realtime Advanced to respond to messages on any channel. 

Contents 

23 

## **MIDI Control Assignments** 

Many of Auto-Tune the Realtime Advanced parameters can be controlled in real time with any MIDI controller that sends MIDI CC (continuous controller) messages. 

To assign an Auto-Tune Realtime Advanced parameter to one of the controls on your MIDI device, enter the MIDI CC value that your MIDI controller sends from that control. 

Check your MIDI controller’s documentation for information about what MIDI CC value is sent by each control. You can also use a utility application such as ​MIDI Monitor​ to see what CC messages are being sent by your controller. 

You will also need to route the MIDI to Auto-Tune Realtime Advanced within your host application (DAW). The procedure for routing MIDI to an audio plugin will vary depending on what DAW you are using, so please see your DAW’s manual or help pages for more information about how to do this. 

## **Save as default** 

When the Save as Default box is checked, any changes to Preferences that you save will become the default settings for future instances of Auto-Tune Realtime Advanced. 

If you want to make a temporary change to the preferences just for this instance, without overwriting your default preferences, uncheck this box before clicking “Save”. 

Contents 

24 

## **Tutorials** 

This chapter will introduce you to how Auto-Tune Realtime Advanced works by guiding you through some brief tutorials. 

## **Pitch Correction Basics** 

This tutorial will guide you through the basic pitch correction features using the audio file “A2- A3-A2 sweep.” This is a simple synthesized waveform sweeping slowly from A2 up to A3 and back to A2. 

## **To begin** 

1. Load or import “A2-A3-A2 sweep” into a track of your host program. Play the track to hear the unprocessed audio. 

2. Open Auto-Tune Realtime Advanced as an insert effect on that track. 

## **Scale and Key Settings** 

3. Set the ​Key​ to “A” and the ​Scale​ to “Major.” 

4. Set ​Retune Speed​ to zero. 

5. Set ​Flex-Tune​ to zero. 

6. Set “A2-A3-A2 sweep” to loop continuously in your host program and start playback. 

What you will hear is an A major scale. This is because Auto-Tune Realtime Advanced is continuously comparing the input pitch to the notes of the A major scale and instantly correcting the output pitch to the nearest of the scale tones. 

## **Remove Notes** 

1. Click the ​Advanced​ button to show the Advanced View controls. 

2. In the ​Edit Scale Display​, click the ​Remove​ buttons under the notes B, D, F# and G#. 

3. Play “A2-A3-A2 sweep” again. 

Contents 

25 

You will now hear an arpeggiated A Major triad because you have removed all the other notes from the scale. 

## **Bypass Notes** 

1. In the Edit Scale Display, click the ​Bypass​ button under the note E. 

2. Play “A2-A3-A2 sweep” again 

You’ll now hear the effect of bypassing the E. When the input pitch approaches E Auto-Tune Realtime Advanced passes the input through uncorrected. 

## **Retune Speed** 

1. Set the Retune Speed to 0 

2. Play “A2-A3-A2 sweep” 

3. Set the Retune Speed to about 30. 

4. Play “A2-A3-A2 sweep” again. Compare the 30 setting to the 0 setting. 

5. Try various other Retune Speed settings. 

The setting of 0 (milliseconds) is fast, and Auto-Tune Realtime Advanced makes instantaneous pitch changes. The setting of 30 is slower, and pitch changes are more gradual. Retune Speed controls how rapidly the pitch correction is applied to the incoming pitch. 

## **Detune** 

1. Set the Retune Speed to 0. 

2. In the Edit Scale Display, click the Remove buttons below all the notes except F#. 

3. Play “A2-A3-A2 sweep” again. As the sound is playing, move ​Detune​ knob. 

The output pitch will be locked to F#, however, you will hear the output pitch change with the Detune knob movement. This is because the Detune knob is changing the pitch standard of the scale. 

Contents 

26 

## **Create Vibrato** 

1. In Advanced View​,​ Select Sine Wave from the​ ​Shape​ menu in the ​Create Vibrato section. 

2. Play “A2-A3-A2 sweep” again. 

3. Experiment with the various Create Vibrato controls to hear their effects. 

## **The Auto-Tune Effect** 

In addition to being the industry standard for pitch correction, Auto-Tune is the tool of choice for one of the signature vocal sounds of popular music: the Auto-Tune Effect. 

First heard on Cher’s 1998 hit song “Believe,” variations of the Auto-Tune Effect have appeared in songs from a huge variety of artists. 

## **What is it?** 

The Auto-Tune Effect is what is technically known as “pitch quantization.” Instead of allowing all of the small variations in pitch and the gradual transitions between notes that are a normal part of singing, the Auto-Tune Effect limits each note to its exact target pitch, stripping out any variation, and forcing instantaneous transitions between notes. 

## **How to do it** 

There are basically three key elements to producing the Auto-Tune Effect in Auto-Tune Realtime Advanced: 

1. Set ​Flex-Tune​ to 0. 

2. Set ​Retune Speed​ to 0. 

3. Pick the right ​scale 

## **Step-by-step** 

1. Start by setting both ​Flex-Tune​ and ​Retune Speed​ to 0. 

2. Set the ​Key​ and ​Scale​ to the key and scale of your track. 

Contents 

27 

3. Play your track. If you like the result, you’re done. 

4. If you’re not happy with the result, try one or more of the following: 

   - Edit the scale notes using the ​Keyboard​ or ​Edit Scale Display​. Adding or removing scale notes can give you distinctly different effects. Removing some notes can be especially effective for a more dramatic effect on note transitions. 

   - Try a different key and/or scale. 

   - Try a Retune Speed of 2 or 3 or a bit slower. This will allow slight pitch variations and slightly less instant note transitions, but may result in the right effect for a particular performance. 

   - Try turning on ​Classic Mode​, for a subtly different flavor of the Auto-Tune Effect 

   - Don’t forget your host application’s bypass and automation functions. Limiting the Auto-Tune Effect just to specific phrases can provide sonic contrast in your song. 

## **Flex-Tune** 

This tutorial will guide you through the use of ​Flex-Tune​ using the same “A2-A3-A2 sweep” file. 

## **To begin** 

1. Load or import “A2-A3-A2 sweep” into a track of your host program. 

2. Set up Auto-Tune Realtime Advanced to be an insert effect on that track. 

3. Set the​ ​Key​ ​to A and the ​Scale​ to Major. 

4. Set the ​Retune Speed​ to zero. 

## **No Flex-Tune** 

1. Set Flex-Tune to 0. 

2. In the ​Edit Scale Display​, click the​ ​Remove​ buttons next to the notes B, D, F# and G#. 

3. Play “A2-A3-A2 sweep.” 

Contents 

28 

You’ll hear an arpeggiated A Major triad because you have removed all the other notes from the scale. 

## **Some Flex-Tune** 

1. Set Flex-Tune of 10. 

2. Play “A2-A3-A2 sweep” again. 

With a lower Flex-Tune setting such as 10, the correction range around each scale note is still quite wide.You will hear each note of the A Major triad instantly tuned as the sweep enters the correction range, but as the sweep moves out of the correction range, you will hear it transition to the next note without correction. 

## **More Flex-Tune** 

1. Set Flex-Tune to of 55. 

2. Play “A2-A3-A2 sweep” again. 

At higher Flex-Tune settings, the correction range around each scale note becomes more narrow. Consequently, each scale note will be tuned to only briefly as the sweep passes through the narrow correction range and will transition to the next note without correction as it leaves the correction range. 

## **Targeting Ignores Vibrato** 

This tutorial will demonstrate the ​Targeting Ignores Vibrato​ feature. Targeting Ignores Vibrato helps Auto-Tune identify pitches correctly when a performance includes vibrato so wide that it approaches adjacent notes. 

1. Load or import “wide_vibrato” into a track of your host program. This is a recording of a male voice singing a sustained “G” with a wide vibrato. 

2. Play the track to hear the unprocessed audio. In addition to the vibrato, you’ll notice that the singer drifts alternately sharp and flat. 

3. Set up Auto-Tune Realtime Advanced to be an insert effect on that track. 

4. Set the ​Key​ to C and the​ ​Scale​ to Chromatic. 

5. Set the ​Input Type​ to Low Male Voice 

Contents 

29 

6. Set ​Retune Speed​ to 24. 

7. Set “wide_vibrato” to loop continuously in the host application and begin playback. Watch the blue detected pitch indication on the ​Keyboard​, and listen to the result. As you will hear, whenever Auto-Tune Realtime Advanced thinks G# or F# is the target pitch, it will move the input closer to those notes, instead of toward G. 

8. Click ​Advanced​ to show the ​Advanced View controls​, then click Targeting Ignores Vibrato to turn it on. With Targeting Ignores Vibrato engaged, Auto-Tune Realtime Advanced recognizes the pitch deviations as vibrato and continues to use “G” as the target pitch. 

## **Natural Vibrato** 

This tutorial will demonstrate the​ ​Natural Vibrato​ feature using the “wide_vibrato” audio file. The Natural Vibrato feature allows you to increase or diminish the range of vibrato that is already present in your audio. 

1. Load or import “wide_vibrato” into a track of your host program. This is a recording of a male voice singing a sustained “G” with a wide vibrato. Play the track to hear the unprocessed audio. 

2. Open Auto-Tune Realtime Advanced as an insert effect on that track. 

3. In Auto Mode, Set the ​Key​ to C and the ​Scale​ to Chromatic. 

4. Set the ​Input Type​ to Low Male Voice 

5. Set ​Retune Speed​ to 24. 

6. Set “wide_vibrato” to loop continuously and begin playback. 

7. Set Natural Vibrato to 12 and note the effect on the vibrato. Set Natural Vibrato to 

   - -12 and note the effect on the vibrato. 

8. In the ​Edit Scale Display​ set all Scale notes to ​Bypass​ ​to disable any pitch correction. Again, adjust the Natural Vibrato control and note that it’s still active even when pitch correction is not being applied. 

Contents 

30 

## **Appendix: The Scales** 

The following are brief descriptions of the scales available in Auto-Tune Realtime Advanced. The first three equal-tempered scales are the common scales found in Western tonal music and popular music. In addition, a number of historical, non-Western, and experimental scales are available. 

## **Modern Equal Temperament** 

**Major: ​** a seven-tone equal tempered major scale. 

**Minor:​** a seven-tone equal tempered minor scale. 

**Chromatic​** : a twelve-tone equal tempered chromatic scale. 

## **Historical Tunings** 

**Ling Lun:​** a twelve-tone scale dating from 2700 B.C. China. 

**Scholar’s Lute:​** a seven-tone scale dating from 300 B.C. China. 

**Greek Diatonic Genus​** : a seven-tone scale from ancient Greece. 

**Greek Chromatic Genus:​** a seven-tone scale from ancient Greece. 

**Greek Enharmonic Genus:​** another seven-tone scale from ancient Greece. 

**Pythagorean​** : a twelve-tone scale based on a series of just perfect fifths, resulting in wider major thirds. 

**Just (major chromatic)​** : a twelve-tone scale based on the harmonic series, and optimized for the major mode. 

**Just (minor chromatic):​** a twelve-tone scale based on the harmonic series, and optimized for the minor mode. 

Contents 

31 

**Werckmeister III:​** a twelve-tone well-tempered scale. This scale was an early attempt (about Bach’s time) to allow for transposition to be played in any key. 

**Vallotti & Young: ​** a twelve-tone well-tempered scale designed to allow arbitrary keys. 

**Barnes-Bach:​** a twelve-tone well-tempered scale. A variation of the Vallotti & Young scale designed to optimize the performance of Bach’s Well-Tempered Clavier. 

## **Non-Western Tunings** 

**Indian:​** A 22-tone just scale. 

**Slendro: ​** A five-tone Indonesian scale is played by percussion ensembles called gamelans. 

**Pelog​** : A seven-tone Indonesian scale also used in gamelan music. 

**Arabic 1​** : A 17-tone arabic scale related to the Pythagorean scale. 

**Arabic 2 (chromatic):​** A twelve-tone variation of the previous Arabic scale 

## **Contemporary Experimental Tunings** 

**19 Tone Equal Temperament​** : Divides the octave into 19 equal parts. Thirds and sixths more closely resemble those found in just intonation than 12-tone equal temperament. Perfect fifths are narrower than those found in twelve-tone equal temperament. 

**24 Tone Equal Temperament:​** Also known as the quarter tone scale, this scale divides the octave into 24 equal parts. Does not offer a significant advantage over 12-tone equal temperament in terms of approximating just intervals. 

**31 Tone Equal Temperament:​** Divides the octave into 31 equal parts. Offers an excellent approximation of the just harmonic seventh interval often found in a cappella vocal music, such as barbershop. 

Contents 

32 

**53 Tone Equal Temperament:​** Divides the octave into 53 equal parts. The 53-tone scale has good approximations of just major and minor thirds, and fifths and fourths. 

**Partch:​** Harry Partch is considered by many to be the father of modern experimental tuning practice. This 43-tone just scale was devised by him and used in his compositions and instruments. 

**Carlos Alpha:​** Wendy Carlos performed extensive computer analysis to devise a number of equal tempered scales which sacrifice the perfect octave in order to achieve better approximations of other harmonic intervals and their inversions. This scale is good at approximating several just intervals including 7/4. This scale divides the octave into 15.385 steps forming intervals of 78.0 cents. 

**Carlos Beta:​** This scale divides the octave into 18.809 steps forming intervals of 63.8 cents. 

**Carlos Gamma: ​** This scale maintains the just intervals 3/2 and 4/3 and also approximates 5/4. This scale divides the octave into 34.188 steps forming intervals of 35.1 cents. 

**Harmonic (chromatic): ​** This twelve-tone scale is created in the partials in the fifth octave of the harmonic series. The scale degrees that correspond to the classic just intervals are the major second, major third, perfect fifth and major seventh. 

