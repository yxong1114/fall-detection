# Automated Fall Detection using AI Vision

Two architectures are to be implemented and compared: 

(1) one-step fall detection (Using TensorFlow Object Detection API)

(2) two-step fall detection

## Folder

annotations --> Include label map file for fall, sit walk classes and ms coco

cnn_trained_model --> Trained model for fall recognition model

experiment --> Experiment data for one-step fall detection module

images --> Training set: Kaggle dataset (485 images) -- Testing set: Own images (50 each class) with XML annotation files

images_v2 --> Training set: Kaggle dataset (485 images) + Own images (30 each class) -- Testing set: Own images (20 each class)

models --> pipeline.config for the pretrained model

object-detection-trained-model --> Trained model for one step detection module (4th experiment)

scripts --> Contain general scripts for TensorFlow model

## Jupyter Notebook
### Run on Google Colab (Mount Google Drive)
fall_detection_tf2_v4.ipynb --> Notebook for training one-step detection module

model_evaluation.ipynb --> Notebook for running evaluation during the training stage for one-step detection module (Need to open new Google Colab terminal)

two_step_fall_detection_v5.ipynb --> Notebook for training two-step detection module (person detection model & fall recognition model)

### Run on Local PC
obj_detection_camera_v2.ipynb --> Real time prediction using one-step detection module

*Ensure to download the trained model and set the path to that particular folder*

## License

This Github repo is created mainly for educational and non-commercial use only. It is a fulfilment for completion of unit COS30018 - Intelligent Systems offered in Swinburne University of Technology, Sarawak Campus for Semester 1, 2023.

The content might be out-dated or inaccurate, thus, the author(s) does not take any responsibility for incorrect information disseminate or cited from this repo.
