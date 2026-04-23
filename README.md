# 🖼️ Custom-Image-Classifier 🔍

🔗Colab link here: https://colab.research.google.com/drive/1buGjTRW36ySGEwfDAsQlqxAQQcU3CLMF#scrollTo=UnHFYpw4z0BI

# **❓Guide Questions (Student Reflection & Explanation)📝**
1. Dataset Preparation
   --
**○ How did you organize your dataset in Google Drive?** <br>
💬Answer: I re-used the dataset I used in teachable machine, I imported the dataset from the teachable mahine to my google drive. I renamed the folder and the subfolders to its corresponding name of species. <br><br>
**○ Why is folder structure important for TensorFlow image loading?** <br>
💬Answer: Since TensorFlow automatically assigns labels based on the subfolder names. The folder structure determines how images are labeled and organized into datasets.<br> 

2. Model Training
   --
**○ What is the role of convolutional layers in image classification?** <br>
💬Answer: The role of convolutional layers is they are the ones who see the image and they learn its features like the shapes, textures, etc., and help the model to effeciently recognize it. <br><br>
**○ Why do we split data into training and validation sets?** <br>
💬Answer: Training set is used to teach the model while validation set is like a meeting with data the model hasn't seen before. By checking performance on the validation set, we can see if the model is truly learning the patterns or just overfitting the training data. Splitting data into training and validation sets is important because it prevents the model from just memorizing the examples it sees. <br>

3. Performance Analysis
   --
**○ What accuracy did your model achieve?** <br>
💬Answer: Accuracy = 0.9672 <br><br>
**○ How did the number of images affect the model’s performance?** <br>
💬Answer: The accuracy shows that the model had enough images to learn well in the dataset and achieve high validation accuracy. <br>

4. Critical Thinking
   --
**○ What challenges did you encounter while using your own dataset?** <br>
💬Answer:The challenges I encountered is when I started training the my datasets because there are some images that didn't have the correct format of the image like "jpg, png" and TensorFlow detected it as problematic files so I had to identify every problematic files and convert it into required format using the Pillow library. <br><br>
**○ How can data augmentation improve your model?** <br>
💬Answer: Data augmentation helps give your model extra practice with different examples like its angles so it performs better on new unseen data.  <br>

5. Application
   --
**○ Suggest a real-world application for your trained model.** <br>
💬Answer:Trained orchid species model can be used in a plant identification. Images trained can be taken for a system to identify what kind of species it is. This helps a gardener, students, and researchers quickly recognize different orchids. It can also support plant conservation by helping experts monitor  rare orchid species. <br><br>
**○ How can this system be integrated into a mobile or web application?** <br>
💬Answer:The trained orchid species model can be integrated into a mobile or web application by connecting it to the app's backend. Users can upload or capture an image of an orchid using their phone or computer. The image will then sent to the server where the trained model processes it and predicts the orchid species. This allows users to easily identify orchid species through a simple and user-friendly interface. <br>


# **❓Guide Questions (Student Explanation & Reflection)📝**
**Visualization & Overfitting** 
--
**1. What signs indicated overfitting in your first model?** <br>
💬Answer:My first model indicated both accuracies high so there's no signs that indicates overfitting because the result shows good fit. 
**2. How did data augmentation affect validation accuracy?** <br>
💬Answer:Data augmentation gives multiple result of angles of one image and it helps identify accuracy with possible high result of validation. <br>

**Model Improvement**
--
**3. What is the purpose of dropout layers?** <br>
💬Answer: It helps improve the reliability of neural networks by making them less overfitting. <br>
**4. Why does data augmentation improve generalization?** <br>
💬Answer: Because its results provide multiple angles of the images.  <br>

**Performance Comparison**
--
**5. Compare accuracy before and after improvements.** <br>
💬Answer: Before the improvements, the accuracy is almost as close with each other but after improvements, the gap seemed to be very obvious and visible. <br>   
**6. Which technique contributed most to improvement?** <br>
💬Answer: The re-training of the model. <br>

**Deployment & Application**
--
**7. Why is saving the model important?** <br>
💬Answer:  It's important so you'll have records of what you've changed and you won't lose the data with the changes you have made. <br>
**8. How can this model be deployed in a real-world system?** <br>
💬Answer:  This helps improve and minimize difficulty in detection. <br>
