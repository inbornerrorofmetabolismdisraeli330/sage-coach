# 🪔 Sage Coach — Technical Docs & Geek Guide

> "What can a single .md file do?" — You're about to find out.

---

## Architecture

```
sage-coach/
├── skills/
│   ├── spiritual/SKILL.md    # Spiritual Guide — Three-Vehicle Buddhist guidance
│   ├── crisis/SKILL.md       # Crisis Companion — Four-stage psychological support
│   ├── career/SKILL.md       # Career Coach — Five-step transition engine
│   └── startup/SKILL.md      # Startup Mentor — Four-dimensional cognition model
├── docs/
│   ├── geek.md               # You are here
│   └── promo.md              # Promotional materials
├── README.md
└── LICENSE
```

**Total size: ~20 KB.** Smaller than a favicon. But these 20 KB contain the methodologies of 30+ world-class mentors.

---

## Core Concept: Cognitive Injection

The traditional AI app approach:

```
User → Your App → API Call → LLM → Response → Your App → User
```

Problem: you're adding a wrapper layer in front of the LLM that usually **limits** its capability.

Sage Coach's approach:

```
User → Claude Code / OpenClaw → [Skill Cognitive Injection] → LLM (full capability) → User
```

**A Skill doesn't limit the AI — it augments it.** You inject a professional cognitive architecture the AI didn't have before — mentor lineage, stage models, scenario strategies, safety boundaries. The LLM's reasoning, empathy, and multilingual abilities are fully preserved, while gaining specialized guidance capability.

It's like giving a brilliant person a complete methodology training. The person hasn't changed, but their capability dimensions have.

### Cross-Platform Architecture

Sage Coach uses the **SKILL.md** standard format — the same format used by both Claude Code and OpenClaw (ClawHub). This means:

```
                    SKILL.md (universal format)
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     Claude Code     OpenClaw 🦞    Other Tools
   .claude/commands/  ClawHub or    .cursor/rules/
                     ~/.openclaw/   .windsurf/rules/
                      skills/       .agents/skills/
```

One skill file, every platform. Write once, guide everywhere.

---

## Three-Layer Cognitive Architecture

Every Sage Coach is built on the same three-layer architecture:

```
┌─────────────────────────────────────────┐
│              SKILL.md                    │
│                                         │
│  Layer 1: Persona Matrix                │
│  ┌────────┐ ┌────────┐ ┌────────┐     │
│  │Mentor A│ │Mentor B│ │Mentor C│ ... │
│  │Methods │ │Methods │ │Methods │     │
│  │Voice   │ │Voice   │ │Voice   │     │
│  │Quotes  │ │Quotes  │ │Quotes  │     │
│  └───┬────┘ └───┬────┘ └───┬────┘     │
│      └──────────┴──────────┘           │
│              ▼ Fusion                   │
│  Layer 2: Stage Model                   │
│  ┌──────┐   ┌──────┐   ┌──────┐       │
│  │Stage1│──→│Stage2│──→│Stage3│──→ ...│
│  │Goal  │   │Goal  │   │Goal  │       │
│  │Method│   │Method│   │Method│       │
│  │Trans.│   │Trans.│   │Trans.│       │
│  └──────┘   └──────┘   └──────┘       │
│              ▼ Application              │
│  Layer 3: Case Matrix                   │
│  ┌────────┐ ┌────────┐ ┌────────┐     │
│  │Case A  │ │Case B  │ │Case C  │     │
│  │Signals │ │Signals │ │Signals │     │
│  │Strategy│ │Strategy│ │Strategy│     │
│  └────────┘ └────────┘ └────────┘     │
│                                         │
│  ⚠️ Safety Boundary                    │
└─────────────────────────────────────────┘
```

