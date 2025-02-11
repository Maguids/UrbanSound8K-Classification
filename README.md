# UrbanSound8K Classification

This project was developed for the "Machine Learning II" course and aims to **develop deep learning classifiers** for urban sound data, using the UrbanSound8K dataset.  Classifiers must be able to **identify which of 10 classes of urban sounds** (such as sirens, dog barking, drills, etc.) **a previously unseen audio clip belongs to**.  For this we implemented: **Convolutional Neural Network 2D (CNN)** and **Recurrent Neural Network (RNN)**. 
First Semester of the Third Year of the Bachelor's Degree in Artificial Intelligence and Data Science.

<br>

## Requirements:

	- librosa 
	- matplotlib 
	- ipython 
	- scipy 
	- pandas 
	- numpy 
	- seaborn 
	- soundfile 
	- scikit-learn 
	- tensorflow

<br>

## The Project
As stated previously, the goal of this project is to develop two types of neural networks capable of correctly classifying portions of audio correctly.

<br>

### The Dataset:

In this project we use the **"UrbanSound8K"** dataset which can be obtained through the following link: https://urbansounddataset.weebly.com/urbansound8k.html. This dataset contains 8732 labed sounds excerpts of duration less than or equal to 4 seconds. The sound excerpts are labelled according to the following 10 classes:
- air conditioner;
- car horn;
- children playing;
- dog bark;
- drilling;
- engine idling;
- gun shot;
- jackhammer;
- sirne;
- street music.

<br>

### Pre-Processing:
Before preparing the data for each model, we start by dealing with the sound tracks in general, that is, we make some changes that do not impact the choice of the model to be used:
- Standardize Sampling Rate at 22050Hz;
- Convert to Mono;
- Standardizing Audio Duration to 4s using zero-padding or truncation;
- Normalizing Amplitude to the Range [-1,1].

<br>

### Models

- **CNN 2D**
- **RNN**


<br>

## About the repository:

- Project.pdf ➡️Project statement
- Trabalho_AC.ipynb ➡️ The work developed;

<br>

## Link to the course: 

This course is part of the **<u>first semester</u>** of the **<u>third year</u>** of the **<u>Bachelor's Degree in Artificial Intelligence and Data Science</u>** at **<u>FCUP</u>** and **<u>FEUP</u>** in the academic year 2024/2025. You can find more information about this course at the following link:

<div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
  <a href="https://sigarra.up.pt/fcup/pt/ucurr_geral.ficha_uc_view?pv_ocorrencia_id=529877">
    <img alt="Link to Course" src="https://img.shields.io/badge/Link_to_Course-0077B5?style=for-the-badge&logo=logoColor=white" />
  </a>

  <div style="display: flex; gap: 10px; justify-content: center;">
    <a href="https://sigarra.up.pt/fcup/pt/web_page.inicial">
      <img alt="FCUP" src="https://img.shields.io/badge/FCUP-808080?style=for-the-badge&logo=logoColor=grey" />
    </a>
    <a href="https://sigarra.up.pt/feup/pt/web_page.inicial">
      <img alt="FEUP" src="https://img.shields.io/badge/FEUP-808080?style=for-the-badge&logo=logoColor=grey" />
    </a>
  </div>
</div>
