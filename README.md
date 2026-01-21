# GoDigital Skills Repository

This repository contains skills and knowledge bases for use with Claude (AI assistant) in GoDigital projects.

## What are Skills?

Skills are structured documents that give Claude specific knowledge and guidelines to follow. They help ensure consistent, accurate responses aligned with company standards.

## Available Skills

### 1. Brand Identity Skill
**File:** `skills/brand-identity-skill.md`

Contains GoDigital's complete brand guidelines:
- Company information
- Logo usage guidelines
- Brand colors (main palette + warning colors)
- AIDA color strategy
- Typography
- Brand voice

### 2. ICP (Ideal Customer Profile) Skill - GoDigital
**File:** `skills/icp-skill.md`

Contains GoDigital's ideal customer profile for automation services:
- Target company characteristics
- Decision maker personas
- Pain points and triggers
- ROI requirements
- Product information (30-Day Automation Pilot)
- Sales messaging templates
- DACH region specifics

### 3. Mercedes-AMG SL43 ICP Skill
**File:** `skills/mercedes-sl43-icp-skill.md`

Ideal Customer Profile for selling a Mercedes-AMG SL43 in South Africa:
- Target buyer demographics (age, income, occupation)
- Psychographics and lifestyle
- Buying behavior and triggers
- Pain points and desires
- Messaging strategy
- Decision logic for content creation

### 4. Autotrader Listing Skill
**File:** `skills/autotrader-listing-skill.md`

Generates optimized Autotrader South Africa listings:
- Title and description templates
- Feature categorization
- Writing guidelines (do's and don'ts)
- Photo requirements
- Pricing guidance
- Complete listing output format

---

## Projects Using These Skills

### Mercedes-AMG SL43 | Autotrader ZA Sale

This project uses skills #3 and #4 to create an optimized Autotrader listing for a 2024 Mercedes-AMG SL43 in Cape Town, South Africa.

**Skills involved:**
- `mercedes-sl43-icp-skill.md` - Defines the ideal buyer
- `autotrader-listing-skill.md` - Generates the listing copy

---

## How to Use These Skills

### In Claude Code (VS Code Extension)

You can reference these skills in your CLAUDE.md file or point Claude to this repository.

### In Claude Desktop App / Claude.ai

1. Create a new Project (e.g., "Mercedes-AMG SL43 | Autotrader ZA Sale")
2. Add the skill files as Project Knowledge
3. Claude will use the skills when working on related tasks

### In GitHub Desktop

Clone this repository to your local machine:

```bash
git clone https://github.com/neveleren/godigital-skills.git
```

Or in GitHub Desktop:
1. Click "Clone a repository from the Internet"
2. Select `neveleren/godigital-skills`
3. Choose where to save it
4. Click Clone

---

## Contributing

To add new skills:
1. Create a new `.md` file in the `skills/` folder
2. Follow the existing skill format
3. Update this README

---

**Company:** Go Digital Software GmbH  
**Website:** https://godigital-ai.de/
