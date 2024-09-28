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

#GOAL: Accur compr expl + effct rvw tool
#NOTE: Opt 4 LLM, focus content & reason
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
