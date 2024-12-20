﻿# FlightFinderAI ✈️🤖

FlightFinderAI is a technical flight e-support system powered by the Gemini AI agent and Chainlit for UI/UX. 🚀 It answers your flight-related queries and provides detailed information. The project is dockerized, deployed on Render, and uses SQLite with dummy data generated via Faker. 📊

## Features 🌟
- **AI-powered answers** using Gemini 🤖
- **Interactive UI** built with Chainlit 💬
- **Dockerized** for easy deployment 🐳
- **SQLite database** with dummy data 📦
- **Deployed on Render** for scalability 🌐

## Project Structure 📂

```
FlightFinderAI/
   ├── app.py                 
   ├── GetFlights.py          
   ├── FlightData.db          
   ├── dummy_data_maker.py
   ├── Dockerfile    
   ├── .env                  
   ├── requirements.txt      
```

## Quick Start 🚀

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/FlightFinderAI.git
   cd FlightFinderAI
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your `.env` file for environment variables.

4. Run locally:
   ```bash
   python app.py
   ```

## Docker 🐳
If you want to run the project in a container separately, follow these steps:
1. Build the Docker image:
   ```bash
   docker build -t flightfinderai .
   ```

2. Run the Docker container:
   ```bash
   docker run -p 5000:5000 flightfinderai
   ```

## Deployment on Render 🌐

1. Push your code to GitHub.

2. Go to [Render](https://render.com) and create a new **Web Service**.

3. Connect your GitHub repository to Render.

4. Render will automatically detect the Dockerfile and deploy the app! 🚀

## License 📄

MIT License. See the [LICENSE](LICENSE) for details.

## Demo 🎬

https://github.com/user-attachments/assets/d3e94f67-08c4-4263-acc6-5a3a81887cfe




