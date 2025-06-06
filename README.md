# WhatsApp API with Slim + Twilio

## Features
- Send interactive WhatsApp message using Twilio API
- Handle user replies via webhook

## Setup Instructions

1. Copy `.env.example` to `.env` and add your Twilio credentials.
2. Deploy to Render (it auto-detects `render.yaml`).
3. Hit `/send-whatsapp` endpoint with a JSON body:

```json
{
  "mobile": "your_mobile",
  "name": "Rolex"
}
```
