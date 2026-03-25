# Product Requirements Document — Slopify

## 1. Product name
Slopify

## 2. Product summary
Slopify is a parody AI tool that rewrites normal text into stereotypical, over-polished, buzzword-heavy AI slop.

The site should look like a real modern AI startup landing page, but the product itself is intentionally absurd.

## 3. Primary goal
Launch a polished parody SaaS site and working text transformation tool for April Fool's Day.

## 4. Core joke
Most tools promise to "humanize AI writing."

Slopify proudly does the opposite:
it makes writing sound more AI-generated, more cliché, more synthetic, and more enterprise-ready.

## 5. MVP scope

### In scope
A single-page responsive marketing site with:
- hero section
- subheadline
- CTA buttons
- interactive text transformation tool
- feature grid
- fake testimonials
- fake pricing section
- FAQ
- footer disclaimer

A working app experience with:
- text input
- text output
- generate button
- slop level selector
- mode selector
- sample text presets
- copy result button
- loading state
- error state
- graceful fallback state

A server route that:
- receives input text and settings
- calls the configured LLM provider
- returns transformed output

### Out of scope
- user accounts
- auth
- billing
- analytics dashboards
- saved generations
- database
- multi-page product architecture
- admin panel
- real subscriptions
- real checkout
- real integrations

## 6. User experience goals
The visitor should experience the following:
1. Initial impression: "This looks like a real AI startup."
2. Second impression: "Wait, this is ridiculous."
3. Tool interaction: "Okay, this is actually funny."
4. Share impulse: "I should send this to someone."

## 7. Target vibe
- polished
- generic in a deliberate way
- stereotypical AI/SaaS website
- deadpan
- premium-looking
- joke revealed through content, not chaotic design

## 8. Core functionality

### Tool input
The user can paste or type text into a textarea.

### Controls
The user can choose:
- slop level
- mode / format

#### Slop levels
- Mild
- Thought Leader
- Enterprise
- VC Pitch Deck

#### Modes
- LinkedIn Post
- Blog Intro
- Sales Email
- Executive Memo
- Startup Landing Page

### Tool output
The system returns a rewritten version of the input that:
- preserves the broad meaning
- exaggerates AI-writing clichés
- increases buzzwords and filler
- remains readable and funny

## 9. Functional requirements

### Landing page sections
1. Hero
2. Demo / tool section
3. Example transformations
4. Feature cards
5. Testimonials
6. Pricing
7. FAQ
8. Footer

### Tool UX requirements
- clear input and output areas
- user can copy result
- sample presets should be clickable
- loading state should feel polished
- error state should not break the layout
- generation should happen via server route, not direct client-side model call

## 10. Technical requirements
- Use Next.js
- Use Tailwind CSS
- Keep architecture simple and deployable
- Use a server route for model requests
- Default to Gemini as provider
- Keep provider integration structured cleanly enough that swapping providers later is possible
- Use environment variables for model configuration
- No database required

## 11. Content requirements
The copy should:
- sound like a real startup site
- be concise
- lean into parody via terminology
- avoid overexplaining the joke too early

Examples of parody language:
- enterprise-grade verbosity
- thought-leadership enrichment
- synergy amplification
- authenticity suppression
- data-driven fluff injection

## 12. Legal / parody requirements
The site must:
- clearly state it is parody
- clearly state it is not affiliated with Shopify
- avoid directly mimicking Shopify's branding too closely
- avoid any fake billing or deceptive purchase flows

## 13. Success criteria for V1
The first implementation is successful if:
- the site is visually polished
- the tool works end to end
- the output is funny and recognizable
- the site is responsive
- it is deployable to Vercel
- the parody disclaimer is clearly visible

## 14. Nice-to-have items
These are optional if time allows:
- fake logo wall
- slop score meter
- extra sample presets
- animated loading flourish
- better result formatting
- OG image polish
