# Assignment 3

---

## Overview
This assignment covers three major topics:
1. **Graph Cut Segmentation (GrabCut)**  
   - Detect person using a pretrained model.  
   - Apply `cv2.grabCut` for 1, 3, and 5 iterations.  
   - Visualize original, mask, and segmented results.

2. **Fully Convolutional Network (FCN)**  
   - Implement FCN with pretrained ResNet backbone.  
   - Compare upsampling: **Transpose Convolution vs Bilinear Interpolation**.  
   - Evaluate using Pixel Accuracy and Mean IoU.

3. **Variational Autoencoder (VAE)**  
   - Train on MNIST dataset.  
   - Visualize reconstruction, random generation, and latent interpolation.  
   - Compare results with latent dim = 128 vs 256.

---

## Summary
| Task | Topic | Key Focus | Result |
|------|--------|-----------|--------|
| 1 | Graph Cut | Classical segmentation | Foreground extraction successful |
| 2 | FCN | Deep learning segmentation | Bilinear outperformed Transpose |
| 3 | VAE | Representation learning | Smooth reconstruction and latent transitions |


---

🧑‍💻 **Aphisit (st126130)**
