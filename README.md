<h1 align="center">Detection of COVID-19 using classification algorithms.</h1>



<h1 align="center">Abstract</h1>
This project focuses on the use of machine learning algorithms for binary classification
of COVID-19 data. Several algorithms were applied, including k-Nearest Neighbors (KNN),
Linear Support Vector Machine (SVM), Gaussian SVM, and Perceptron. The performance of
these algorithms was evaluated on a dataset of COVID-19 cases and compared to determine
the most effective method for classifying positive and negative cases. The results of this study
demonstrate the potential of these machine learning techniques for accurately identifying COVID-19
cases and could be useful in the development of diagnostic tools and tracking the spread of the
disease.


<h1 align="center">GENERAL INTRODUCTION</h1>

Our end-of-semester project aims to explore the capabilities of various supervised machine learning algorithms by applying them to a selected database. To achieve this, we will begin by selecting an appropriate database and then label it to prepare the data for analysis. Next, we will use algorithms such as KNN, linear SVM, Gaussian SVM, and perceptron to extract useful information from the database and assess their performance. We hope that this project will allow us to understand the advantages and limitations of these algorithms and gain a better insight into how they can be used to solve real-world problems.


<h1 align="center">COVID-19 Dataset</h1>
<h2>The Context</h2>
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus. Most individuals infected with the COVID-19 virus will experience mild to moderate respiratory illness and will recover without requiring special treatment. Elderly individuals and those with underlying medical conditions such as cardiovascular diseases, diabetes, chronic respiratory diseases, and cancer are more likely to develop severe illness. Throughout the course of the pandemic, one of the primary challenges faced by healthcare providers has been the scarcity of medical resources and a suitable plan for their efficient distribution. In these challenging times, being able to predict the type of resource an individual might require upon testing positive or even before that could be immensely helpful for authorities, as they could procure and organize the necessary resources to save the patient's life.

The main objective of this project is to build a machine learning model that, based on the symptoms, current health status, and medical history of a COVID-19 patient, will predict whether the patient is at high risk or not.

<h2> The Content </h2>

The dataset has been provided by the Mexican government (link). This dataset contains an enormous amount of anonymized information about patients, including pre-existing conditions. The raw dataset consists of 21 unique features and 1,048,576 unique patients. In boolean features, 1 signifies "yes," and 2 signifies "no." Values like 97 and 99 represent missing data.

<ul>
  <li>Gender: 1 for female and 2 for male.</li>
  <li>Age: Age of the patient.</li>
  <li>Classification: COVID test results. Values 1 to 3 indicate different degrees of diagnosed COVID. 4 or more indicates that the patient is not a carrier of COVID or the test is inconclusive.</li>
  <li>Patient type: Type of care received by the patient in the unit. 1 for home return and 2 for hospitalization.</li>
  <li>Pneumonia: Whether the patient has inflammation of the air sacs or not.</li>
  <li>Pregnancy: Whether the patient is pregnant or not (applicable to female patients).</li>
  <li>Diabetes: Whether the patient is diabetic or not.</li>
  <li>COPD (Chronic Obstructive Pulmonary Disease): Indicates if the patient has this condition.</li>
  <li>Asthma: Whether the patient has asthma or not.</li>
  <li>Immunodeficiency: Whether the patient is immunocompromised or not.</li>
  <li>Hypertension: Whether the patient has hypertension (high blood pressure) or not.</li>
  <li>Cardiovascular: Whether the patient has a heart or vascular disease.</li>
  <li>Chronic Kidney Disease: Whether the patient has chronic kidney disease or not.</li>
  <li>Other Disease: Whether the patient has another disease or not.</li>
  <li>Obesity: Whether the patient is obese or not.</li>
  <li>Tobacco: Whether the patient is a tobacco consumer.</li>
  <li>USMR (Medical Care Unit): Indicates if the patient was treated in first, second, or third-level medical care units.</li>
  <li>Medical Unit: Type of establishment within the national health system that provided care.</li>
  <li>Intubated: Whether the patient was connected to a ventilator.</li>
  <li>ICU (Intensive Care Unit): Indicates if the patient was admitted to an intensive care unit.</li>
  <li>Date of Death: If the patient has deceased, indicates the date of death; otherwise, "9999-99-99."</li>
</ul>
The primary goal of this project is to construct a machine learning model that, considering the symptoms, current health status, and medical history of a COVID-19 patient, will predict whether the patient is at high risk or not. The dataset, provided by the Mexican government, contains a substantial amount of anonymized information about patients, allowing for an in-depth analysis of COVID-related factors.

<h1 align="center">Data Preparation and Results</h1>

"Within the code, you will discover an explanation of the data preparation steps, details about the applied algorithms, and a comprehensive presentation of the results.
<a href="project_final_.ipynb">Data Preparation and Results</a>




<h1 align="center">GENERAL CONCLUSION</h1>

In conclusion, the application of machine learning algorithms on a COVID database has highlighted the performance of each one of them. The comparison among different algorithms has shown that some have been more effective than others in detecting COVID cases. It is important to continue exploring and enhancing these algorithms to make them even more effective in the fight against this pandemic.




<h1 align="center">Team</h1>
<ul>
	<li> Ayoub Hsaine</li>
	<li> Achraf Rachid</li>
</ul>





