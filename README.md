# breast-cancer-detection
# Breast_cancer_prediction_

![Project Logo/Image](https://raw.githubusercontent.com/deepak525/Breast-Cancer-Visualization-and-Classification/a624b112600b87dc9f35e4163a2488ff827eacd1//sps.png)
## ➲Overview
## ➲Prerqusites
This is list of required packages and modules for the project to be installed :

- Python 3.x

- Pandas

- Scikit-learn

Install all required packages :
```bash
!pip install -r requirement.txt
```
## ➲The Dataset
## ➲Dataset Description
The Data description is as follows:

- diagnosis: The diagnosis of breast tissues (1 = malignant, 0 = benign) where malignant denotes that the disease is harmful

- mean_radius: mean of distances from center to points on the perimeter

- mean_texture: standard deviation of gray-scale values

- mean_perimeter: mean size of the core tumor

- mean_area: mean area of the core tumor

- mean_smoothness: mean of local variation in radius lengths

**Dataset head:**

![Project Logo/Image](https://github.com/rishika-shrimal2107/Breast_cancer_prediction_/blob/main/Images/Screenshot%202024-01-29%20064517.png)

### Libraries used
```python
import pandas as pd #for chopping, processing
from sklearn import tree
from sklearn.model_selection import train_test_split # to split the data in train and test
from sklearn import metrics  # for checking the accuracy

#Classifiers 

from sklearn.neighbors import KNeighborsClassifier # for K neighbor classifier
from sklearn.tree import DecisionTreeClassifier #for decision tree classifier
from sklearn.naive_bayes import GaussianNB  #for naive bayes classifier
from sklearn.ensemble import RandomForestClassifier #for Random Forest
from sklearn.ensemble import GradientBoostClassifier # Boost
from sklearn.ensemble import BaggingClassifier # Bagging
from sklearn.linear_model import LogisticRegression #for Logistic Regression
from sklearn.svm import SVC # for SVM 
### Classifiers used to predict the breast cancer for a training size = 455 

Type of Classifiers | Training accuracy | Testing accuracy |
:---:|:---:|---:
**Decision Tree Classifier** | 99.0% | 92.0% | 
**Bagging Classifier** | 98.0% | 93.0% | 
**Gradient Boosting Classifier** | 99.0% | 94.0% |
**Naive Bayes GaussianNB** | 90.0% | 95.0% | 
**Random Forest Classifier** | 99.0% | 94.0% |
**K-Neighbors Classifier** | 99.0% | 94.0% | 
**Logistic Regression** | 93.0% | 94.0% |
**SVM Linear** | 93.0% | 94.0% | 
**SVM rbf** | 94.0% | 95.0% | 







## ➲Installation


   1. **Clone the Repository:**
   ```bash
   git clone https://github.com/rishika-shrimal2107/Breast_cancer_prediction_.git
   ```

   2. **Run the code from cmd:**
   ```bash
   python Breast_cancer_prediction_.py
   ```

   ## ➲Contact

- E-mail   : [rishita.u1234@gmail.com@gmail.com](mailto:rishita.u1234@gmail.com)
  
