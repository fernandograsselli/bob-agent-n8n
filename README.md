
---

### 🇺🇸 English Version

```markdown
# 🥃 Bob - The Spirit Guide (n8n Agent)

Bob is an AI agent designed to analyze a user's "bar" within the BAXUS ecosystem and recommend personalized spirits based on their tastes, preferences, and pricing history. It was built using [n8n](https://n8n.io/) and runs via Docker.

## 🚀 How to Run the Project Locally

### Prerequisites

- Docker installed ([instructions](https://docs.docker.com/get-docker/))

- Before running the project, you’ll need two API keys to ensure proper communication with external services:

1. **Google Sheets API Key**: To access and manage your collection data. Get your key from the [Google Cloud Console](https://console.cloud.google.com/)
2. **Groq API Key**: To access the freely available AI models. Create your account and generate your key at [groq.com](https://groq.com/)

### Step-by-step

```bash
# Clone this repository
git clone https://github.com/your-username/bob-n8n.git

# Enter the project folder
cd bob-n8n

# Start the container with n8n and Bob’s workflow
docker compose up -d
