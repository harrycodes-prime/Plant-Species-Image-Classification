# Plant-Species-Image-Classification

https://drive.google.com/drive/folders/1X7r9qPx0bbonH6GolK5jxFyPpASlzI9l?usp=sharing

# DATA SET SCREENSHOT


<img width="1900" height="973" alt="Data Set" src="https://github.com/user-attachments/assets/c9a3adc5-2eee-4f8b-994e-f0c8d8b0cd2d" />

# A. Project Overview Brief description of the project 
   - This project uses Teachable Machine by Google to create an image classification model that can identify different tree species.

The dataset contains 20 classes with a total of 5,000 image frames. Each class has an equal number of images to keep the data balanced. The images show different angles, lighting conditions, and backgrounds to help the model learn better.

The main goal of the project is to train a model that can correctly recognize and classify trees based on their visible features, such as leaf shape, color, texture, and overall appearance.

With 5,000 images across 20 classes, the dataset provides enough data to train the model and achieve accurate and reliable results, especially when properly trained and tested.


# PURPOSE OF THE IMAGE CLASSIFICATION MODEL

   - The purpose of the image classification model is to automatically identify and classify different tree species using images. By analyzing visible features such as leaf shape, color, texture, and overall tree structure, the model can determine which class a tree belongs to without manual inspection. This reduces the time and effort needed for identification and helps minimize human error. The system is designed to provide a faster, more consistent, and reliable method of recognizing tree species, which can support environmental monitoring, research activities, and educational purposes.


# B. Plant Species Section

![2](https://github.com/user-attachments/assets/e291e9f7-dbb2-48da-8799-1a8e9d6f25c8)


The Banaba tree is a medium to large tropical tree known for its beautiful clusters of bright purple or violet flowers. When it blooms, the tree becomes very colorful and stands out because of its many flowers covering the branches. Its leaves are green, smooth, and oval-shaped, and they grow thickly around the tree, giving it a full and healthy appearance. The Banaba tree grows well in warm climates and is commonly found in tropical countries. It is often planted along roads, in parks, and in gardens because it provides shade and adds beauty to the surroundings. Aside from its appearance, the leaves of the Banaba tree are also known to be used in traditional herbal practices.

The Banaba tree has purple flowers because of natural pigments found in its petals. These pigments are called anthocyanins, which are responsible for red, purple, and blue colors in many plants.
Anthocyanins help attract pollinators like bees and butterflies. The bright purple color makes the flowers more visible, which helps the tree reproduce because pollinators are drawn to colorful flowers.
The exact shade of purple can also be affected by factors like sunlight, soil condition, and the natural chemistry inside the plant cells.


# C. Model Training Details

<img width="222" height="488" alt="Model" src="https://github.com/user-attachments/assets/032430c0-0fe6-490d-86de-622cff2d7c2e" />

Number of images per class :250

# D. Model Evaluation

<img width="389" height="631" alt="Epoch" src="https://github.com/user-attachments/assets/4c6f5748-dfb5-4ecd-8e29-ad89f516a4d1" />

# E. Model Testing

<img width="206" height="937" alt="1" src="https://github.com/user-attachments/assets/f9f0c052-a7ad-403b-ae34-d9fe0f0c749e" />

<img width="200" height="935" alt="2" src="https://github.com/user-attachments/assets/c9dff903-e5cd-4055-8225-bf6eef41e9b6" />

<img width="199" height="933" alt="3" src="https://github.com/user-attachments/assets/160c8a80-68b4-4f8b-815d-659e3cf686ac" />

<img width="200" height="932" alt="4" src="https://github.com/user-attachments/assets/8a85b5e7-3563-44a2-abcc-de7115b08d6c" />

<img width="201" height="932" alt="5" src="https://github.com/user-attachments/assets/ea5a1754-1b3b-40d3-9c32-2550b819b3fb" />

<img width="201" height="934" alt="6" src="https://github.com/user-attachments/assets/3cb5f723-adb6-46e1-8f87-b6990a5ca476" />

<img width="205" height="934" alt="7" src="https://github.com/user-attachments/assets/b42ceefc-8df8-48fc-909b-0eb5bbd4b281" />

<img width="200" height="935" alt="8" src="https://github.com/user-attachments/assets/94d90dcb-4c14-42ab-8496-7ac1cc8fc01f" />

<img width="203" height="935" alt="9" src="https://github.com/user-attachments/assets/db27a88d-3103-409e-b01a-9682f838ebd0" />

<img width="199" height="938" alt="10" src="https://github.com/user-attachments/assets/e64ff9de-2d28-4a4b-afca-49907f7acdac" />



# REFLECTION QUESTIONS: 

  1. How did the number of images per class affect your model's accuracy?

      Answer: The number of images per class had a big effect on the model’s accuracy. Since each class had 250 images, the dataset was balanced, which helped the model learn each tree species equally. Having enough images allowed the model to                        recognize different features like leaf shape, color, and texture better, which improved its accuracy. If there were fewer images, the model might have struggled to identify some classes correctly.

  2. Which plant species were most commonly misclassified and why?

      Answer: The plant species that were most commonly misclassified are most of them, because of their similar features, such as leaf shape or color. For example, trees with similar green leaves or small flowers could confuse the model.                              Misclassification usually happened because the images looked alike, or the angles and lighting in some images were not clear enough for the model to tell the difference.


   3. How did you changing the epochs, batch size, or learning rate affect the training results?

       Answer: Changing the number of epochs, batch size, or learning rate affected how well the model learned. More epochs helped the model improve accuracy but could also cause overfitting if too many were used. A smaller batch size made the model                   learn more slowly but sometimes improved precision, while a larger batch size trained faster but could reduce accuracy. Adjusting the learning rate also changed how quickly the model learned, and the right balance helped the model reach                 better performance.

   4. What challenges did you encounter during dataset collection and labeling?

       Answer: One challenge was making sure all 5,000 images were clear and of good quality. Some images had poor lighting or angles that made the tree features hard to see. Another challenge was labeling each class correctly because some trees looked                similar, and mistakes in labeling could affect the model’s accuracy. Collecting images from different angles and backgrounds also took time.

   5. If you were to improve your model, what specific changes would you make why?

       Answer: To improve the model, I would collect more images for each class, especially for trees that are easily confused. I would also include more variety in lighting, angles, and backgrounds so the model can recognize trees in real-world                       conditions. Additionally, I could try tuning the epochs, batch size, and learning rate more carefully to prevent overfitting and improve overall accuracy. Finally, using image augmentation like rotation or zoom could help the model learn                better from limited data.