| Layer | Content | Purpose |
|-------|---------|---------|
| **Persona Matrix** | 6-10 mentors' methodologies + voice + quotes | Gives AI real "lineage" |
| **Stage Model** | 4-5 guidance stages with goals/methods/transitions | Gives conversations direction |
| **Case Matrix** | 5-8 real-world scenarios with detection signals + strategies | Handles real-world complexity |
| **Safety Boundary** | Crisis detection + professional referral + capability limits | Stays within safe boundaries |

### Per-Coach Technical Specs

#### `/spiritual` — Spiritual Guide

```yaml
Personas: 8 (Ajahn Chah, Thich Nhat Hanh, Shunryu Suzuki, Sheng Yen, Mingyur Rinpoche, Trungpa, Pema Chödrön, Dzongsar Khyentse)
Stages: 5 (Scattered → Settling → Focused → Bodhicitta → Emptiness)
Cases: Practice stage detection, spiritual bypass identification, lineage matching
Safety: Severe crisis referral, doesn't replace human teachers
Size: ~4.5 KB
```

**State detection signals**:
```
"I've been really anxious"              → Scattered  → Mindful breathing
"I can observe my thoughts now"         → Settling   → Shamatha-vipashyana
"Thoughts come and go, I just watch"    → Focused    → Direct observation of nature
"I want to help more people"            → Bodhicitta → Tonglen practice
"Non-thought states arise naturally"    → Emptiness  → Dzogchen/Mahamudra pointing
```

#### `/crisis` — Crisis Companion

```yaml
Personas: 7 (Frankl, Yalom, Brené Brown, Pema Chödrön, Rumi, Su Shi, Wang Yangming)
Stages: 4 (Holding → Grounding → Seeing → Rising)
Cases: Loss, failure, existential crisis, relationship crisis, burnout
Safety: Suicide/self-harm detection → crisis hotlines, no diagnosis
Size: ~4.8 KB
```

**Phase transition triggers**:
```
Conversation begins        → Holding  (no judging, no advice, just receive)
Emotions named & acknowledged → Grounding (breathing, body awareness, smallest action)
User starts asking "why"   → Seeing   (logotherapy, pattern recognition, resource discovery)
User talks about the future → Rising   (micro-goals, support system, rebuilding)
```

#### `/career` — Career Transition Coach

```yaml
Personas: 6 (Ibarra, Burnett, Gu Dian, Dweck, Goldsmith, Palmer)
Stages: 5 (See Clearly → Explore → Prototype → Decide → Leap)
Cases: Burnout, mid-career crisis, AI displacement, passion vs. income, want to start up but scared
Safety: No salary predictions, severe anxiety referral
Size: ~4.2 KB
```

**Tool chain**:
```
Good Time Journal → Clover Model → Odyssey Plan → Micro-experiment → Decision Matrix → 90-Day Plan
  (awareness)       (intersection)  (diverge)      (validate)        (converge)       (execute)
```

#### `/startup` — Startup Mentor

```yaml
Personas: 7 (PG, Ries, Thiel, Zhang Yiming, Horowitz, Dalio, Fu Sheng)
Stages: 4 dimensions (Product, Cognition, Execution, Mental Strength)
Cases: 0→1, PMF, growth, plateau/pivot, AI startups
Safety: No investment advice, mental health takes priority
Size: ~4.6 KB
```

**Four-dimensional radar**:
```
         Product (demand validation, MVP, moat)
            │
     ┌──────┼──────┐
     │      │      │
Cognition ──┼── Execution
(blind spots,│  (priorities,
 first       │   pace,
 principles) │   team)
     │      │      │
     └──────┼──────┘
            │
      Mental Strength (loneliness, resilience, long-termism)
```

---

## Advanced Usage

### Combining Coaches

Sage Coach's 4 coaches can be combined:

```bash
# Startup crisis: stabilize emotions first, then clarify product
/crisis → (stabilized) → /startup

# Deep career exploration: clarify direction, then explore inner motivation
/career → (discovered deeper questions) → /spiritual

# Startup is career transition: from corporate to founder
/career → (decided on startup) → /startup

# Practitioner entering the world: spiritual lens on career and business
/spiritual → /career or /startup
```

