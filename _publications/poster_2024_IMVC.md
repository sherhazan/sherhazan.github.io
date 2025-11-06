---
title: "Estimation of relative position between objects for robotic insertion of LDOs using classification learning methods"
collection: publications
type: "Posters & Presentations"
permalink: /publication/2024-imvc-poster
excerpt: 'Poster presentation at IMVC: Israel Machine Vision Conference, 2024.'
date: 2024-04-08
paperurl: "/files/Poster_IMVC_2024.pdf"
citation: 'S. Hazan, R. Schneor, and A. Fischer, "Estimation of relative position between objects for robotic insertion of LDOs using classification learning methods", IMVC: Israel Machine Vision Conference, Poster presentation, 2024.'
---

## Abstract

This work proposes a robust method for evaluating the relative position between LDOs in real-time assembly tasks. The proposed approach utilizes a classification CNN architecture with RGB-D data fusion. Several fusing approaches were tested and compared. In order to use classification CNN on a continuous problem, the scene space was divided into sub-areas as classes. The classification resulted with the prediction of probabilities of each class. Subsequently, these probabilities were combined using linear interpolation, resulting in an accurate evaluation of the relative position between the objects. For the validation process, three PegIn-Hole tasks were defined. An RGB-D realistic database was created for each task. Then, pre-processing and augmentation techniques were applied on the data. Finally, the CNNs were trained separately using the same setup to ensure comparable results. The method was evaluated by embedding and testing it in the insertion process of each task at the Technion and the in industry. The feasibility of the proposed method was demonstrated in those tasks, showing an automatic process with high performance.

## Poster Preview

![IMVC 2024 Poster Preview](/images/Poster_IMVC_2024.jpg) 