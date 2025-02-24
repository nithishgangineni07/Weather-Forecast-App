# Weather-Forecast-App

The Weather Forecast Application is a web-based tool built with JavaScript, HTML, and Tailwind CSS. It fetches real-time weather data from an API, allowing users to search by city name or get weather updates for their current location. 

# Weather Forecast Application

## Overview
This is a weather forecast application built using JavaScript, HTML, and Tailwind CSS. It integrates with a weather API to provide users with location-based forecasts, current weather conditions, and extended forecasts.

## Features
- Search weather by city name
- Get weather for the current location
- Display temperature, humidity, and wind speed
- Show a 5-day weather forecast with icons
- Store and display recently searched cities
- Responsive design for desktop, iPad Mini, and iPhone SE
- User input validation and error handling

## Technologies Used
- JavaScript
- HTML
- Tailwind CSS
- Weather API 
- Local/Session Storage
- Git for version control

## Setup Instructions

### Prerequisites
- Node.js and npm (for Tailwind CSS installation)
- A weather API key (sign up on OpenWeather or another provider)
- Git installed on your machine

### Installation Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/weather-forecast-app.git
   cd weather-forecast-app
   ```
2. Install Tailwind CSS:
   ```sh
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```
3. Add your Weather API key in `script.js`:
   ```js
   const API_KEY = '17251aea81a87db5685b646487f5ef5a';
   ```
4. Open `index.html` in a browser or use Live Server for development.

## Usage
- Enter a city name and click 'Search' to get the weather.
- Click 'Current Location' to fetch the weather for your location.
- Click on a recently searched city from the dropdown to view its weather.
- View extended weather forecasts for five days.

## Error Handling
- Displays messages for invalid inputs or API errors.
- Handles cases where the city is not found.
- Prevents empty searches.

## Repository and Version Control
- The project is tracked using Git.
- Push changes to GitHub using:
   ```sh
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

## License
This project is open-source and available for modification and distribution.

