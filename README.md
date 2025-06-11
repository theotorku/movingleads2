AI-powered lead scoring system for the moving industry.

## Features

- Validates and scores incoming leads
- Uses OpenAI for intelligent scoring
- Stores leads in Supabase
- Dockerized for deployment

## Usage

```bash
docker build -t moving-leads-ai .
docker run --env-file .env -p 8000:8000 moving-leads-ai
```

Access API at: `http://localhost:8000/leads/score`

---

## .env example

```
SUPABASE_URL=https://your-project.supabase.co
SUPABASE_KEY=your-anon-or-service-role-key
OPENAI_API_KEY=your-openai-key
```
