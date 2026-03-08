# 🖼️ Custom-Image-Classifier 🔍

🔗Colab link here: https://colab.research.google.com/drive/1buGjTRW36ySGEwfDAsQlqxAQQcU3CLMF#scrollTo=UnHFYpw4z0BI

# **❓Guide Questions (Student Reflection & Explanation)📝**
1. Dataset Preparation
   --
**○ How did you organize your dataset in Google Drive?
○ Why is folder structure important for TensorFlow image loading?** <br>
<i>💡I re-used the dataset I used in teachable machine, I imported the dataset from the teachable mahine to my google drive. I renamed the folder and the subfolders to its corresponding name of species. <br>
💡Since TensorFlow automatically assigns labels based on the subfolder names. The folder structure determines how images are labeled and organized into datasets.<br> </i>

2. Model Training
   --
**○ What is the role of convolutional layers in image classification?
○ Why do we split data into training and validation sets?** <br>
<i>💡The role of convolutional layers is they are the ones who see the image and they learn its features like the shapes, textures, etc., and help the model to effeciently recognize it. <br>
💡Training set is used to teach the model while validation set is like a meeting with data the model hasn't seen before. By checking performance on the validation set, we can see if the model is truly learning the patterns or just overfitting the training data. Splitting data into training and validation sets is important because it prevents the model from just memorizing the examples it sees. </i> <br>

3. Performance Analysis
   --
**○ What accuracy did your model achieve?
○ How did the number of images affect the model’s performance?** <br>
<i>💡accuracy: 0.9672 <br>
💡The accuracy shows that the model had enough images to learn well in the dataset and achieve high validation accuracy. </i> <br>

4. Critical Thinking
   --
**○ What challenges did you encounter while using your own dataset?
○ How can data augmentation improve your model?** <br>
<i>💡The challenges I encountered is when I started training the my datasets because there are some images that didn't have the correct format of the image like "jpg, png" and TensorFlow detected it as problematic files so I had to identify every problematic files and convert it into required format using the Pillow library. <br>
💡Data augmentation helps give your model extra practice with different examples like its angles so it performs better on new unseen data. </i> <br>
