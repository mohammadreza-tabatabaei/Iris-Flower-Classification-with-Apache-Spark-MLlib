# Iris Flower Classification with Apache Spark MLlib
## 📂 Dataset
The dataset used in this project is the Iris dataset, which contains 150 samples of iris flowers categorized into three species
Setosa
Versicolor
Virginica

The dataset features:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)

## 🏗 Project Workflow
1. Load the dataset using Spark DataFrame.
2. Convert feature columns into a single feature vector using VectorAssembler.
3. Convert categorical labels (Species) into numerical labels using StringIndexer.
4. Split the data into training (60%) and test (40%) sets.
5. Train three different classifiers:
  Naive Bayes
  Multilayer Perceptron (Neural Network)
  Decision Tree
6. Evaluate models using MulticlassClassificationEvaluator.
7. Compare the accuracy of the models.

## 🛠 Future Improvements
Experiment with Random Forest and Gradient Boosted Trees (GBT).
Optimize hyperparameters for better accuracy.
Implement cross-validation to improve model selection.

## 📌 Author
👤 Mohammadreza Tabatabaei




