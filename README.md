# API Automation test

#### Install libraries
npm install -g newman,
npm install -g newman-reporter-htmlextra

#### Execute tests
newman api/Directions.postman_collection.json -e api/mapbox.postman_environment.json -r htmlextra

#### Report
![Image](https://raw.githubusercontent.com/Nish2211/first/main/screencapture-file-D-DirectionsAPI-newman-report-html-2022-11-13-17_17_51.png)
