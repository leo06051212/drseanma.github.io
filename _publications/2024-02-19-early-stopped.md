---
title: "Early-Stopped Technique for BCH Decoding Algorithm Under Tolerant Fault Probability"
collection: publications
permalink: /publication/2024-02-19-early-stopped
excerpt: ''
date: 2024-02-19
venue: 'International Congress on Information and Communication Technology'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-97-3299-9_3'
citation: 'Wang, SS., Chou, Hf., Zhong, X., Ma, S.L. (2024). Early-Stopped Technique for BCH Decoding Algorithm Under Tolerant Fault Probability. In: Yang, XS., Sherratt, S., Dey, N., Joshi, A. (eds) Proceedings of Ninth International Congress on Information and Communication Technology. ICICT 2024 2024. Lecture Notes in Networks and Systems, vol 1002. Springer, Singapore. https://doi.org/10.1007/978-981-97-3299-9_3'
---

In this paper, a technique for the Berlekamp-Massey(BM) algorithm is provided to reduce the latency of decoding and save decoding power by early termination or early-stopped checking. We investigate the consecutive zero discrepancies during the decoding iteration and decide to early stop the decoding process. This technique is subject to decoding failure in exchange for the decoding latency. We analyze our proposed technique by considering the weight distribution of BCH code and estimating the bounds of undetected error probability as the event of erroneous stop checking. The proposed method is effective in numerical results and the probability of decoding failure is lower than 10^-119 for decoding 16383 code length of BCH codes. Furthermore, the complexity compared the conventional early termination method with the proposed approach for decoding the long BCH code. The proposed approach reduces the complexity of the conventional approach by up to 80%. As a result, the FPGA testing on a USB device validates the reliability of the proposed method.

Recommended citation: 

@InProceedings{10.1007/978-981-97-3299-9_3,
author="Wang, Shih-Shuan
and Chou, Hong-fu
and Zhong, Xinchao
and Ma, Sean Longyu",
editor="Yang, Xin-She
and Sherratt, Simon
and Dey, Nilanjan
and Joshi, Amit",
title="Early-Stopped Technique for BCH Decoding Algorithm Under Tolerant Fault Probability",
booktitle="Proceedings of Ninth International Congress on Information and Communication Technology",
year="2024",
publisher="Springer Nature Singapore",
address="Singapore",
pages="27--36",
abstract="In this paper, a technique for the Berlekamp-Massey(BM) algorithm is provided to reduce the latency of decoding and save decoding power by early termination or early-stopped checking. We investigate the consecutive zero discrepancies during the decoding iteration and decide to early stop the decoding process. This technique is subject to decoding failure in exchange for the decoding latency. We analyze our proposed technique by considering the weight distribution of BCH code and estimating the bounds of undetected error probability as the event of erroneous stop checking. The proposed method is effective in numerical results and the probability of decoding failure is lower than {\$}{\$}10^{\{}-119{\}}{\$}{\$}10-119for decoding 16383 code length of BCH codes. Furthermore, the complexity compared the conventional early termination method with the proposed approach for decoding the long BCH code. The proposed approach reduces the complexity of the conventional approach by up to 80{\%}. As a result, the FPGA testing on a USB device validates the reliability of the proposed method.",
isbn="978-981-97-3299-9"
}
