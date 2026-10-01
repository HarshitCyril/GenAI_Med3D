# 3D Lung Visualizer 🫁

A medical imaging application that transforms 2D DICOM scan slices into interactive 3D volumetric models for surgical planning and lung volume analysis.

## Overview
Analyzing complex medical scans slice-by-slice can be time-consuming and hard to visualize spatially. This project automates that workflow by combining DICOM scan stacks into unified 3D spatial models, giving surgeons quick volume calculations and detailed structural insights directly from the raw scan data.

## Key Features
- **3D Volumetric Rendering:** Reconstructs continuous 3D pulmonary models from stacks of 2D DICOM files.
- **Automated Segmentation:** Applies deep learning models to identify target lung regions and calculate precise tissue volumes.
- **Containerized Pipeline:** Separates backend GPU processing microservices from the web interface for smooth performance.
- **Interactive Controls:** Supports real-time rotation, zoom, clipping planes, and density thresholding.

## Tech Stack
- **Backend & APIs:** Python, Node.js, Express, MERN Stack
- **Image Processing & ML:** PyTorch, OpenCV, SimpleITK, CUDA
- **3D & Rendering:** Docker, WebGL
- **Database:** MongoDB

## Quickstart

```bash
# Clone the repository
git clone [https://github.com/HarshitCyril/3d-lung-visualizer.git](https://github.com/HarshitCyril/3d-lung-visualizer.git)
cd 3d-lung-visualizer

# Build and launch with Docker
docker-compose up --build
