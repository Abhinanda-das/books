---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/elysia alpha master Manual.pdf
converted_at: 2026-06-03T09:53:13Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 6005
---


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0001-00.png>)


# **alpha compressor** 

## **WeLcOMe! introduction** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0002-01.png>)


## **FIRST OF ALL...** 

...thank you very much for using the alpha compressor plugin! 

The ‘virtual’ alpha compressor is the software reincarnation of our famous mastering compressor. It gives you a painstaking emulation of the sound and features the hardware is known and popular for – programmed by the code experts from Brainworx. 

The alpha compressor has a unique set of features which makes it much more than just another compressor. It is a highly versatile toolbox, providing a comprehensive collection of everything needed to process dynamics the way you always wanted to: 

M/S and stereo processing, feedback and feed forward modes, audio and sidechain filters, parallel compression and additional limiters, just to name a few. 

But not only the final stage of mastering will profit big time from this ultimate dynamics processor. In fact, the compression section alone is such a useful tool that we have decided to include a dedicated mixing version with a reduced interface. You might want to use this on every single track of your DAW... 

manual version UAD 1.0 

introduction - welcome! 

2 

## **AbOUT M/S introduction** 

M/S technology is commonly known as a variant of stereo microphoning. This technique uses a microphone with cardioid pattern for the middle signal (M) and another one with bi-directional pattern with an offset of 90° for the side signal (S). The main advantage of this technology is its mono compatibility. FM radio stations use M/S technology for transmitting stereo signals exactly for this reason. 

To create M/S signals, the left and right channels of the stereo sum are added to generate the mid (M), whereas the side (S) is created by subtracting the right from the left channel: 

## **M = L+R S = L-R** 

To decode an M/S signal back into stereo again, M is added to S for the left channel and S is subtracted from M for the right channel: 

## **L = M+S R = M-S** 

The integration of an M/S encoder and decoder into a compressor generates new potentials that classic linked stereo compressors can hardly offer. One of the main advantages is the possibility to process the middle and side signals separately. This way you can make the center more compact without corrupting the original stereo spectrum, for example. 

Of course it is also possible to enhance the presence of the side signals in an already finished mix. The stereo width can be influenced fast and effectively, too, and it is also possible to compress specific parts of a mix that could not be selected in a stereo mix as precisely as it is possible in M/S mode. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0003-08.png>)


A practical example helps to understand the general idea. The ideal track for this would be the following: Important parts like voice, drums and bass have been placed in the middle whereas the remaining instruments have been mixed stereophonically. 

Switch the alpha compressor into M/S mode and leave the link function deactivated for now. Now the left side of the compressor controls the middle channel and the right side is responsible for the side channel. 

By using the Compressed switches, you can solo both channels and listen to them separately, enabling you to hear what is just going on in the particular channel. 

Now you can process the mono and side parts separately from each other. Depending on the mix, sometimes it is only the middle channel that needs compression whereas the side channel remains unprocessed. 

Other mixes have a lot of stereo information; in these cases both middle and side channels are processed, the settings of which can be completely different from each other. 

At the beginning, both gain controllers should be set at the same values, but that can change in the progress of optimization by all means. You can use different settings of the gain controllers in M/S mode for specific changes of the stereo width, for example. 

Of course the link function also works in M/S mode. In this case, signals in the M and S channels are reduced by the same amount so that the result of the compression is the same as if working in stereo mode. However, you are still able to adjust the level proportion between M and S with the gain controllers. 

introduction - about m/s 

3 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0004-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0004-02.png>)


**Threshold:** If the input level exceeds this value, the compression process will start. 

pressor takes to return back to unity gain after 6 dB of gain reduction. 

pressor part, thus it will not influence the behavior of the dynamics section. 

**Feed Forward:** switches the feed of the sidechain alternatively behind (feedback) or in front (feed forward) of the actual compressor section. 

**Attack:** the transient response of the compressor. It determines the time the alpha compressor needs to react to a peak. 

**Auto Fast:** a semi-automation. This function shortens the attack time automatically on fast and loud signal impulses. 

**Auto Fast:** the semi-automated regulation of the time constants is also available for the release controller. 

**Ratio:** the relation between the input level and the output level. The printed values double in feed forward mode. 

