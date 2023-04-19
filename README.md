# Parameter-optimization-of-SVM-for-Multiclass-Classification

Multiclass Classification is the type of classification in which the machine learning model classifies an instance in three or more classes.

SVM(support vector machine) is a supervised machine learning algorithm that helps in both classification and regression problem statements. It tries to find an optimal boundary (known as hyperplane) between different classes. In other words, SVM performs complex data transformations depending on the selected kernel function and aims to maximize the separation boundaries between your data points.

SVM also has some hyper-parameters (Optimal kernel, C or gamma values to use) and finding optimal hyper-parameter is a very hard task to solve. But it can be found by just trying all combinations and see what parameters work best

<h1>DATA ANALYTICS</h1><br />
We performed our observations on a nursery dataset from UCI dataset https://archive.ics.uci.edu/ml/datasets/Nursery 
Each attribute of Nursery dataset is categorical.
Label encoding was performed to modify the dataset.
It contains no NA values:<br />

<img width="186" alt="image" src="https://user-images.githubusercontent.com/65918628/232877658-05e9c531-1c56-4f21-96c3-5997460aa252.png">
<br />
No of rows : 12959
No of attributes : 8+1(target)
<br />

Class Distribution (number of instances per class)<br />

   not_recom    4320   
   recommend       2   
   very_recom    328   
   priority     4266   
   spec_prior   4044   

<br/>

<h3>The Best parameters for 10 different samples is as shown below :<h3><br />
<img width="363" alt="image" src="https://user-images.githubusercontent.com/65918628/233064119-c6d5c2a6-4dc1-499f-a90c-48a678726a5b.png">

<br />

Sample8 performed with best accuracy here.<br />
<h4>Convergence graph for accuracy of sample 8</h4><br />


The convergence graph for Sample 4 :


