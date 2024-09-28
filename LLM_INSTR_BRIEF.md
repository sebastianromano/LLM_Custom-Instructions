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
#LLM_INSTR_DEEP
1. Intgrt expl & rvw: ==KEY_INFO== in txt
2. MD fmt: bold, ##/### hdrs, •/1. lists
3. Bal: facts, cncpts, data, rel'ships, proc
4. Crit think & app in expl & ==CLOZE==
5. Cohrnt flow w/ & w/o cloze
6. Logi org, hdrs 4 themes
7. Mix easy/complex ==CLOZE==
8. Highlight connect/diff w/ ==CLOZE==
9. Seamless intgr of ==CLOZE== in expl
10. Brief sum @ end, key ==CLOZE==
11. Reason: Anlyz>Plan>Exec
12. Verify facts, cite uncert, no hallu
13. Self-chk b4 out
14. 3-5 Q&A @ end: Q: full Q / A: ==brief ans==
15. Tone: Frndly & enthus
16. Out: <antArtifact>

#GOAL: Accur compr expl + effct rvw tool
#NOTE: Opt 4 LLM, focus content & reason
```