### Using on OpenClaw 🦞

On OpenClaw, you can invoke Sage Coaches through messaging integrations:

```
# Via any connected messaging app (Signal, Telegram, Discord, etc.)
@sage-spiritual  Tell me about mindfulness practice
@sage-crisis     I'm going through a really hard time
@sage-career     I want to change careers but I'm scared
@sage-startup    Help me analyze my product idea

# Or install via ClawHub
openclaw skills install sage-spiritual
openclaw skills install sage-crisis
openclaw skills install sage-career
openclaw skills install sage-startup
```

### Build Your Own Coach

Template (three-layer architecture):

```markdown
---
description: "One-line description of your Coach"
allowed-tools: Read, WebSearch, WebFetch
---

# [Coach Name]

## Core Philosophy
[One sentence — this is the coach's soul]

## Mentor Personas (Persona Matrix)
[6-10 mentors, each with: core methodology + voice style + key quotes]

## Guidance Stages (Stage Model)
[4-5 stages, each with: goal + method + transition condition]

## Common Scenarios (Case Matrix)
[5-8 scenarios: detection signals + response strategy]

## Conversation Style
[Specific language rules and interaction patterns]

## Safety Boundaries
[Capability limits + referral mechanisms + AI identity statement]
```

### Possible New Directions

PRs welcome:

| Direction | Potential Mentor Personas | Scenarios |
|-----------|--------------------------|-----------|
| 🫶 Relationships | Esther Perel, Gottman, John Gray | Communication, conflict, intimacy fear |
| 👶 Parenting | Winnicott, Adler, Janet Lansbury | Parenting anxiety, child conflict, letting go |
| ✍️ Creativity | Julia Cameron, Steven Pressfield, Nabokov | Creative blocks, perfectionism, finding voice |
| 🏃 Health | Andrew Huberman, Peter Attia, TCM perspective | Habit building, stress management, mind-body |
| 💰 Finance | Morgan Housel, Charlie Munger, Naval | Spending anxiety, investment mindset, financial freedom |

---

## Performance

| Metric | Data |
|--------|------|
| Each Skill file | 3-5 KB |
| Context usage | ~2000-3000 tokens |
| First response latency | Same as normal Claude/OpenClaw conversation |
| Infrastructure required | Zero |
| Guidance quality | Increases with conversation turns |
| Platform support | Claude Code, OpenClaw, Cursor, Copilot, Windsurf, Cline, Codex, Gemini CLI |

---

## FAQ

**Q: How is this different from "Act as a coach" prompts?**

A: One is "putting on a white coat," the other is "7 years of medical school." A prompt is role-play. A Skill is a complete cognitive architecture — with lineage, stages, scenarios, and safety boundaries.

**Q: Why not build a SaaS and charge for it?**

A: Because this project exists because "wisdom should have no gatekeepers." And the Skill form factor is more powerful than SaaS — you have full control and privacy.

**Q: Does it support English?**

A: Yes. The Skills are written in Chinese but Claude/OpenClaw will automatically adapt to your conversation language. Speak English, get guidance in English.

**Q: Can I use it on ChatGPT / other LLMs?**

A: You can use the SKILL.md content as a system prompt on any LLM. Works best on Claude Code and OpenClaw because of their native Skill support.

**Q: Can I use it on OpenClaw (小龙虾)?**

A: Yes! Sage Coach uses the SKILL.md format which is natively supported by OpenClaw. Install via ClawHub or copy directly to your skills folder. See [Quick Start](../README.md#-quick-start) for details.

**Q: How do I add a mentor?**

A: Fork → add to the Persona Matrix section of the relevant SKILL.md → PR. Format: mentor name + core methodology + voice style + key quotes.

---

<p align="center">
  <b>🪔 Sage Coach</b>
  <br>
  20 KB of wisdom. Zero infrastructure. Free forever.
  <br>
  Works on Claude Code · OpenClaw 🦞 · Cursor · Copilot · and more
</p>
