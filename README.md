Windows Native Guifications Themes
==================================

V1.1
By BoffinbraiN
http://boffinbrain.deviantart.com


Introduction
------------

Thanks for trying these themes.  I hope you find them beautiful and massively useful.  All notification types that the plugin supports, including new e-mail notifications, are available.

I have very high standards, and I'm very proud to use these themes on a daily basis.  I would certainly hope you don't find any faults in my work!  But, if you do, then I welcome your feedback either on deviantART via a note or comment, or add a comment to the tracker on SourceForge.


Installation
------------

Every Guifications theme is located in the Themes directory inside your Pidgin user directory.  To get there, browse to:

- Windows XP: `C:\Documents and Settings\<your username here>\Application Data\.purple\guifications\themes`
- Windows 7:  `C:\Users\<your username here>\AppData\Roaming\.purple\guifications\themes`

If you've just installed Pidgin or Guifications, make sure it is running and the plugin is enabled, otherwise the directory may not exist yet.

Extract the 'themes' directory from this archive and move all the contents there, so that all the theme names are visible under 'themes'.

Then, just go to the Guifications options window via the Plugins window, to see the list of available themes (refresh if the window is already open).  Unless you want to do advanced per-user theming, make sure only one theme is enabled - this will make sure the correct one is used.

One final note: these themes have only been tested on Windows. The Windows 10 themes reference the Segoe UI font, which probably won't exist on Linux distributions.


Customisation
-------------

Need to fine-tune your own colour scheme, or add other personal touches?  I've given you all the files you need to get started!  They're in the `source` directory.

Every theme file is derived from one of three theme XML files.  The layout for all Windows XP and Windows 7 themes is the same; only the text colours change (the Windows 10 themes have more padding).  Select the most suitable one based upon the average brightness of the background image:

- Light: black headings, dark grey text
- Mid: white headings, black text
- Dark: white headings, light grey text

All images are made from pages and layers in the source.png file - an Adobe Fireworks CS3 file.  If you have Fireworks, you can modify layers and export to make a derivative theme. The Windows 10 images are not provided in the source because they are literally flat colours - you can alter an existing background in Paint or any other program.

Be careful with transparency - it looks like any alpha value that is less than 100% is rendered completely transparent by Windows, and for that reason, none of my themes use translucent backgrounds.  If you know why, or better still, have a workaround, let me know!


Version History
---------------

- V1.0 2012-02-11 - Initial release with 6 themes for Windows XP and 8 colours for Windows Vista and 7
- V1.1 2015-08-25 - No changed to existing themes, but added 9 flat colour themes for Windows 8 and 10