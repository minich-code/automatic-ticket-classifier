# Automatic Ticket Classifier
## Overview
Customer complaints are a critical indicator of service quality for financial institutions. Unresolved or mismanaged complaints can lead to customer dissatisfaction, churn, and reputational damage. Therefore, this project aims to develop an automated ticket classification model that streamlines complaint handling, ensuring timely resolution, and enhanced customer experience.

## Business Understanding
The company seeks to automate the classification of customer complaints based on the type of product or service mentioned. We will leverage Natural Language Processing (NLP), to categorize customer complaints into predefined product or service categories. This will enable efficient routing of complaints to the relevant department, reducing resolution time and improving customer satisfaction.
Additionaly, topic modeling will be incorporated to identify patterns and recurring words in the complaint data.

### Business Objectives
1. Faster complaint resolution
Reducing the time required to process and assign complaints to the correct department.

2. Enhanced Customer Experience
Providing timely responses and resolutions to customer concerns, leading to higher satisfaction levels.

3. Optimized Resource Allocation
Freeing up human resources by minimizing manual classification efforts, allowing them to focus on high-priority cases and complex customer needs.

## Data Understanding
The dataset, contains unstructured text data related to customer complaints. It comprises of 78313 rows and 18 columns. 

## Data Preprocessing
Loading and cleaning the data.

Handling missing values and duplicates.

## EDA
Complaint distributions across categories


### Text Preprocessing
Tokenization, stopword removal, and text normalization.

Word cloud generation to identify common terms.

![Most Frequent Words in Complaints](/automatic-ticket-classifier/images/Most%20Frequent%20Words%20in%20Complaints.png)


## Topic Modeling (Unsupervised Learning)

Applied Latent Dirichlet Allocation (LDA) to group complaints into key themes.

Visualization of topic clusters using NMF and LDA topic modeling.
![Distribution of Complaints by Topic (NMF & LDA)](/automatic-ticket-classifier/images/Distribution%20of%20Complaints%20by%20Topic%20(NMF%20&%20LDA).png)

## Supervised Learning Model

## Evaluation & Optimization

Comparing models and selecting the best-performing classifier.