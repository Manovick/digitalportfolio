# AI Support Ticket Classifier

## Overview

This project uses AI to classify customer support messages into categories and priority levels.

## Features

- AI-powered ticket classification
- Priority assignment
- JSON formatted output

## Categories

- Billing
- Technical Issue
- Account
- General Inquiry

## Priority Levels

- High
- Medium
- Low

## Installation

```bash
pip install openai
```

## Run

```bash
python app.py
```

## Approach

The application sends customer support messages to an AI model using an OpenAI-compatible API. The AI dynamically classifies messages and returns structured JSON output.

## Sample Output

```json
[
    {
        "message": "My payment got deducted but service is not activated",
        "category": "Billing",
        "priority": "High"
    }
]
```
