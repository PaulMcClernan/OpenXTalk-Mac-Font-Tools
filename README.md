# OpenXTalk macOS Font Tools
OpenXTalk Font related stuff for macOS

FontTools.lcb

A Extension Builder library for Font related xBuilder handlers that utilize macOS APIs: CoreText, NSFontManager, etc.
The first handler added to the library was GetFontURLs(), which returns a line-delimited URL list of the Fonts currently in use. The URLs include the file:// path URL as well as the Font's postscript name tacked on the the end of the path (seperated by the # character). This operates differently from the OXT community engines built-in Font stuff.

NOTE: .oxtstack is compatible with .livecode v9.x stack format

Tester.oxtstack 

Tester stack in the 'samples' folder is the main test stack for testing the  library, accessible by right-clicking the extensiopn in the list in Enxtension Manager stack in the OXT IDE. It contains simple buttons that call the handlers of the library and 'put' the result into the message box.

The Experiments folder contains various test stacks, some of which use methods other than xBuilder extension to retrieve information about fonts, which may not be specific macOS. For example some stacks in this folder may use FontConfig fc-list or fc-scan commonly found pre-installed in Linux Distrobutions (FontConfig can also be installed on macOS via HomeBrew or MacPorts). On macOS the command line tools system_profiler and mdls, which come with the OS, may also be used to retireiveing font meta data information.

GetFontNames.oxtstack 

OpenXTalk Stack showing a few examples of usage of FontTools.lcb. There's also some examples of using the built-in Font functions. This can be useful for doing things like copying invisible Font-Sync-cache files from hidden directories that certain graphics company software uses to store on the fly online font syncing caches.
