To build WebImage, the FrameWrk sample must first be built. First run 
\inetsdk\setenv.bat to be sure the ActiveX SDK include, bin, and lib
directories are included (first) in your environment. Run the 'nmake'
to build a debug version (built to the Debug subdirectory) or
'nmake nodebug=1' to build a retail (nodebug) directory into the
Retail subdirectory.

After building the FrameWrk library you can build the WebImage 
control by running 'nmake' or 'nmake nodebug=1'.
