---
title: "Estimation of relative position between objects for robotic insertion of LDOs using classification learning methods"
collection: publications
type: "Thesis"
permalink: /publication/msc-thesis
excerpt: 'M.Sc Thesis completed at the Technion - Israel Institute of Technology, 2024.'
date: 2024-05-19
paperurl: "/files/thesis.pdf"
citation: Hazan, Sher, Anath Fischer, and Technion - Israel Institute of Technology. Faculty of Mechanical Engineering degree granting institution. “Estimation of Relative Position between Objects for Robotic Insertion of LDOs Using Classification Learning Methods / Sher Hazan ; [Supervision - Anath Fisher].” Technion - Israel Institute of Technology, 2024. Web.

---

## Abstract

Robotic integration in various industrial fields has long been a desirable goal, aiming to enhance production efficiency and reduce costs. However, one of the most prevalent challenges faced in the integration of robots into production lines is effectively handling different kinds of uncertainty, especially in assembly tasks. Such tasks often demand high precision for manual robot programming, particularly when inserting one part into another mechanically. To address this challenge and make production more cost-effective, robots should possess the ability to handle uncertainties in the assembly set-up. While existing methods have been successful to reduce uncertainty during assembly of rigid bodies by Integrating 3D models of objects. they fall short when dealing with non-rigid bodies. Non-rigid objects not only lack a readily available 3D model but also introduce additional uncertainty due to their flexible nature.
This work proposes a robust method for evaluating the relative position between both rigid and non-rigid objects in real-time assembly tasks. The proposed solution involves the development and demonstration of approach that fuses depth information with color information using different classification neural network architectures. In order to use classification architectures, we divide the assembly space into classes, which allowing the prediction of probabilities for belonging to each class. These probabilities are then combined using a linear interpolation technique, resulting in the accurate determination of the relative position between objects.
To validate our method, we defined three Peg-In-Hole tasks, varying in complexity. The tasks included a classic PID with rigid objects, wiring a 1 mm thick wire to a rigid connector, and the main challenge of wiring a non-rigid medical pipe to a non-rigid connector. The effectiveness of the method was evaluated testing each task in a robotic cell at the Technion. Furthermore, the real-world applicability and generalization of the method were validated by embedding it in an industrial-grade robotic cell.