This repository provides a custom tiny dataset for evaluating the effectiveness of Content-Based Image Retrieval (CBIR) models against the COCO-Val 2017 dataset (which contains 5,000 images).

We have carefully selected 37 challenging image pairs from COCO-Val 2017. Each pair consists of:
1 query image
1 corresponding target image (the expected retrieval result within COCO-Val)

Dataset Structure:
The dataset is organized into 37 folders.
Each folder contains exactly 2 images:
The query image
Its corresponding target image
In total, there are 74 images (37 queries + 37 targets).

Usage

You can use this dataset to:
Benchmark your CBIR model on difficult cases from COCO-Val 2017.
Validate whether a query retrieves its sole expected target image from the dataset.