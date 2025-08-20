<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Central - Your Complete Weather Dashboard</title>
     <link rel="stylesheet" href="styles2.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <div class="logo">
                <h1>🌤️ WeatherCentral</h1>
            </div>
            <!-- Navigation using Flexbox -->
            <nav class="nav">
                <ul class="nav-list">
                    <li><a href="#current">Current</a></li>
                    <li><a href="#forecast">Forecast</a></li>
                    <li><a href="#radar">Radar</a></li>
                    <li><a href="#alerts">Alerts</a></li>
                    <li><a href="#climate">Climate</a></li>
                </ul>
                <div class="mobile-menu-toggle">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </nav>
        </div>
    </header>

    <!-- Main Layout using CSS Grid -->
    <main class="main-layout">
        <!-- Hero Weather Section -->
        <section class="hero weather-hero" id="current">
            <div class="current-weather">
                <div class="weather-main">
                    <div class="temperature">
                        <span class="temp-value">24</span>
                        <span class="temp-unit">°C</span>
                    </div>
                    <div class="weather-info">
                        <h2>Partly Cloudy</h2>
                        <p class="location">📍 Nairobi, Kenya</p>
                        <p class="last-updated">Updated 5 minutes ago</p>
                    </div>
                </div>
                <div class="weather-icon">
                    <div class="animated-weather">
                        <div class="sun">☀️</div>
                        <div class="clouds">
                            <div class="cloud cloud-1">☁️</div>
                            <div class="cloud cloud-2">☁️</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Current Conditions Grid using CSS Grid -->
            <div class="conditions-grid">
                <div class="condition-card">
                    <span class="condition-icon">💧</span>
                    <div class="condition-info">
                        <span class="condition-label">Humidity</span>
                        <span class="condition-value">68%</span>
                    </div>
                </div>
                <div class="condition-card">
                    <span class="condition-icon">💨</span>
                    <div class="condition-info">
                        <span class="condition-label">Wind Speed</span>
                        <span class="condition-value">12 km/h</span>
                    </div>
                </div>
                <div class="condition-card">
                    <span class="condition-icon">👁️</span>
                    <div class="condition-info">
                        <span class="condition-label">Visibility</span>
                        <span class="condition-value">10 km</span>
                    </div>
                </div>
                <div class="condition-card">
                    <span class="condition-icon">🌡️</span>
                    <div class="condition-info">
                        <span class="condition-label">Feels Like</span>
                        <span class="condition-value">27°C</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Content Area -->
        <section class="content">
            <!-- 7-Day Forecast Section using Flexbox -->
            <div class="forecast-section" id="forecast">
                <h2>7-Day Forecast</h2>
                <div class="forecast-container">
                    <div class="forecast-day">
                        <div class="day-name">Today</div>
                        <div class="weather-emoji">⛅</div>
                        <div class="temp-range">
                            <span class="high">26°</span>
                            <span class="low">18°</span>
                        </div>
                        <div class="precipitation">60%</div>
                    </div>
                    <div class="forecast-day">
                        <div class="day-name">Thu</div>
                        <div class="weather-emoji">🌦️</div>
                        <div class="temp-range">
                            <span class="high">23°</span>
                            <span class="low">16°</span>
                        </div>
                        <div class="precipitation">80%</div>
                    </div>
                    <div class="forecast-day">
                        <div class="day-name">Fri</div>
                        <div class="weather-emoji">🌧️</div>
                        <div class="temp-range">
                            <span class="high">21°</span>
                            <span class="low">15°</span>
                        </div>
                        <div class="precipitation">90%</div>
                    </div>
                    <div class="forecast-day">
                        <div class="day-name">Sat</div>
                        <div class="weather-emoji">☀️</div>
                        <div class="temp-range">
                            <span class="high">28°</span>
                            <span class="low">19°</span>
                        </div>
                        <div class="precipitation">10%</div>
                    </div>
                    <div class="forecast-day">
                        <div class="day-name">Sun</div>
                        <div class="weather-emoji">☀️</div>
                        <div class="temp-range">
                            <span class="high">29°</span>
                            <span class="low">20°</span>
                        </div>
                        <div class="precipitation">5%</div>
                    </div>
                    <div class="forecast-day">
                        <div class="day-name">Mon</div>
                        <div class="weather-emoji">⛅</div>
                        <div class="temp-range">
                            <span class="high">27°</span>
                            <span class="low">18°</span>
                        </div>
                        <div class="precipitation">30%</div>
                    </div>
                    <div class="forecast-day">
                        <div class="day-name">Tue</div>
                        <div class="weather-emoji">🌤️</div>
                        <div class="temp-range">
                            <span class="high">25°</span>
                            <span class="low">17°</span>
                        </div>
                        <div class="precipitation">20%</div>
                    </div>
                </div>
            </div>

            <!-- Hourly Forecast -->
            <div class="hourly-section">
                <h3>24-Hour Forecast</h3>
                <div class="hourly-scroll">
                    <div class="hourly-item">
                        <div class="hour">Now</div>
                        <div class="hourly-icon">⛅</div>
                        <div class="hourly-temp">24°</div>
                        <div class="hourly-rain">60%</div>
                    </div>
                    <div class="hourly-item">
                        <div class="hour">15:00</div>
                        <div class="hourly-icon">☀️</div>
                        <div class="hourly-temp">26°</div>
                        <div class="hourly-rain">20%</div>
                    </div>
                    <div class="hourly-item">
                        <div class="hour">16:00</div>
                        <div class="hourly-icon">☀️</div>
                        <div class="hourly-temp">27°</div>
                        <div class="hourly-rain">10%</div>
                    </div>
                    <div class="hourly-item">
                        <div class="hour">17:00</div>
                        <div class="hourly-icon">⛅</div>
                        <div class="hourly-temp">25°</div>
                        <div class="hourly-rain">30%</div>
                    </div>
                    <div class="hourly-item">
                        <div class="hour">18:00</div>
                        <div class="hourly-icon">🌤️</div>
                        <div class="hourly-temp">23°</div>
                        <div class="hourly-rain">40%</div>
                    </div>
                    <div class="hourly-item">
                        <div class="hour">19:00</div>
                        <div class="hourly-icon">🌦️</div>
                        <div class="hourly-temp">22°</div>
                        <div class="hourly-rain">70%</div>
                    </div>
                </div>
            </div>

            <!-- Weather Map Section -->
            <div class="radar-section" id="radar">
                <h2>Weather Radar</h2>
                <div class="map-container">
                    <div class="weather-map">
                        <div class="map-overlay">
                            <h3>Interactive Radar</h3>
                            <p>Real-time precipitation and weather patterns</p>
                            <div class="map-legend">
                                <div class="legend-item">
                                    <span class="legend-color rain-light"></span>
                                    <span>Light Rain</span>
                                </div>
                                <div class="legend-item">
                                    <span class="legend-color rain-moderate"></span>
                                    <span>Moderate Rain</span>
                                </div>
                                <div class="legend-item">
                                    <span class="legend-color rain-heavy"></span>
                                    <span>Heavy Rain</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Sidebar -->
        <aside class="sidebar">
            <div class="sidebar-content">
                <!-- Weather Alerts -->
                <div class="widget alerts-widget" id="alerts">
                    <h3>🚨 Weather Alerts</h3>
                    <div class="alert-item">
                        <div class="alert-type">Thunderstorm Watch</div>
                        <div class="alert-time">Valid until 8:00 PM</div>
                        <div class="alert-description">Scattered thunderstorms possible this evening</div>
                    </div>
                    <div class="alert-item">
                        <div class="alert-type">UV Index High</div>
                        <div class="alert-time">Tomorrow 12:00-16:00</div>
                        <div class="alert-description">UV levels will be high. Use sun protection</div>
                    </div>
                </div>
                
                <!-- Climate Data Widget -->
                <div class="widget climate-widget" id="climate">
                    <h3>🌍 Climate Data</h3>
                    <div class="climate-stats">
                        <div class="climate-stat">
                            <span class="stat-label">Monthly Avg</span>
                            <span class="stat-value">22°C</span>
                        </div>
                        <div class="climate-stat">
                            <span class="stat-label">Rainfall This Month</span>
                            <span class="stat-value">45mm</span>
                        </div>
                        <div class="climate-stat">
                            <span class="stat-label">Seasonal Outlook</span>
                            <span class="stat-value">Above Normal</span>
                        </div>
                    </div>
                </div>

                <!-- Air Quality Widget -->
                <div class="widget air-quality-widget">
                    <h3>🌬️ Air Quality</h3>
                    <div class="aqi-display">
                        <div class="aqi-value good">
                            <span class="aqi-number">42</span>
                            <span class="aqi-label">AQI</span>
                        </div>
                        <div class="aqi-description">
                            <strong>Good</strong>
                            <p>Air quality is satisfactory for most people</p>
                        </div>
                    </div>
                    <div class="aqi-breakdown">
                        <div class="pollutant">
                            <span>PM2.5</span>
                            <div class="pollutant-bar">
                                <div class="pollutant-level" style="width: 30%"></div>
                            </div>
                        </div>
                        <div class="pollutant">
                            <span>O₃</span>
                            <div class="pollutant-bar">
                                <div class="pollutant-level" style="width: 45%"></div>
                            </div>
                        </div>
                        <div class="pollutant">
                            <span>NO₂</span>
                            <div class="pollutant-bar">
                                <div class="pollutant-level" style="width: 25%"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Sun & Moon Widget -->
                <div class="widget sun-moon-widget">
                    <h3>☀️ Sun & Moon</h3>
                    <div class="sun-moon-grid">
                        <div class="sun-info">
                            <div class="celestial-icon">🌅</div>
                            <div class="celestial-data">
                                <span class="celestial-label">Sunrise</span>
                                <span class="celestial-time">6:32 AM</span>
                            </div>
                        </div>
                        <div class="sun-info">
                            <div class="celestial-icon">🌇</div>
                            <div class="celestial-data">
                                <span class="celestial-label">Sunset</span>
                                <span class="celestial-time">6:47 PM</span>
                            </div>
                        </div>
                        <div class="sun-info">
                            <div class="celestial-icon">🌙</div>
                            <div class="celestial-data">
                                <span class="celestial-label">Moon Phase</span>
                                <span class="celestial-time">Waxing Crescent</span>
                            </div>
                        </div>
                        <div class="sun-info">
                            <div class="celestial-icon">⚡</div>
                            <div class="celestial-data">
                                <span class="celestial-label">UV Index</span>
                                <span class="celestial-time">7 (High)</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </aside>
    </main>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Weather Services</h3>
                    <div class="weather-links">
                        <a href="#">Current Conditions</a>
                        <a href="#">Extended Forecast</a>
                        <a href="#">Weather Radar</a>
                        <a href="#">Severe Weather</a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>Locations</h3>
                    <ul>
                        <li><a href="#">Nairobi</a></li>
                        <li><a href="#">Mombasa</a></li>
                        <li><a href="#">Kisumu</a></li>
                        <li><a href="#">Eldoret</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Weather Alerts</h3>
                    <p>Stay informed with severe weather notifications</p>
                    <form class="alert-signup">
                        <input type="email" placeholder="Enter your email">
                        <button type="submit">Subscribe</button>
                    </form>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 WeatherCentral. Powered by advanced meteorological data.</p>
            </div>
        </div>
    </footer>
