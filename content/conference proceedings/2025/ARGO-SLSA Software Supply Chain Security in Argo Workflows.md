---
title: ARGO-SLSA Software Supply Chain Security in Argo Workflows,
draft: false
tags:
  - conference
---

**Abstract:**

Distributed systems widely adopt microservice architecture to handle growing complexity and scale. This approach breaks applications into independent, loosely coupled services. Kubernetes has become the de facto standard for managing microservices, and automating complex, multi-step workflows is a common requirement in Kubernetes. Argo Workflows is a Kubernetes-native engine for managing these workflows in an automated fashion. These workflows generate artifacts such as executables, logs, container images, and packages, which often require proper management through software supply chain security. However, Argo Workflows does not include built-in functionality for frameworks like Supply-chain Levels for Software Artifacts (SLSA), which is essential for ensuring artifact integrity, traceability, and security. This gap compels practitioners to rely on external tools to meet software supply chain security standards. In response, this paper proposes a Kubernetes-native controller built on top of existing open-source Argo Workflows to enhance artifact security. By generating cryptographic signing and provenance attestations, the controller enables Argo Workflows to comply with SLSA standards. We demonstrate that implementations can provide such cryptographic signing and provenance attestations for artifacts produced by the controller, allowing software artifacts built with Argo Workflows to adhere to SLSA requirements. The proposed validation model evaluates the proof of concept of the controller, including its ability to reconcile workflows, detect pods associated with workflow nodes, operate without disrupting existing operations, enforce integrity, and monitor software artifacts.


**Published in:** 2025 11th Moratuwa Engineering Research Conference (MERCon).

**Date of Conference:** 14-15 Aug 2025

**Date Added to IEEE _Xplore_:** 

**ISBN Information:**

**Electronic ISBN:**

**Print on Demand(PoD) ISBN:**

**DOI:** <a href="https://doi.org/10.48550/arXiv.2503.20079" target="_blank">10.48550/arXiv.2503.20079</a>.

**Publisher**: IEEE

**Conference Location:** Moratuwa, SriLanka
