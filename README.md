# Summary
The following notebooks conduct a full ML pipeline on the BEED Epilepsy dataset. *The lack of subject identifiers and electrode/brain-region correspondence limits the interpretations to the observation rows.*
A Dummy Classifier, Logistic Regression, and a Random Forest model are used to classify each observation as healthy, seizure activity, focal, or generalized seizure. The pipeline also tests this problem as a binary classification. 

The RandomForest performed the best (especially in binary) and struggled distinguishing between focal seizures and general seizure activity the most. The physiological interpretation is limited, 
so future work will utilize data with more identifiers as well as more robust models.

<img width="1262" height="726" alt="Screenshot 2026-08-10 123421" src="https://github.com/user-attachments/assets/c0bc87a4-2550-44aa-abb4-49dd382e4597" />
<img width="506" height="501" alt="Screenshot 2026-08-10 123408" src="https://github.com/user-attachments/assets/aa9a1fd0-d395-421c-9f44-dedd7b08ee40" />
<img width="1262" height="726" alt="Screenshot 2026-08-10 123421" src="https://github.com/user-attachments/assets/2babbc76-6801-43b3-ad38-5e9432d81145" />
<img width="1219" height="939" alt="Screenshot 2026-08-10 123757" src="https://github.com/user-attachments/assets/9d03fc7b-6db1-46e1-9c9a-07001ad7de6b" />
