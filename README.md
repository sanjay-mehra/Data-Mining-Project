# Data-Mining-Project
### **_PROJECT NAME:_  Bengali.AI Handwritten grapheme classification**


### **_PROJECT UNDER:_ Dr. Rishav Singh ( NITD Professor )**

## Team Members Name
### 1. **Abhimanyu Trigun ( 171210001 )**
### 2. **Sanjay Mehra ( 171210038 )**
### 3. **Saurabh Patel ( 171210049 )**
### 4. **Vikas Dhurwey ( 171210057 )**

## Competition Description
The competition can be viewed [here](https://www.kaggle.com/c/bengaliai-cv19) and detailed description on competition can be found there. The task was a multilabel classification problem: For every image, one of 168 Grapheme Roots, 11 Vowel Diacritics and 7 Consonant Diacritics had to be predicted. The training data consisted of 200840 137x236 grayscale images (given as arrays/dataframes of numerical pixel values divided among four .parquet files). The private validation data consisted of a similar, possibly identical, amount of images.



## Experience Level
We didn't have any prior practical experience working with machine learning or deep learning. So it was a bit challenging for us to work in this competition as we never participated in kaggle competition earlier.

## Techniques used
  - Conv2D
  - MaxPooling2D
  - Dropout
  - Flatten
  - Dense
  - Used Adam Optimizer
## Software and hardware requirements
 - software requirements:
   - Python Notebook supporting software
 - Hardware requirements:
   - Central Processing Unit (CPU) — Intel Core i5 6th Generation processor or higher is recommended. An AMD equivalent processor will also be optimal.
   - RAM — 8 GB minimum, 16 GB or higher is recommended.
   - Graphics Processing Unit (GPU) — NVIDIA GeForce GTX 960 or higher is recommended. For more information on NVIDIA GPUs for deep learning please visit https://developer.nvidia.com/cuda-gpus.

## The GPU Problem
Because I do not own any GPU other than an Intel HD 520 (which is obviously useless for deep learning), I had to use cloud services. Since I did not want to pay for my experiments, I was somewhat limited in my options. So, I used Kaggle Kernel
- **kaggle kernal:** These give you 30h of GPU-time per week. They can run up to 9h in one go and are nicely integrated into the Kaggle ecosystem.
  
Use of GPU is much better than no GPU at all.
  
  
## How to run code?
**prerequisite:** Should have a kaggle account ( if not create one )

**Code** is available [here](https://github.com/sanjay-mehra/Data-Mining-Project/blob/master/Bengali_CNN.ipynb)

### STEP 1: 
Open [Kaggle Notebooks](https://www.kaggle.com/notebooks) and then create new notebook.

### STEP 2:
Now add competition data to your notebook.

### STEP 3:
Now you are all set to run the given code.

### STEP 4:
Now Click on File button and select upload button.
So in this way we can run our code on Kaggle kernal using GPU.



