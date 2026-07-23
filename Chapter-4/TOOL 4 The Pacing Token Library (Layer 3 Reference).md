## TOOL 4: The Pacing Token Library (Layer 3 Reference)

### *Keep this open during every Layer 3 session. Your complete token vocabulary with usage guidance.*

---

### Core Tokens

| Token | What It Does | When to Use It | Example Placement |
|---|---|---|---|
| `[PAUSE 1s]` | Brief beat of silence | Before a key revelation; after a surprising statement; before a pivot | "And the number that changed everything was— [PAUSE 1s] —zero." |
| `[PAUSE 2s]` | Longer, weighted silence | After an emotional admission; before the biggest reveal; at the end of a section | "I hadn't told anyone that. [PAUSE 2s] But here's why I'm telling you now." |
| `[FAST ENERGY]` | Accelerate delivery, shorter sentences | During lists, escalations, "here's what happened next" moments, building excitement | "[FAST ENERGY] Three apps. Three weeks. Three crashes. Same pattern. Every. Single. Time." |
| `[SLOW DOWN]` | Decelerate, longer sentences, reflective weight | During vulnerable admissions, reframes, "here's what I learned" moments | "[SLOW DOWN] And I think the reason we don't talk about this is because admitting it means admitting we built our entire identity on a system that was never designed to love us back." |
| `[B-ROLL: ___]` | Visual break / illustration | After a claim needing evidence; during a list; at a transition; when the viewer needs to *see* something | "[B-ROLL: Screen recording of my app graveyard — 43 icons, most with a single use timestamp]" |
| `[REACTION BEAT]` | Physical reaction from presenter | After something absurd; during a "can you believe this?" moment; at a pattern interrupt | "They charged me $200 for the 'premium' tier. [REACTION BEAT] *stares at camera*" |
| `[WHISPER EMPHASIS]` | Drop volume for intimacy/secrecy | When sharing something that feels like insider knowledge; a confession; a "just between us" moment | "[WHISPER EMPHASIS] And here's the part they don't put in the documentation..." |
| `[LAUGH BREAK]` | Natural levity / chuckle | After a dry joke; during a self-deprecating admission; to release built-up tension | "I color-coded my calendar. For fun. [LAUGH BREAK] Yeah. I know." |
| `[BEAT]` | Micro-pause (<1 second) | For comedic timing; before a punchline word; after a setup | "The best productivity system is the one you'll actually— [BEAT] —use." |

---

### Placement Rules (The Grammar of Pacing)

| Rule | Explanation |
|---|---|
| Pauses go BEFORE revelations, not after | The silence creates anticipation. The reveal fills it. |
| [FAST ENERGY] sections use sentences under 10 words | Short = fast. The token tells the AI to compress. |
| [SLOW DOWN] sections allow sentences of 20–25 words | Long = reflective. The token tells the AI to expand. |
| [B-ROLL] never interrupts mid-thought | Place it at natural breaks: after a complete idea, between sections, during a list. |
| Max 2 [PAUSE] tokens per 100 words | More than that and the script feels halting, not dramatic. |
| [LAUGH BREAK] follows the joke, doesn't precede it | The laugh is the release. The joke is the setup. |
| [WHISPER EMPHASIS] max once per script section | Overuse kills the intimacy effect. |
| Every [FAST ENERGY] section needs a [SLOW DOWN] or [PAUSE] within 3 sentences | You can't sprint forever. The contrast creates the rhythm. |

---

### Emotional Stage Direction Templates

Add these to your Layer 3 prompt to guide token placement per section:

```
EMOTIONAL STAGE DIRECTIONS:
- Hook (0:00–0:15): Sharp, slightly confrontational. [FAST ENERGY]
  opening. One [BEAT] before the key claim. No [PAUSE] here—
  momentum is everything.

- Stakes (0:15–0:35): Personal, vulnerable. [SLOW DOWN]. One
  [PAUSE 2s] after the personal admission. Sentence length: 15–22
  words. Let it breathe.

- Tension Loop (0:35–0:45): Mysterious, forward-pulling. One
  [WHISPER EMPHASIS] or [PAUSE 1s] before the teased revelation.

- Body Sections: Building energy. Mix [FAST ENERGY] for lists/
  evidence with [SLOW DOWN] for insights. [B-ROLL] at every
  claim that needs visual proof.

- Payoff: Warm, resolved. [SLOW DOWN]. One [PAUSE 2s] before
  the final reframe. Slightly triumphant energy.

- CTA: Casual, low-pressure. Normal pacing. One [BEAT] before
  the specific action step. No [FAST ENERGY]—this is an
  invitation, not a sales pitch.
```

---

---