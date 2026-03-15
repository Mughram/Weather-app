# Weather App 🌤️

A simple weather app that shows real-time weather information for any city using the OpenWeatherMap API.

## Features

- Search weather by city name
- Displays temperature in °C
- Displays humidity percentage
- Displays weather description
- Weather emoji based on conditions

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Mughram/Weather-app.git
```

### 2. Get an API key
1. Go to [openweathermap.org](https://openweathermap.org)
2. Sign up for a free account
3. Go to API keys and copy your key

### 3. Set up your API key
1. Rename `config.example.js` to `config.js`
2. Open `config.js` and replace with your key:
```javascript
const apiKey = "your_api_key_here";
```

### 4. Run the app
Open `index.html` directly in your browser or use Live Server in VS Code.

## Project Structure

```
Weather-app/
├── index.html
├── style.css
├── index.js
├── config.example.js   ← rename to config.js and add your key
├── .gitignore
└── README.md
```

## Usage

1. Type a city name in the search box
2. Press **Enter** or click the search button
3. Weather info will appear on the card

## Weather Emojis

| Condition | Emoji |
|-----------|-------|
| Thunderstorm | ⛈️ |
| Drizzle | 🌧️ |
| Rain | 🌧️ |
| Snow | ❄️ |
| Fog/Mist | 🌫️ |
| Clear | ☀️ |
| Clouds | ☁️ |

## Note
> The API key is not included in this repo for security reasons. You must add your own key in `config.js`.
