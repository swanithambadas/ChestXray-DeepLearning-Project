<p align="center">
  <img src="assets/demo.gif" alt="LungVision Demo" width="80%"/>
</p>

<h1 align="center">🩺 LungVision - ChestXray Classification</h1>
<p align="center"><strong>Autoencoder, Transfer Learning & Pneumonia Detection Pipeline</strong></p>

<p align="center">
  <a href="#notebooks">📓 Notebooks</a> •
  <a href="#techniques">🔬 Techniques</a> •
  <a href="#technologies">📚 Technologies</a> •
  <a href="#structure">📁 Structure</a> •
  <a href="#contributors">👥 Contributors</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-2.6-red?logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-1.21-blue?logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-1.3-lightblue?logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-3.4-purple?logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-0.11-9cf?logo=seaborn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white"/>
</p>

---

## 📓 Notebooks

- **Autoencoder Prototype** ([`manishbi_hsriram_swanitha_autoencoder_cnn.ipynb`](./manishbi_hsriram_swanitha_autoencoder_cnn.ipynb))  
- **Baseline Preprocessing** ([`manishbi_hsriram_swanitha_project_checkpoint1.ipynb`](./manishbi_hsriram_swanitha_project_checkpoint1.ipynb))  
- **VGG19 Transfer Learning** ([`manisbi_hsriram_swanitha_vgg19.ipynb`](./manisbi_hsriram_swanitha_vgg19.ipynb))  
- **ResNet50 Pipeline** ([`manishbi_hsriram_swanitha_project_checkpoint2_resnet.ipynb`](./manishbi_hsriram_swanitha_project_checkpoint2_resnet.ipynb))  
- **DenseNet121 Experiments** ([`manishbi_hsriram_swanitha_project_checkpoint2_densenet.ipynb`](./manishbi_hsriram_swanitha_project_checkpoint2_densenet.ipynb))  
- **InceptionV3 (GoogLeNet)** ([`googlenet.ipynb`](./googlenet.ipynb))  
- **Final Pipeline & Evaluation** ([`fin_last.ipynb`](./fin_last.ipynb))  
- **Presentation Slides** ([`Team9_presentation_final_project.pptx`](./Team9_presentation_final_project.pptx))  

---

## 🔬 Techniques

- **Convolutional Autoencoder** for unsupervised feature extraction ([Keras example](https://keras.io/examples/vision/autoencoder/))  
- **Transfer Learning** using pre-trained CNNs: VGG19, ResNet50, DenseNet121, InceptionV3  
- **Real-time Data Augmentation** via [Keras ImageDataGenerator](https://keras.io/api/preprocessing/image/)  
- **Training Callbacks**: [EarlyStopping](https://keras.io/api/callbacks/early_stopping/), [ModelCheckpoint](https://keras.io/api/callbacks/model_checkpoint/)  
- **Visualization** of training metrics & confusion matrices with [matplotlib](https://matplotlib.org/) & [seaborn](https://seaborn.pydata.org/)  

---

## 📚 Technologies

- **TensorFlow 2.x** – Core deep learning framework ([docs](https://www.tensorflow.org/))  
- **Keras** – High-level neural network API ([docs](https://keras.io/))  
- **NumPy** – Numerical operations ([docs](https://numpy.org/))  
- **pandas** – Data manipulation ([docs](https://pandas.pydata.org/))  
- **matplotlib** & **seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive computing environment  
- **python-pptx** – PPTX slide generation ([docs](https://python-pptx.readthedocs.io/))  

---

## 📁 Structure

```bash
.
├── fin_last.ipynb
├── googlenet.ipynb
├── manisbi_hsriram_swanitha_vgg19.ipynb
├── manishbi_hsriram_swanitha_autoencoder_cnn.ipynb
├── manishbi_hsriram_swanitha_project_checkpoint1.ipynb
├── manishbi_hsriram_swanitha_project_checkpoint2_densenet.ipynb
├── manishbi_hsriram_swanitha_project_checkpoint2_resnet.ipynb
├── Team9_presentation_final_project.pptx
└── data/
    └── images/
