---
title: Docs
type: book  # Do not modify.
toc: false
---

Welcome to the _introduction_!

Deep learning in retinal imaging (using e.g. optical coherence tomography volumes) offers great potential to transform research in eye diseases. One of the  big challenges in deep learning is producing high-quality labels for (semi-, self- or full-) supervised learning. For tasks like semantic segmentation in OCT images pixel-level labels are produced in a time-consuming and tedious effort. To ease this task and to support democratization of deep learning research for ophthalmologists and computer scientists, we prepared a large annotated dataset with multiple gradings. The quality of labels is important to train accurate models and to compare with human-level performance. We present a new data set, comprising 1668 annotated grayscale images of 2 different disease types and 1 normal/healthy group obtained with a Heidelberg Spectralis device. The images are divided between intermediate AMD, Diabetes and normal/healthy scans. Every image in the data set was annotated by expert graders who followed the same instructions. The images are selected from a pool of 150 OCT volumes. In a first step, 21 AMD volumes, 19 DME volumes and 20 healthy/normal volumes (19-69 Bscans/volume; 1668 total number of scans) from each group are selected for annotation. In each image the graders annotated 5 retinal layers using a custom-built image labeling platform. All images were graded independently 3 times. With 5004 annotations and ~30024 segmented bands, our collection offers a unique and heterogeneous training data set for retinal imaging deep learning application development.
