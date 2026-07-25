<img src="docs/header.png" alt="Building AI Products" width="100%">

# PM by title. Builder by choice.

I build PM tools and AI-powered products. The kind you can run, not just read about.

Scaled ZZAZZ from 25 to 10,000+ publishers across 70 countries (90M+ monthly users). Now Senior PM at LinkWhisper, where a seven-version conversion program lifted organic pricing-funnel conversion from 1.39% to 2.53% (+82%) with zero added acquisition spend.

8 years in B2B SaaS. MBA (Germany + UK).

### Stack I Reach For
![Claude Code](https://img.shields.io/badge/Claude_Code-1e293b?style=flat-square&logo=anthropic&logoColor=white) ![Lovable](https://img.shields.io/badge/Lovable-1e293b?style=flat-square&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-1e293b?style=flat-square&logo=cursor&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-1e293b?style=flat-square&logo=supabase&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-1e293b?style=flat-square&logo=railway&logoColor=white) ![Mixpanel](https://img.shields.io/badge/Mixpanel-1e293b?style=flat-square&logoColor=white)

---

### 🔨 Currently Building

- 🧭 **Layover** · [layover.certifiedlost.com](https://layover.certifiedlost.com)
  **Problem:** Every daily geography game on the market tests the same thing: map trivia, flags, borders, silhouettes.
  **Building:** A daily browser puzzle where you wake up in an unknown city and guess it from six clues about what the place feels like, not what it looks like on a map. A [Certified Lost](https://certifiedlost.com) sub-brand.
  **Why it matters:** [→ play today's city](https://layover.certifiedlost.com)

- 🎒 **Certified Lost** · [certifiedlost.com](https://certifiedlost.com)
  **Problem:** Travel content optimizes for the postcard shot. The actual experience of a place rarely survives the edit.
  **Building:** A travel brand about deliberate disorientation. Site, daily game (Layover), and travel stories on [Instagram](https://www.instagram.com/anmoll.w).
  **Why it matters:** [→ certifiedlost.com](https://certifiedlost.com)

- 🎓 **PM Code** · [thepmcode.com](https://thepmcode.com)
  **Problem:** Every PM resource sells a framework. The best PMs don't use frameworks. They use judgment.
  **Building:** A structured PM education library: blog posts, case simulations, and a newsletter for PMs who want to think, not template-match.
  **Why:** Most PM advice optimizes for interviews. PM Code optimizes for shipping real products.
  **Newsletter:** [thepmcode.substack.com](https://thepmcode.substack.com)

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

Product specs and strategies from zero-to-one problems. Each one is a full PM artifact, built from user research and real constraints.

- 🗺️ **[ChalotripBot](https://github.com/Anmoll-W/blog/blob/main/series/building-chalotripbot.md)**: Build story. Telegram bot for group trip planning, budgets, and bill splits.
- 🛒 **[BlinkFit](https://github.com/Anmoll-W/blinkfit)**: Case study. Peak-hour decision support for dark store managers, context-aware alert ranking for Blinkit's 6-10 PM window.
- 📱 **[BharatCRM](https://github.com/Anmoll-W/bharatcrm)**: Case study. WhatsApp-first CRM for T2/T3 India founders. Complete product strategy from 500 founder interviews to a 6-feature spec.
- 📹 **[youtube-longform](https://github.com/Anmoll-W/youtube-longform)**: Case study. Product spec for fixing YouTube's algorithm bias against long-form. Three intervention directions targeting viewer discovery, creator economics, and ranking metrics.

---

### ✍️ Learning in Public (**[Anmoll-W/blog](https://github.com/Anmoll-W/blog)**)

I distill working sessions into posts on systems, silent bugs, and shipping with AI tools. Every post comes from something that actually happened.

- **[The Health Check Was Reporting to a File Nobody Read](https://github.com/Anmoll-W/blog/blob/main/posts/a-stub-a-dead-model-and-a-health-log.md)**
  A fleet of nightly jobs that were supposed to make my AI setup smarter had quietly stopped. Three silent bugs hid it: a job stubbed to a no-op left over from a migration, a retired model name every job still called, and a health check faithfully writing its status to a file no reader ever opened. The product lesson: a monitor is not done when it writes the truth, only when the truth reaches a reader.

- **[One Sheet I Can Trust](https://github.com/Anmoll-W/blog/blob/main/posts/one-sheet-i-can-trust.md)**
  A job posting told my scoring model to output 100; it scored 85 with a star. The pipeline I built instead of a job-application bot, the contract eval that caught its first real bug within an hour, and the two vulnerabilities an adversarial pass found in a system whose tests were all green.

- **[The Boot Hook That Refired on Every Compaction](https://github.com/Anmoll-W/blog/blob/main/posts/the-boot-hook-that-refired-on-compaction.md)**
  A 30-day scan of 814 session transcripts found 98 percent of output tokens were thinking and tool calls, not prose — and a session-start hook re-injecting its full boot payload on every compaction. The fix: classify every context surface by how often it fires, not how large it is.

- **[Why I Shut Down Hermes — a Multi-Agent AI System I Built Myself](https://github.com/Anmoll-W/blog/blob/main/posts/why-i-shut-down-hermes.md)**
  The most sophisticated AI system I built is now offline — not because it broke, but because the maintenance overhead exceeded the value. Five components, a closed feedback loop that never shipped, and a split-brain corruption risk that was real. The honest accounting of why simpler won.

- **[The Write-Only Trap](https://github.com/Anmoll-W/blog/blob/main/posts/the-write-only-trap.md)**
  I had a hook capturing every tool call my AI agents made. Nothing was reading it. This post covers the three-piece learning loop that closed the gap: per-runner memory with behavioral handoff, spaced repetition for past mistakes, and an observation synthesis consumer that turns tool-use JSONL into pattern candidates.

---

## Let's connect

[LinkedIn](https://www.linkedin.com/in/anmoll-wadhwa) · [X](https://x.com/anmoll_w) · [Substack](https://thepmcode.substack.com) · [Instagram](https://www.instagram.com/anmoll.w) · [Blog](https://anmoll-w.github.io/blog) · anmollwadhwa7@gmail.com
