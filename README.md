# Data science portfolio by Luke Monington

This portfolio is a compilation of AI notebooks which I wrote in order to explore machine learning and deep learning.

### Temperature Regulator - Reinforcement Learning [Github](https://github.com/lukemonington/shower_temp_reinforcement_learning)
In my current apartment, the shower temperature fluctuates frequently, especially 
if someone flushes the toilet. In this project, I simulated the fluctuating shower environment and 
built a reinforcement learning model with TensorFlow in order to keep the temperature within 
the desired range. To do this, I built a Sequential Neural Network and used a DQNAgent with a BoltzmannQPolicy. 


### Landscape Recognition - CNN / Transfer Learning [Github](https://github.com/lukemonington/landscape_classification)
Image recognition using deep learning is a driving force behind many of today's AI advancements. The purpose 
of this project is to use deep learning in order to train a neural network to classify different types of 
landscape within images. The categories are: buildings, forest, glacier, mountain, sea, and street. 
I first did this by building my own Convolutional Neural Network using MaxPooling2D and Dropout. 
Then, I used transfer learning with the ResNet50V2 architecture to improve on those results.


### Yelp Reviews - NLP Binary Classifier [Github](https://github.com/lukemonington/yelp_reviews)
In this project, I worked with the Yelp Reviews dataset, which contains over 7 million reviews. The purpose of this project 
is to use NLP to classify these Yelp reviews into positive reviews (4-5 stars) and negative reviews (1-2 stars). To do this, 
I experimented with a Conv1D NN Architecture and a Bidirectional LSTM NN Architecture. In the end, I found that the Conv1D 
NN Architecture achieved nearly the same results, but with a drastically lower training time.


### Pokemon Images - Autoencoder / GAN [Github](https://github.com/lukemonington/pokemon_images_gan)
An autoencoder is a type of NN which is used to learn efficient representations for a set of data by ignoring the noise.
The purpose of this project was to train an autoencoder to remove gaussian noise from pokemon images. From there, I
attempted to build a GAN to generate new pokemon images.


### Facial Recognition - VGGFace / OpenCV [Github](https://github.com/lukemonington/facial_recognition_opencv)
OpenCV is a library of programming functions mainly aimed at real-time computer vision. One of its uses is for facial recognition.
In this project, I use OpenCV to detect faces and eyes in images using OpenCV's Haar feature-based cascade classifier. This classifier 
also returns the location, height, and width of the face. I use that information in order to crop out the face from images and videos.
From there, I use the VGGFace pretrained Neural Network to do One Shot Learning and perform real-time facial recognition with my webcam.

### Facial Expression Recognition - OpenCV / CNN [Github](https://github.com/lukemonington/facial_emotion_recognition) | [Video Presentation](https://youtu.be/YucL6Jk8RMY)
For this project, I used OpenCV's Haar classifier to identify a face, which I then fed into a deep CNN to identify the facial expression.
I classified three different expressions: happy, sad, and neutral. Then, I identified one way that this technology could potentially be used
to help a client with their business problem. A 15 minute presentation of this project can be found at the link.

### Financial Statement XBRL Tag Classifier - NLP Binary Classifier [Github](https://github.com/lukemonington/financial-statement-classifier) | [Writeup](https://github.com/lukemonington/financial-statement-classifier/blob/main/Write%20Up%20on%20My%20Approach.docx)
Financial statements are treated very differently depending on whether they are classified as Industrial or Financial and they can be classified based on their usage of XBRL concepts in SEC 10-K/10-Q filings. In this project, I attempt to classify the financial statements first with a tokenizer and a machine learning algorithm to achieve 98% accuracy. Then, I build a neural network and am able to achieve 100% accuracy. After this, I investigate another method of feature engineering where I use a count vectorization instead of a tokenizer and am able to achieve 100% accuracy with just a Naive Bayes model.

### IMDB - EDA [Github](https://github.com/lukemonington/imdb-eda) | [PowerPoint](https://github.com/lukemonington/imdb-eda/blob/main/Analysis%20of%20Movie%20Data.pptx)
In this scenario, I am a data scientist for a top movie studio. After a series of box office flops, the producers at my studio are starting to question their strategy and need some direction. The producers are asking that I spend some time analyzing the data and present a report detailing my findings along with recommendations on how to revamp the studio's strategy. In this project, I challenged myself to perform EDA to find useful information in only 4 hours. I wanted to demonstrate my ability to quickly and efficiently find patterns and trends in the data.


### Categorical Feature Encoding Challenge - Machine Learning [Github](https://github.com/lukemonington/Categorical-Feature-Encoding-Challenge)
In this project, I experimented with different types of categorical features, sampling methods, and predictive algorithms in order to 
implement machine learning. This required different methods of feature engineering in order to work with the dataset, which consisted of 
5 binary columns, 10 nominal columns, and 6 ordinal columns. 


### Household Electric Power Consumption - Neural Networks [Github](https://github.com/lukemonington/household_electric_power_consumption)
One promising use of neural networks is for time series forecasting. Here, I work with forecasting electric power consumption in
a single household, when given 4 years of data with a one-minute sampling rate. First, I try predicting a single time step into the future.
I build and compare models such as linear models, Neural Networks, CNNs, and LSTM Neural Networks. Then, I build and compare models that predict
24 time steps into the future.


### Hourly Staff Planning - Genetic Algorithms [Github](https://github.com/lukemonington/genetic_algorithm)
Staff planning is a topic of optimization research that comes back in many companies. As soon as a company has many employees, it becomes 
hard to find planning that suits the business needs while respecting certain constraints. In this project, I implement genetic 
algorithms to find an optimal hourly staff planning solution.


### Don't Overfit AI Challenge - Machine Learning [Github](https://github.com/lukemonington/Don-t-Overfit-AI-Challenge)
In this project, I was challenged to not overfit to a dataset with only 300 features and 250 observations ot training data, while
predicting 19,750 rows of test data. The dataset was unbalanced, with almost twice as many positive examples as negative examples,
so I applied Synthetic Minority Over-sampling (SMOTE) to make the dataset more balanced. Then I compared the performance of different
classifiers such as RandomForestClassifier, SVC, and KNeighborsClassifier.


### Car Rental Company Relational Database [Github](https://github.com/lukemonington/Car-Rental-Company-Relational-Database)
The challenge was to develop a relational database using Oracle SQL Developer for a hypothetical car rental business with several addresses. 
The business rents multiple different types of cars, which each have their own respective rental prices. The rental pricing is also dependent 
upon available promotions. Additionally, the business keeps track of all of its customers and employees. It is also possible to be both an 
employee and a customer at the same time.

