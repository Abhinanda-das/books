---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/elysia mpressor Manual.pdf
converted_at: 2026-06-03T09:53:59Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 4152
---


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0001-00.png>)


**mpressor** 

## **WeLcOMe! introduction** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0002-01.png>)


## **FIRST OF ALL...** 

...thank you very much for using the mpressor plugin! 

The ‘virtual’ mpressor is the as-close-as-it-canget emulation of our famous creative compressor. Its all discrete circuitry and its special character have been translated into software in every painstaking detail.... 

The plugin offers the great functions of the hardware which can be combined in many ways. 

Whatever you are looking for – a high grade sum compressor, a flexible tool for single instruments or an inspiring dynamics effect processor: the mpressor delivers. 

Enjoy it! 

The result is an outstanding universal compressor as well as a dynamics effect machine which will significantly enhance the potentials of your host software. 

manual version UAD 1.0 

introduction - welcome! 

2 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0003-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0003-02.png>)


**Floor:** switches the emulation of the mpressor’s analog noise floor on and off. 

**Link:** left and right channel can be linked on a stereo track. 

**Active:** sets the plugin from bypass to active status. 

**GRL:** indicates activity of the Gain Reduction Limiter. 

**Meter:** displays the amount of gain reduction in dB. 

**Threshold:** If the input level exceeds this value, the compression process will start. 

**Attack:** the transient response of the compressor. It determines the time the mpressor takes to react to a peak. 

**Auto Fast:** a semi-automation. This function shortens the attack time automatically on fast and loud signal impulses. 

**Release:** the return phase of the compressor. It controls the period of time that the compressor takes to return back to unity gain after 6 dB of gain reduction. 

**Anti Log:** an alternative characteristic of the release curve. Switches from a linear to an antilogarithmic progression. 

**Ratio:** the relation between the input level and the output level. As a specialty of the mpressor, even negative ratios can be set here. 

controls - overview 

3 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0004-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0004-02.png>)


- **eQ Gain:** the characteristic of the Niveau Filter. Between the mid and fully counterclockwise position, bass is boosted and treble is cut (vice versa in the other direction). 

- **x10:** shifts the frequency range of the Niveau Filter. The printed values from 26 Hz to 2.2 kHz are multiplied by 10 to 260 Hz and 22 kHz. 

**Gain:** the ‘make up gain‘. In the mpressor, amplification already takes place in the input stage, thus the whole plugin can be driven harder on purpose. 

- **On:** activates the Niveau Filter. In the signal path, this special EQ is placed after the compressor part, thus it will not influence the behavior of this section. 

**GR Limit:** limits the virtual control voltage. This innovative limiter is not placed in the audio path as usual, but in the control algorithm of the compressor. 

**version:** A click on the elysia logo will reveal the actual version of the plugin you have installed and the people behind the project. 

- **eQ Freq:** the center frequency of the Niveau Filter. Around this reference point, the bass is boosted and treble is cut or vice versa. 

- **On:** activates the Gain Reduction Limiter. 

controls - overview 

4 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0005-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0005-02.png>)


The threshold determines the operating point of the compressor. If the input level exceeds the value set with this controller, the compression process will start. 

The settings of threshold and ratio should always be considered as a couple: If a high ratio is applied, the threshold will usually be in the lower range in order not to produce an overdone amount of gain reduction. 

However, if lower ratio settings are chosen, the threshold will be turned more clockwise as a general rule. 

The complete control range covers a total of 34 dB, offering the complete variety from very sensitive processing up to the most extreme effect settings. 

The figure to the right shows a number of different threshold points of the mpressor. 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0005-08.png>)


**----- Start of picture text -----**<br>
dB<br>dB<br>**----- End of picture text -----**<br>


Several threshold settings at a fixed ratio 

controls - threshold 

5 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0006-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0006-02.png>)


The attack time parameter is a very crucial factor for the control behavior of a compressor. Choosing the right setting is very important, but depending on the dynamic progress of the source material this can be a difficult task. 

