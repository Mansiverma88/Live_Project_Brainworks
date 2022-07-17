#Storage Implication
> Created simple workpage with two sections: Save and fetch data using HTML, CSS, JS and Google Sheet API SheetDB.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Project Status](#project-status)


## General Information
- This project showcases my skills on HTML CSS, JS and 
- A simple webpage is created, which has been divided into two section:
- Save- Created two text input fields in it: Firstname and Lastname, and a Save button
- Fetch-Created one text input field in it: Firstname, and a Fetch button
- When the user clicks on the Save button in the Save section, the data entered by the user gets saved in a Google Sheet using the url link genrated by API SheetDB by POST method 
- When the user enters a Firstname in the Fetch section, code fetches the corresponding Lastname from the same Google Sheet. The fetched Lastname is printed on the webpage using GET method.
- This simple code, can help us to find a particular information from a large amount of data in google sheets. Further since data is being stored in Google sheet, internal storage of the device is free.


## Technologies Used
- VS Code - version 1.69


## Features
List the ready features here:
- POST first name and last name entered in google sheet, when Save button is clicked
- GET the first name and last name of all enteries matching the name entered in Fetch.
- SheetDB API converts the data stored in Excel sheet, format-  to JSON format and returns the data as a response to HTTP get method. Now this JSON data is searched on basis of matching {{first name}} column.


## Project Status
Project is:  _complete_


