---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/12241979631380-Sphere-Plug-In-Operation-and-Preferences.html'
converted_at: 2026-05-31T13:44:43Z
tool: htmlq+pandoc
title: 'Sphere Plug-In Operation and Preferences'
word_count: 736
---

# Sphere Plug-In Operation and Preferences


## In this article

- <a href="#h_01GPDB43H8A28V4YFA3H7SE9KV" target="_self">Keyboard and mouse shortcuts and modifiers</a>
- <a href="#h_01GPDB4B004CXTWFGSXZ1Y295N" target="_self">Plug-in and preference file locations</a>
- <a href="#h_01GPDB4HT0EEWXVYYTQTKF21G0" target="_self">Plug-in types, names, and categories</a>
- <a href="#h_01GPDB4X3TA6D6N0HE43WXXJN6" target="_self">Uninstalling Sphere plug-ins</a>
- <a href="#h_01GPDB59SHRT5KRNT8M9QVP1S8" target="_self">Automation parameters</a>

# Keyboard and mouse shortcuts and modifiers

Use the following keyboard and mouse shortcuts in Sphere plug-ins.

- Double-click a parameter to reset its default value.

<!-- -->

- On macOS, Command+click a parameter to reset to its default value.

<!-- -->

- On Windows, Alt+click a parameter to reset to its default value.

# Plug-in and preference file locations

During installation, the Sphere plug-ins and preferences are installed in these locations on the hard drive.

## Plug-in install locations

<table>
<tbody>
<tr>
<td style="text-align: center;"><p><strong>OS</strong></p></td>
<td style="text-align: center;"><p><strong>Plug-in format</strong></p></td>
<td style="text-align: center;"><p><strong>Location</strong></p></td>
</tr>
<tr>
<td rowspan="4" style="text-align: center; vertical-align: top;"><p>Windows</p></td>
<td style="text-align: center; vertical-align: top;"><p>VST2</p></td>
<td style="text-align: center; vertical-align: top;"><p>C:\Program Files\Steinberg\VstPlugins\</p></td>
</tr>
<tr>
<td style="text-align: center; vertical-align: top;"><p>VST3</p></td>
<td style="text-align: center; vertical-align: top;"><p>C:\Program Files\Common Files\VST3\</p></td>
</tr>
<tr>
<td style="text-align: center; vertical-align: top;"><p>AAX</p></td>
<td style="text-align: center; vertical-align: top;"><p>C:\Program Files\Common Files\Avid\Audio\Plug-Ins\</p></td>
</tr>
<tr>
<td style="text-align: center; vertical-align: top;"><p>UAD</p></td>
<td style="text-align: center; vertical-align: top;"><p>C:\Program Files\Common Files\Audio\Plug-Ins\Universal Audio\</p></td>
</tr>
<tr>
<td rowspan="4" style="text-align: center; vertical-align: top;"><p>macOS</p></td>
<td style="text-align: center; vertical-align: top;"><p>VST2</p></td>
<td style="text-align: center; vertical-align: top;"><p>/Library/Audio/Plug-Ins/VST/</p></td>
</tr>
<tr>
<td style="text-align: center; vertical-align: top;"><p>VST3</p></td>
<td style="text-align: center; vertical-align: top;"><p>/Library/Audio/Plug-Ins/VST3/</p></td>
</tr>
<tr>
<td style="text-align: center; vertical-align: top;"><p>AAX</p></td>
<td style="text-align: center; vertical-align: top;"><p>/Library/Application Support/Avid/Audio/Plug-Ins/</p></td>
</tr>
<tr>
<td style="text-align: center; vertical-align: top;"><p>Audio Units</p></td>
<td style="text-align: center; vertical-align: top;"><p>/Library/Audio/Plug-Ins/Components/</p></td>
</tr>
</tbody>
</table>

## Plug-in preference file locations

Preferences for your Sphere plug-ins are stored in the following locations. Preference files are named *\[plugin_name\].txt*.

- macOS: /Users/\<username\>/Library/Application Support/Universal Audio/workspace/preferences/
- Windows: C:\Users\\username\>\AppData\Roaming\Universal Audio\\

# Plug-in types, names, and categories

## DSP and native plug-ins

If you have an Apollo or Pro Tools HDX system, you will get the best performance by using the DSP-powered plug-ins.

### Using UAD DSP plug-ins in Apollo Console

In Apollo Console, UAD DSP plug-ins are automatically loaded. 

### Using UAD DSP plug-ins in LUNA and other DAWs

In LUNA and other DAWs, Sphere DSP plug-ins are named differently from the native versions, so you can load the correct plug-in. To use the DSP version of your Sphere plug-in, observe the naming conventions to load the correct plug-in:

- A UAD plug-in name begins with the prefix UAD; for example **UAD Sphere Mic Collection**
- A native plug-in name does not begin with a prefix; for example **Sphere Mic Collection**

### Using AAX DSP plug-ins in Pro Tools HDX

In Pro Tools HDX with a DSP accelerator, switch the channel to DSP mode to use the AAX DSP version of the Sphere plug-in you want to use.

## Sphere plug-in categories

In Apollo Console and LUNA, plug-ins appear in the **Microphone** category.

In other DAWs, Sphere plug-ins are sorted into different categories, which may vary depending on your selected DAW preferences and the type of plug-ins your DAW uses. 

### When plug-ins are sorted by manufacturer

If your DAW is configured to sort plug-ins by manufacturer:

- UAD DSP plug-ins appear in the **Universal Audio** folder
- Native plug-ins appear in the **Universal Audio Sphere** folder

### When plug-ins are sorted by category or tags

If your DAW sorts plug-ins by category or tags:

- In Pro Tools, AAX plug-ins appear in the **Sound Field** category
- VST2 and VST3 plug-ins appear in the **Spatial** or **FX \| Spatial** categories
- Audio Units plug-ins appear in the **Specialized** category

![sphere-plug-ins-naming-categories.png](Sphere%20Plug-In%20Operation%20and%20Preferences_assets/141d7a5aa0f338cb529c807a6924309a7ca568f4.png)

*An example of Sphere plug-in sorting in a DAW*

# Uninstalling Sphere plug-ins

## Native 

#### To remove the native Sphere plug-ins from your macOS system

- Delete the plug-in files from their installed locations by dragging them to the Trash. See <a href="#h_01GPEHNG3A04CN32MVJ98TDCDV" target="_self">Plug-in install locations</a>.

#### Windows

#### To remove the native Sphere plug-ins from a Windows computer

1.  Navigate to Control Panel\Programs\Programs and Features.
2.  Select Universal Audio Sphere. 
3.  Double-click to uninstall.

## UAD

To remove UAD software, please [visit these articles](https://help.uaudio.com/hc/en-us/search?utf8=%E2%9C%93&query=%22UAD+Uninstall%22&commit=Search). 

# Automation parameters

The following automation parameters are available for Sphere plug-ins. 

|               |                                   |
|:-------------:|:---------------------------------:|
| **Parameter** |             **Name**              |
|     Axis      | Mic1 Axis Shift / Mic2 Axis Shift |
|    Filter     |     Mic1 Filter / Mic2 Filter     |
|    Pattern    |    Mic1 Pattern / Mic2 Pattern    |
|     Type      |       Mic1 Type / Mic2 Type       |

 

