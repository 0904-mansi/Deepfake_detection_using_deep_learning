# Deepfake detection using Deep Learning (ResNext and LSTM)
<!-- 
## Star⭐ this repo 😉 and Follow me on<a href="https://github.com/abhijitjadhav1998/">  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a> -->


 ## 1. Introduction
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. 


<!-- ## 2. Directory Structure
For ease of understanding the project is structured in below format
```
Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
    |--- Documentaion
```
1. Django Application 
   - This directory consists of the django made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
2. Model Creation
   - This directory consists of the step by step process of creating and training a deepfake detection model using our approach.
3. Documentation
   - This directory consists of all the documentation done during the project
    -->
## 2. System Architecture
<p align="center">
  <img width = 500 src="https://user-images.githubusercontent.com/81081105/182219807-6b564204-b8f4-42bd-a2f7-b9f077c846a3.png">
</p>


## 3. Our Results

| Model Name | No of videos | No of Frames | Accuracy |
|------------|--------------|--------------|----------|
|model_84_acc_10_frames_final_data.pt | 01 |10 |84.21461|
|model_87_acc_20_frames_final_data.pt | 01 |20 |87.79160|
|model_89_acc_40_frames_final_data.pt | 01| 40 |89.34681|
|model_90_acc_60_frames_final_data.pt | 01| 60 |90.59097 |
|model_91_acc_80_frames_final_data.pt | 01 | 80 | 91.49818 |
|model_93_acc_100_frames_final_data.pt| 01 | 100 | 93.58794|


<!--  
## 4. License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  -->

## 4. Glimpse of our Application
- Home page
<img width="600" height="200" src="https://user-images.githubusercontent.com/81081105/182218376-ced21792-85b8-4db1-9ee4-5cbce708af0e.png">

- Uploading video
<img width="600" height="400" src="https://user-images.githubusercontent.com/81081105/182218810-5964ead9-2a9c-43b9-a56e-8d96c09e661a.png">

- Frames Splitting and cropping face video
<img width="600" height="200" src="https://user-images.githubusercontent.com/81081105/182219069-e9284edd-90ef-4375-8c9e-52cb9ac30ef4.png">

- Result
<img width="600" height="200" src="https://user-images.githubusercontent.com/81081105/182219417-701fe7dc-dc60-4673-813b-6fd39bf708c4.png">





## 5. Supporting Documents
- ![Presentation](https://docs.google.com/presentation/d/1kFa-L47akB8ZIXdpN19zDk0U8xA9_QSMbd4zdVvNeuA/edit?usp=sharing)
- ![Report](https://docs.google.com/document/d/166_1DMP7pMpaxwVmAW0mqKVdZxv4gGxYAILef5yLQT8/edit?usp=sharing)
- ![Abstract]()

## 6. Contributors
- ![Mansi Mishra](https://github.com/0904-mansi)
- ![Sanskriti Harmukh](https://github.com/SanskritiHarmukh)
- ![Satyam Jain](https://github.com/satyam298)
- ![Archit Chawda]()
