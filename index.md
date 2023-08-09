---
layout: project_page
permalink: /

title: Learning Dense Correspondence for NeRF-Based Face Reenactment
Paper: https://demoforshow.github.io/planedict/
---

<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
The application of Neural Radiance Field (NeRF) in face reenactment has demonstrated potential in producing photo-realistic synthetic images and achieving 3D-consistent rendering. However, unlike mesh-based 3D parametric models (e.g., 3DMM) with index-aligned vertices, establishing dense correspondence between different face NeRF-based representations is non-trivial. Although aligning 3DMM with NeRF-based generative models can realize explicit motion control, it is sub-optimal for their limited face-only modeling and low identity fidelity. Thus, we present a more challenging yet crucial question: Can we learn the dense correspondence of different face NeRF-based representations without 3D parametric model prior? To address this challenge, we propose a novel framework based on tri-plane representations for one-shot multi-view face reenactment. The key contribution of our framework is the Plane Dictionary (PlaneDict) module, which learns dense correspondence and enables the transformation of motion vectors to structural plane feature deformations. In the PlaneDict module, we decompose the motion plane feature deformations relative to the canonical tri-planes into a linear addition of learnable orthogonal plane bases. To the best of our knowledge, our PlaneDict is the first method which achieves one-shot multi-view face reenactment without 3D parametric model and produces comparable results to previous works. It has more flexibility to control the motion of arbitrary objects without relying on a 3D parametric model.
        </div>
    </div>
</div>

---

## Framework
![](/static/image/pipeline.png)

## Cross-Identity Face Reenactment
![](/static/image/demo_0.gif)
![](/static/image/demo_1.gif)

## Multi-View Synthesis