</body>
</html>

    <style>
/* CSS Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    line-height: 1.6;
    color: #333;
    background: linear-gradient(135deg, #74b9ff 0%, #0984e3 50%, #6c5ce7 100%);
    min-height: 100vh;
    position: relative;
}

body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: 
        radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 50%),
        radial-gradient(circle at 80% 20%, rgba(255, 255, 255, 0.1) 0%, transparent 50%),
        radial-gradient(circle at 40% 80%, rgba(255, 255, 255, 0.1) 0%, transparent 50%);
    pointer-events: none;
    z-index: -1;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

/* Header Styles - Using Flexbox */
.header {
    position: sticky;
    top: 0;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    z-index: 1000;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
}

.logo h1 {
    background: linear-gradient(135deg, #74b9ff, #0984e3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-size: 1.8rem;
    font-weight: 700;
}

/* Navigation using Flexbox */
.nav-list {
    display: flex;
    list-style: none;
    gap: 2rem;
    align-items: center;
}

.nav-list a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: all 0.3s ease;
    position: relative;
}

.nav-list a:hover {
    color: #74b9ff;
    transform: translateY(-2px);
}

.nav-list a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -5px;
    left: 0;
    background: linear-gradient(135deg, #74b9ff, #0984e3);
    transition: width 0.3s ease;
}

