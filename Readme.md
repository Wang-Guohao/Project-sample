## Project Title: Decision Support System in Oncology

Team Members: FirstName LastName, FirstName LastName, and FirstName LastName.

### Contents

* [Problem](#Problem)
* [Solution](#Solution)
* [ML Pipeline](#ML-Pipeline)
* [Data Management](#Data-Management)
* [Study Design](#Study-Design)
  * Identify clinical goal (Predict Cancer Onset)
  * Define prediction outcome (Identify risk factors for quality review, or clinical decision making)
  * Participant inclusion/exclusion criteria (all gender, subset of columns)
* Exploratory Analysis
* Training/Validation Split
* Feature Engineering
* Model Training ( XGBoost, Logistic Regression AUC performance metric)
* Validation Strategies
* Results & Model Performance
* [Solution Video](#Solution-Video)
  * Link a short video ( Youtube could work ) that walks through your approach and solution.
* [Clinical Relevance of the Model](#Clinical_Relevance_of_the_Model)
* [Acknowledgments](#acknowledgments)

#### Problem
- Physcians are overwhlemed with patient cancer data, and would benefit from a system that outlined indiviaulized patients risk factors based  patient's background like gender, date of birth, enthicity aswell as familial history, primiary site, cancer stage and grading to augment their clinical decision making. 

#### Solution
- A clinical decision system to help physicians keep track of their patients' progress using their background and individualized molecular level data.

#### ML-Pipeline
- ML WorkFlow depicting the solution below.![Image](https://github.com/aimsymposium/Project-sample/raw/main/MLpipeline.png)
- Add a link to your code(Google Colab). Refer to this [sample notebook](https://colab.research.google.com/drive/1GFtlNPVoSZ1RHcb2DvUzaLY8mEgdqeAV?usp=sharing) for further details.
#### Data-Management
- Data Pre-processing/ Cleansing/Transformations(Changing column names, Merging different data sources, etc). Refer to this subtitle in the [Google Collab notebook](https://colab.research.google.com/drive/1GFtlNPVoSZ1RHcb2DvUzaLY8mEgdqeAV?usp=sharing) for more detail. 
- Methods for removing and selection of outliers
- Methods for poor quality or missing data
- Descriptive statistics(Pairwise correlation, ANOVA, Univariate Analysis, Odds Ratio).
#### Study-Design
( Below are answer templates that can be used to formulate a paragraph for Study Design based on the goal and exploratory data analysis)
-   Identify clinical goal (Prediction of cancer patient survival.)
-   Define prediction outcome (Predict cancer patient survival for quality review and better clinical decision making.)
-   Participant inclusion/exclusion criteria 
(2000 patients with various cancer types were included. A diverse patient population race was involved including whites (1860 [93%]),  African Americans (88 [4.5%]), American Indians (12 [0.6%]), Asians (7 [0.35%]),  Alaskan Natives (12 [1%]), Native Hawaiians (2 [0.15%]), and from other races (7 [0.45%]). The median age (interquartile range) was 62 (54-70) years old. Refer to Race subtitle in the [Google Collab notebook](https://colab.research.google.com/drive/1GFtlNPVoSZ1RHcb2DvUzaLY8mEgdqeAV?usp=sharing) for more detail. 
36% of the patients had a paternal history with cancer and the greatest proportion was 10% prostate cancer. 39% of the patients had a maternal history with cancer and the greatest proportion was 11% breast cancer. Refer to Family History subtitle in the [Google Collab notebook](https://colab.research.google.com/drive/1GFtlNPVoSZ1RHcb2DvUzaLY8mEgdqeAV?usp=sharing) for more detail. 
Out of 785 males,the majority of the tumors were from the prostate gland as the primary site (371[47.2%]),adenocarcinoma(496 [63%]), grade III: Poorly differentiated , dedifferentiated (369 [47%]), and stage 1 (478[60%]) . 
Out of 1215 females, the majority of the tumors were from the breast upper outer quadrant primary site(300 [24.69%]), infiltrating duct carcinoma(535 [44%]), grade II: moderately differentiated, intermediate differentiated (522 [43%]), and stage 1 (737 [60%]).
Refer to Male and Female Primary Site, Histology, Grade and Stage Distribution subtitle in the [Google Collab notebook](https://colab.research.google.com/drive/1GFtlNPVoSZ1RHcb2DvUzaLY8mEgdqeAV?usp=sharing) for more detail. 

#### Solution-Video

[![Watch the video](https://github.com/Code-and-Response/Liquid-Prep/blob/master/images/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)


#### Clinical_Relevance_of_the_Model

#### Acknowledgments
