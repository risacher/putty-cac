PuTTY-CAC
=========
Secure shell client with support for US Gov't Smartcards and other X.509 certificates.

This is a fork of PuTTY. It breaks much of the delictious goodness of
the original PuTTY, in that it only builds for Windows, and is only
known to build correctly with Microsoft Visual C, at this time.

But it supports the DoD Common Access Card (CAC) and a number of other smartcards.  

PuTTY-CAC is now updated to 0.67 and is in sync with the latest PuTTY
Suite 0.67. PuTTY 0.67, fixes a security hole in 0.65 and 
before: vuln-pscp-sink-sscanf. It also contains a few other small bug fixes.

Source(s):
http://www.chiark.greenend.org.uk/~sgtatham/putty/ 
(Original PuTTY was developed by Simon Tatham.)
Source: http://www.risacher.org/putty-cac/
(PuTTY-CAC was developed by Daniel Risacher.)

WARNING: The PKCS11 API originally from PuTTY-SC has been removed 
from all applications in this PuTTY-CAC Suite. However, CAPI support 
is still functional which is the main premise behind PuTTY-CAC anyways. 
If you need to use PKCS11 then DO NOT DOWNLOAD THIS VERSION. Download 
an older release of 0.62 which has support for PKCS11. If you do not 
know what I am talking about then this release should be fine for your needs.

I have included compiled versions of the PuTTY-CAC suite that can be 
found in the EXECUTABLES folder for each type listed above for those 
that do not want to compile the code. However, these compiled 
applications may only work on Windows 7/8/10. They have not been tested 
on older OS’s such as Vista/XP.

If you choose to compile the source code yourself you will need
to use the MakeFile.vc as I did not update the other MakeFile.* files.