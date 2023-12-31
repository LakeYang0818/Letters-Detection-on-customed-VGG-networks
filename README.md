# Letter Detection on customed VGG networks and Comparison of Solid and Hollow Letters Detection Models

## Introduction
This project focuses on building letter detection models and comparing the performance of detecting solid and hollow letters using a VGG (Visual Geometry Group) model. Our findings indicate that hollow letters outperform solid letters in detection tasks, emphasizing the effectiveness of neural networks, particularly for edge detection. This superiority stems from the distinctive features, reduced background noise, simplicity, and robustness inherent in hollow letters. In conclusion, this study reaffirms the suitability of neural networks for letter detection, leveraging the advantages of hollow letters

### Scope and Limitations
The scope of this project consists of evaluating neural network models for single-letter detection using a dataset consisting of both solid and hollow letters. This project does not deal with multiple letter detection, the letters should be horizontal in the image with no rotation.

## Steps
### 1. Data Preparation
- [Solid Letters dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/Dataset%20Design%20for%20Solid%20Letters.ipynb)
- [Hollow Letters dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/Dataset%20Design%20for%20Hollow%20Letters.ipynb)

### 2. Customized VGG Models
- [Solid Letters Model](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/Object%20Classification%20and%20Localization.ipynb)
- [Hollow Letters Model](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/Object%20Classification%20and%20Localization.ipynb)

### 3. Comparisons of performances of solid and hollow models
|    | Solid Letters Model  | Hollow Letters Model  |
|-----------|-----------|-----------|
| **Total Loss, Loss for class label loss, Loss for bounding box loss** | ![Total Loss of Solid Letters Dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/Evaluation%20Metrics%20for%20solid%20letters%20model.png) | ![Total Loss of Hollow Letters Dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/Evaluation%20Metrics%20for%20hollow%20letters%20model.png)  |
| **Accuracy**  | ![Total Loss of Solid Letters Dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/accuracy%20solid.png)  | ![Total Loss of Solid Letters Dataset](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/accuracy%20hollow.png)  |

### 4. Sample Output
- [Solid Letters Sample](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Solid%20Letters%20Model/Object%20Classification%20and%20Localization%20Inference.ipynb)
- [Hollow Letters Sample](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/blob/main/Hollow%20Letters%20Model/Object%20Classification%20and%20Localization%20Inference.ipynb)
![image](https://github.com/LakeYang0818/Letters-Detection-on-customed-VGG-networks/assets/91699109/a4a6a236-2616-4d22-b580-da762d08e8d2)


## Findings and Conclusion
- 
