# Foundation Models in High-Energy Physics

Course project exploring foundation models and self-supervised learning for particle physics.

## Project Overview

This project investigates how ideas from foundation models and self-supervised learning can be applied to high-energy physics data.

The project focuses on a review of **PoLAr-MAE**, a masked autoencoder developed for learning representations from LArTPC particle physics data.

The main questions explored include:

- What are foundation models?
- How can self-supervised learning be applied to scientific data?
- How do masked autoencoders learn representations?
- What can a model learn from particle physics data without explicit labels during pretraining?

## PoLAr-MAE

PoLAr-MAE uses masked autoencoding as a self-supervised learning objective.

A simplified conceptual workflow is:

```text
Input detector data
        │
        ▼
Mask part of the input
        │
        ▼
      Encoder
        │
        ▼
Learned representation
        │
        ▼
      Decoder
        │
        ▼
Reconstruct masked input
