# Weather Data Collection System 

## Project Overview
This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
- External API Integration (OpenWeather API)
- Cloud Storage (AWS S3)
- Infrastructure as Code
- Version Control (Git)
- Python Development
- Error Handling
- Environment Management

## Features
- Fetches real-time weather data for multiple cities
- Displays temperature (°F), humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports multiple cities tracking
- Timestamps all data for historical tracking

## Technical Architecture
- **Language:** Python 3.x
- **Cloud Provider:** AWS (S3)
- **External API:** OpenWeather API
- **Dependencies:** 
  - boto3 (AWS SDK)
  - python-dotenv
  - requests
 ```markdown
## Project Structure
weather-dashboard/
  src/
    __init__.py
    weather_dashboard.py
  tests/
  data/
  .env
  .gitignore
  requirements.txt

## Setup Instructions
Clone the source code 
git clone https://github.com/manoj0692/Weather-dashboard.git
cd weather-dashboard
## Installed Dependencies 
- pip install boto3==1.26.137
- pip install python-dotenv==1.0.0
- pip install requests==2.28.2
## Configure environment variables(.env)
- OPENWEATHER_API_KEY=your_api_key
- AWS_BUCKET_NAME=your_bucket_name
## AWS Configuration
Configure your aws Account by following command
- aws configure
## Running Python Script
python /src /Weather-dashboard.py

## What I Learn
AWS S3 bucket creation and management
Environment variable management for secure API keys
Python best practices for API integration
Git workflow for project development
Error handling in distributed systems
Cloud resource managementned

## Troubleshooting
While Running Python Script following Error was Comming
**Error Creating Backet: Expected string or Byte got 'nonType)**
Solutation :
In Environment configuration Backet name was mismatch. After remodified Environment Variable programme run successfully




    

