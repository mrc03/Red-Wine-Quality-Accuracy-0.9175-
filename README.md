/* Date : 05/07/2018
   Author: Raj Mehrotra
*/

The Red Wine Quality dataset from kaggle.


The dataset contains details about samples of wine and different features accounting for the concentrations of the different chemicals in 
the wine. The target variable is the quality of the wine on a scale of 0-10.


I have first explored and analyzed the data and visualized using pandas,matplotlib,seaborn library and studied distribution of different categorical as well as numerical features. Then I have cleaned the data and prepare it for modelling.Then I have also scaled all the numeric features for better performance using the StandardScaler provided by sklearn. 


Finally I have used different ML algorithms from the scikit learn including SVM,RandomForest etc... . I have also tuned the parameters of all the algorithms using the GridSearchCV function.


Lastly I got an accuracy of 0.9175 on the dataset by using a Support Vector Machine with 'rbf' kernel and the tuned values of parameters 'C' and 'gamma'.
