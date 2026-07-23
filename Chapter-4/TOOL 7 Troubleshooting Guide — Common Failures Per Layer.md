## TOOL 7: Troubleshooting Guide — Common Failures Per Layer

### *When the output isn't right, diagnose it here. Specific symptoms, specific fixes.*

---

### Layer 1 Troubleshooting

| Symptom | Likely Cause | Fix |
|---|---|---|
| Beat sheet is generic — could apply to any creator | Angle wasn't specific enough in the prompt | Rewrite the ANGLE field. Add: "This is different from the usual advice because ___." Name your specific contrarian take. |
| Beats are in the wrong order / don't escalate | Structure wasn't specified clearly | Name the exact narrative framework. Or describe the sequence: "Beat 1 must be the pain. Beat 2 must be the hidden cause. Beat 3 must be my story. Beat 4 must be the reframe." |
| Emotional outcome is missing or vague | You wrote "inform" or "educate" instead of a feeling | Replace with a specific emotion: "The viewer should feel *seen* and *slightly angry* that they've been doing this wrong for years." |
| Too many beats (10+) or too few (3) | No beat count specified | Add: "Generate exactly 6 beats." Or "5–7 beats, no more." |
| Personal element is absent | You forgot to include it in the prompt | Add the PERSONAL ELEMENT field. Even one sentence: "Include a beat where I share my specific failure with ___." |

---

### Layer 2 Troubleshooting

| Symptom | Likely Cause | Fix |
|---|---|---|
| Skeleton reads like a Wikipedia summary | AI defaulted to informational mode | Add: "This is NOT an informational article. It is a persuasive narrative. Every beat must advance an argument, not just present facts." |
| Transitions are abrupt / jarring | No transition instruction given | Add: "Between each beat, write a 1–2 sentence transition that connects the previous idea to the next. Use conversational bridges: 'And here's where it gets weird...' or 'But that's not the whole story.'" |
| [HOOK] placeholder has no material to work with | The first beat is too abstract | Revise Layer 1's first beat to include a specific detail, number, or moment. Then regenerate Layer 2. |
| Skeleton is too short / too long | No word count target given | Add: "Total length: approximately [X] words. Each beat should be [Y]–[Z] words." |
| AI added jokes or stylized language | "No style" instruction wasn't strong enough | Add: "ZERO personality. ZERO humor. ZERO rhythm variation. This should read like a clear internal memo. Deliberately boring. Style comes in Layer 3 and 4." |

---

### Layer 3 Troubleshooting

| Symptom | Likely Cause | Fix |
|---|---|---|
| Pacing tokens feel random / scattered | No emotional stage directions given | Add per-section emotional guidance (see Tool 4 templates). Tell the AI WHERE to place energy shifts. |
| Script still feels flat despite tokens | Sentence length wasn't varied | Add: "In [FAST ENERGY] sections, no sentence may exceed 10 words. In [SLOW DOWN] sections, allow sentences of 20–25 words. The contrast IS the pacing." |
| [B-ROLL] descriptions are vague ("show relevant image") | No specificity instruction | Add: "Every [B-ROLL] must describe a SPECIFIC visual: a screen recording, a specific graph, a specific object. Not 'relevant footage.' What EXACTLY appears on screen?" |
| Too many tokens — script feels choppy | No density guideline | Add: "Maximum 2 [PAUSE] tokens per 100 words. Maximum 1 [B-ROLL] per 150 words. Tokens should enhance, not interrupt." |
| AI changed the content / added new information | No "preserve content" constraint | Add: "Do NOT add, remove, or change any content. Only add pacing tokens and adjust sentence length. The words and ideas are locked." |

---

### Layer 4 Troubleshooting

| Symptom | Likely Cause | Fix |
|---|---|---|
| Script sounds generic / "AI voice" | Voice description too abstract | Replace "conversational" with concrete specs: "Starts sentences with 'And' and 'But.' Uses 'look' and 'here's the thing' as pivots. Never says 'furthermore' or 'moreover.'" |
| Pacing tokens were removed | No preservation constraint | Add: "PRESERVE ALL BRACKETED TOKENS IN THEIR EXACT POSITIONS. Do not remove, relocate, or modify any [PAUSE], [B-ROLL], [FAST ENERGY], etc. token." |
| Humor doesn't sound like mine | Humor style described too vaguely | Replace "add humor" with: "One dry, observational joke per section. Structure: setup → unexpected comparison → flat delivery. No puns. No 'haha' energy. Example of my humor: [paste a real line]." |
| Banned phrases appeared | Banned list wasn't included | Add your full banned phrase list to the prompt. Explicitly: "NEVER use: 'In today's video,' 'Let's dive in,' 'Without further ado,' 'comprehensive,' 'delve.'" |
| Voice is consistent in the hook but drifts by the middle | Prompt only described voice briefly | Add: "Maintain this voice consistently across ALL sections. The CTA should sound as much like me as the hook. Do not shift to 'presenter voice' in later sections." |
| AI over-polished / made it sound "professional" | Register wasn't specified firmly enough | Add: "This should sound like a voice memo to a friend, not a polished presentation. Imperfect is good. Fragments are good. Starting with 'And' is good. Do NOT clean up my roughness." |

---

---