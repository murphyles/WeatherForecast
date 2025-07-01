# WeatherForecast
# Weather Forecast App  

A simple web application for checking current weather conditions with city search or device geolocation functionality.  

## Features  

- **City Search**: Enter a city name to get weather data  
- **Geolocation**: Get weather for your current location  
- **Weather Display**: Shows current temperature, weather condition with an icon  
- **Detailed Metrics**: Displays feels-like temperature, humidity, and wind speed  
- **Animations**: Smooth gradient background animation  

## Technologies Used  

- **HTML5**  
- **CSS3** (Animations, Flexbox, Grid)  
- **JavaScript** (Basic event handling)  
- **Future Plans**:  
  - API integration (OpenWeatherMap or similar)  
  - React.js migration  

## File Structure  

```
/
├── WeatherForecast.html       - Main page with search form  
├── WeatherForecast.css        - Styles for main page  
├── WeatherForecast2.html      - Weather display page  
├── WeatherForecast2.css       - Styles for weather page  
├── images/                   - Icons & assets  
│   ├── favicon.ico  
│   ├── favicon-32x32.png  
│   ├── weather-icon.svg  
│   ├── placeholder.png  
│   ├── thermometer.png  
│   ├── humidity copy.png  
│   ├── 315686_wind_icon.png  
│   └── Screenshot 2025-01-03 at 20.35.42.png (back button)  
└── (Future: React components and API service files)
```

## Current JavaScript Implementation  

- Form submission handling  
- Basic navigation between pages  
- Event listeners for:  
  - Enter key press in search field  
  - Button clicks  
  - Back navigation  

## Installation & Usage  

1. Clone the repository or download project files  
2. Open `WeatherForecast.html` in any modern browser  
3. Either:  
   - Enter a city name and press Enter  
   - Or click "Get device location"  

## Design Features  

- Responsive layout  
- Smooth gradient animations  
- Intuitive UI  
- Dark/light mode friendly  

## Roadmap  

### Short-term  
- [ ] Integrate real weather API  
- [ ] Add loading states  
- [ ] Improve error handling  

### Medium-term  
- [ ] Convert to React application  
- [ ] Add multi-day forecast  
- [ ] Implement search history  

### Long-term  
- [ ] Unit preference system (C/F, km/h/mph)  
- [ ] Time-based theme switching  
- [ ] PWA implementation  

## Author  

murphyles (JIEC)