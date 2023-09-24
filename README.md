# EfficientNetV2B0-PlantVillage

Plant disease detection on PlantVillage dataset using EfficientNetV2-B0.
In this code, I focused on only 6 labels of this dataset. First PlantVillage dataset has been downloaded and loaded. Then these 7 labels has been seperated for preprocessing step. Processing step includes 2 main stages: resizing and augmentation. After preprocessing, I used EfficientNetV2B0 with pre-traind weights of Imagenet dataset. After fine-tuning, for a better analysis, Macro, Micro, and Weighted has been calculated for Precision, Recall, and F1-score. Moreover, the confusion matrix has been shown. At last, EfficientNetV2B0 could achieve around 98% accuracy on these 7 classes.
