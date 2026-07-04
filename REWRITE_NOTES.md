# LLMs4Leaders Homepage Rewrite Notes

**Date:** 2026-04-23  
**Deployed to:** https://llms4leaders.netlify.app  
**Site ID:** 03dfc179-8174-4e74-b9cf-77b6798414ce

## What Changed

### Framing
- **Old:** Full-service strategic chat interface (Compadre as the AI)
- **New:** Continuity and coaching layer above whatever commercial AI (ChatGPT/Claude/Gemini) the exec already uses

### Hero
- Old headline: "Lead the AI Conversation."
- New headline: "Your Commercial AI Resets. The Compadre Doesn't."
- Old CTA: "Start Your First Session Free" → New CTA: "Request Early Access"

### Dialogue Demo
- Old: Compadre answers the M&A culture-fit question directly
- New: Compadre coaches the exec to bring a sharper question to their ChatGPT and come back to debrief what it misses — shows the actual product model

### Confidentiality Claims (tightened)
- Removed: "Your conversations stay yours. Nothing enters our training data." (undefendable)
- Added honest specifics: relationship profile in dedicated per-user store, actual content stays in commercial AI, ZDR settings for model calls, export/delete anytime, SOC 2 in-progress admission

### New Section: "Bring Your AI — We'll Help You Get More From It"
- Added between Compadre Difference and For Your Team
- Explains bring-your-own-AI model explicitly
- Covers ChatGPT history upload → strategic synthesis
- Covers "extract what your AI knows about you" workflow
- Covers work vs. personal AI hygiene

### New Feature: Personality Flexibility
- "Matches Your Register" replaces generic "Peer-to-Peer" feature
- Explicit: if you curse in meetings it matches register; if you're clinical it won't fake folksy

### Pricing (session-metering language removed)
- "3 strategic sessions per week" → "Build your relationship profile"
- "Unlimited sessions" → relationship depth / continuity language
- Tier names: Free → Explorer, Explore → Partner, Premium → Principal
- CTA buttons: "Build Your Profile" / "Try for $1" / "Go Deep"

### Use Cases (6 tiles)
- Kept same scenarios, reframed copy to reflect coaching model (bring AI output here, debrief the gap)

### Other
- Portland, OR → Denver, CO (footer)
- Nav: added "Bring Your AI" link to new section

## What Was NOT Changed
- Visual design, color palette, layout structure
- CSS (zero changes)
- All internal anchor links
- Mike + Claude authorship framing
- Transparent compute pricing ethos
- Org cohort program section

## Deployment
No git repo in this directory. Deployed directly:
```
netlify deploy --prod --dir=. --site=03dfc179-8174-4e74-b9cf-77b6798414ce
```
