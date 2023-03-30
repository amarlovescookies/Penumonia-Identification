# Penumonia Identification
### By: Sang Ik Han, Byung Hui Yoon, Philipp Gaissert, and Amar Mohanty
Pneumonia is a deadly disease where the lungs fill with fluid making breathing difficult. Traditionally,
identification of pneumonia requires radiologists to look at chest x-ray scans of patients. We aim to
automate this process using machine learning. In this study, we evaluated DenseNet, LeNet-5, AlexNet,
and custom CNN to classify chest x-ray images from Kaggle. We found that a pre-trained DenseNet
model with transfer learning performed the best with 90.06% accuracy and 92.43% F1 score. Out of the
four models we explored, we found that more complex models tend to perform better if some level of
regularization was applied.

### Set-Up
**Prerequistes: numpy, pandas, torch, torchvision, PIL, matplotlib**
1. Clone the project to your local environment
2. Download the prequiste packages
3. Open your desired model notebook and run the notebook.

**We included the Jupyter Notebooks that we used to train and test the models used in this research paper.**
- AlexNet.ipynb
  - Notebook to train and test AlexNet Model
- CNN.ipynb
  - Notebook to train and test CNN Model
- DenseNet.ipynb
  - Notebook to train and test DenseNet Model
- LeNet5.ipynb
  - Notebook to train and test LeNet5 Model

**We used a pneumonia chest x-ray dataset found on [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)**
