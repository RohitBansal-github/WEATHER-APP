# ☁️Weather App

This project is a simple weather application that allows users to view weather information for their current location or search for weather information for a specific city.  It features a user-friendly interface with tabs for accessing user location weather and searching for city weather.

## Features

| Feature             | Frontend Technologies | Backend Technologies | Frontend Setup Steps                               | Backend Setup Steps                                      |
|----------------------|-----------------------|-----------------------|----------------------------------------------------|----------------------------------------------------------|
| Get Current Location Weather | HTML, CSS, JavaScript | None (Uses OpenWeatherMap API) | 1. Clone the repository.<br>2. Open `index.html` in a browser. | None (Client-side only application)                      |
| Search City Weather   | HTML, CSS, JavaScript | None (Uses OpenWeatherMap API) | 1. Clone the repository.<br>2. Open `index.html` in a browser. | None (Client-side only application)                      |


## Project Structure

```
weather-app/
├── index.html      // Main HTML file
├── index.js        // JavaScript logic
├── style.css       // CSS styling
└── images/          // Folder containing image assets (gif.webp, placeholder.png, icons8-search-30.png, etc.)
```

## Setup

This project is a client-side application using the OpenWeatherMap API. No backend setup is required.


### Frontend Setup:

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   ```
2. **Open `index.html`:** Open the `index.html` file in your web browser.


## How to Use

1. **Get your current location's weather:** Click the "Your Weather" tab.  The application will prompt you to grant location access.  Once granted, your current location's weather information will be displayed.

2. **Search for a city's weather:** Click the "Search Weather" tab. Enter the name of the city in the search bar and click the search button. The weather information for that city will be displayed.

## Examples

* **UI Interaction:**  Clicking the tabs switches between the "Your Weather" and "Search Weather" views.  Entering a city name and submitting the form fetches the weather data for that city.

## API Documentation

This application uses the OpenWeatherMap API.  Refer to their documentation for details: [https://openweathermap.org/current](https://openweathermap.org/current)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

MIT License

## Contact

For any questions or issues, please contact the repository owner.
