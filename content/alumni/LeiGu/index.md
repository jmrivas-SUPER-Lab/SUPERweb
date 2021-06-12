---
title: "Lei Gu, Ph.D."
subtitle: "Stanford Ph.D. 2019"
excerpt: "Stanford Ph.D. 2019"
tags:
  - Lei Gu
weight: 6
author: ""
draft: false
# layout options: single or single-sidebar
layout: single-sidebar
links:
- icon: google-scholar
  icon_pack: ai
  name: Lei Gu, Ph.D.
  url: https://scholar.google.com/citations?hl=en&user=sJf1iI8AAAAJ
- icon: envelope
  icon_pack: fa
  name: leigu@alum.stanford.edu
  url: leigu@stanford.edu
---

# Doctoral Dissertation

## *Design considerations for radio frequency power converters*
 + Presented in 2019
 + Manuscript available [here.](https://searchworks.stanford.edu/view/13335787)
 
### Summary

Compact and efficient high-frequency power converters and amplifiers are needed in a variety of applications, including base stations, mobile devices, and medical equipment. The ever-growing need for a smaller size, longer battery life, and lower cost introduces challenging design considerations for radio-frequency power converters. Today, these radio-frequency resonant converters use harmonic tuning to shape the voltage or current waveform of the switching device, with the primary goals of reducing device stress and increasing achievable efficiency. Although harmonic-tuned resonant converters can be very compact and efficient for a certain condition, significant challenges remain to widespread adoption, including limited high-efficiency range, complicated design procedures, and higher device stress compared with conventional approaches. This thesis presents circuit techniques that can extend the voltage, frequency, and efficiency ranges of radio-frequency power converters and provides more straightforward analysis and easy-to-implement design procedures. This thesis first presents a multi-resonant gate driver circuit developed using the harmonic wave-shaping technique that significantly reduces the high-frequency gate driving losses for Si and SiC MOSFETs. By controlling different harmonic components of an ideal square wave, we can resonantly shape a quasi-square voltage waveform at the gate. This gate driver is simple to control and has a low component count. Compared with a sine wave gate signal, this method reduces the transition time between the MOSFET is fully enhanced and turned-off, driving down the switching losses. Compared with similar multi-resonant drivers that are self-oscillating, this driver reduces the long start-up time required to reach steady-state. Intuitive design methodologies based on the frequency-domain plot are introduced. Using this technique, we are able to resonantly drive a Si MOSFET at 20 MHz and recycle 60% of the hard-switching gate-driving loss. We also demonstrate this driver on a SiC MOSFET switching at 30 MHz and save 80% of the hard-switching loss. Modern applications demand power converters to maintain a constant voltage output with high efficiency across significant load variation. This thesis presents a bidirectional dc-dc converter that enables efficient fixed-ratio voltage conversion at tens of megahertz. By selecting a proper matching network for the intermediate gain stage, we address multiple challenges simultaneously; a) replacing a lossy passive diode with a more efficient active transistor, b) maintaining efficient soft-switching operation, and c) a constant voltage conversion ratio over a wide load range. A 64 MHz, 12 W, 36 V-to-12 V prototype converter with 75% peak efficiency verifies the operation of the structure. An interleaved configuration is then proposed to improve the efficiency and transient performance of a single-phase structure. A 13.56 MHz, 210 V-to-30 V prototype converter with 90% peak efficiency at 200 W demonstrates the advantages of this proposed structure. RF power amplifiers underpin many systems that support our modern infrastructure. The Class EF and E/F family of harmonic-tuned switch-mode amplifiers have simple gate drives, reduced voltage stress, and higher output power capabilities than a conventional Class E circuit. To best utilize the performance potential of this family of circuits, this thesis presents a novel push-pull Phi2 (EF2) amplifier using interleaving and series-stacking techniques, denoted as a PPT Phi2 circuit. This series-stacked PPT Phi2 circuit combines all of the main advantages of different topologies, like the simplicity of gate driving, highest cut-off frequency, lowest voltage stress, and load-invariant operation. A compact 6.78 MHz, 100 V, 300 W prototype converter is demonstrated. Using lowcost Si devices, the prototype converter achieves 96% peak total efficiency and maintains above 94.5% drain efficiency across a wide range of voltage and power. This new series-stacked PPT F2 RF amplifier doubles the maximum operating frequency and voltage range of a Class EF or E/F amplifier with benefits in many modern applications that require high-frequency high-power RF signals, like wireless charging for electric vehicles, plasma RF drives, and nuclear magnetic resonance (NMR) spectroscopy