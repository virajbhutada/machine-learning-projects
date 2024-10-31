
## Hand Gesture Recognition 
**Overview**
This repository presents a sophisticated hand gesture recognition system employing Convolutional Neural Networks (CNNs) for intuitive human-computer interaction and gesture-based control systems. The project seamlessly integrates computer vision techniques with machine learning methodologies to accurately classify various hand gestures, paving the way for innovative applications in virtual reality, gaming, assistive technology, and beyond.

**Dataset**
The dataset consists of near-infrared images captured by the Leap Motion sensor. It encompasses 10 unique hand gestures meticulously performed by 10 different subjects, ensuring diversity in gesture styles and orientations. Each gesture is meticulously organized into folders corresponding to the subjects (00 to 09) and specific gestures (e.g., "01_palm," "02_l," "10_down"), offering a comprehensive and structured dataset for model training and evaluation.

**Dataset Source:** https://link.springer.com/chapter/10.1007/978-3-319-48680-2_5

**Dataset Link**: https://www.kaggle.com/datasets/gti-upm/leapgestrecog

**Project Tasks**

**1. Data Loading and Preprocessing:**
- Loaded and preprocessed near-infrared images, ensuring uniformity and compatibility for model training.

**2. Model Architecture:**
- Developed a robust CNN architecture, integrating convolutional layers, activation functions, max-pooling, and dropout layers for effective gesture recognition.

**3. Data Splitting and Training:**
- Split the dataset into training and testing sets, facilitating rigorous model training on diverse hand gestures.

**4. Model Evaluation:**
- Achieved an exceptional accuracy of 99.97% on the test dataset, ensuring precise recognition of various hand gestures.

**5. Visualization and Interpretation:**
- Visualized sample hand gestures, enhancing model interpretation and providing valuable diagnostic insights.

**Project Outcome**
- **Test Accuracy:** 99.97%
- **Key Achievements:** Implemented a high-performing CNN model, demonstrating near-perfect accuracy in recognizing diverse hand gestures.

**Technologies Used**
- **Python:** Programming language for data processing and model development.
- **Keras and TensorFlow:** Deep learning frameworks for building and training neural networks.
- **NumPy:** Library for numerical computations and array operations.
- **OpenCV:** Image handling library for preprocessing and visualization.
- **Matplotlib and Seaborn:** Libraries for data visualization.


This project showcases the successful fusion of advanced technologies and meticulous dataset organization, ensuring a robust foundation for gesture-based human-computer interaction systems. For a detailed exploration of the dataset and its creation, refer to the provided research paper citation. Explore the code and delve into the future of seamless gesture recognition interfaces.