**eQ Gain:** the characteristic of the Niveau Filter. Between the mid and fully counterclockwise position, bass is boosted and treble is cut (vice versa in the other direction). 

**eQ Freq:** the center frequency of the Niveau Filter. Around this reference point, the bass is boosted and treble is cut or vice versa. 

**x10:** shifts the frequency range of the Niveau Filter by a factor of ten. 

**Sc Gain:** sets the integrated sidechain filter from low pass to high pass with lots of useful intermediate values. 

**On:** activates the sidechain filter. 

**Release:** the return phase of the compressor. It controls the period of time that the com- 

**On:** activates the Niveau Filter. In the signal path, this special EQ is placed after the com- 

**Sc Freq:** sets the center frequency of the integrated sidechain filter. 

controls - overview master version 

4 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0005-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0005-02.png>)


**Direct:** activates the direct and unprocessed signal taken from the input. 

**Mix:** If the Direct and Compressed buttons are pressed, this controller can blend between the unprocessed and compressed signals (parallel compression). 

**compressed:** activates the processed signal. 

**Gain:** compensates the gain reduction caused by the compression process. 

**Warm:** a switchable sound shaping option. Subtle, but nice. 

**Soft clip:** sets the threshold of the Soft Clip Limiter, which tames short and loud tran- 

sients and smoothens the signal peaks, providing additional headroom and loudness if needed. 

**On:** activates the Soft Clip Limiter. 

**M/S Mode:** activates Mid/Side processing. The left channel becomes the mid, the right becomes the side. If function is not active, the compressor will work in stereo mode. 

**Active:** sets the plugin from bypass to active status. 

**channel Link:** left and right or mid and side channel can be linked. In this case, the left set of controllers becomes the master for the right channel. 

**GR Meter:** displays the amount of gain reduction in dB. 

**Soft clip LeD:** indicates activity of the Soft Clip Limiter. 

**Version:** A click on the elysia logo will reveal the actual version of the plugin you have installed and the people behind the project. 

controls - overview master version 

5 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0006-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0006-02.png>)


**Active:** sets the plugin from bypass to active status. 

**GR Meter:** displays the amount of gain reduction in dB. 

**Threshold:** If the input level exceeds this value, the compression process will start. 

**Feed Forward:** switches the feed of the sidechain alternatively behind (feedback) or in front (feed forward) of the actual compressor section. 

**Attack:** the transient response of the compressor. It determines the time the alpha compressor needs to react to a peak. 

**Auto Fast:** a semi-automation. This function shortens the attack time automatically on fast and loud signal impulses. 

**Release:** the return phase of the compressor. It controls the period of time that the compressor takes to return back to unity gain. 

**Auto Fast:** the semi-automated regulation of the time constants is also available for the release controller. 

**Ratio:** the relation between the input level and the output level. The printed values double in feed forward mode. 

**Sc Gain:** sets the integrated sidechain filter from low pass to high pass with lots of useful 

intermediate values. 

**On:** activates the sidechain filter. 

**Sc Freq:** sets the center frequency of the integrated sidechain filter. 

**Warm:** a switchable sound shaping option. Subtle, but nice. 

**Mix:** blends between the unprocessed and compressed signals (parallel compression). 

**Link:** left and right channel can be processed linked or unlinked on a stereo track. 

**Gain:** compensates the gain reduction caused by the compression process. 

controls - overview mix version 

6 

## **THReSHOLD controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0007-01.png>)


The threshold determines the operating point of the compressor. If the input level exceeds the value set with this controller, the compression process will start. 

The settings of threshold and ratio should always be considered as a couple: If a high ratio is applied, the threshold will usually be in the lower range in order not to produce too much gain reduction. 

Accordingly, if lower ratio settings are chosen, the threshold will be turned more clockwise as a general rule. 

The complete control range covers 33 dB, offering the complete variety from sensitive processing up to the most extreme effect settings. 

## **FeeD MODe** 

This function makes it possible to switch the feed of the sidechain alternatively behind (feedback) or in front (feed forward) of the actual compressor section. 

It has an enormous effect on the character of the compressor: While processing in feedback mode is smooth and even, switching into feed forward mode will result in a clearly stronger and harder kind of compression. 

