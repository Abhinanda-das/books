---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/4838035578516-Sidechaining-in-LUNA.html'
converted_at: 2026-05-31T13:45:01Z
tool: htmlq+pandoc
title: 'Sidechaining in LUNA'
word_count: 1455
---

# Sidechaining in LUNA


<div collection="contentId-199393353" context-id="199393353" file-mime-type="image/png" file-name="create-plugin-icon.png" file-size="176338" data-height="230" data-id="a95c18b2-9adc-4728-be48-78cc000d6955" node-type="media" data-type="file" data-width="393" title="Attachment">

## In this article

- <a href="#h_01FYA93PQH74DSBK15AS6AFX5P" target="_self">Sidechain Source and Destination</a>
- <a href="#h_01FYA93XSN2YCKSJ0YNF3VQ987" target="_self">Configuring a Sidechain with API Vision Console Emulation</a>
- <a href="#h_01FYA942Z928KJ9TQH4M65H14A" target="_self">Configuring a Sidechain with a UAD Plug-In </a>
- <a href="#h_01FYA942Z928KJ9TQH4M65H14A" target="_self">Configuring a Sidechain with a Non-UAD Plug-In </a>
- <a href="#h_01FYA94ACVSR8K9TBAA7GFX5P9" target="_self">Configuring Sidechain Options</a>
- <a href="#h_01FYA94H2KT45JNH0NSN3KPHYX" target="_self">Removing a Sidechain</a>
- <a href="#h_01FYA94QEJXF9CSXK01GMFH5VR" target="_self">Sidechain Hover Options</a>

Sidechaining allows you to use the audio output from one track to key, or trigger, an effect such as a compressor on another track. Sidechaining is generally used with compression, but you can use any processor (typically a dynamically-triggered processor) that supports sidechaining. For example, a gate can be triggered to silence a tom channel when the snare is hit, or an expander can be triggered to bring up room tone on a snare hit. 

------------------------------------------------------------------------

# Sidechain Source and Destination

Sidechaining uses a source and destination: a source track (the audio source that will trigger the processor), and a destination (the audio processor on a track that will be triggered by the source audio). 

- **Sidechain source:** Any audio, instrument, or bus track, with no requirement for plug-ins or extensions. The sidechain source is post-plug-in, post-extension, and pre-fader.

- **Sidechain destination:** One sidechain-capable plug-in or extension on any audio, instrument, or bus track. It is important to remember that the sidechain source is a track, but the sidechain destination is a plug-in or extension on a track.

Each audio, instrument, and bus track in LUNA has a single sidechain input that can route sidechain audio to a single processor on the track. The sidechain can be configured in the Utility row for the destination track, or in the plug-in or extension (when using API Vision Console Extensions). Note that the sidechain source track is not heard through the destination track — it is only used to trigger the plug-in or extension to which it is routed. 

## Before you configure a sidechain

- A sidechain source track can be any audio track, instrument track, or bus track. The source track must pass audio, or it will not have any functionality.
- The sidechain-capable plug-in or extension on your destination track (for example, an API Vision Console Emulation extension) must be instantiated.

------------------------------------------------------------------------

# Configuring a Sidechain with API Vision Console Emulation

You can configure an API Vision Console Emulation LUNA Extension as a sidechain destination from within the extension.

#### Configuring an API Vision Console Emulation extension as a sidechain

1.  Make sure the Console row is showing in the LUNA mixer.\
    ![avc-console-row-show-hide.png](Sidechaining%20in%20LUNA_assets/acd2d1a8fac51f369ac650cf76e922e39220a161.png)

     

