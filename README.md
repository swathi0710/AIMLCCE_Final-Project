# AIMLCCE_Final-Project
<h1>Ingredient Analyser
for Consumables</h1>
<br>
<h2>Description</h2>
This tool aims to provide a means to judge the safety of consumable products based on the additives present in the ingredient list.
It uses a ML classification model to effiently rank the product on a scale of 1 to 5. 5 being the safest.

<h2>Steps to test the tool</h2>
(http://swathi071094.pythonanywhere.com/ "Click here to open the web service")<br>
1. Copy the ingredient list of the chosen product from any shopping service/ingredient database and click on the
“Classifier” link.<br>
OR<br>
Click on the “Sample ingredients” link and copy any ingredient list from the list provided and click on the “Go to Classifier”
link below the table.<br>
2. Paste the ingredient list in the form box and click classify to see how safe the product is ranked on a scale of 1-5 where 5
is the safest.
<br>
<h2>Stages invovled in the project</h2>

Data Collection:<br>
A collection of 10000 consumable products with their full ingredient list was obtained.

Data Preparation:<br>
Unwanted features were dropped and missing values were handled.

Labeling Records:<br>
Each Record is labeled intuitively on a scale of 1 to 5 based on the position and importance of the ingredients. Features are extracted from the ingredient list to train the ml model.

Training Classification Models:<br>
The data is split into training and testing subsets. Logistic Regression, Naive-Bayes     Classifier, K-Nearest Neighbors, SVM, Random Forest Classifier and  Decision Tree Classifier models are used to build classification models on the training data set.

Choosing the best Model:<br>
Performance metrics of the classification models are analyzed to choose the best model.

Serialization/Pickling:<br>
The trained model is saved into a file using Pickle module.

Designing a Web Service:<br>
A simple flask application is developed to take inputs from the user and provide the  classification.

Deploying:<br>
An HTML interface is built and hosted for ease of use.

<h2>Future Scope:</h2><br>
More samples should be collected and more features should be fed to the model to cover more scenarios and increase efficiency.
A mobile application which scans ingredients using image to text conversion should be built using the existing API.

Authored by:<br>
Swathi Venugopal<br>
[mail](mailto:swa094@gmail.com "gmail")

