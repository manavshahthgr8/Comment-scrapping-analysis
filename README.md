About project & how to run?

Project Comment-scrapping-anaysis for youtube 
-> When user enter's youtube url, it automatically opens it on automated browser and fetch the comments to wordcloud, after that it sorts comment into positive , negative and neutral based on some words.

Technology used:-> Selenium{for browser automation}, python{with various libraries like flask,numpy , nltk etc}

![Screenshot (326)](https://user-images.githubusercontent.com/70972976/233432154-a596b4d2-babd-4d66-9557-ef1c0ac54b08.png)

Note : 

Step 1-To run the code with help of pip install all the libraries used 

(re,os,nltk,joblib,requests,numpy,bs4,flask,wordcloud (supports till python3.7*))

Step 2-Run the following command before the first run:

       pip install selenium
       
       pip install wordcloud nltk selenium
       
Step 3-In code (app.py) before running first time

      uncomment the line (4,19,20) 

You can run your code now (or command flask run) and it will be hosted on local server:)

![Screenshot (327)](https://user-images.githubusercontent.com/70972976/233434966-2856f0fd-5f71-4590-a9f4-420f8e308d7e.png)
