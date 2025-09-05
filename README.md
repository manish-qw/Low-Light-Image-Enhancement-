# Low-Light Image Enhancement | Zero Reference DCE-Net

## Project Overview
This project focuses on **low-light image enhancement** using a custom implementation of **Zero Reference Deep Curve Estimation Network (DCE-Net)**.  
The model is designed to improve the quality of images captured in poor lighting conditions, achieving better perceptual and quantitative results.

## Timeline
**Duration:** May 25 – June 25

## Key Contributions
- Designed an **8-layer DCE-Net** with **Batch Normalization** and **AdamW optimizer**, improving **PSNR** and **SSIM** metrics.  
- Integrated **Convolutional Block Attention Module (CBAM)** to prioritize important features and a **NAF-Net module** for effective post-enhancement denoising.  
- Performed **fine-tuning with data augmentation** and experimented with multiple activation functions (**ReLU, ELU, Mish**).  
- Reduced **total loss by 25%** and improved **convergence speed by 50%** compared to the baseline model.

## Skills & Technologies
- **Deep Learning, Computer Vision, Image Processing**  
- **Neural Network Architecture Design (DCE-Net, NAF-Net, CBAM)**  
- **Optimization Techniques (AdamW, Batch Normalization, Activation Functions)**  
- **Performance Evaluation (PSNR, SSIM)**  
- **Keras, Python**  

## Results
- Achieved significant improvements in image clarity and structure under low-light conditions.  
- Outperformed baseline models in both **quantitative metrics** and **convergence speed**.

## Future Work
- Explore transformer-based architectures for low-light enhancement.  
- Extend the model for **real-time video enhancement**.  
- Compare performance with diffusion-based approaches.

## References
- Zero Reference Deep Curve Estimation for Low-Light Image Enhancement (Chen et al., 2021)  
- NAF-Net: Nonlinear Activation Free Network for Image Restoration (Chen et al., 2022)  
- Convolutional Block Attention Module (Woo et al., 2018)  
