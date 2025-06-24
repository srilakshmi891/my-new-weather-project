# 🌤️ Weather Website

A modern, responsive weather application that provides real-time weather information, forecasts, and beautiful weather visualizations.

## ✨ Features

### 🌡️ Current Weather
- **Real-time temperature** display in Celsius/Fahrenheit
- **Weather conditions** with descriptive icons
- **Humidity, wind speed, and pressure** information
- **Feels like temperature** calculation
- **UV index** and visibility data

### 📅 Weather Forecast
- **5-day forecast** with daily predictions
- **Hourly forecasts** for detailed planning
- **Temperature ranges** (high/low)
- **Precipitation probability**
- **Weather condition icons** for each period

### 🔍 Location Features
- **City search** with autocomplete
- **Geolocation** support for current location
- **Recent searches** history
- **Favorite locations** bookmarking

### 🎨 User Interface
- **Responsive design** for all devices
- **Dark/Light theme** toggle
- **Animated weather icons**
- **Smooth transitions** and hover effects
- **Modern card-based layout**

### 📱 Mobile Optimized
- **Touch-friendly** interface
- **Progressive Web App** features
- **Offline capability** with cached data
- **Mobile-first** responsive design

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Dynamic functionality and API integration
- **Weather API** - OpenWeatherMap for real-time data
- **Geolocation API** - Browser location services
- **Local Storage** - Data persistence and caching

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls
- Optional: OpenWeatherMap API key for extended features

### Installation

1. **Clone or download** the project files
   ```bash
   git clone https://github.com/yourusername/weather-website.git
   cd weather-website
   ```

2. **Open the application**
   - Double-click `weather-website.html` or
   - Open with your preferred web browser
   - Or serve using a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - Navigate to `http://localhost:8000` (if using local server)
   - Or simply open the HTML file directly in your browser

### API Setup (Optional)

For enhanced features, you can add your own OpenWeatherMap API key:

1. **Get API Key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate an API key

2. **Configure API**
   - Open `weather-website.html`
   - Find the API configuration section
   - Replace `YOUR_API_KEY` with your actual API key

## 📁 Project Structure

```
weather-website/
├── weather-website.html    # Main application file
├── README.md              # Project documentation
├── assets/                # Optional: for additional resources
│   ├── images/           # Weather icons and backgrounds
│   ├── css/             # External stylesheets (if separated)
│   └── js/              # External JavaScript (if separated)
└── .gitignore           # Git ignore file
```

## 🎯 How to Use

### Basic Usage
1. **Allow location access** when prompted
2. **View current weather** for your location
3. **Search for other cities** using the search bar
4. **Toggle temperature units** (Celsius/Fahrenheit)
5. **Switch themes** (Dark/Light mode)

### Advanced Features
- **Add to favorites** by clicking the heart icon
- **View detailed forecasts** by clicking on forecast cards
- **Check hourly weather** for precise planning
- **Save preferences** automatically

## 🔧 Customization

### Adding New Features
- **Weather alerts** and notifications
- **Weather maps** integration
- **Historical weather data**
- **Weather widgets** for embedding
- **Multi-language support**

### Styling Customization
- **Color schemes** in CSS variables
- **Weather icons** replacement
- **Layout modifications** for different screen sizes
- **Animation effects** enhancement

### API Integration
- **Multiple weather APIs** support
- **Custom API endpoints**
- **Data caching** strategies
- **Error handling** improvements

## 📊 API Endpoints Used

The application uses the following OpenWeatherMap API endpoints:

- **Current Weather**: `/weather`
- **5-Day Forecast**: `/forecast`
- **Geocoding**: `/geo/1.0/direct`
- **Reverse Geocoding**: `/geo/1.0/reverse`

## 🎨 Design Features

### Color Scheme
- **Primary**: Modern blue gradients
- **Accent**: Warm orange highlights
- **Background**: Clean white/dark themes
- **Text**: High contrast for readability

### Typography
- **Font Family**: System fonts for optimal performance
- **Font Sizes**: Responsive scaling
- **Font Weights**: Varied for hierarchy

### Animations
- **Smooth transitions** between states
- **Hover effects** on interactive elements
- **Loading animations** for API calls
- **Weather icon animations**

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## 🔒 Privacy & Security

- **No personal data** collection
- **Local storage** for preferences only
- **Secure API calls** via HTTPS
- **Location permission** required for geolocation

## 🐛 Troubleshooting

### Common Issues

1. **Weather data not loading**
   - Check internet connection
   - Verify API key (if using custom key)
   - Clear browser cache

2. **Location not working**
   - Allow location permissions
   - Check browser settings
   - Try manual city search

3. **Styling issues**
   - Clear browser cache
   - Check for CSS conflicts
   - Verify file integrity

### Performance Tips
- **Enable caching** for better performance
- **Use CDN** for external resources
- **Optimize images** for faster loading
- **Minimize API calls** with smart caching

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch
3. **Make** your changes
4. **Test** thoroughly
5. **Submit** a pull request

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Test on multiple browsers
- Ensure mobile responsiveness

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **OpenWeatherMap** for weather data API
- **Weather Icons** for beautiful weather representations
- **Community contributors** for feedback and improvements

## 📞 Support

If you need help or have questions:

- **Create an issue** on GitHub
- **Check documentation** for common solutions
- **Review troubleshooting** section above

## 🔄 Version History

### v1.0.0 (Current)
- Initial release
- Basic weather functionality
- Responsive design
- Search and geolocation features

### Planned Features
- Weather alerts
- Historical data
- Weather maps
- Multi-language support
- PWA enhancements

---

**Made with ❤️ for weather enthusiasts everywhere!**

*Last updated: December 2024*