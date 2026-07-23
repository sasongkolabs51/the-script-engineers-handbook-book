## TOOL 9: Troubleshooting Guide — Voice Drift Patterns

### *When the profile isn't holding. Systematic diagnosis and repair.*

---

### Problem 1: Voice Holds for 2–3 Paragraphs, Then Drifts

**Cause:** The AI's attention to the voice constraints weakens as the output lengthens. The profile is "front-loaded" in the model's processing.

**Fix:**
- Add a mid-script reminder to your Layer 4 prompt: "At the halfway point of the script, re-read the Voice Profile constraints and verify you are still following them. If you detect any drift toward formality or generic language, self-correct immediately."
- For scripts over 1,500 words, split Layer 4 into two passes: voice the first half, then voice the second half separately, pasting the profile again.
- Shorten your profile to the most critical constraints. If it's over 400 words, the AI may lose track. Keep it dense and specific.

---

### Problem 2: Voice Sounds Right in Hooks but Generic in Body Sections

**Cause:** The hook was likely generated with strong voice constraints (from Chapter 5 prompts), but the body sections were generated in Layer 2 (structural skeleton) with no voice instruction, and Layer 4 didn't fully overwrite the formal register.

**Fix:**
- In your Layer 2 prompt, add: "Write the skeleton in a neutral register, but avoid formal vocabulary. No 'therefore,' 'thus,' 'moreover.' Use simple, direct language even in skeleton form."
- In Layer 4, add: "Pay special attention to body sections (Beats 2–5). These are most prone to formal drift. Apply the Colloquial Fingerprint constraints with extra density here."

---

### Problem 3: Humor Feels "AI Funny" Not "Me Funny"

**Cause:** The humor type specification is too abstract. "Self-deprecating" covers a huge range. The AI defaults to the most common version of self-deprecation in its training data.

**Fix:**
- Add a REFERENCE EXAMPLE to your profile: paste 2–3 of your actual jokes/lines with a note explaining the mechanism. "This is my humor: [line]. The mechanism: [unexpected comparison between X and Y, delivered flat]. Replicate this mechanism, not these words."
- Add a negative example: "This is NOT my humor: [generic AI joke]. Never produce anything that sounds like this."
- Specify the setup-punchline structure: "My jokes follow this pattern: [observation] → [unexpected connection] → [flat delivery]. No rimshot. No 'am I right?' energy."

---

### Problem 4: CTA Sounds Like a Different Person

**Cause:** The AI shifts into "YouTuber voice" or "marketing voice" at the CTA because its training data associates CTAs with a specific register.

**Fix:**
- Add a CTA-specific voice instruction to your profile: "The CTA must sound EXACTLY like the rest of the script. Same sentence length. Same vocabulary. Same emotional temperature. If the script is dry and understated, the CTA is dry and understated. Never shift to 'presenter voice' or 'sales voice' at the end. The CTA is a continuation of the conversation, not a commercial break."
- Add to banned phrases: "Smash that subscribe button," "Hit the bell icon," "Don't forget to like and subscribe," "I'll see you in the next one."

---

### Problem 5: Voice Profile Works for One Topic but Not Another

**Cause:** Your Colloquial Fingerprint may be missing topic-specific vocabulary. Your voice sounds right when talking about [topic A] but drifts when talking about [topic B] because the vocabulary of topic B pulls the AI toward a different register.

**Fix:**
- Add topic-specific vocabulary notes to your profile: "When discussing [topic B], use [specific simple terms] instead of [jargon]. Translate all technical terms into [your preferred analogy domain]."
- Test your profile on 3–4 different topics during calibration (Tool 5). If it fails on one, add constraints for that topic's vocabulary.

---

### Problem 6: The Voice Sounds Like a Caricature of Me

**Cause:** The profile is too extreme. You've over-specified quirks (too many fragments, too much slang, too many catchphrases) and the AI is amplifying them into a parody.

**Fix:**
- Dial back density specifications. If you said "50% fragments," try "25–30%."
- Remove any instruction that says "always" and replace with "frequently" or "often."
- Add a balance constraint: "The voice should feel natural, not performed. These are tendencies, not rules. If applying every constraint makes a sentence feel forced, prioritize naturalness."
- Read the output aloud. If it sounds like an impression of you rather than you, the profile is over-specified.

---

### Problem 7: Earlier Layers Are Contaminating the Voice

**Cause:** Your Layer 2 beat script or Layer 3 pacing prompt contains formal language that biases the AI's register, and Layer 4 can't fully overwrite it.

**Fix:**
- Write your beat scripts (Layer 1/2) in your natural vocabulary, even though they're "just structure." If you write "the protagonist must demonstrate vulnerability," the AI mirrors that register. Write "I need to admit the thing I'm embarrassed about" instead.
- In Layer 3, avoid formal pacing language. Not "the presenter should decelerate" but "slow it down here, let it breathe."
- Add to Layer 4: "Ignore any formal register that may have crept in from earlier layers. The Voice Profile overrides all previous tonal signals."

---

---