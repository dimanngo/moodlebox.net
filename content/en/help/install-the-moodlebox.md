---
title: How to install the MoodleBox
authors:
  - Nicolas Martignoni
type: kb
date: 2017-09-15
lastmod: 2019-04-15
description: The procedure to install the MoodleBox for its first utilisation is described here
slug: install-the-moodlebox
weight: 1
categories:
  - First steps
aliases:
  - ../install

---
This is the procedure to install the MoodleBox for its first utilisation.

### Step 1: Buy the hardware

The [stuff you will need][1] to build your MoodleBox is essentially a Raspberry Pi Model 3B or 3B+ with a power supply and a MicroSD card. [More information here][1].

### Step 2: Download the MoodleBox disk image

The [MoodleBox disk image][2] is available [here][2].

### Step 3: Copy the disk image on your MicroSD card

For this operation, use preferably [balenaEtcher][10]. [More information here][3].

### Step 4: Startup your MoodleBox

Insert your microSD card into the Raspberry Pi 3 slot and power it up. The red LED lights up, and after a few seconds the green LED lights up intermittently. If desired, connect the MoodleBox to the network or to an Internet router with an Ethernet cable to allow connected devices to access the Internet.

There is no other manipulation to do: after the boot, your MoodleBox is ready and totally functional.

### Next steps

  * [Wi-Fi connection][5]
  * [Access to Moodle][4]
  * [Change the main password][11]
  * [Wi-Fi configuration][6]
  * [SSH access][7] to the MoodleBox
  * [Support the MoodleBox project][8]

For more information, browse the [knowledge base][9].

 [1]: {{< relref "hardware.md" >}}
 [2]: {{< relref "download-the-disk-image.md" >}}
 [3]: {{< relref "copy-the-disk-image.md" >}}
 [4]: {{< relref "access-to-moodle.md" >}}
 [5]: {{< relref "wi-fi-connection.md" >}}
 [6]: {{< relref "wi-fi-configuration.md" >}}
 [7]: {{< relref "command-line-access.md" >}}
 [8]: {{< relref "/support-moodlebox.md" >}}
 [9]: {{< relref "/help" >}}
 [10]: https://www.balena.io/etcher/
 [11]: {{< relref "/change-password.md" >}}
