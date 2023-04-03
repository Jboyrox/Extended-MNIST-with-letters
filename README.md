# Extended-MNIST-with-letters
I extend the MNIST dataset by adding a number of non-digit letters and see if the classifier can distinguish the digits from the non-digits. All non-digits will be lumped as a single 11-th class. This is a highly simplified version of 'detection' problem (as opposed to 'classification' problem). Detection is vital in OCR and related problems since the non useful characters must be rejected.</br>
I also:</br>
1)Combine multiple datasets</br>
2)Select the SVM parameters (C and gamma) via cross-validation.</br>
3)Use the GridSearchCV method to search for parameters with cross-validation.</br>
The results of this experiment are present in the notebook emnist.ipynb
