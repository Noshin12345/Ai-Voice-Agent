This workflow powers an AI voice assistant that listens to user queries via a webhook, processes them with OpenAI, and integrates with Google Calendar and Google Sheets. The assistant responds in a natural voice using ElevenLabs.
<img width="919" height="415" alt="image" src="https://github.com/user-attachments/assets/30e98c6f-d8ab-4d0b-8e9d-eb9c0ffb2ac4" />

<section>
  <h3>Node Breakdown</h3>
  <ul>
    <li><strong>Webhook</strong> (<code>POST /information</code>) &rarr; Captures user voice/text input.</li>
    <li><strong>OpenAI Chat Model</strong> (<code>gpt-4o-mini</code>) &rarr; Generates short, conversational responses.</li>
    <li><strong>AI Agent</strong> &rarr; Orchestrates the assistant logic, tone, and behavior.</li>
    <li><strong>Google Sheets</strong> &rarr; Stores or retrieves structured data.</li>
    <li><strong>Google Calendar</strong> &rarr; Schedules and manages events from voice commands.</li>
    <li><strong>Respond to Webhook</strong> &rarr; Sends the processed response back to the user.</li>
  </ul>
</section>
