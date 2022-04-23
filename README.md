# Cancer Diagnosis

<h2>BUSINESS PROBLEM</h2>

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/


<h2>Context:</h2>
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462


<h2>Problem statement :</h2>

Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

<h2>Real-world/Business objectives and constraints:</h2>

No low-latency requirement.

Interpretability is important.

Errors can be very costly.

Probability of a data-point belonging to each class is needed.

<h2>Data Overview:</h2>

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID

Data file's information:

training_variants (ID , Gene, Variations, Class)
training_text (ID, Text)

<h2>Type of Machine Learning Problem:</h2>

There are nine different classes a genetic mutation can be classified into => Multi class classification problem.

<h2>CREDITS:</h2>
APPLIED AI COURSE.
