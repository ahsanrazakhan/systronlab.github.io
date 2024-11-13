---
layout: post
title: "Kangfeng presents at SEFM2024"
date: 2024-11-07 12:00:00 +0000
subtitle: "User-Guided Verification of Security Protocols via Sound Animation"
background: '/img/posts/kangfeng-presenting-at-sefm-2024-2.jpg'
---

Kangfeng Ye presented his work on the formal verification of security protocols at the [22nd International Conference on Software Engineering and Formal Methods (SEFM 2024)](https://sefm-conference.github.io/2024/), held alongside the [12th International Symposium From Data to Models and Back (DataMod 2024)](https://datamod-symposium.github.io/DataMod-2024/) at the University of Aveiro, Portugal.

![Kangfeng presenting at SEFM 2024](/img/posts/kangfeng-presenting-at-sefm-2024-1.jpg)

The paper is titled "User-Guided Verification of Security Protocols via Sound Animation". It is joint work between Kangfeng, Roberto Metere, and Poonam Yadav. This work addresses the accessibility issue of formal verification to security protocols designers by introducing animation as a formal way to verify protocols and the soundness issue of animation. This paper proposes an innovative and iterative workflow to allow designers to carry our verification in the early stage of design with a guarantee that a problem detected during animation must be a bug in the design. Most importantly, animators are automatically generated from security protocol models. As a result, designers can find bugs earlier and deliver secure protocols efficiently without a loss of guarantee.

## Abstract of the paper

Current formal verification of security protocols relies on specialized researchers and complex tools, inaccessible to protocol designers who informally evaluate their work with emulators. This paper addresses this gap by embedding symbolic analysis into the design process. Our approach implements the Dolev-Yao attack model using a variant of CSP based on Interaction Trees (ITrees) to compile protocols into animators – executable programs that designers can use for debugging and inspection. To guarantee the soundness of our compilation, we mechanised our approach in the theorem prover Isabelle/HOL. As traditionally done with symbolic tools, we refer to the Diffie-Hellman key exchange and the Needham-Schroeder public-key protocol (and Lowe’s patched variant). We demonstrate how our animator can easily reveal the mechanics of attacks and verify corrections. This work facilitates security integration at the design level and supports further security property analysis and software-engineered integrations.

<div class="clearfix">
    <a class="btn btn-primary float-right" href="/files/2024-presentation-formal-verification-security-protocols-sefm-2024.pdf">View the Slides</a>
</div>