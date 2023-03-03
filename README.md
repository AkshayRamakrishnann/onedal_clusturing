# Parkinson Syndrome Detection
![images-_7__1](https://user-images.githubusercontent.com/111365771/222625936-03a7c36b-f2fc-4595-bd99-42a0206cc12c.jpg)


# Introduction
Parkinson's disease is a neurodegenerative disorder that affects movement, causing tremors, rigidity, and difficulty with walking and coordination. Early detection of Parkinson's disease is crucial for effective treatment and management. Machine learning techniques have shown promise in accurately detecting Parkinson's disease from various medical data, including imaging, genetic, and clinical data.

# Methods
In this project, we used the oneDAL clustering method with a Lasso model to detect Parkinson's disease. The dataset used in this study consisted of clinical data from 195 patients, including 48 with Parkinson's disease and 147 without. The data was preprocessed, and features were selected using the Lasso regression method. The selected features were then used to cluster the data using the oneDAL clustering method. We evaluated the performance of the model using the accuracy metric.

![download](https://user-images.githubusercontent.com/111365771/222626165-1d331370-f9d2-4480-b142-c0e374002b8b.png)

# oneAPI
oneAPI is an open, cross-architecture programming model that enables developers to write applications that can run on a variety of hardware platforms, including CPUs, GPUs, and FPGAs. The goal of oneAPI is to provide a common interface that can be used across different hardware architectures, reducing the complexity of developing software for heterogeneous systems. With oneAPI, developers can write code in standard programming languages such as C++, DPC++, and Fortran, and then use oneAPI libraries to take advantage of hardware-specific optimizations.

# oneDAL
oneDAL (oneAPI Data Analytics Library) is one of the libraries included in the oneAPI toolkit. It is a high-performance library for data analytics and machine learning that provides a variety of algorithms and functions for tasks such as data preprocessing, feature selection, regression, classification, and clustering. oneDAL is designed to work with large datasets and can take advantage of hardware-specific optimizations to achieve high performance. It supports a wide range of data formats and can be used with a variety of programming languages, including C++, Python, and Java.


# Results
The accuracy of the model was 32.15%. Although this accuracy may not be considered high enough for practical use, it provides insights into the data structure and potential feature importance. Future studies may consider using other machine learning techniques and incorporating other types of data to improve the accuracy of Parkinson's disease detection.
