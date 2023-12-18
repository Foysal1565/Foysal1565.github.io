---
layout: page
title: IEEE 802.11 Beamforming Feedback Information Extraction Tool
description:
img: assets/img/Wi-BFI.png
importance: 3
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Wi-BFI.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Wi-BFI: Extracting the IEEE 802.11 Beamforming Feedback Information from Commercial Wi-Fi Devices
</div>

Recently, researchers have shown that the beamforming feedback angles (BFAs) used for Wi-Fi multiple-input multiple-output (MIMO) operations can be effectively leveraged as a proxy of the channel frequency response (CFR) for different purposes. Examples are passive human activity recognition and device fingerprinting. However, even though the BFAs report frames are sent in clear text, there is not yet a unified open-source tool to extract and decode the BFAs from the frames. To fill this gap, we developed Wi-BFI, the first tool that allows retrieving Wi-Fi BFAs and reconstructing the beamforming feedback information (BFI) – a compressed representation of the CFR – from the BFAs frames captured over the air. The tool supports BFAs extraction within both IEEE 802.11ac and 802.11ax networks operating on radio channels with 160/80/40/20 MHz bandwidth. Both multi-user and single-user MIMO feedback can be decoded through Wi-BFI. The tool supports real-time and offline extraction and storage of BFAs and BFI. The real-time mode also includes a visual representation of the channel state that continuously updates based on the collected data. Wi-BFI code is open source and the tool is also available as a pip package.

Please find the <a href="https://github.com/kfoysalhaque/Wi-BFI">Wi-BFI tool here.</a>
