# Year in Poetry (My Year in Moments)

A quiet, late-night web experience that turns your meaningful dates into an AI-curated year you can read like a poem.

**Visual aesthetic:** [listening-room](../../skills-garden/ux-design-skills/listening-room.md) — warm-dark canvas, breathing host orb, drifting dust, broadcast chrome. No hero artifact: the user's moments are the visual.

## Setup Instructions

### 1. Backend Configuration
Navigate to the backend directory and install dependencies with `uv`:
```bash
cd /Users/annie/Documents/Demo/coding-jam/year-in-poetry/backend

# Install dependencies
uv sync
```

### 2. Environment Variables
Create a `.env` file in the `backend/` directory and add your Gemini API key:
```env
GEMINI_API_KEY=your_api_key_here
```

### 3. Running the App
Once your environment is set up and your API key is added, you can start the FastAPI backend. (The backend will automatically serve the frontend files!)

Run the following command from the `backend/` directory:
```bash
uv run uvicorn main:app --reload --port 8090
```

### 4. Open the App
Open your browser and navigate to:
[http://localhost:8090](http://localhost:8090)

---
*Note: Make sure your terminal remains open and running while you're using the application.*
