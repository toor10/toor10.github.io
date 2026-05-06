================================================================================
WHAT IS FreeCommander
================================================================================
FreeCommander is an easy-to-use alternative to the standard Windows file manager. 
You can configure almost everything. Supported Windows versions: Windows XP and above.
FreeCommander XE is in two versions 32 and 64 bit. 
Please check the info about using FreeCommander XE 32 bit on 64 bit Windows http://freecommander.com/en/version-summary/    



================================================================================
AFTER YOU HAVE INSTALLED FreeCommander XE
================================================================================

If you have worked with the FreeCommander 2009.02b:
- the settings of the FreeCommander 2009.02b are not compatible with the settings of the FreeCommander XE
- do not copy the old settings to the new settings folder

If you have worked with the FreeCommander XE 32 bit version and now you want use 64 bit version
- the settings are compatible; you can use the settings from the 32 bit version in the 64 bit version
- for moving the settings you can use Tools->Backup all settings, Tools->Restore all settings


The available help files you can download from the site http://freecommander.com/en/languages/  

Trouble with the help file
==========================
When viewing your CHM documentation, Microsoft's HTML Help Viewer is showing an error page saying either that:
 - The action has been canceled 
 - The page cannot be displayed
 
Solutions
 - Launch help file from local drive and not from a network path or via a mapped networked drive.  
 - Make sure your help file isn't in a path with symbols such as "#" (sharp).  
 - In some cases, you can have access to an "unblock" button in the properties page of the help file. Right click on the file then go to its properties and click the "unblock" button. This button is not available in all systems though. 
 - Try the HHReg utility http://www.ec-software.com/products_hhreg.html or read this technical note from the Microsoft Knowledge Base http://support.microsoft.com/kb/896054/.

================================================================================
FEEDBACK & SUGGESTIONS
================================================================================

Direct your feedback, suggestions and bug reports to the FreeCommander forum http://www.forum.freecommander.com
or directly to me marek@freecommander.com but please do not expect that you get an answer immediately :). 


I hope you will enjoy FreeCommander 

MAREK JASINSKI


================================================================================
Important changes and bug fixes in the release 652
================================================================================
 - Implemented for detail view if horizontal scrollbar is not visible: using of left/right arrow for fast navigation to top/bottom of the list
 - Implemented: %ActivSel% and other variables are available in the DOS command line http://www.forum.freecommander.com/viewtopic.php?f=20&t=5571 
 - Implemented: new option added for drives bar - "Use large images" 
 - Bug fix: "Compare folders" may not works properly if the option "Reload both lists before compare" is not active
 - Bug fix: "Compare folders" - the option "Reload both lists before compare" turn off auto refresh
 - Bug fix: file created with %ActivSelAsFile% parameter is not UTF8 encoded
 - Bug fix: some mp3 values (status, multi rename) are not properly extracted from mp3 file 
 - Bug fix: "Favorite tools edit..." - possible exception while define the first category
 - Bug fix: Selection problem if quick search field open http://www.forum.freecommander.com/viewtopic.php?f=19&t=5550
 - Bug fix: No name for Lister plugins if %FcSrcPath% is used in path http://www.forum.freecommander.com/viewtopic.php?f=7&t=5511
 - Bug fix: Shift+Tab is not available in the search dialog if tree view is open in main window http://www.forum.freecommander.com/viewtopic.php?f=7&t=5555
 - Bug fix: Synchronize - compare may ignore file of size if "Compare by Date" options are active
 - Bug fix: Focus issues http://www.forum.freecommander.com/viewtopic.php?f=7&t=5559, http://www.forum.freecommander.com/viewtopic.php?f=7&t=5558
 - Bug fix: Mouse wheel does not works for the file list if the active control is the tree http://www.forum.freecommander.com/viewtopic.php?f=20&t=5575
 - Bug fix: List view refresh issue http://www.forum.freecommander.com/viewtopic.php?f=7&t=5584
 - Bug fix: Status bar truncated text issue http://www.forum.freecommander.com/viewtopic.php?f=7&t=5352
  
