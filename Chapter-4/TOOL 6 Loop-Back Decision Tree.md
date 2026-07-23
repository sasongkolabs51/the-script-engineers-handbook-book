## TOOL 6: Loop-Back Decision Tree

### *Something's off. You don't need to nuke the whole chain. Find the broken layer. Fix it there. Re-run downstream.*

---

### The Diagnostic: Where Is the Problem?

**Read your current output and identify the symptom:**

| Symptom | Broken Layer | Fix Protocol |
|---|---|---|
| The angle feels generic. The beats could apply to any creator in my niche. The emotional outcome is vague. | **Layer 1** | Refine the ideation prompt. Add more specificity to your angle. Name the emotional outcome more precisely. Regenerate beat sheet. Then re-run Layers 2–4. |
| The argument doesn't hold together. Transitions are jumpy. A beat feels underdeveloped or padded. Stakes aren't personal. | **Layer 2** | Refine the skeleton prompt for the specific failing beat. Add a directive like "expand beat 3 with a specific sensory detail from my experience." Regenerate that section. Then re-run Layers 3–4. |
| The script reads like a wall of text. No breathing room. Pacing feels flat. B-roll moments are vague or missing. | **Layer 3** | Refine the pacing prompt. Add emotional stage directions per section. Specify which beats need [FAST ENERGY] vs. [SLOW DOWN]. Regenerate. Then re-run Layer 4. |
| The script sounds generic. Doesn't sound like me. Banned phrases appeared. Humor is "internet humor" not MY humor. | **Layer 4** | Refine the voice prompt. Add more specific voice characteristics. Replace abstract descriptors ("conversational") with concrete ones ("starts sentences with 'And' and 'But'"). Regenerate. No downstream layers needed. |
| Pacing tokens were removed or relocated during voice overlay. | **Layer 4** | Add explicit constraint: "Preserve ALL tokens in their EXACT positions. Do not remove, relocate, or modify any bracketed token." Regenerate Layer 4 only. |
| The hook is weak even though the structure is sound. | **Layer 2** (hook beat) | Regenerate Layer 2 with a specific hook directive: "The [HOOK] beat must open with [specific structure from Ch. 1: a number / a confession / a contradiction]." Then re-run Layers 3–4. |
| The CTA feels disconnected from the rest of the script. | **Layer 2** (CTA beat) | Add to Layer 2 prompt: "The [CTA] must reference the specific pain point named in the Stakes beat. Frame the action as the viewer's next logical step." Regenerate CTA section. Re-run Layers 3–4 for that section. |

---

### The Loop-Back Protocol (Step by Step)

1. **Identify the broken layer** using the table above.
2. **Isolate the fix.** Adjust ONLY that layer's prompt. Don't touch the others.
3. **Regenerate** the broken layer's output.
4. **Re-run the handoff checklist** (Tool 3) for that layer.
5. **If it passes, re-run all DOWNSTREAM layers** (layers after the broken one) using the new output as input.
6. **If it still fails, refine further.** You may need to loop back twice. That's fine. It's still faster than a full rewrite.
7. **Never go back further than necessary.** If Layer 3 is the problem, don't regenerate Layer 1. The beat sheet is fine. The skeleton is fine. Only the pacing needs work.

---

### The Targeted Section Fix (When Only a Few Lines Are Off)

Sometimes the whole layer is fine except for 2–3 sentences. Don't regenerate the entire layer. Use a targeted prompt:

```
In the following script, rewrite ONLY the sentences I've marked
with [REVOICE]. Preserve everything else exactly — all tokens,
all structure, all surrounding text.

[Paste the script with [REVOICE] markers around the problem lines]

For the [REVOICE] sections:
- [Specific instruction: e.g., "Make this sound more self-deprecating
  and less formal. I'd say 'yeah, I completely botched that' not
  'I made a significant error in judgment.'"]
- [Specific instruction: e.g., "Shorten these three sentences to
  under 10 words each. Punchy. Fragmented."]

Do NOT change anything outside the [REVOICE] markers.
```

---

---