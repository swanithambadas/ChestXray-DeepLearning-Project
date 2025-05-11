# 🩺 LungVision - ChestXray

> A collection of Jupyter notebooks exploring deep learning for chest X-ray classification using autoencoders and transfer learning.

## Description

This repo contains step-by-step experiments and a final pipeline for classifying chest X-ray images into healthy vs. pneumonia cases. You’ll find:

- **Autoencoder prototype** ([`manishbi_hsriram_swanitha_autoencoder_cnn.ipynb`](./manishbi_hsriram_swanitha_autoencoder_cnn.ipynb))  
- **Baseline pipelines & preprocessing** ([`manishbi_hsriram_swanitha_project_checkpoint1.ipynb`](./manishbi_hsriram_swanitha_project_checkpoint1.ipynb))  
- **Transfer learning** with:
  - [VGG19](https://keras.io/api/applications/vgg/) ([`manisbi_hsriram_swanitha_vgg19.ipynb`](./manisbi_hsriram_swanitha_vgg19.ipynb))
  - [ResNet50](https://keras.io/api/applications/resnet/) ([`manishbi_hsriram_swanitha_project_checkpoint2_resnet.ipynb`](./manishbi_hsriram_swanitha_project_checkpoint2_resnet.ipynb))
  - [DenseNet121](https://keras.io/api/applications/densenet/) ([`manishbi_hsriram_swanitha_project_checkpoint2_densenet.ipynb`](./manishbi_hsriram_swanitha_project_checkpoint2_densenet.ipynb))
  - [InceptionV3 (GoogLeNet)](https://keras.io/api/applications/inception_v3/) ([`googlenet.ipynb`](./googlenet.ipynb))
- **Final integrated pipeline & evaluation** ([`fin_last.ipynb`](./fin_last.ipynb))  
- **Presentation slides** ([`Team9_presentation_final_project.pptx`](./Team9_presentation_final_project.pptx))

---

## ✨ Interesting Techniques

- **Convolutional Autoencoder** for unsupervised feature extraction ([Keras example](https://keras.io/examples/vision/autoencoder/))  
- **Transfer Learning** using pre-trained CNNs: VGG19, ResNet50, DenseNet121, InceptionV3  
- **Real-time Data Augmentation** via [Keras ImageDataGenerator](https://keras.io/api/preprocessing/image/)  
- **Callback Management** with [EarlyStopping](https://keras.io/api/callbacks/early_stopping/) and [ModelCheckpoint](https://keras.io/api/callbacks/model_checkpoint/)  
- **Training Visualization** using [matplotlib](https://matplotlib.org/) & [seaborn](https://seaborn.pydata.org/) for loss/accuracy curves and confusion matrices  

---

## 🛠️ Non-Obvious Technologies

- [TensorFlow 2.x](https://www.tensorflow.org/) – core deep learning framework  
- [Keras](https://keras.io/) – high-level neural network API  
- [seaborn](https://seaborn.pydata.org/) – statistical data visualization  
- [Jupyter Notebook](https://jupyter.org/) – interactive experiment environment  
- [python-pptx](https://python-pptx.readthedocs.io/) – (optional) automate slide generation  

---

## 📁 Project Structure

```bash
.
├── Team9_presentation_final_project.pptx      # Final slide deck
├── fin_last.ipynb                             # Integrated pipeline & evaluation
├── googlenet.ipynb                            # InceptionV3 (GoogLeNet) experiments
├── manisbi_hsriram_swanitha_vgg19.ipynb       # VGG19 transfer learning
├── manishbi_hsriram_swanitha_autoencoder_cnn.ipynb  # Convolutional autoencoder prototype
├── manishbi_hsriram_swanitha_project_checkpoint1.ipynb  # Data prep & baselines
├── manishbi_hsriram_swanitha_project_checkpoint2_densenet.ipynb  # DenseNet121 experiments
└── manishbi_hsriram_swanitha_project_checkpoint2_resnet.ipynb    # ResNet50 experiments