.nav-list a:hover::after {
    width: 100%;
}

.mobile-menu-toggle {
    display: none;
    flex-direction: column;
    cursor: pointer;
    gap: 4px;
}

.mobile-menu-toggle span {
    width: 25px;
    height: 3px;
    background: #333;
    transition: all 0.3s ease;
}

/* Main Layout using CSS Grid */
.main-layout {
    display: grid;
    grid-template-columns: 1fr 350px;
    grid-template-areas: 
        "hero hero"
        "content sidebar";
    gap: 2rem;
    max-width: 1200px;
    margin: 2rem auto;
    padding: 0 2rem;
}

/* Hero Weather Section */
.weather-hero {
    grid-area: hero;
    background: rgba(255, 255, 255, 0.15);
    backdrop-filter: blur(20px);
    border-radius: 20px;
    padding: 3rem;
    margin-bottom: 2rem;
    border: 1px solid rgba(255, 255, 255, 0.2);
    position: relative;
    overflow: hidden;
}

.current-weather {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 2rem;
}

.weather-main {
    display: flex;
    align-items: center;
    gap: 2rem;
}

.temperature {
    display: flex;
    align-items: flex-start;
    color: white;
}

.temp-value {
    font-size: 4.5rem;
    font-weight: 300;
    text-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
}

