---
layout: post
title: "Cisco Systems 2015-2021"
author: Kousik Nandy
---

In 2015, I returned to Cisco Systems with a specific mission: to fill a growing void in the enterprise networking industry. The landscape had shifted dramatically. We were no longer just managing office desktops; we were facing a world of pervasive Wi-Fi, a deluge of IoT devices, and an increasingly sophisticated threat landscape. 

The industry lacked a centralized "brain" capable of managing tens of thousands of devices with the automation and security required for the modern era. My journey over these six years was centered on building that brain—**Cisco DNA Center**.

## Bridging the Void with Project Maglev

Enterprise networks had become too complex for manual configuration. To solve this, we initiated **Project Maglev**, the underlying Platform-as-a-Service (PaaS) that powers DNA Center. We didn't just want to build an application; we wanted to change the paradigm of how Cisco delivered management software.

The challenge was unique: we needed to deliver a cloud-like microservices experience, but on-premise within the customer’s data center. 

### Building an On-Premise Kubernetes Distribution
As a Principal Engineer, I led the team responsible for the infrastructure and platform layers. We built a custom on-premise Kubernetes distribution that was OEM-ready for hardware appliances. This involved:
* **Custom OS and Kernel:** Maintaining a hardened operating system and kernel tailored for high-performance networking tasks.
* **Service Orchestration:** Designing an infrastructure that allowed various networking applications to run as modular microservices.
* **In-place Upgrades:** Developing a seamless mechanism to update firmware, the OS, Kubernetes, and the PaaS layer without disrupting the network's management plane.
* **Enterprise Adaptations:** Adding critical features like link-local addressing support for Kubernetes to ensure compatibility with enterprise data center architectures.

---

## Security as the Foundation

In a world of pervasive security threats, a management controller is the ultimate target. If the controller is compromised, the entire network is at risk. Taking this responsibility to heart, I led the product-wide security team and served as the **Security Officer for Cisco DNA Center**.

Holding a **Security Ninja Brown Belt** (the penultimate level of security expertise at Cisco), I focused on building a "Defense in Depth" strategy:
* **Hardware-Rooted Trust:** Implementing TPM-based key management and Secure Boot to ensure hardware integrity.
* **Data Protection:** Developing encrypted file systems and managing the critical security assets and keys of the product.
* **Vulnerability Management:** Managing the lifecycle of CVEs and maintaining a rigorous secure development lifecycle (SDL), including threat modeling and vulnerability scans.
* **Compliance:** Driving the efforts toward FIPS compliance and other vital government certifications.

---

## Impact at Scale

What started as a foundational project in Bangalore grew into Cisco’s flagship product for Enterprise Networking. By 2021, our installation base surpassed **13,000 customers** (as of 2021), and I had the privilege of evangelizing the platform to a community of over a thousand application developers and partners.

Building a team of 20 talented engineers from the ground up to realize this vision was one of the most rewarding aspects of my career. We didn't just build a tool; we built a scalable, secure, and automated ecosystem that defined the next generation of Intent-Based Networking (IBN). 

Cisco DNA Center proved that even the most complex enterprise networks can be tamed through the right blend of microservices orchestration, rigorous security, and a platform-first mindset.

---
