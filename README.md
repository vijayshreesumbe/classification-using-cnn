# classification-using-cnn
Project: Cat-Dog Classification using CNN
Overview:
Developed a binary image classification model to differentiate between cats and dogs using Convolutional Neural Networks (CNN). Gained hands-on experience with TensorFlow/Keras frameworks and essential ML concepts, including data preprocessing, model building, and evaluation.

Skills and Achievements Gained
Data Handling & Preprocessing:

Handled datasets with 2000 training images and 1000 validation images from two categories (cats, dogs).
Utilized ImageDataGenerator to rescale images and efficiently generate batches during training and validation.
CNN Model Development:

Built a CNN model with Conv2D, MaxPooling, Flatten, and Dense layers to extract features and perform binary classification.
Compiled the model using Adam optimizer and binary cross-entropy loss.
Model Training & Evaluation:

Trained the model for 5 epochs with batch size 128.
Monitored metrics like accuracy and loss to track the model's performance over training and validation datasets.
Best Validation Accuracy: 54.69%
Model Saving & Deployment:

Saved the trained model in HDF5 format (model.h5) and converted it to TensorFlow GraphDef and XML for compatibility with other systems.
Visualization:

Visualized the model’s learning process by plotting training vs. validation accuracy and loss curves using Matplotlib.
Experience with TensorFlow APIs:

Gained familiarity with TensorFlow’s model conversion utilities, such as convert_variables_to_constants_v2.
Worked with graph definitions and understood compatibility issues between TensorFlow versions.
Model Debugging & Iteration:

Identified and analyzed discrepancies between training and validation accuracy to improve future models.
Learned to use random sampling and data augmentation techniques to enhance the model’s robustness.
Tools & Technologies Used:
Programming Language: Python
Frameworks & Libraries: TensorFlow, Keras, NumPy, Matplotlib
Data Handling: ImageDataGenerator for batch processing
Model Storage Formats: HDF5, GraphDef, XML
Impact:
Though the model’s initial accuracy was around 54.69%, this project provided crucial experience in working with convolutional neural networks, image classification, and TensorFlow tools. It enabled the understanding of model training dynamics and deployment techniques, laying a foundation for more advanced ML projects.

