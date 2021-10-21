# OpenXTalk macOS Font Tools
OpenXTalk Font related stuff for macOS

FontTools.lcb

A LiveCode Builder library for Font related LCB handlers that utilize macOS APIs. 
Currently this has only one useful handler, GetFontURLs(), which returns a line-delimited URL list of the Fonts currently in use. The URLs include the file:// path URL as well as the Font's postscript name tacked on the the end of the path (seperated by the # character). This operates slightly differently from LiveCode's built-in Font stuff.



GetFontNames.livecode

Test LiveCode Stack showing a few examples of usage of FontTools.lcb. There's also some examples of using the built-in LiveCode Font functions. This can be useful for doing things like copying invisible Font-Sync-cache files from hidden directories that a certain graphics company's software uses to store on the fly online font syncing caches.
