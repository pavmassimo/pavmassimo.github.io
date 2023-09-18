---
title: "TyBox: an automatic design and code-generation toolbox for TinyML incremental on-device learning"
collection: publications
permalink: /publication/Tybox
excerpt: 'An On-device learning toolbox for the automatic conversion of a static tinyML solution to an incremental learning one.'
date: 2023-04
venue: 'ACM Transactions on Embedded Computing Systems - Special Issue on TinyML'
paperurl: 'https://dl.acm.org/doi/10.1145/3604566'
citation: 'Pavan, M., Ostrovan, E., Caltabiano, A., Roveri, M.  (2023). &quot;TyBox: an automatic design and code-generation toolbox for TinyML incremental on-device learning&quot; <i>ACM Transactions on Embedded Computing Systems - Special Issue on TinyML</i>. 1(3).'
---
Incremental on-device learning is one of the most relevant and interesting challenges in the ield of Tiny Machine Learning (TinyML). Indeed, diferently from traditional TinyML solutions where the training is tipically carried out on the Cloud and inference-only occurs on the tiny devices (e.g., embedded systems or Internet-of-Things units), incremental on-device TinyML allows both the inference and the training of TinyML models directly on tiny devices. This ability paves the way for TinyML-enabled intelligent devices that can learn directly on-the-ield and adapt to evolving environments, diferent working conditions or speciic users. The TinyML literature in this ield is very limited with very few solutions focusing only on the incremental ine-tuning of machine learning models, while a general solution encompassing algorithms and code-generation for incremental on-device TinyML is still perceived as missing. The aim of this paper is to introduce, for the irst time in the literature, a toolbox, called TyBox, for the automatic design and code-generation of incremental on-device TinyML classiication models. In more detail, starting from a "static" TinyML model, TyBox is able to (i) automatically design the "incremental" on-device version of the TinyML model that has been suitably designed to take into account the technological constraint on the RAM memory of the target tiny device and (ii) autonomously provide the C++ codes and libraries to support the inference and learning of the incremental on-device TinyML model directly on the tiny devices.
TyBox has been extensively compared with a state-of-the-art incremental learning solution for TinyML and tested on an of-the-shelf tiny device (i.e., the Arduino Nano 33 BLE) in three relevant TinyML application tasks and scenarios, i.e., binary image classiication, multi-class image classiication and Ultra-Wide-Band human activity recognition. In addition, TyBox is released to the scientiic community as a public repository.

[Download paper here](https://dl.acm.org/doi/10.1145/3604566)

Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3).
