# Data-Mining-Project
**_PROJECT NAME:_  Bengali.AI Handwritten grapheme classification**


**_PROJECT UNDER:_ Dr. Rishav Singh ( NITD Professor )**

## Team Members Name
- **Abhimanyu Trigun ( 171210001 )**
- **Sanjay Mehra ( 171210038 )**
- **Saurabh Patel ( 171210049 )**
- **Vikas Dhurwey ( 171210057 )**

## Competition Description
The competition can be viewed [here](https://www.kaggle.com/c/bengaliai-cv19) and detailed description on competition can be found there. The task was a multilabel classification problem: For every image, one of 168 Grapheme Roots, 11 Vowel Diacritics and 7 Consonant Diacritics had to be predicted. The training data consisted of 200840 137x236 grayscale images (given as arrays/dataframes of numerical pixel values divided among four .parquet files). The private validation data consisted of a similar, possibly identical, amount of images.



## Experience Level
We didn't have any prior practical experience working with machine learning or deep learning. So it was a bit challenging for us to work in this competition as we never participated in kaggle competition earlier.

## The GPU Problem
Because I do not own any GPU other than an Intel HD 520 (which is obviously useless for deep learning), I had to use cloud services. Since I did not want to pay for my experiments, I was somewhat limited in my options. So, there are two services I used
- **kaggle kernal:** These give you 30h of GPU-time per week. They can run up to 9h in one go and are nicely integrated into the Kaggle ecosystem.
- **Google Colab:** Google Colab is offered by Google for free. It allows the user to use spare GPU capacities for scientific computing. It does, however, have a few drawbacks:
  - It disconnects if left idle for too long. This forces me to watch over it while it runs and makes overnight experiments impossible.
  - I have to take precautions against losing my progress: If it suddenly disconnects (which is possible) I obviously do not want to lose all my progress on the current experiment. My solution to this was to connect it to Google Drive and create a backup in a Google Drive folder after every epoch.
  
Use of GPU is much better than no GPU at all.
  
  
## How to run code? ( Kaggle version )
**prerequisite:** Should have a kaggle account ( if not create one )
**Code** is available [here](https://github.com/sanjay-mehra/Data-Mining-Project/)

### STEP 1: 
Open [Kaggle Notebooks](https://www.kaggle.com/notebooks/) and then create new notebook.

### STEP 2:
Now add competition data to your notebook.

### STEP 3:
Now you are all set to run the given code.


## How to run code? ( Google Colab version )
**prerequisite:** Should have a google colab account ( if not create one )
**Code** is available [here](https://github.com/sanjay-mehra/Data-Mining-Project/)

### STEP 1: 
Download competition data from kaggle. ( File size : approx 4.8 GB )

### STEP 2:
Add data to your google drive and give permission to read and write the file.

### STEP 3: 
Open [Google Colab](https://colab.research.google.com/) and then create new notebook.

### STEP 4:
Now simply run the given code on Google Colab.





