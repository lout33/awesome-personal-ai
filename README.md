# Awesome Personal AI

A curated list of tools, projects, and systems for building your personal AI assistant.

Not chatbots. Not generic tools. **AI that knows you.**

---

## Contents

- [Life OS](#life-os)
- [Second Brain](#second-brain)
- [AI Coaches](#ai-coaches)
- [Memory Infrastructure](#memory-infrastructure)
- [Digital Twins](#digital-twins)
- [AI Companions](#ai-companions)
- [Resources](#resources)

---

## Life OS

AI that lives on your device, manages your life, knows your context.

| Project | Description | Stars |
|---------|-------------|-------|
| [Clawdbot](https://github.com/clawdbot/clawdbot) | Open source personal AI. Runs on dedicated hardware (Mac Mini, old laptop). Integrates with WhatsApp, Telegram, Slack. Controls your computer, browses web, runs tasks autonomously. | 20K+ |
| [Claude Life Assistant](https://github.com/lout33/claude_life_assistant) | Symbiotic AI system. Two-file pattern (AGENTS.md + NOW.md) where AI knows your personality, goals, psychology. Challenges you, not just serves. | 600+ |
| [OpenWork](https://github.com/AshishKukreti2003/openwork) | Local-first desktop app for non-technical users. Run agentic workflows for home automation, personal apps, life tasks. "Obsidian for agents." | - |
| [Zropi](https://zropi.com) | Personal AI with delayed responses (feels human), proactive messaging, remembers context from weeks ago. Built by ML engineer during burnout. | - |

## Second Brain

Knowledge base + AI. Store everything, find anything, synthesize on demand.

| Project | Description | Stars |
|---------|-------------|-------|
| [Khoj](https://github.com/khoj-ai/khoj) | Self-hosted AI second brain. Semantic search over your notes, PDFs, docs. Custom agents, automations, offline LLM support. Obsidian plugin. | 20K+ |
| [Letta-Obsidian](https://github.com/letta-ai/letta-obsidian) | Vault-aware agents with persistent memory. Your Obsidian notes become AI context. | - |
| [Mem](https://mem.ai) | AI-driven auto-organization. Captures notes, auto-tags, instant search across all content. | - |
| [Saner.AI](https://saner.ai) | AI inbox that captures notes/emails, auto-tags, turns thoughts into tasks. Unified organization. | - |
| [Minimal Second Brain](https://github.com/gokhanarkan/minimal-second-brain) | AI-native Obsidian vault template. Structure for knowledge management with AI integration. | - |

## AI Coaches

Accountability, habits, goals. AI that pushes you to do what you said you'd do.

| Project | Description | Stars |
|---------|-------------|-------|
| [Rocky.ai](https://rocky.ai) | Behavioral science coaching. Detects needs, sets habit goals, daily accountability conversations. | - |
| [Shimmer / Indy](https://shimmer.care/indy) | ADHD support. Structured planning, reflection, tracks what works/doesn't work for you over time. Built on 80K coaching sessions. | - |
| [Summit](https://summit.ai) | Text-based accountability on goals/tasks. 24/7 AI coach. | - |
| [Overlord](https://overlord.ai) | Monitors habits 24/7, blocks distractions, pushes visions into progress. Hardcore accountability. | - |

## Memory Infrastructure

Technical layer for persistent AI memory. Build your own personal AI on top.

| Project | Description | Stars |
|---------|-------------|-------|
| [Letta (MemGPT)](https://github.com/letta-ai/letta) | Stateful agents with persistent memory blocks (persona, human). Auto context management. Serializable agent state. | 20K+ |
| [Mem0](https://github.com/mem0ai/mem0) | Universal memory layer for AI. Stores user profiles across sessions. Hybrid DB (vector + graph). | 25K+ |
| [Honcho](https://github.com/plastic-labs/honcho) | Open source memory infrastructure. Build AI apps that remember users. | - |
| [LangMem](https://langchain.com) | LangChain SDK for persistent user profiles. Long-term memory across threads. | - |
| [Screenpipe](https://github.com/screenpipe/screenpipe) | Searchable screen text and audio history for personal AI through a local API and MCP. Raw history stays local by default; configured cloud services can transmit context. Source-available under the Screenpipe Commercial License. | - |

## Digital Twins

AI that learns to be "you". Your voice, your style, your knowledge.

| Project | Description | Stars |
|---------|-------------|-------|
| [Personal.ai](https://personal.ai) | Learns your voice/style from messages. Builds digital twin. User-owned data. | - |
| [secondbrain-ai](https://github.com/jacklatrobe/secondbrain-ai) | User "theory of mind" (psychology modeling). Stores insights/goals. Self-talk for personality adaptation. | - |
| [my-digital-twin](https://github.com/ammonhaggerty/my-digital-twin) | Professional identity emulation. Life insights. Privacy-focused, local LLM. | - |

## AI Companions

Emotional support, conversation, relationship. AI as friend/mentor.

| Project | Description | Stars |
|---------|-------------|-------|
| [Replika](https://replika.com) | Learns personality over time. Memory of your life/emotions. Emotional support companion. | - |
| [Pi](https://pi.ai) | Remembers conversations. Emotional intelligence. Acts as mentor/coach. By Inflection AI. | - |
| [Dot](https://dot.ai) | Personal AI that knows your context. Learns from interactions. | - |
| [Kin](https://kin.ai) | Emotionally intelligent. Focus on clarity and relationships. | - |

---

## Resources

### Articles
- [I Fed Claude 7 Years of Daily Journals](https://medium.com/swlh/i-fed-claude-7-years-of-daily-journals-it-showed-me-the-future-of-ai-2c13a8d18ef9) - What personalized AI context feels like
- [Clawdbot Memory System Deep Dive](https://avasdream.com/blog/clawdbot-memory-system-deep-dive) - How persistent memory works
- [Build Your Second Brain with Khoj](https://highsignalai.substack.com/p/build-your-second-brain-with-khoj) - Self-hosted setup guide

### Discussions
- [HN: Clawdbot Goes Viral](https://news.ycombinator.com/item?id=46760237) - 389 points, users sharing how they use it
- [HN: How are you LLM-coding?](https://news.ycombinator.com/item?id=46292682) - Developers sharing personal AI workflows
- [HN: Shimmer ADHD Body Doubling](https://news.ycombinator.com/item?id=42009087) - AI for executive function support

### Patterns
- **Two-File System**: AGENTS.md (who you are) + NOW.md (current state) - [Claude Life Assistant](https://github.com/lout33/claude_life_assistant)
- **Memory Bank**: Hierarchical docs synced by agents - [centminmod](https://github.com/centminmod/claude-code-memory-bank)
- **Dedicated Hardware**: Give AI its own device (Mac Mini, old laptop, separate phone number)

---

## What Makes Personal AI Different

| Generic AI | Personal AI |
|------------|-------------|
| Stateless | Remembers you |
| Reactive | Proactive |
| Generic advice | Knows your context |
| Tool | Partner |

---

## Contributing

Know a project that should be here? Open a PR or issue.

Criteria:
- Must be about personal AI (not generic chatbots, not enterprise tools)
- Must have some form of persistent context or memory
- Open source preferred, but notable products included

---

## License

CC0 - Public Domain
