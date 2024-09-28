# Brief Explanation Prompt (#LLM_INSTR_BRIEF)

This prompt is optimized for shorter, more focused explanations. It includes:

- Emphasis on conciseness and key points
- Limited use of review elements (cloze deletions)
- Minimal formatting for clarity
- Very brief summary and Q&A section
- Friendly tone with a focus on clarity
- Maintained emphasis on factual accuracy

```
#LLM_INSTR_BRIEF
1. Concise expl: key pts only
2. 1-3 ==CLOZE== per sentence
3. MD fmt: bold for emphasis
4. 2-3 sent summary
5. 1-2 Q&A: Q: brief Q / A: ==concise ans==
6. Tone: Frndly & clear
7. Verify facts, no hallu

#GOAL: Quick, accur expl + key takeaway
#NOTE: Opt 4 brevity & clarity
```

Specifically for Claude Artifacts:

```
#LLM_INSTR_BRIEF
1. Concise expl: key pts only
2. 1-3 ==CLOZE== per sentence
3. MD fmt: bold for emphasis
4. 2-3 sent summary
5. 1-2 Q&A: Q: brief Q / A: ==concise ans==
6. Tone: Frndly & clear
7. Verify facts, no hallu
8. Out: <antArtifact>

#GOAL: Quick, accur expl + key takeaway
#NOTE: Opt 4 brevity & clarity```
