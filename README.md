# Base64 Encoder API

A simple Node.js and Express API for Base64 encoding text, designed for automation tools like n8n, webhooks, and microservices.

## Features
- Accepts raw text input via POST requests
- Returns Base64-encoded output
- Lightweight and fast
- Ideal for automation workflows (e.g., n8n Cloud, Zapier, Make.com)

## API Usage

### POST `/encode`

**Request Body:**
gis 
```json
{
  "text": "Your raw text here"
}
