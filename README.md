## Predicting Severity of Mammographic Masses

The .ipynb file is also viewable on https://nbviewer.org/github/asvch/mamm-severity/blob/main/FinalProject_Mammogram_Severity.ipynb

A lot of unnecessary anguish and surgery arises from false positives arising from mammogram results. If we can build a better way to interpret them through supervised machine learning, it could improve a lot of lives.

Predicting severity (benign=0 or malignant=1) using the following attributes of masses: 
1. Age: patient's age in years (integer)
2. Shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
3. Margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
4. Density: high=1 iso=2 low=3 fat-containing=4 (ordinal)

Several approaches resulted in an accuracy of around 78-81%. If we have a choice of multiple algorithms that are around equally good for a problem, we should just keep it simple! 

So taking into account both the score and the simplicity, Logistic Regression (80.72%) was the clear winner.

![image](https://github.com/user-attachments/assets/b47bf552-5336-4646-b209-730748d05502)
