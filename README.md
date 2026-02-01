# AI-Generated-Voice-Detection
FastAPI-based AI Generated Voice Detection API supporting multi-language audio inputs (Tamil, English, Hindi, Malayalam, Telugu) for fraud detection and user safety.
# AI Generated Voice Detection API

## Description
This project detects whether a given voice/audio input is AI-generated or human-generated.
It is built using FastAPI and provides a secure REST API with token-based authorization.

## Technologies Used
- Python
- FastAPI
- Uvicorn
- REST API

## API Endpoint
POST /detect-voice

## Authorization
Header:
Authorization: Bearer Sanjai@0077

## Sample Request
{
  "audio_url": "https://example.com/sample.wav",
  "message": "test"
}

## Sample Response
{
  "classification": "AI-generated",
  "confidence": 0.91
}

## Use Cases
- Detect AI-generated voice fraud
- Media authenticity verification
- Voice-based security systems

## Author
Sanjai Prasath
