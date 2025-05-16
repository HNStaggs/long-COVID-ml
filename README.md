# Long-COVID
Understanding Predictive Factors of Brain Fog in Long-COVID

## Background
Long-COVID is a chronic, multisymptom condition that develops after one or more COVID-19 infections. The diagnostic definition is 12+ weeks since initial infection, one or more new persistent symptoms, and a report of affect on daily functioning. Primary complaints include physical fatigue and brain fog, along with sleep dysfunction and mental health symptoms.

## Methods
In this analysis, various aspects of long-COVID are explored in a sample of 793 people. First, a binary classification model (long-COVID vs. healthy) was trained and tested to identify biopsychosocial features of a long-COVID diagnosis. The input features include the following domains: various types of stress, social support, mental health symptoms, cogntive complaints, physical complaints, health history, pain, and demographics. Second, a regression model was built to look at the subjective and objective features of brain fog severity, while controlling for long-COVID diagnosis and symptom phenotype. Brain fog score was operationalized as a numerical variable by using the global score from the PROMIS Cognitive Complaints measure. Symptom phenotypes were derived from K-means clustering.

## Results
A long COVID diagnosis is classified by a diverse set of biopsychosocial variables including stress (financial and racial), social support, and being a woman, in addition to common symptomatology. Long COVID symptom clustering revealed that phenotypes with some proportion of mental health symptoms are predictive of subjective cognitive complaint scores, in contrast to phenotypes with purely sleep-related or physical symptoms. Objective evidence related to self-reported cognitive dysfunction includes slower reading and typing, and slower reaction times for semantic recall and visual search. Drift diffusion modeling of the visual search task shows that a long COVID diagnosis is related to changes in information processing speed and thresholds for making choices compared to people not meeting diagnostic criteria for long COVID. These findings may be relevant for an objective case definition of subjective brain fog complaints in people with long COVID, treatment and resource planning for the intersectional impacts of long COVID, and tracking outcomes quantitatively.

## Programming Language
* R: Data Exploration, Cleaning, Clustering
* Python: Data Partition, Transformation Pipeline, Modeling, Model Evaluation
  
