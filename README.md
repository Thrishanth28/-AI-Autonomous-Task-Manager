# 🤖 AI Autonomous Task Manager

A powerful autonomous planning system built with **n8n** and **Google Gemini** where **5 specialized AI agents work in sequence** to take any goal and break it down into a complete, executable action plan with step-by-step guides, priority matrices, timelines and milestones.

Just type any goal in the chat — the system autonomously analyzes it, breaks it into 8 specific tasks, prioritizes them, creates a week-by-week timeline, writes detailed execution guides and generates a comprehensive final report.

**Tested:** "Launch my AI startup in 30 days" → 31,007 tokens of structured intelligence in 33 seconds ✅

---

## 🎯 How It Works

```
You type: "Launch my AI startup in 30 days"
                    │
                    ▼
        ┌───────────────────────┐
        │   GOAL INPUT          │  Detects goal type
        │   PROCESSOR           │  Identifies timeframe
        └──────────┬────────────┘
                   │
                   ▼
        ┌───────────────────────┐
        │   GOAL ANALYZER       │  SMART goal analysis
        │   AGENT               │  Success metrics
        │                       │  Key obstacles
        └──────────┬────────────┘
                   │
                   ▼
        ┌───────────────────────┐
        │   TASK BREAKDOWN      │  8 specific tasks
        │   AGENT               │  Critical path
        │                       │  Quick wins
        └──────────┬────────────┘
                   │
                   ▼
        ┌───────────────────────┐
        │   PRIORITY PLANNING   │  Eisenhower Matrix
        │   AGENT               │  Week-by-week timeline
        │                       │  Day 7/14/21/30 milestones
        └──────────┬────────────┘
                   │
                   ▼
        ┌───────────────────────┐
        │   EXECUTION           │  Step-by-step guides
        │   AGENT               │  Tools and resources
        │                       │  Common mistakes to avoid
        └──────────┬────────────┘
                   │
                   ▼
        ┌───────────────────────┐
        │   MASTER REVIEW       │  Synthesizes everything
        │   AGENT               │  Creates final report
        │                       │  11 structured sections
        └──────────┬────────────┘
                   │
                   ▼
        COMPLETE AUTONOMOUS
        EXECUTION REPORT ✅
```

---

## 📊 What Each Agent Does

### Agent 1 — Goal Analyzer
- Goal clarity score out of 10
- Exact goal interpretation — what success looks like
- Goal complexity rating
- 5 key success factors
- 4 potential obstacles
- Resources needed — skills, tools, time, money
- 3 measurable success metrics
- SMART goal rewrite — Specific, Measurable, Achievable, Relevant, Time-bound

### Agent 2 — Task Breakdown
- Exactly 8 specific executable tasks
- Each task has: name, description, deliverables, skills, dependencies, time estimate, difficulty
- Critical path — 3 most important tasks
- Quick wins — 2 fastest tasks for early momentum

### Agent 3 — Priority Planning
- Eisenhower Matrix — Urgent/Important quadrants for all 8 tasks
- Week-by-week timeline (Week 1 through 4)
- Daily schedule template — Morning, Afternoon, Evening
- 4 key milestones at Day 7, Day 14, Day 21, Day 30

### Agent 4 — Execution Agent
- Detailed 5-step execution guide for the top 3 most critical tasks
- Tools and resources needed for each task
- 3 common mistakes to avoid per task
- Pro tips from expert experience
- Definition of done — exactly when each task is complete
- 5 execution mindset principles

### Agent 5 — Master Review Agent
- Complete synthesized report with 11 sections
- All data from all 4 agents combined
- Risk assessment with mitigation strategies
- Full resources and tools list
- First action to take right now
- Motivational closing paragraph

---

## 📸 Sample Output

**Input:** `Launch my AI startup in 30 days`

```
# AI AUTONOMOUS TASK MANAGER REPORT

Goal: Launch my AI startup in 30 days
Timeframe: 30 days
Agents: Goal Analyzer, Task Breakdown,
        Priority Planning, Execution,
        Master Review

## GOAL INTELLIGENCE
SMART Goal: Launch a minimum viable AI
automation tool targeting SMBs, achieve
3 paying customers, $500 MRR by Day 30.

Goal Clarity Score: 6/10
Goal Complexity: Very Complex

Key Success Factors:
1. Hyper-focused MVP — build the smallest
   thing that delivers real value
2. Pre-existing AI knowledge and tools
3. Rapid prototyping capability
4. Clear target market definition
5. Exceptional personal drive

## YOUR 8 TASKS

Task 1: Validate the market idea (2 days)
Task 2: Define MVP scope tightly (1 day)
Task 3: Build core MVP product (7 days)
Task 4: Create landing page (1 day)
Task 5: Set up payment system (1 day)
Task 6: Launch on Product Hunt (1 day)
Task 7: Run cold outreach campaign (ongoing)
Task 8: Onboard and collect feedback (ongoing)

Critical Path: Tasks 1, 3, 7
Quick Wins: Tasks 4, 5

## PRIORITY — EISENHOWER MATRIX

Quadrant 1 — Do First:
→ Market validation
→ MVP build
→ Cold outreach

Quadrant 2 — Schedule:
→ Landing page
→ Payment setup

## WEEK BY WEEK TIMELINE

Week 1 — Foundation:
→ 20 customer discovery conversations
→ Define exact MVP scope
→ Set up development environment

Week 2 — Build:
→ Build core AI feature
→ Internal testing
→ Create landing page

Week 3 — Launch Prep:
→ Beta testers
→ Product Hunt listing
→ Outreach campaign

Week 4 — Launch:
→ Public launch
→ First paying customers
→ Feedback and iteration

## KEY MILESTONES
Day 7: Market validated — 5 discovery calls done
Day 14: MVP built and tested internally
Day 21: Landing page live, 3 beta users
Day 30: Launched, first paying customer

## TOP 3 TASKS — STEP BY STEP GUIDES

Task 1: Validate Market
Step 1: List 20 potential customers on LinkedIn
Step 2: Send personalised DM to all 20
Step 3: Conduct 5 discovery calls this week
Step 4: Identify the 1 pain point mentioned most
Step 5: Write a one-page problem statement

Pro Tip: The goal is NOT to pitch — it is to
listen. Ask: What is your biggest frustration
with current AI tools?

Definition of Done: 5 conversations completed,
1 specific pain point validated by 3+ people.

## YOUR FIRST ACTION RIGHT NOW
Open LinkedIn. Search for founders and
engineering managers in your target market.
Send 5 personalised messages in the next
30 minutes. Do not overthink. Just start.

## RISK ASSESSMENT
Risk 1: Scope creep — build more than MVP
Mitigation: Write MVP scope on paper and
           refuse to add anything not on it

Risk 2: No paying customers by Day 30
Mitigation: Pre-sell before building —
           ask for payment before launch

...
```

