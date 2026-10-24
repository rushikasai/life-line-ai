# LifeLine AI 🩵

### AI-Powered Safety and Wellbeing Assistant

LifeLine AI is a hosted chat assistant designed to provide calm, practical guidance for everyday safety and wellbeing questions.

It uses conversational AI to help users understand possible next steps in common safety situations and recognise when professional or emergency assistance may be needed.

## Features

- **Safety Guidance:** Provides practical information for everyday safety concerns.
- **Emergency Awareness:** Recognises selected emergency-related messages and prioritises emergency guidance.
- **Conversational Support:** Uses session context to make ongoing conversations more relevant.
- **Agent Chat Protocol:** Supports communication through compatible agent chat interfaces.
- **Fallback Responses:** Provides a fallback message if the AI service is unavailable.
- **Emergency Direction:** For emergencies in India, directs users to call 112 when immediate assistance is needed.

## How It Works

1. A user sends a message through a compatible chat interface.
2. The agent acknowledges the incoming message.
3. Emergency-related messages are checked according to the implemented detection rules.
4. The agent provides relevant guidance or a fallback response.
5. Users are directed to professional or emergency help when appropriate.

## Technology Stack

- Python
- Fetch.ai uAgents
- Agent Chat Protocol
- Agentverse hosting
- ASI:One / ASI1 model integration

The exact dependencies and configuration depend on the implementation.

## Limitations

LifeLine AI is an informational support tool, not a replacement for qualified medical professionals or emergency services.

It does not place emergency calls or contact people on the user's behalf. Emergency detection may not identify every dangerous situation.

For an emergency in India, call 112 directly.

## Setup

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Configure the required environment variables using `.env.example` as a guide.
4. Follow the instructions for the actual agent entry-point file.
5. Test the agent in the intended chat environment.

## Future Scope

- Improved emergency-intent recognition
- More comprehensive safety guidance
- Additional language support
- Further testing of responses across different scenarios

## Project

LifeLine AI — Calm guidance when it matters.
