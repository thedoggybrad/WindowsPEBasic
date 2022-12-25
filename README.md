# WindowsPEBasic
It is a barebones Windows 11 22H2 Pre-installation Environment (PE).
<br>
## Introduction
Windows PE Basic
<br>
-Based on Windows 11 22H2 PE and only supports 64 bit processors.
<br>
-Uses CMD as its user interface (But can access files some GUI apps)
<br>
-Can access some Windows Tools like Diskpart, SFC, DISM, Notepad, Registry Editor and many more....
<br>
-Created using Windows ADK + Windows PE Addon
<br>
-Raw Output from the Windows ADK and immediately converted into an .ISO file
<br>
-Can be used for troubleshooting and fixing broken Windows Installations
<br>
-Compatible with incompatible devices that are incompatible to Windows 11
<br>
<img src="https://thedoggybrad.github.io/WindowsPEBasic/WinPE.png">
<br>
Screenshot provided by ©Microsoft Corporation.
<br>
<br>
## Download
Download Link: https://github.com/thedoggybrad/WindowsPEBasic/releases/download/WinPEBasic/WindowsPEBasic.iso
<br>
<br>
Note: It is not the Windows Recovery Environment. It is just the Windows PE.
<br>
<br>
## System Requirements
WindowsPEBasic has the same requirements as Windows 10 with these exceptions:
<br>
<br>
•No hard drive is required. You can run Windows PE entirely from memory.
<br>
•It requires only 512MB of memory.
<br>
•In order to boot Windows PE directly from memory (also known as RAM disk boot), a contiguous portion of physical memory (RAM) which can hold the entire Windows PE (WIM) image must be available. 
<br>
•The 32-bit version of Windows PE can boot 32-bit UEFI and BIOS PCs, and 64-bit BIOS PCs.
<br>
•The 64-bit version of Windows PE can boot 64-bit UEFI and BIOS PCs.
<br>
<br>
## Why I created this?
Instead of you downloading Windows ADK and its Windows PE add-on and the compiling the output, I decided to upload a compiled version already for everyone to use.
<br>
<br>
## Resources and Links
Resource I used to create this: https://youtu.be/HBFukw1hkKY
<br>
<br>
More about Windows PE: https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/winpe-intro?view=windows-11
