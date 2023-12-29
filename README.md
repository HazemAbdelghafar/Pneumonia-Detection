# Pneumonia-Detection

<h1><b>What is Pneumonia? </b></h1>

Pneumonia is an inflammatory condition of the lung affecting primarily the small air sacs known as alveoli.Symptoms typically include some combination of productive or dry cough, chest pain, fever and difficulty breathing. The severity of the condition is variable. Pneumonia is usually caused by infection with viruses or bacteria and less commonly by other microorganisms, certain medications or conditions such as autoimmune diseases.Risk factors include cystic fibrosis, chronic obstructive pulmonary disease (COPD), asthma, diabetes, heart failure, a history of smoking, a poor ability to cough such as following a stroke and a weak immune system. Diagnosis is often based on symptoms and physical examination. Chest X-ray, blood tests, and culture of the sputum may help confirm the diagnosis.The disease may be classified by where it was acquired, such as community- or hospital-acquired or healthcare-associated pneumonia.

<p align="center">
  <img src= "https://github.com/AIBabyTeaching/deep-learning-project-HazemAbdelghafar/assets/114096531/1f705d68-618f-4be7-a057-5dd5f571c355">
</p>

<h2>Description of the Pneumonia Dataset</h2>

The dataset that will be used is the <a href="https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/">Chest X-ray images</a> dataset.The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal). The train folder is divided into 1341 images labeled as “Normal” and 3875 images labeled as “Pneumonia”. Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

<p align="center">
  <img src= "https://github.com/AIBabyTeaching/deep-learning-project-HazemAbdelghafar/assets/114096531/f1cc483e-6b52-425e-8d66-df09b516b139">
</p>

The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

<br>

Due to the imbalance in the training dataset, I will have to use data augmentation to avoid the overfitting of the model. This will be done to increase the number of “Normal” labelled images using various augmentation techniques.

<br><br>



[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12711583&assignment_repo_type=AssignmentRepo)
