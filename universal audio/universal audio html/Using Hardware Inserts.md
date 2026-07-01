---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/42265531595668-Using-Hardware-Inserts.html'
converted_at: 2026-05-31T13:44:58Z
tool: htmlq+pandoc
title: 'Using Hardware Inserts'
word_count: 953
---

# Using Hardware Inserts


## In this article

- [About Hardware Inserts](#h_01K7NXWKH5QX75011PKE0F2KTN)
- [Using Hardware Inserts](#h_01K7Q1D8RYB6GGNCCDHB93FRHJ)

------------------------------------------------------------------------

# About Hardware Inserts

The LUNA Pro bundle includes a license for the Hardware Insert plug-in. The Hardware Insert plug-in allows you to incorporate your outboard gear into your LUNA workflow as a simple-to-operate plug-in, while maintaining your session audio in sync (latency-compensated).

**Note:** Because a hardware insert requires an assignable output, the following Universal Audio interfaces cannot be used for hardware inserts:

- Apollo Solo
- Volt 1
- Volt 176
- Volt 2
- Volt 276

See [Assigning a hardware insert on Apollo Twin devices](#h_01KBNJXRDXV3N7RYHTR7GV6SGG) for additional Apollo Twin configuration.

## How hardware inserts work

The Hardware Insert plug-in routes audio from your track through its Output to your external gear and returns the processed audio through its Input. The Hardware Insert includes the following controls:

- **Output:** Assign to a physical output on your audio interface. Connect this output to the input of your external hardware. Set the output level to the optimum level for your hardware. This is also known as a Send.
- **Input:** Assign to a physical input on your audio interface. Connect this input to the output of your external hardware. This is also known as a Return. 
- **Levels:** Set the output level to adjust the level to your effect. Set the input level to provide any necessary makeup gain or to trim the signal before it returns to your interface.
- **Calc:** Click to calculate the latency incurred by the roundtrip through your interface and external hardware. The plug-in sends an audio signal and automatically calculates your hardware's latency. Note that the calculation often correctly returns <span math="0">0,</span> because the latency reported by your audio interface and the buffer are already automatically compensated by LUNA. If necessary, you can specify additional samples of compensation by dragging or by double-clicking to type a specific number.
- **Mix:** Adjust to blend the hardware signal with the dry signal.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 100%;">
![hw-insert-callouts.png](Using%20Hardware%20Inserts_assets/685093c4a2d6b1bdfd8cbdb91f9757d2535477a3.png)
</figure>

------------------------------------------------------------------------

# Using Hardware Inserts

Hardware inserts route audio to and from external hardware and insert the processed audio into LUNA tracks. Hardware inserts require specific connections and configuration. 

## Connect your hardware

You can use any available input and output pair, provided the signal levels are appropriate for your external gear. Mono or stereo Hardware Inserts can be used. For stereo hardware, ensure you cable the plug-in input and output to an addressable stereo pair on your interface.

1.  Connect the input of your hardware to an available output on your audio interface. 
2.  Connect the output of your hardware to an available input on your audio interface. 
3.  Power on your hardware, and enable processing. \
    Note that for the most accurate automatic latency calculation, effects that create long tails (such as delays and reverbs) may need to be reduced in level or bypassed temporarily.

## Assign a hardware insert in LUNA

1.  In LUNA, click on an insert slot in the Mixer view or on the Focus channel.
2.  Expand the Hardware Inserts folder, and choose New Hardware Insert, or a preset if available. 
3.  From the Output menu, select the select the interface output you used to send audio to the hardware.
4.  From the Input menu, select the interface input you used to receive audio from the hardware. 
5.  With audio playing on the track, adjust the Input and Output levels using the corresponding knobs, or by double-clicking the values to type a specific number. 
6.  To calculate latency, click Calc. LUNA sends a signal to the hardware and automatically adjusts the latency compensation based on the returned signal.
7.  Adjust the Mix amount with the knob, or double-click the value to type a specific percentage. 

## Save and use hardware insert presets

When you have configured your hardware insert, you can save it as a preset, using the plug-in's preset browser. Hardware insert presets appear in the Hardware Inserts folder in LUNA, which you can see when you click an insert in the LUNA mixer or on a Focus channel. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![hardware-inserts-folder.png](Using%20Hardware%20Inserts_assets/b753f0e70be61be0ab2c279f8c006df0dfb3d3ee.png)
</figure>

A Hardware Insert preset saves the hardware input and output settings, and the plug-in control settings. Make sure that the correct connections are still made when you load a preset. 

## Mix down, bounce, and freeze with hardware inserts

Because hardware inserts must be processed in real time, all mixdowns, bounces, and track freezes occur in real time. The bounce, mixdown, and freeze dialogs include a message to explain this. 

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 50%;">
![bounce-hardware-insert.png](Using%20Hardware%20Inserts_assets/2f0e9830da0fe9d5b6652412266528928acc6524.png)
</figure>

 

## Assigning a hardware insert on Apollo Twin devices

By default, Apollo Twin outputs 3-4 are assigned to the ALT monitor outputs. To use Apollo Twin analog outputs 3 and 4 as hardware inserts, you must reassign hardware outputs 3-4 to channels 7-8 in the I/O Matrix.

1.  In LUNA, click the three dots at the upper left of the window to show the LUNA sidebar, then click Settings. You can also navigate to Settings in UAD Console.

2.  Choose the I/O Matrix tab. Note that in the Outputs area, channel 7-8 are either not assigned, or assigned to virtual outputs.

    <figure>
    <p>![hw-insert-twin-7-8.png](Using%20Hardware%20Inserts_assets/14e93b83bf2d04f3dfbeae2c43d7f4bbcffe21fd.png)</p>
    </figure>

3.  Click on output channel 7. The routing popover appears.

4.  Choose Monitor, then Line 3. Hardware output 3 is now assignable.

    <figure>
    <p>![hw-insert-io-7.png](Using%20Hardware%20Inserts_assets/63591e23715e487ebda68e420161996e8e74c05f.png)</p>
    </figure>

5.  Repeat this for output channel 8, assigned to Monitor and Line 4.

After the channels are configured, hardware inputs 3-4 appear assigned to channels 7-8 in the i/O Matrix.

<figure>
<p>![assign-line-3-4-twin-hw-inserts.png](Using%20Hardware%20Inserts_assets/85c9aa03bf0f35b0b44d1740d6443abe455324e8.png)</p>
</figure>

You can now choose Line 3 and Line 4 as outputs in a LUNA hardware insert.

<figure>
<p>![hw-insert-line-3-4-selected-twin.png](Using%20Hardware%20Inserts_assets/32117956d359508d660058ae1b80e147689f3c72.png)</p>
</figure>

##  

<span class="wysiwyg-font-size-small">251230</span>

 

