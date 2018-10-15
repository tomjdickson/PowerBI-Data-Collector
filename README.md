# PowerBI-Data-Collector
Collects data from PowerBI dashboard and outputs to CSV using NodeJS, FS and Puppeteer.
I am aware that there is a PowerBI API - This project was created to learn Puppeteer.

# Getting Started

## Installation
To run this script first ensure you have [NodeJS](https://github.com/nodejs/node) installed.

Next, clone or download the repository

``` git clone https://github.com/tomjdickson/PowerBI-Data-Collector.git ```

Finally navigate to the directory in-which you have downloaded and run


``` npm install ```

## Setup
To ensure you are authenticated with your instance of PowerBI and you are collecting the disired information you will need to fill out the "app.js" file located in the "Config" directory.
"App.js" Contains the following settings 
* username - Office 365 Email
* password - Office 365 Password
* dashboardURL - PowerBI Dashboard URL
* Selector - Selector in-which contains your information (Default is '.tileContain li'). This is the parent div element for all the data you are wanting to select.



# To-Do
There is still plenty of improvement able to be made here. I have listed what I think are the most important, please let me know if you would like extra features added.
* A more secure way of holding the password in the app.js file instead of plain text
* Option to select weather to pull from Dataset / Report / Dashboard in App.js

