---
layout: post
title:  "DOS Disk Dumper by NCommander"
date:   2026-02-15
tags: dos utility imaging
toc: false
---

[DOS Disk Dumper][1] by [NCommander][2] is standalone DOS utility designed to image a HDD to an image file, it essentially treats the disk as one 'block device', using the hardware level routings built into the Motherboards ROM, to image the disk at the block level.

**Licence:** [BSD-2-Clause license][3]

**Intended User**<br>Designed for digital archiving, preservation and restoration of MS-DOS/Win3x systems by Intermediate & Advanced Users.

## Compatibility
From my understanding, due to the way the program is written, compatibility with DOS versions is irrelevant. Although I have tested it on MS-DOS 5 & 6.22 currently.

## Example Display
<figure><img src="/assets/media/dos_disk_dumper/ncommander_intel486_screen.png" alt=""/>
<figcaption>YouTube - <a href="https://youtu.be/ywCRGrwVrEA">486 Data Recovery with MSBACKUP and NetWare - Intel Professional Workstation (Part 2)</a></figcaption></figure>

## Usage
<div style="background-color:#000;padding:5px;text-align:center;">
<br>
<video controls>
  <source src="/assets/media/dos_disk_dumper/diskdump.webm" type="video/webm" />
  Download the <a href="/shared-assets/videos/flower.webm">WEBM</a> video.
</video>
</div>
**Note:** Video recorded using 86box on MS-DOS 5, speeds of imaging and disks may vary depending on your physical hardware and configuration.

### Command Flags

There are none, not in this early version of the program. ``diskdump /?`` will just run the program normally there is no help flag.

## Sequence Diagram
<img src="/assets/media/dos_disk_dumper/sequence_diagram.svg" alt="" style="max-width: 90%;margin:0 auto;text-align:center;display:block;" />

## Links
- Github - [NCommander DOS Disk Dumper][1]
- Tech Tangent [Chaplet Halikan Manual Scanning](https://youtu.be/8ZOAIpvLo8Q?t=8760) - Shelby used Disk Dumper to image the 40M HDD of this rare vintage laptop to a USB flash drive.

[1]: https://github.com/NCommander/dos_disk_dumper
[2]: https://www.youtube.com/c/NCommander
[3]: https://github.com/NCommander/dos_disk_dumper/blob/master/COPYING