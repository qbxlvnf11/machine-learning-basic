
Description
=============

#### - Basic machine learning model
#### - Upload code as a Jupiter Notebook file (.ipynb) for immediate understanding


Contents
=============

#### - K-NN Classifier and Regressor
#### - Comparison between Decision Tree and Random Forest
#### - MNIST, CIFAR-10 Image Classifier with Multi Class ROC Curve
#### - Charcter-level Featrue and Word-level Feature t-SNE
#### - Bidirectional LSTM News Classifier with Character Embedding
#### - Recurrent Convolution News Classifier with Character Embedding
#### - Solving Regression Problem (Prediction of Fuel Efficiency)

Datasets
=============

#### - News Aggregater

https://www.kaggle.com/uciml/news-aggregator-dataset

#### - Pima Indians Diabetes

https://www.kaggle.com/uciml/pima-indians-diabetes-database

#### - Auto MPG

https://archive.ics.uci.edu/ml/datasets/auto+mpg

References
=============

#### - CIFAR10 Classifier

https://appliedmachinelearning.blog/2018/03/24/achieving-90-accuracy-in-object-recognition-task-on-cifar-10-dataset-with-keras-convolutional-neural-networks/

#### - Multi-class ROC Curve

https://scikit-learn.org/stable/auto_examples/model_selection/plot_roc.html

#### - Sequence Data Classifier

https://tykimos.github.io/2017/08/17/Text_Input_Binary_Classification_Model_Recipe/

#### - K-NN

https://subinium.github.io/MLwithPython-2-3-1/

#### - t-SNE

https://www.kaggle.com/eliotbarr/news-exploration

#### - Confusion Matrix Visualization

https://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html

#### - Regression Problem

https://www.tensorflow.org/tutorials/keras/regression?hl=ko

Erratum of Jupyter Notebook Files
=============

#### - News_classifier_recurrent_convolution.ipynb

[29] block: 

y_train = np.expand_dims(X_train, -1) -> y_train = np.expand_dims(y_train, -1)

y_test = np.expand_dims(X_test, -1) -> y_test = np.expand_dims(y_test, -1)

#### - News_classifier_bidirectional_LSTM.ipynb

[29] block: 

y_train = np.expand_dims(X_train, -1) -> y_train = np.expand_dims(y_train, -1)

y_test = np.expand_dims(X_test, -1) -> y_test = np.expand_dims(y_test, -1)

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
