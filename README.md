# Crop_Recommandation_System
Completed Repositiory of My DBMS Project Crop Recommender System and all its Machine Learning Components.

DESCRIPTION:
  The Web Application asks a User to register to use our application . After signing up the user may enter details about his land and its nutritional value in form of (N,P,K) and his respective budget and the deep learning algorithms take over to suggest the best crop to be sown considering the Nutrient Data , Weather Data and Budget of the user. The application then generates a PDF Report containing the results of the Search an top 3 recommendations of the crop and where to procure crop seeds and machinary in his vicinity.

Server Folder Contains the Flask Application , HTML ,CSS Files of websites , thier corresponding static files and a sqlite database which is our primary database.

Ml Folder Contains THe Weather Detection and Nutrient based Detection Models, Data Pre Processing Code , Data Scraped From Internet.
          - Nutrient model is a classification model which outputs suitable crop to be sown using soil data.
          - Weather Model is a RNN model which was trined on previous weather information of 5 cities scraped from an API.
          
