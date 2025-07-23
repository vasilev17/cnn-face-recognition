<div align="center">
  
<h1>🕵️ CNN Face Recognition — Deep Learning Pipeline</h1>
  
<p>End-to-End Convolutional Neural Network (CNN) Pipelines for Face Recognition – from <b>data preparation</b>, through <b>model training</b>, to <b>real-time inference</b>.</p>

<div>
  <img src="https://img.shields.io/badge/Solo-Project-gray?logo=codecrafters&labelColor=cyan&logoColor=%23323232" style="height: 30px; width: auto;">
</div>

</div>

---

## 📜 Key Features

- **Data Ingestion** - Converts raw face images into clean, labelled **train** / **val** / **test** splits.

- **Real-World Image Dataset** – Classification task done on [VGGFace2](https://www.robots.ox.ac.uk/~vgg/data/vgg_face2/).
  
- **Performance Evaluation** – Accuracy visualization plots.
  
- **Real-Time Detection** – [OpenCV](https://opencv.org/) demo that detects one and multiple agents' faces live.
  
- **Docs / Report** – [12-page write-up](CNN%20for%20Face%20Recognition.docx) with theory & results and hosted notebooks for preview [[1](https://vasilev17.github.io/cnn-face-recognition/Benchmark%20(LowAccur_FewFeatures).html), [2](https://vasilev17.github.io/cnn-face-recognition/Benchmark%20(HighAccur_MoreFeatures).html), [3](https://vasilev17.github.io/cnn-face-recognition/TransferLearningNotebook.html), [4](https://vasilev17.github.io/cnn-face-recognition/RealTimeFaceDetectionNotebook.html)].

---

## 🏗️ Tech Stack
| Layer            | Technology                                  |
|------------------|---------------------------------------------|
| Core ML          | TensorFlow / Keras, NumPy |
| Computer Vision  | 	OpenCV, MTCNN detector |
| Experimentation  | 	Jupyter Notebook, Matplotlib |
| Utilities        | 	YAML for config, [tqdm](https://tqdm.github.io/) progress bars |


---

## 🏁 Getting Started

### Prerequisites
- **Python ≥ 3.10**
- pip (or [conda](https://anaconda.org/anaconda/conda) if you prefer)

### Clone & Install
```bash
git clone https://github.com/vasilev17/cnn-face-recognition.git
cd cnn-face-recognition

# Linux / macOS
python -m venv .venv
source .venv/bin/activate

# Windows (PowerShell)
python -m venv .venv
.venv\Scripts\Activate.ps1

pip install tensorflow keras opencv-python matplotlib scikit-learn pandas notebook

jupyter notebook            # or jupyter lab
```
Once Jupyter is opened:
1. Navigate to `Code Notebooks/`
2. Open any `.ipynb` file
3. Run the cells from top to bottom, tweak parameters or swap datasets

> [!NOTE]
> The notebooks expect the sample images inside `Datasets/`

---

## 🎬 Showcase

### Single Agent Real-Time Face Detection
https://github.com/user-attachments/assets/9795ec71-89dc-4773-aaf7-fb673ae04f24

### Milti-Agent Real-Time Face Detection
https://github.com/user-attachments/assets/633b802e-091c-4ecf-99d9-35609fcb75f1

### Notebook Previews
[LowAccur_FewFeatures](https://vasilev17.github.io/cnn-face-recognition/Benchmark%20(LowAccur_FewFeatures).html)  &nbsp;&nbsp;  |  &nbsp;&nbsp;  [HighAccur_MoreFeatures](https://vasilev17.github.io/cnn-face-recognition/Benchmark%20(HighAccur_MoreFeatures).html)  &nbsp;&nbsp;  |  &nbsp;&nbsp;  [TransferLearning](https://vasilev17.github.io/cnn-face-recognition/TransferLearningNotebook.html)  &nbsp;&nbsp;  |  &nbsp;&nbsp;  [RealTime](https://vasilev17.github.io/cnn-face-recognition/RealTimeFaceDetectionNotebook.html)

