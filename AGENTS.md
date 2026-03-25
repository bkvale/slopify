# Slopify Build Rules

## Goal
Build a polished single-page parody SaaS site called Slopify with a working LLM-backed text transformation tool.

## Priorities
1. Working functionality
2. Clean UI
3. Clear structure
4. Deployability
5. Polish

## Stack
Use:
- Next.js
- Tailwind CSS
- TypeScript
- server route for LLM calls

Avoid:
- unnecessary state libraries
- unnecessary animation libraries
- database setup
- auth frameworks
- heavy UI kits unless clearly justified

## Scope
Follow `PRD.md` and stay within MVP scope.

Do not add:
- accounts
- database
- subscriptions
- dashboards
- multiple pages unless clearly necessary

## Visual guidance
Follow `design-direction.md`.

Important:
- intentionally generic modern AI/SaaS look
- do not overdesign it
- humor comes from product and copy
- avoid overly novel visual ideas

## LLM rules
Follow `prompt-spec.md`.

Requirements:
- use a server route
- use environment variables
- default to Gemini
- keep code organized enough for future provider swap if practical
- include basic error handling and fallback messaging

## UX
- mobile responsive
- polished loading state
- clear error state
- obvious copy-to-clipboard interaction
- intuitive control labels

## Accessibility
- semantic HTML
- accessible buttons and form labels
- sufficient contrast
- keyboard-friendly interaction where practical

## Brand safety
Do not:
- closely mimic Shopify's real logo or styling
- imply affiliation with Shopify
- create fake billing or deceptive purchase flows

Must include:
- a clear parody disclaimer
- a not-affiliated statement in the footer

## When in doubt
- choose simpler architecture
- choose cleaner UI
- choose narrower scope
- preserve the parody concept
