# Lightdetection-Imageclassification
This project showcases my work in leveraging deep learning to solve real-world challenges in smart home automation. I developed a light status detection system to classify lighting conditions—artificial, natural, and no light—aimed at improving energy efficiency and user comfort.

# What I Did

Dataset: I collected and annotated 97 images, ensuring quality and relevance across three classes.

Preprocessing: I rescaled pixel values, identified and removed corrupt files, and split the data into train/test sets for better performance.

Models: I implemented transfer learning using MobileNetV2 and InceptionV3 to achieve accurate classification.

# Tools and Techniques

Frameworks: TensorFlow and Keras were my go-to tools for building and training the models.
Techniques: I applied transfer learning, data augmentation, and caching/prefetching to optimize training and improve model efficiency.

# Results
MobileNetV2: Delivered 84% accuracy, proving its efficiency and reliability for this task.
InceptionV3: Achieved 58% accuracy but showed limitations in generalizing across classes.

Through this project, I discovered that MobileNetV2’s lightweight architecture is particularly well-suited for real-time applications in smart home environments. Its strong performance highlights its potential for energy-efficient and adaptive systems.
