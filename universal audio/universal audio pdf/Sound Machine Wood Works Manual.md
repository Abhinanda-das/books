---
source: /Users/abhinanda/Documents/00_Works_Air/Конвертация/Авто/Sound Machine Wood Works Manual.pdf
converted_at: 2026-06-03T09:41:27Z
tool: pymupdf4llm
tool_version: 1.27.2.3
word_count: 1874
---

## **Sound Machine® Wood Works®** 

## **UAD Plug-In User Manual** 

## **Superior Acoustic Guitar Recording** 

Wood Works brings dramatic new versatility, quality and simplicity to recording and mixing acoustic guitars. Now you can truly have microphone quality sound when recording direct from an acoustic’s on-board pickup. So you can get all the advantages of going direct without having to limit your final sound quality or flexibility. You’re free to re-mic as you mix, so you can refine your sound, build complexity and drama, or radically re-think your production at any stage of the mix process — all without having to re-track. 

Use Wood Works on its own, or alongside physical mic’ing. No matter how you’ve recorded and mixed acoustic guitars before, Wood Works now gives you the freedom to do it better. 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0001-05.png>)


The Sound Machine Wood Works plug-in window 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC 

pg. 1 

## **How To Start Using Wood Works** 

The best way to first experience Wood Works is to record a quick track captured from the direct out of your acoustic guitar, without applying Wood Works as part of the recording process. Then play that track back in your DAW, adding Wood Works. As the track plays, spin the big voicing dial in Wood Works to find your most preferred sound, and don’t be afraid of trying Studio and Jumbo voicings even if your source guitar was a dreadnought. 

Each voicing comes up with the two virtual microphones set to give a good starting point. If you want to hear the neck or body mic alone, turn down the other mic’s knob. 

Notice the DEFAULTS/MANUAL switch below the voicing dial. When set to DEFAULTS, the NECK, BODY and associated PAN knobs will be moved to good starting values each time you change voicing. If you flip the switch to MANUAL, those knobs will be left alone as you move the voicing dial, making it easy to compare just neck mics, body mics, or maintain some other particular balance of the mics' levels and pans. 

As with real microphones, you’ll want to process the output from Wood Works through your favorite UAD-2 preamps, EQs, compressors, reverbs, channel strips or other plug-ins. (We did not “bake-in” any of this type of processing, leaving you the greatest freedom to make your own choices.) You’ll hear the signature sound of the preamps or other processing you use, just as you would if applied to microphone-sourced tracks. One nice signal chain that will fit within a single SHARC chip on any UAD-2/Apollo device @ 44.1KHz or 48KHz is Source Acoustic Guitar > Sound Machine Wood Works > Pultec EQP-1A Legacy EQ > Teletronix LA-2A Legacy Leveler > EMT140 Plate Reverb. If you need to run a Preamp plug-in before Wood Works (for instance, to have it operate in Unison mode with an Apollo), that works, too. 

We expect you'll also enjoy the sound of more than one instance of Wood Works at once, which is basically like using more virtual mics on your guitar. Multiple instances of Wood Works should be run in parallel, not in series, so you may want to put Wood Works instances on aux tracks, or make multiple copies of the guitar track and apply Wood Works to them separately. Try using different voicings in each instance for a richer soundscape. 

Once you get a sound you really like, if you want to monitor it while tracking, you'll get the best experience by using headphones (rather than speakers to 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC pg. 2 

monitor), and it's best if the headphones have good isolation. This helps avoid any weirdness you may experience in hearing the sound directly from your guitar to your ears, at the same time as the sound being routed through your computer and Wood Works. If you record with an Apollo and run Wood Works in Apollo’s Console application as you are tracking, Wood Works will operate in mono if placed on an insert for your Hi-Z input. You can run Wood Works in stereo in Console if you run it as an Aux effect. Of course, it's not necessary to monitor Wood Works as you record, since Wood Works lets you make all your acoustic guitar mic'ing choices as you mix. 

## **Compatibility with source pickups/electronics** 

Here's how to use Wood Works with 4 possible source types: 

- **Under-saddle piezo pickup:** This is the most common type of pickup, so if you don't know what you have, start by trying this setup. Run Wood Works in series routing on this source, entirely replacing the sound of the piezo with virtual microphone sound. If you want to run more than one instance of Wood Works, or want to have the piezo source available to run directly through other processing, or to mix in as another element of your sound, then you may want to bus the source track out to multiple tracks where Wood Works or other processing can be run. You'll want each instance of Wood Work to run parallel to others, rather than series, to avoid a "twice-baked" sound (same idea as running more than one amp model on the same source electric guitar audio). 

