# 🎋 Wheat Disease Detection Using Transfer Learning

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction
Products from __wheat__ are available almost everywhere. Looking at various products such as __bread__ and other food items, we see that most of them are made with some component of wheat. Therefore, we could see how __ubiquitous__ the presence of wheat is in our nutrition. 

<img src = "https://github.com/suhasmaddali/Images/blob/main/hello-i-m-nik-AC_mtXehWzo-unsplash.jpg" width = "450" height = "350" /> <img src = "https://github.com/suhasmaddali/Images/blob/main/ales-krivec-QnNqGoCnBg0-unsplash.jpg" width = "450" height = "350"/>

## Challenges
When producing wheat, however, there might be various diseases attached to them. There could be diseases such as [Stripe Rust](https://smallgrains.wsu.edu/disease-resources/foliar-fungal-diseases/stripe-rust/) that affects the growth of wheat. As a result, the produce for that particular field is reduced to a large extent. 

__Identifying__ and __combating__ this task seems to be the primary challenge for farmers. This is because they would have to manually look at all the crops and carefully analyze their health before taking steps to prevent them. As it is manually time consuming to gauze the health of wheat as there are lots of them available in fields, it would be good to use artificial intelligence and deep learning to combat this problem. 

## Computer Vision 
With an improvement in technology and computational resources, it has become easier to train and deploy deep learning models, specifically for tasks such as [computer vision](https://www.ibm.com/topics/computer-vision). Therefore, we could leverage this technology to identify various diseases associated with wheat without manually having to identify them. As a result, this would save a lot of time and effort on the part of the farmers and research scientists in the field of agriculture respectively. 



## Outcomes
* The __computer vision__ model that was performing the best in classifying the diseases in wheat plants is __VGG19__. 
* The accuracy for classifying the diseases in wheat plants was __95%__ on the test data (data that the model has not seen before). 
* Furthermore, __VGG19__ was also being deployed in real-time where users can get to upload their own images of wheat and get to know if the wheat plant in the images is healthy or has diseases. 

## Future Scope
* More high precision images from wheat plants could be collected and analyzed under different __climatic__ and __lighting__ conditions.
* It could be integrated with a __camera__ where it is able to provide regular updates about the condition of wheat plants. 


In the ipython notebook, the images of wheat are taken and trained before giving them to the computer vision models for prediction of different kinds of diseases. Feel free to take a look. Thanks.

## 💻 Training with NVIDIA's RTX 2080 GPU

* GPU-accelerated deep learning frameworks offer flexibility to design and train __deep neural networks__.
* With cuDNN and Nvidia's graphics drivers, I was able to train the models really quickly by using GPU cores rather than the CPU cores.
* This led to a significant increase in the speed of training and developing __convolutional neural networks (CNNs)__. 


## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git which could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in the "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link to the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(18).png" width = "600" />

5. The link to the repository can be found when you click on "Code" (Green button) and then, there would be an HTML link just below. Therefore, the command to download a particular repository should be "Git clone HTML" where the HTML is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(20).png" width = "600" />

8. Later, open the Jupyter notebook by writing "Jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 

