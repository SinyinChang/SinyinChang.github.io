---
title: "AdapSan: Adaptive Input Sanitization in Medical Systems with eBPF"
collection: publications
permalink: /publication/20241201-AACD-AdapSan
date: 2024-12-01
venue: 'ACM Workshop on Adaptive and Autonomous Cyber Defense, 2024'
paperurl: 'https://dl.acm.org/doi/10.1145/3689935.3690397'
citation: '<b><u>Sinyin Chang</u></b>, Ao Li, Evin Jaff, Yuanhaur Chang, Jinwen Wang, Ning Zhang, Hsu-Chun Hsiao. AdapSan: Adaptive Input Sanitization in Medical Systems with eBPF. ACM Workshop on Adaptive and Autonomous Cyber Defense, 2024'
---
## Abstract

The current state of healthcare is challenged by the widespread use of legacy systems, which often lack the advanced security features necessary to combat modern cyber threats. However, our investigation reveals that hospitals are often reluctant to upgrade their systems, which is primarily due to the following factors: low tolerance to service downtime and patch errors, platform diversities, and the resource constraints of embedded medical devices.

Motivated by these challenges, we propose AdapSan, a framework that allows users to dynamically deploy input sanitization schemes for kernel according to the risk profiles of the target system. AdapSan utilizes eBPF as the key technique to enable dynamic reconfiguration of defense strategies, thereby avoiding downtime. Additionally, it uses eBPF's verification mechanisms to sandbox patch code, minimizing the impact of potentially buggy patches. Furthermore, the platform-agnostic nature of eBPF bytecode and its Just-In-Time (JIT) compilation facilitate the deployment of this solution across various platforms while maintaining the execution speed of native code. AdapSan incorporates two types of insertion schemes, offering a balance between usability and code complexity. Preliminary evaluations of AdapSan indicate that the patching time can be less than 19 milliseconds and the average runtime overhead post-patching can be maintained below 36%.
