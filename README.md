🚦 Traffic Sign Detection using HOG, SVM, and KNN

This project focuses on detecting and classifying traffic signs using classical computer vision and machine learning techniques. Instead of relying on deep learning, we implement a lightweight yet effective pipeline that can run on low-resource devices.

<img width="723" height="613" alt="image" src="https://github.com/user-attachments/assets/e9685194-1635-4b27-ac14-eabb7febba2b" />

🔑 Key Components

HOG (Histogram of Oriented Gradients): Feature extraction method to capture shape and edge information of traffic signs.

SVM (Support Vector Machine): Supervised learning model used for robust classification with a clear decision boundary.

KNN (K-Nearest Neighbors): Complementary classifier for benchmarking and comparison, based on similarity in feature space.

⚙️ Workflow

Preprocessing – Convert images to grayscale, normalize, and resize.

Feature Extraction (HOG) – Extract gradient-based descriptors from traffic sign images.

Model Training – Train classifiers (SVM and KNN) on labeled HOG features.

Evaluation – Compare performance metrics (accuracy, precision, recall) between SVM and KNN.

Detection & Recognition – Apply trained models to detect and classify signs in test images.

🎯 Applications

Driver assistance systems (ADAS).

Autonomous vehicles.

Intelligent traffic monitoring.

<img width="885" height="620" alt="image" src="https://github.com/user-attachments/assets/fb96e9da-8be1-4cb3-bd0e-34023167f797" />
