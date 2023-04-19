# Parameter-optimization-of-SVM-for-Multiclass-Classification

Multiclass Classification is the type of classification in which the machine learning model classifies an instance in three or more classes.

SVM(support vector machine) is a supervised machine learning algorithm that helps in both classification and regression problem statements. It tries to find an optimal boundary (known as hyperplane) between different classes. In other words, SVM performs complex data transformations depending on the selected kernel function and aims to maximize the separation boundaries between your data points.

SVM also has some hyper-parameters (Optimal kernel, C or gamma values to use) and finding optimal hyper-parameter is a very hard task to solve. But it can be found by just trying all combinations and see what parameters work best

# DATA ANALYTICS
We performed our observations on a nursery dataset from UCI dataset https://archive.ics.uci.edu/ml/datasets/Nursery 
Each attribute of Nursery dataset is categorical.
Label encoding was performed to modify the dataset.
It contains no NA values:

<img width="186" alt="image" src="https://user-images.githubusercontent.com/65918628/232877658-05e9c531-1c56-4f21-96c3-5997460aa252.png">


      No of rows : 12959
      No of attributes : 8+1(target)

      Class Distribution (number of instances per class)

      not_recom    4320   
      recommend       2   
      very_recom    328   
      priority     4266   
      spec_prior   4044   

<br/>
On our entire dataset we made 10 samples and by splitting them into 70:30 train test ratio,The best accuracy for all was recorded.
<br/>
# The Best parameters for 10 different samples is as shown below :
<img width="363" alt="image" src="https://user-images.githubusercontent.com/65918628/233064119-c6d5c2a6-4dc1-499f-a90c-48a678726a5b.png">


Sample 6 and 8 performed with best accuracy here.
   
# Convergence graph for accuracy of sample 6 
<img width="302" alt="image" src="https://user-images.githubusercontent.com/65918628/233078814-af690d27-0925-4ba8-a0a7-77c8959b3396.png">





