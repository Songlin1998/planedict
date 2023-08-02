---
layout: project_page
permalink: /

title: PlaneDict: Learning Dense Correspondence of Tri-Planes for One-Shot Multi-View Face Reenactment
Paper: https://demoforshow.github.io/planedict/
---

<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
One-shot multi-view face reenactment aims to drive a source face image with the motion condition from the driving image and realize multi-view rendering. The main challenge is to establish dense correspondence between different implicit representations of the face in order to transfer the motion condition. Although adopting 3D parametric models (e.g., 3DMM) can realize motion control, it is sub-optimal for their limited face-only modeling and low identity fidelity. Thus, we present a more challenging yet crucial question: \textbf{\textit{Can we learn the dense correspondence of different face implicit representations without 3D parametric model prior?}} To address this challenge, we propose a novel framework based on tri-plane representations for one-shot multi-view face reenactment. The key contribution of our framework is the Plane Dictionary (\textbf{PlaneDict}) module, which learns dense correspondence and enables the transformation of motion vectors to structural plane feature deformations. In the PlaneDict module, we decompose the motion plane feature deformations relative to the canonical tri-planes into a linear addition of learnable orthogonal plane bases. To the best of our knowledge, our PlaneDict is the first method which achieves one-shot multi-view face reenactment without 3D parametric model and produces comparable results to previous works. This demonstrates the potential to control the motion of arbitrary objects without relying on a 3D parametric model.
        </div>
    </div>
</div>

---
