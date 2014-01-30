# A Sublime Text 2 Build Script for Matlab.

A collection of sublime-build scripts which allow Sublime to run headless Matlab scripts directly.

1. From within Sublime Text 2, go to Tools → Build System → New Build System.
2. Copy the contents of a *-Matlab.sublime-build file that is appropriate for your system and paste it into this window.
    - Replace the path for Matlab to the appropriate location on your computer. For example, `/usr/local/MATLAB/R2012a/bin/matlab`, `C:/Program Files (x86)/Matlab/bin`, or `/Applications/MATLAB_R2012a.app/bin/matlab`
    - Edits may need to be made to the additional parameters if you are not running the same Matlab version specified in the filenames (i.e. 2012a, 2012b, 2013a, etc.).
3. Save.

The Linux variant I am using in tandem with this build file is Ubuntu 12.04.

This code is MIT licensed.
