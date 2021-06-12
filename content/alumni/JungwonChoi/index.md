---
title: "Jungwon Choi, Ph.D."
subtitle: "Stanford Ph.D. 2018"
excerpt: "Stanford Ph.D. 2018"
tags:
  - Jungwon Choi
weight: 5
author: ""
draft: false
# layout options: single or single-sidebar
layout: single-sidebar
links:
- icon: google-scholar
  icon_pack: ai
  name: Jungwon Choi, Ph.D.
  url: https://scholar.google.com/citations?hl=en&user=n0S_XggAAAAJ
- icon: envelope
  icon_pack: fa
  name: jwonchoi@alum.stanford.edu
  url: jwonchoi@stanford.edu
---

# Doctoral Dissertation

## *High-frequency, high-power resonant converter with wide bandgap devices for wireless power transfer systems*
 + Presented in 2018
 + Manuscript availabe [here.](https://searchworks.stanford.edu/view/12854783)
 
### Summary

As demand for electric vehicles (EVs) grows, wireless power transfer (WPT) technology becomes beneficial by removing the need for manual intervention to charge EV batteries. These high-power applications require power electronics systems that not only efficiently deliver sufficient power, but are also small enough to be embedded in the EV. However, while the size of other vehicle components has shrunk considerably over the past decade, that of power electronics systems has not. This presents a major challenge to making power electronics systems for EVs, plasma generation and other high-power industrial applications both efficient and small. This dissertation describes the design and implementation of efficient, compact power electronics systems for charging EVs and other industrial applications, as well as their extensions to WPT. A large part of this work involves overcoming technical limitations by designing high-power (above 2 kW) and high-efficiency (above 90%) systems to operate at tens of MHz switching frequency. First, wide bandgap (WBG) devices such as silicon carbide (SiC) MOSFETs or enhancement mode gallium nitride (eGaN) FETs are used to reduce the size and weight of the entire WPT system and improve system performance. With SiC MOSFETs and eGaN FETs, 2 kW resonant inverters and resonant rectifiers for WPT systems can successfully operate at 13.56 MHz switching frequency. Thus, this work opens up the possibility of achieving kilowatt-level output powers at MHz switching frequencies. After implementing a high-efficiency resonant inverter for the WPT system, the coupling coils must be designed very carefully to deliver power with high efficiency over a mid-range coil distance. Therefore, an open-type four-coil unit is also presented in this work. The advantage of the coils is that the resonant frequency can be changed by adjusting the length of copper wire and distance between two coils. Using this type of coil unit eliminates the need for external capacitors that incur additional losses. However, even when the coupling coils are designed and implemented perfectly to provide high efficiency, the WPT system performance may decrease because of misalignments between the transmitting and receiving coils. Specifically, resonant converters are sensitive to load variation, which increases losses in switching devices. The impedance of magnetic resonant coupling (MRC) coils seen by inverters can be easily changed according to the distance or alignment between transmitting and receiving coils. This is one of the main factors that degrades the overall efficiency of WPT systems. To overcome this issue, this dissertation introduces a new kind of matching network, called an impedance compression network (ICN), to maintain the robustness of coil efficiency in various coil positions. An ICN consisting of a resistance compression network (RCN) and a phase compression network (PCN) was designed and implemented to compensate for distance and alignment variations between coils in a WPT system. Using an ICN helps maintain zero voltage switching (ZVS) and zero dv/dt operation in a resonant inverter and achieve system performance of over 90% efficiency. While WPT systems offer a convenient way to enable high-power applications, a critical unresolved concern is the safety of these systems. This dissertation presents two safety guidelines for EMF exposure and previous studies that evaluate human exposure level compared to the values recommended in the regulations. However, the limits of human exposure to electric, magnetic and electromagnetic fields in high-power WPT systems have not been clearly demonstrated yet. Based on the guidelines and the previous research, future research is required to evaluate EMF exposure in high-frequency, high-power WPT systems. One of the challenges in designing WPT systems for EVs is the need to combine power amplifiers to obtain higher power levels. To address this problem, this dissertation proposes a power-combining resonant inverter that can be applied not only to WPT systems, but also plasma generation and other industrial applications. Current RF power amplifiers for plasma generation operate at very high frequency (VHF), but provide low efficiency around 70% because they use linear amplifier topologies. Using a resonant inverter with WBG devices provides high power while maintaining high efficiency in a 40.68 MHz plasma-generation system. However, WBG devices cannot effectively dissipate heat at frequencies above 40 MHz. To reduce the losses in each eGaN FET, a power-combining inverter based on a class Phi2 inverter is designed and implemented to provide 1.2 kW output power at 40.68 MHz. A configurable method used to tune a class Phi2 inverter allows us to easily connect four of them in parallel to create a power-combining inverter that can achieve up to 1.2 kW output power. Also, the proposed inverter topology reduces the power loss in each switching device, improving the power density of the resonant inverter. In conclusion, this dissertation proposes high-frequency, high-power resonant converters with WBG devices to improve the power density and efficiency of both WPT and plasma generation systems. Furthermore, it presents a novel ICN topology that mitigates misalignment problems caused by MRC coils.
