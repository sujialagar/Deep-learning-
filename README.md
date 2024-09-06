# Title
Manga Book Classifier
# Assignment Describtion
Images are categorized by this project into two groups: books (Libros) and comics (Mangas). TensorFlow and Keras are used to build the classification model, which is trained on a dataset taken from the yorius96/manga_book_classifier collection. The objective is to use deep learning algorithms to accurately identify between images of manga and books.
# Features
Images are divided into two categories: comics (Mangas) and books (Libros).
TensorFlow and Keras are used to create a deep learning model.
Overfitting can be avoided by using regularization techniques like Batch Normalization and Dropout.
To guarantee peak performance, early halting and model checkpointing are used.
# Model Training
The model was trained with a convolutional neural network (CNN) architecture on the Manga Book Classifier dataset. Important methods used in the training such as
Dropout Regularization: During training, a portion of the input units are randomly set to zero to prevent overfitting.
Batch normalization: By normalizing inputs to each layer, this technique accelerates and stabilizes training.
Early Stopping: When performance on the validation set no longer improves, training is stopped.
Model Checkpointing: This feature automatically preserves the model that performs the best throughout validation.
# Result
Accuracy: The model successfully distinguished between "Libros" and "Mangas" with over 70% accuracy on the validation set.
Confusion Matrix: A thorough examination of the confusion matrix reveals excellent performance and very few incorrect classifications
