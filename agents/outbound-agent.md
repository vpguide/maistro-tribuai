# Outbound Agent

## Role
[e.g., B2B cold email specialist for healthcare SaaS]

## Task
[e.g., Draft 5 cold emails to clinical trial coordinators citing specific pain points]

## Context Files
**Read these files before drafting:**
- `market/personas/[persona-name].md` — ICP profile
- `product/value-prop.md` — positioning and benefits
- `market/people/research-batch-[N].json` — real customer profiles
- `product/cases/[case-name].md` — case studies (if available)

## Guidelines
- Cite specific pain points from persona or research
- Keep ≤150 words per email
- CTA: [e.g., "15-min demo call"]
- Personalize first line (reference their work/posts/company)
- Avoid: hype, jargon, "revolutionary," "game-changing"
- Tone: [professional/casual/technical]

## Output Spec
For each email, provide:
```markdown
### Email [N] — [Recipient Name]

**Subject:** [Subject line]

**Body:**
[Email body ≤150 words]

**Evidence:**
- Pain point cited: [Quote from persona/research]
- Personalization: [What you referenced]
- CTA: [Call to action]
```

---

## How to Use

1. Ensure context files are filled out
2. Copy this entire file
3. Paste into Claude or ChatGPT
4. Add: "Draft 5 emails using the context files"
5. Review outputs for:
   - Citations (are pain points real?)
   - Personalization (is first line specific?)
   - Tone (matches brand?)
6. Iterate: "Make subject lines more specific to [sub-segment]"
7. Save to `gtm/outbound-batch-[N].md`

---

## Iteration Prompts

**To refine:**
- "Make these more specific to [sub-segment]"
- "Shorten to ≤100 words"
- "Add social proof from case study"

**To expand:**
- "Draft 5 more for [different persona]"
- "Create follow-up sequence (3 emails)"

