# Deepfake Detection
The 'Mid-term project in Computer Vision' :  **Ensemble VIT and Efficientnet-B1 in Deepfake Detection**
Team members: Nguyen Minh Duc, Duong Duc Duy, Bui Thuy Duong, Nguyen Huynh Tra My, Nguyen Truong Thanh

## Contributions
- A video dataset containing 100 videos (50 real and 50 fake)
- Found best ensemble way to get excellent results in our proposed dataset (0.8 accuracy and 0.8640 AUC)

## Dataset
- Training data (DFDC) can be found in [Deepkfake Detection Challenge](https://www.kaggle.com/competitions/deepfake-detection-challenge) contaring 400 Gb videos. However, data we directedly used is extracted from this dataset, you can find this in the [link](https://www.kaggle.com/competitions/deepfake-detection-challenge/discussion/134420)

- Testing Data: our data is collected from Youtube, Tiktok, ...

## Model
- Mobiletnet SSD in face detection phase
- VIT and Efficient-B1 in classification phase

