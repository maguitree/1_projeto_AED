# AED 2025 — Project 1: Images with indexed colors (Pseudocolors)

## Authors
Margarida Pinheiro 
125011

Miguel Sousa 
125624

## Description
This project implements a modular C library (`imageRGB`) for handling and processing RGB images. Unlike standard raster implementations that store full RGB triplets for every pixel, this module utilizes a **Look-Up Table (LUT)** architecture. Pixels are stored as integer indices pointing to a shared color palette, simulating indexed color formats (similar to GIF) to optimize memory usage for images with limited color depth.

## Main funtions implemented
- Image ImageCopy(img)
- int ImageIsEqual(img1, img2)
- Image ImageRotate90CW(img)
- Image ImageRotate180CW(img)
- int ImageRegionFillingRecursive(img, u, v, color)
- int ImageRegionFillingWithQUEUE(img, u, v, color)
- int ImageRegionFillingwWithSTACK(img, u, v, color)
- int ImageSegmentation(img, fillFunct)

## References
- Guião do 1º projeto de AED - 2025/2026
- Documentação fornecida nos ficheiros já feitos
- Slides das aulas teóricas de AED
- GeeksforGeeks. (n.d.). Flood Fill Algorithm – Explained with Examples. Disponível em: https://www.geeksforgeeks.org/flood-fill-algorithm/
