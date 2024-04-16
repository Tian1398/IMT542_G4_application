# IMT542_G4_application
Use SEC API to create a small application that automatedly download the relevant data in csv file as the user enters the company's stock symbol (ticker name).

This application includes 2 major parts:
1. fetch CIKs for companies
2. write a function to get company's asset data by ticker name

This application currently supports the deatures including
- allowing a user to input any compnay ticker name in either lower case or uppercase
- returning an error if the company asset data is not found
- downloading a csv file with revelent company aseet data for the user

Meanwhile, this application could be imrpoved by
- supporting multiple data formats such as csv/json/xml/etc
- allowing a user to input multiple company names and download data in one single file