From the technical point of view, this function mainly influences the characteristic curve of the ratio value. In feedback mode it goes up to a moderate ratio of 1:2.5. The feed forward mode provides much higher values which also allow limiter settings and even negative ratios. 

The values of the attack controller also change noticeably in feed forward mode, as they are almost twice as high as the values shown on the scale. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0007-11.png>)


**----- Start of picture text -----**<br>
db<br>db<br>**----- End of picture text -----**<br>


Several threshold settings at a fixed ratio 

controls - threshold 

7 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0008-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0008-02.png>)


The attack time parameter is a very crucial factor for the control behavior of a compressor. Choosing the right setting is very important, but depending on the dynamic progress of the source material this can be a difficult task. 

If a very short time is chosen, the compressor will be able to catch the short peaks, but on the other hand the sustaining signal will also be processed, which might result in audible distortion. Longer attack settings reduce distortion significantly, but then the compressor is too slow for fast impulses. 

This is where the Auto Fast function comes into play. If you engage this mode, the attack time will be shortened automatically on fast and loud signal impulses. 

This way the compressor can be very fast, but only if it is really needed. The Auto Fast process happens on short and loud impulses only; in all other cases the controller has priority. 

The compressor reduces the signal quickly and prevents it from slipping through. Then the attack time directly and automatically returns to its original setting. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0008-08.png>)


**----- Start of picture text -----**<br>
db db<br>sec sec<br>Several attack settings Standard attack (dark) and Auto Fast (light)<br>**----- End of picture text -----**<br>


controls - attack 

8 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0009-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0009-02.png>)


The release parameter, on the other hand, has a strong influence on the character of the compression being obvious or unobtrusive to the ear. 

The release also often forces the user to accept compromises when searching for the right setting. If it is set it too fast, distortion will occur, if it is too slow, drive and loudness are lost. 

This is why the alpha compressor plugin offers a separate Auto Fast controller for the release parameter, too, helping the compressor to find the right setting semi-automatically . 

_Note:_ If you use very long release times, the effectiveness of this function will decrease. Very long attack times will also reduce the intensity of this circuit. 

This function can be a great help especially for applications with difficult dynamic structures, as it counteracts the danger of clippings caused by too short values. 

On top of this, it prevents the music from losing loudness and pressure caused by too slow release settings at the same time. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0009-09.png>)


**----- Start of picture text -----**<br>
db db<br>sec sec<br>Several release settings Standard release (dark) and Auto Fast (light)<br>**----- End of picture text -----**<br>


controls - release 

9 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0010-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0010-02.png>)


The alpha compressor works with a soft knee characteristic with rising gain reduction values at increasing ratios. The scale on the front panel is based on a measured gain reduction of 6 dB. 

ly obvious at higher settings. The lower curve shows the radical effects: An input level of 0 dB is reduced to -8 dB. An input level of +10 dB is reduced to -15 dB (!) 

Such extreme settings can only be achieved with a feed forward compressor, and they can result in very freaky effects. 

Strictly speaking, the ratio values become noticeably higher on stronger reductions: When there is 17 dB of reduction going on, the ‘real’ ratio value is 1:4.5 instead of the printed 1:2.5. 

Anyhow, the scale is optimized to the lower gain reduction settings as these are the ones most frequently used in mastering applications. 

In feed forward mode, the ratio characteristics differs strongly from the one in feedback mode. Although they remain quite comparable up to a value of 1:1.5, the differences become extreme- 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0010-09.png>)


**----- Start of picture text -----**<br>
db db<br>db db<br>Several ratio settings (feedback) Several ratio settings (feed forward)<br>**----- End of picture text -----**<br>


controls - ratio 

10 

## **NIVeAU FILTeR controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0011-01.png>)


This filter specialized in changing the overall sonic character of a track in fine nuances. It features two controllers per channel and is capable of flexibly producing convincing results in no time at all. 

Whenever a classic shelving filter would be too limited and a fully parametric filter would too much, the Niveau Filter is the efficient and elegant solution. 

Its main task is changing the proportions between high and low frequencies. It works like a pair of scales: Dependent on the gain setting around a selectable center frequency, the high frequencies are boosted up to +3 dB while the low frequencies are simultaneously attenuated by -5 dB maximum. 

_Note:_ Settings in the border areas of the covered frequency range produce ‘almost’ shelving filters, by the way. 

