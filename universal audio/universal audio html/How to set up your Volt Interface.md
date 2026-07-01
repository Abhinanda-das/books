---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/4409233546644-How-to-set-up-your-Volt-Interface.html'
converted_at: 2026-05-31T13:45:00Z
tool: htmlq+pandoc
title: 'How to set up your Volt Interface'
word_count: 3810
---

# How to set up your Volt Interface


![volt_logo_black.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/37316259bc72bbeb26690ac760c62868876a4711.png)

This article explains how to register your Volt, download your software, and redeem your bundled software with the UA Connect app, and how to set up your interface with audio software. These instructions are similar for all Volt audio interface models.

**Note:** To learn how to use Volt's hardware controls and connections, please see the [hardware manual for your specific Volt model](../sections/4409216352148.html).

## Article Contents

- <a href="#h_01FK40ZYV0XK0R3ZGR1EEDM01Q" target="_self">Quick Setup Steps</a>
- <a href="#h_01FK410EPAKW8J50SCQ3ZP3TRS" target="_self">Volt Software Overview</a>
- <a href="#h_01FK413B5PJCQZCPV2THY4G1SH" rel="undefined" target="_self">UA Connect Software App</a>
- [Install Software](#h_01GS6JVE4DHZTMVPYTTYVEGKS4)
- <a href="#h_01FK412S55TF9GTRWE7P847BRX" target="_self">Using Volt with a Windows PC</a>
- <a href="#h_01FK414J7VCPJSZ7R23WXCCMNG" target="_self">Using Volt with macOS</a>
- <a href="#h_01FK42F7B26P3C2Z9TAEAYMYM1" target="_self">Direct Monitoring and Software Monitoring</a>
- <a href="#h_01GS6JWJWKAPQMD9P3WFHXGKGD" target="_self">Updating the Volt firmware or hardware driver</a>
- <a href="#h_01FKK9RR74Q15ER82SYN44K9CA" target="_self">Volt Driver I/O Lists</a>
- <a href="#h_01FKK9TE475A3Q9TSSG5TRRKQA" target="_self">What Next?</a>

------------------------------------------------------------------------

# Quick Setup Steps

To begin with software setup, follow the steps below. The UA Connect software guides you through the process step-by-step.

1.  Download and install UA Connect from <a href="https://www.uaudio.com/volt/start" rel="noopener noreferrer" target="_blank">www.uaudio.com/volt/start</a> 
2.  Launch the UA Connect application
3.  Follow the instructions within the app

Complete details about UA Connect and additional setups are in <a href="13178401374612-Getting-Started-with-UA-Connect.html" target="_self">this article</a>.

------------------------------------------------------------------------

# Volt Software Overview

**Note:** Complete instructions for these items are provided later in this article.

### UA Connect

You'll use the UA Connect software application to register your Volt and redeem the bundled audio software. Your unique claim codes are provided in UA Connect along with links to the software providers for downloading and licensing the software.

### System Sound Setup

System sound is used by software such as music players, web browsers, and conferencing software, as well as system alert sounds. Volt can be set as the input and output (I/O) device for system sound in the operating system (macOS/Windows) settings.

### Audio Software Setup

With some audio software — such as a DAW (digital audio workstation) — you need to choose the device to use for audio I/O. After selecting Volt as the audio interface for the software, the software can directly access and route Volt's I/O.

### Operating Audio Software

Volt is a peripheral device used by software for audio I/O. This article contains general instructions for peripheral I/O device setup. For specific instructions on how to operate the audio software itself, consult the documentation for the software provided by the developer. 

------------------------------------------------------------------------

# UA Connect Software App 

Follow the steps within UA Connect to get started with your Volt. The software guides you through the steps, but detailed instructions are provided in this section.

- <a href="13178401374612-Getting-Started-with-UA-Connect.html" target="_self">Download and install UA Connect</a>
- Hardware Setup
- New Volt Setup
- Redeem bundled software

## Download and Install UA Connect

Visit <a href="13178401374612-Getting-Started-with-UA-Connect.html" target="_self">this article</a> to download and install UA Connect.

## First time Volt setup

You will be prompted to set up and register your Volt. 

<figure class="wysiwyg-image">
![add-detected-volt.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/fd17390b29a4e505d1c652b57deaa3d27d7e42d1.png)
</figure>

## Adding additional Volt interfaces

If you are adding additional Volt interfaces to your system, you may need to add them manually. 

Click the Volt Interfaces tab, then click Add New Volt to add your new Volt to UA Connect. 

<figure class="wysiwyg-image">
![add-new-volt.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/d61bd71f33c256e6a867b8107a958026eb18bff4.png)
</figure>

Connect Volt to your system using the included USB-A to USB-C cable (Volt desktop models) or the included USB-C cable (Volt 876). You can use another appropriate USB 2.0 or higher data cable. Power on your Volt with the power switch.  

![set-up-volt-hardware.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/b32a92e17adca3efa167ed5b375fb486397d7a0a.png)

**Note:** Volt interfaces (except Volt 476, Volt 476P, and Volt 876) are bus powered when connected to ports that meet USB 2.0 specifications. However, some USB ports, such as those on low-quality hubs, don't meet USB specs and cannot supply adequate bus power. If your Volt doesn't power on, connect Volt to external 5VDC power with the included power cable to compensate for the underpowered USB ports.

## New Volt Setup

When you register your new Volt hardware, you are eligible to receive the Volt software bundle and any updates. 

After you log in and connect and power your Volt, follow the prompts to register. 

**Note:** On a PC, you'll install the Volt hardware driver after registration.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![uac-new-volt.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/620a177291d7f1d9d0e55d3343457c5b3787ceb9.png)
</figure>

### PC only: Install driver

Volt is USB class-compliant and can be used for WDM audio without installing the driver. However, you'll benefit from lower latency and improved performance if you install Volt's hardware ASIO driver for audio software. 

Driver installation is part of the Volt registration process. After you complete the registration on a Windows system, you are prompted to install the Volt hardware driver. Click the Install button to install the hardware driver.

<figure class="wysiwyg-image wysiwyg-image-resized" style="width: 75%;">
![uac-install-volt-driver.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/e131c0724c3c06f4af52cebce4e02c2b26c68a98.png)
</figure>

------------------------------------------------------------------------

# Install Software

After registration (and hardware driver install on a PC), you see the main UA Connect screen. Click the Volt Interfaces link in the left sidebar to display the Volt items in the main area. 

![volt-interfaces-tab.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/c8f1c518045a15bd12bd4c36cc10c85e76b45ff8.png)

## Install UAD Console for Volt 876

For Volt 876, install UAD Console to get full remote control of the preamps and configuration for your Volt. You do not need to install UAD-2 software for Volt 876 (UAD-2 software is only used with Apollo devices). 

Next to UAD Console, click Download. To update UAD Console software, click Update.

## Redeem and install bundled software

In the Volt Interfaces area, you can get driver downloads and firmware downloads, get LUNA, get your UAD software, and get unique claim codes for the audio creation software bundled with your Volt. You can access your Volt devices to see registration information and offers, and get software download links from the software providers' websites. 

Click Redeem and follow the on-screen instructions that appear for each software title. Each software title has its own installation and licensing procedure. In most cases, you'll:

1.  Get your item's claim code in UA Connect, and follow a link to the provider's website.
2.  Create an account at the provider's website and enter your claim code or serial number.
3.  Download the software from the provider's website and authorize the software license.

## Redeeming software example: Ableton Live Lite

As an example, the instructions for redeeming the Ableton Live Lite license are detailed below.

#### Redeem the license for Ableton Live Lite

1.  Open UA Connect.
2.  Click Volt Interfaces in the left sidebar. The individual titles are displayed in the **Complete Your Volt** and **UAD Partner Software** areas. Scroll the window to see all titles. Click Show More to see a longer list. \
    ![uac-volt-partner-software.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/25c6b244cc3322683ff17b5a1d57b61353f50743.png)
3.  In the Live Lite area, click Redeem. The Ableton Live Lite Redeem Software overlay appears. Click Claim Your Code. The screen changes to show your unique registration code for Ableton Live Lite.\
    ![uac-live-reg-code.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/7b00854e4e8d1f5dba8f8c928484e29e9b3ca30a.png)
4.  The code is automatically copied to the clipboard.\
    **Tip:** You can also click the code to copy it to your clipboard.
5.  Click Continue. The ableton.com account creation page opens in your web browser.
6.  If you don't have an Ableton account, register for an account. If you already have an Ableton account, log in to your account. 
7.  On the Register a Product page, paste the registration code in the Registration code box and click Register. The license is added to your account. 
8.  Choose the version of Ableton Live Lite to download, and click the Download button.
9.  Install Ableton Live Lite with the downloaded file.
10. <a href="https://help.ableton.com/hc/en-us/articles/209773585-Authorizing-Live-9" rel="noopener noreferrer" target="_blank">Follow Ableton's instructions to authorize your computer for Ableton Live Lite</a>. 

**Note:** The "Claim Your Code" button changes to "Continue" after you claim the code. The code is saved in UA Connect. After you redeem the license for a software title, the Redeem button on the main Software page changes to an Info button, where you can access your existing claim codes. 

------------------------------------------------------------------------

# Using Volt with a Windows PC

In this section, you will learn how to:

- Set up Volt for system sound I/O on your PC 
- Set up Volt for audio software I/O with a DAW
- Set the buffer size for the Volt ASIO driver

## Set up Volt for system sound I/O on your Windows PC

Setting up Volt for system sound allows music players, web browsers, conferencing software, and system alert sounds to use Volt for input and output. 

1.  Connect Volt to your system using the included USB-A to USB-C cable, or another cable appropriate to your system, and power on Volt. 
2.  Click Start from the Windows taskbar and choose Settings.
3.  Click System, then click Sound. 
4.  Choose MONITOR L/R (Volt) as the output device. 
5.  Choose INPUT (Volt) as the input device.

![driver-windows-choose.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/e618a6bea894dd73dac1574c74a805d7d9a12b7a.png)

Your system sounds will now play through Volt, and the first input on Volt will be the default audio source. 

**Note:** Install the hardware driver for low latency performance with audio creation, recording, and mixing apps. 

## Set up Volt for audio software I/O on your Windows PC

On a Windows PC, you select the audio device for I/O (audio input and output) from within each audio app. Once the hardware driver is installed, Volt appears as an ASIO device. When selected in your audio app, this option provides the lowest latency and best system performance.

We include instructions for configuring Volt as the audio device for Ableton Live Lite (included in your software bundle). 

1.  Connect Volt to your system using the included USB-A to USB-C cable, or another cable appropriate to your system, and power on Volt with its rear panel switch. 
2.  Open Ableton Live Lite.
3.  From the Options menu, select Preferences.
4.  Click the Audio tab.
5.  From the Driver Type menu, select ASIO.
6.  From the Audio Device menu, select Universal Audio Volt.\
    ![live-audio-driver-choose-windows.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/d5aa19cdcf5698efc8a95e5432341ad20735b054.png)
7.  Close the Preferences window, and audio I/O setup is complete.

## Configure inputs for Ableton Live Lite on your Windows PC

On a Windows PC, you configure audio inputs in the audio app you are using. 

1.  Start Ableton Live Lite.
2.  From the Options menu, select Preferences.
3.  In the Audio Device Channel Configuration area, click Input Config.\
    ![windows-input-output-config-click.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/14e82a3c19de8abaf53dfc9c55c57d19131d01d1.png)
4.  Click to highlight the inputs you want to use with Live. To clear an input, click an input so it is not highlighted. Click OK when you have selected the inputs.\
    ![live-windows-select-inputs.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/9037975811311c752efc06149d9c0369cada7822.png)
5.  Click Output Config.
6.  Click to highlight the outputs you want to use with Live. To clear an output, click an output so it is not highlighted. Click OK when you have selected the outputs.\
    ![live-windows-select-outputs.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/07c1d49d1dfdc3833c1eb6ce9d51aa6772fffa7f.png)
7.  Close the Preferences window, and audio I/O setup is complete.

## Configure Volt audio buffer size in Windows

The audio buffer size determines how much time the system has to process audio. The smaller (shorter) the buffer size, the faster the system responds, and the less latency (delay) you hear when playing virtual instruments or monitoring audio through the app. However, smaller buffer sizes also require more host processing power and system resources, and in some cases low buffer sizes can cause pops, clicks, or stutters in the audio. 

Adjust the buffer size to balance low latency with CPU and system performance. To start, try setting the buffer size to 128 or 256 samples for less latency when recording and monitoring through the audio software. If you hear pops, clicks, or stutters in the audio, increase the buffer size.

**Tip:** You can monitor audio inputs without latency using Volt's direct monitoring feature. See <a href="#h_01FK42F7B26P3C2Z9TAEAYMYM1" target="_self">Direct Monitoring and Software Monitoring</a> for more information. 

### Configure the audio buffer size for Windows

1.  From the Windows taskbar, click Start, then choose Volt Driver Control Panel. The Volt Driver Control Panel opens.\
    ![windows-buffer-size-setting.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/a1eb960c4ce7c203463707510e2727a2ce99ec25.png)
2.  Click the Buffer Settings tab.
3.  Choose the buffer size from the drop menu. 
4.  Close the Control Panel when you have finished configuring the Volt buffers.

**Tip:** The Buffer Settings panel shows the input and output latency in the ASIO Status area as you change buffer sizes. 

------------------------------------------------------------------------

# Using Volt with macOS

On macOS, Volt appears as a Core Audio device. You can configure the audio buffer size in your audio app.

We include instructions for configuring Volt as the audio device for Ableton Live Lite (included in your software bundle). 

You choose to use your Volt device for audio input and output within your audio software.

## Set up Volt for system sound I/O on macOS

Because Volt is class-compliant and supports Core Audio, you can immediately use Volt for system audio and audio creation, recording, and mixing apps on macOS. 

1.  Connect Volt to your system using the included USB-A to USB-C cable, or another cable appropriate to your system, and power Volt on. 
2.   Click the Apple icon in the upper left of your screen, and choose System Preferences.
3.  Click Sound. 
4.  Click Output, and select your Volt as the output device. 
5.  To use Volt as your system input device, click Input, and select Volt.
6.  Click OK to allow microphone access if prompted by macOS.

![audio-macos-choose-intput.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/1a739c4663cacc4ae45e60e2f79ef1f5f62f3a17.png)

![audio-macos-choose-output.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/9b5220ed0543808bf6881d731cb9dc936013fc7c.png)

Your system sounds will now play through Volt, and the first input on Volt will be the default audio source. 

## Set up Volt for audio software I/O on macOS

On a Mac, you select the audio device for I/O (audio input and output) from within each audio app. 

We include instructions for configuring Volt as the audio device for Ableton Live Lite (included in your software bundle). 

1.  Connect Volt to your system using the included USB-A to USB-C cable, or another cable appropriate to your system, and power Volt on. 
2.  Open Ableton Live Lite.
3.  From the Live menu, select Preferences.
4.  Click the Audio tab.
5.  From the Driver Type menu, select Core Audio. 
6.  From the Audio Input Device menu, select your Volt. 
7.  From the Audio Output Device menu, select your Volt.\
    ![live-audio-buffers.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/4c6d271f1c3327bd8ca5e87eab077c26fd163db8.png)
8.  Under Latency, set the buffer size, if you want to change it.
9.  Close the Preferences window. 

### About audio buffer size

The audio buffer size determines how much time the system has to process audio. The smaller (shorter) the buffer size, the faster the system responds, and the less latency (delay) you hear when playing virtual instruments or monitoring audio through the app. However, smaller buffer sizes also require more host processing power and system resources, and in some cases low buffer sizes can cause pops, clicks, or stutters in the audio. 

Adjust the buffer size to balance low latency with CPU and system performance. To start, try setting the buffer size to 128 or 256 samples for less latency when recording and monitoring through the audio software. If you hear pops, clicks, or stutters in the audio, increase the buffer size.

#### Buffer size tips

- You can monitor audio inputs without latency using Volt's direct monitoring feature. See <a href="#h_01FK42F7B26P3C2Z9TAEAYMYM1" target="_self">Direct Monitoring and Software Monitoring</a> for more information.
- Ableton Live Lite shows CPU usage in the upper right corner of the screen. You can see the impact of your buffer size changes on the system CPU as you change the buffer size. 

![live-lite-cpu-usage.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/906509a888db6c9482f6a74bc10c91cc640bdcd8.png)

## Configure inputs for Ableton Live Lite on macOS

You configure inputs in your audio software on macOS. We include an example configuration for inputs and outputs in Ableton Live Lite (included in your Volt software bundle). 

For other audio software, refer to your audio app documentation for information on how to configure inputs and outputs.

1.  Start Ableton Live Lite.
2.  From the Live menu, select Preferences.
3.  In the Audio Device Channel Configuration area, click Input Config.\
    ![live-macos-input-output-click.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/2941c83fb8f26b655c44f380b806007443e106ea.png)
4.  Click to highlight the inputs you want to use with Live. To clear an input, click an input so it is not highlighted. Click OK when you have selected the inputs.\
    ![live-input-select-inputs.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/9b8024d55f0312f5c4c068c08bb566fec2b7d320.png)
5.  Click Output Config.
6.  Click to highlight the outputs you want to use with Live. To clear an output, click an output so it is not highlighted. Click OK when you have selected the outputs.\
    ![live-output-select-outputs.png](How%20to%20set%20up%20your%20Volt%20Interface_assets/339fd1675803017dbc105ad6e5f6a10ae5cf2262.png)
7.  Close the Preferences window.

------------------------------------------------------------------------

# Direct Monitoring and Software Monitoring

You can monitor input signals with either software monitoring or direct monitoring. 

**Note:** These instructions apply to Volt desktop models. For Volt 876, direct hardware monitoring can be flexibly mixed and routed with Volt 876 UAD Console. See the [UAD Console for Volt 876 manual](41288447947284-UAD-Console-for-Volt-876-Manual.html) for more. 

## Direct monitoring

Use direct monitoring on Volt to hear your live input signals with no latency. Direct monitoring routes Volt's inputs directly to its outputs, but you can still hear audio from the software. This allows you to use higher buffer sizes when recording while still hearing your live inputs without latency. 

### Direct monitoring notes (Volt desktop units)

- Direct monitoring allows you to use the Vintage Preamp and 76 Compressor, but you cannot use plug-ins or other software processing on direct monitored tracks. 
- Volt interfaces with one input always present the direct signal panned to the center. The Direct button is lit blue when active. 
- Volt desktop interfaces with two or more inputs pan input 1 and input 3 to the left, and input 2 and 4 to the right when the Direct button is lit orange. When the Direct button is lit blue the signals are panned to the center, except on Volt 476, which has a separate Mono button.
- When you enable direct monitoring on a Volt desktop unit, the output level from your software is reduced slightly so you can clearly hear your input signals.

#### To use direct monitoring:

1.  Press the Direct button on your Volt so it is lit orange or blue. On Volt models with two or more inputs, press the button until it is lit orange to monitor inputs panned in stereo. Press the button until it is lit blue to monitor the inputs panned to the center.\
    **Note:** On Volt 476, press the button to select each pair of direct monitor sources, which are monitored in stereo by default, and press the Mono button to monitor the direct inputs panned to the center.
2.  In your audio app, disable software monitoring for the record track, or mute the record track. If you don't disable software monitoring in your audio software when direct monitoring is on, your inputs might sound thin or "phasey." There are different methods to do this for each app; see your software documentation for more information

## Software monitoring

When using your audio software's monitoring feature, live input signals from Volt pass through the software before you hear them back through the monitor or headphone outputs. Because the live signal passes through the software, it uses the software's audio buffers, and incurs some latency — the signal is delayed slightly, depending on the buffer size. 

Higher buffer sizes cause longer delays, which can make recording more challenging. However, when you want to record through software plug-ins, software monitoring lets you hear the live input with plug-in processing. 

With software monitoring, lower the buffer size to reduce the amount of latency to an acceptable amount. If you hear artifacts like pops, clicks, and stuttering audio, increase the buffer size. 

#### To use software monitoring

1.  Make sure the direct monitoring button on the Volt interface is off (unlit). 
2.  In your audio app, enable software monitoring for the record track, or unmute the record track. There are different methods to enable software monitoring for each app; see your software documentation for more information

------------------------------------------------------------------------

# Updating the Volt firmware or hardware driver

When new firmware or a new hardware driver is available for your Volt, the details appear on the Hardware page. 

## Update Volt firmware

When new firmware is available, the Update button appears in the UA Connect firmware area.

1.  Open UA Connect.
2.  Click the Volt Interfaces tab on the left of the window.
3.  If new firmware is available, the Update button appears on the Firmware line. 
4.  Click Update to update the firmware.

## Update Volt hardware driver

When a new Volt hardware driver is available, the Update button appears in the UA Connect Drivers and Control Panel area.

1.  Open UA Connect.
2.  Click the Volt Interfaces tab on the left of the window.
3.  If a new hardware driver is available, the Update button appears on the Drivers and Control Panel line. 
4.  Click Update to update the hardware driver.
5.  Follow the prompts. You may be required to power off and power on Volt. 

------------------------------------------------------------------------

# Volt Driver I/O Lists

The tables in this section list the I/O numbers and names for all Core Audio / ASIO streams available with Volt hardware. For Volt 876 driver I/O lists, see the [Volt 876 Hardware Manual.](41288385879956-Volt-876-Hardware-Manual.html) 

### **Volt 1 I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2 (Duplicate of Input 1 for stereo-only software)
- **Outputs**
  - 1: MONITOR L
  - 2: MONITOR R

### **Volt 2 I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2
- **Outputs**
  - 1: MONITOR L
  - 2: MONITOR R

### **Volt 176 I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2 (Duplicate of Input 1 for stereo-only software)
- **Outputs**
  - 1: MONITOR L
  - 2: MONITOR R

### **Volt 276 I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2
- **Outputs**
  - 1: MONITOR L
  - 2: MONITOR R

### **Volt 4 I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2
  - 3: LINE IN 3
  - 4: LINE IN 4
- **Outputs**
  - 1: LINE 1
  - 2: LINE 2
  - 3: LINE 3
  - 4: LINE 4

### **Volt 476 I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2
  - 3: LINE IN 3
  - 4: LINE IN 4
- **Outputs**
  - 1: LINE 1
  - 2: LINE 2
  - 3: LINE 3
  - 4: LINE 4

### **Volt 476P I/O**

- **Inputs**
  - 1: INPUT 1
  - 2: INPUT 2
  - 3: INPUT 3
  - 4: INPUT 4
- **Outputs**
  - 1: LINE 1
  - 2: LINE 2
  - 3: LINE 3
  - 4: LINE 4

# What Next?

Visit these links to learn more about Volt.

## Volt Tutorials

Watch these videos to learn the basics: how to connect your Volt to your computer or iPad, headphones and speakers, instruments, and microphones,

- <a href="4409498087828-Volt-Tutorial-Videos.html#h_01FKF7029N8FT9Q5TTR8G1EGFS" rel="undefined" target="_self">Connecting Volt to Your Computer or iOS Device</a>
- <a href="4409498087828-Volt-Tutorial-Videos.html#h_01FKF70NWVJVNT55TGGG09T7QW" target="_self">Basic Audio Connections with Volt</a>

Watch these videos to get started with Volt and your DAW software.

- <a href="4409498087828-Volt-Tutorial-Videos.html#h_01FKF717WPYKHCSX3E7SE58GYZ" target="_self">Setting up your DAW with Volt</a>
- <a href="https://www.youtube.com/watch?v=CWZtG3M-IZ8" target="_self">How to Redeem and Install Software Included with Volt</a>

Watch these videos to learn more about how to use Volt features like direct monitoring, Vintage Preamp Mode, the 76 Compressor, and phantom power.

- <a href="4409498087828-Volt-Tutorial-Videos.html#h_01FKF71FHCQ1TETQB0GGXP7E50" target="_self">Volt Basics</a>

<span class="wysiwyg-font-size-small">v260414</span>

