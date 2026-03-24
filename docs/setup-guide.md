# Setup Guide

### prerequisites
- A running instance of `n8n`
- `Ollama` installed and running `llama3`
- A Meta Developer account
- A Google Cloud specific service account

## Step-by-step
1. **Google Sheets Config**
   - Create a Google Sheet.
   - Include columns: `Name`, `Phone Number`, `Status`, `Followup`.
   - Share the sheet with your service account email.
2. **Meta App Config**
   - Register for WhatsApp Cloud API.
   - Add your test numbers or connect a real business number.
3. **Local AI**
   - Ensure Ollama is running and accessible from the machine hosting n8n.
4. **n8n Connectivity**
   - Import credentials properly.
   - Route Webhooks to localhost via ngrok, or use a live URL if hosted.
5. **Test**
   - Send a sample message.
   - View the execution logs in n8n.
   - Watch the Google Sheet update magically!
