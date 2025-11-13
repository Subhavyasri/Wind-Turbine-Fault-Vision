🌬️ Wind Turbine Fault Vision – CNN Based Fault Detection
🔍 Final Project Submission
👩‍🎓 Medarametla Subhavyasri
🏫 Krishnaveni Engineering College for Women
📌 Project Overview

Wind turbines are essential for renewable energy production. However, turbine blades often get damaged due to environmental stress, erosion, or mechanical failure. Manual inspection is risky and time-consuming.

This project aims to develop an automated fault detection system using Convolutional Neural Networks (CNN) that classifies blade images into:

🟢 Normal

🔴 Fault

The model is built using MobileNetV2 (Transfer Learning), a powerful CNN architecture capable of achieving high accuracy even with limited datasets.

📁 Dataset Information
📦 Dataset Used:

CAI-SWTB: Structural Wind Turbine Blade Dataset

🔗 Dataset Link:
https://drive.google.com/file/d/1SrhdI_vgvEmhWwYTzzSx0FFTSt1POemk/view?usp=drive_link

📂 Dataset Structure
CAI-SWTB-Dataset/
 ├── Train/
 │    ├── Fault/
 │    └── normal/
 ├── Test/
 │    ├── Fault/
 │    └── normal/
 └── Validation/
      ├── Fault/
      └── normal/

📊 Data Details

4200 Training Images

1200 Testing Images

Balanced Classes:

2100 Fault

2100 Normal

🤖 Model Used: MobileNetV2 (CNN Transfer Learning)
Why MobileNetV2?

Lightweight CNN architecture

Pretrained on ImageNet

Fast training

High accuracy

Ideal for real-time and edge deployment

✔ Final Model Accuracy: 82%
✔ Final Model Loss: 0.39
🧪 Final Model Performance
✔ Confusion Matrix
[[465 135]
 [ 76 524]]

✔ Classification Report
Class	Precision	Recall	F1-Score
Fault	0.86	0.78	0.82
Normal	0.80	0.87	0.83
✔ Overall Accuracy: 82%

Weekly Progress Summary

📍 Week 1 – Project Setup
✔ Tasks Completed

Understood project problem statement
Selected wind turbine fault detection as project theme
Collected dataset & uploaded to Google Drive
Created GitHub repository
Added initial README and file structure

✔ Improvisations

Reorganized dataset folders
Removed unusable/corrupted files
Maintained balanced dataset structure

📍 Week 2 – Model Building & Preprocessing
✔ Tasks Completed

Loaded dataset in Google Colab
Performed image preprocessing:
Resizing
Normalization
Augmentation
Built initial custom CNN
Evaluated accuracy (~55%)
Identified overfitting issues
Improved dataset quality

✔ Improvisations

Added stronger augmentation
Experimented with different CNN layers
Balanced training samples

📍 Week 3 – Final Model Training & Evaluation
✔ Tasks Completed

Implemented MobileNetV2 Transfer Learning
Fine-tuned the model
Applied callbacks:
EarlyStopping
ModelCheckpoint
Achieved final accuracy 82%
Generated confusion matrix & classification report
Exported model (mobilenetV2_final_cnn.h5)
Created prediction sample images

✔ Improvisations
Shifted from basic CNN to Transfer Learning
Added dense layers with dropout for overfitting control
Tuned learning rate and optimizer
Used balanced dataset for stable accuracy

🔧 Technologies & Tools Used

Python
TensorFlow / Keras
MobileNetV2
NumPy
Matplotlib
Sklearn
Google Colab
GitHub


🏁 Conclusion

This project successfully builds a CNN-based wind turbine fault detection system with an accuracy of 82%,
demonstrating the power of AI-driven predictive maintenance in renewable energy systems.

👩‍💻 Developer
Medarametla Subhavyasri

Krishnaveni Engineering College for Women


