# Panorama Stitcher — Groupe_Alaoui

**ESIN, UIR — Introduction to Computer Vision — Spring 2026**
Professor: Ilias TOUGUI

## Group members
- Mohamed Anouar FARESS
- Mohammed Yassine BEN MEZIANE
- Imad Eddine EL KHORASSANI
- Anys LOUZAL

## Project
Project 4 — Panorama Stitcher (Intermediate, max 18/20). Stitch two or more overlapping images into a seamless panorama using Harris corner detection (from scratch), local patch descriptors, SSD keypoint matching, homography estimation with RANSAC, perspective warping and alpha blending.

## Repository structure
data/images/ — input image sets | data/output/ — generated panoramas | data/README.txt — dataset description | code/panorama_stitcher.ipynb — main notebook | report.pdf — project report

## How to run
1. Place overlapping images in data/images/set1/
2. Open code/panorama_stitcher.ipynb
3. Run all cells from top to bottom
4. Output saved to data/output/panorama_result.jpg

## Dependencies
pip install numpy opencv-python matplotlib scipy