If a very short time is chosen, the compressor will be able to catch the short peaks, but on the other hand the sustaining signal will also be processed, which might result in audible distortion. Longer attack settings reduce distortion significantly, but then the compressor is too slow for fast impulses. 

This is where the Auto Fast function comes into play. If you engage this mode, the attack time will be shortened automatically on fast and loud signal impulses. The compressor reduces the signal quickly and prevents it from slipping through. 

Then the attack time directly and automatically returns to its original setting. This way the compressor can be very fast, but only if it is really needed. The attack parameter is influenced on short and loud impulses only; in all other cases the controller setting is given priority. 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0006-07.png>)


**----- Start of picture text -----**<br>
dB<br>sec<br>**----- End of picture text -----**<br>



![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0006-08.png>)


**----- Start of picture text -----**<br>
dB<br>sec<br>**----- End of picture text -----**<br>



![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0006-09.png>)


**----- Start of picture text -----**<br>
Standard attack (dark) and Auto Fast (light)<br>**----- End of picture text -----**<br>


controls - attack 

6 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0007-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0007-02.png>)


The release parameter, on the other hand, has a strong influence on the character of the compression being obvious or unobtrusive to the ear. As a general rule, linear or logarithmic release curves will be employed if a discreet performance of the compressor is required. 

It is characteristic of a logarithmic release that the time constant shortens when the gain reduction raises. The advantage of this is that short and loud peaks (e.g. drums) have a fast release time, while the remaining material is processed with a slower release time. 

But if intentionally striking and creative compression as well as producing new and interesting sounds are the sought-after goals, it definitely makes sense to turn the established approach upside down. For this reason, you can switch the release curve of the mpressor from linear to antilogarithmic. 

Compared to a logarithmic release curve, the effect of the Anti Log option behaves just the other way round: If the threshold point is passed, the release time will no longer be shortened at first. If the input signal starts to decline, however, the release time will become faster. 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0007-07.png>)


**----- Start of picture text -----**<br>
dB<br>sec<br>**----- End of picture text -----**<br>



![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0007-08.png>)


**----- Start of picture text -----**<br>
dB<br>sec<br>**----- End of picture text -----**<br>


Standard linear release (dark) and Anti Log (light) 

controls - release 

7 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0008-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0008-02.png>)


The mpressor is a typical hard knee compressor, which is easy to see in the diagram to the right. Compression directly starts with the full ratio in the very moment the input signal passes the threshold point. 

Compared to a soft knee characteristic, this kind of compression is more on the noticeable and audible side. 

The mpressor also features negative ratios – but what exactly does this mean? At a negative ratio, the characteristic curve bends and returns back down after crossing the threshold. 

The louder the input signal becomes with a setting like this, the lower the output level becomes – perfect for groovy compression effects. 

To get a grip on the extreme ‘destruction’ this can cause, engaging the Gain Reduction Limiter is just the right idea. 

This special capability of the mpressor might seem a little hard to understand in theory. Just give it a try with some drum samples and you will understand what this is all about... 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0008-09.png>)


**----- Start of picture text -----**<br>
dB<br>dB<br>**----- End of picture text -----**<br>


Different ratio settings including negative values 

controls - ratio 

8 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0009-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0009-02.png>)


This filter is specialized in changing the overall sonic character of a track with ease. 

Its main function is to change the proportions between high and low frequencies. The principle is similar to a pair of scales: Dependent on the gain setting around a variable center frequency, the high frequencies are boosted and the low frequencies are cut (or vice versa). 

The characteristics of the filter change in the extreme positions of the EQ Gain controller: the full counter-clockwise setting will produce a low pass filter (full clockwise = high pass). 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0009-06.png>)


**----- Start of picture text -----**<br>
dB dB<br>hz hz<br>**----- End of picture text -----**<br>


EQ Gain settings between 0 and Hi position @ 500 Hz 

EQ Gain settings between 0 and Lo position @ 1.5 kHz 

controls - niveau filter 

9 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0010-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0010-02.png>)


A specialty of the mpressor plugin is the Gain Reduction Limiter. This limiter is not placed in the audio path where you would expect it, but in the control path of compressor instead. 

