# Machine Learning Model

So in this project, we developed a machine learning model that is able to classify brain tumor types based on MRI images. This model uses a Convolutional Neural Network (CNN) architecture that is specifically designed for classification tasks. This model has four convolutional layers equipped with BatchNormalization and MaxPooling. This model is trained using a dataset that has been preprocessed through augmentation and normalization, so that it can produce accurate predictions for brain tumor types. We also trained our model with 30 epochs and after that we obtained the following results:

![image](https://github.com/user-attachments/assets/a46e1c70-a4d7-4a32-9572-afab8a6df58e)


![image](https://github.com/user-attachments/assets/776a2f63-f790-4298-b149-779cbd0a2354)

# Evaluasi Model pada Data Testing
Untuk mengevaluasi kinerja model dalam mengklasifikasikan jenis-jenis tumor otak, kami menggunakan Confusion Matrix dan Classification Report.
## berikut hasilnya:
![image](https://github.com/user-attachments/assets/bf8e04dc-c3d0-433a-8c26-ded369f8a1d5)

Classification Report:

    precision    recall  f1-score   support
glioma       1.00      0.84      0.91       163
meningioma       0.86      0.89      0.88       165
notumor       0.96      0.98      0.97       201
pituitary       0.90      0.99      0.95       176

accuracy                           0.93       705
macro avg       0.93      0.93      0.93       705
weighted avg       0.93      0.93      0.93       705
