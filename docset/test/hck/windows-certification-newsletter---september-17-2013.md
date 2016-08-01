---
author: joshbax-msft
title: Windows Certification Newsletter - September 17, 2013
description: Windows Certification Newsletter - September 17, 2013
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 430f83d3-7621-4445-95e7-b82676d10a50
---

# Windows Certification Newsletter - September 17, 2013


This newsletter provides up-to-date news about the Windows Certification (formerly Logo) Program and often provides info you can't get anywhere else. Did you get this from a friend? [Subscribe now](http://go.microsoft.com/fwlink/p/?linkID=313282) so you don't miss any important updates or changes.

## In this issue


[Hardware certification policies and processes update](#hardware913)

[The Fast Track program](#fast913)

[RTM version of the Windows HCK for Windows 8.1 available](#rtm913)

[HCK 2.0 will retire on November 30](#hck913)

[HCK QFE 02 for Windows 8.1 RTM now available](#qfe913)

## <a href="" id="hardware913"></a>Hardware certification policies and processes update


Take a look at the updated Windows Hardware Certification Policies and Processes document for certification testing policies, information about product submission, and business requirements.

## <a href="" id="fast913"></a>The Fast Track program


The Fast Track program to make your drivers available for Windows 8.1 is the quickest method to ensure that your customers have the right drivers for the new release. By making these drivers available on Windows Update, you can help ensure that our joint customers will automatically receive the correct driver after they upgrade to Windows 8.1. We expect that most Windows 8 users will upgrade their systems with the free Windows 8.1 update.

To those partners who have already used this program and are ready for launch, thank you. If you haven’t, read on to learn how to participate and provide the best possible user experience.

You can fast-track Windows 8 certified devices listed in the table below for Windows 8.1 certification if:

-   The device was previously certified for Windows 8.

-   The device's binaries haven't changed since the submission for Windows 8, and only the INF is updated to reflect the new Windows version.

If the device meets these criteria, here's how you can create a submission:

1.  Use the new Windows HCK for Windows 8.1, create a Windows 8.1 project, and run the Device.DevFund INF test.

2.  Use the Windows Dev Center hardware dashboard to package the results for submission upload.

3.  Include the previous Windows 8 submission ID in the README file.

4.  Reference errata ID 2657, "Windows 8 to Windows 8.1 driver certification update special," in the README file.

Submissions are reviewed for these items:

1.  The earlier Windows certification is referenced in the README file.

2.  The DevFund INF test passes.

3.  No driver binary changes occurred. (We test this by using WinDiff.)

If the review is successful, the submission is free.

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th>Certified Windows 8 devices and drivers that you can resubmit for Windows 8.1 using the plan above</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Digital Video Camera</p></td>
</tr>
<tr class="even">
<td><p>Digital Media Renderer</p></td>
</tr>
<tr class="odd">
<td><p>Digital Still Camera</p></td>
</tr>
<tr class="even">
<td><p>Distribution Scan Management Enabled Device</p></td>
</tr>
<tr class="odd">
<td><p>Enterprise WSD Multifunction Printer</p></td>
</tr>
<tr class="even">
<td><p>Game Controller</p></td>
</tr>
<tr class="odd">
<td><p>Generic Controller</p></td>
</tr>
<tr class="even">
<td><p>Graphics Tablet</p></td>
</tr>
<tr class="odd">
<td><p>Hard Drive – HDD, SSD</p></td>
</tr>
<tr class="even">
<td><p>LAN</p></td>
</tr>
<tr class="odd">
<td><p>LCD</p></td>
</tr>
<tr class="even">
<td><p>Monitor</p></td>
</tr>
<tr class="odd">
<td><p>Multifunction Printer</p></td>
</tr>
<tr class="even">
<td><p>Optical Drive</p></td>
</tr>
<tr class="odd">
<td><p>Pen Digitizer</p></td>
</tr>
<tr class="even">
<td><p>Printer</p></td>
</tr>
<tr class="odd">
<td><p>Removable Storage</p></td>
</tr>
<tr class="even">
<td><p>Router</p></td>
</tr>
<tr class="odd">
<td><p>Scanner</p></td>
</tr>
<tr class="even">
<td><p>SDIO Controller</p></td>
</tr>
<tr class="odd">
<td><p>Signature Tablet</p></td>
</tr>
<tr class="even">
<td><p>Smart Card</p></td>
</tr>
<tr class="odd">
<td><p>Smart Card Reader</p></td>
</tr>
<tr class="even">
<td><p>Storage Array</p></td>
</tr>
<tr class="odd">
<td><p>Storage Controller (Client)</p></td>
</tr>
<tr class="even">
<td><p>Storage Spaces Adapter (Client)</p></td>
</tr>
<tr class="odd">
<td><p>Storage Spaces Drive</p></td>
</tr>
<tr class="even">
<td><p>Storage Spaces Enclosure</p></td>
</tr>
<tr class="odd">
<td><p>Touch</p></td>
</tr>
<tr class="even">
<td><p>Touch Monitor</p></td>
</tr>
<tr class="odd">
<td><p>USB Hub</p></td>
</tr>
<tr class="even">
<td><p>WSD Multifunction</p></td>
</tr>
<tr class="odd">
<td><p>WSD Printer</p></td>
</tr>
<tr class="even">
<td><p>WSD Scanner</p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="rtm913"></a>RTM version of the Windows HCK for Windows 8.1 available


You can now download a new version of the Windows Hardware Certification Kit (HCK). This release of the HCK includes all QFEs released since the release of HCK for Windows 8.1 Preview, plus additional test fixes that didn’t make it into a QFE release. [You can download the kit here](http://msdn.microsoft.com/windows/hardware/bg127147).

## <a href="" id="hck913"></a>HCK 2.0 will retire on November 30


We’d like to remind our partners that HCK 2.0 submissions to the Windows Dev Center hardware dashboard will no longer be accepted after November 30, 2013.

## <a href="" id="qfe913"></a>HCK QFE 02 for Windows 8.1 RTM now available


For information about QFE updates, see [Windows Hardware Certification Kit QFE Updates](windows-hardware-certification-kit-qfe-updates.md).

To get the latest QFEs for the Windows HCK, run [HCKSetup.exe](http://msdn.microsoft.com/windows/hardware/bg127147). The Windows HCK download includes all previous QFE updates.

[Windows Hardware Certification Kit QFE Updates](windows-hardware-certification-kit-qfe-updates.md)

[Download and install HCK to get the QFE](http://msdn.microsoft.com/windows/hardware/bg127147)

[Download the QFE now](http://msdn.microsoft.com/windows/hardware/bg127147)

**Note**  
Before applying the QFE, close all active DTM Studio sessions. Applying this QFE might affect in-progress submissions, so please complete any submissions before applying the QFE. After installing this QFE, you'll need to regenerate any affected submission that was generated before the QFE was installed.

 

## Related topics


[Hardware Dev Center](http://msdn.microsoft.com/en-US/windows/hardware/)

[Windows hardware development kits and tools](http://msdn.microsoft.com/windows/hardware/bg127147)

[Windows hardware development samples](http://code.msdn.microsoft.com/windowshardware/)

[Windows Hardware Certification](http://msdn.microsoft.com/en-US/windows/hardware/gg463010)

[Newsletter archive](windows-certification-newsletter-archive.md)

[Your dashboard](https://sysdev.microsoft.com/hardware/member/)

[Getting started](http://msdn.microsoft.com/library/windows/hardware/gg507680/)

 

 






