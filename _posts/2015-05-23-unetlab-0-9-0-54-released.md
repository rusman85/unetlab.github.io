---
layout: post
published: true
title: "UNetLab 0.9.0-54 Released"
excerpt:
  "What's new on UNetLab 0.9.0-54 (beta)."
section: "Release"
authors:
- andrea
tags:
- UNetLab
- Beta
- Release
---
Fixed on this release:

* IOU/IOL nodes do not crash anymore enabling IS-IS protocol.
* IOU/IOL nodes do not stop if `stop all` button is pressed (issue is still present if serial links are used).
* Fixed network issue on Cisco CSR routers.
* Adding multiple networks/nodes work as expected.
* ASAv now use serial console (see [Adding Cisco ASAv images](/2015/06/adding-cisco-asav-images/ "Adding Cisco ASAv images") post).

New features:

* Authentication with multi user support (default username is `admin` with password `unl`).
* Initial config support for both IOU/IOL and Dynamips nodes.
* Errors should report a better description. 
* Default QEMU is now 2.3.0.

New supported images:

* Cisco Sourcefire
