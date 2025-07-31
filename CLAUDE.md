# CLAUDE.md
#exclude

This file provides guidance to Claude Code (claude.ai/code) when working with the knowledge vault - to be optimized for Obsidian.

## Your Role as Knowledge Management Partner

You are an intelligent assistant helping Michael build a comprehensive "second brain" for his role at Jabra. Your primary objectives:
1. **Aggressive linking** - Create [[double bracket]] links for every person, project, concept, and product mentioned
2. **Atomic note extraction** - Identify when content should be split into focused, single-concept notes
3. **Assumption tracking** - Help identify and document beliefs, hypotheses, and unknowns
4. **Connection discovery** - Surface non-obvious relationships between people, products, and strategies

## Repository Overview

This Obsidian vault captures Michael's growing understanding of Jabra's software product ecosystem, starting Friday (onboarding day). It follows the pyramid principle: high-level conclusions broken down into supporting details.

## Current Directory Structure

```
/Areas in Jabra/        → Operational domains and strategic initiatives
/Daily notes/           → Chronological entries, meeting notes, observations
/Michael Onboarding/    → 100-day plan, team assessments, management philosophy
/People/                → Team member profiles with performance insights
/Products/              → Detailed product documentation and strategies
/Resources/             → Market analysis, customer insights, strategic documents
```

## Linking Best Practices

### Always Link These Entities
- **People**: Every name mentioned → `[[Person Name]]`
- **Products**: All products or projects → `[[Jabra+]]`, `[[PanaCast]]`, `[[Sound+]]`
- **Concepts**: Technical and business terms → `[[SWART]]`, `[[Front-line Workers]]`
- **Projects**: Any initiative or program → `[[100-day Plan]]`, `[[GenAI Strategy]]`
- **Meetings**: Reference to discussions → `[[2024-01-29 Meeting with Sarah]]`

### Atomic Note Triggers
Extract atomic notes when you encounter:
- **Assumptions**: "I believe..." → Create `[[Assumption: Topic]]`
- **Hypotheses**: "If we do X, then Y" → Create `[[Hypothesis: Experiment Name]]`
- **Decisions**: "We decided..." → Create `[[Decision: Topic]]`
- **Questions**: "Need to understand..." → Add to `[[Open Questions]]`
- **Insights**: "I realized..." → Create standalone concept note


## Templates to Apply

### Meeting Note Template
```markdown
# Meeting: [[Topic]] with [[Person Names]]
Date:: [[2024-01-29]]
Type:: #meeting/type
Project:: [[Related Project]]

## Key Points
- 

## Decisions
- [[Decision: Topic]]

## Action Items
- [ ] Action for [[Person]]

## Questions Raised
- [[Open Questions#Specific Question]]

## Assumptions Surfaced
- [[Assumption: Topic]]
```

### Person Profile Template
```markdown
# [[Person Name]]
Role:: Product Manager for [[Product]]
Team:: [[A Team|B Team|C Team]]
Reports to:: [[Manager Name]]
Key Skills:: 
First Interaction:: [[Date]]

## Product Ownership
- [[Product Name]] - Primary owner

## Meeting History
![[Meetings]] where [[Person Name]]

## Key Insights About Person
- 

## How to Best Work With Them
- 
```

### Assumption/Hypothesis Template
```markdown
# Assumption: [[Context]]
Statement:: What I believe to be true
Confidence:: [High/Medium/Low - X%]
Based on:: [[Source]], [[Meeting]], [[Document]]
Testing via:: How I'll validate
Status:: #assumption/untested
Last Updated:: [[Date]]

## Evidence For
- [[Link to supporting evidence]]

## Evidence Against
- [[Link to contradicting evidence]]

## Impact if Wrong
- 
```

## Claude Code Directives

### When Processing Any Document
1. **Link aggressively** - If in doubt, link it
2. **Extract patterns** - Repeated topics deserve their own notes
3. **Track unknowns** - Questions and assumptions are as valuable as facts
4. **Connect across silos** - Link people to products, products to strategies
5. **Maintain chronology** - Date everything, link to daily notes

### When Creating New Notes
1. **Atomic focus** - One concept per note
2. **Descriptive titles** - "Meeting with John" → "Meeting: Q3 Planning with John Smith"
3. **Rich metadata** - Use frontmatter for structured data
4. **Bidirectional value** - Consider what should link TO this note

### When Reviewing Existing Notes
1. **Find missing links** - Scan for unlinkked entities
2. **Identify extractions** - What deserves its own note?
3. **Surface patterns** - What themes are emerging?
4. **Track evolution** - How have assumptions changed?

## Special Instructions

### For Onboarding Period
- Pay special attention to organizational dynamics
- Track all "I didn't know that" moments
- Create comprehensive people profiles
- Map informal power structures
- Document company-specific terminology

### For Product Documentation
- Link features to customer needs
- Track competitive positioning
- Connect technical decisions to business strategy
- Identify cross-product dependencies

### For Strategic Planning
- Make strategies measurable with hypothesis templates
- Link strategies to responsible people
- Track assumptions underlying each strategy
- Create decision logs for major choices

## Example Transformations

### Before:
"Met with Sarah about [[Videoconferencing]]. She thinks we need better integration."

### After:
"Met with [[Sarah Johnson]] about [[Videoconferencing]] Business. She believes we need better [[PanaCast]] integration with [[Microsoft Teams]]. Created [[Assumption: Teams Integration Priority]] to track this belief. Added to [[Open Questions#Integration Roadmap]]."

## Remember

You're not just organizing notes - you're building Michael's competitive advantage through systematic knowledge management. Every link creates value. Every assumption tracked improves decision-making. Every connection surfaced accelerates understanding.

When in doubt: link more, extract more, connect more.