================================================================================
Important changes and bug fixes in the release 653
================================================================================
 - Implemented: Right click on version info in about box shows "Copy" popup menu
 - Implemented: Settings - Select items - Colors for hot item; new options added
 - Bug fix: Saving of the column profile may change the column order (x64)
 - Bug fix: Changes for status bar settings are not saved (x64)
 - Bug fix: Copying of the file(s) from the nested archive may not work
 - Bug fix: Using of the "-C" parameter in the command line cause error message http://www.forum.freecommander.com/viewtopic.php?f=22&t=5617
 - Bug fix: Error message will be shown for rename (when using dialog for rename) if nothing was changed http://www.forum.freecommander.com/viewtopic.php?f=22&t=5524
 - Bug fix: Synchronize of network folders may not start (error message will be shown 'Operation is not supported for choosed folders')
 - Bug fix: Thumbnails view navigation issue http://www.forum.freecommander.com/viewtopic.php?f=7&t=3966
 - Bug fix: Thumbnail creating - issues and bugs http://www.forum.freecommander.com/viewtopic.php?f=7&t=5658
 - Bug fix: The values for size defined in filter are not included in the check, only the scope between the values is checked   
 

================================================================================
Important changes and bug fixes in the release 654
================================================================================
- Implemented: Quick starter - shortcuts for repository activating added: Ctrl+1,...,Ctrl+0
- Implemented: New actions for quick starter opening added 
- Implemented: Using file/folder colors for selected items (Windows colors)
- Implemented: Dot in the extension column is controlled by ShowExtensionWithDot=1 
- Implemented: Plain view button in the "Delete" dialog http://www.forum.freecommander.com/viewtopic.php?f=18&t=5745
- Implemented: Size of the MD5-Checksum dialog is saved now
- Bug fix: Font style not used for status bar
- Bug fix: Tree refresh fail if folder is deleted in the tree http://www.forum.freecommander.com/viewtopic.php?p=17683#p17683
- Bug fix: Starting with command line always create new tabs http://www.forum.freecommander.com/viewtopic.php?f=19&t=5710
- Bug fix: Invalid entry in FreeCommander.ini file http://www.forum.freecommander.com/viewtopic.php?f=7&t=5720
- Bug fix: Tabs are not saved when saving the Setttings with the command Tools->Save settings
- Bug fix: Plain view with folders - folder size inclusive subfolders is showed
- Bug fix: Some folders are not correctly extracted (introduced in 653) http://www.forum.freecommander.com/viewtopic.php?f=7&t=5716

================================================================================
Important changes and bug fixes in the release 655
================================================================================
- Implemented: Option to define in the freecommander.ini if last used path of each tab (locked too) should be restored - TabRestoreLastPathForAll=1 
- Implemented: Option to define in the freecommander.ini for changing the splitting 25/75 - SplitterSwitchSmall=25
- Implemented: Layouts  
- Bug fix: Plain view icon state issue http://www.forum.freecommander.com/viewtopic.php?f=7&t=5809#p18237
- Bug fix: Possible exception on program close http://www.forum.freecommander.com/viewtopic.php?f=7&t=5801
- Bug fix: Folder synchronize may not works on some PCs

================================================================================
Important changes and bug fixes in the release 656
================================================================================

- Bug fix: http://www.forum.freecommander.com/viewtopic.php?f=22&t=5863
- Bug fix: http://www.forum.freecommander.com/viewtopic.php?f=7&t=5864

================================================================================
Important changes and bug fixes in the release 657
================================================================================
- Bug fix: Layouts - tabs saved in layout are not restored

================================================================================
Important changes and bug fixes in the release 658
================================================================================
 - Implemented: Icons for layouts
 - Implemented: Internal popup menu for layouts for using in toolbar
 - Bug fix: Address bar text not visible and /or icons shifted
 - Bug fix: Restore layout may not update address bar 

