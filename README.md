# Lending-Club-Capstone
Capstone Supervised Learning 

This capstone project looks at data from LendingClub in order to analyze if we can predict if a customer will default vs. pay in full based on various variables. This is done by using supervised learning methods. 

The first notebook titled, Unit 3 Capstone Final, shows the supervised learning models used including Random Forest with Grid Search, Logistic Regression with Grid Search, KNN Neighbors and Naive Bayes. Accuracy scores from each models are provided in the notebook.

The second notebook titled, Class Imbalance Fixes (RF and LR), shows how I handle the classification problem faced in the dataset. Most financial datasets are imbalanced so it is important to look at precision and recall scores for the minority class (here: Default customers). There is more of a risk to a company if the model incorrectly predicts that a customer will not default when in reality they do. Therefore, I focused on increading precision for the minority class. I did this by applying class weights on two of the best performing models from the initial notebook. 

