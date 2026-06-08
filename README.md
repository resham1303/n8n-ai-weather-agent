# n8n-ai-weather-agent
AI-powered weather assistant built using n8n, OpenAI, and APIs
# AI Weather Agent (n8n)

##  Overview
An AI-powered weather assistant built using n8n that automatically fetches and sends daily weather updates.

## Features
- Fetches real-time weather data
- Checks calendar for location context
- Uses AI to generate human-friendly summaries
- Sends automated email updates
- Includes air quality insights (AQI)

## Tech Stack
- n8n (workflow automation)
- OpenAI (AI responses)
- OpenWeatherMap API
- AirNow API
- Google Calendar API
- Gmail API

## Workflow
1. Schedule trigger runs daily  
2. AI agent determines location  
3. Fetches weather + AQI  
4. Generates response using AI  
5. Sends email update  

## Project Structure
- `workflow.json` → n8n workflow
- `screenshots/` → visuals

##  Setup Instructions
1. Import `workflow.json` into n8n  
2. Add your API keys and credentials  
3. Activate workflow  

##  Note
All API keys and credentials have been removed for security.

## Future Improvements
- Telegram/WhatsApp integration  
- Multi-location support  
- Weather alerts & predictions  
