# Movie-and-Music-recommender-using-face-emotion-detection
##Inspiration 

In todays world where everyone have mood swings and at a particular they want things according to their mood . So this models is designed to assist them.


##What it does


It will detect the facial emotion of the person and then ask them to whether they want to hear song or watch movie according to their mood .
1.It will recognize facial expression based on seven categories 
2. Based on these emotions it will recommend movie or song .
3. When user clicks on movie it will take them to its imdb page and for song to the spotify website.


##How to build
Python is the programming language used to create the emotion recognition model and deploy it on the web application using flask. CV2, TensorFlow, NumPy, matplotlib, and other libraries are also utilized. The model is build using the transfer learning 
approach for which MobileNet model is used. The FER-2013 dataset, which comprises around 35000 photos, was utilized for model training and validation. This model is deployed on a website created with HTML and CSS using the flask framework. Based on the seven emotions, a new dataset of movies and music was constructed. 
The data from movies and songs was utilized to create the various templates that correlate to various emotions. 
