# LCMacFontStuff
LiveCode Font related stuff for macOS

FontTools.lcb 
A LiveCode Builder library for Font related LCB handlers. 
Currently this has only one useful handler, GetFontURLs(), which returns a line-delimited URL list of the Fonts currently in use. The URLs include the file:// path URL as well as the font postscript name tacked on the the end of the path (seperated by the # character).

GetFontNames - Test LiveCode Stack showing a few examples of usage of FontTools.lcb, as well as using the built-in LiveCode Font functions.
