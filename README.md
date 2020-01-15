# pneumonia
Simple web app for classifying x-ray images for pneumonia

Credits to https://www.kaggle.com/paultimothymooney for the dataset and to https://www.kaggle.com/aakashnain for the model

# Training
	1. Download the pre-trained weights from https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg16_weights_tf_dim_ordering_tf_kernels_notop.h5 (I couldn't upload them due to size constraint)
	2. Go to https://github.com/Kaggle/kaggle-api and follow the instructions on how to create your own kaggle.json file
	3. Open https://colab.research.google.com/
	4. Open Pneumonia_Train.ipynb
	5. Change Runtime Type > Hardware Accelerator to GPU
	6. Run All
	
	Note: Make sure to change the paths in the notebook to reflect your own

# Running
	1. Open https://colab.research.google.com/
	2. Open Pneumonia_App.ipynb
	3. Change Runtime Type > Hardware Accelerator to GPU
	4. Run All
