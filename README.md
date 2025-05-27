# Deep Learning-Based Land Cover Assessment Using Satellite Imagery

## Overview

This project presents a deep learning-based solution for land use and land cover (LULC) classification using high-resolution satellite imagery. The model is based on the **U-Net architecture**, which is highly effective for semantic segmentation tasks. It was trained on a large-scale remote sensing dataset to classify six different land cover classes.

## Key Features

- **Model Architecture**: U-Net (Convolutional Encoder-Decoder)
- **Dataset**: Large remote sensing imagery dataset with labeled land cover classes
- **Number of Classes**: 6 land cover types
- **Accuracy Achieved**: **91.70%**
- **Training Epochs**: **25** *(limited by computational resources)*
- **Application Areas**: Environmental monitoring, urban planning, land use analysis

## Results

The images below show a sample result from the **Noida region**, captured using **Google Maps Satellite View**.

![image](https://github.com/user-attachments/assets/f716be6b-7e9e-4c65-88dd-1cc2f96f9ff7)

### Color Legend (Predicted Image):
- 🟨 **Yellow**: Vegetation  
- 🟦 **Cyan**: Water bodies  
- 🟪 **Purple**: Concrete surfaces (roads, buildings)

The predicted segmentation effectively distinguishes between different land use categories, showcasing the model’s ability to extract meaningful spatial patterns from satellite images.  
**However, the results could have been further improved if the model had been trained for more epochs.** Due to limited computational resources, the training was capped at 25 epochs.

## Running the Code

To run the classification pipeline:

```bash
Open and run `Image_classification.ipynb`
