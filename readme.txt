-The folder 'android' consists of the android build files, and the 'archive' folder consists of the datasets on which the model is built and the .pkl files of the serialized model itself.
-The scraper.ipynb consists of the code used to web-scrape the data from myanimelist.net for the advanced recommendations (art1.csv, soundtrack1.csv and so on). Running the scraper code is not recommended in this directory as it will overwrite the existing csv files.
-The code used to train the model was done on google colab. You can simply launch the model_train.url file to access the training code.

-The apk is included but to run the app one needs to setup the server from the server.ipynb notebook in this directory along with ngrok.exe and run the following commands:
'ngrok authtoken 245ySIebZyjtxGRMXKISriSKWyT_2inrQoCTbUfe1BYKpS8uX'
'ngrok.exe http 5000'

-After this, you need to copy the public IP address provided by ngrok and change the HTTP request URL variable in SearchRepository.java and RecommendRepository.java files to the IP Address of the server.

-If you require a demo MyAnimeList account use the following account:
Username: Demo_User
Password: demouser684

-Feel free to get in touch with me at rayan967@gmail.com in case you run into any issues.