---

## 🚀 Quick Start

### Prerequisites
- n8n installed (cloud or self-hosted)
- Google Gemini API key (free at [aistudio.google.com](https://aistudio.google.com))

### Get Free Gemini API Key
1. Go to [aistudio.google.com](https://aistudio.google.com)
2. Sign in with Google account
3. Click **Get API Key** then **Create API Key**
4. Copy the key ✅

### Import and Run
1. Clone this repo
   ```bash
   git clone https://github.com/Thrishanth28/AI-Autonomous-Task-Manager.git
   cd AI-Autonomous-Task-Manager
   ```
2. Open your n8n dashboard
3. Go to **Workflows** → **Import from File**
4. Select `AI_Autonomous_Task_Manager.json`
5. Connect **Google Gemini credentials** to all 5 Gemini nodes:
   - Gemini — Goal Analyzer
   - Gemini — Task Breakdown
   - Gemini — Priority Planning
   - Gemini — Execution
   - Gemini — Master Review
6. Click **Chat** button at bottom left
7. Type any goal and get your complete action plan! ✅

---

## 🧪 Goals to Test

```
→ Launch my AI startup in 30 days
→ Learn Python programming in 4 weeks
→ Get a remote internship in 2 weeks
→ Build and launch a SaaS product in 60 days
→ Grow my LinkedIn to 1000 followers in 30 days
→ Build a freelance career in 45 days
→ Write and publish a book in 90 days
→ Get fit and lose 10kg in 3 months
```

---

## 🏗️ Project Structure

```
AI-Autonomous-Task-Manager/
├── AI_Autonomous_Task_Manager.json   ← n8n workflow (16 nodes)
└── README.md
```

---

## 🔧 Technical Architecture

### Node Count: 16 Nodes
| Node Type | Count | Purpose |
|-----------|-------|---------|
| Chat Trigger | 1 | Receives user goal |
| Code Nodes | 6 | Input processing + data storage |
| chainLlm Agents | 5 | AI agents |
| Gemini Models | 5 | Language model for each agent |

### Why chainLlm
All agents use `chainLlm` (Basic LLM Chain) nodes instead of `conversationalAgent`. This ensures clean plain text output without ReAct JSON wrapping — reliable and error-free in all downstream code nodes.

### Sequential Data Flow
Each agent's output is stored in a code node and passed forward to the next agent. This means:
- Every agent has access to all previous agents' work
- The Master Review Agent receives all 4 data sources simultaneously
- No parallel merge errors — clean sequential execution every time

### Goal Type Detection
The Goal Input Processor automatically detects goal categories:
- **creation** — launch, build, create, develop, start
- **learning** — learn, study, master
- **growth** — grow, scale, increase, improve
- **planning** — plan, organize, manage
- **marketing** — market, promote, sell

---

## 💡 Real World Use Cases

- 🚀 **Entrepreneurs** — Plan startup launches step by step
- 🎓 **Students** — Break down complex learning goals
- 💼 **Professionals** — Plan career transitions and skill development
- 📊 **Project Managers** — Generate project plans from high-level goals
- 🏃 **Anyone** — Turn any ambiguous goal into a clear action plan

---

## 📊 Performance

| Metric | Result |
|--------|--------|
| Total tokens | 31,007 per run |
| Execution time | ~33 seconds |
| Sections in report | 11 |
| Tasks generated | 8 |
| Agents used | 5 |

---

## 🔐 Security Note

Never commit real API keys to GitHub.
All credentials are configured inside n8n credential manager.
Use environment variables for any Python integrations.

---

## 🙋‍♂️ Built By

**S. Thrishanth Reddy** — AI Automation Developer

2nd year B.Tech CSE student at SRM University Haryana.
Built 15+ real-world AI automation projects in 3 weeks independently.
Specializes in multi-agent AI systems using n8n and Google Gemini.

Skills: n8n · Google Gemini API · Prompt Engineering · Python · JavaScript · HTML · CSS · SQL

📎 [LinkedIn](https://linkedin.com/in/thrishanth-reddy) | 🔗 [GitHub](https://github.com/Thrishanth28)

---

## 📄 License

MIT License — free to use, modify and share!
