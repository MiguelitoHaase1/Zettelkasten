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
- **Products**: All products or projects → `[[Jabra+]]`, `[[Panacast]]`, `[[Sound+]]`
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

### Stakeholder Suffixes for Comprehensive Profiles
When documenting stakeholders, use these core suffixes to capture multi-dimensional insights:

- **[[Person Name/views]]** - Their priorities, concerns, stated positions, and perspectives
- **[[Person Name/strengths]]** - What they excel at, their superpowers, areas of expertise
- **[[Person Name/weaknesses]]** - Development areas, blind spots, areas for growth/improvement
- **[[Person Name/style]]** - Personality type, communication preferences, behavioral patterns, working style

Example usage:
- `[[Sarah Johnson/views]]` → Document her stance on product strategy, concerns about timeline
- `[[Sarah Johnson/strengths]]` → Technical expertise, stakeholder management, strategic thinking
- `[[Sarah Johnson/weaknesses]]` → Delegation, saying no to scope creep
- `[[Sarah Johnson/style]]` → Direct communicator, data-driven, prefers written summaries

### Assumption/Hypothesis Template
```markdown
# Assumption: [[Context]]
Statement:: What I believe to be true
Confidence:: [High/Medium/Low - X%]

# Testing card: How I'll validate

## Evidence For/against
- [[Link to supporting evidence]]

## What to do if we are right
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

## Weekly Planning Template

### Purpose
Create focused weekly plans that drive concrete outcomes, not just activities. Each week should either solve a specific problem or validate/reject a key hypothesis.

### Weekly Plan Structure
```markdown
# Week of [Date]: [Action-Oriented Title]

## Purpose This Week
[2-3 sentences in plain language explaining what you're trying to accomplish and why it matters. Connect to one of the 3 digital transformations in @/digital transformations (skunk works teams, integrating hardware and software, or AI centric product development) and previous learnings and hypotheses.]

## The One Key Problem to Solve
**[Single, specific question or problem statement related to one of the 3 digital transformations]**

Success looks like: [Concrete deliverable or outcome by Friday]

## Key Questions to Ask Everyone
1. [Universal question that reveals system dynamics]
2. [Question that identifies decision makers and blockers]
3. [Question that uncovers what would need to change]
4. [Question inspired by the 'great questions' markdown in @/Michael Onboarding

## Five Other Potential Focus Areas for the Week

### 1. [Action-Oriented Title]
**Hypothesis/Problem**: [What you're testing or solving]
**Action**: [Specific steps you'll take]
**Key People**: [Who to engage with links]

### 2-5. [Repeat structure above]

## Success Metrics by Friday
- [ ] [Specific, measurable outcome]
- [ ] [People/champions identified]
- [ ] [Deliverable created]
- [ ] [Decision or validation achieved]
- [ ] [Next steps clarified]

## Remember
[One-line reminder about bias toward action over analysis]
```

### Planning Best Practices
1. **One Main Thing**: Each week focuses on ONE primary problem/hypothesis
2. **Concrete Outcomes**: Success metrics should be binary - achieved or not
3. **People-Centric**: Every focus area identifies specific people to engage
4. **Action Bias**: Frame everything as "what to do" not "what to study"
5. **Build on Previous**: Connect to learnings and hypotheses from prior weeks

## Example Transformations

### Before:
"Met with Sarah about [[Videoconferencing]]. She thinks we need better integration."

### After:
"Met with [[Sarah Johnson]] about [[Videoconferencing]] Business. She believes we need better [[Panacast]] integration with [[Microsoft Teams]]. Created [[Assumption: Teams Integration Priority]] to track this belief. Added to [[Open Questions#Integration Roadmap]]."

## Remember

You're not just organizing notes - you're building Michael's competitive advantage through systematic knowledge management. Every link creates value. Every assumption tracked improves decision-making. Every connection surfaced accelerates understanding.

When in doubt: link more, extract more, connect more.