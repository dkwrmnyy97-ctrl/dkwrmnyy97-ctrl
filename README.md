# Isabella Fugaro

I work in **identity and access management** on enterprise IAM, non-human identity, and AI security. When I run into a problem worth solving, I build something.

I own these products end to end: the product decisions, the access-control and privacy design, testing, and shipping. I came to software from identity and security rather than engineering, and I build with **Claude Code** as my primary implementation tool; it wrote most of the code from my direction. Each README explains what's implemented and what isn't, and which apps call the Claude API at runtime (Flock doesn't).

**Portfolio:** [isabella-fugaro-preview.netlify.app](https://isabella-fugaro-preview.netlify.app)

## Projects

### [BellaHealth](https://github.com/dkwrmnyy97-ctrl/bellahealth): *your health doesn't happen in pieces*
An iOS app that unifies Apple Health, Oura, nutrition, and life context (travel, illness, cycle, training) into one understandable picture. It includes an AI chat grounded in your own data.
- **Status:** private beta on TestFlight.
- **Stack:** React Native / Expo, Supabase, Claude API.
- **Access controls:** Oura OAuth with PKCE (the secret stays server-side), anonymous-first Supabase Auth with Sign in with Apple, owner-only RLS, JWT-verified Edge Functions, and analytics that never capture health data.

### [Flock](https://github.com/dkwrmnyy97-ctrl/flock-app): *Catholic community, made easier*
A social app for parishes, ministries, and friend groups. It has a feed, communities and groups, events with recurring schedules, Discover (Mass times and events), and a Bible reader.
- **Status:** private beta (iOS TestFlight and Android).
- **Stack:** React Native / Expo, Supabase.
- **Access controls:** about 165 RLS policies, layered community, group, and platform roles, moderation and blocking, private media with signed URLs, and account deletion with token revocation.

### [No Cache News](https://github.com/dkwrmnyy97-ctrl/no-cache-news): *AI moves fast. Attention is finite.*
A personal AI-news intelligence dashboard. Claude turns AI and cybersecurity feeds into a categorized Today / Week / Month briefing, with analyst Q&A, podcast picks, and read-aloud.
- **Status:** live at [nocachenews.com](https://nocachenews.com).
- **Stack:** Node / Express, React, Claude API.

### [Career Agent](https://github.com/dkwrmnyy97-ctrl/career-agent): *a job search that thinks with you*
A local CLI and dashboard that pulls postings from public ATS boards, scores fit, and tracks pipeline, contacts, and next actions. Claude drafts materials for review, and nothing is ever sent automatically.
- **Status:** internal tool.
- **Stack:** Python, Flask, SQLite, Claude API.

## In the lab

These are concepts without published code. They're described on my portfolio:
- **[Procurement, Rethought](https://isabella-fugaro-preview.netlify.app/lab/procurement)**: an AI-assisted guide to taking an enterprise application through security onboarding. This was my capstone concept for the MIT AI & Cybersecurity certificate program.
- **Entertainment Hub**: "What do I want to watch tonight, and where is it streaming?", filtered to the services you actually have.
