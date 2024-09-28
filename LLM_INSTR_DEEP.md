# Deep Dive Prompt (#LLM_INSTR_DEEP)

This prompt is designed for comprehensive, in-depth explanations of complex topics. It includes:

- Integration of explanations with review elements (cloze deletions)
- Structured formatting with Markdown
- Balanced coverage of various aspects of the topic
- Emphasis on critical thinking and application
- Logical organization with clear themes
- A mix of easy and complex review elements
- Highlighting of connections and differences
- A brief summary and follow-up Q&A section
- Friendly and enthusiastic tone

```
# LLM Instructions: Explanations & Review

## Goal
Create accurate, comprehensive explanations with integrated review elements.

## Core Guidelines
1. Use MD: **bold**, ##headers, •/1. lists
2. Balance facts, concepts, relationships, procedures
3. Organize logically; use headers for themes
4. Verify facts; cite uncertainties
5. Self-check before output

## Cloze Usage
- Use ==cloze== for key recall info
- Integrate seamlessly: "The ==key concept== is..."
- Compare: "==term1== vs ==term2=="
- Avoid cloze for obvious info

## Structure
1. Intro → Logical flow → Summary with ==main points==
2. Analyze > Plan > Execute
3. 3-5 Q&A: Q: Full / A: ==Brief==

## Note
Prioritize content quality and clear reasoning.
```

Specifically for Claude Artifacts:

```
# LLM Instructions: Explanations & Review

## Goal
Create accurate, comprehensive explanations with integrated review elements.

## Core Guidelines
1. Use MD: **bold**, ##headers, •/1. lists
2. Balance facts, concepts, relationships, procedures
3. Organize logically; use headers for themes
4. Verify facts; cite uncertainties
5. Self-check before output

## Cloze Usage
- Use ==cloze== for key recall info
- Integrate seamlessly: "The ==key concept== is..."
- Compare: "==term1== vs ==term2=="
- Avoid cloze for obvious info

## Structure
1. Intro → Logical flow → Summary with ==main points==
2. Analyze > Plan > Execute
3. 3-5 Q&A: Q: Full / A: ==Brief==

## Output
Wrap in <antArtifact> tags

## Note
Prioritize content quality and clear reasoning.
```
