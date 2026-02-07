---
layout: post
title: "Analog Devices 1999–2000"
author: "Kousik Nandy"
---

The late 90s marked a paradigm shift in Digital Signal Processing. During my tenure at **Analog Devices**, I focused on transitioning DSP development from rigid assembly to the flexibility of high-level languages.

### Engineering the VDK (VisualDSP++ Kernel)
I developed core components of the **VDK**, a priority-based, preemptive RTOS. I was responsible for the "trinity" of the kernel: **thread management, inter-thread communication (semaphores/messages), and hardware timers**. 
In the context of the TigerSHARC, VDK provided the deterministic scheduling required for multi-tasking applications, such as 3G cellular base stations and early-stage medical imaging, where timing jitter was unacceptable.



### Taming TigerSHARC with C/C++
The **TigerSHARC** was a VLIW beast capable of executing multiple instructions per cycle, but hand-coding assembly for its complex pipelines was a massive bottleneck. By developing the **'libc' and 'complex math' libraries**, 
I helped bridge the gap between high-level abstraction and silicon efficiency. 

Writing these in C/C++ allowed engineers to implement complex algorithms—like FFTs and FIR filters—without managing register-level dependencies manually. This shift to high-level languages transformed the development lifecycle, 
enabling faster iteration and making the power of the TigerSHARC accessible for the high-bandwidth video and audio processing that defines our modern world.
