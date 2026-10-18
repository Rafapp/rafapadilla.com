---
title: Projects
permalink: /projects/

feature_row:
  - image_path: /assets/images/penumbra.png
    alt: "Penumbra"
    title: "Penumbra"
    excerpt: "<b>Path-tracing Renderer</b><br><br>Penumbra is a compact, physically based path-tracing renderer written from scratch in C++, designed for fast iteration, rendering experiments, and research. It implements modern light-transport techniques, including multiple importance sampling (MIS) and next-event estimation (NEE) alongside the Walt Disney Animation Studios' principled BSDF/BSSRDF, and supports mono and stereo image and animation output."
    url: "https://github.com/Rafapp/Penumbra"
    btn_class: "btn--primary"
    btn_label: "Github repo"
  - image_path: /assets/images/vargrid_logo.png
    alt: "Walt Disney Animation Studios"
    title: "VarGrid"
    excerpt: "<b>Trainee Team Project</b><br><br>Pixar Universal Scene Description (USD) based tool that visualizes asset variant data intuitively"
    url: "https://gumlet.tv/watch/6879674d7193df23ac9880a7/"
    btn_class: "btn--primary"
    btn_label: "Demo Video (password required)"

  - image_path: /assets/images/wdas.jpg
    alt: "Walt Disney Animation Studios"
    title: "LookAround"
    excerpt: "<b>Individual Trainee Project</b><br><br>Tool for the look department that allows to render turntable views of an asset in all of the film's sets"
    url: "https://gumlet.tv/watch/6879674daa14b70eb1c6a38b/"
    btn_class: "btn--primary"
    btn_label: "Demo Video (password required)"

  - image_path: /assets/images/JellyEngineNew.gif
    alt: "Jelly Engine"
    title: "Jelly Engine"
    excerpt: "<b>Soft Body Physics Game Engine</b><br><br>Architected a game engine for my graduation thesis with real-time soft body physics support. Optimized physics solver reaching <b>120+ FPS</b> for up to <b>1000-triangle</b> meshes, and implemented a custom GLSL shader for subsurface scattering using the Oren-Nayar model.<br><br><i><b>Languages & Tools:</b></i> C/C++, CMake, OpenGL, GLSL"
    url: "https://github.com/Rafapp/jellyengine"
    btn_class: "btn--primary"
    btn_label: "Github repo"

  - image_path: /assets/images/PrimDemo.gif
    alt: "Prim"
    title: "Prim"
    excerpt: "<b> MAYA plug-in</b><br><br>Enables artists to name and save scene meshes as primitives, curate 3D primitive libraries, instance them in new projects, and export them using a custom .prim file format for sharing among users.<br><br><i><b>Languages & Tools:</b></i> QT, PySide6, Maya, MEL, Python"
    url: "https://github.com/Rafapp/Prim"
    btn_class: "btn--primary"
    btn_label: "Github repo"
---

{% include feature_row type="single"%}
{% include new-window-fix.html %}