Turning the gain controller into the other direction will cut the treble and boost the bass instead. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0011-07.png>)


**----- Start of picture text -----**<br>
db db<br>Hz Hz<br>EQ gain low EQ gain high<br>**----- End of picture text -----**<br>


controls - niveau filter 

11 

## **SIDecHAIN FILTeR controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0012-01.png>)


The sidechain filter allows frequency-dependent shaping of the compression process by giving specific frequency areas a stronger or weaker influence on the detection circuit. 

In low pass mode, the filter should always be set to the highest frequency you just about want the compressor to react to. 

In high pass mode, however, the controller should be set to the lowest frequency you just about want the compressor _not_ to react to. 

If the SC gain controller is set to HP (High Pass), the filter will act like a 6 dB high pass and the reaction of the compressor on bass frequencies decreases. The setting LP (Low Pass) turns the filter into a 6 dB low pass and the compressor primarily reacts on low frequencies. 

The combination of the sidechain filters, M/S matrix and different attack settings enables you to make very selective changes and – depending on the source material – even allows to process single instruments or voices in finished mixes. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0012-07.png>)


**----- Start of picture text -----**<br>
db db<br>Hz Hz<br>Sidechain filter low pass Sidechain filter high pass<br>**----- End of picture text -----**<br>


controls - sidechain filter 

12 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0013-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0013-02.png>)


Parallel compression, also known as ‘New York’ compression, is a technique based on mixing a dry signal with a heavily compressed identical signal. It is thought to maintain the subtleties of a performance while stabilizing the dynamics. 

The mix controller of the alpha compressor makes it possible to cross-fade between the unprocessed and the compressed and filtered signals. This allows parallel compression right in the box and supersedes additional routings in favor of a better usability. 

Now you can use even extreme compression settings without killing a track by winning the loudness war. By mixing just a part of the compressed signal to the original, the major portion of the initial dynamic structure remains intact. 

## **SIGNAL MATRIX** 

Let’s have a look at the control logic of this interesting feature: If only the Compressed button is pushed, you will hear the compressed signal only. Otherwise, if only the Direct button is pushed, only the unprocessed signal routed from before the compressor section will be heard. If both buttons are activated, the mix controller will become active, and if none of the buttons is pushed, the channel will be muted. 

In practice this lets you switch between unprocessed, compressed or mixed signals very fast without having to change the position of the mix controller. The left and right channels (stereo mode) or the middle and side channels respectively (M/S mode) can be listened to separately – again you have the choice between the 

original, the compressed or the mixed signal. To mute the other channel, just deactivate its associated Direct and Compressed buttons. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0013-10.png>)


**----- Start of picture text -----**<br>
db<br>db<br>Several mix settings<br>**----- End of picture text -----**<br>


controls - mix 

13 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0014-00.png>)


## **controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0014-02.png>)


The gain controller is responsible for compensating the reduction of overall gain which is caused by the compression process, therefore it is often called ‘makeup gain’ as well. 

In the M/S mode of the alpha compressor you can use the gain controllers to make changes to the stereo spectrum of your mixes (e.g. more focused mids or wider stereo image) as well. 

In some cases you might want to add some gain when using the Niveau Filter in the extreme position of its EQ Gain controller, too. 

In the signal path, the gain stage is placed after the compressor section and the audio filter, but before the mix controller, transformer option and the Soft Clip Limiter. 

## **TRANSFORMeR** 

Each channel of the hardware alpha compressor features an additional transformer that can be switched into the signal chain after the mix stage. These are classic output transformers, but they are not used for balancing and galvanic isolation, but as an additional means of sound shaping. 

We have decided to do this a little bit different with the software version. Here you get something similar to the Warm function known from the museq: a slew rate limiter which alters the frequency spectrum, harmonics and transient response. 

Because of the mastering approach of the alpha compressor, this feature is much more of a sub- 

tle audio shaping feature than a glaring sound effect, but it’s certainly nice to add a little bit of color to a signal which might otherwise seem to be too clean. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0014-12.png>)


**----- Start of picture text -----**<br>
V<br>sec<br>**----- End of picture text -----**<br>


Effect of the slew rate limiter on a sine wave 

controls - gain 

14 

## **SOFT cLIP LIMITeR controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0015-01.png>)


