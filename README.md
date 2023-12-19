### ML-Principles-YummyDataset😋 Mini Project 

This repository represents my personal work on the 'Principles of Machine Learning' course's miniproject using the MLEnd yummy dataset. The Colab notebooks are divided into two distinct files: basic and advanced.

#### Basic assignment

The basic assignment focuses on constructing a machine learning model that distinguishes between rice and chips in input image files. The notebook encompasses diverse experiments on the dataset, various feature extraction methods, and classification models. I created three different training datasets: the original, a version with applied data augmentation, and another with food area cropping. Particularly noteworthy is my unique approach to feature extraction, which involves cropping the food area based on the bounding box around regions with high saturation. For image classification, I opted for several popular classification models, including Logistic Regression, Support Vector Machine, Naïve Bayes, an ensemble model, and CatboostClassifier.

#### Advanced assignment
The advanced assignment delves into the intriguing question: 'Does the appearance of food influence food preference?' Unlike the basic project, the output of the image classification here represents the preference scale for the food. Moreover, this advanced assignment distinguishes itself by emphasizing the application of multiple CNN models for image classification. Basic data augmentations are applied to the images during data loading. ResNet, VGG16, and GoogleNet models are employed with careful comparison between train and test losses.

Overall, both the basic and advanced assignments constitute fascinating projects that have aided me in developing a structured approach to machine learning experiments and analyzing their results.

### Q. What is MLEnd Yummy dataset? 

The Yummy dataset comprises food images collected by students, including myself, under the guidance of our amazing professor, Jesus Requena-Carrion, from Queen Mary University of London. It consists of a total of 3,250 images, accompanied by a metadata CSV file containing additional details such as food preferences and vegetarian categorization [(MLEnd dataset documentation)](https://mlend.readthedocs.io/en/latest/). This dataset holds significance as it represents raw images collected by students, serving as an excellent starting point for practicing image preprocessing and feature extraction.

🙌 Big thanks to Professor Jesus for giving us this chance to work hands-on from gathering data to building a machine learning system!



