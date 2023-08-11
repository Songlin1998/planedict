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
The task of face reenactment is challenging due to the need to establish dense correspondence between various representations of the face for motion transfer. Utilizing Neural Radiance Field (NeRF) as fundamental representation further improves its performance in multi-view rendering with photo-realism and 3D consistency. However, establishing dense correspondence across different face NeRFs is non-trivial, because implicit representations lack ground-truth correspondence annotations like mesh-based 3D parametric models (e.g., 3DMM) with index-aligned vertices. Although aligning 3DMM space with NeRF-based face representations can realize motion control, it is sub-optimal for their limited face-only modeling and low identity fidelity. Therefore, we are inspired to ask: Can we learn the dense correspondence of different face NeRF-based representations without 3D parametric model prior? To address this challenge, we propose a novel framework based on tri-plane representations (i.e., three spatially-orthogonal plane feature maps). The key contribution of our framework is the Plane Dictionary (PlaneDict) module, which learns dense correspondence and enables the transformation of motion vectors to structural plane feature deformations. Specifically, we decompose the motion plane feature deformations into a linear addition of learnable orthogonal plane bases. To the best of our knowledge, our PlaneDict is the first method which achieves one-shot multi-view face reenactment without 3D parametric model and produces better results than previous works in fine-grained motion control and identity preservation.
        </div>
    </div>
</div>

---

## <center> Framework
![](/static/image/pipeline.png)

---

## <center> Cross-Identity Face Reenactment
![](/static/image/demo_0.gif)
![](/static/image/demo_1.gif)

---

## <center> Multi-View Synthesis
![](/static/image/demo_2.gif)
![](/static/image/demo_3.gif)
