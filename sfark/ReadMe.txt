sfArk SoundFont Compression
Copyright 1997-2001 Melody Machine
Website: www.melodymachine.com
Support & comments: sfark@melodymachine.com
===========================================

What is sfArk?
==============
sfArk is a program for compressing SoundFont (sf2) files.  The compression is LOSSLESSS - absolutely no reduction in sound quality occurs.  After compressing then uncompressing, the resulting file is identical to the original.  Compressed files are typically 35-65% of their uncompressed size.  sfArk is free for non-commercial use.

Why use sfArk?
==============
Because SoundFont files are often large (several MB) using sfArk can significantly reduce disk space, bandwidth and transfer times.  sfArk offers considerably better compression performance than conventional compression tools such as Zip/WinZip.

What's new in this version?
==========================
If you've previously only used Version 1.x, then a lot is new.  sfArk version 2 is much faster than version 1, and provides significantly better compression, plus an improved user interface.  If you've previous used version 2, this release adds support for creating "self-extracting" files, and has a number of other minor improvements and bug fixes.  See "Update History" below for the complete list.

Obtaining the latest version of the program
===========================================
Visit the melodymachine.com website for information on upgrades and additional sfArk products.  Also, you can be kept informed of new releases by joining our mailing list - Send an email to sfarklist@melodymachine.com with a subject of "join".  Mailings are infrequent (rarely more than once overy few months) and we won't give your email address to anyone else.

Installing & Removing
=====================
This version comes with automatic setup and remove utilities.  Some notes:

* If you have installed sfArk v1.x, you can install V2.x without removing V1.  However, if you subsequently remove V1, you will lose file associations between sfArk and SoundFont (sbk/sf2) files.  You can re-install these file associations by clicking the sfArk.reg file which is included with this distribution, or by running the "Re-install sfArk file associations" link which should appear in the sfArk group on your Start menu.  Alternatively, simply re-install sfArk V2.

* When installing, you should accept the default location of C:\Program Files\sfArk.  If you install to a different location, then File Associations will not work.  You can correct this in several ways: (a) Edit settings for file types .sfArk, .sbk and .sf2 from Explorer's View/Folder Options/File types (b) Correctly locate sfArk.exe and sfArkXTc.exe when Windows asks (c) Edit the file sfArk.reg and replace all occurences of C:\Program Files\sfArk with the location you choose, then save the file and merge it into the registry by clicking it in Explorer.

Known issues
============
1. Included help file is from sfArk v1.x and has not yet been updated for V2.  However, much of the information in the help file remains relevant, and most people won't need the help file anyway.

2. When uncompressing a sfArk v1.x file, the progress display is not updated correctly.  This is not really noticable except with large files (or very slow machines).

Self-extracting Files
=====================
"Self-extracting" files can be created.  This means that the decompression program is actually included as part of the compress file - simply running the file extracts the original soundfont.  To create a self-extracting file from within the program, first select a sfArk file then choose "Create self extracting file" from the File menu.  The installer also adds this option to Explorer's right-click menu for sfArk files.

WebMasters please note
======================
sfArk v2.x can uncompress files created with sfArk v1.x.  If you are a web-master *please* take the time to convert any .sfArk files on your site to V2 format.  This is because forthcoming sfArk add-ons (including Mac and Linux based decompressors, and the existing sfArkXTc utility do NOT support the older V1 format.

Programmers please note
=======================
We have available a DLL which makes it easy to add sfArk compression & decompression to your application.  For further information visit the melodymachine.com website, or email sfark@melodymachine.com.  For most applications, you can use and distribute the sfArk DLL free of charge.

Other Applications that support sfArk
=====================================
At the time of writing sfArk SoundFont Compression technology is already supported by:
* Alive SoundFont Editor - www.soundfaction.com
* AWave sound file editor/convertor - www.fmjsoft.com

Commercial Use
==============
This freeware version of sfArk is NOT licensed for commercial use.  For a description of what we mean by commercial use, please read the license agreement.  If you are uncertain whether your use would be regarded by us as commercial or not, please email us: sales@melodymachine.com

There are now several commercial users of sfArk who have integrated sfArk compression technology with their own systems.  Compressed files reduce download times, net traffic and disk space - reducing costs and customer frustration caused by long download times.  To discuss your requirements please email sales@melodymachine.com.

Future Plans
============
sfArk will shortly support many other sound file formats apart from SoundFonts.  Included will be wav, GigaSampler, DLS and others.  There will also be decompression utilities for Mac and Linux platforms.

Quickstart Guide
================
The setup program adds a number of Windows shell extensions.  Assuming you have used the setup program you can right-click existing .sf2 or .sfArk files in Explorer (etc) to compress/uncompress them.

You can also process files by starting the sfArk program and using drag & drop onto the main open program.

Update history
==============
v2.15 21-November-2001 - Offical Release
Added "Create self-extracting file" function
Bug which caused the program to crash after uncompressing a file created with sfArk V1.x is now fixed.
Several minor bug fixes
Default directory is now "My Documents"

Acknowledgements
================
"soundfont" is a trademark of E-MU Systems.

"sfArk" and the sfArk logo are trademarks of melodymachine.com