Even the fastest compressor cannot always catch the all impulses and peaks. Although its time parameters might be fast enough for this job from a technical point of view, the required settings and their effects would not correspond to the original intention of using a compressor in the first place. 

The additional Soft Clip Limiter of the alpha compressor plugin is specialized in catching short and transient-like signals reliably. The technical principle is different from a classic ‘brickwall’ design which completely forbids further level increases beyond a certain threshold. 

Instead, it is working similar to an analog tape machine driving loud impulses into saturation, acting like a ‘natural’ limiter. Just as with tape, 

the characteristic saturation curve of the Soft Clip Limiter results in rounding peaks instead of cutting them off. 

It comes in very handy especially when the source material contains variable peak values. You will benefit from increased headroom and loudness, but your source material will stay musical because it will not be chopped by the limiter. 

The Soft Clip modules are placed directly in front of the outputs of the plugin. Their thresholds are not influenced by the mix and gain controllers. This is also the case in M/S mode, because the limiters are located after the M/S decoder, and therefore they are always assigned to the left and right stereo channels. 

The Soft Clip LEDs located on top of the gain reduction meters should only light up shortly from time to time as noticeable distortion will appear if you drive this circuit too hard. 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0015-09.png>)


**----- Start of picture text -----**<br>
db<br>db<br>**----- End of picture text -----**<br>


Several Soft Clip limiter settings 

controls - soft clip limiter 

15 

## **M/S | AcTIVe | LINK controls** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0016-01.png>)


## **M/S** 

The alpha compressor works in M/S mode when this button is pressed. The left side of the control panel then processes the mid signal and the right side processes the side signal. When the M/S button is not active, the plugin works as a standard stereo compressor. 

## **AcTIVe** 

There is no big secret behind this button: It switches the alpha compressor into the signal path (blue control light on) or bypasses the plugin (light off). 

By the way: On a hardware alpha compressor, the gain reduction meter stays active even if the unit is in bypass mode. The software version does not do this because of technical reasons. 

## **LINK** 

In link mode, the alpha compressor uses the information of both the left and the right channel to generate one combined ‘virtual control voltage’ which is then applied to both channels. This works both in stereo and in M/S mode. 

_Note:_ The ‘alpha master’ version with the fullfledged front panel will only appear on stereo tracks, the ‘alpha mix’ version is available on both mono and stereo tracks. 

In _linked stereo mode_ , all the parameters of the left channel are transferred to the controllers of the right channel (from right to left, too). 

In _linked M/S mode_ , however, the Niveau Filter, mix stage and gain controller and the Warm 

mode option remain unlinked. This gives you the possibility to make changes to the stereo image. 

In _unlinked stereo mode_ , imagine the compressor plugin as a dual mono compressor with two fully independent sets of controllers. 

In _unlinked M/S mode_ , the left side of the control panel processes the mid signal and the right side processes the side signal. All controllers can be set fully independent from each other. 

controls - m/s | active | link 

16 

## **STeReO LINKeD settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0017-01.png>)


**----- Start of picture text -----**<br>
* *<br>**----- End of picture text -----**<br>


This setting is especially useful for tracks in which the instruments are not placed straight in the middle of the stereo spectrum – when a recording has been made by the use of classic stereo miking like in Jazz, for example. 

In order to come up to such styles of music, one should make sure to create an unobtrusive and smooth kind of compression. This can be achieved by setting a long attack time and a ratio value in the lower control range, at which only a very few dB of gain reduction are required. 

Moreover, you can kick in the audio filters to make additional sonic corrections. 

Of course the linked stereo mode can also be used for many other styles of music, but in quite some cases you will be able to achieve even better results in M/S mode. 

***** You will need to adapt _all_ suggested settings to your actual source material. This is especially important for the threshold and ratio controls! 

If necessary, you can use the mix controllers to apply the effect of the compressor in even finer doses (both direct and compressed buttons have to be activated for this). 

settings - stereo linked 

17 

## **M/S LINKeD settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0018-01.png>)


The function of the compressor in linked M/S mode is quite similar to its function in linked stereo mode, and the resulting gain reduction in the middle and the side channel is exactly the same. 

