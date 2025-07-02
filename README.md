Training ai by Teachable Machine and Google Colab for Human vs. Robot Image Recognition

Overview

This project demonstrates how to create and train an AI model using Teachable Machine and Google Colab to recognize "human" and "robot" images from sample datasets. The model is trained in Teachable Machine and fine-tuned or tested using Google Colab with TensorFlow.

Requirements





Teachable Machine: Access via teachablemachine.withgoogle.com



Google Colab: Access via colab.research.google.com



Python Libraries: TensorFlow, NumPy, PIL (installable via pip)



Dataset: Images of humans and robots (e.g., 9 robot samples, 7 human samples)

Setup

Teachable Machine





Visit Teachable Machine and create a new project.



Upload images:





Add 9 image samples for the "robot" class.



Add 7 image samples for the "human" class.



Use the "Upload" or "Google Drive" option to import images.



Train the model:





Click "Train Model" and wait for the training to complete.



Export the model:





Select "Export Model" and choose TensorFlow as the format.



Download the keras_model.h5 and labels.txt files.

Google Colab





Open a new Colab notebook.



Upload the exported keras_model.h5 and labels.txt files to Colab.

images of the work
<img width="1427" alt="Screenshot 1447-01-06 at 7 12 32 PM" src="https://github.com/user-attachments/assets/69972c83-9cac-47cb-bf98-35da2c767969" />
<img width="1427" alt="Screenshot 1447-01-06 at 7 13 20 PM" src="https://github.com/user-attachments/assets/55f49178-0992-4a01-84b5-bf9f3f4f63fb" />
<img width="1427" alt="Screenshot 1447-01-06 at 7 46 11 PM" src="https://github.com/user-attachments/assets/58871cce-9b34-4fd4-b91f-9d76a6b590e0" />
<img width="1427" alt="Screenshot 1447-01-06 at 7 46 16 PM" src="https://github.com/user-attachments/assets/c80b37d3-58e9-4984-98be-533ba4ce61e5" />







