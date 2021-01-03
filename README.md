# APS360
Artificial Intelligence Fundamentals

<br>
<h3>Pneumonia Detetction (Course Project)</h3>

<p>The purpose of this project is to automate the classification of pneumonia given an image of a chest X-ray and detecting the presence of lung opacities. The dataset consists of chest X-rays of children aged 1–5 years from Guangzhou Women and Children’s Medical Center found on Kaggle. The chest X-rays were originally classified into three categories: normal, bacterial pneumonia and viral pneumonia. </p>

<p>The automation is accomplished through the use of transfer learning. By combining the convolutional layers of a pre-trained AlexNet model with a fully-connected ANN, we are able to achieve classification accuracies of 96.61% on 412 never-seen-before images in approximately 1.15s. Comparatively, a linear SVC chosen as the baseline model was only able to achieve an accuracy of 93.0% on the same test dataset. </p>

<h3>Labs</h3>

* *Lab 1 PyTorch and ANNs* > This introductory lab introduced Deep Learning frameworks, such as PyTorch, while reviewing the basics of Python and relevant Python libraries. It also involved designing a simple 2-layer ANN to classify whether a given handwritten digit was less than or greater than 3 and training the neural network using the MNIST dataset.

* *Lab 2 Cats vs Dogs Using a CNN* > This lab provided the experience required to work with images and large datasets, such as CIFAR-10. Inputs with spatially-related features perform much better with a CNN compared to a multi-layer perceptron network, and the purpose of this lab was to classify an image into one of two classes ("cat" or "dog") using a CNN. Following the parameter-training, I had the opportunity to experience the process of hyperparameter optimization using learning curves for the training and validation datasets.

* *Lab 3 Gesture Recognition Using a CNN* > Similar to Lab 2, this lab also focused on working with images, placing a greater emphasis on creating our own datasets for various hand gestures from the sign language. This process involved generating the data as well as overcoming the challenges involved during the data cleaning process. The second part of the lab involved a multi-class classification problem, which was first solved by using a CNN of my own design and later, using transfer learning (AlexNet) to improve the initial model.

* *Lab 4 Data Imputation Using an Autoencoder* > Moving away from classification problems, this lab introduced the concepts of unsupervised learning and using Deep Learning to generate data. Using the census records in the Adult Data Set provided by the UCI Machine Learning Repository, this lab used a denoising linear autoencoder to perform the task of generating missing values in the records. The data cleaning process allowed me to gain experience with textual data, including one-hot encoding, as well as using baseline models to interpret model performance.

* *Lab 5 Spam Detection using an RNN* > Similar to Lab4, this lab also focused on working with textual data using the concepts of tokenization and batching for RNNs. Text from emails were inputted into a character-level RNN to classify whether an email was "spam" or "not-spam". This lab also provided an opportunity to study how various models, such as GRUs and LSTMs, performed, while analyzing specific aspects of model performance, such as false positives and false negatives.

<h3>Tutorials</h3>

* *Tutorials 1-5* > These tutorials covered concepts very similar to Labs 1-5 with different problems.

* *Tutorial 6* > 

* *Tutorial 7* >
