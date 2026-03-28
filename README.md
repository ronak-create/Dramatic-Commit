# 🎭 DRAMATIC COMMITS
### *A Tragedy in Several Pushes*

> *"To commit, or not to commit — that is the merge conflict."*

---

## ACT I — What Hath Been Wrought

You wrote `fixed button`. You pushed. You moved on.

But the button wept. The git log wept. Your future self, six months hence, staring at `git blame` at 2am — **they wept the most.**

**Dramatic Commits** takes your shameful, lazy, three-word commit messages and transforms them into the masterpieces they always deserved to be. Shakespearean tragedy. Villain monologues. Existential dread. Indian meme chaos. All of it. For a button fix.

---

## ACT II — The Cast of Characters

| File | Role |
|------|------|
| `public/index.html` | The stage. The spotlight. The drama itself. |
| `api/proxy.js` | The backstage crew. Talks to Groq so your API key isn't left dying in the spotlight. |
| `vercel.json` | The director. Routes everything. Gets no credit. |
| `package.json` | The contract. Vercel won't even look at you without it. |

---

## ACT III — Deploying (The Rising Action)

### Prerequisites
- A [Groq API key](https://console.groq.com) *(free, takes 30 seconds, no excuse)*
- A GitHub account
- Vercel account *(also free)*

### The Steps

```bash
# Clone the repo into your life
git clone https://github.com/yourusername/dramatic-commits
cd dramatic-commits

# Push it to your GitHub (Vercel needs this)
git add .
git commit -m "feat: add dramatic commits"   # ironic, isn't it
git push
```

Then go to **[vercel.com](https://vercel.com)** → **Add New Project** → import your repo.

**Before you hit Deploy** — set your environment variable:

```
GROQ_API_KEY=your_key_here
```

> *Settings → Environment Variables → Add → Redeploy if you missed it.*

Click **Deploy**. Wait 30 seconds. Weep tears of joy.

---

### BLah Blah Blah! Let's do better

Go to vercel deployed link int the repo description and try it for free... no API brainrots.
 
---

## And here's the link for some lazy ones

[Do Better for your commits](https://dramatic-commit.vercel.app)

## ACT IV — The Moods (Choose Your Suffering)

| Mood | What It Does To Your Soul |
|------|--------------------------|
| 🎭 **Tragedy** | Shakespeare himself would shed a single tear |
| 🌑 **Existential** | Does the button even exist? Do *you*? |
| 💔 **Romance** | The CSS and the HTML were in love, once |
| 💥 **Action Hero** | Every bug fix is a one-liner before an explosion |
| 😤 **Passive Aggressive** | *"Fixed the thing that was apparently my job to fix"* |
| 🦹 **Villain** | You didn't fix the bug. You *chose* to spare it. |

---

## ACT V — How It Works (The Technical Monologue)

```
Your Browser
    │
    │  POST /api/proxy  (your commit, the mood, the chaos)
    ▼
Vercel Serverless Function
    │
    │  Forwards to Groq API  (llama-3.3-70b-versatile)
    │  with your secret GROQ_API_KEY 🔒
    ▼
The LLM
    │
    │  Returns something magnificent
    ▼
Your Screen
    │
    ▼
  git commit -m "THE STARS THEMSELVES RECOIL FROM THIS MERGE"
```

Your API key never touches the browser. It lives in Vercel's servers, in the dark, where it belongs.

---

## EPILOGUE — Contributing

Found a bug? Open an issue. But write the issue title dramatically, or it will be closed without mercy.

Found a feature idea? PRs welcome. The codebase is a single HTML file and a 20-line proxy. You can do this.

---

## IN MEMORIAM

*For every `fix bug`, `update stuff`, and `asdfgh` commit that came before.*
*You deserved better. We all did.*

---

<p align="center">
  <sub>Built with Groq + Llama 3.3 · Deployed on Vercel · Cried over by developers everywhere</sub>
</p>