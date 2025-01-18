# Res-KAN
ResNet-KAN is a hybrid deep learning model designed for efficient human action recognition. By combining a ResNet101 backbone for robust feature extraction with Kolmogorov-Arnold Networks (KANs) for modeling non-linear relationships, the model achieves high accuracy and adaptability. This architecture is applied to two widely recognized datasets for action recognition, demonstrating its versatility and effectiveness.

## Datasets:
### Penn Action Dataset
The Penn Action dataset contains annotated video frames of 15 diverse human actions, such as sports and fitness activities, including tennis serve, golf swing, and bench press. The dataset is preprocessed with frames resized to 224x224 resolution and normalized using ImageNet statistics.

### Human Action Recognition (HAR) Dataset
The HAR dataset, downloaded from Kaggle, provides a rich collection of labeled human actions captured in images. These actions are diverse, covering various physical activities. The dataset is preprocessed similarly, ensuring compatibility with the ResNet backbone.

## How to use the code
1. Clone the repository to your local machine or an editor like Google Colab (recommended)
2. For Penn Action dataset, download the dataset from https://dreamdragon.github.io/PennAction/ and save it as "data.zip" to Google Drive
3. Run the code as needed
