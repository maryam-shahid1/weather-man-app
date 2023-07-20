WeatherMan App Readme

**Functionality:**

weatherman.py:__
WeatherReading: Data structure to hold each weather reading.__
ParsingData: Class for parsing the files and populating the WeatherReading data structure with  correct data types.__
Main: Responsible for calling apppropriate methods to generate the required report.__

calculations.py__
ReportCalculations: Class for computing month or year report calculations given the WeatherReadings data structure.__

report.py:__
Report: Class for creating the reports given the Results data structure.__
Results: Data structure for holding the calculations results.__


**Commands to run project:**

First, create a virtual environment and activate it using command:__
source virtual_env/bin/activate__

To get any year's report:__
python3 weatherman.py -e 2005__ 

To get any month's report:__
python3 weatherman.py -a 2006/4__

To get any month's report in the form of charts:__
python3 weatherman.py -c 2006/4__

To get multiple reports (any order can be followed):__
python3 weatherman.py -a year/month -e year -c year/month__

