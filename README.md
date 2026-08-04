# Alex Clayton

**Senior Technical Recruiter who builds and ships his own AI tooling.**
Mechanicsburg, PA · Remote

Ten years recruiting senior technical, ERP, and finance-systems talent for enterprise consulting and delivery teams, across both agency and in-house environments. Since 2025 I've been building the AI tooling most talent acquisition teams are still evaluating, and running it in daily production against real requisitions while carrying a full desk.

Most of the work here is private, so the contribution graph is the visible part. What follows is what's behind it.

---

## What I build

### AI candidate credibility verification
*Chrome extension + web app*

Cross-references ATS candidate profiles against public professional profiles in about a minute, replacing manual line-by-line verification. 39 signals across resume, profile, cross-source, and composite categories, with deterministic scoring, forced-review overrides, and identity-theft detection. 200+ credibility reviews at roughly $0.10 per run.

Built for the high-risk employment AI category: human-in-the-loop verdicts only, no automated rejection, no protected-attribute signals, no candidate data retention, visible failure over silent error.

`TypeScript` · `Manifest V3 extension` · `React` · `Node/Express` · multi-provider AI fallback chain with per-review model traceability · `Render`

### AI resume formatting engine
*Web app*

Generates submission-ready, pixel-precise .docx resumes in any of three client formats in 25 to 45 seconds, replacing 15 to 25 minutes of manual reformatting per submission. In daily production use by a recruiting team since April 2026, on under $20 in total API cost.

Governed by formal versioned rule documents rather than prompt improvisation: no fabricated experience, no title inflation, resume-as-source-of-truth, and inline review flags so nothing uncertain reaches a client silently.

`Node.js/Express` · `Anthropic API` · deterministic docx generation with provenance metadata · `Render`

### Recruiting workflow automation
*Daily-workflow tooling*

**New-role intake.** One triggered run turns a job posting into compensation scenarios, outreach drafts, a three-tier Boolean sourcing strategy, and a client-ready intake document.

**Candidate triage.** Tiers and stack-ranks sourcing results, maintains a running shortlist and stack rank across sessions, and drafts personalized openers for review. The recruiter sends everything.

`Python` · `MCP` · scheduled runs · browser automation with human-pace and stop-on-anomaly controls

---

## Recruiting track record

Ten years of full-cycle technical recruiting across banking, financial services, insurance, consulting, software, and government / public sector.

- **110+ IT hires** delivered at a single firm, plus 30+ across Finance, Marketing, and Sales
- **4 of 5 seats** filled on one enterprise ServiceNow engagement worth roughly **$906K in annual revenue**, including the rescue of two stalled senior developer roles
- **20+ placements** into a Big 4 Financial Services Regulatory Compliance & Risk practice, across capital markets, regulatory compliance, and operational risk
- Promoted to **Team Lead** while carrying a full requisition load; led and mentored five recruiters on sourcing, technical evaluation, and offer delivery
- Raised team-wide InMail response rates from **32% to 45%** through targeted sourcing strategy
- **10/10 ClearlyRated** candidate scores across pre-screen, interview, and hire phases
- Evaluated and led the national rollout and training of an AI recruiting platform
- Authored an interviewer training guide adopted by consulting teams company-wide
- Spearheaded staffing of two new national practice areas against strict certification requirements

---

## How I work

- **Human in the loop by design.** Nothing I build makes a hiring decision or contacts a candidate on its own. Recruiters approve and send.
- **Deterministic where it counts.** AI handles judgment and language; scoring, formatting, and document generation stay deterministic and auditable.
- **Rules as artifacts.** Formatting and content rules live in versioned documents, not scattered prompts, so behavior is reviewable and changes are traceable.
- **Compliance-aware.** Employment AI is a regulated surface. No protected-attribute signals, no silent automated adverse action, evidence attached to every output.
- **Repo is truth.** Decisions logged as ADRs, artifacts committed as they're built, read-back verification before anything is called done.

---

## Tooling

**Languages & runtime**
`Python` · `JavaScript` · `TypeScript` · `Node.js` · `Express` · `React` · `SQL` · `PowerShell` · `HTML/CSS`

**AI & agent engineering**
`Anthropic API` · `OpenAI API` · `Google Gemini API` · Multi-provider orchestration & fallback design · `MCP (Model Context Protocol)` · `Claude Code` · Prompt & rule-document engineering · Eval harness & regression-suite design · Anchored, explainable scoring rubrics · Retrieval and structured extraction · Agent authority scoping & human-checkpoint design

**Platform & delivery**
`Chrome Extensions (Manifest V3)` · `Render` · `Cloudflare Workers` · `Cloudflare D1` · `Cloudflare R2` · `Git` · `GitHub` · Branch/PR discipline · Webhook services & scheduled cron jobs · REST API integration · Automated `.docx` generation (docx-js) · `VS Code`

**Recruiting systems**
`Bullhorn` · `JazzHR` · `JobDiva` · `Fieldglass` · `Workday Recruiting` · `Textkernel` · `LinkedIn Recruiter`

**Recruiting & delivery practice**
Full-cycle technical recruiting · Intake & requisition scoping · Sourcing strategy (Boolean/X-ray, referrals, passive outreach) · Offer negotiation & closing · Hiring-manager & executive stakeholder partnership · Team leadership & mentorship · Candidate experience · ERP & finance-systems talent (Workday, SAP, ServiceNow) · Government / public-sector & VMS recruiting · RPO & staff augmentation

**Workflow & ops**
`ClickUp` · `Obsidian` · `Typeform` · Process documentation & SOP design · Workflow specification (trigger, inputs, output, human checkpoints)

---

## Education & certifications

HACC, Business Administration and Management
AIRS Certified Diversity & Inclusion Recruiter (2024–2026)

---

## Elsewhere

[LinkedIn](https://linkedin.com/in/alexc717) · alx.cly@proton.me

*Repositories are private. Happy to walk through architecture, rule documents, or a live demo on request.*
