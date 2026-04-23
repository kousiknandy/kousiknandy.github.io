---
layout: post
title: "Meta/Facebook 2021-2025"
author: Kousik Nandy
---


At Meta’s scale, privacy is not just a policy—it is a monumental engineering challenge. From 2021 to 2025, I had the privilege of leading the **London Production Engineering Privacy team**, where we were tasked with a mission that was as critical as it was complex: ensuring that data access control and lifecycle management remained unbreakable across Facebook and Instagram. 

My journey was defined by a fundamental shift in how we approach data deletion, moving from reactive scripts to a robust, scalable infrastructure capable of meeting the world’s most stringent regulatory demands.

### Re-Architecting for the Modern Era: The Three-Plane Deletion Framework

The cornerstone of my work was the complete re-architecture of Meta’s deletion framework. To solve the inherent scalability and compliance bottlenecks of the legacy systems, I designed and implemented a **three-plane architecture**. This separation of concerns allowed us to decouple the core logic of data identification from the actual execution and management of deletion tasks.

To bring this architecture to life, I built a **Python-based orchestrator** that served as the brain of the system. By introducing a **multi-tenant model**, we empowered individual product teams to manage and fund their own data deletion workflows. This wasn’t just a technical upgrade; it was a paradigm shift. It enabled the platform to handle massive, unpredictable data bursts—like product deprecations or sudden regulatory shifts—without disrupting the daily operations of Meta’s global infrastructure.

### Impact by the Numbers

The results of this re-architecture were immediate and transformative:

* **Product Deprecations:** When we deprecated "Nearby Friends," the new system seamlessly deleted **23.7 billion Instagram accounts** and **2.7 trillion objects**. 
* **Regulatory Compliance:** To comply with EU regulations for the launch of the **Ads Free Service**, we deleted the ads data of **3 billion inactive and 300 million active users** in just four days—a feat that would have been impossible under the old framework.
* **Efficiency Gains:** The multi-tenant approach sped up completion times by **10x** and reduced operational alerts by **30%**, all while increasing throughput by **52%**.

### Strengthening the Service Mesh

Beyond deletion, we focused heavily on the reliability of privacy enforcement within Meta’s service mesh. We applied privacy policies to over a **trillion accesses per day** across Thrift RPC calls and data warehouse flows. 

To ensure our systems were truly resilient, I introduced **"Privacy Storms."** This involved intentionally triggering privacy control shutdowns in production (including a fleet-wide killswitch) to validate our recovery protocols. This "chaos engineering" for privacy increased the overall safety of our infrastructure by **75%** and ensured we maintained a record of **zero site-wide outages** throughout my tenure.

---

### Leadership and Legacy

Technical architecture is only half the story. Over these four years, I grew and mentored a Production Engineering team from the ground up to a group of seven dedicated engineers. Together, we supported three major privacy organizations and over 1,000 engineers, embedding a culture of reliability and "privacy-first" design into the DNA of Meta’s infrastructure.

By separating concerns, automating execution, and protecting the core infrastructure, we didn't just delete data—we built the foundation for trust at a global scale.
