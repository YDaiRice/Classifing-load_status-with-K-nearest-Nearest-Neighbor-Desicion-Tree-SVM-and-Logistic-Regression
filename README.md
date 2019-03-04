# Machine_Learning_Class_Project
#### This is the [final project code in jupyter notebook](ML-CL8-Project.ipynb) for class Machine Learning by Python by IBM. Below are the summary.
* Data Visulization and Preprocessing
* Feature Selection and Data Engineering
* Find best model among the following classifiers
  1. K-Nearest Neighbour Classifier
  2. Desicion Tree
  3. Support Vector Machine
  4. Logistic Regression
* Calculate the Jaccard similarity and F1-score for classfier
* Conclusion
* Note and Future work
  1. Tried Random forest but becuase the dataset has only 300 data, Random forest has the similar accuracy with Decision Tree.
  2. The F1-score is only for loan_status 'PAID_OFF' not for 'COLLECTION'.The F1-score for 'COLLECTION' is much lower than 'PAID_OFF'. I think it is becuase the dataset has much more 'PAID_OFF' label then 'COLLECTION' label(260:86), the predication bias toward 'PAID_OFF'. 
  3. I will try feature study with Random forest and parameter selection with cross-validation in future. The first one will improve understanding of dataset. The second one will enure better parameter selected. 
