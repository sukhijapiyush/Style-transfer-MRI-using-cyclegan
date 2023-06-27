# Style-transfer-MRI-using-cyclegan

> In this project, we use a cycleGan to do style transfer of MRI images type from T1 to T2 and vice versa. This is done to reduce the time taken to acquire images of both types. The CycleGAN has been created in tensorflow and keras.

## Table of Contents

- [Style-transfer-MRI-using-cyclegan](#style-transfer-mri-using-cyclegan)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Algorithms Used](#algorithms-used)
    - [Problem Statement](#problem-statement)
    - [Dataset Information](#dataset-information)
  - [Steps Involved](#steps-involved)
  - [Results](#results)
  - [Conclusion](#conclusion)
  - [Technologies Used](#technologies-used)
  - [Contact](#contact)
  - [License](#license)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Algorithms Used

CycleGAN

### Problem Statement

Misdiagnosis in the medical field is a very serious issue but it’s also uncomfortably common to occur. Imaging procedures in the medical field requires an expert radiologist’s opinion since interpreting them is not a simple binary process ( Normal or Abnormal). Even so, one radiologist may see something that another does not. This can lead to conflicting reports and make it difficult to effectively recommend treatment options to the patient.

One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.

### Dataset Information

The data containes unpaired images of T1 and T2 MRI images which are used to train the model.  

## Steps Involved

- Data Loading
- Data Visualization
- Data Preprocessing(Resizing, Normalization, Augmentation)
- Data Batching
- Creating Generator and Discriminator
- Defining Loss Functions
- Defining Optimizers
- Creating CycleGAN
- Defining Callbacks
- Model Training
- Model Evaluation

## Results

**Output After 300 Epochs:**

<center><img src="Epoch 300 output.png" alt="drawing" width="400"  /></center>

**Loss Visualization:**
<center><img src="loss viz.png" alt="drawing" width="800"  /></center>

**Epochs GIF to show the progress of the model:**
<center><img src="cyclegan_mri_pre.gif" alt="drawing" width="800"  /></center>

**Predictions for T1 to T2:**
<center><img src="T1 Predictions.png" alt="drawing" width="400"  /></center>

**Predictions for T2 to T1:**
<center><img src="T2 Predictions.png" alt="drawing" width="400"  /></center>

## Conclusion

The model is capable of generating images of T1 type from T2 and vice versa. The model can be used to reduce the time taken to acquire images of both types which can be used for further analysis. This also reduces the cost of acquiring them as well delay in diagnosis.

## Technologies Used

- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy

## Contact

Created by [@sukhijapiyush] - feel free to contact me!

## License

This project is open source and available under the [MIT License](LICENSE).

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)
