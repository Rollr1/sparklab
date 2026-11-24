# SparkLab curriculum ideas

Working notes on what kids aged 10 to 15 should learn about AI, and what parents will pay for. The prototype implements Unit 1 in full; everything else here is a proposal to iterate on.

## The promise to parents

> In five minutes a day, your kid learns to **direct** AI, **question** it, and **build** real things with it, safely.

Parents are not paying for "screen time with AI." They are paying for three things they worry their kid will miss:

1. **A head start.** AI is becoming a basic tool like typing or search. Parents want their kid fluent early, not left behind.
2. **Good judgment.** Parents fear AI will make kids lazy or gullible (cheating, believing made-up facts, deepfakes, oversharing). A product that teaches kids to check AI and use it honestly answers that fear directly.
3. **Visible proof of progress.** Parents need to see what their kid learned without sitting through it: skills, streaks, real work they made, and a question to ask at dinner.

## What kids should learn (the skill pillars)

Every unit maps to one or more of these. They are written so a parent can read them on the progress page.

| Pillar | What the kid can do | Why parents care |
|---|---|---|
| **Direct AI** | Write clear, specific prompts; give context, constraints and examples; iterate on results | The core skill of every AI tool, at school and later at work |
| **Question AI** | Spot made-up facts, wrong numbers and bias; verify with trusted sources | Protects against misinformation and over-trust |
| **Stay safe** | Protect personal info, recognize scams and deepfakes, know when to ask an adult | The #1 worry parents have about AI |
| **Use AI honestly** | Use AI to understand and practice, not to hand in its work; know school rules | Parents and teachers worry about cheating |
| **Make real things** | Go from idea to a real object, program, story or artwork with AI as a helper | Turns screen time into building; something to show off |
| **Understand AI** | Explain in simple terms how AI learns from data and why it makes mistakes | Demystifies the tech; foundation for future CS learning |

## Course map

**Unit 1. Make it real: AI + 3D printing (built in the prototype)**
1. How 3D printers build: filament, nozzle, layers, overhangs (quiz)
2. From idea to object: the maker workflow, AI as a partner (ordering game)
3. Prompt like a maker: the 5 ingredients of a design prompt (live AI or offline coach scores the kid's prompt)
4. AI design studio: describe a keychain, phone stand or pencil cup in words, watch a 3D model update, iterate
5. Spot the AI's mistakes: too big for the bed, walls too thin, floating parts, wrong safety facts, privacy grabs
6. Slice and print: layer height, infill and supports trade-offs, then watch their own design print layer by layer

Why 3D printing first: it is the most tangible demo of AI. The kid types words and ends with something they can hold, and every step naturally teaches prompting, checking AI output, and iteration.

**Proposed next units**
- **Talk to AI: prompting basics.** Role, context, examples, step-by-step asks. Mini-games: "make the bot answer like a pirate," "get a recipe for exactly 3 people."
- **Safe and smart with AI.** Personal info, AI scams, voice clones and deepfakes, what to do if something feels off. Strong parent-sell unit; consider making it free.
- **Is that true? Fact-checking AI.** Hallucinations, checking sources, lateral reading. Game: one of three AI answers is made up, find it.
- **AI study buddy, not a cheat code.** Use AI to explain, quiz you, and give feedback on your own draft. Clear lines on what's honest.
- **Create with AI.** Art, music, stories. Plus who owns what AI makes and giving credit.
- **How AI learns.** Train a tiny classifier in the browser with your own examples; see bias appear when the data is lopsided.
- **Build a bot.** First Python or Scratch-style program written with an AI pair programmer.
- Later: AI for robotics, drones, video editing, starting a small business with AI.

## Lesson design rules

- **5 minutes, 3 to 6 steps.** Short enough for a daily habit.
- **Mix interaction types.** Quiz, ordering, free-text prompts, sliders, hands-on builders. Never three quizzes in a row without something hands-on.
- **Every lesson ends in a skill a parent can read** and a "talk about it at dinner" question.
- **Teach through mistakes.** When the kid asks for something unprintable, the app explains why (bed size, wall thickness) instead of silently failing.
- **AI as coach, never as answer key.** Live AI gives feedback on the kid's own work; it doesn't do the task for them.

## Fun and motivation

- XP, daily streaks, unit badges (Maker Level 1), confetti at the end of a lesson.
- A mascot (Bolt) who coaches in a friendly, short voice.
- Ideas to add: weekly challenges ("design something for your pet"), a gallery of the kid's designs, optional real prints mailed home or printed at a library makerspace, friend leagues with parent-approved friends only.

## Safety and trust (non-negotiables)

- No open chat with strangers; any social features are parent-approved.
- Live AI runs behind a kid-safe system prompt and only on specific tasks (feedback on a prompt, not open-ended chat), with an offline fallback.
- No ads. Minimal data: first name only for the kid. COPPA compliance needed before launch for under-13s (verifiable parental consent).
- A parent dashboard that shows what the kid did, including the actual prompts they wrote.

## Business model notes

- Monthly family subscription, with Unit 1 or the safety unit free as a trial.
- Parent progress page and weekly email recap are the main retention and renewal driver for the payer.
- Possible upsells: monthly print box (we print their best design and mail it), school or makerspace licenses.

## Open questions

- Ages 10 to 15 is a wide band. Split into two tracks (10 to 12 and 13 to 15) with different tone and depth?
- Which real text-to-3D tool should the studio connect to later, and is it safe for kids?
- How much live AI per kid per month can the price support?
