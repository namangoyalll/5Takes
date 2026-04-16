# 5 Takes

Ask any question. Get responses from 5 very different AI personalities.

## Personalities
- 🧠 **Engineer** — Logical, structured, practical
- 😎 **Savage Friend** — Funny, blunt, slightly roasting
- 💔 **Overthinker** — Dramatic, emotional, worst-case thinking
- 🧘 **Therapist** — Calm, supportive, balanced
- 💼 **Corporate HR** — Formal, professional, corporate tone

---

## Deploy to Vercel (recommended)

### 1. Push to GitHub
Create a new repo on GitHub and push this folder to it.

### 2. Import on Vercel
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **Add New → Project**
3. Import your GitHub repo
4. Under **Environment Variables**, add:
   - Key: `ANTHROPIC_API_KEY`
   - Value: your key from [console.anthropic.com](https://console.anthropic.com)
5. Click **Deploy**

You'll get a live URL like `https://5takes.vercel.app` in about 60 seconds.

---

## Run locally

```bash
npm install
cp .env.example .env.local
# edit .env.local and add your ANTHROPIC_API_KEY
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).
