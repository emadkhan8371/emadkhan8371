# Emad Khan

I build production AI systems with Claude Code and the Claude API, and I teach people to build them.
LSE Philosophy & Economics student. Founder of [Columen Consulting](https://columenconsulting.com).

### What I've shipped

- **AI video-review engine.** It turns a creator's short-form video into the critique a coach would give. The pipeline is Whisper transcript → Claude vision decode → evidence-checked findings → written review. It's live for a creator-coaching company and graded by evals against the coach's own past reviews, with 644 tests behind it.
- **White-label client platform.** A member portal with a roadmap, tracker, course player, intake form, admin and a CSM cockpit, themed per client from one codebase. Built with Next.js, Supabase and Postgres RLS.
- **Headless Claude Code agent.** A Telegram bot that generates images and video for a client's editor on a shared account, without the editor ever getting the login. Tools are restricted to one CLI, and a PreToolUse hook outside the model enforces a daily spend cap ([claude-code-spend-cap](https://github.com/emadkhan8371/claude-code-spend-cap)).
- **Wu**, my autonomous personal AI system (238 commits since Aug 2026). It runs 24/7 across a VPS and a home node: a Telegram agent, a voice/text PWA, and headless Claude sweeps of my mail, calendar and university Moodle feeding one event log. Safety is enforced below the model: anything that reaches another person needs my one-tap approval on a card rendered from the literal payload, external content is read with no tools, and an out-of-band kill switch locks away its credentials. It also tutors me through my degree with spaced repetition and an Obsidian plugin I wrote ([obsidian-tutor-quiz](https://github.com/emadkhan8371/obsidian-tutor-quiz)).

### How I work with Claude

I've written my own Claude Code skills and subagents. The one I've open-sourced is **[plan-council](https://github.com/emadkhan8371/plan-council)**: a plan goes to a council of review lenses, then an adversarial pass re-checks every claim against the real code before anything gets built.

### Teaching

I was Lovable's first student ambassador and later a Campus Leader. I've run build workshops for around 400 people at London Tech Week, the Oxford–Cambridge Fellowship, Imperial, Chicago Booth and LSE.

**Stack:** Python · TypeScript · Next.js · Astro · FastAPI · Supabase/Postgres · Claude API · Claude Code · Linux/systemd · Cloudflare

[LinkedIn](https://www.linkedin.com/in/emadkhan-/) · [columenconsulting.com](https://columenconsulting.com) · emadkhan8371@gmail.com
