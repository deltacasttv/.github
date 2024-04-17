[Who is DELTACAST?](#who-is-deltacast)

[What is DELTACAST VideoMaster?](#what-is-deltacast-videomaster)

[What is DELTACAST VideoMasterIP?](#what-is-deltacast-videomasterip)

[How to get VideoMaster and VideoMasterIP software?](#how-to-get-videomaster-and-videomasterip-software)

[What is hosted on this GitHub?](#what-is-hosted-on-github)

# Who is DELTACAST?

<p align="center">
   <img src="img/deltacast_logo.png" width="600">
</p>
We are a Belgian company designing and selling hardware and software video products.

</br>

DELTACAST devices and software components mainly intend to bring in video connectivity to high-end and professional applications, under the form of PCI Express interface cards or under the form of software components for Video of IP.
</br>

DELTACAST video I/O products sit in computer systems used in TV broadcasting, digital cinema production, live events, corporate broadcasting, e-sports, medical video systems, industrial vision appliances, and many more!
</br>

Learn more on [www.deltacast.tv](https://www.deltacast.tv)

# What is DELTACAST VideoMaster ?

**VideoMaster** is the software environment allowing the usage of [DELTACAST video I/O cards and FLEX solution](https://www.deltacast.tv/products/developer-products) on Windows, Linux and macOS computer platforms.

<p align="center">
   <img src="img/cards.png" width="700">
</p>
DELTACAST PCIe boards and FLEX modules provide video I/O connectivity in SDI, HDMI, DisplayPort, ASI, IP to computer-based application.

</br>

**VideoMaster** is essentially composed of drivers and libraries implementing the interfacing between the DELTACAST hardware, the platform and the operating system, as well as low-level features and video processing. That core software bundle is also surrounded by a series of components made to use the DELTACAST I/O cards in specific software frameworks and applications : Directshow filters, Unreal Engine plugin, Nvidia Holoscan operators, …

The VideoMaster software environment also includes a [software development kit (SDK) for developers](https://www.deltacast.tv/products/developer-products/software-development-kit/videomaster-oem-sdk). The **VideoMaster SDK** allows OEMs and 3rd-party applications developers to make use of DELTACAST I/O boards to bring in video connectivity to their designs.

<p align="center">
   <img src="img/videomaster.png">
</p>

# What is DELTACAST VideoMasterIP ?

**VideoMasterIP** is the software part of the [IP Virtual Card](https://www.deltacast.tv/products/developer-products/ip-software/ip-virtual-card-smpte-st-2110-edition) concept.

<p align="center">
   <img src="img/ipvc_logo.png">
</p>

The IP Virtual Card is a high-performance video streaming solution allowing to use COTS network cards to ingest and playout uncompressed video up to 4K as per SMPTE ST 2110.

The IP Virtual Card is available under Windows and Linux. It is provided as a set of software libraries and low-level components protected by runtime licenses and coming with a Software Development Kit (SDK) to develop computer-based ST 2110 video processing solutions.

# How to get VideoMaster and VideoMasterIP software ?

The VideoMaster software installers for Windows, Linux and maxOS, as well as the DELTACAST Directshow filters, are freely available onto the DELTACAST download center at :
<p align="center">
   <a href="https://www.deltacast.tv/support/download-center">HTTPS://WWW.DELTACAST.TV/SUPPORT/DOWNLOAD-CENTER</a>
</p>

Under the “Documentations” section, the download center also hosts installation and cabling guides of all the DELTACAST products. Please carefully follow the instructions in these guides.

The VideoMasterIP software installers are also available, together with dedicated documentation, onto the DELTACAST download center at :
<p align="center">
   <a href="https://www.deltacast.tv/support/download-center">HTTPS://WWW.DELTACAST.TV/SUPPORT/DOWNLOAD-CENTER</a>
</p>

To obtain a runtime license needed to execute the IP Virtual Card software components, please contact us at contact@deltacast.tv, or register yourself onto https://www.deltacast.tv/contact.

If you are a developer and wish to obtain the VideoMaster SDK or the VideoMasterIP SDK, you will also need to contact our staff at contact@deltacast.tv, or register yourself onto https://www.deltacast.tv/contact.

# What is hosted on GitHub ?

DELTACAST currently hosts the following project repositories on GitHub :

|  |  |
| --- | --- |
| ![](img/unreal.png) | [ue-media-plugin](https://github.com/deltacasttv/ue-media-plugin) </br> The DELTACAST Unreal Engine (UE) plugin offers direct support of DELTACAST video cards into the Unreal Engine, allowing live video capture from DELTACAST card input ports to the Unreal Engine, and sending rendered video from UE to an output port of a DELTACAST video card. |
| ![](img/videoviewer.png) | [video-viewer](https://github.com/deltacasttv/video-viewer) </br>Video monitoring module that manages to create a window with OpenGL context that displays incoming video data. |
| ![](img/holohub.png) | [holohub](https://github.com/deltacasttv/holohub) </br> Fork from the Nvidia Holohub central repository extensions and applications for the Holoscan platform. Includes DELTACAST video I/O operators and sample applications.|
| ![](img/nmos.png) | [nmos-ipvc-samples](https://github.com/deltacasttv/nmos-ipvc-samples) </br> NMOS IPVC samples explain the usage of the NMOS APIs in conjunction with IP Virtual Card VideoMasterIP API, to use as a reference for implementing IPVC solutions in media production and distribution workflows using NMOS. |
| ![](img/overlay.png) | [overlay-from-live-content](https://github.com/deltacasttv/overlay-from-live-content) </br> Application that demonstrates the possibility to overlay content generated from live stream with minimal latency, using DELTACAST keyer-enabled video I/O cards and the VideoMaster SDK. |
| ![](img/monitor.png) | [videomaster-video-monitor](https://github.com/deltacasttv/videomaster-video-monitor) </br> Application that displays the content of an input stream captured by a DELTACAST device, interfaced with the VideoMaster SDK. |
