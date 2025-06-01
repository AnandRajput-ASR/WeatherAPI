# Angular Weather App

A simple Angular application to fetch and display current weather data for any city using the OpenWeatherMap API.

---

## Features

- Search weather by city name
- Displays temperature, humidity, wind speed, and weather description
- Responsive and clean UI

---

## Demo

This app runs locally at:  
`http://localhost:4200`

---

## Getting Started

### Prerequisites

- Node.js and npm installed
- Angular CLI installed globally (`npm install -g @angular/cli`)
- OpenWeatherMap API key (free signup at [openweathermap.org](https://openweathermap.org/api))

## Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/AnandRajput-ASR/WeatherAPI.git
   cd weatherApp
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Add your OpenWeatherMap API key:**

   Open both of the following files and replace `'YOUR_API_KEY_HERE'` with your actual API key:

   - `src/environments/environment.ts`
   - `src/environments/environment.prod.ts`

   Example:

   ```ts
   export const environment = {
     production: false,
     weatherApiKey: 'YOUR_API_KEY_HERE'
   };
   ```

4. **Run the app:**

   ```bash
   ng serve
   ```

5. **Open your browser at:**

   ```
   http://localhost:4200
   ```

---

## Usage

- Enter a city name in the input box
- Press "Get Weather" button or hit Enter
- View current temperature, humidity, wind speed, and weather description

---

## Technologies Used

- Angular 15+
- OpenWeatherMap API
- TypeScript, SCSS
- Angular Environment Files
