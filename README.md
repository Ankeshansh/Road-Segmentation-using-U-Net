# Road Segmentation using U-Net  

This project focuses on **semantic segmentation of roads** using deep learning. A **U-Net model** is trained on the **Cityscapes dataset** to detect road regions from aerial and street-view images.  

##  Features  
- **Deep Learning-based Segmentation**: Uses a U-Net model to accurately segment roads.  
- **Cityscapes Dataset**: Utilizes high-resolution urban street-view images.  
- **Preprocessing Pipeline**: Image resizing, normalization, and augmentation.  
- **Performance Metrics**: Achieved an **accuracy of 0.81** using a custom convolutional block.  

##  Dataset  
- Dataset: **Cityscapes**  
- Classes: Road segmentation mask  
- Image Type: RGB with annotated ground truth  

##  Model Pipeline  
1. **Data Preprocessing**: Image normalization and augmentation  
2. **Training**: U-Net architecture with custom convolutional and upsampling blocks  
3. **Evaluation**: Assessed with segmentation accuracy and IoU  
4. **Inference**: Tested on new road images for real-world application

###  Model Performance  

| Model  | Accuracy | IoU  |
|--------|---------|------|
| U-Net  | 0.81    | 0.78 |

The results indicate that the U-Net model performs well in segmenting road structures with high accuracy. The segmentation output aligns closely with the ground truth masks. 

##  Installation  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/your-repo/road-segmentation.git
cd road-segmentation
pip install -r requirements.txt
