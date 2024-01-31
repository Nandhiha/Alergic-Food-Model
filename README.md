# Alergic-Food-Excluder-Model
## Overview
![alergy](https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/3aad6d20-fa96-4c7f-86ad-636cdbfbc74f)

This repository contains the code for an Allergic Food Project, focusing on predicting and managing allergic reactions related to certain foods. The system utilizes machine learning, specifically implementing [Specify the algorithm or approach], and takes into account various features such as the individual's allergies, dietary preferences, and location. The implementation includes a user-friendly interface for real-time predictions, enhancing accessibility and usability for potential users.

## Introduction
Food allergies occur when the immune system reacts abnormally to certain foods, perceiving them as harmful substances. This reaction triggers a range of symptoms that can vary from mild to severe, and in some cases, even life-threatening. Common symptoms include skin rashes, itching, swelling, difficulty breathing, abdominal pain, vomiting, and in severe cases, anaphylaxis—a sudden and severe allergic reaction that requires immediate medical attention.

Food allergies affect millions of people worldwide, with prevalence varying by region and population. In some countries, the incidence of food allergies has been steadily increasing, particularly among children. The most common food allergens include peanuts, tree nuts, shellfish, fish, eggs, milk, soy, and wheat.

## Proposed System
The proposed system aims to develop an "Allergy Food Excluder" using a combination of oneAPI and machine learning (ML) concepts, with integration into Gradio for a user-friendly interface. Initially, the system will collect and preprocess a dataset containing information about various foods, including ingredients, nutritional values, and potential allergens. Through feature engineering, relevant characteristics such as allergen presence and ingredient composition will be extracted. ML algorithms will then be employed to develop a model capable of predicting the safety of a food item for consumption based on its features. Leveraging Intel's oneAPI libraries, particularly oneDAL, will optimize data processing and model training, ensuring efficient utilization of hardware resources across CPUs, GPUs, and accelerators. Gradio will facilitate the creation of a straightforward interface where users can input food items and receive clear feedback regarding their safety, including any allergen warnings. Performance optimization strategies will be implemented to enhance the system's efficiency, including memory optimization techniques to minimize data movement. Rigorous testing and validation will be conducted to ensure the model's accuracy and reliability across various food types and allergens. Once deployed, the system will undergo continuous monitoring and maintenance, with updates and improvements implemented based on user feedback and evolving allergy concerns. In essence, the "Allergy Food Excluder" system aims to provide users with a reliable tool for making informed decisions about food consumption while considering their allergy requirements. Not only allergic food but also people can choose food according to preferences.

## Flowchart

![flowchart](https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/8a967a4f-accd-434d-9e4c-32de3fdb86e2)

## Table Of Contents
Installation:#installation

Usage:#usage

Why ONEAPI:#why ONEAPI

Model Comparison:   #model-comparison

Demo: #demo

Output Screenshots: #output-screenshots

## Insatllation

1. Clone the repository:
   
bash git clone https://github.com/your-username/allergic-food-project.git cd allergic-food-project 

2. Installation Dependencies:

pip install -r requirements.txt pip install -r requirements.txt

## Usage

1.Open the Jupyter notebook Allergic food excluder model.ipynb.

2.Follow the instructions and run the cells to:

   *Explore the data
      
   *Train the machine learning model
      
   *Launch the Gradio interface for real-time predictions

## OneAPI Optimization
Optimizing machine learning models with Intel's oneAPI involves leveraging optimized libraries like oneDAL for efficient deep learning operations. Implementing DPC++ programming model taps into parallel processing across CPUs, GPUs, and accelerators. Offloading tasks to GPUs via oneAPI leads to speed improvements. Prioritize memory optimization, including data layout, minimizing movement, and cache-friendly structures. Explore quantization and model pruning for precision and computational efficiency. Use profiling tools to identify bottlenecks, and stay updated with Intel's support for guidance.

## Why ONEAPI
![openai](https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/78e06ba5-8caa-4e46-b2b2-4c86b996fbda)

The grand idea behind oneAPI is to enable the use of one platform for a range of different hardware, hence developers would not have to use different languages, tools, and libraries when they code for CPUs and GPUs.
![Screenshot (380)](https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/04e3a9b4-ec80-48ad-b940-34b62bc6e290)


## Model Comparison

We evaluated Six machine learning models:

1.Naive Bayes Accuracy: 0.95

2.Decision Tree Accuracy: 0.95

3.Random Forest Accuracy: 0.95

4.SVM Accuracy: 0.95

5.KNN Accuracy: 0.95

6.Logical regression Accuracy: 85 

Accuracies of different models are actually similar so we chose naive bayes because it gives output in less time.

## Demo Video

https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/1953db83-347c-4d50-b730-63cc66c48a74

## Output Screenshots

![image_1](https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/3c7f0a3f-b876-4bc3-83e8-87e45c690beb)

![Image_2](https://github.com/Nandhiha/Alergic-Food-Model/assets/116743485/091f4759-e61d-4b6f-808f-76524a557d6b)

## Future Scope

The model's potential extends to the pharmaceutical industry, identifying allergens in drugs or chemicals. It enhances safety by recognizing known and unknown allergens, aiding in drug development and labeling. This innovation ensures individuals are informed about potential allergic reactions, fostering a safer and more personalized pharmaceutical experience.
