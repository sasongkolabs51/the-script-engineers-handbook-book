## TOOL 9: Troubleshooting Guide — Framework Execution Failures

### *When the output doesn't match the blueprint. Specific symptoms, specific fixes.*

---

| Symptom | Diagnosis | Fix |
|---|---|---|
| AI collapsed two beats into one paragraph | Prompt too long; model truncated. Or beat descriptions too similar. | Split the prompt: send Beats 1–4 in one message, Beats 5–7 in a follow-up. OR make the beat descriptions more distinct — emphasize what makes each beat DIFFERENT from the adjacent one. |
| Output reads like a summary despite beat script | Summary Prohibition Guard missing or too weak. | Add the Summary Prohibition Guard (Tool 5, Guardrail 3). Also add: "Write as if you ARE the narrator speaking to one person. Not describing a video. BEING the video." |
| Emotional arc is flat — all beats feel the same temperature | Emotional Spike Guard missing. Or emotional jobs not specified distinctly. | Add the Emotional Spike Guard. Make each beat's emotional job more distinct: "Beat 2 should make the viewer ANGRY. Beat 3 should make them AFRAID. Beat 4 should make them HOPEFUL." Name the emotions explicitly. |
| Mandatory fields are missing (no specific number, no callback) | AI ignored the mandatory field instruction. | Bold or capitalize the mandatory field: "MANDATORY: Include a specific number." Or add a post-generation check: "After writing, verify: does Beat 1 contain a number? Does Beat 7 echo it? If not, rewrite those beats." |
| The hook doesn't connect to the body | Hook was generated separately and pasted without integration instruction. | Add to Layer 2 prompt: "The first structural beat must flow DIRECTLY from the hook's retention mechanism. If the hook ended with an open loop, Beat 1 provides context for that loop. If the hook ended with a pattern interrupt, Beat 1 explores the unexpected direction." |
| Stakes don't escalate — Beat 3 feels the same as Beat 2 | Stake-Escalation Guard missing. Or escalation not specified. | Add the Stake-Escalation Guard. Specify the escalation type: "Beat 2: daily cost. Beat 3: yearly cost. Beat 4: identity-level cost. Each beat must be a HIGHER order of magnitude than the last." |
| Final beat doesn't reference Beat 1 | Payoff-Reference Guard missing. | Add the Payoff-Reference Guard. Also add explicitly: "The final sentence of Beat 7 must contain [the specific detail from Beat 1]. This is non-negotiable." |
| Framework feels forced / mechanical | Too many beats for the video length. Or beats are too rigid. | Compress: for a 5-minute video, use 4–5 beats max. For 10 minutes, 6–7. Allow beats to breathe. Add: "Transitions between beats should feel natural, not abrupt. Use conversational bridges." |
| AI adds content I didn't ask for (extra tips, unsolicited advice) | Prompt lacks a "do NOT add" constraint. | Add: "Do NOT add any content, tips, or advice not specified in the beat script. Execute ONLY what is described. No bonus material. No 'additional considerations.' Stay in the blueprint." |
| The "Solution" beat (PAS) reads like a listicle | Solution Expansion prompt too vague. | Specify: "The solution is NOT a list of tips. It is ONE insight explained in 2–3 steps. Each step: name it, explain the mechanism, give one example. No bullet points. Prose. Narrative." |

---

### The Emergency Framework Fix

If the output is fundamentally broken and you're in a rush:

1. **Identify the single weakest beat.** (Usually the one that reads like a summary.)
2. **Re-prompt ONLY that beat.** "Rewrite Beat 3 only. Keep Beats 1, 2, 4–7 exactly as written. For Beat 3: [specific instruction with emotional job and mandatory field]."
3. **Paste the fixed beat back into the full script.**
4. **Re-run Layer 4 (voice overlay) on the full script** to ensure the fix blends seamlessly.

This takes 5 minutes. Not a full regeneration. The modularity of the system is the point.

---

---