## MyWeatherApp
MyWeatherApp is an interactive weather application developed using Python and Gradio. The app allows users to fetch a 7-day weather forecast for any city worldwide, perform CRUD operations on saved locations, and learn about the Product Manager Accelerator (PMA) program.

The app is fully deployed on Hugging Face Spaces and can be accessed here: https://huggingface.co/spaces/siri89/myweatherapp

## Features
7-Day Weather Forecast Enter any city, ZIP code, or landmark to get the weather forecast Displays min and max temperatures and weather conditions using emojis Download the forecast as a CSV file

## CRUD for Saved Locations
Create: Add a city to the saved locations list Read: View all saved locations Update: Replace an existing location with a new city Delete: Remove a location from the list

## PMA Info Section
Click the PMA Info button to learn about the Product Manager Accelerator program Information is displayed immediately below the button

Beautiful and Interactive UI Gradient headers and buttons Rounded boxes for sections Colorful, user-friendly interface

## CSV Export
Download a CSV of the 7-day forecast for any location

## Tech Stack

Python 3.8+ Gradio for building the interactive web interface Pandas for data handling and CSV export Requests for API calls (Open-Meteo and OpenStreetMap) Open-Meteo API for weather forecast data OpenStreetMap API (Nominatim) for geocoding cities Hugging Face Spaces for deployment

## Usage Instructions
PMA Info Click the PMA Info button to display information about the Product Manager Accelerator program

## Check Weather
Enter a city, ZIP code, or landmark in the Location textbox Click the Check Weather button The Weather Summary box displays a 7-day forecast A CSV download button appears below the summary for exporting data

## CRUD Operations
Add Location: Enter a city and click Add Location Update Location: Enter old city and new city, then click Update Location Delete Location: Enter a city and click Delete Location List Locations: Click List Locations to view all saved cities

## Requirements
gradio==3.44.0 pandas==2.1.0 requests==2.31.0

Install dependencies with:

pip install -r requirements.txt

## Deployment
The app is deployed on Hugging Face Spaces: https://huggingface.co/spaces/siri89/myweatherapp

Users can run the app online without installing Python Hugging Face handles hosting and provides a publicly accessible link

## UI Layout
Header and PMA Info: Gradient header with info button and description box Location and Weather: Location input, Check Weather button, 7-day forecast summary, CSV download CRUD Section: Add, Update, Delete, and List buttons with saved locations

## License
This project is open source and free to use under the MIT License

## Notes
Developed entirely in Python with Gradio for the UI Supports both local execution and online deployment via Hugging Face Spaces