================================================================================
Important changes and bug fixes in the release 659
================================================================================
 - Implemented: DOS box can be opened with UNC path http://www.forum.freecommander.com/viewtopic.php?f=7&t=5655
 - Implemented: Settings for defining quick viewer size by file type (only for "One viewer per panel" and vertical orientation of the main splitter)
 - Bug fix: Folders are not properly sorted (sorting on size) after auto refresh action
 
================================================================================
Important changes and bug fixes in the release 660
================================================================================
- Implemented: Warning message if files to compare are not the same type http://www.forum.freecommander.com/viewtopic.php?f=20&t=5922
- Implemented: New option for the tab property added: Use as base folder for the tree
- Bug fix:  Dual/one panel (F10) - "split horizontal" state forgotten http://www.forum.freecommander.com/viewtopic.php?f=19&t=5939

================================================================================
Important changes and bug fixes in the release 661
================================================================================
- Implemented: Option to disable MD5 file association can be defined in the freecommander.ini [Form] section: Md5VerifyUseFC=0 
- Implemented: Main form size and location is saved with layout
- Bug fix: History is removed on tab double-click http://www.forum.freecommander.com/viewtopic.php?f=7&t=5946
- Bug fix: File container arrow keys bug http://www.forum.freecommander.com/viewtopic.php?f=7&t=5963
- Bug fix: File container move operation bug http://www.forum.freecommander.com/viewtopic.php?f=7&t=4036 
- Bug fix: Folder structure is not preserved if copy folder from a file container  http://www.forum.freecommander.com/viewtopic.php?f=6&t=5958

================================================================================
Important changes and bug fixes in the release 662
================================================================================
- Bug fix: Rename file fails with the message "The file/folder name is not valid"

================================================================================
Important changes and bug fixes in the release 663
================================================================================
- Implemented: New option for active tab color in the inactive panel added
- Implemented: New options for tab properties; Remove all colors; Always use the colors - for active tab too. 
- Implemented: New option for drives added: "Calculate free space for network drives too - can be very slow"
- Changed: The option "Drive hint visibility" changed to "Show drive hint"
- Bug fix: Quick filter does not filter folder names if "Plain view - folders" or "Plain view - files, folders" is active http://www.forum.freecommander.com/viewtopic.php?f=7&t=5979
- Bug fix: Restore from system tray does not work if the option "Start as minimized" is active
 
================================================================================
Important changes and bug fixes in the release 664
================================================================================
- Implemented: New option - color for inactive file container tab added
- Implemented: New viewer option "Use IrfanView/XnView to load images" 

================================================================================
Important changes and bug fixes in the release 665
================================================================================
- Implemented: Operations implemented for MTP devices: rename, create directory and delete (Win 8)

================================================================================
Important changes and bug fixes in the release 666
================================================================================

- Bug fix: Tree option "Show link to folders" broken
- Bug fix: Loading viewer in the search dialog: only internal viewer is used http://www.forum.freecommander.com/viewtopic.php?f=22&t=6027
- Bug fix: Unexpected result for "New folder" http://www.forum.freecommander.com/viewtopic.php?f=19&t=6040
- Implemented: Operations implemented for MTP devices: copy, move (Win 8)

================================================================================
Important changes and bug fixes in the release 667
================================================================================
 - Bug fix: LNK files with "read only" attribute can not be opened
 - Bug fix: Folder size option is not restored with layout
 - Implemented: Search dialog - selection for the size column content  
 - Implemented: Operations implemented for MTP devices: copy, move, delete (Win 7)
 - Implemented: Operations implemented for MTP devices: multi rename (not all options are possible) (Win 8)

================================================================================
Important changes and bug fixes in the release 668
================================================================================
 - Bug fix: Not active option "Quick filter bar always visible" works not correctly
 - Bug fix: Copy from MTP device will remove file extension (Win8) http://www.forum.freecommander.com/viewtopic.php?f=7&t=6066
 - Bug fix: Sorting is not restored with layout
 - Bug fix: [exif_taken] in multi rename generate "????? Read EXIF info error" for some jpg pictures http://www.forum.freecommander.com/viewtopic.php?f=19&t=6086 
 - Implemented: Click on empty tab area activate the panel http://www.forum.freecommander.com/viewtopic.php?f=20&t=6080
 - Implemented: New action added "File - New item" http://www.forum.freecommander.com/viewtopic.php?f=20&t=6082
 
