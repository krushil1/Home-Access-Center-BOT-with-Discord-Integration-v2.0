# Home Access Center BOT v2.0

### A big thanks to https://github.com/Hedgy134117/ for helping me out and making this possible!

#### This is basically the same version of v1.0, except with new terminal output with colors and fixed minor errors!

## Installation
* Install Python3
* Have Chrome, before installing the ChromeWebDriver, check your current Chrome browser's version number and then proceed to download the ChromeWebDriver with the matching version number to your Chrome brower from https://chromedriver.chromium.org/downloads 
* store the chromedriver.exe file in a folder that you won't delete from and make remember where you save it.
* run the command pip install -r requirements.txt

## Setup
* enter your username and password in the credentials.py file
* create a discord server dedicated for your grades to be dumped into
* create a new webhook inside your discord server and copy it's URL
* paste the webhook URL inside the webhook variable in the main.py file. It will the end of the code, read the comments for more help!!
* paste the location of the chromedriver.exe file in the main.py file, read the comments for more help!!

## Running the python script
* Simply open up your terminal if you are on mac or command prompt if you are on windows
* Switch to the directory where the python script is with the cd command
* To run the program now, simply type python3 main.py
* And now it should start the process of fetching your grades and dumping them to your discord, it might take up to a minute

## Running it automatically
* if you plan on running this bot automatically on Windows, use Task Scheduler. Its an pre-installed application to automatically run scripts like python
* if you plan on running this bot automatically on MacOS, use Automator. Its an pre-installed application to automatically run scripts like python

## Adding more classes
* read the comments in the end of the code in main.py to add more classes!

## You're all set and ready to run your bot! Feel free to open up a issue if something goes wrong or doesn't work, I will troubleshoot your issue!! 
