# Identification of Diabetes in Pima Indian Population

<img src="https://github.com/misiungs/readme_images/blob/master/diabetes.jpg?raw=true" alt="drawing" width="500"/>

# Problem

The project consists of data gathered from Pima Indian population near Phoenix, Arizona.
The study was carried out by the National Institute of Diabetes and Digestive and Kidney Diseases and it focused on identifying diabetes.
The goal is therefore to classify whether the person is a diabetic based on provided personal data.

The dataset comes from the article:
Smith, Jack W., et al. Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In: Proceedings of the Annual Symposium on Computer Application in Medical Care. American Medical Informatics Association, 1988. p. 261.

# Approach

First the dataset has been explored.
The key features and their interactions have been identified.
Next, numerous classification algorithms have been applied ranging from simple logistic regression to voting classifier which ensembles multiple classifiers.
Results from different models have been compared and the best approach has been chosen.

# Conclusions
The best model was an ensemble method, the voting classifier made out of random forest and gradient boosting classifiers.
The final achieved accuracy was 83.9%.