The effect: No matter how high the input level or your threshold and ratio settings become – the amount of gain reduction will never exceed the value which is set with the GRL controller. 

Loud parts in an arrangement can keep their dynamics, and special effects like ducking or upward compression can be achieved by only reducing the quieter signal parts. 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0010-06.png>)


**----- Start of picture text -----**<br>
dB dB<br>sec dB<br>Compression progress at different GRL settings Input to output ratio at different GRL settings<br>**----- End of picture text -----**<br>


controls - gain reduction limiter 

10 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0011-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0011-02.png>)


The gain controller is used to make up the difference in level between the original and the compressed signal. As you might already have expected, there is something special about this ‘standard’ controller on the mpressor, too: 

The higher the amount of gain it is, the more harmonics are produced. In the mpressor, this function is located directly in the input stage, therefore the added harmonics will be processed by the complete compressor algorithm. 

The diagram to the right shows the saturation behavior of the mpressor plugin at increasing 

amplitudes. It clearly shows how the original sine form is shaped with an additional edge reminding of a square wave form. This produces a rich sound by generating additional harmonics. 

If you want your signal to stay clean, you should take care not to use lots of make up gain, but use a simple gain plugin from your host software directly after the mpressor instead. 

However, if added harmonics are just what you are looking for, apply a good amount of make up gain with the mpressor and use a following gain plugin to reduce the overall level. 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0011-09.png>)


**----- Start of picture text -----**<br>
v<br>   sec<br>**----- End of picture text -----**<br>


Saturation characteristics at several amplitudes 

controls - gain 

11 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0012-00.png>)


## **controls** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0012-02.png>)


## **FLOOR** 

This button switches the emulation of the mpressor’s analog noise floor at -96 dBFS on and off. 

## **LINk** 

In link mode, the mpressor uses the information of both the left and the right channel to generate one combined ‘virtual control voltage’ which is then applied to both channels (a true stereo compressor in this case). 

If the link mode is not active, imagine the mpressor plugin as a dual mono compressor 

that generates separate ‘virtual control voltages’ for left and right channel with the same controller settings. 

But why would this make any sense? The answer is that by running a stereo compressor in unlinked mode you might benefit from a more vivid feeling of your track. This is because both channels are compressed differently from each other (as a result of different signals in the left and right channel). 

## **MONO** 

On a mono channel, the link function is obvi- 

ously not available. The link button is semitransparent in this case to indicate it is not available. 

## **AcTIve** 

There is no big secret behind this button: It switches the mpressor into the signal path (white control light on) or bypasses the plugin (light off). 

By the way: On a hardware mpressor, the gain reduction meter stays active even if the unit is in bypass mode. The software version does not have this feature because of technical reasons. 

controls - floor | link | active 

12 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0013-00.png>)


## **settings** 

Because of the well-balanced adjustment of its parameters, the mpressor is suited perfectly for many applications in everyday studio business. 

The settings shown in the above figure provide a good starting position for ‘normal’ compression jobs like vocals, choirs, guitars, drums, keyboards and so on. 

Moderate ratios from 1:2 to 1:5 and release times around 300 ms make a good basis for further parameter variations. The threshold controller is used to adjust the desired amount of gain reduction. 

*** *** Keep in mind that the mpressor is a hard knee design. This means that if you are looking for subtle compression, you will need to use moderate settings to get there. to very extreme compression results. 

Realize that the mpressor gives you an ample range of possible settings, which like the super fast attack times or the negative ratios can lead to very extreme compression results. 

While this can be very cool in lots of cases, it might not always be what you are actually looking for. With the mpressor, you get what you set. Take some time to find out which settings work best for you. 

Depending on the source material, the EQ section can be used in addition with great benefit. It definitely pays off to spend some time on getting to know this interesting feature of the mpressor and what it can do for your sound. 

The Gain Reduction Limiters offer completely new possibilities, too, and therefore should be given a try soon by all means. 

***** You will need to adapt _all_ suggested settings to your actual source material. This is especially important for the threshold and ratio controls! 

settings - standard compression 

13 

