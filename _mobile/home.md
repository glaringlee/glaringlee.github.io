---
layout: mobile
title: Home
permalink: /mobile/home/
background-class: mobile-background
body-class: mobile
order: 1
published: true
redirect_from: "/mobile/"
---

# PyTorch Mobile

Running ML on edge devices is growing in importance as applications continue to demand lower latency. It is also a foundational element for privacy-preserving techniques such as federated learning. As of PyTorch 1.3, PyTorch supports an end-to-end workflow from Python to deployment on iOS and Android. 

This is an early, experimental release that we will be building on in several areas over the coming months:

- Provide APIs that cover common preprocessing and integration tasks needed for incorporating ML in mobile applications
- Support for QNNPACK quantized kernel libraries and support for ARM CPUs
- Build level optimization and selective compilation depending on the operators needed for user applications (i.e., you pay binary size for only the operators you need)
- Further improvements to performance and coverage on mobile CPUs and GPUs

Learn more or get started on [Android]({{site.baseurl}}/mobile/android) or [iOS]({{site.baseurl}}/mobile/ios).

<div class="text-center">
  <img src="{{ site.baseurl }}/assets/images/pytorch-mobile.png" width="100%">
</div>

<!-- Do not remove the below script -->

<script page-id="home" src="{{ site.baseurl }}/assets/menu-tab-selection.js"></script>
