Data set - https://drive.google.com/drive/folders/17xoSIAe-24-18iJiN3zKPqJl-RNDqIeW?usp=drive_link

Part 2 - Task 6: CNN Concept Explanation

What is convolution?
A convolution is a sliding window operation that scans the image and extracts important visual patterns (edges, curves, textures). It allows the network to learn spatial features automatically.

Why is pooling used?
Pooling downsamples features to reduce computation, overfitting, sensitivity to small shifts in the image.
Max pooling keeps the most important activation in each region.

Why is ReLU commonly used?
ReLU sets negative values to zero. It’s popular because it prevents vanishing gradients, is simple and fast and works well empirically in deep networks

Why are CNNs better than feed-forward networks for image data?
They exploit spatial structure in images and requires far fewer parameters. They learn local patterns first, then complex shapes.
Also, the model scale effectively to high-resolution images.

Part 2 - Task 7: Business Use Case Mapping

Domain: Manufacturing

A CNN-based defect classifier like this can automatically inspect product surfaces, detect scratches, dents, and stains in real time, eliminate manual visual inspection
reduce defect escape rates, improve quality control accuracy and consistency, eliminate manual visual inspection and reduce defect escape rates

This type of system is commonly deployed on production lines using cameras and edge‑devices.
