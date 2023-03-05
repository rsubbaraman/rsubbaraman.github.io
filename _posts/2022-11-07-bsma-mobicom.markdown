---
layout: post
title:  "BSMA: scalable LoRa networks using full duplex gateways"
date:   2022-11-07 10:22:00 +00:00
image: /images/bsmafig1.png
categories: research
author: "Raghav Subbaraman"
authors: "<strong>Raghav Subbaraman</strong>, Yeswanth Guntupalli, Shruti Jain, Rohit Kumar, Krishna Chintalapudi, and Dinesh Bharadia"
venue: "ACM Conference on Mobile Computing and Networking (MobiCom)"
paper: "https://dl.acm.org/doi/10.1145/3495243.3560544"
# slides: https://wcsng.ucsd.edu/files/mmreliable.pdf
code: https://github.com/ucsdwcsng/bsma_lora
---
We present Busy Signal Multiple Access (BSMA), where the LoRa gateway transmits a downlink busy signal while receiving an uplink transmission. The IoT devices defer uplink transmissions while a busy signal is present. Practically viable BSMA requires a full-duplex LoRa gateway - i.e., a gateway that can simultaneously receive and transmit in the same channel. We develop the first full Duplex LoRa gateway in the 915 MHz ISM band, overcoming challenges that arise from a 9× greater delay spread and the need for 1000× greater self-interference cancellation. Our implementation works with COTS LoRa devices and improves network capacity by 100% compared to CSMA in bursty loads while being fair to all IoT devices near and far.