# Slopify

Slopify is a parody AI micro-SaaS built for April Fool's Day.

Its core feature is simple: take clear, normal writing and transform it into polished, cliché-ridden, stereotypical AI-generated "slop" — the kind of over-optimized, buzzword-heavy, vaguely corporate writing style people instantly recognize.

This project is intentionally built like a real product:
- real Git repo
- real web app
- real LLM integration
- real deployment workflow

The joke is the product concept, not the implementation quality.

## Goals
- Launch a polished parody SaaS site and tool
- Make the site feel believable at first glance
- Keep the build lightweight and fast to ship
- Use this project as a repeatable test case for future AI product workflows

## Planned stack
- Next.js
- Tailwind CSS
- Vercel
- LLM-backed server route
- Default provider: Google Gemini

## Default model plan
- Primary: `gemini-2.5-flash-lite`
- Fallback: `gemini-2.5-flash`

## Project structure
This repo uses markdown context files to guide Codex and future coding agents.

Key files:
- `PRD.md` — product requirements
- `AGENTS.md` — implementation rules and agent instructions
- `design-direction.md` — UI and visual direction
- `prompt-spec.md` — Slopify transformation behavior
- `launch-checklist.md` — pre-launch QA and readiness
- `.env.example` — expected environment variables

## Product summary
Slopify is the opposite of a "humanize AI text" tool.

Instead of making AI content sound more human, it makes writing sound more aggressively AI-generated:
- more buzzwords
- more empty transitions
- more fake confidence
- more enterprise language
- more polished nonsense

## MVP
The MVP is a single-page parody SaaS landing page with:
- hero section
- interactive slopification demo
- feature section
- testimonials
- pricing
- FAQ
- parody disclaimer footer

## Notes
This is parody and must clearly state that it is:
- a joke / April Fool's project
- not affiliated with Shopify
- not a real paid SaaS product
