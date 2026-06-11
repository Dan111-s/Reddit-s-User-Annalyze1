# Reddit Research Automation

AI-powered Reddit research tool for Korean content marketing teams.

## Local setup

```bash
npm install
```

Create a `.env` file:
```
VITE_ANTHROPIC_API_KEY=sk-ant-your-key-here
```

Run locally:
```bash
npm run dev
```

## Deploy to Vercel (free)

1. Push this entire folder to a **new GitHub repo**
2. Go to [vercel.com](https://vercel.com) → New Project → Import that repo
3. Framework will auto-detect as **Vite** ✓
4. Under **Environment Variables**, add:
   - Name: `VITE_ANTHROPIC_API_KEY`
   - Value: your key from [console.anthropic.com](https://console.anthropic.com)
5. Click **Deploy**

> Each research run costs ~$0.02–0.05 in Anthropic API credits.
