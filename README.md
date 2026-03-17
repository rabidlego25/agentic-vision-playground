# agentic-vision-playground
Agentic computer vision playground for benchmarking AI coding workflows with CNNs, U-Nets, segmentation, classification, and automated experiment reporting.

## Overview

This project is a small but complete computer vision lab designed for **agentic programming experiments**. It uses a well-known image dataset to support tasks such as **image classification**, **image segmentation**, **visualization**, and **automated reporting**.

The main goal is not just to train models, but to create a clean environment for testing how well an AI coding agent can:

- scaffold a project,
- prepare data,
- train and evaluate models,
- debug issues,
- compare experiments,
- and produce useful documentation.

The project is intentionally practical, visual, and easy to inspect so that both model behavior and agent behavior can be evaluated clearly.

## Main Goals

- Build a reproducible computer vision workflow around a famous dataset
- Train a **CNN baseline** for classification
- Train a **U-Net** for segmentation
- Generate visual outputs for predictions and masks
- Save metrics, artifacts, and run summaries
- Use the project as a benchmark for **agent autonomy, reliability, and iteration quality**

## Planned Tasks

The project is centered around two core vision tasks:

### 1. Classification
A baseline CNN will classify images into pet breed categories.

### 2. Segmentation
A U-Net model will predict segmentation masks for pets in images.

### 3. Explanation and Reporting
The system will generate example outputs showing:

- original image,
- predicted label or mask,
- ground truth where available,
- and concise run summaries in Markdown.

## Why This Project

This repository is meant to be a realistic but manageable benchmark for agentic ML workflows.

It is useful because it is:

- **visual** — outputs can be inspected quickly,
- **practical** — it includes real ML engineering tasks,
- **modular** — components can be swapped or extended,
- **benchmark-friendly** — it exposes setup, training, debugging, evaluation, and reporting tasks in one place.

Rather than optimizing for state-of-the-art accuracy, the focus is on **workflow quality** and **repeatable experimentation**.

## Benchmark Use Case

This project is designed to help answer questions like:

- Can an agent create a working training pipeline?
- Can it recover from broken paths, bad configs, or tensor shape bugs?
- Can it compare a CNN and a U-Net with minimal manual intervention?
- Can it save outputs and write a meaningful experiment summary?

Example benchmark dimensions include:

- **Build success**
- **Debugging robustness**
- **Experiment management**
- **Artifact generation**
- **Documentation quality**
