# A Sublime Text 2 Build Script for Matlab.

1. From within Sublime Text 2, go to Tools->Build System->New Build System
2. Copy the contents of a *-Matlab.sublime-build file that is appropriate for your system and paste it into this window. If you are not running R2012a, then make edits accordingly.
3. Replace "/usr/local/MATLAB/R2012a/bin/matlab" or "/Applications/MATLAB_R2012a.app/bin/matlab" with the path to your Matlab program.
4. Save.
5. This should make Sublime build .m files automatically from within Sublime.

Let me know if something doesn't work right for you. I have not tested this code on Windows or with any version of Matlab besides R2012a. The Linux variant I am using in tandem with this build file is Ubuntu 12.04.


This code is MIT licensed.
