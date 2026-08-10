# Summary
The following notebooks conduct a full ML pipeline on the BEED Epilepsy dataset. *The lack of subject identifiers and electrode/brain-region correspondence limits the interpretations to the observation rows.*
A Dummy Classifier, Logistic Regression, and a Random Forest model are used to classify each observation as healthy, seizure activity, focal, or generalized seizure. The pipeline also tests this problem as a binary classification. 

The RandomForest performed the best (especially in binary) and struggled distinguishing between focal seizures and general seizure activity the most. The physiological interpretation is limited, 
so future work will utilize data with more identifiers as well as more robust models.