.temp-unit {
    font-size: 2rem;
    margin-top: 0.5rem;
    opacity: 0.8;
}

.weather-info h2 {
    font-size: 2rem;
    color: white;
    margin-bottom: 0.5rem;
    text-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
}

.location, .last-updated {
    color: rgba(255, 255, 255, 0.9);
    font-size: 1rem;
    margin-bottom: 0.3rem;
}

.weather-icon {
    display: flex;
    justify-content: center;
    align-items: center;
}

.animated-weather {
    position: relative;
    font-size: 4rem;
}

.sun {
    animation: rotate 20s linear infinite;
    display: inline-block;
}

@keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
}

.clouds {
    position: absolute;
    top: -20px;
    left: -20px;
    width: 120px;
    height: 80px;
}

.cloud {
    position: absolute;
    animation: float 8s ease-in-out infinite;
}

.cloud-1 {
    top: 0;
    left: 0;
    animation-delay: 0s;
    font-size: 2rem;
}

.cloud {
    top: 20px;
    right: 0;
    animation-delay: 2s;
    font-size: 1.5rem;
    opacity: 0.8;
}

@keyframes float {
    0%, 100% { transform: translateY(0px) translateX(0px); }
    33% { transform: translateY(-10px) translateX(5px); }
    66% { transform: translateY(5px) translateX(-5px); }
}

/* Current Conditions Grid using CSS Grid */
.conditions-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5rem;
}

.condition-card {
    background: rgba(255, 255, 255, 0.2);
    backdrop-filter: blur(20px);
    border-radius: 15px;
    padding: 1.5rem;
    border: 1px solid rgba(255, 255, 255, 0.3);
    display: flex;
    align-items: center;
    gap: 1rem;
    transition: all 0.3s ease;
}

.condition-card:hover {
    transform: translateY(-5px);
    background: rgba(255, 255, 255, 0.25);
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
}

.condition-icon {
    font-size: 2rem;
}

.condition-info {
    display: flex;
    flex-direction: column;
}

.condition-label {
    color: rgba(255, 255, 255, 0.8);
    font-size: 0.9rem;
    margin-bottom: 0.2rem;
}

