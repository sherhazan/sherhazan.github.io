---
title: "IndustRoPose: Zero Shot Real-Time 6D Pose Tracking for Industrial Robotic Manipulation"
collection: publications
type: "Paper"
permalink: /publication/2026-industropose
redirect_to: "https://sherhazan.github.io/IndustRoPose/"
excerpt: 'This paper is under review for ICRA 2026.'
date: 2026-06-01
citation: 'S. Hazan, N. Curtis, A. Agafonov, Z. Feldman, and D. Di Castro, "IndustRoPose: Zero Shot Real-Time 6D Pose Tracking for Industrial Robotic Manipulation", Under Review, ICRA: IEEE International Conference on Robotics and Automation, 2026.'
---

![2026-industropose](/images/6D_Pose_Tracker.png) 

## Abstract

Robotic assembly remains a core challenge in industrial automation, requiring high precision, real-time feedback, and adaptability across diverse parts and dynamic environments. While recent advances in 6D object pose estimation and foundation models offer promising capabilities, most approaches are evaluated in static environments and lack robust integration into industrial workflows. In this work, we introduce IndustRoPose, a real-time, zero-shot 6D pose tracker for industrial robotic manipulation. IndustRoPose integrates SAM2 for high-frequency segmentation with MegaPose for render-and-compare 6D pose estimation. Its mask-consistency scoring adaptively switches between tracking, refinement, and recovery modes, ensuring robustness under occlusion, motion blur, and visual ambiguity. IndustRoPose enables fast and easy onboarding of new objects using only a CAD model and a single annotated image, without task-specific retraining or simulation. We integrate IndustRoPose into the robot via a pose-based control policy that fuses perception with motion commands, maintaining stable tracking even during high-speed movements. To address flexible and scalable automation, we present IndustRobot, a modular framework for industrial robotic assembly. IndustRobot seamlessly integrates IndustRoPose with a skill-based manipulation layer, supporting adaptive behaviors and rapid task reconfiguration. This enables precise execution of contact-rich skills such as insertion, screwing, and part manipulation, while allowing skills to be reused or extended for new tasks with minimal programming. Finally, we demonstrate sub-millimeter pose accuracy and high task success rates, 96.7% for plug insertion and 97.5% for screwing, on real industrial assembly tasks, validating the practicality and robustness of the approach in dynamic environments.