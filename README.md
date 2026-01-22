# Assignment 4 – ML Course

Students:\
Shir Nehoray 209544352\
Itamar Talpaz 315078196

GitHub repository:  
https://github.com/talpazi/ml-course-assign4

---

## Repository Description

This repository contains the solution for **Assignment 4**. This repository contains the solution for Assignment 4 of the ML course, which involves classifying flower images using pre-trained deep neural networks (DNNs). Specifically, we used VGG19 and YOLOv5 models to classify images from the Oxford 102 Flowers dataset.

The solution includes the following stages:

1. Preprocessing: Data loading, resizing, normalization, and augmentation.

2. Architecture: Adjusting the VGG19 model and modifying the classification head.

3. Hyperparameter Optimization (HPO): Conducting a lightweight grid search over hyperparameters like dropout and the depth of the fine-tuning layers.

4. Final Training and Evaluation: Using the best configuration to train the model and evaluate it on a test set.

Detailed results, including performance metrics, hyperparameter choices, and training curves, are provided in the accompanying PDF report.

---

## Repository Structure

ml-course-assign4/
├── 102flowers/                    # Oxford 102 Flowers dataset (images)
├── VGG19/                         # VGG19 model files and scripts
│   ├── DF_ALL.pkl                 # Preprocessed dataframe for 102flowers
│   ├── HPO/                       # Folder containing results from Hyperparameter Optimization (HPO)
│   ├── outputs/                   # Folder containing final models, history, results, and plots
│   ├── VGG19.ipynb                # Jupyter notebook for training and evaluation using VGG19
├── YOLOV5/                        # YOLOv5 model files and scripts
│   ├── HPO/                       # Folder containing results from Hyperparameter Optimization (HPO)
│   ├── outputs/                   # Folder containing results for YOLOv5
│   ├── plot_yolov5_results.ipynb  # Jupyter notebook for plotting figure 6 YOLOv5 
│   ├── YOLOV5.ipynb               # Jupyter notebook for training and evaluation using YOLOv5
│   ├── yolov5su.pt                # Pretrained YOLOv5 weights
├── README.md                      # Project description and repository structure

## Notes
- Detailed explanations and results are provided in the accompanying PDF report submitted via Moodle.
