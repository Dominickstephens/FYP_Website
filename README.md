# REMI: Visualising Real-time Pose

**REMI** is a system for real-time 3D human pose estimation and dynamic visualization, designed to provide immediate, intuitive feedback on movement quality. This project explores applications in fitness, physiotherapy, and general human movement analysis using standard monocular video.

**Project Page:** [View the Project Showcase](index.html)

## Core Components & Code

The REMI system is built upon modified versions of the following key projects:

* **Aitviewer (Real-time Visualization):** The modified code used for real-time 3D mesh visualization.
    * Repository: [https://github.com/Dominickstephens/aitviewer-skel-RT](https://github.com/Dominickstephens/aitviewer-skel-RT)
* **Ipman (Real-time Pose Estimation):** The modified code used for real-time 3D human pose and shape estimation.
    * Repository: [https://github.com/Dominickstephens/ipman-r-RT](https://github.com/Dominickstephens/ipman-r-RT)

## Overview

This Final Year Project investigates the effectiveness of real-time, markerless 3D human pose estimation and dynamic visualization for providing immediate, intuitive feedback on movement quality. Current accessible methods often lack detailed, multi-dimensional feedback. REMI addresses this gap by developing and evaluating an end-to-end pipeline that captures movement via standard monocular video, performs real-time 3D pose and shape estimation, and renders the corresponding 3D human mesh dynamically. The project assesses the potential of this immediate visual representation as a valuable form of feedback for human movement analysis.

## Key Features

* **Real-time Performance:** Designed for immediate feedback through efficient 3D pose and shape estimation from monocular video.
* **Markerless System:** Utilizes standard video cameras, removing the need for specialized markers or equipment.
* **Dynamic 3D Visualization:** Renders a 3D human mesh that dynamically mirrors the user's movements.
* **Focus on Feedback:** Investigates the intuitive nature of visual feedback for movement quality analysis.
* **Applications:** Explores potential uses in fitness, physiotherapy, and other areas requiring movement understanding.
* **Research Question Addressed:** "How effectively can a real-time system combining monocular 3D pose estimation and dynamic 3D mesh visualization provide immediate, intuitive visual feedback for human movement analysis?"

## Thesis

For a detailed understanding of the research, methodology, and findings, please refer to the full thesis document:

* **Thesis PDF:** [Pose_Driven_MASS_Thesis__FYP___Copy___17_04_ (20).pdf](./Pose_Driven_MASS_Thesis__FYP___Copy___17_04_ (20).pdf)

## Website Template Acknowledgement

The project website template was adapted from the [Nerfies project page](https://nerfies.github.io/).
Thanks to the authors for making their template available.

@article{park2021nerfies,author    = {Park, Keunhong and Sinha, Utkarsh and Barron, Jonathan T. and Bouaziz, Sofien and Goldman, Dan B and Seitz, Steven M. and Martin-Brualla, Ricardo},title     = {Nerfies: Deformable Neural Radiance Fields},journal   = {ICCV},year      = {2021},}
## Website License

The content of the project website (`index.html` and associated assets adapted from the Nerfies template) is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

---

*This README provides an overview of the REMI project. For detailed setup and usage instructions for the individual code components (Aitviewer-RT and Ipman-RT), please refer to the README files within their respective repositories.*