## **BIG dRUMS settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0014-01.png>)


In this case, a complete drum mix is processed with the mpressor. The intensity of audible transients is determined by the attack time. If this parameter is very short, only the first milliseconds of the signal will be emphasized, whereas longer settings will come closer to its original structure. 

The release controller can now be used to adjust the loudness. Shorter settings will produce louder signals, while longer settings can influence the groove of a track in a nice way. 

If high ratios are applied, this effect will become 

more and more extreme. You can use the Gain Reduction Limiter to use such settings without producing too wild results in order to get very energetic drums. 

Drums like these are very punchy, with beautiful attacks that can really shine in a mix. An increased amount of ambience is generated on top of it, resulting in a loud and massive sound. 

We have received lots of good feedback from our hardware mpressor customers, and one comment is mentioned time and again: “The mpressor is killer on drums!” 

If you ask us, this pretty much nails it. Make sure to give it a good try with some drums you really like - this is not only about compression, it is about ambience, transients, sonic structure, too... 

So many attributes you can influence with the mpressor plugin... just go ahead! 

settings - big drums 

14 

## **SMAShed dRUMS settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0015-01.png>)


If the drums are supposed to sound extremely compressed and loud, this setting can be used to limit almost the entire signal in a way where nearly no dynamics remains. 

The Auto Fast function for the attack parameter makes sure that the mpressor works fast but without distortion, and fast release times of about 50 ms are responsible for the loudness. 

The ratio controller is set to 1:10 which makes the mpressor act like a kind of fast brickwall limiter. The drums now sound as if they had been recorded with a focus on the room micro- 

phones: few transients, lots of ambience and long sustaining toms and cymbals. 

Just play with this a little and find out that you can use the mpressor almost as a reverb processor. Do not be afraid of extreme sounds! You can always keep things under control by doing the following: 

Route the compressed signal to a separate buss and then mix it with the unprocessed original, and the result will be the typical parallel compression which is very popular for this kind of application. 

Remember that setting high amounts of makeup gain also adds harmonics which can contribute to a powerful sound. 

If you are processing a stereo track, just try deactivating the Link button. The result will be that the left and right channel will not be compressed exactly the same anymore, which can breath some new life into a heavily compressed track. 

settings - smashed drums 

15 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0016-00.png>)


## **settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0016-02.png>)


This is so cool! Because the mpressor also features negative ratios, you can perfectly use it to create weird and really way-out effects: 

Signals sound like if they were played backwards and become louder in their progression. Very loud input signals are reduced by large amounts which creates the reverse effect. 

The Auto Fast function for the attack parameter is used to perform the control process fast and without distortion. The position of the release controller determines the character the sound will get louder with. 

The Anti Log mode should also been given a try on top of this, as it will even increase the intensity of the reverse effect. 

A good balance of the threshold, release and ratio parameters is very important for this effect. A setting like this can easily produce an amount of gain reduction which exceeds the 20 dB mark frequently, therefore adequate settings of the gain controller have to be made for compensation. 

Again, the mpressor shows that it is not only a dynamics tool, but a powerful effects proces- 

sor at the same time. Try the suggested settings with some percussive material like drums or a slap bass guitar - did you expect it could sound this different? 

The mpressor plug-in is perfect for mangling samples! Just add some modulation, distortion and delays to taste ;-) 

settings - reverse sounds 

16 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0017-00.png>)


## **settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0017-02.png>)


A special task is to emphasize the transients at the beginning of a tone, chord and so on. The Gain Reduction Limiter is of special importance in this scenario. The chosen parameters result in a rather strong amount of compression with fast release times and negative ratios. 

Without the limiter, the signal would be compressed way too much; 10 to 15 dB of gain reduction would occur quite regularly in this case. But here the limiter reduces the maximum amount of gain reduction to 6 dB. 

If now the gain controller is set to 6 dB, the sig- 

nal will be boosted by 6 dB at its beginning and will then be held at 0 dB during its further progress. 

If for example an organ is processed this way, it will sound tighter as its transients receive an accentuation. And no matter if a single note or a full chord is played – the output level will always stay the same, so that the result does not sound like typical compression. 

