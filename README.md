# C. elegans Video Segmentation Pipeline

A Python-based computer vision tool designed to automate the tracking and extraction of isolated instances of *C. elegans* from video sequences. 

This project is being developed within the **Computer Vision Research Laboratory (CVRL)** at the **University of Notre Dame** under the mentorship of Professor Patrick Flynn.

---

## Overview

Tracking microscopic organisms like *C. elegans* is challenging due to low-contrast environments, shifting backgrounds, and irregular biological movements. The goal of this pipeline is to ingest raw laboratory video footage, isolate individual organisms, and generate high-fidelity segmented masks for behavioral analysis.

Currently, the project focuses on the **core segmentation and data extraction architecture**.

---

## Current Implementation & Features

*   **Video Processing:** Scripts to ingest video corpus files frame-by-frame and handle preprocessing.
*   **Instance Isolation:** Automated contour detection and thresholding techniques to isolate distinct *C. elegans* specimens from the background.
*   **Mask Generation:** Extraction of clean, isolated binary masks of the organisms to prepare data for downstream analysis.
*   **Core Stack:** Python, OpenCV, NumPy, Matplotlib.

---
