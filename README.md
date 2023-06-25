<h1>Diabetes Classification Model - Pima Indians Diabetes Data Set</h1>

This repository contains a Naive Bayes classifier implemented from scratch, which is used to classify whether a patient has diabetes, based on the Pima Indians Diabetes Data Set.

<h2>Table of Contents</h2>

<ol>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#data-set">Data Set</a></li>
<li><a href="#naive-bayes-classifier">Naive Bayes Classifier</a></li>
<li><a href="#results">Results</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#license">License</a></li>
</ol>

<h2 id="introduction">Introduction</h2>

Diabetes is a chronic metabolic disease that results in high blood sugar levels. Early diagnosis and treatment can help prevent or delay the onset of complications. Machine learning algorithms have the potential to improve the prediction and classification of diabetes. In this project, we implement a Naive Bayes classifier from scratch to classify whether a patient has diabetes, based on the Pima Indians Diabetes Data Set.

<h2 id="data-set">Data Set</h2>

The Pima Indians Diabetes Data Set is a widely used data set for diabetes prediction and classification. It is composed of 768 instances and 9 attributes. The attributes are as follows:

<table>
<tr>
<th>Attribute</th>
<th>Description</th>
</tr>
<tr>
<td>1. Number of times pregnant</td>
<td>Number of times a person has been pregnant</td>
</tr>
<tr>
<td>2. Plasma glucose concentration</td>
<td>Plasma glucose concentration a 2 hours in an oral glucose tolerance test</td>
</tr>
<tr>
<td>3. Diastolic blood pressure</td>
<td>Diastolic blood pressure (mm Hg)</td>
</tr>
<tr>
<td>4. Triceps skinfold thickness</td>
<td>Triceps skinfold thickness (mm)</td>
</tr>
<tr>
<td>5. 2-Hour serum insulin</td>
<td>2-Hour serum insulin (mu U/ml)</td>
</tr>
<tr>
<td>6. Body mass index</td>
<td>Body mass index (weight in kg/(height in m)^2)</td>
</tr>
<tr>
<td>7. Diabetes pedigree function</td>
<td>Diabetes pedigree function</td>
</tr>
<tr>
<td>8. Age</td>
<td>Age (years)</td>
</tr>
<tr>
<td>9. Class variable</td>
<td>Class variable (0 or 1)</td>
</tr>
</table>

The class variable indicates whether the person has diabetes (1) or not (0).

<h2 id="naive-bayes-classifier">Naive Bayes Classifier</h2>

The Naive Bayes classifier is a probabilistic classifier based on Bayes' theorem, with an assumption of independence betweenthe features. Despite its simplicity, the Naive Bayes classifier often performs well in many applications, including text classification and medical diagnosis.

In this project, we implement a Gaussian Naive Bayes classifier from scratch. The classifier assumes that the likelihood of the features is Gaussian, which is a common assumption for continuous data.

<h2 id="results">Results</h2>

After running the main script, you will see the performance metrics of the classifier, such as accuracy, precision, recall, and F1 score. You can also visualize the confusion matrix to assess the performance of the classifier in more detail.

<h2 id="contributing">Contributing</h2>

If you would like to contribute to this project, please feel free to submit a pull request or open an issue to discuss any changes or improvements.

<h2 id="license">License</h2>

This project is licensed under the MIT License. See the LICENSE file for details.
