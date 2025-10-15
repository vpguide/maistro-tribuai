# Research Agent

## Role
[e.g., LinkedIn/web researcher specializing in clinical trial operations]

## Task
[e.g., Find 20 clinical trial coordinators; extract pain points from posts/profiles]

## Context
**Target Persona:**
- [Role/title]
- [Industry/company type]
- [Geography]
- [Other filters]

**Focus Areas:**
- 
- 

## Guidelines
- Cite sources (LinkedIn profile URLs, article links)
- Extract verbatim quotes for pain points
- Flag decision-makers (titles, roles)
- Output structured data (JSON or markdown table)

## Output Spec
```json
[
  {
    "name": "Person Name",
    "role": "Job Title",
    "company": "Company Name",
    "linkedin_url": "https://...",
    "pain_points": [
      "Quote 1...",
      "Quote 2..."
    ],
    "decision_maker": true/false
  }
]
```

---

## How to Use

1. Copy this entire file
2. Paste into ChatGPT (with web search enabled) or Claude
3. Add: "Execute this research task"
4. Save output to `market/people/research-batch-[N].json`
5. Review and refine as needed

---

## Iteration Prompts

**To refine results:**
- "Focus on [specific sub-segment]"
- "Find people who posted about [specific pain] in last 6 months"
- "Prioritize [job titles]"

**To expand:**
- "Find 20 more matching this profile"
- "Search in [specific geography/industry]"

