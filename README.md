✨ Key Features
🌡️ Weather Information
Real-time weather data display
Current temperature and conditions
Detailed weather metrics:
Humidity
Wind speed and direction
Atmospheric pressure
Visibility
Sunrise and sunset times
"Feels like" temperature
📊 Advanced Features
5-day weather forecast with detailed predictions
Dynamic weather icons that change based on conditions
Dynamic background colors reflecting current weather
Excel-based weather data logging system
Date and time display with automatic updates
User-friendly interface with intuitive controls
🛠️ Technical Requirements
System Requirements
Python 3.8 or higher
Active internet connection
OpenWeatherMap API key
100MB free disk space
4GB RAM recommended
Dependencies
requests==2.31.0
pandas==2.1.0
openpyxl==3.1.2
Pillow==10.0.0
python-dateutil==2.8.2
numpy==1.24.3
📥 Installation Guide
Clone the Repository

git clone https://github.com/sabbirahmad12/weather-application.git
cd weather-application
Set Up Virtual Environment

# Create virtual environment
python -m venv venv

# Activate virtual environment
# For Windows:
venv\Scripts\activate
# For Linux/Mac:
source venv/bin/activate
Install Dependencies

pip install -r requirements.txt
⚙️ Configuration
Get OpenWeatherMap API Key
Visit OpenWeatherMap
Create a free account
Navigate to your account dashboard
Generate an API key
Replace API_KEY in main.py with your key
📁 Project Structure
weather_app/
├── data/                  # Excel logs and data storage
├── main.py                # Main application file
├── background_manager.py  # Background color management
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
└── sc/                    # Application screenshots
🚀 Usage Guide
Launch the Application

python main.py
Using the Application

Enter city name in the search box
Click "Get Weather" or press Enter
View current weather and forecast
Check Excel logs in the data folder
📊 Data Logging
The application automatically logs weather data to Excel files:

Location: data/weather_logs.xlsx
Logged Information:
Timestamp
City name
Temperature
Weather conditions
Humidity
Wind speed
Pressure
Visibility
⚠️ Important Notes
Ensure stable internet connection for real-time updates
Keep your API key secure and don't share it
Weather data updates every 5 minutes
Excel logs are stored in the data folder
Application requires Python 3.8 or higher
