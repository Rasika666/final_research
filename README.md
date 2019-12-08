# Research-final

### The best satellite bands combimations for paddy crop classification and yield forecasting

# installation
---
1. install whl files located in config file(for windows)
2. install req.txt packages 
4. vs 2017
3. cuda v10.0
4. cuDnn v7.4.1
5.tensorflow-gpu v1.14



#importance url
---
* [Unofficial Windows Binaries for Python Extension Packages](https://www.lfd.uci.edu/~gohlke/pythonlibs/)

# folder structure
|- config  # some config files for windows to integrate with seninel-hub python
|- important doc # docs for project
|- logbooks # campuz logbooks
|- test # experiment folder
|- models # SVM, CNN models build here
|     |- b4b3b2-rgb # sat b4,b3,b2 bands images dataset 
|     |- b11b8b2-dataset # sat b11,b8,b2 bands images  dataset
|     |- b11b8b4-agriAnalysis # sat b11,b8,b4 bands images  dataset
|     |- cloud-classify # cloud detection dataset
|     |- cnn.ipynb
|     |- cnn-up.ipynb # final cnn model for paddy stage classification using b11,b8,b2 bands combination
|     |- data_augmentation.ipynb # images augmentation codes
|     |- SVM_classifer_cloud.ipynb
|     |- SVM_classifier_b4b3b2.ipynb
|     |- SVM_classifier_b11b8b2.ipynb
|     |- SVM_classifier_b11b8b4.ipynb
|
|
|
