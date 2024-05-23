# Machine-learning
**What is machine learning?**

In simple term, machine is learning. But how? We train machine with some training data then machine will learn from it to make predictions when new data is being fed. Hence, machine learning is training computer/machine to learn from data. 

https://github.com/Laxmi-Dhungel/Machine-learning/assets/154451345/cf11a447-b412-436d-bd94-0c81562d4bff

**Types of Machine learning System**

**Does the training require human supervision?**

Can be Supervised, Unsupervised, Semisupervised and Reinforcement learning. 

**Supervised learning**: The training data fed to the system includes desired solutions. Examples, k-nearest neighbors, Linear regression, Logistic regression, Support Vector Machines (SVMs), Decision Trees and Random Forests, Neural networks. A very simple example of supervised learning is feeding training data with body temperature and labeling them as fever OR no fever based on whether temperature is above 98 degree F or less than or equal to 98 degree F (System with desired solutions). With this training data, machine can now classify new data as fever or no fever based on the given body temperature.

**Unsupervised learning**: No teacher!! Unlabelled training data. Learns on its own by either detecting similarities, correlated features, anomaly detection, and assoication between attributes. Examples, Clustering (k-means, Hierarchical Cluster Analysis (HCA)), visualization and dimensionality reduction (Principal Component Analysis (PCA), Kernel PCA), Association rule learning (Apriori, Eclat). Example of unseupervised learning: machine is trained with normal body temperature and it detects when there is an abnormal body temperature (anomaly detection)

**Semisupervised learning**: Partially labeled training data. Example, Google photos recognizing family members in all the other photo when you labelled them in just one photo.

**Reinforcement learning**: Learn by experience. The system is introduced to the environment, gets rewards for positive experiences and penalties for negative experiences. Then it makes a strategy (policy) to get most reward. This policy is used to decide on how to react in a given situation. (Similar human example: we decide if we want to watch particular show on TV based on our experience (Reward/penalty) :) ). Examples, Robot learning how to walk.


**Is machine learning in batch or on the fly?**

Can be batch or Online learning

**Batch learning**: Trained using all the available data and launched. To train about new data, training needed from scratch (using both old and new data) and replace the old system with new system. 

**Online learning**: Learning on the fly. Continous feed the system with new data for learning. 

**Instance based vs model-based learning**

**Instance based learning**: Learn the examples by heart to generalize in new cases. Example, flagging spam emails based on similarity of words.

**Model-based learning**: : Build a model based on the example and make predictions based on that model. Example, using linear regression to predict target variables. 


**Other terms**

**Overfitting and underfitting**

**Overfitting**:  Good performance in training data however, performs over generalization on test data. May result due to noise, small training set. Model too complex. 

**Underfitting**: Model too simple and cannot understand the underlying data structure. Inaccurate predictions even on training data sets. 
