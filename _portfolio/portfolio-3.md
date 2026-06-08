---
title: "Cross-Domain Deception Dataset"
excerpt: "Dissertation Research<br/><img src='/images/featured.jpg'>"
collection: portfolio
---

# Cross-Domain Deception Dataset (CD3)

## Description

The **Cross-Domain Deception Dataset (CD3)** contains frame-level visual features extracted from interview video recordings to support research in deception detection using facial expressions, action units, gaze, and body/hand gestures.

Using a commercial laptop and Microsoft Teams, **45 participants** completed mock interviews across two sessions, responding to questions about biography, academic success, and well-being.

The dataset provides **1,270 truthful clips** and **587 deceptive clips**, enabling cross-domain analysis of how deception appears differently across content areas and supporting research into well-being–specific deception models.

## Included Features

Each sample includes **983 frame-level features**, including:

### Gaze

* 8 gaze features
* Direction vectors
* Gaze angles

### Landmarks

* 136 × 2D facial landmarks
* 204 × 3D facial landmarks
* 112 × 2D eye landmarks
* 168 × 3D eye landmarks
* 140 × 2D face keypoints

### Head Pose

* Translation: x, y, z
* Rotation: pitch, yaw, roll

### Face Shape

* 40 PCA-based shape parameters

### Facial Action Units

* 35 total action unit features

  * 18 presence features
  * 17 intensity features

### Body & Hands

* 50 body keypoints, 2D
* 84 hand keypoints, 2D

### Labels & Identifiers

* Deception label

  * `1 = deceptive`
  * `0 = truthful`
* Participant ID

  * Format: `PXXX`

## File Format

* Provided in `.csv` format
* Each row represents one video frame from a participant response

## Suggested Uses

* Deception detection, including cross-domain and well-being–specific modeling
* Action unit and gaze-based behavioral modeling
* Gesture and micro-expression analysis
* Domain adaptation and cross-domain inference
* Multimodal vision features for cognitive state estimation
* Representation learning for social and behavioral computing

## Educational & Research Use

This dataset is available for coursework, capstone projects, theses, and experimentation in deception detection, behavioral modeling, and multimodal machine learning.

## Citation

S. L. King and T. Neal, “Exploring Vision-Based Features for Detecting Deception in Well-Being: A Cross-Domain Comparison,” *2025 IEEE 19th International Conference on Automatic Face and Gesture Recognition (FG)*, Tampa/Clearwater, FL, USA, 2025, pp. 1–10, doi: `10.1109/FG61629.2025.11099290`.
