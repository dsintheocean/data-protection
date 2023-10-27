# Customer Personal Data Protection

## Project Description
Development of a method for anonymizing personal data.  
The goal is to protect data in such a way that the quality of machine learning models does not deteriorate after transformation.  

## Key Findings
A method for protecting personal data by multiplying features by a random invertible matrix has been developed.  
It has been demonstrated that this method does not degrade the quality of linear regression.  
As practical confirmation, the same value of the R2 metric was obtained for linear regression trained on encoded features.  

## Additional Information
Toolkit: Pandas, NumPy, Linear Algebra, Python, Scikit-learn.