================================================================================
Important changes and bug fixes in the release 669
================================================================================
 - Bug fix: Selection problem if "Full row select" option is active http://www.forum.freecommander.com/viewtopic.php?f=7&t=5649
 - Bug fix: Tree pane - font color for hoovered item not correctly http://www.forum.freecommander.com/viewtopic.php?p=19237#p19237
 - Bug fix: Quick filter options (field width and color) broken
 - Bug fix: Folder tree remains hidden after switch dual/one panel http://www.forum.freecommander.com/viewtopic.php?f=7&t=6111
 - Bug fix: Rename dialog not correctly displayed (now the dialog is resizable) http://www.forum.freecommander.com/viewtopic.php?f=7&t=6106
 - Bug fix: Inconsistent file quoting in main window vs search results http://www.forum.freecommander.com/viewtopic.php?f=7&t=6120
 - Changed: Synchronize folders - empty folders are showed in the file list now
 - Implemented: System context menu for favorites   

================================================================================
Important changes and bug fixes in the release 670
================================================================================
 - Bug fix:  click on column caption doesn't sort the column if opened in detail view
================================================================================
Important changes and bug fixes in the release 671
================================================================================
- Bug fix: Command list in the "Define action toolbars" dialog is empty for some languages http://www.forum.freecommander.com/viewtopic.php?f=7&t=6134
- Bug fix: Favorite toolbar - drag&drop won't work for item at position 1 http://www.forum.freecommander.com/viewtopic.php?f=19&t=6102
- Bug fix: Layouts broken
- Changed: Tree option "Show floppy drives (A:,B:)" removed. The drives option "Don't show floppy drives" is valid for the tree too.

================================================================================
Important changes and bug fixes in the release 672
================================================================================
- Bug fix: Search in archives ignores timestamps between and not older options http://www.forum.freecommander.com/viewtopic.php?f=7&t=6153
- Bug fix: "Open location" in the search dialog highlights .. element (root) in folder were file was found, instead of highlighting required file http://www.forum.freecommander.com/viewtopic.php?f=7&t=6154
- Bug fix: Filter cannot use created/accessed date http://www.forum.freecommander.com/viewtopic.php?f=7&t=6155
- Bug fix: Tab can be closed when new tab created with double click http://www.forum.freecommander.com/viewtopic.php?f=7&t=6165
- Bug fix: Quick filter does not works properly for "Plain view - folders"
- Bug fix: 'Use current folder' option in pack/unpack dialog is saved but not restored
- Changed: Using slash char for creating folders is allowed now (works the same way as with backslash)  
- Implemented: Keyboard shortcut to copy MD5 sum to clipboard http://www.forum.freecommander.com/viewtopic.php?f=20&t=6151
- Implemented: Option 'ThumbsNoClipCaption' to define in the [Form] section. The value 1 draws caption without clipping. The user must self increase Y spacing.
 
