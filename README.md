This workflow powers an AI voice assistant that listens to user queries via a webhook, processes them with OpenAI, and integrates with Google Calendar and Google Sheets. The assistant responds in a natural voice using ElevenLabs.
<img width="919" height="415" alt="image" src="https://github.com/user-attachments/assets/30e98c6f-d8ab-4d0b-8e9d-eb9c0ffb2ac4" />

Node Breakdown
Webhook (POST /information) → Captures user voice/text input.
OpenAI Chat Model (gpt-4o-mini) → Generates short, conversational responses.
AI Agent → Orchestrates the assistant logic, tone, and behavior.
Google Sheets → Stores or retrieves structured data
Google Calendar → Schedules and manages events from voice commands.
Respond to Webhook → Sends the processed response back to the user.
