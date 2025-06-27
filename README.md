# Dog vs Cat Classification using Pre-trained ResNet-101 Model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DVezhbUFmZGFa9BClWhSwC4ZgILWE3js?usp=sharing)
[![Python](https://img.shields.io/badge/Python_3.9_+-3776AB?logo=python&logoColor=FF6F00)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-FF6F00?logo=tensorflow)](https://tensorflow.org)

<!--
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?logo=pytorch)](https://pytorch.org)
-->


> **Brief Description:** This project implements a dog and cat image classification model using the pre-trained ResNet-101 architecture with the PyTorch library. The model is fine-tuned on the Microsoft Cats and Dogs Dataset to distinguish between images of dogs and cats.


## 📊 Dataset

### Dataset Information

- **Name:** Microsoft Cats and Dogs Dataset
- **Source:** Kaggle (downloaded via the provided Microsoft link)
- **Size:** Approximately 25,000 images (after removing corrupted files), split into training and validation sets.
- **Format:** JPEG image files.

## 🧠 Model Architecture

The project utilizes the ResNet-101 model, pre-trained on the ImageNet-1K dataset. The final fully connected layer of the ResNet-101 model is modified to output predictions for two classes: 'Cat' and 'Dog'.


## 📈 Results

The notebook provides a visualization of sample predictions and a comparative error analysis.

<table>

<tr>
<td align="center">

#### MODEL PERFORMANCE SAMPLE

</td>

</tr>

<tr>
<td>

![Performance Comparison](https://raw.githubusercontent.com/ritanjit/Dog_vs_Cat_ResNet101/main/model_predictions.png) 

</td>
</tr>
</table>


## ⚙️ Configuration

### How to Run the Code

1.  **Open in Google Colab:** Click the "Open in Colab" badge.
2.  **Run the cells:** Execute the code cells sequentially from top to bottom.
3.  **Explore the results:** The notebook includes visualizations of sample predictions and a comparative error analysis.
### Files

*   `.ipynb`: The main Colab notebook containing all the code.
*   `model_predictions.png`: A figure visualizing the predicted classes using the model.

## 🚀 Future Work

*   Experiment with different hyperparameters for each model.
*   Implement additional model architectures (e.g., DenseNet, VGG).
*   Explore data augmentation techniques to further improve performance.
*   Analyze misclassifications in more detail to understand model weaknesses.

---

<div align="center">

**⭐ Star this repo if you found it helpful!**
-->

Made with ❤️ by [Ritanjit](https://github.com/ritanjit)

</div>
