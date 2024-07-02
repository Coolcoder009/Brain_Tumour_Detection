# Brain Tumor Detection

Brain Tumor Detection is a project aimed at detecting brain tumors from medical images using various deep learning algorithms. This project utilizes several advanced neural network architectures to achieve high accuracy in tumor detection.

## Installation

1. Clone the repository 
```bash 
git clone <repository-url>
cd <repository-directory>
```

2. To install the required dependencies, run the following command:
```bash
pip install -r requirements.txt
```

3. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```
## How It Works
### Algorithms Used
The project leverages multiple deep learning algorithms to detect brain tumors from images. The following models are implemented in the Jupyter notebooks:

<ul>
<li><strong>Convolutional Neural Network (CNN):</strong> A basic CNN architecture to classify brain images.</li>
<li><strong>Ensemble Learning:</strong> Combines predictions from multiple models to improve accuracy.</li>
<li><strong>Inception V3:</strong> A pre-trained model known for its efficiency in image classification tasks.</li>
<li><strong>MobileNet V3:</strong> A lightweight model optimized for mobile devices.</li>
<li><strong>ResNet 101:</strong> A deep residual network with 101 layers.</li>
<li><strong>VGG19:</strong> A convolutional neural network with 19 layers.</li>
</ul>

### Model Training
The models are trained on a dataset of brain images. The training process involves the following steps:

<ul>
<li><strong>Data Preprocessing:</strong> Images are preprocessed to ensure uniformity and suitability for model input.</li>
<li><strong>Model Training:</strong> Each model is trained using the preprocessed data.</li>
<li><strong>Validation:</strong> Model performance is validated using a separate validation dataset.</li>
<li><strong>Testing:</strong> The trained models are tested on a test dataset to evaluate their accuracy and performance.</li>
</ul>

### Example Usage
To run the models and train them on the dataset, follow these steps:

### Open Jupyter Notebook:

Open each notebook file (.ipynb) and execute the cells to train and evaluate the models. The notebooks include:
<ul>
<li>`Brain_Tumor_Classification_CNN.ipynb`</li>
<li>`ensembBrain_Tumor_Classification_EnsembleLearning.ipynb`</li>
<li>`Brain_Tumor_Classification_InceptionV3.ipynb`</li>
<li>`Brain_Tumor_Classification_MobileNetV3.ipynb`</li>
<li>`Brain_Tumor_Classification_Resnet101.ipynb`</li>
<li>`Brain_Tumor_Classification_Vgg19.ipynb`</li>
</ul>

### Results
The results of the model training and evaluation are presented in the notebooks.
