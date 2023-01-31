# aqitracker
Air Quality Index Tracker

## Live Site link:https://nitin931.github.io/airpollution.github.io/

## Hoe to use the code:
Code is done in 3 languages. HTML for front-end, CSS for styling and JavaScript for API calling and back-end. File index.html contains all the front-end code. File style.css contains the styling code. File script.js contains the JavaScript code for back-end. API and all necessary information required to display the Air Quality Index is carried through OpenWeatherMap API. If you want to contrinute towards the project, kindly fork the repo and then contribute in the main branch. 

## Inspiration:
Today (05-06-2021) is World Environment Day. I hail from India and my country suffers heavily from Atmospheric Pollution. Air Quality Index of various Indian Cities falls in "Very Poor" category. Many people here suffer from respiratory diseases. Thus, I decided to develop an "Air Quality Index Tracker" which helps user to find the Air Quality at his/her location and take preventive measures accordingly so that precious lives can be saved.

## What it does:
This web-application takes input of geographical location from user (it can be done automatically as well as manually). Then by the help of API, the Air Quality Index of that location is provided to the user along with the exact concentration of various Air Pollutants like Carbon Monoxide, Nitrogen Monoxide, Nitrogen Dioxide, Ozone, Sulphur Dioxide, etc. Later, a user can study detailed prevention measures from the links provided in the web-application to improve Air Quality Index.

![Screenshot (90)](https://user-images.githubusercontent.com/55184719/215907505-74368865-22fc-43cf-8bb5-894c3dfa8cb9.png)
Allow access to get the exact coordinates of your location
![Screenshot (91)](https://user-images.githubusercontent.com/55184719/215907512-5d726b7d-0eb6-4a32-90be-d86cdce658c4.png)
Click Search and scroll down to see the results
![Screenshot (92)](https://user-images.githubusercontent.com/55184719/215907514-b88b35b9-2524-464d-85e7-3b20a472ef30.png)
You can see the Air quality status of your current location  all with all pollutants concentration
![Screenshot (93)](https://user-images.githubusercontent.com/55184719/215907516-f37ab5dc-73d7-46eb-9050-333cbaca50ca.png)
some articles and blogs to refer

## How I built it:
I built the front-end of the application using HTML and styled it using CSS. I used openweathermap API to display Air Quality Index data based upon latitudinal and longitudinal positions as inputted by the user. 

## Challenges we ran into:
Major challenge was accuracy with respect to real-time data of Air Quality Index. The API provides Air Quality Index data correctly up to 95%  accuracy. Later on, I tried applying Machine Learning Algorithm using R programming but it showed lesser accuracy than API result and hence I took API value as the final result.

## Accomplishments that I am proud of:
This application is able to show the Air Quality Index accurately thus providing user true information regarding Air Quality Index which can guide them to take needed measures to control the Air Quality Index and decrease the risk of respiratory disease and keep our environment clean and green.

## What I learned:
I learned correct application of APIs to display the Air Quality Index results. Also, while studying different research papers on Air Quality Index, I learned how important it is to keep our environment clean and green.

## What's next for Air Quality Tracker:
In coming days, I will add few new features like AI based medical support for those people who are suffering from respiratory diseases as well as I plan to add a real time 3D earth map to display the Air Quality Index information on dashboard. 
