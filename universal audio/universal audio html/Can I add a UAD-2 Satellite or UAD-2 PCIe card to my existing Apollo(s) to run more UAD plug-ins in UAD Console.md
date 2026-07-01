---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360051054191-Can-I-add-a-UAD-2-Satellite-or-UAD-2-PCIe-card-to-my-existing-Apollo-s-to-run-more-UAD-plug-ins-in-UAD-Console.html'
converted_at: 2026-05-31T13:44:56Z
tool: htmlq+pandoc
title: 'Can I add a UAD-2 Satellite or UAD-2 PCIe card to my existing Apollo(s) to run more UAD plug-ins in UAD Console?'
word_count: 143
---

# Can I add a UAD-2 Satellite or UAD-2 PCIe card to my existing Apollo(s) to run more UAD plug-ins in UAD Console?


When using **UAD DSP** plug-ins in **UAD Console**, only the DSP of your Apollo interface(s) can be used for processing these plug-ins. \
\
**UAD Console** is the control software for the Apollo's internal mixer engine, and when a plug-in is instantiated on an input channel of an Apollo via Console it is loaded directly into that Apollo's internal mixer engine - this is what makes it possible to track through UAD plug-ins in real time with an Apollo, since the audio processing and plug-in processing is happening synchronously in the same place. \
\
When instantiating UAD plug-ins in your DAW, the DSP of all of your connected UAD-2 & Apollo devices will be used (within the system constraints). 

