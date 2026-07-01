---
source: '/Users/abhinanda/Downloads/us.sitesucker.mac.sitesucker/help.uaudio.com/hc/en-us/articles/360041902831-Working-with-Sessions.html'
converted_at: 2026-05-31T13:44:55Z
tool: htmlq+pandoc
title: 'Working with Sessions'
word_count: 2038
---

# Working with Sessions


## In this article

- <a href="#h_0532135f-22ed-49c5-8084-a149e30c017c" rel="undefined" target="_self">Creating a New Session</a>
- <a href="#h_01F24KS9AM1EWA0WXHB5VXQKQY" target="_self">Using Session Templates</a>
- <a href="#h_f91ffa23-9b87-4568-a35a-f0ce413dd035" rel="undefined" target="_self">Importing an AAF Session</a>
- [Using Session Versions, Bookmarks, and Auto-Backups](#h_01EKZDFT5BGPRSMSWRJX2KZ4DE)
- [Trashing Unused Audio](#h_01H6YTBBQD7AAE4SS7V0HCPZBH) 

------------------------------------------------------------------------

# Creating a New Session

You create sessions and session templates on the Create Session panel. In LUNA, click File \> New, or click the Create item from the LUNA sidebar.

1.  On the Create Session panel, type a name for the session.
2.  Specify a tempo and time signature for the session, or accept the defaults. Note that you can change the tempo and meter after you create the session.
3.  To find the approximate tempo, you can tap the Tap button in time four or more times.
4.  Click the Location bar to open a dialog where you can choose the location for the session file, or accept the default location.
5.  When you have configured the new session settings, click Create.

A new session is created in a parent folder of the same name. When you export files, an Exported Files folder is created in this folder. This folder is the default location for any files exported from the session.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-199393551" context-id="199393551" file-mime-type="image/png" file-name="new-session.png" file-size="100283" data-height="799" data-id="54e005c8-a343-4d01-bc77-46ab59798711" node-type="media" data-type="file" data-width="439" title="Attachment">

![session-page.png](Working%20with%20Sessions_assets/40d71a191a0ae30e3613616ec4ee21d530a53122.png)

</div>

</div>

To create a new session from the main LUNA window, choose File \> New (or use the Command+N macOS or Ctrl+N Windows key command) from the File menu. 

## To open an existing session

- Click the session name in the Recent list, and click Open, or
- Click Open From Disk… and select the session, then click Open.

## To clear the recent sessions list

- Right-click in the Recent sessions list and select Clear Recent.
- Or choose File \> Open Recent \> Clear Recent List from the LUNA menus.

------------------------------------------------------------------------

# Using Session Templates

Use templates to create starting points for new sessions, with recording and mixing configurations preconfigured. A saved session contains all of the settings and customizations of the session from which it is created; however it does not save the undo history, versions, or bookmarks. When you create a new session from a template, it is a completely new session with no history.

A session template contains:

- Tracks

- Plug-ins

- Instruments

- LUNA Extensions

- Send and routing information

- Session Tempo

- Meter

- Markers

- Timeline information

- (Optional) Audio and MIDI data from the source session

## Saving a session template

1.  From the LUNA menus, select File \> Save as Template. The Save Template window opens.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="template-save-as.png" file-size="349786" data-height="495" data-id="2f129689-250e-47b6-9a9c-a10fb8fdeea8" node-type="media" data-type="file" data-width="795" title="Attachment">

    ![template-save-as.png](Working%20with%20Sessions_assets/406a862bf54dfb5ff0ecaad27e0bb1f4c658c379.png)

    </div>

    </div>

2.  Type a name for the template.

3.  In the Notes area, type any notes for the template. 

4.  To save audio and MIDI with the template, select Save audio with template.

5.  Click Save.

You can now use this template when creating a new session.

## Creating a new session from a template

1.  From the LUNA menus, select File \> New, or press Command+N (macOS) / Ctrl+N (Windows).

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="session-new-from-template.png" file-size="50661" data-height="289" data-id="7c535f02-1c4a-49a6-97d2-d243cc17a75a" node-type="media" data-type="file" data-width="453" title="Attachment">

    ![session-new-from-template.png](Working%20with%20Sessions_assets/20ae970d65d33519e7509bde8bc9e8382d5dce52.png)

    </div>

    </div>

2.  Next to Start From, click Template. The Choose Template window opens.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="template-choose.png" file-size="259937" data-height="494" data-id="98a6bb5b-9f9d-40e5-be87-f1976e729a0d" node-type="media" data-type="file" data-width="794" title="Attachment">

    ![template-choose.png](Working%20with%20Sessions_assets/46c96e9314f497706e3e640a50354d12c9803f68.png)

    </div>

    </div>

3.  Choose a template, then click Choose Template.

4.  The name of the session is updated with the template name, and the tempo and signature of the session are adjusted to match the template. In the Template field, the name of the template appears.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="template-populated-fields.png" file-size="59245" data-height="327" data-id="077b9cf5-7fee-4f62-9b60-aae7fc28e44a" node-type="media" data-type="file" data-width="453" title="Attachment">

    ![template-populated-fields.png](Working%20with%20Sessions_assets/52d3e91b447c1e707709a612ddb936c8c3009aee.png)

    </div>

    </div>

5.  Type a new name for the session. Adjust the tempo and signature and change the session location if required.

6.  Click Create to create the session.

The new template is created with the tracks and configuration of the template. If you chose to include audio or MIDI data in the template, that audio or MIDI appears in the new session.

------------------------------------------------------------------------

# Importing an AAF Session

AAF (Advanced Authoring Format) is used by DAW and video applications such as Avid Pro Tools and Adobe Premiere to exchange sessions. LUNA can create new sessions using the AAF file, the audio files generated when the AAF is exported, and a multi-track MIDI file generated with the AAF file. 

## What is imported

When you export or import an AAF file, you can exchange multiple audio tracks with their time positions, fades, and track names. Automation, panning, master tracks, buses, and plug-ins are not included in an AAF file. 

## To create a session from an AAF file

1.  On the Create Session panel, type a name for the session.
2.  Click the Start From AAF button.
3.  From the dialog that opens, choose the AAF session to import.
4.  Type a name for the session.
5.  Specify a tempo for the session, or click the MIDI button, and choose a MIDI file to import.
6.  Click the Location bar to open a dialog where you can select the location for the session, or accept the default location.
7.  When you have configured the new session settings, click Create.

<div layout="align-start" node-type="mediaSingle" data-width="65">

<div class="wysiwyg-text-align-center" collection="contentId-199393551" context-id="199393551" file-mime-type="image/png" file-name="new-session-from-aaf.png" file-size="83731" data-height="439" data-id="7ba6cb9d-66a0-4bfc-a1f4-8a604fa94892" node-type="media" data-type="file" data-width="451" title="Attachment">

![new-session-from-aaf.png](Working%20with%20Sessions_assets/0ed80d856fbab1df60305ebffacd77dd530ea14d.png)

</div>

<div collection="contentId-199393551" context-id="199393551" file-mime-type="image/png" file-name="new-session-from-aaf.png" file-size="83731" data-height="439" data-id="7ba6cb9d-66a0-4bfc-a1f4-8a604fa94892" node-type="media" data-type="file" data-width="451" title="Attachment">

</div>

------------------------------------------------------------------------

# Using Session Versions, Bookmarks, and Auto-Backups

LUNA includes session versioning and bookmarking features, to save the mix and edit state of a session at a defined point in time. Versions and bookmarks have slight differences. 

- **Versions:** Like saving a new session, without actually creating a new session. A version creates a top-level item in the version history. The name of the currently loaded version appears appended to the session name at the top of the LUNA application. Use a version to add elements to a session, change the arrangement of a session, or otherwise significantly change the session. 
- **Bookmarks:** Recall a state of the session. Bookmarks are created below the latest version, or the currently recalled version. Use a bookmark to save separate mixes below a version, or for minor changes in the mix or arrangement. For example, you could make bookmarks under a version for a test mix, a mix with the vocals up and down 3 dB, and an instrumental mix.
- **Automatic backups:** Saved when you close a session. You can view and open automatic backups of your session without creating specific restore points.

 

<div layout="center" node-type="mediaSingle" data-width="100">

<div class="wysiwyg-text-align-center" collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="version-bookmark-tree.png" file-size="161108" data-height="280" data-id="5abebc9c-8ee9-4ef1-924c-c4c1679fb9da" node-type="media" data-type="file" data-width="637" title="Attachment">

![version-bookmark-tree.png](Working%20with%20Sessions_assets/be3458ca2cacca0b89771dcf5d8843baf4a8b672.png)

</div>

</div>

## Accessing versions and bookmarks

You can access versions and bookmarks through a simple interface that allows you to create, name, add, and remove versions and bookmarks.

<div layout="center" node-type="mediaSingle" data-width="100">

<div collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="session-versions-dialog.png" file-size="215021" data-height="494" data-id="33874cd1-431d-4e63-99d5-ea1682b7f8e9" node-type="media" data-type="file" data-width="795" title="Attachment">

![versions.png](Working%20with%20Sessions_assets/b7be64672df952118e79437e81ebf42624f6b317.png)

</div>

</div>

## To create a session version

1.  With a session open, choose File \> Save New Version (or press Shift+Command+S on macOS). 
2.  Type the name for the version and any notes, then click Save.

![version-save-as.png](Working%20with%20Sessions_assets/c60aa822c3b8e28f9fb808b64ac6a92bef2bc049.png)

The new version is saved, and the version name is appended to the session name at the top of the LUNA window. Versions are listed in the Session Versions window (Command+Shift+O on macOS, Ctrl+Shift+O on Windows, or File \> Open Version).

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div class="wysiwyg-text-align-center" collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="version-name-appended.png" file-size="197591" data-height="667" data-id="7843bcde-5d16-42f4-b862-c005df4af23d" node-type="media" data-type="file" data-width="520" title="Attachment">

![version-name-appended.png](Working%20with%20Sessions_assets/8d1af1d1125ab1e5d7c0bcac15c56025efbaf8c9.png)

</div>

</div>

## To create a bookmark

1.  With a session open, press Command+S (macOS) / Ctrl+S (Windows) or choose File \> Save Bookmark.

    ![versions-save-bookmark.png](Working%20with%20Sessions_assets/95fca8f13516d80defb331a80ba64abfa0f57d90.png)

2.  Type a name for the bookmark and any notes, then click Save. 

The new bookmark is saved. Bookmarks are listed in the Session Versions window (Command+Shift+O on macOS, Ctrl+Shift+O on Windows, or File \> Open Version).

## To switch to a different version or bookmark:

1.  With a session open, press Command+Shift+O on macOS, Ctrl+Shift+O on Windows, or choose File \> Open Version. The Session Versions window opens.

    <div layout="center" node-type="mediaSingle" data-width="95">

    <div class="wysiwyg-text-align-center" collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="session-versions-dialog.png" file-size="215021" data-height="494" data-id="33874cd1-431d-4e63-99d5-ea1682b7f8e9" node-type="media" data-type="file" data-width="795" title="Attachment">

    ![versions.png](Working%20with%20Sessions_assets/b7be64672df952118e79437e81ebf42624f6b317.png)

    </div>

    </div>

2.  Locate the session Version or Bookmark you want to open. You can click the **\>** next to a version to expand it, and show the bookmarks associated with the version. Click on a version or bookmark to read any Notes associated with the version or bookmark. 

3.  To show auto backups, click Show Auto-Backups.\
    ![auto-backups.png](Working%20with%20Sessions_assets/6ae2b01121b52104c157266f5ac48b97264f0f17.png)

4.  Double-click on the bookmark or version to open it. 

The version, bookmark, or auto-backup opens in LUNA. 

## To delete a version or bookmark

1.  With a session open, press Command+Shift+O on macOS, Ctrl+Shift+O on Windows, or choose File \> Open Version. The Session Versions window opens. 
2.  Right-click or Control-click on a version, bookmark, or auto-backup, and choose Delete. Click Delete on the warning dialog. The version or bookmark is deleted. 

<div layout="align-start" node-type="mediaSingle" data-width="75">

<div class="wysiwyg-text-align-center" collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="version-bookmark-delete.png" file-size="189796" data-height="492" data-id="81bd3fe4-6f0d-4759-b726-e3f9ed75d34f" node-type="media" data-type="file" data-width="398" title="Attachment">

![version-bookmark-delete.png](Working%20with%20Sessions_assets/c4d1f5a7ad4ef965e08ec21807d2f776922abe28.png)

</div>

</div>

 

## To rename a version or bookmark

1.  With a session open, press Command+Shift+O on macOS, Ctrl+Shift+O on Windows, or choose File \> Open Version. The Session Versions window opens. 
2.  Right-click or Control-click on a version or bookmark, and choose Edit. 
3.  Type the new name and click Save.

The version or bookmark is renamed.

## <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">To open a session version</span>

1.  In the Recent list, select a session. If the Recent list is not visible, select File \> New.

2.  Press Command+Shift+O on macOS, Ctrl+Shift+O on Windows, or choose File \> Open Session Version.

    ![open-version.png](Working%20with%20Sessions_assets/ef91d436c3ebfee9e55448c649db31e50f621076.png)

3.  Select a version or auto backup and click Open. To show automatic backups, click Show Auto-Backups.

The selected session version opens.

## To view and change Session Info

1.  Click the triangle next to the session name at the top of the LUNA window.\
    The Session Info popover opens.

    <div layout="center" node-type="mediaSingle" data-width="">

    <div class="wysiwyg-text-align-center" collection="contentId-225741222" context-id="225741222" file-mime-type="image/png" file-name="session-info-popover.png" file-size="151941" data-height="552" data-id="e3a6e981-1a29-4acd-b148-5619b46309ee" node-type="media" data-type="file" data-width="1132" title="Attachment">

    ![session-info-popover.png](Working%20with%20Sessions_assets/f06a1fd3cea3052220b9a33fded34225266ff2ee.png)

    </div>

    </div>

     

2.  Rename the session by selecting and changing the Session Name.

3.  Rename the version by selecting and changing the Version Name.

4.  To open the Session Versions window, click View Version and Bookmarks.

5.  To open the Session Location in the Finder, click the Location.

</div>

------------------------------------------------------------------------

# Trashing Unused Audio

You can remove (trash) unused audio from your session to reduce the session file size. Removed audio is moved to the macOS Trash or Windows Recycle Bin.

There are two options for removing unused audio:

1.  Remove unused audio that isn't used in the session. This removes any audio that is not used in the current version, a saved bookmark, another session version, or an auto-backup. 
2.  Remove all unused audio, including any audio in the undo queue and any audio in an auto-backup. Currently unused audio that is used in a session version or bookmark is always preserved.

In addition, when you trash unused audio, you are given the option to clear the undo queue. This can free up more currently unused audio files, but will remove your ability to undo any changes. 

## To trash unused audio

1.  From the LUNA menus, select File \> Trash Unused Audio...\
    You are prompted to clear the undo queue. \
    \
    ![trash-audio-clear-undo.png](Working%20with%20Sessions_assets/7976f63dd35b0d2d6e7c01cff9b841eb0d58108c.png)\
     
2.  Click Yes to clear the undo queue, or No to continue without clearing the queue.\
    Depending on whether there are unused audio files in your auto-backups, you will see one of these dialogs.\
    ![trash-audio-no-auto-backup.png](Working%20with%20Sessions_assets/497eea8858ff708144764421fc88402b8b7a9c96.png)\
    \
    ![trash-audio-clear-audio.png](Working%20with%20Sessions_assets/5c46505946b1f66e4a26bf4379ce9d3e4844ae28.png)\
     
3.  Click Trash Unused to move unused files that are not used in an auto-backup to the trash. If the Trash All option is presented, you can click that to move all unused audio files to the trash, including files in auto-backups. To cancel without moving any audio files to the trash, click Cancel.

Unused audio files are moved to the trash. 

 

<span class="wysiwyg-font-size-small">260106</span>