- **Microphones:** Wood Works is a great complement to actual microphones, giving you additional virtual microphones for instantly larger and more complex sound (like you'd get if using multiple microphones instead of one) and dramatic new freedom to "re-voice" your sound by blending in Wood Works voicings that are unlike the source guitar's original sound. To be able to use Wood Works, you'll need to capture a direct out from the mic'd up guitar at the same time as you are mic'ing it. Then apply Wood Works to this direct source as you mix. 

- **Other/hybrid pickups:** Some on-board electronics (such as Taylor Expression System 2) include additional resonance or microphone-like sound aspects beyond what standard piezos provide. For these sources, run Wood Works as you would to complement an actual microphone, on a parallel aux mixed in alongside the source sound. Adding Wood Works gives you an instantly larger and more complex sound (like you'd 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC pg. 3 

get if using multiple microphones instead of one), adds additional microphone qualities, and new freedom to "re-voice" your sound by blending in Wood Works voicings that are unlike the source guitar's original sound. If you're using Wood Works in Apollo’s Console application, you can put it on one of the Aux inserts to achieve this, and since Console's Aux inserts are stereo whereas its channel inserts are mono, this also means you get stereo goodness from Console. 

- **Magnetic pickups:** Treat as you would a piezo pickup. The signature sound of the magnetic pickup will be part of the resulting sound, so you won't get as close a "match" to microphones as a neutral piezo source would allow, but this is still a great sound that brings back the "wood" from your guitar, with more honk than a piezo source would provide. 

## **Hi-Z inputs** 

When recording acoustic guitars for processing via Wood Works, you should connect the direct out of the acoustic guitar’s on-board pickup/electronics to a Hi-Z/instrument input of your audio interface, and process that audio via Wood Works. If your audio interface does not have a Hi-Z/instrument input, you should connect your acoustic guitar to a preamp with Hi-Z/instrument input, then connect the line output of the preamp to a line input of your audio interface. Follow standard practice for setting recording input level. 

## **Nylon and steel/bronze strings** 

Wood Works operates equally well with nylon and steel/bronze string sources. 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC pg. 4 

## **Sound Machine Wood Works Controls** 

## **Voicing Dial** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0005-02.png>)


The dial selects from the available voicings, which provide resonances and other acoustic properties well-matched to Jumbo, Dreadnought and Studio (small body) guitars. Select the voicing that best matches the natural sound of the source acoustic guitar, or creatively re-voice the source acoustic guitar by choosing other settings. Changing voicing for different portions of a track allows the sound to evolve and transform to fit the emotional arc of a production, like swapping to a different guitar or a different set of microphones. Running multiple instances of Wood Works with varied voicings allows richer soundscapes to be built. 

## **Defaults Enable Switch** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0005-05.png>)


This toggle determines whether NECK, BODY and PAN controls will be set to default settings each time voicing is changed (DEFAULTS), or remain as previously set (MANUAL). Defaults have been chosen to give optimal starting settings for each voicing, and are particularly helpful when “browsing” voicings. 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC 

pg. 5 

## **Neck Knob** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0006-01.png>)


This knob sets the level of the virtual neck microphone, equivalent to a microphone placed to mic the guitar neck, near the 12th fret. This mic will tend to emphasize somewhat higher frequency resonance points than the body mic, as well as the high frequency content that comes directly off the vibrating strings. Turn the knob fully clockwise (minimum) to silence the microphone, and allow use of only the BODY microphone. 

## **Body Knob** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0006-04.png>)


This knob sets the level of the virtual body microphone, equivalent to a microphone placed to mic the guitar body, near the lower bout. This mic will tend to emphasize somewhat lower frequency resonance points than the neck mic, as well as the high frequency content that comes off the top surface of the guitar around the bridge. Turn the knob fully clockwise (minimum) to silence the microphone, and allow use of only the NECK microphone. 

## **Pan Knobs** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0006-07.png>)


Two pan knobs are provided, to independently control stereo placement for the neck and body virtual microphones. Double-click a knob or click the word PAN above it to re-set it to center position. These knobs are disabled when Wood Works is run with mono output. 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC pg. 6 

## **Input Knob** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0007-01.png>)


This knob provides input level adjustment from infinite attenuation @ minimum, to +0dB @ noon, to +12dB @ maximum. 

## **Output Knob** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0007-04.png>)


This knob provides input level adjustment from infinite attenuation @ minimum, to +0dB @ noon, to +12dB @ maximum. 

## **Output Level Meter** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0007-07.png>)


The output level meter shows output level for neck and body virtual microphones combined. 

## **Power Switch** 


![](<Sound Machine Wood Works Manual_assets/Sound_Machine_Wood_Works_Manual.pdf-0007-10.png>)


The power switch bypasses all plug-in processing when off. You can use this switch to compare the processed sound to that of the original signal. 

Sound Machine® Wood Works® UAD Plug-in User Manual revised January 14, 2015 © Sound Machine LLC 

pg. 7 

