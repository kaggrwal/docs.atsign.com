---
layout: list

title: "IoT Devices" # The title (ON THE PAGE)
lead: | # The lead below the title (ON THE PAGE)
  Add end-to-end security to your IoT devices with the atPlatform.

description:
  | # SEO Description of the page (Shows in google and atsign.dev search)
  Get started with IoT (Internet of Things) devices on the atPlatform

draft: false # Change this to "true" to hide the page
toc: true # Change this to "false" to hide the table of contents
autolinks: true # Change this to "false" to hide the automatic links below your content
weight: 3
---

## What is IoT?

IoT–Internet of Things–is a system of interconnecting devices, mechanical or electronic, that are designed to work together to provide a service, such as the transmission of information, or the control of a device.

In simple terms, an IoT device is any device (such as a camera, a smart phone, a thermostat, a TV, a computer, etc) that is connected to the internet. IoT devices have sensors that are always collecting data and sending it through the Internet. However, these data are usually precious data that are valuable to the owner. For example, a person may own a camera connected to the internet which is constantly surveilling the living room of their house. It is important that outside parties have no access to this data and that the data the camera is collecting is sent securely over the internet. This is where the atPlatform comes in. The atPlatform adds security to this IoT camera device and sends the data securely to whomever the owner chooses.

As said on our website [atsign.com](https://atsign.com/iot-internet-of-things/#overview), the atPlatform strips things down to the protocol level, creating both zero trust and zero configuration environments–completely without passwords–eliminating all attack surfaces created by over-complexity, and simplifying the administration of devices in the process.

## atPlatform

The atPlatform is a free, open-source, platform with the capabilities to add end-to-end security to your IoT devices. Check out our [Tools and Demos](https://atsign.com/iot-internet-of-things/#tools) page to see how we are adding end-to-end security to our IoT devices. 

In most demos, a raspberry-pi is used to act as the IoT device. The R-PI runs the atPlatform via Dart where the atSign associated with the IoT device sends the data end-to-end encrypted to another atSign which is running a Flutter app.

IoT Network Architecture

{{< image type="page" src="atIoT-Network-Architecture-1.png.webp" >}}

## Ssh! No Ports

Ssh! No ports is a perfect demonstration of how the atPlatform is adding end-to-end security to your IoT devices.

Want to ssh to your remote (IoT or non-IoT) device without it having any open ports?

See our Ssh! No Ports tutorial:

{{< card/breadcrumb href="/tutorials/sshnp/1-prerequisites/" first="Ssh! No Ports" >}}

## Contact us

Here at Atsign, we believe in a world where IoT devices have atSigns and send their data end-to-end-encrypted to other atSigns. We'd love to work with you on adding security to your IoT devices. Please contact us at [info@atsign.com](mailto:info@atsign.com) or join our [discord](https://discord.gg/55sHTQFxfz) 
and ask us about anything and we will be happy to answer!