<h1>Mammogram masses prediction</h1>

The project compares different supervised machine learning techniques and yields which model gives high accuracy. The techniques used are Decision tree, Random forest, KNN, Naive Bayes, SVM, Logistic Regression, and  neural network using Keras. 

<h2>Data</h2>

The data used for this project comes from the "mammographic masses" public dataset from the UCI repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass).

This data contains 961 instances of masses detected in mammograms, and contains the following attributes:
<ul>
<li>BI-RADS assessment (ordinal) - 1 to 5</li>
<li>Age (integer) - Patient's age in years </li>
<li>Mass shape (nominal)- Mass shape: round=1 oval=2 lobular=3 irregular=4</li> 
<li>Mass margin (nominal) - circumscribed=1; micro-lobulated=2; obscured=3; ill-defined=4; spiculated=5</li>
<li>Mass density (ordinal) - high=1; iso=2; low=3; fat-containing=4 </li>
<li>Severity (binomial) - benign=0 or malignant=1</li>
</ul>

<h2>Methodology</h2>
Data pre-processing:
<ul>
<li>Data exploration</li>
<li>Handling missing data</li>
<li>Feature selection</li>
<li>Normalization</li>
 </ul>
 
Apply several different classification supervised machine learning techniques and see which one yields the highest accuracy.