2.  Click on the Console row on a track and choose API Vision or API 2500.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="avc-add-console.png" file-size="54415" data-height="126" data-id="ffe2e84c-b57f-4267-b827-cfa879c1f46b" node-type="media" data-type="file" data-width="287" title="Attachment">

    ![avc-add-console.png](Sidechaining%20in%20LUNA_assets/ea415f4e16c8f37e722bd1e0e35f2db2141ce43e.png)

    </div>

    </div>

    <div layout="center" node-type="mediaSingle" data-width="">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="avc-assign-bus-main.png" file-size="64406" data-height="174" data-id="9a4f2131-f52d-4147-ab5e-e14bc63ec796" node-type="media" data-type="file" data-width="291" title="Attachment">

    </div>

    </div>

3.  The API Vision Console Extension browser opens. If you are using API Vision channel strip, enable the module you want to use as the sidechain destination (for example, the compressor). On API 2500, you do not need to enable a module, as all processors are enabled.

4.  At the top of the extension browser under Sidechain, click Assign.

    <div layout="center" node-type="mediaSingle" data-width="63">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-assign-avc.png" file-size="360213" data-height="603" data-id="7f411004-729a-4395-ad58-eec29d3ebce9" node-type="media" data-type="file" data-width="578" title="Attachment">

    ![sidechain-assign-avc.png](Sidechaining%20in%20LUNA_assets/ebc90d36c5198d62805fea46e4f1355e5a585692.png)

    </div>

    </div>

     

5.  From the Sources list, click the source track.

    ![sidechain-source-select-avc.png](Sidechaining%20in%20LUNA_assets/d288b27456e3f6fbf135e03abf5640d37670eef0.png)

The sidechain is configured with the source and destination you selected.

<div layout="align-start" node-type="mediaSingle" data-width="41">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-configured-no-callouts-extension.png" file-size="194826" data-height="397" data-id="e894067f-d4f3-4453-9866-1306888204d3" node-type="media" data-type="file" data-width="258" title="Attachment">

![sidechain-configured-no-callouts-extension.png](Sidechaining%20in%20LUNA_assets/e5c5c6c035d141e1d56cd9e796a57a07d0682672.png)

</div>

</div>

------------------------------------------------------------------------

# Configuring a Sidechain with a UAD Plug-In 

You can configure a sidechain-capable UAD plug-in from within the plug-in. 

#### Configuring a UAD plug-in as a sidechain destination

1.  Instantiate a sidechain-capable plug-in on a track. 

    <div layout="center" node-type="mediaSingle" data-width="55">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-assign-plugin.png" file-size="1695808" data-height="691" data-id="d0c7c935-0654-4b4c-b8e9-ab310aadfb83" node-type="media" data-type="file" data-width="577" title="Attachment">

    ![sidechain-uad-assign-plugin.png](Sidechaining%20in%20LUNA_assets/779b1352dd923a16e7983375ecbd4cea0fd71140.png)

    </div>

    </div>

     

2.  At the top of the plug-in, click the Sidechain:Assign or SC button.

    <div layout="center" node-type="mediaSingle" data-width="55">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-plugin-sc-button.png" file-size="1481574" data-height="633" data-id="4f6cf5a2-1c65-4991-bf9b-cc52fd027157" node-type="media" data-type="file" data-width="453" title="Attachment">

    ![sidechain-uad-plugin-assign-button.png](Sidechaining%20in%20LUNA_assets/ab440f4e51b3a6549e3dead87f3ef1732c41db0c.png)

    </div>

    </div>

     

3.  From the Sources list, click the source track.

    <div layout="center" node-type="mediaSingle" data-width="63">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-source-select-plugin.png" file-size="176264" data-height="541" data-id="6a36527a-3914-4377-baf7-7387dd2fcbf4" node-type="media" data-type="file" data-width="559" title="Attachment">

    ![sidechain-uad-source-select-plugin.png](Sidechaining%20in%20LUNA_assets/31371b7b1bc87cd329df09d8dbdc46f94e46aefb.png)

    </div>

    </div>

The sidechain is configured with the source and destination you selected. Configure the plug-in settings to taste.

