# Improved-Predictive-Outcome-using-PCA
PCA is a dimensionality reduction technique useful to represent high dimension space in low dimensional space with minimal loss of information. 
The key trick of PCA is to discover new axis such that it captures the maximum essence of the original data set in the form of variation. The number of axis discovered by PCA are equal to the number of dimensions present in the data set. Each axis is the linear combination of variables present in the original data set. In PCA terminology, new axis discovered are called principal component(PC).Each principal component explains some percentage of the variation within the data. The first principal component always explains
the most variation, followed by the second, and so on. PCA has wide applicability in various domains and can be applied on numeric, textual and image
data sets.

PCA technique not only helps in dimensionality reduction but, is a useful way of discovering hidden insights from given a data set which
otherwise may be left unidentified. The way it is performed by discovering new axis that help giving a new angle of representing the data set. 
This charateristics of PCA is useful in improving classification and clustering results. At times, classification models results in poor
performance even when hypertuned. In such cases, PCA can be integrated with classification task to improve the performance.

This small project demonstrates  use PCA to improve classification results. A small medical data set on heart disease is taken for study.
It is (303 x 14) in size. First,a simple Decision tree classifier is applied on the data set and  performance is evaluated. Then, 
PCA is applied and its transformation is taken. Next, Decision tree model is built and tested on new data set. Finally, a comparison is shown
between decision tree performance on original and transformed dataset. The results reveales performance improvement by 5%. 

More details on PCA can be found here:


https://drive.google.com/file/d/1QBSNQvAYsj1Lpd_x41VXXHGA25Ih0EV5/view?usp=sharing

Data set details :


Name of data set: heart attack 


Data set link :

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset






