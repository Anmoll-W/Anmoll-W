<img src="docs/header.png" alt="Building AI Products" width="100%">

# 👋 Hi, I'm Anmoll

I scaled a platform to 90M users.
I'm still figuring out what great product looks like.

Senior PM with 8 years building across consumer scale, creator ecosystems, and AI infrastructure. Grew ZZAZZ from 1M to 90M MAU across 70 countries. Now at LinkWhisper, shaping AI-powered SEO products and using Claude Code to spec, build, and ship internal tools without waiting on engineering cycles.

I build Claude Code skills for product managers: runnable tools that go from spec to verdict in one command.

### Stack I Reach For
![Claude Code](https://img.shields.io/badge/Claude_Code-1e293b?style=flat-square&logo=anthropic&logoColor=white) ![Claude API](https://img.shields.io/badge/Claude_API-1e293b?style=flat-square&logo=anthropic&logoColor=white) ![Claude Design](https://img.shields.io/badge/Claude_Design-1e293b?style=flat-square&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-1e293b?style=flat-square&logo=googlegemini&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-1e293b?style=flat-square&logoColor=white) ![Hermes Agent](https://img.shields.io/badge/Hermes_Agent-1e293b?style=flat-square&logoColor=white) ![ChatGPT](https://img.shields.io/badge/ChatGPT-1e293b?style=flat-square&logo=openai&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-1e293b?style=flat-square&logo=cursor&logoColor=white) ![Lovable](https://img.shields.io/badge/Lovable-1e293b?style=flat-square&logoColor=white) ![NotebookLM](https://img.shields.io/badge/NotebookLM-1e293b?style=flat-square&logo=google&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-1e293b?style=flat-square&logo=openai&logoColor=white) ![Runway](https://img.shields.io/badge/Runway-1e293b?style=flat-square&logoColor=white) ![Mixpanel](https://img.shields.io/badge/Mixpanel-1e293b?style=flat-square&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1e293b?style=flat-square&logo=postgresql&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-1e293b?style=flat-square&logo=figma&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-1e293b?style=flat-square&logo=jira&logoColor=white) ![Obsidian](https://img.shields.io/badge/Obsidian-1e293b?style=flat-square&logo=obsidian&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-1e293b?style=flat-square&logo=supabase&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-1e293b?style=flat-square&logo=vercel&logoColor=white) ![Google Stitch](https://img.shields.io/badge/Google_Stitch-1e293b?style=flat-square&logo=google&logoColor=white)

---

### 🔨 Currently Building

- 🧰 **prompt-generator-skill**
  **Problem:** Vague prompts force the model to guess tone, structure, and format. Every guess is variance and wasted tokens.
  **Built:** Open-source Claude Code skill that turns a role description into a production-ready XML prompt. ~75% token reduction.
  **Why it matters:** [→ install](https://github.com/Anmoll-W/prompt-generator-skill)

- 🧠 **pg-startup-eval**
  **Problem:** AI feedback on startup ideas is encouraging mush. No framework rigor, no forced verdict.
  **Built:** Claude Code skill that runs any idea through 17 investor frameworks (PG, Thiel, Sequoia, Mom Test) and forces a Strong/Weak/Pivot verdict.
  **Why it matters:** [→ install](https://github.com/Anmoll-W/pg-startup-eval)

- 🤖 **AI support automation**
  **Problem:** LinkWhisper support tickets required manual triage and back-and-forth that didn't scale.
  **Built:** Claude-powered workflows that cut ticket resolution effort 50%.
  **Why it matters:** [→ build story](https://github.com/Anmoll-W/blog)

---

### 📋 Case studies

- 🗺️ **ChalotripBot**: Telegram bot for group trip planning, budgets, and bill splits → [build story](https://github.com/Anmoll-W/blog/blob/main/series/building-chalotripbot.md)
- 🛒 **BlinkFit**: peak-hour decision support for dark store managers, context-aware alert ranking for Blinkit's 6-10 PM window → [case study](https://github.com/Anmoll-W/blinkfit)
- 📱 **BharatCRM**: WhatsApp-first CRM for T2/T3 India founders. Complete product strategy from 500 founder interviews to a 6-feature spec → [case study](https://github.com/Anmoll-W/bharatcrm)
- 📹 **youtube-longform**: product spec for fixing YouTube's algorithm bias against long-form. Three intervention directions targeting viewer discovery, creator economics, and ranking metrics → [case study](https://github.com/Anmoll-W/youtube-longform)

---

### Learning in Public (**[Anmoll-W/blog](https://github.com/Anmoll-W/blog)**)

I distill working sessions into posts on systems, silent bugs, and shipping with AI tools. Every post comes from something that actually happened.


| Title | Covers 
|---|---|
| [Your Agents Are Only as Good as the Context You Program Them With](https://github.com/Anmoll-W/blog/blob/main/posts/context-is-the-program.md) | How an AI agent vault degraded because quality gates lived in prose the model could skip instead of code the system enforced, and the overhaul that moved invariants into hooks, cut the boot context roughly 24% while making it fresher, and removed 115 references to deleted personas left over from a 13-to-6 persona consolidation. The twist: a deterministic suite passed 28 of 28 and live simulations ran clean, yet adversarial agents (instructed to break the claims, not confirm them) found the cleanup incomplete and a fresh dead-path bug the green tests never saw. Three takeaways: put invariants in code, a passing test proves what you checked and not what is true, and ghost references are a process failure not a documentation one. |
| [How My Hermes Agent Works: From a PM's Point of View](https://github.com/Anmoll-W/blog/blob/main/posts/building-a-personal-ai-ops-layer.md) | A product-manager's overview of Hermes, the always-on AI body for my Obsidian vault: the problem (a sleeping Mac silently kills scheduled automation), the three-layer architecture (vault as brain, Claude Code as hands, a rented server as the always-on body), guardrails as product constraints (it drafts and alerts but never publishes, trades, or moves money), and a value-first wave roadmap that ships a usable slice before paying for the next layer of infrastructure. Closes with four PM takeaways: build-vs-buy, designing for trust and reversibility, sequencing value over infra, and multi-lens adversarial review as product QA. |
| [Hermes, Wave 4: Finance Intel From a Server That Cannot See My Finances](https://github.com/Anmoll-W/blog/blob/main/posts/hermes-wave-4-finance-intel-off-server.md) | Wave 4 of the Hermes series: a daily snapshot of my long-term savings progress, crypto market alerts, and the ability to text the bot an investment to log, all from a server deliberately blindfolded to every finance file. The resolution: the math runs on the Mac that can see the accounts, and only a sanitized verdict plus one headline number ever crosses to the always-on server, which delivers it (enforced in code, not good intentions) and can never trade or move money. Reviewed through three lenses (build, adversarial-security, and a finance-domain pass that caught two numbers that lied comfortingly: a progress benchmark that chased the balance instead of holding the plan, and a horizon counted to the unsafe target). Deployed; no soak behind it yet. |
| [Hermes, Wave 3: A Machine That Drafts From My Notes But Cannot Post](https://github.com/Anmoll-W/blog/blob/main/posts/hermes-wave-3-the-machine-that-drafts.md) | Wave 3 of the Hermes series: the always-on server starts to write: it drafts LinkedIn posts from existing vault signals onto a review bench for two surfaces, and by construction, it cannot post a single one. A machine that ingests your own notes is a prompt-injection surface, and the two-reviewer adversarial review caught three holes that green tests missed: a note that could break out of its content wrapper into instruction space, a crafted identifier that could forge an approved status past the human gate, and fingerprint collisions that could silently drop content. A separate end-to-end review caught two more: a duplicate-draft-on-retry, and an over-broad sync rule that would have copied private notes to the server. The safety comes from a human-approve gate the code cannot bypass, privacy-pinned no-log routing that fails the call rather than leak, and someone actively trying to break both. |
| [Hermes, Wave 2: The Tests Passed. The Code Was Broken Anyway.](https://github.com/Anmoll-W/blog/blob/main/posts/hermes-wave-2-tests-that-lie.md) | Wave 2 of the Hermes series: consolidating a sprawl of scattered Mac automation into a handful of hardened, always-on jobs on a rented server, and the verification discipline that made it trustworthy. A two-reviewer adversarial gate caught six defects that a green test suite completely missed: a deploy tool that could not deploy its own code, a backup that would have wiped the target on failure, an idempotency ledger that could split and re-fire reminders as spam, a consolidated job that sent the morning digest twice, two tests that passed against deliberately-broken code, and a safety-gate check whose test was deliberately written to pass against the bug it documented. The lesson: a passing test is a claim, and claims get checked by trying to break them. Built and verified by 574 passing checks across nineteen test suites; going live after the current soak. |
