---
title: "Research"
date: 2026-03-21
draft: false
layout: "research"
description: "Research by Zilong Ji on computational neuroscience, theta sweeps, hippocampal and entorhinal circuits, virtual reality experiments, and brain-inspired AI."
---

## Computational Neuroscience

<div class="research-gif-row">
  <img src="/movies/gridcell_sweeps.gif" alt="Grid cell sweeps" class="research-gif">
</div>

[Ji et al., 2025, Current Biology](https://www.cell.com/current-biology/fulltext/S0960-9822(24)01174-6?uuid=uuid%3A47a8abd3-bd6d-4c23-a93c-e7f26e5af58e)

I develop computational models to understand how the brain supports spatial navigation, episodic memory. Recently, I built a biophysical [model](https://www.cell.com/current-biology/fulltext/S0960-9822(24)01174-6?uuid=uuid%3A47a8abd3-bd6d-4c23-a93c-e7f26e5af58e) of the parasubiculum–entorhinal microcircuit and modelled the generation of left–right theta sweeps recently discovered in the brain ([Vollan et al, 2025](https://www.nature.com/articles/s41586-024-08527-1)). This model led to the discovery of two interesting phenomena in the brain. One was the finding of [theta phase coding in directional tuning cells in the anteroventral thalamus nuclei (AVN)](https://onlinelibrary.wiley.com/doi/full/10.1002/hipo.70008), and the other was the finding of [a gradient of theta-sweep angle along the dorsoventral axis in medial entorhinal cortex](https://www.biorxiv.org/content/10.64898/2026.03.08.710351v1.article-metrics).

Based on these recent findings, I am interested in the function of theta sweeps and in why the brain generates theta sweeps rather than tracking the animal’s behaviour accurately. A recent attempt can be found [here](https://2025.ccneuro.org/abstract_pdf/Marshall_2025_Efficient_spatial_learning_hippocampus_via_left-right.pdf) in a CCN poster. The biological brain develops such dynamics for a specific reason, but what is that reason? Why does the brain maintain these dynamics? What is the connection between theta sweeps and cognitive map theory?



## Experimental Neuroscience

<div class="research-media-row">
  <div class="research-media-card research-media-card-image">
    <img src="/images/2DVR.jpg" alt="2D virtual reality setup" class="research-media">
  </div>
  <div class="research-media-card research-media-card-video">
    <video autoplay muted loop playsinline controls class="research-media">
      <source src="/movies/2dVR_demo.mp4" type="video/mp4">
      Your browser does not support MP4 playback. <a href="/movies/2dVR_demo.mp4">Download the movie</a>.
    </video>
  </div>
</div>

(In preparation, but see a epys design from the Burgess lab [here](https://elifesciences.org/articles/34789))

Over the past four years, I have developed a two-photon imaging system that allows us to image the mouse brain while the animal navigates in a virtual reality environment. Compared with other setups, in which the mouse’s head must be fixed so that the same population of neurons appears at the same location in successive images, the system I developed mounts the animal’s head without fixing it, allowing the animal to rotate freely through 360 degrees as if navigating in an immersive two-dimensional virtual reality environment. With advanced image-processing techniques and the latest NVIDIA graphics cards, we are able to perform online drift correction, enabling us to track hundreds of cells simultaneously during long recording sessions.

These techniques allow us to address questions that could not previously be studied in head-fixed animals navigating linear-track environments, where they cannot turn their heads. This makes it possible to investigate neuroscience questions in a more naturalistic setting while still allowing precise manipulation of environmental features through virtual reality.

## Brain-inspired AI

Brain-inspired AI could have significant impact by guiding the development of learning systems that are more efficient, adaptive, and robust. Because biological neural systems learn from limited data, retain useful knowledge over time, and flexibly adjust to changing environments, they offer important principles for addressing core challenges in AI such as few-shot learning, continual learning, and generalisation.

I developed an unsupervised few-shot deep-learning algorithm [paper](https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2020.00083/full) and applied it to computer vision tasks, such as pedestrian identification [paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730018.pdf). Later, in collaboration with Xiaolong Zou, I proposed a dual-pathway deep learning model that mimics the dorsal-ventral visual pathways in the primate brain [paper](https://www.sciencedirect.com/science/article/pii/S0893608023004069).

Currently, I am interested in how principles from neural systems—specifically the hippocampal formation—can inspire efficient algorithms for learning, memory, and adaptive computation in AI. 
