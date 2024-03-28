# Image-Super-resolution-using-Efficient-Subpixel-CNN

An approach to image super-resolution, integrating an Efficient Subpixel Convolutional Neural Network (CNN) with Residual Dense Blocks for enhanced performance.

The incorporation of Residual Dense Blocks adds depth and improves the model's capacity to capture intricate features within image datasets. Feature maps are extracted in its Low-Resolution space as opposed to earlier techniques where this was done in the High-Resolution space. In addition to the sub-pixel convolution layer, which learns an array of filters to upscale the final LR feature maps into the HR output, the Residual Dense Blocks (RDBs) heavily focuses on keeping the information extracted in previous layers alive, while computing outputs for the present layer.

**Dataset:**
DIV2K dataset- divided into train, test, validation-stored in High Resolution.


Drive link where datasets are stored: https://drive.google.com/drive/folders/1S__g_YZZLmWt9pG6omVcN_d3dEYCZc_h?usp=drive_link

