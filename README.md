# Novartis_ODIR_Classification

Submission for a Binary Ocular Disease Classification Using ODIR-5K, by Team Phoenix, BITS Pilani Hyderabad Campus.

A deep learning project for **binary classification of retinal images as healthy or diseased** using the ODIR-5K dataset.

The project uses **EfficientNetV2-S transfer learning** with image preprocessing, augmentation, and focal loss.

## Results

| Metric      |      Score |
| ----------- | ---------: |
| ROC-AUC     | **0.8501** |
| Accuracy    | **78.53%** |
| F1 Score    | **0.7820** |
| Sensitivity | **0.7078** |
| Specificity | **0.8778** |

## Repository Contents

* [Novartis_submission_team_phoenix.ipynb](https://github.com/medha-007/Novartis_ODIR_Classification/blob/main/Novartis_submission_team_phoenix.ipynb "Novartis_submission_team_phoenix.ipynb") — Complete code and executed notebook
* [requirements.txt](https://github.com/medha-007/Novartis_ODIR_Classification/blob/main/requirements.txt "requirements.txt") — Required Python packages
* [Team_Phoenix_Novartis_Report.pdf](https://github.com/medha-007/Novartis_ODIR_Classification/blob/main/Team_Phoenix_Novartis_Report.pdf "Team_Phoenix_Novartis_Report.pdf") — Detailed project report
* [Team_Phoenix_Novartis_presentation.pptx](https://github.com/medha-007/Novartis_ODIR_Classification/blob/main/Team_Phoenix_Novartis_presentation.pptx "Team_Phoenix_Novartis_presentation.pptx") — Project presentation

## Google Colab

The notebook can also be run directly in Google Colab:

https://colab.research.google.com/drive/1rKpSOB2HmXFAia1CVRvmuIIFzKTPDphp?usp=sharing

## Dataset

This project uses the **ODIR-5K (Ocular Disease Intelligent Recognition)** dataset:

https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k

The dataset is downloaded automatically using `kagglehub` when the notebook is run.

## Running the Project

Install the required dependencies:

install requirements.txt

Then open `Novartis_submission_team_phoenix.ipynb` or use the Google Colab link above.

## Documentation

For detailed methodology, implementation, analysis, and discussion of results, refer to the **project report** and **presentation**.
