# Capstone Project - DATA2206
# Why is this project important?
Disruptions in circadian rhythm can lead to serious health issues such as cancer, mood disorders, and sleep disturbances. Traditional drug discovery methods are time-consuming, costly, and often fail due to undetected toxicity in candidate compounds. This project uses machine learning to predict molecular toxicity, helping identify harmful molecules earlier and accelerating the development of safer treatments.
# What kind of data did we use?
We worked with a structured dataset of 171 molecules, each described by numerical chemical descriptors. To ensure model fairness and reliability, we balanced the dataset using SMOTE and addressed outliers using Tukey's method. The target variable was binary-classifying compounds as toxic or non-toxic.
# How did we approach modeling?
Three models were evaluated: Logistic Regression, Decision Tree, and Random Forest. The Decision Tree model emerged as the top performer with an accuracy of 80% and a recall of 91% for toxic compounds - an essential metric in healthcare settings where failing to detect a toxic compound can be dangerous. Logistic Regression performed poorly, while Random Forest offered a more balanced but slightly less accurate alternative.
# What does this mean for drug discovery?
By using machine learning to screen for toxicity, pharmaceutical research can become faster, more cost-effective, and safer. This approach allows researchers to focus resources on promising compounds while reducing the risk of late-stage failures. Future improvements such as using ADASYN for smarter class balancing or incorporating deep learning could further enhance performance and scalability.
