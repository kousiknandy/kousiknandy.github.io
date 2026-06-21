---
layout: post
title: "Meta: 2025 onwards"
author: Kousik Nandy
---

When I stepped into the mandate of scaling Meta’s Cloud Foundation from 2025 onwards, the objective was clear but monumental: harness the public cloud to nearly double Meta's total compute capacity. Meeting the insatiable demand for next-generation AI training and inference required looking beyond our physical walls. To achieve this, I turned to the industry's major hyperscalers and emerging neocloud vendors—including AWS, OCI, GCP, and CoreWeave—to systematically unlock their massive GPU, TPU, and CPU repositories and integrate them directly into Meta’s ecosystem.

The core challenge lay in connectivity. AI workloads cannot thrive in isolated silos; they require massive data pipelines and near-zero latency. To bridge this gap, I designed and optimized hybrid-cloud networking frameworks that seamlessly connect external cloud vendors to Meta’s own internal data centers. By establishing over 10 high-speed, direct interconnect circuits ranging from 1 to 128 Tbps, we effectively built a unified, ultra-high-throughput data highway. This infrastructure allows Meta to readily deploy massive compute capacity exactly where and when it is needed most.

### Pioneering Multi-Cloud AI Architecture

This initiative culminated in the pioneering of Meta’s first production-grade multi-cloud AI networking architecture. This architecture now serves as the company’s gold standard for engineering blueprints, covering everything from initial interconnect provisioning to application-layer routing across frontend, backend, and AI fabric networks. 

Through this unified framework, we successfully extended Meta’s production network into the public cloud, enabling an unprecedented **2.4 GW of AI compute** alongside 400 MW of non-AI compute. This massive expansion nearly doubled the size of the Meta fleet, supporting the seamless orchestration of next-generation GPU (including NVIDIA Blackwell) and TPU clusters.

### Scale, Security, and Compliance

Operating at this magnitude meant designing for clusters ranging from 10K to 40K GPUs. To support the data-heavy pipelines required for large-scale AI training, I architected a unified storage network capable of hosting 60 PB of ultra-fast storage, leveraging AWS S3 Express One Zone and FSx for Lustre. 

However, raw speed and scale are nothing without control. To ensure that these massive, distributed clusters operate safely, I defined rigorous routing, admission control, and security policy frameworks. This established a standardized operational baseline, ensuring that every multi-cloud AI cluster remains fully secure, compliant, and operationally consistent regardless of which cloud provider hosts the underlying hardware.

Looking back from 2025 to the present, this architectural evolution has fundamentally shifted how Meta scales. By transforming the public cloud into a seamless extension of our own data centers, we have ensured that Meta's AI infrastructure remains agile, robust, and fully prepared for the next generation of AI innovation.
