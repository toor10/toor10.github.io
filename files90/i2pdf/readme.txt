i2pdf 1.0
(C) 2009-2011 LMG Software


*** INSTALLATION

Unzip the archive in a folder of your choice.

You will find three files: i2pdf.exe (the program), i2pdf.chm (the help file) and readme.txt. 

You can create a shortcut to i2pdf.exe in the usual way. 

Run i2pdf.exe. 

A configuration file, i2pdf.ini, will be created after the program is closed for the first time. 

You can always delete this file safely if you want to restore i2pdf to its default values.


*** LICENSE       

i2pdf is FREEWARE !

You can use and distribute freely this software but you should not alter it in any way or sell it, alone or with other software.
The program is distributed "AS IS". No warranty of any kind is expressed or implied. You use it at your own risk. 
The author will not be liable for data loss, damages, loss of profits or any other kind of loss while using or misusing this software.


*** HISTORY

1.0.46 Jul 18, 2014 (PB 5.30)
* Removed the executable packers, some minor cosmetic fixes.

1.0.43 Sep 21, 2011 (PB 4.51)
! Fixed the saving of the window's coordinates when quitting the program while minimized. 

1.0.40 May 22, 2011 (PB 4.51)
+ Added the ability to skip the resize of an image if its width in pixel is less than a certain value (suggested by Wayne).
! Some small fixes (mostly cosmetic).

1.0.38 Mar 16, 2011 (PB 4.51)
! Fixed the "Remember window position" option (functionality altered in 1.0.37).
* Made the program a little more friendly when the display is set at higher DPI settings (reported by Wayne).

1.0.37 Mar 7, 2011 (PB 4.51)
+ Added an option to save the PDF to the same dir of the dropped files if they are all coming from a single dir (suggested by Patrick).
+ Added the total size of the dropped files near the label of the files count.
* Moved the reminder for the JPG storing mode from the background to the bottom right.
+ Now you can remove one or more files from the list pressing the [Del] key.
! Fixed a DIV by ZERO happening sometimes on very fast hardware.
! Fixed the fact a ".PDF" wasn't appended to the output file name in some cases (filenames with dots).
! Fixed some cosmetic sizing problems at the startup.

1.0.30 June 23, 2010 (PB 4.50)
+ When a single image is dropped, the default name of the PDF file will be taken from the image file name minus the extension (suggested by Melissa).

1.0.29 May 19, 2010 (PB 4.41)
! Implemented a check to accept only 24 bpp JPG images if JPG storing mode is enabled (other depths were erroneously accepted, resulting in pages not viewable).

1.0.28 May 16, 2010 (PB 4.41)
! Fixed the lock of the image files when the JPG storing option was enabled.
+ Added a message in the log when the JPG storing option is enabled.

1.0.27 May 16, 2010 (PB 4.41)
! Fixed a rounding error in the display of the free memory shown while building the PDF.

1.0.26 March 28, 2010 (PB 4.41)
+ Added a reminder to the main window when the JPG storing option is in effect.

1.0.25 March 27, 2010 (PB 4.41)
+ Added an option to store JPG images in the resulting PDF without reprocessing them (suggested by Tomas).
! Fixed the darker edge shown on two of the four sides of an image when a format different from Paperless was used.
! Fixed the positioning of the scroll bar in the last tab of the settings' window.

1.0.23 December 20, 2009 (PB 4.40)
! Fixed the program's attempt to launch a PDF when the file was not created for some reason.
! Fixed the inconsistent behavior of the progress bars under Windows Vista and Windows 7.
! Fixed the positioning of the thumbnail window under Windows Vista and Windows 7 with Aero enabled.

1.0.20 November 4, 2009 (PB 4.31)
+ Added ability to drop not only files but folders too (with optional recursion for the subfolders).
+ If a single folder is dropped, the default name for the PDF file will be taken from the folder's name.
+ Added to the statusbar the number of files currently loaded.
+ Added a progress bar even if image preprocessing is disabled.
+ Double click on the status bar act as a shortcut to the Options window.
+ Added the ability to move a group of selected files to the top or bottom of the list.

1.0.15 August 19, 2009 (PB 4.31)
+ Added the statusbar with the current values of the "PDF Creation" options.
! Fixed a leakage in GDI resources causing a decrease of the available memory over time.
! Removed the need to click once to make the mouse wheel works in the Options window.
! Fixed log generation in case all file processed where skipped, damaged, missing or whatever.
! Fixed log counters to count as processed only the files successfully added to the PDF.

1.0.13 April 1, 2009 (PB 4.30) 
! Fixed the trapping of errors caused by corrupted image files.
! Fixed the cursor change in proximity of the listview header erroneously suggesting a manual column resize was possible.

1.0.12 internal beta (PB 4.30)
+ Added a log of the files added, skipped or missing, and other more or less useful information.
+ Added the option to automatically delete the log if the PDF is created without errors.
+ Added an option to enable/disable the image preprocessing.
+ Added the ability to export the list of files skipped in the preprocessing phase.
+ Added an option to include the full path of the files in the sort.
+ Added a runtime check to limit i2pdf to only one instance.
* Changed the style of the thumbnail window to #WS_EX_TOOLWINDOW
+ Added two checkboxes to make the storing of author and document title in the .ini file optional.
+ Added the option to automatically set the document title from the name of the output file (minus the ".pdf").

1.0.9 internal beta (PB 4.30)
! The save dialog is now showed again when the user choose to not overwrite the destination file.
! Fixed a bug in the sort of files coming from different directories.

1.0.8 internal beta (PB 4.30)
* Reworked the error handling routines.
+ Added more thorough checking of the GDI+ error codes.

1.0.7 internal beta (PB 4.30)
! Fixed a bug in the list ordering in case of multiple drag and drop operation.
! Fixed a bug occurring when canceling the preprocessing of the dropped files.
* Changed the way a near zero memory condition is treated.

1.0.6 internal beta 
First usable beta.