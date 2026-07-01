---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/18479403068820-FAQ-How-do-I-use-external-sidechain-in-my-DAW.html'
converted_at: 2026-05-31T13:44:45Z
tool: htmlq+pandoc
title: 'FAQ: How do I use external sidechain in my DAW?'
word_count: 693
---

# FAQ: How do I use external sidechain in my DAW?


This article explains how to use an external sidechain signal with **UAD Native plug-ins** in various DAWs. The following UAD Native plug-ins support external sidechain input:

- **API 2500 Bus Compressor**
- **API Vision Channel Strip**
- **Capitol Mastering Compressor**
- **SSL 4000 E Channel Strip Collection**
- **SSL 4000 G Bus Compressor**

For a detailed explanation of how to use sidechaining with UAD Native plug-ins, see the plug-ins manual page <a href="17949313152532-Using-an-External-Sidechain-with-UAD-Plug-Ins.html" rel="noopener noreferrer" target="_blank">here</a>. 

## Configuring a Sidechain in Your DAW

Each DAW handles external sidechaining differently. Click on the preferred DAW below to access its specific steps:

- <a href="#h_01H8CKV23581N126GH2G92CCSV" target="_self">Logic Pro</a>
- <a href="#h_01H8CKTJ20YDDMY2F2F54JG0V9" target="_self">Ableton Live</a>
- [Cubase and Nuendo](#h_01H8CKTWC2EGCWH8ZERCTMVE7R)
- <a href="#h_01H8CKV769RESWJRBGJD7BFP5P" target="_self">Pro Tools</a>

## Logic Pro

**Note:** the steps for Logic Pro are also available in <a href="https://www.youtube.com/watch?v=yaMrPR3AH2A" rel="noopener noreferrer" target="_blank">this video</a>.

1.  Load a native plug-in that can be sidechained.\
    In this example, we are loading the **Capitol Mastering Compressor**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> on our </span>**Synth Bass**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> track.</span>\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/2108a5706f3b89b5431df2c98139da88b9547a1c.png)
2.  Open the plug-in window and click the **Sidechain**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> slider button to enable the functionality.</span>\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/99926b9ed240658759bf906fa06cf650c2142ebc.png)
3.  In the upper header of the plug-in, click the **Side Chain drop-down menu**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> and select the track you want to use as a sidechain source. </span>In this example, we are sidechaining our **Synth Bass**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> track to the </span>**Drums**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> audio track in our project.</span>\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/07f8dd3756e3602ec261826aaed38a39b03dea06.png)

## Ableton Live

**Note: T**he steps for Ableton Live are also available in <a href="https://www.youtube.com/watch?v=Emyt-hEDllw" rel="noopener noreferrer" target="_blank">this video</a>.

1.  Load a UAD Native plug-in that can be sidechained. In this example, we are loading the **API 2500 Bus Compressor** VST3 plug-in on a track labeled **Synth Bass**. We also have another track, labeled **Drums**, that we will use as our sidechain source in the next step.
2.  In the plug-in tab located in the **Device View Selector**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> at the bottom, select a </span>**Sidechain** <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">source.</span>\
    In this example, we are choosing our **Drums**<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;"> track.</span>\
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![1_SC_Live_LoadingAPI2500.png](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/896db47a37767f0d9d4f20235e2ed8fd178f6720.png)</span>
3.  In the upper header of the plug-in window, the **Sidechain** <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">switch will enable automatically\*, as shown below. You can disable it to easily A/B the resulting sound, if necessary, without changing sidechain settings.</span>\
    <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">![2_SC_Live_SidechainSlideButtonEnabled.png](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/4d6868ee45d2c0143015b85f010a9b955a7e04ea.png)</span>

**Important:** The sidechain switch toggles automatically with the VST3 plug-in, but not the Audio Units version. When using the Audio Units version you will need to toggle the sidechain switch to enable.

## Cubase and Nuendo

**Note:** the steps for Cubase and Nuendo are also available in <a href="https://www.youtube.com/watch?v=r-wjJSZOshM" rel="noopener noreferrer" target="_blank">this video</a>.

1.  Insert a UAD Native plug-in that can be sidechained onto the desired channel.\
    ![1_SC_Cubase_InsertPlugin.png](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/f1802c9d51ca2256d9b8cccc035ecb2de7d9a05a.png)

2.  Open the plug-in window and enable sidechaining within Cubase or Nuendo.\
    ![2_SC_Cubase_EnableSidechainCubase.png](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/22b1c5450d54e8b33c8eb95a7da8c77db1b10b43.png)

3.  Hit the settings cog to the right of the enable sidechain button. Select “Add Side-Chain Source” and select the desired track.

    **Note: T**he track name in this example is “Sidechain source.”

    ![3_SC_Cubase_AddSidechainSource.png](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/29385d87d1cab10c850b0064e9ceb7d15ed9f343.png)

4.  Enable the sidechain input on the plug-in.\
    ![4_SC_Cubase_EnableSidechainPlugin.png](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/d55964814628d3a876bf75b345339b285558d481.png)

## Pro Tools

**Note: T**he steps for Pro Tools are also available in <a href="https://www.youtube.com/watch?v=x8naU2OZxnc" rel="noopener noreferrer" target="_blank">this video</a>.

1.  Insert the UAD Native plug-in onto the desired channel.\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/5a893dedb60cc58cd56e64016f115383c21b44ef.png)

2.  Open the plug-in window and select the desired bus to enable side-chaining within Pro Tools.\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/386ffee1fb1d280be7e06c95ba4f73ff68a78cc9.png)

3.  On the track that feeds the side-chain input, create a send to the previously selected bus. In this case, Bus 1 will be used.\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/e3b0bbe3d3b0efaeeac57d7689dc7021ad7562ca.png)

4.  Turn up the send to a desired level.\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/bfedf47390f423fe4045b092c6fa6c2d5eb60bb5.png)

5.  Confirm side-chaining is enabled in the plug-in.\
    ![](FAQ%20How%20do%20I%20use%20external%20sidechain%20in%20my%20DAW_assets/d55964814628d3a876bf75b345339b285558d481.png)

    **Note:** Pro Tools should automatically enable side-chaining in the plug-in once the side-chain input has been selected.\
     

