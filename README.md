### Face Recognition Project

This project explores three distinct paths for face recognition, employing various machine learning algorithms and data augmentation techniques.

#### Paths

1. **Path 1:**
   - Algorithms: SVM, KNN
   - Dataset Size: 274 (Raw Data)

2. **Path 2:**
   - Preprocessing: PCA (dimensionality reduction)
   - Algorithms: Decision Tree, Random Forest, KNN, Logistic Regression, SVM (RBF)
   - Data Augmentation: Flip, Rotate, Shrink/Enlarge, Brightness, Contrast, Saturation
   - Dataset Size: 7,085 (Combined)

3. **Path 3:**
   - Preprocessing: PCA with LDA (dimensionality reduction)
   - Algorithms: Decision Tree, Random Forest, KNN, Logistic Regression, SVM (RBF)
   - Data Augmentation: Flip, Rotate, Shrink/Enlarge, Brightness, Contrast, Saturation
   - Dataset Size: 17,639 (Combined)

<img width="281" alt="image" src="https://github.com/SuyashSalvi/Face-Recognition-App/assets/40499151/b4b1cbc4-43a1-489b-811e-5984cf99a7e5">


#### Data Augmentation Techniques

- Flip
- Rotate
- Shrink and Enlarge
- Brightness
- Contrast
- Saturation
<img width="801" alt="image" src="https://github.com/SuyashSalvi/Face-Recognition-App/assets/40499151/3274cc87-92b9-40a4-a551-fadfc89983e7">


#### Dataset Sizes

- Path 1: 274 (Raw Data)
- Path 2: 7,085
- Path 3: 17,639

#### Accuracy

**Path 1:**
- SVM (RBF): 53
- KNN: 47

**Path 2:**
- Decision Tree: 44
- KNN: 66
- Logistic Regression: 78
- Random Forest: 69
- SVM (RBF): 80

**Path 3:**
- KNN: 81
- SVM (RBF): 83

This project aims to compare the performance of different paths in face recognition and provides insights into the impact of preprocessing and algorithm selection on accuracy. Feel free to explore the code and results in detail.
