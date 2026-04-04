# Pneumonia Detector w/ ResNet-CNN Architecture 

## Objective 
The aim of this notebook is to explore the usage of Convolutional Neural Networks (CNNs) and Transfer Learning to detect Pneumonia given X-ray images of the lungs of patients. This notebook will have a look at vanilla CNNs, as well as pretrained CNNs models such as ResNet50V2, EfficientNetV1 B0 and the new EfficientNetV2 B0. Perfomance evaluation via selected metrics will be discussed in this notebook in order to compare the architectures explored.

The dataset used to train the model in this notebook is the Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification (Version 2), published on 6 January 2018.
Find the Kaggle Version here: <https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia>


## Pneumonia Definition & Symptoms
Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses and fungi, can cause pneumonia.

The signs and symptoms of pneumonia vary from mild to severe, depending on factors such as the type of germ causing the infection, and your age and overall health. Mild signs and symptoms often are similar to those of a cold or flu, but they last longer.

## Signs and symptoms of pneumonia may include:

<list>
- Chest pain when you breathe or cough
- Confusion or changes in mental awareness (in adults age 65 and older)
- Cough, which may produce phlegm
- Fatigue
- Fever, sweating and shaking chills
- Lower than normal body temperature (in adults older than age 65 and people with weak immune systems)
- Nausea, vomiting or diarrhea
- Shortness of breath
- Newborns and infants may not show any sign of the infection. Or they may vomit, have a fever and cough, appear restless or tired and without energy, or have difficulty breathing and eating.
Read here for more: <Mayo Clinic - Pneumonia>
</list>