.condition-value {
    color: white;
    font-size: 1.3rem;
    font-weight: 600;
}

/* Content Area */
.content {
    grid-area: content;
    background: white;
    border-radius: 20px;
    padding: 2rem;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

.forecast-section, .hourly-section, .radar-section {
    margin-bottom: 3rem;
}

.forecast-section h2, .radar-section h2 {
    font-size: 2rem;
    margin-bottom: 1.5rem;
    background: linear-gradient(135deg, #74b9ff, #0984e3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.hourly-section h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: #333;
}

/* 7-Day Forecast using Flexbox */
.forecast-container {
    display: flex;
    gap: 1rem;
    overflow-x: auto;
    padding: 1rem 0;
}

.forecast-day {
    min-width: 140px;
    background: linear-gradient(135deg, #f8f9ff, #e8f0ff);
    border-radius: 15px;
    padding: 1.5rem 1rem;
    text-align: center;
    transition: all 0.3s ease;
    border: 1px solid rgba(116, 185, 255, 0.2);
    flex-shrink: 0;
}

.forecast-day:hover {
    transform: translateY(-5px);
    background: linear-gradient(135deg, #74b9ff, #0984e3);
    color: white;
    box-shadow: 0 15px 35px rgba(116, 185, 255, 0.3);
}

.day-name {
    font-weight: 600;
    margin-bottom: 0.5rem;
    font-size: 0.9rem;
}

.weather-emoji {
    font-size: 2.5rem;
    margin: 0.5rem 0;
}

.temp-range {
    display: flex;
    justify-content: space-between;
    margin: 0.5rem 0;
    font-weight: 600;
}

.high {
    color: #e17055;
}

.low {
    color: #74b9ff;
    opacity: 0.7;
}

.forecast-day:hover .low {
    opacity: 1;
    color: rgba(255, 255, 255, 0.8);
}

.precipitation {
    font-size: 0.85rem;
    opacity: 0.7;
    margin-top: 0.5rem;
}

/* Hourly Forecast */
.hourly-scroll {
    display: flex;
    gap: 1rem;
    overflow-x: auto;
    padding: 1rem 0;
}

.hourly-item {
    min-width: 80px;
    background: #f8f9fa;
    border-radius: 12px;
    padding: 1rem 0.5rem;
    text-align: center;
    flex-shrink: 0;
    transition: all 0.3s ease;
    border: 1px solid #e9ecef;
}

.hourly-item:hover {
    background: #74b9ff;
    color: white;
    transform: translateY(-3px);
}

.hour {
    font-size: 0.8rem;
    margin-bottom: 0.5rem;
    opacity: 0.7;
}

.hourly-icon {
    font-size: 1.5rem;
    margin: 0.3rem 0;
}

.hourly-temp {
    font-weight: 600;
    margin: 0.3rem 0;
}

.hourly-rain {
    font-size: 0.75rem;
    opacity: 0.6;
}

/* Weather Radar Section */
.map-container {
    background: #f8f9fa;
    border-radius: 15px;
    overflow: hidden;
    border: 1px solid #e9ecef;
}

.weather-map {
    height: 300px;
    background: linear-gradient(135deg, #74b9ff 0%, #0984e3 50%, #6c5ce7 100%);
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
}

.map-overlay {
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    border-radius: 15px;
    padding: 2rem;
    text-align: center;
    border: 1px solid rgba(255, 255, 255, 0.3);
}

.map-overlay h3 {
    margin-bottom: 0.5rem;
    color: #333;
}

.map-overlay p {
    color: #666;
    margin-bottom: 1.5rem;
}

.map-legend {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
}

.legend-item {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    font-size: 0.85rem;
}

.legend-color {
    width: 16px;
    height: 16px;
    border-radius: 3px;
}

.rain-light { background: #81ecec; }
.rain-moderate { background: #00b894; }
.rain-heavy { background: #00a085; }

/* Sidebar */
.sidebar {
    grid-area: sidebar;
    background: white;
    border-radius: 20px;
    padding: 2rem;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    height: fit-content;
    position: sticky;
    top: 100px;
}
