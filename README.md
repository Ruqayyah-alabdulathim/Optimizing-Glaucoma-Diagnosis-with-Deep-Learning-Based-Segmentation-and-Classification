Project Name:
Optimizing Glaucoma Diagnosis with Deep Learning-Based 
Segmentation and Classification of Retinal Images 

Description
 Glaucoma is a leading cause of permanent blindness worldwide. This
 project aims to tackle this issue by proposing an automatic
 glaucoma detection system using Deep Learning. The system enhances
 retinal images using a U-Net architecture with a pre-trained
 Residual Neural Network (ResNet34) as an encoder for segmentation,
 and an EfficientNetB0 pre-trained model for classification.
 
 📚 Dependencies
 The project uses several Python libraries. Install them using the
 following commands in your Google Colaboratory notebook:
 ```python
 !pip install tensorflow==2.12
 !pip install keras==2.12
 !pip install -U segmentation-models
 !pip install efficientnet
 !pip install gradio opencv-python

🗃 Datasets
 The project uses the ORIGA, HRF, RIM-ONE DL, and REFUGE datasets.
 Extract the provided Zip file to access the datasets and upload
 them to your Google Drive.

 Environment Setup
 Mount your Google Drive in the Google Colaboratory notebook:
 from google.colab import drive
 drive.mount('/content/drive')

📖 Project Structure
 The project is organized into multiple Jupyter notebooks, each
 explaining a specific part of the project. Open each notebook
 from your Google Drive in Google Colab, copy the code, and paste
 it into a new notebook. Each notebook contains comments within
 the code that explain what specific parts of the code are doing.

🚀 Running the Code
 After copying the code and setting the dataset paths, you can run
 the code in the new notebooks