================================================================================
Important changes and bug fixes in the release 673
================================================================================
- Bug fix: Search dialog - regular expression tooltip is dispayed after switching to other task http://www.forum.freecommander.com/viewtopic.php?f=7&t=6185
- Bug fix: Exception for delete operation on '..' item if "Use Windows" option is used http://www.forum.freecommander.com/viewtopic.php?f=7&t=6196
- Bug fix: 'Edit->Load selection from file' broken
- Bug fix: Return key may not work in main window if search dialog is open 
- Bug fix: Favorite item path is not expanded http://www.forum.freecommander.com/viewtopic.php?f=20&t=6203
- Implemented: New search option "Use for full subfolder path (otherwise only for subfolder name)"  
- Implemented: New properties to favorites added - sort and view type  
- Implemented: Customize toolbars dialog - 'Apply' button added
================================================================================
Important changes and bug fixes in the release 674
================================================================================
- Bug fix: Favorite tool does not work http://www.forum.freecommander.com/viewtopic.php?f=7&t=6236
- Bug fix: Move operation (FreeCommander dialog) for some relative paths does not work http://www.forum.freecommander.com/viewtopic.php?f=7&t=6238
- Bug fix: Recycle Bin does not open http://www.forum.freecommander.com/viewtopic.php?f=7&t=6225
- Bug fix: Exclude folder filter (RegEx) in the search dialog does not work properly http://www.forum.freecommander.com/viewtopic.php?f=7&t=6232
- Bug fix: New Word document in context menu creates a text file  http://www.forum.freecommander.com/viewtopic.php?f=22&t=6223#p19661
- Implemented: New options for adding folder paths in the search dialog
- Implemented: Search dialog - in 'File name' field you can define filters too (folder, timestamp, size)
- Implemented: "Auto save current layout" option for layouts - the selected layout is automatically saved on layout change and program end
- Implemented: New command line parameters: -layout= and -aslayout=
               -layout=asExplorer       - layout with the name "asExplorer" will be loaded on program start
               -aslayout="as Explorer"  - layout with the name "as Explorer" will be loaded on program start and "Auto save current layout" option activated  
- Changed: Layout restore with the option 'Close not locked tabs' or 'Keep all tabs' - now the tabs are merged and not added
================================================================================
Important changes and bug fixes in the release 675
================================================================================
- Bug fix: Multiple filters are ignored if space is used between filters http://www.forum.freecommander.com/viewtopic.php?f=7&t=6265
- Bug fix: Few problems with "Auto save current layout" mode fixed
- Implemented: Internal UNRAR plugin
================================================================================
Important changes and bug fixes in the release 676
================================================================================
- Bug fix: Invalid pointer operation in synchronize folders http://www.forum.freecommander.com/viewtopic.php?f=7&t=6282
- Bug fix: Search dialog http://www.forum.freecommander.com/viewtopic.php?p=19895#p19895
- Bug fix: UNRAR plugin does not work with encrypted archives
- Changed: Status bar height min value changed to 10 
================================================================================
Important changes and bug fixes in the release 680
================================================================================
- Bug fix: UNRAR plugin - password problem http://www.forum.freecommander.com/viewtopic.php?p=19945#p19945
- Bug fix: Invalid pointer operation in synchronize folders http://www.forum.freecommander.com/viewtopic.php?f=7&t=6298
================================================================================
Important changes and bug fixes in the release 681
================================================================================
- Bug fix: fc_internal_zip plugin does not work properly if encryption is active
- Bug fix: Unpack archive file ends with exception if only one pane is visible http://www.forum.freecommander.com/viewtopic.php?f=22&t=6319
- Bug fix: Name column auto resize works not properly http://www.forum.freecommander.com/viewtopic.php?f=7&t=6312
- Bug fix: Search gives locked files in results http://www.forum.freecommander.com/viewtopic.php?f=7&t=6321#p20016
- Bug fix: Problem with fc_internal_rar http://www.forum.freecommander.com/viewtopic.php?p=20038#p20038 
================================================================================
Important changes and bug fixes in the release 682
================================================================================
- Bug fix: Right mouse button selection in NC-Mode - context menu may appear on end of selection
- Bug fix: Column auto resize works not properly http://www.forum.freecommander.com/viewtopic.php?f=7&t=6347
- Bug fix: The drives order may be wrong if Windows Explorer shows the drive letter at the beginning of the drive name
- Bug fix: Password request while search in RAR archive is broken http://www.forum.freecommander.com/viewtopic.php?f=6&t=6281   
- Implemented: About dialog shows platform for both 32 and 64 bit
- Implemented: Text in version info field in about dialog is selectable now 
================================================================================
Important changes and bug fixes in the release 685
================================================================================
- Bug fix: Pack operation (fcZip) may fail without error info
              
 