This example shows that the mpressor can have a strong influence on the complete envelope of a signal. Take some time to find out how the 

specific parameters relate and you will be able to use the mpressor not only as a compressor, but as a creative envelope shaping tool, too! 

And once you got your envelope right, do not forget to check if the Niveau Filter can give an additional kick to the processed signal... 

settings - transient enhancer 

17 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0018-00.png>)


## **settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0018-02.png>)


By using very fast time constants, the mpressor can also be abused to create special distortion sounds. To do so, set the attack controller to its minimum of 0.01 ms and the release time also to its fastest value of 5.0 ms. 

Now the compressor becomes so fast that it compresses and twists almost every single wave form separately! The result sounds similar to a distortion unit, but without the usual drawback that the noise floor of the input signal is amplified. 

Remember that a high makeup gain setting will 

increase the amount of total harmonic distortion (THD) which can be used to push this effect even further. 

If this causes too much output gain for the following stages, just add a simple gain plugin from your host software directly after the mpressor to get it right. 

Now you can also use the Niveau Filter to shape the distortion sound you have just generated. 

If the filter is used in its low pass position, for example, everything will start to sound in a 

wonderful LoFi style. Especially bass and drums are ideal instruments for being processed in this way. 

These characteristic sounds can be the perfect twist for Ambient Music, Trip Hop and all styles of electronic music in general. 

settings - distorted compression 

18 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0019-00.png>)


## **settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0019-02.png>)


Delay and compressor in a loop – does that make any sense at all? Absolutely, because this combination is a truly rich source for lots of crazy sounds! 

To create them, assign an AUX buss (let’s say AUX 1) to the input of the mpressor. Send the output of the mpressor to the input of a following delay, which has to be set to 100 % wet, so that its output carries only the processed signal. 

The output of this delay is what you will listen to, but at the same time you send the output of the delay to AUX 1, too! 

Now send a signal from any source into AUX 1. If the gain controller of the compressor is set in a way that the delay sound becomes louder with every repetition, it will finally fall into a feedback loop which is kept steady by the compressor. 

If the Niveau Filter is used in addition to bend the frequency response, very noisy, pumping and breathing sounds that keep changing continuously will be the result. 

Very short delay times between 5 and 30 ms can even generate oscillating sounds that instantly remind of synthesizers. Turning the Niveau Fil- 

ter controllers during this process results in a shift of the frequency response with each repetition of the delay. 

If you are familiar with feedback loops, you will not have a hard time setting this up. If it feels difficult at first, though, never surrender: it takes some experiments at the beginning to get it right. 

Make sure to check the demo sounds both for the mpressor hardware and the plugin on our website in order to get an idea how this will sound and what you can do with it. 

settings - delay loops 

19 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0020-00.png>)


## **settings** 


![](<elysia mpressor Manual_assets/elysia_mpressor_Manual.pdf-0020-02.png>)


The mpressor also proves of great value when used as a high class mix buss compressor, especially when it comes to the more vehement genres like rock and electronic music. 

We even have some clients who are using the hardware for mastering applications. If you are aiming to do so, though, always keep in mind that the mpressor is a hard knee design and that applying lots of gain also increases THD. 

If you want to achieve gentle results, gentle and careful settings are the inevitable basis to get there. 

If you use the mpressor plugin straight on from the beginning of a mix, it is very likely that you will automatically adapt your mixing to the sound this produces. 

The proportions between the levels of the separate tracks will be attuned perfectly to the active compressor. This kind of mixing especially makes sense if the complete basic sound is supposed to sounds different from the ‘standards’ of other productions. 

If you want a complete song to sound very groovy and pumping, for example, just mix the 

drums louder as usual so that they dominate the compression process. All other instruments which are quieter in the mix now groove in conformity with the drums and become very vivid thereby. 

From here on, feel free to experiment with the mpressor plugin in any way that comes to your mind. There are lots of options and interesting sounds to be discovered. We wish you lots of fun finding them! 

settings - mix buss 

20 

# **MORe? elysia.com** 

