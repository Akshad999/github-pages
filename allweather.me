<!-- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Weather Detector</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      transition: background 0.5s ease;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
    }

    nav {
      background-color: #333;
      width: 100%;
      padding: 10px;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-size: 18px;
    }

    nav a:hover {
      color: #ddd;
    }

    .alert-bar {
      background-color: yellow;
      color: black;
      padding: 10px;
      width: 100%;
      text-align: center;
      position: fixed;
      top: 40px;
      left: 0;
      z-index: 1000;
      display: none;
    }

    .alert-close {
      cursor: pointer;
      font-weight: bold;
      margin-left: 15px;
    }

    .container {
      text-align: center;
      padding: 30px;
      border-radius: 20px;
      background: rgba(255, 255, 255, 0.2);
      box-shadow: 0 8px 16px rgba(0,0,0,0.3);
      backdrop-filter: blur(10px);
      max-width: 400px;
      margin-top: 100px;
    }

    input {
      padding: 10px;
      width: 80%;
      border: none;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    button {
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      background-color: #007BFF;
      color: white;
      cursor: pointer;
      margin-bottom: 20px;
    }

    .info {
      font-size: 18px;
      line-height: 1.5;
    }

    section {
      margin-top: 100px;
      padding: 20px;
      width: 90%;
      max-width: 800px;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      display: none;
    }

    .footer {
      margin-top: 50px;
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    .sunny {
      background: linear-gradient(to top, lightyellow, gold);
    }

    .cloudy {
      background: linear-gradient(to top, lightgray, slategray);
    }

    .rainy {
      background: linear-gradient(to top, mediumslateblue, lightskyblue);
    }

    .windy {
      background: linear-gradient(to top, lightgray, darkslategray);
    }

    .clear {
      background: linear-gradient(to top, deepskyblue, lightskyblue, white);
    }
  </style>
</head>
<body>
  <nav>
    <a href="javascript:void(0)" onclick="goHome()">Home</a>
    <a href="javascript:void(0)" onclick="showAbout()">About</a>
    <a href="javascript:void(0)" onclick="showOwner()">Product Owner</a>
    <a href="javascript:void(0)" onclick="showFAQ()">FAQ</a>
  </nav>

  <div id="weatherAlert" class="alert-bar">
    <span id="alertMessage">Severe Weather Alert.</span>
    <span class="alert-close" onclick="closeAlert()">X</span>
  </div>

  <div id="app" class="container">
    <h1>Weather Detector 🌤️</h1>
    <input type="text" id="cityInput" placeholder="Enter City Name (e.g., Kangra)">
    <button onclick="getWeather()">Get Weather</button>
    <div id="weatherInfo" class="info"></div>
  </div>

  <section id="aboutSection">
    <h2>About This Website</h2>
    <p>This website provides real-time weather updates for any city worldwide.</p>
  </section>

  <section id="ownerSection">
    <h2>Product Owner</h2>
    <p>This website is created and owned by <strong>Akshad</strong>.</p>
  </section>

  <section id="faqSection">
    <h2>FAQ</h2>
    <p><strong>Q:</strong> Where does the weather data come from?<br><strong>A:</strong> It is sourced from OpenWeatherMap.</p>
  </section>

  <div class="footer">
    <p>© 2025 Akshad | All rights reserved.</p>
  </div>

  <script>
    const apiKey = 'c0559416e5e9446c9de2b5883b08fa40';

    function showWeatherAlert(message) {
      document.getElementById('alertMessage').textContent = message;
      document.getElementById('weatherAlert').style.display = 'block';
    }

    function closeAlert() {
      document.getElementById('weatherAlert').style.display = 'none';
    }

    function goHome() {
      document.getElementById('cityInput').value = '';
      document.getElementById('weatherInfo').innerHTML = '';
      document.getElementById('app').style.display = 'block';
      document.getElementById('aboutSection').style.display = 'none';
      document.getElementById('ownerSection').style.display = 'none';
      document.getElementById('faqSection').style.display = 'none';
    }

    function showAbout() {
      document.getElementById('app').style.display = 'none';
      document.getElementById('aboutSection').style.display = 'block';
      document.getElementById('ownerSection').style.display = 'none';
      document.getElementById('faqSection').style.display = 'none';
    }

    function showOwner() {
      document.getElementById('app').style.display = 'none';
      document.getElementById('aboutSection').style.display = 'none';
      document.getElementById('ownerSection').style.display = 'block';
      document.getElementById('faqSection').style.display = 'none';
    }

    function showFAQ() {
      document.getElementById('app').style.display = 'none';
      document.getElementById('aboutSection').style.display = 'none';
      document.getElementById('ownerSection').style.display = 'none';
      document.getElementById('faqSection').style.display = 'block';
    }

    async function getWeather() {
      const city = document.getElementById('cityInput').value.trim();
      if (!city) return alert('Please enter a city name');

      try {
        const geoRes = await fetch(`https://api.openweathermap.org/geo/1.0/direct?q=${city}&limit=1&appid=${apiKey}`);
        const geoData = await geoRes.json();
        if (!geoData.length) throw new Error("City not found");

        const { lat, lon, name, country, state } = geoData[0];
        const weatherRes = await fetch(`https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${apiKey}&units=metric`);
        const weatherData = await weatherRes.json();

        const temp = weatherData.main.temp;
        const weather = weatherData.weather[0].main.toLowerCase();
        const wind = (weatherData.wind.speed * 3.6).toFixed(1);

        let condition = 'clear';
        if (weather.includes('cloud')) condition = 'cloudy';
        else if (weather.includes('rain')) condition = 'rainy';
        else if (weather.includes('wind')) condition = 'windy';
        else if (weather.includes('sun') || weather.includes('clear')) condition = 'sunny';

        document.body.className = condition;
        document.getElementById('weatherInfo').innerHTML = `
          <h2>${name}, ${state || ''} (${country})</h2>
          <p>Temperature: ${temp}°C</p>
          <p>Condition: ${weather.charAt(0).toUpperCase() + weather.slice(1)}</p>
          <p>Wind Speed: ${wind} km/h</p>
        `;

        const forecastRes = await fetch(`https://api.openweathermap.org/data/2.5/forecast?lat=${lat}&lon=${lon}&appid=${apiKey}&units=metric`);
        const forecastData = await forecastRes.json();
        const nextDay = forecastData.list[8];
        const nextTemp = nextDay.main.temp;

        if (nextTemp > 30) {
          showWeatherAlert(`Tomorrow will be hot in ${name}. Stay hydrated and avoid peak sun.`);
        } else if (nextTemp < 5) {
          showWeatherAlert(`Cold weather expected tomorrow in ${name}. Stay warm!`);
        } else if (nextDay.weather[0].main.toLowerCase().includes('rain')) {
          showWeatherAlert(`Rain is likely tomorrow in ${name}. Don't forget your umbrella!`);
        } else {
          closeAlert();
        }
      } catch (error) {
        document.getElementById('weatherInfo').innerHTML = `<p style="color:red;">Error: ${error.message}</p>`;
        document.body.className = '';
        closeAlert();
      }
    }
  </script>
</body>
</html> -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Weather Detector</title>
  <style>
    /* Basic styling */
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      transition: background 0.5s ease;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
    }

    /* Navbar Styling */
    nav {
      background-color: #333;
      width: 100%;
      padding: 10px;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-size: 18px;
    }

    nav a:hover {
      color: #ddd;
    }

    /* Weather Alert Bar */
    .alert-bar {
      background-color: yellow;
      color: black;
      padding: 10px;
      width: 100%;
      text-align: center;
      position: fixed;
      top: 40px;
      left: 0;
      z-index: 1000;
      display: none; /* Hidden by default */
    }

    /* Styling for Alert Close Button */
    .alert-close {
      cursor: pointer;
      font-weight: bold;
      margin-left: 15px;
    }

    /* Main content styling */
    .container {
      text-align: center;
      padding: 30px;
      border-radius: 20px;
      background: rgb(180, 174, 174);
      box-shadow: 0 8px 16px rgb(255, 19, 19);
      backdrop-filter: blur(10px);
      max-width: 400px;
      margin-top: 100px;
    }

    input {
      padding: 10px;
      width: 80%;
      border: none;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    button {
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      background-color: #007BFF;
      color: white;
      cursor: pointer;
      margin-bottom: 20px;
    }

    .info {
      font-size: 18px;
      line-height: 1.5;
    }

    /* FAQ Section Styling */
    #faqSection {
      background-color: rgba(255, 255, 255, 0.1);
      padding: 20px;
      margin-top: 20px;
      border-radius: 10px;
      width: 80%;
      max-width: 600px;
    }

    /* Section Styling */
    section {
      margin-top: 100px;
      padding: 20px;
      width: 90%;
      max-width: 800px;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
    }

    .footer {
      margin-top: 50px;
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    /* Weather Background Colors */
    .sunny {
      background-color: #fce205;
    }

    .mild {
      background-color: #f0e68c;
    }

    .cloudy {
      background-color: #b0c4de;
    }

    .rainy {
      background-color: rgb(70, 70, 243);
    }

    .windy {
      background-color: #add8e6;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <a href="javascript:void(0)" onclick="goHome()">Home</a>
    <a href="javascript:void(0)" onclick="showAbout()">About</a>
    <a href="javascript:void(0)" onclick="showOwner()">Product Owner</a>
    <a href="javascript:void(0)" onclick="showFAQ()">FAQ</a>
  </nav>

  <!-- Weather Alert Bar -->
  <div id="weatherAlert" class="alert-bar">
    <span id="alertMessage">Severe Weather Alert: Heavy rainfall expected in your area.</span>
    <span class="alert-close" onclick="closeAlert()">X</span>
  </div>

  <!-- Main Weather Detector Container -->
  <div id="app" class="container">
    <h1>Weather Detector 🌤️</h1>
    <input type="text" id="cityInput" placeholder="Enter City Name (e.g., Kangra)">
    <button onclick="getWeather()">Get Weather</button>
    <div id="weatherInfo" class="info"></div>
    <div id="tomorrowWeatherInfo" class="info"></div>
  </div>

  <!-- About Section -->
  <section id="aboutSection" style="display: none;">
    <h2>About This Website</h2>
    <p>This website provides real-time weather updates for any city worldwide. It helps you stay informed about the weather conditions, including temperature, humidity, wind speed, and more!</p>
    <p>Weather data is sourced from OpenWeatherMap API.</p>
  </section>

  <!-- Product Owner Section -->
  <section id="ownerSection" style="display: none;">
    <h2>Product Owner</h2>
    <p>This website is created and owned by <strong>Akshad</strong>. It is a personal project developed to provide real-time weather updates to users worldwide.</p>
  </section>

  <!-- FAQ Section -->
  <section id="faqSection" style="display: none;">
    <h2>FAQ</h2>
    <p><strong>Q1: What data does this site provide?</strong></p>
    <p>A1: This website provides real-time weather data for any city worldwide. The data includes temperature, weather condition, and wind speed.</p>

    <p><strong>Q2: What are the limitations of this site?</strong></p>
    <p>A2: The site has some limitations, such as:</p>
    <ul>
      <li>Weather data might not be 100% accurate due to the nature of forecasting.</li>
      <li>The site depends on third-party APIs for data, so availability and speed may vary.</li>
      <li>There are occasional API call limitations, especially for free-tier accounts.</li>
    </ul>

    <p><strong>Q3: How can I get more accurate weather information?</strong></p>
    <p>A3: For more detailed weather reports, we recommend checking official weather websites or apps.</p>
  </section>

  <div class="footer">
    <p>© 2025 Akshad | All rights reserved.</p>
  </div>

  <script>
    const apiKey = 'c0559416e5e9446c9de2b5883b08fa40'; // Your real OpenWeatherMap API key

    // Function to display Weather Alert
    function showWeatherAlert(message) {
      const alertBar = document.getElementById('weatherAlert');
      const alertMessage = document.getElementById('alertMessage');
      alertMessage.textContent = message; // Set the alert message
      alertBar.style.display = 'block'; // Show the alert bar
    }

    // Close the Weather Alert Bar
    function closeAlert() {
      const alertBar = document.getElementById('weatherAlert');
      alertBar.style.display = 'none'; // Hide the alert bar
    }

    // Function to navigate back to the home page and show an alert
    function goHome() {
      alert("Oh, you want to know about your city weather? Please put your city name in the box!");
      const cityInput = document.getElementById('cityInput');
      cityInput.value = ''; // Clear the city input field
      document.getElementById('weatherInfo').innerHTML = ''; // Clear the weather info
      document.getElementById('tomorrowWeatherInfo').innerHTML = ''; // Clear tomorrow weather info
      document.getElementById('app').style.display = 'block'; // Show the main weather div
      document.getElementById('aboutSection').style.display = 'none'; // Hide the About section
      document.getElementById('ownerSection').style.display = 'none'; // Hide the Owner section
      document.getElementById('faqSection').style.display = 'none'; // Hide FAQ section
    }

    // Show About Section
    function showAbout() {
      document.getElementById('aboutSection').style.display = 'block';
      document.getElementById('ownerSection').style.display = 'none';
      document.getElementById('app').style.display = 'none';
      document.getElementById('faqSection').style.display = 'none'; // Hide FAQ section
    }

    // Show Product Owner Section
    function showOwner() {
      document.getElementById('aboutSection').style.display = 'none';
      document.getElementById('ownerSection').style.display = 'block';
      document.getElementById('app').style.display = 'none';
      document.getElementById('faqSection').style.display = 'none'; // Hide FAQ section
    }

    // Show FAQ Section
    function showFAQ() {
      document.getElementById('aboutSection').style.display = 'none';
      document.getElementById('ownerSection').style.display = 'none';
      document.getElementById('app').style.display = 'none';
      document.getElementById('faqSection').style.display = 'block'; // Show FAQ section
    }

    async function getWeather() {
      const city = document.getElementById('cityInput').value.trim();
      if (!city) return alert('Please enter a city name');

      const geoUrl = `https://api.openweathermap.org/geo/1.0/direct?q=${city}&limit=1&appid=${apiKey}`;

      try {
        const geoRes = await fetch(geoUrl);
        const geoData = await geoRes.json();

        if (!geoData.length) {
          throw new Error("City not found");
        }

        const { lat, lon, name, country, state } = geoData[0];

        // Fetching weather data
        const weatherUrl = `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${apiKey}&units=metric`;
        const weatherRes = await fetch(weatherUrl);
        const weatherData = await weatherRes.json();

        const temp = weatherData.main.temp;
        const weather = weatherData.weather[0].main.toLowerCase();
        const wind = (weatherData.wind.speed * 3.6).toFixed(1); // Convert to km/h

        let condition = 'clear';
        let weatherMessage = '';
        if (weather.includes('cloud')) {
          condition = 'cloudy';
          weatherMessage = "Tomorrow will be cloudy.";
        } else if (weather.includes('rain')) {
          condition = 'rainy';
          weatherMessage = "Tomorrow will be rainy.";
        } else if (weather.includes('wind')) {
          condition = 'windy';
          weatherMessage = "Tomorrow will be windy.";
        } else if (weather.includes('sun') || weather.includes('clear')) {
          condition = 'sunny';
          weatherMessage = "Tomorrow will be sunny.";
        }

        // Apply background color based on weather condition
        document.body.className = condition;

        // Display current weather info
        document.getElementById('weatherInfo').innerHTML = `
          <h2>${name}, ${state || ''} (${country})</h2>
          <p>Temperature: ${temp}°C</p>
          <p>Condition: ${weather.charAt(0).toUpperCase() + weather.slice(1)}</p>
          <p>Wind Speed: ${wind} km/h</p>
        `;

        // Display tomorrow's weather message
        document.getElementById('tomorrowWeatherInfo').innerHTML = `
          <h3>${weatherMessage}</h3>
        `;

        // Display weather alert based on conditions
        if (weather.includes('rain')) {
          showWeatherAlert("Severe Weather Alert: Heavy rainfall expected in your area.");
        }

      } catch (error) {
        console.error("Error:", error.message);
        document.getElementById('weatherInfo').innerHTML =
          `<p style="color:red;">City not found or API error: ${error.message}</p>`;
        document.body.className = '';
      }
    }
  </script>
</body>
</html>