An attack time of 30-40 ms ensures that transients from percussion instruments are hardly compressed, while the release time of 250 ms lets the compressor decrease its gain reduction fast enough. Variations of the release time are especially effective in controlling the amount of loudness. 

rameters. A ratio around 1:1.7 has often proved to be a good start. 

But what is the essential advantage of the linked M/S mode compared to the linked stereo mode? The levels of M and S can be set differently, which makes it very easy to perform changes of the stereo width (Mix too narrow? More gain to the side channel. Not enough punch? Add gain to the middle). 

Here, activating the Auto Fast function should be preferred to setting a very fast release time. The generated gain reduction is primarily affected by matching the threshold and ratio pa- 

settings - m/s linked 

18 

## **M/S UNLINKeD settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0019-01.png>)


The true strengths of an M/S compressor will not be revealed until it is switched into unlinked M/S mode. Depending on the mix and the style of music, the dynamics and loudness in the middle and side channel can be completely different from each other. 

Take a heavily pumping bass drum right in the middle and 100 % stable strings in the sides, for example – just try this with any other compressor ;-) Thus it can make perfect sense to set strongly differing values of threshold, attack, release and ratio for the middle and the sides. 

the other channel for this. Using the audio filters, which can also be set completely different from each other now, can help to additionally enhance the tonal balance of a mix. 

Once you have discovered the potentials of the M/S mode, lots of formerly hard to handle mixes can be controlled much better, resulting in audibly better masters. 

In order to achieve a better evaluation of the results, it is advisable to listen to the processed channel solo for a start. Please remember to deactivate the Direct and Compressed buttons of 

settings - m/s unlinked 

19 

## **UPWARD LeVeLING settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0020-01.png>)


Upward Leveling – this describes the possibility of making only the low signal parts louder and leave the louder changes in dynamics unprocessed. 

The settings shown above are suitable for classical music, for example, where ‚typical‘ compression is objectionable. The compressor works in linked stereo mode, the attack time is set at maximum and the release time is at 150 ms. 

and the make up gain is about 6 dB. The result of these settings: Quieter passages which do not produce any gain reduction will be boosted by 6 dB, whereas loud signals will be limited by the compressor. 

Now the special trick is to set the mix controller to 50 %. By adding the original signal, the initial dynamics will be saved, and the result is that only the quieter signals will be made louder. 

Under these conditions the alpha compressor will function as a leveler. In feed forward mode the attack time is twice as long compared to feedback mode and therefore amounts to 300 ms. 

The ratio characteristic corresponds to a limiter, 

settings - upward leveling 

20 

## **M/S LeVeLING settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0021-01.png>)


As with Upward Leveling, long attack times are the secret of M/S Leveling. The compressor primarily reacts to the overall signal energy and not so much to single rhythmic accents. 

If this principle is now used on the mid and the side channel separately, a stereo mix will become more compact in an unobtrusive way and everything will sound a little bit more vivid. This method is especially interesting for enhancing rock and pop tracks in a subtle but effective way. 

Here the feed forward mode is active again. The ratio is set at about 1:1.5 and the gain controller at about 3 dB. The threshold is adapted to a value that results in approx. 3-4 dB  of gain reduction. 

settings - m/s leveling 

21 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0022-00.png>)


## **settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0022-02.png>)


Sometimes it would be great being able to just emphasize the rhythmical elements of a mix in order to bring out the groove with the purpose of giving a track the right kick. 

This example shows how the alpha compressor can help you to cope with this challenge. The bass drum is used as a trigger for the compressor; therefore the sidechain filter is of special importance in this application. 

Depending on the song and the style of music, the gain reduction can get a little bit higher from time to time; usually 5-6 dB should do very good. The linked M/S mode makes sense in this application because the influence of the bass drum on the control process is enhanced, and so is the resulting sonic effect, too. 

It is set to low pass, with a center frequency of approx. 70 Hz. Now the threshold and ratio controllers are used to set the intensity of the gain reduction, and the groove will be controlled by the release parameter, which you can easily adapt to the speed of the track. 

settings - groove compression 

22 

## **VOcALS DOWN settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0023-01.png>)


If you have a track in which the vocals are too loud, the compressor can be set in a way that it mainly reacts to the lead vocals placed in the middle, resulting in a better integration into the mix. 

