# Interactive Map of Japanese Rope Art Locations in Italy
[Click to see the interactive map](https://www.andrearopes.com/ropes-around-italia/)

## Project Overview
This map was commissioned by a client who wanted to map all the places 
where Japanese rope art is practiced in Italy, to be embedded 
in their WordPress blog. 
The goal was to create an interactive, visually 
appealing, and easy-to-use map.

## Features
- **Interactive map** built with Folium (Python)
- **Custom markers** using the studio's personalized logo for each location
- **Pop-up windows** for each location, containing useful information and
  clickable Instagram contacts
- **Google Sheets as data source** — the client can easily update the data
  without any technical knowledge, simply by editing the spreadsheet
- **Embedded in WordPress** via iframe

## How It Works
The data source is a Google Sheet that the client fills in autonomously.
Once updated, running the Python script generates an .html file that can
be directly uploaded to WordPress.

## Designed for Sustainability
A key focus of this project was making it maintainable by a non-technical user.
After delivery, a step-by-step Word guide was provided to the client, covering:
- How to add or update locations in the Google Sheet
- How to run the script to regenerate the map
- How to upload the updated map to WordPress
- Future possible implementations, such as expanding the map to include
  locations across Europe

## Technologies Used
- Python
- Folium
- Google Sheets API
- HTML