<div layout="align-start" node-type="mediaSingle" data-width="33">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-configured-no-callouts-plugin.png" file-size="117365" data-height="405" data-id="807acb9b-1b64-4a1e-9977-c0e5b58198fe" node-type="media" data-type="file" data-width="256" title="Attachment">

![sidechain-uad-source-assigned.png](Sidechaining%20in%20LUNA_assets/75b7d803b2de83b493fa2760808e9ea108f20b37.png)

</div>

</div>

 

------------------------------------------------------------------------

# Configuring a Sidechain with Non-UAD Plug-In 

You can configure sidechain-capable Audio Units or VST3 plug-ins from within the plug-ins. 

## Configuring a plug-in as a sidechain destination

1.  Instantiate a sidechain-capable plug-in on a track. 

    <div layout="center" node-type="mediaSingle" data-width="55">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-assign-plugin.png" file-size="1695808" data-height="691" data-id="d0c7c935-0654-4b4c-b8e9-ab310aadfb83" node-type="media" data-type="file" data-width="577" title="Attachment">

    ![sidechain-assign-plugin.png](Sidechaining%20in%20LUNA_assets/d227c0314e97dedc6081fbc94e1dd1f03df6e03a.png)

    </div>

    </div>

     

2.  At the top of the plug-in, click the Sidechain Enable, Sidechain, or SC button.

    <div layout="center" node-type="mediaSingle" data-width="55">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-plugin-sc-button.png" file-size="1481574" data-height="633" data-id="4f6cf5a2-1c65-4991-bf9b-cc52fd027157" node-type="media" data-type="file" data-width="453" title="Attachment">

    ![sidechain-plugin-sc-button.png](Sidechaining%20in%20LUNA_assets/4a4cff8b201d0185dc5657f8ca557389f1051181.png)

    </div>

    </div>

3.  From the Sources list, click the source track.

    <div layout="center" node-type="mediaSingle" data-width="63">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-source-select-plugin.png" file-size="176264" data-height="541" data-id="6a36527a-3914-4377-baf7-7387dd2fcbf4" node-type="media" data-type="file" data-width="559" title="Attachment">

    ![sidechain-source-select-plugin.png](Sidechaining%20in%20LUNA_assets/7e9126b592aef785f223bc16ea234a93ea5349ae.png)

    </div>

    </div>

The sidechain is configured with the source and destination you selected. 

<div layout="align-start" node-type="mediaSingle" data-width="33">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-configured-no-callouts-plugin.png" file-size="117365" data-height="405" data-id="807acb9b-1b64-4a1e-9977-c0e5b58198fe" node-type="media" data-type="file" data-width="256" title="Attachment">

![sidechain-configured-no-callouts-plugin.png](Sidechaining%20in%20LUNA_assets/6400908f2000b729ee8c14f7ccb7734ef11e23ed.png)

</div>

</div>

## Set plug-in to respond to key or sidechain input

Configure the plug-in to respond to key or sidechain input. The process for configuring a plug-in to “listen” to the sidechain input varies. See the example below.

<div layout="align-start" node-type="mediaSingle" data-width="83">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-enable-in-plugin .png" file-size="1556730" data-height="568" data-id="d871a924-8b19-4683-b93a-3a0db5e561cd" node-type="media" data-type="file" data-width="835" title="Attachment">

![sidechain-enable-in-plugin_.png](Sidechaining%20in%20LUNA_assets/097b44258c680485a423cd81d29c70a1bf6d1e84.png)

</div>

</div>

### Sidechain input examples

Different plug-ins use different methods to enable the key or sidechain input, as shown below. 

<div layout="align-start" node-type="mediaSingle" data-width="83">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-enabled-3rd-party.png" file-size="2306109" data-height="522" data-id="9c5056ef-a12d-4701-a397-580033ddc2e1" node-type="media" data-type="file" data-width="882" title="Attachment">

![sidechain-enabled-3rd-party.png](Sidechaining%20in%20LUNA_assets/95229e812e64cdcf7709594d4b20afb7178656f9.png)

