## TOOL 9: Troubleshooting Guide — Pacing Failures

### *When the rhythm isn't right. Specific symptoms, specific fixes.*

---

| Symptom | Diagnosis | Fix |
|---|---|---|
| AI ignores tokens entirely — output has no brackets | Tokens blending into text; format not distinct enough | Ensure tokens are in ALL CAPS with SQUARE BRACKETS. Add to prompt: "Preserve all tokens EXACTLY as written. They must appear in the output in [square brackets]. Do not paraphrase or remove them." |
| Rhythm feels rushed overall — no breathing room | Not enough pause tokens; [Fast energy] overused | Add: "Insert [Pause 1.5s] after every key statement. Maximum sentence density: 4 sentences before a pause or speed change." Reduce [Fast energy] sections. |
| Rhythm feels choppy / staccato — too many interruptions | Over-tokenized; tokens on every sentence | Remove tokens from "normal" sentences. Keep them only at inflection points. Add: "Tokens should appear on no more than 25–30% of sentences. The rest flow at natural conversational speed." |
| Pauses feel random / unearned | No tempo map guiding placement | Build a rhythm grid (Tool 2) BEFORE running Layer 3. Specify WHERE pauses go: "Place [Pause 1.5s] only after: (1) the hook's key claim, (2) the rock-bottom moment, (3) the solution insight." |
| [Fast energy] sections don't actually feel faster | AI didn't shorten sentences in those sections | Add: "In [Fast energy] sections, NO sentence may exceed 10 words. Use fragments. Compress. 'Three apps. Three weeks. Three crashes.' That rhythm." |
| [Slow down] sections don't feel slower | AI didn't lengthen sentences | Add: "In [Slow down] sections, allow sentences of 20–25 words. Use subordinate clauses. Let the thought unfold gradually. The reader should feel time stretching." |
| Voice overlay (Layer 4) removes or relocates tokens | Layer 4 prompt doesn't preserve tokens | Add to Layer 4: "PRESERVE ALL PACING TOKENS IN THEIR EXACT POSITIONS. Do not remove, relocate, rephrase, or alter any bracketed token. The tokens are structural, not stylistic." |
| B-roll descriptions are generic ("show a laptop") | Prompt lacks specificity instruction | Add: "Every [B-roll] must include: a specific brand/model, a specific screen/interface/object, a specific action or state. If you cannot be specific, write [B-roll: NEEDS SPECIFIC VISUAL — describe what should appear]." |
| Pacing works in the hook but flattens in the body | Tempo map only specified the hook; body left unguided | Extend the tempo map to ALL beats. Specify tempo per beat. Don't just say "add pacing." Say "Beat 2: [Fast energy], Beat 3: [Build speed], Beat 4: [Pause 3s] + [Slow down]." |
| The script reads well but sounds flat when performed | Written rhythm ≠ spoken rhythm | Read aloud during Layer 3 handoff. Mark where you stumble. Add: "Write for the EAR, not the eye. Vary sentence length. Include fragments. The script should sound natural at conversational speaking speed." |
| [Pause 3s] appears 5+ times | No density constraint | Add: "[Pause 3s] appears MAXIMUM 1–2 times in the entire script. It is reserved for the single biggest revelation and the emotional peak. All other pauses use [Pause 0.5s] or [Pause 1.5s]." |
| Transitions between beats feel abrupt despite tokens | No transition guidance between beats | Add: "Between beats, use a conversational bridge sentence (1 sentence) before the tempo shift. 'And here's where it gets weird...' or 'But that's not the whole story.' Then shift tempo." |

---

### The Emergency Pacing Fix (30 minutes from recording)

If your script has no pacing and you're about to record:

1. **Read it aloud once.** Mark with a pen where you naturally pause, speed up, or slow down.
2. **Insert [Pause 1.5s] at your 3 biggest natural pauses.** (After the hook claim, at the emotional peak, before the CTA.)
3. **Insert [Fast energy] at your 1 fastest section.** (Usually a list or escalation.)
4. **Insert [Slow down] at your 1 most reflective section.** (Usually the solution or personal admission.)
5. **Insert [B-roll] at your 2–3 most visual moments.** (Where you'd naturally cut away in editing.)
6. **Record.** Follow the marks. It won't be perfect. But it'll be 80% better than unmarked prose.

---

---