For this purpose, switch into the unlinked M/S mode. Again, the specialty here lies in combining the sidechain filters with suitable attack parameters. The SC filter of the middle channel is set to high pass at a center frequency of about 270 Hz with the effect that the compressor hardly reacts to bass impulses anymore. 

so that the compressor can return to unity gain fast enough. 

In the side band, both the controller for the threshold and the ratio parameters should be turned hard left if you do not wish any further side channel processing. An equal setting of the middle and side channel gain controllers is also advised. 

The attack time lies between 70-100 ms. Thus, transient-like signals like a snare drum only have a minor influence on the compression process. The release time is set at about 100 ms 

settings - vocals down 

23 

## **DeeSSING settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0024-01.png>)


A variation of the Vocals Down scenario is DeEssing which is used for reducing unwanted ess and hiss sounds. 

The sidechain filter of the middle channel is set to approx. 2 kHz, which is even higher than in the previous application, thus only the high frequencies can influence the detection circuit. 

At about 100 ms, the attack time is also quite long and the release time is set to a fast value of 50 ms.  Threshold and ratio are used to set the trigger point and the intensity of processing. 

Again, this application is run in unlinked M/S mode to assure that only the middle channel is processed (but of course you can additionally process the sides separately if needed). 

settings - deessing 

24 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0025-00.png>)


## **settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0025-02.png>)


If it should (or must) become really loud, you can also use the alpha compressor to drive a track against the wall – but without the negative effects this usually brings with it. 

just created ‘flat‘ signal is mixed to the original signal in moderate rates, it is possible to achieve an increase in loudness while still saving a great part of the initial dynamics. 

For this procedure it is preferable to work in classic linked stereo mode. The time parameters are set very fast here; especially the attack time at only 10 ųS. The release parameter is set at 150 ms, while the corresponding Auto Fast function is activated and the ratio is at its maximum. 

With these settings, everything will be compressed very intensely – even fast transients and impulses, resulting in an intense limitation of the output peak levels. 

Now the mix controller comes into play: If the 

settings - parallel compression 

25 

## **STeReO eNHANceR settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0026-01.png>)


Even when there is nothing to compress from time to time, your productions can still benefit from the alpha compressor, as the combination of the M/S matrix and the audio filters makes a very nice tool for influencing the stereo spectrum. 

course simply increasing the level in the side channel can be used to achieve a (broadband) change in the stereo spectrum, too, but the variant shown here offers much more differentiated options because it is frequency-dependent. 

For this purpose the compressor is switched into M/S mode and the audio filter of the side channel adds 1.0-1.5 dB at a center frequency of approx. 1 kHz. The gain controllers of both channels are at 0 dB. These settings cause a boost of all frequencies above 1 kHz in the side channel, which intensifies the spatial perception as the room reflections become more distinct. 

The lower frequencies, however, are not of that great importance for spatial perception. Of 

settings - stereo enhancer 

26 

## **LOFI cOMPReSSION settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0027-01.png>)


Can the alpha compressor also sound really bad? Of course not, but sometimes it can be, well … different. 

In this LoFi compression scenario, the use of the audio filters is the crucial point. By reducing the high frequencies from 4 kHz on, everything sounds a little darker, while the bottom end experiences a great degree of additional punch at the same time. 

The chosen time parameters result in loud and twangy compression effects. The high ratio settings create a great amount of compression, so that gain reduction values of 8-12 dB are absolutely normal. In this application, the mix controllers give you the option to blend this extreme sound with the original at will. 

settings - lofi compression 

27 

## **eXTReMe SeTTINGS settings** 


![](<elysia alpha master Manual_assets/elysia_alpha_master_Manual.pdf-0028-01.png>)


Even though the main focus of the alpha compressor lies on mastering applications, you can also use it to find interesting and sometimes extreme settings for single channels or subgroups. 

Here is just one of many examples. It is especially suitable for processing drum tracks effectively: The time parameters with the additionally activated Auto Fast functions are very fast. The high ratio in feed forward mode causes an extreme characteristic curve so that loud signals will be reduced significantly. 

This can create very high gain reduction values of 20 dB and more.  The spatial elements come into the foreground more articulately – it sounds as if the microphones had been placed a little bit further away during recording. 

settings - extreme settings 

28 

# **MORe? elysia.com** 