</div>

</div>

 

------------------------------------------------------------------------

# Configuring Sidechain Options

After you configure the sidechain source and destination, the sidechain configuration appears in the sidechain browser. In the sidechain browser, you can change the configuration.

- If desired, use the trim knob to adjust the key trigger level from the sidechain source.
- To hear the sidechain source, click the solo button.
- To enable or disable the sidechain, click the power button.
- With a stereo sidechain destination, you can optionally link the left and right input levels from the sidechain source by checking the Link L/R input levels box.\
  **Tip:** Stereo link allows you to apply the stereo sidechain signal to both channels of the destination processor equally when the source levels vary (so, for example, the stereo panorama doesn’t shift).

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-config.png" file-size="231907" data-height="392" data-id="335e3f92-78ab-4a79-bde0-06792a0e2621" node-type="media" data-type="file" data-width="630" title="Attachment">

![sidechain-config.png](Sidechaining%20in%20LUNA_assets/1037e66890af4a41563a7c1269c6765fe2204c19.png)

</div>

</div>

*Sidechain options with a LUNA Extension*

 

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-config-3p.png" file-size="150323" data-height="405" data-id="c13077de-fd9e-4f59-b77a-4fad580fcd7a" node-type="media" data-type="file" data-width="616" title="Attachment">

![sidechain-config-3p.png](Sidechaining%20in%20LUNA_assets/fb703b63c90b6de40825ad8e419ef1ea84ba4a59.png)

</div>

</div>

*Sidechain options with a plug-in*

------------------------------------------------------------------------

# Removing a Sidechain

You can remove a sidechain by removing the sidechain source, or removing the sidechain insert.

**Tip:** To temporarily disable sidechain processing, power off the sidechain with the power button in the sidechain browser. 

#### To remove a sidechain source:

1.  Click the plus sign in the Utility row of the destination track to open the sidechain browser.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-browser-open.png" file-size="116550" data-height="275" data-id="292793a4-5a10-4583-849f-75072097cf7e" node-type="media" data-type="file" data-width="440" title="Attachment">

    ![sidechain-browser-open.png](Sidechaining%20in%20LUNA_assets/5cffddfb77e05a6bbb157e660821bbf20634afdb.png)

    </div>

    </div>

     

2.  Click the X next to the sidechain source to remove the sidechain source. The sidechain destination is automatically removed.

3.  To remove the sidechain destination without removing the sidechain source, click the Insert and select None. 

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-remove.png" file-size="253162" data-height="446" data-id="6b3fa5af-a696-4959-bf55-b3f566c33643" node-type="media" data-type="file" data-width="559" title="Attachment">

![sidechain-remove.png](Sidechaining%20in%20LUNA_assets/609a12fce9d7228fcd47798b8b3db6c86d268f2e.png)

</div>

</div>

 

------------------------------------------------------------------------

# Sidechain Hover Options

The sidechain control plate appears in the Utility row on the track where the sidechain destination extension or plug-in is instantiated. When you hover your mouse over the sidechain plate, these options appear.

- Click the plus sign to open or close the sidechain browser.
- Click the square to open or close the sidechain extension or plug-in.
- Click ••• to show a menu that allows you to enable or disable the sidechain (this is the same as clicking the power button in the sidechain browser).

![sidechain-hover-options.png](Sidechaining%20in%20LUNA_assets/ac6464c400aa9f07a5ce90a0ac7101c3f67c2f60.png)

<div layout="center" node-type="mediaSingle" data-width="">

<div data-alt="" collection="contentId-225740764" context-id="225740764" file-mime-type="image/png" file-name="sidechain-hover-options.png" file-size="446976" data-height="472" data-id="5f91848a-23ee-480f-b7e2-f7b5faabe6e2" node-type="media" data-type="file" data-width="660" title="Attachment">

</div>

</div>

<span class="wysiwyg-font-size-small">260102</span>

</div>

