<h1>Real-Time Weather Monitoring Application</h1>
<p>
  This is a web-based weather monitoring application that fetches real-time weather data based on the user's location using the OpenWeatherMap API. It displays the current weather conditions such as temperature, humidity, wind speed, sunrise, sunset, and provides a 7-day weather forecast.
</p>
<h2>Features</h2>
<ul>
  <li>Real-Time Weather Data: Displays current weather conditions including temperature, humidity, pressure, wind speed, sunrise, and sunset.</li>
  <li>7-Day Forecast: Shows day and night temperatures along with weather icons for the next 7 days.</li>
  <li>Responsive Design: The interface adapts to different screen sizes, making it user-friendly on both desktop and mobile devices.</li>
  <li>Dynamic Background: Background image changes based on the current time or weather conditions</li>
</ul>
<h2>Tech Stack</h2>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>OpenWeatherMap API</li>
</ul>
<h2>Setup</h2>
<h3>Prerequisites</h3>
<ol>
  <li>Basic knowledge of HTML, CSS, and JavaScript.</li>
  <li>An OpenWeatherMap API key. You can get one by signing up on the OpenWeatherMap website</li>
</ol>
<h2>Code Overview</h2>
<ul>
  <li>HTML: Basic structure and elements for the weather data.</li>
  <li>CSS: Styling for the weather display, with media queries to handle different screen sizes.</li>
  <p>JavaScript</p>
  <li>Fetches current weather data using the navigator.geolocation API to get the user's location.</li>
  <li>Fetches weather details from the OpenWeatherMap API.</li>
  <li>Displays the weather data dynamically on the web page.</li>
</ul>
<h3>Key Functions in JavaScript</h3>
<ul>
  <p>getWeatherData():</p>
  <li>Uses geolocation to get the user's current coordinates.</li>
  <li>Fetches weather data using the OpenWeatherMap API.</li>
</ul>
<h3>showWeatherData(data)</h3>
<ul>
  <li>Processes the data from the API and updates the UI with weather details, including humidity, wind speed, and sunrise/sunset times.</li>
  <li>Displays a 7-day weather forecast.</li>
</ul>
<h2>OpenWeatherMap API</h2>
<p>This project uses the One Call API from OpenWeatherMap to retrieve weather data. The data includes:</p>
<ul>
  <li>Current weather information (temperature, humidity, pressure, wind speed, sunrise, sunset)</li>
  <li>7-day forecast with day and night temperatures</li>
</ul>
<h2>Future Enhancements</h2>
<ul>
  <li>Dynamic Background: Change the background based on weather conditions (e.g., rainy, sunny, cloudy).</li>
  <li>Hourly Forecast: Display an hourly forecast in addition to the 7-day forecast.</li>
  <li>Weather Alerts: Add functionality to display weather alerts, if available.</li>
</ul>
