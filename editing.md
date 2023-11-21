# Editing

This section is about tools for video and photo editing.

## Kdenlive

A video editing suite that can acomplish most editing requirements. Support hardware rendering with both Nvidia and AMD GPUs. AMD only works with propriatary drivers properly installed.

[Website](https://kdenlive.org/)

## DaVinci Resolve

A proprietary video editing suite that is a bit more industry standard compared to Kden. However being that it’s proprietary, it’s free version has limitations compared to the pay-for premium “studio version”. Only certain video codecs can be imported. As seen in documentation here: https://documents.blackmagicdesign.com/SupportNotes/DaVinci_Resolve_16_Supported_Codec_List.pdf

Easiest way to convert video to compatible format is to use ffmpeg or a gui frontend like Winff with this command (soon). Also note that davinci only works with Cuda capable Nvidia GPUs Running the proprietary nvidia driver. Although older versions may work with integrated intel graphics. Davinci offers a great deal of video effects and node-based effects in their “fusion” editor. It also has relatively fast video exporting compared to the likes of Adobe’s editors. 

[Website](https://www.blackmagicdesign.com/products/davinciresolve)

## GIMP

An image editor that can do most things that Adobe PhotoShop can do. UI may be unfriendly so installing the PhotoGIMP theme/preset can be recommended if you are familiar with PhotoShop.

[Website](https://www.gimp.org/) \
[PhotoGIMP](https://github.com/Diolinux/PhotoGIMP)
