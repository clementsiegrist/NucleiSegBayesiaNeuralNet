# segmentation_probabilisticDL
## Quantification de l’incertitude de la segmentation sémantique de noyaux de cellules grâce aux réseaux de neurones bayésiens.

**Authors :** *Clément Siegrist*, *Ihab Bendidi*

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clementsiegrist/segmentation_probabilisticDL/blob/main/bayesiannet_segmentation.ipynb)

To consult and use our work on probabilistic segmentation with Bayesian Unet Open the Colab and follow the instructions. To learn more about our motivations and probabilistic deep-learning consult and download our report Projet_biomedical_bendidi_siegrist.pdf [here](https://github.com/clementsiegrist/segmentation_probabilisticDL/blob/main/segmentation_probabiliste.pdf) or/and [here](https://github.com/clementsiegrist/segmentation_probabilisticDL/blob/main/Prez_seg_bay.pdf) for our oral presentation slides. 

## Outline 

**I - Data Preparation & Pipelines**

**II - Model Training**
- *1 - Standard U-Net*
- *2 - Bayesian U-Net*

**III - Results & Comparison**
- *1 - Standard U-Net*
- *2 - Bayesian U-Net*

## Samples of our results

The figure below presents results performed on the test data. Both images and labels have been provided by Kaggle during the 2018 Data Science Bowl. The model also predicts the degree of certainty/uncertainty for its prediction each pixel by projecting a heatmap on the image, where the red color indicates the utmost uncertainty while the blue color indicates the utmost certainty of the prediction.

![GitHub Logo](https://github.com/clementsiegrist/segmentation_probabilisticDL/blob/main/logs/result_sample.png)
