# VATT Multimodal Learning Exploration - DA323 Course Project

Welcome to the repository for my DA323 Course Project at the Indian Institute of Technology, Guwahati. This project focuses on exploring the **Video-Audio-Text Transformer (VATT)**, a groundbreaking convolution-free framework introduced at NeurIPS 2021 for multimodal self-supervised learning from raw video, audio, and text data.

## Overview

This repository contains the materials and documentation for a comprehensive study of VATT, including a detailed presentation, Jupyter Notebook with a blog-style explanation, and related resources. The project was completed as part of the DA323 course requirements and presented on May 8, 2025.

## Project Description

The Video-Audio-Text Transformer (VATT) represents a significant advancement in multimodal learning by leveraging Transformer architectures to process raw, unlabeled data across video, audio, and text modalities. This project explores VATT's motivation, historical context, key learnings, technical approach, experimental setups, results, personal insights, and potential areas for improvement.

### Key Highlights of VATT
- **Convolution-Free Architecture**: Outperforms traditional CNNs without relying on convolutional biases, achieving 82.1% top-1 accuracy on Kinetics-400 (video) and 39.4% mAP on AudioSet (audio).
- **Self-Supervised Learning**: Uses contrastive losses (NCE and MIL-NCE) to align modalities on unlabeled datasets like HowTo100M and AudioSet.
- **Modality-Agnostic Potential**: Demonstrates a single-backbone Transformer with shared weights across modalities, performing comparably to modality-specific models.
- **DropToken Innovation**: Reduces computational complexity by dropping tokens during training, enabling high-resolution inputs with lower costs.
- **Transferability**: Achieves 78.7% top-1 accuracy on ImageNet despite pre-training on video data, showcasing cross-domain generalizability.

## Repository Contents

- **Presentation Slides**: A 23-slide PowerPoint presentation (`VATT_PPT.pdf`) covering all aspects of VATT, from motivation to results and future scope.
- **Jupyter Notebook**: A blog-style explanation (`VATT_Blog.ipynb`) with detailed sections on motivation, historical perspective, key learnings, approach, results, surprises, scope for improvement, and references. Includes visualizations and code snippets for performance metrics.
- **Youtube Video**: <a href="https://youtu.be/xy1Ji365y-I" target="_blank">Watch Here</a>


## Project Structure in Notebook

1. **Title & Author**: Introduction to the project and presenter details.
2. **Motivation**: Why VATT is a significant advancement in AI, focusing on cost reduction, raw data processing, and outperforming CNNs.
3. **Historical Perspective**: Evolution from CNNs to Transformers, and the rise of multimodal learning leading to VATT.
4. **Key Learnings**: Insights into convolution-free Transformers, self-supervised learning, modality-agnostic potential, DropToken, and transferability.
5. **Approach**: Technical details on tokenization, DropToken, Transformer architecture, common space projection, and contrastive learning.
6. **Experiments & Results**: Pre-training setup, downstream evaluation across 10 datasets, and detailed performance metrics (video, audio, image, retrieval tasks).
7. **Reflections**: Personal surprises (e.g., transferability, CNN parity) and scope for improvement (e.g., text quality, computational efficiency).
8. **References**: Citation of the original VATT paper and related works.

## How to Use This Repository

1. **View the Presentation**: Download and review `MMDP_PROJECT.pdf` for a visual and detailed walkthrough of VATT.
2. **Explore the Notebook**: Open `VATT_Blog.ipynb` in Jupyter Notebook or JupyterLab to read the blog-style explanation, view visualizations, and run code snippets if applicable.
3. **Learn More**: Check the references section for the original VATT paper and related resources to dive deeper into multimodal learning.

## Installation & Setup

To view the Jupyter Notebook:
Clone the repository
[git clone https://github.com/raunitpatel/DA323---Course-Project/](https://github.com/raunitpatel/DA323---Course-Project.git)
cd DA323---Course-Project

Install dependencies 

Open the notebook
jupyter notebook VATT_Blog.ipynb
