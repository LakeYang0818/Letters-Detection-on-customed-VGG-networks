# Letter Detection on customed VGG networks and Comparison of Solid and Hollow Letters Detection Models

## Introduction
This project focuses on building letter detection models and comparing the performance of detecting solid and hollow letters using a VGG (Visual Geometry Group) model. Our findings indicate that hollow letters outperform solid letters in detection tasks, emphasizing the effectiveness of neural networks, particularly for edge detection. This superiority stems from the distinctive features, reduced background noise, simplicity, and robustness inherent in hollow letters. In conclusion, this study reaffirms the suitability of neural networks for letter detection, leveraging the advantages of hollow letters

### Scope and Limitations
The scope of this project encompasses the evaluation of NN models for single-letter detection, utilizing a dataset comprising both solid and hollow letters.
The project does not delve into multiple-letter detection, and the letters are supposed to be horizontal without rotation in the image.

## Steps
### 1. Data Preparation
- Solid Letters dataset:
- Hollow Letters dataset:

### 2. Customized VGG Models

### 3. Comparisons of performances of solid and hollow models
|    | Solid Letters Model | Hollow Letters Model  |
| **Total Loss**<br>**Loss for class label loss**<br>**Loss forr bounding box loss** | ![Total Loss of Solid Letters Dataset]([image1.jpg](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/Evaluation%20Metrics%20for%20solid%20letters%20model.png))<br><br>   | ![Total Loss of Hollow Letters Dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/Evaluation%20Metrics%20for%20hollow%20letters%20model.png)<br><br>  |
| **Accuracy**  | ![Total Loss of Solid Letters Dataset]([image1.jpg](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/accuracy%20solid.png))  | ![Total Loss of Solid Letters Dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/accuracy%20hollow.png)  |







## Findings and Conclusion
- Summary of key findings and their significance.
- Conclusions regarding the effectiveness of detecting solid and hollow letters.
- Recommendations for future research or applications.
