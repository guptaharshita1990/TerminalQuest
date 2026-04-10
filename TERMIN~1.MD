# Terminal Quest 🎮 — Course Plan
### A gamified app to master Git, Bash & Claude Code

---

## 🏗️ Build Recommendation: Use Cowork (this tool)

**Why Cowork, not Claude Code?**

This is actually a classic chicken-and-egg problem: you'd need to learn the terminal *before* you could use Claude Code, but Claude Code is what you want to learn. So the right approach is:

- **Phase 1:** Build the app *here* in Cowork. No terminal needed. Works on phone + laptop immediately as a web app.
- **Phase 2:** Once you finish Level 3–4 of the course, *you'll have enough skill* to open the same project in Claude Code and extend it yourself. That's the graduation moment.

Cowork can produce a single-file React app (works in any browser, phone or laptop) with missions, progress tracking, and a gamified UI — everything you need.

---

## 📋 App Concept: "Terminal Quest"

A mobile-friendly web app structured like a game:
- 🗺️ **World map** view showing 5 Levels (unlocked progressively)
- 🎯 **Missions** inside each level (mini lessons + a quiz challenge)
- ⭐ **XP & badges** awarded on completion
- 📖 **Quick reference cheat sheet** always accessible
- 💡 **"Ask Claude" tip button** (links to Claude.ai for follow-up questions)

---

## 🎓 Course Structure: 5 Levels

---

### Level 1 — "The Awakening" 🌱
**Theme:** What even IS the terminal?
**Missions:**

| # | Mission | What you learn |
|---|---------|---------------|
| 1.1 | Open the terminal | Mac: Terminal app / Windows: PowerShell or WSL |
| 1.2 | Know where you are | `pwd` — prints your current folder path |
| 1.3 | Look around | `ls` — lists files and folders |
| 1.4 | Move around | `cd folderName`, `cd ..`, `cd ~` |
| 1.5 | Make things | `mkdir` (create folder), `touch` (create file) |
| 1.6 | Read things | `cat filename.txt` — print file contents |
| 1.7 | Boss Challenge ⚔️ | Navigate to Desktop, create a folder called `my-quest`, create a file inside it |

**XP reward: 100 pts + "Explorer" badge**

---

### Level 2 — "The Time Machine" ⏳
**Theme:** Git & GitHub — save your work like a pro
**Missions:**

| # | Mission | What you learn |
|---|---------|---------------|
| 2.1 | What is Git? | Version control explained simply (like saving checkpoints in a game) |
| 2.2 | Install Git | Check with `git --version` |
| 2.3 | Set up identity | `git config --global user.name` and `user.email` |
| 2.4 | Your first repo | `git init` — turn any folder into a Git project |
| 2.5 | Track changes | `git add .` → `git commit -m "message"` |
| 2.6 | See your history | `git log`, `git status`, `git diff` |
| 2.7 | Connect to GitHub | Create a GitHub account → `git remote add origin <url>` → `git push` |
| 2.8 | Clone a project | `git clone <url>` — copy someone's repo to your laptop |
| 2.9 | Boss Challenge ⚔️ | Create a repo, make 3 commits, push to GitHub |

**XP reward: 200 pts + "Time Traveler" badge**

---

### Level 3 — "The Ninja Path" 🥷
**Theme:** Intermediate Bash — become fluent
**Missions:**

| # | Mission | What you learn |
|---|---------|---------------|
| 3.1 | Power search | `grep "word" filename` — find text inside files |
| 3.2 | File detective | `find . -name "*.txt"` — find files by pattern |
| 3.3 | Chain commands | Pipes `|` — send output of one command into another |
| 3.4 | Save output | `>` and `>>` — write command output to a file |
| 3.5 | Environment | What are environment variables? `.env` files |
| 3.6 | Your profile | `.bashrc` / `.zshrc` — make commands stick across sessions |
| 3.7 | Permissions | `chmod`, `ls -la` — what do file permissions mean? |
| 3.8 | Package managers | `npm`, `pip`, `brew` — installing tools from the terminal |
| 3.9 | Boss Challenge ⚔️ | Write a bash alias, add it to your shell profile, use it |

**XP reward: 300 pts + "Ninja" badge**

---

### Level 4 — "The AI Forge" 🤖
**Theme:** Claude Code in terminal — your AI coding partner
**Missions:**

| # | Mission | What you learn |
|---|---------|---------------|
| 4.1 | What is Claude Code? | It's Claude, but in your terminal — delegates coding tasks |
| 4.2 | Install Claude Code | `npm install -g @anthropic-ai/claude-code` |
| 4.3 | First conversation | Running `claude` and having your first terminal chat |
| 4.4 | Give it a task | Ask Claude Code to create a file, explain a script, fix a bug |
| 4.5 | Cowork vs Claude Code | Cowork = file/doc tasks in a GUI. Claude Code = coding in your project folder |
| 4.6 | Can I use bash commands? | Yes! Claude Code can *run* bash for you AND explain commands |
| 4.7 | Slash commands | What `/help`, `/clear`, `/cost` do inside Claude Code |
| 4.8 | Boss Challenge ⚔️ | Use Claude Code to explain and improve a real file in your project |

**XP reward: 400 pts + "AI Forge" badge**

---

### Level 5 — "Pro Mode" 💎
**Theme:** Token management, Claude Pro, advanced tips
**Missions:**

| # | Mission | What you learn |
|---|---------|---------------|
| 5.1 | What are tokens? | How LLMs "read" text — tokens = words/pieces of words |
| 5.2 | Context window | Why Claude forgets things in long sessions |
| 5.3 | Claude Pro vs API | Pro = unlimited Claude.ai chat. API = pay-per-token for Claude Code |
| 5.4 | Does Claude Pro help with terminal? | No — Claude Code terminal uses API billing separately |
| 5.5 | Reduce token use | Use `/clear` often, write focused prompts, avoid pasting large files |
| 5.6 | Use `.claudeignore` | Tell Claude Code to skip certain files (like node_modules) |
| 5.7 | CLAUDE.md file | A file that gives Claude persistent instructions about your project |
| 5.8 | Boss Challenge ⚔️ | Set up a real project with CLAUDE.md, .claudeignore, and make a meaningful commit |

**XP reward: 500 pts + "Pro" badge + 🏆 Course Completion Certificate**

---

## 🗺️ Learning Path Summary

```
Level 1 (Terminal Basics)
    ↓
Level 2 (Git & GitHub)
    ↓
Level 3 (Intermediate Bash)
    ↓
Level 4 (Claude Code in Terminal)
    ↓
Level 5 (Tokens, Pro, Advanced Tips)
    ↓
🎓 Graduate: You can now build apps with Claude Code yourself!
```

---

## 📱 App Features to Build

- Mobile-first design (works perfectly on phone)
- Mission cards with lock/unlock logic
- XP bar and badge showcase
- Quick-reference cheat sheet (searchable)
- Progress saved in browser (localStorage)
- Each mission has: Explanation → Example → Mini-quiz → Mark complete

---

## 🛠️ What to Build First

1. **Start in Cowork** → build the full app as a React web app
2. **Open in browser on phone** → use it daily as you practice
3. **At Level 4** → you'll know enough to open the project in Claude Code
4. **Level 5 graduation** → extend and deploy the app yourself

*Estimated build time in Cowork: 1–2 sessions*
*Estimated course completion time: 2–4 weeks of daily 15-min practice*
