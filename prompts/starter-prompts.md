# Starter Prompts

Use these prompts with **Assuring Learning After Automation** and this companion repo. They are designed for a back-and-forth session with an agent.

## Understand The Argument

**Best for:** getting the clean version of the essay before debating or applying it.

```text
Use "Assuring Learning After Automation" and the companion repo to explain the argument in 10 bullets.

Do not turn this into a generic AI-in-education summary. Preserve the specific claim: once AI can produce the visible artifact, NWC must teach and assess frame ownership, appropriate reliance, and human accountability.

Start with the files:
- README.md
- AGENTS.md
- claims.md
- sources/source-spine.md

Return:
1. the thesis in one sentence;
2. the argument in 10 bullets;
3. the claim most likely to be misunderstood;
4. why that misunderstanding is tempting;
5. two questions NWC faculty should keep open.
```

## Inspect The Claims

**Best for:** letting Dan/Rich or faculty pressure-test the essay instead of passively receiving it.

```text
Use the companion repo to help me inspect the evidence behind "Assuring Learning After Automation."

First, read:
- claims.md
- sources/source-spine.md

Then list 5-7 important claims from the essay that are worth auditing. For each one, give me a short label and one sentence on why it matters.

Ask me which claim I want to inspect.

After I pick a claim, audit it with me. Return:
1. the best evidence in the repo;
2. the strongest unresolved question or counterexample;
3. where the evidence is strong, weak, or incomplete;
4. what source I should read if I want to go deeper;
5. one practical implication for NWC instruction.

Keep it conversational. Do not defend the essay by default, and do not bury me in sources before I choose the claim.
```

## Design An NWC Exercise

**Best for:** turning the essay into a concrete faculty activity.

```text
I want to turn "Assuring Learning After Automation" into a practical NWC learning exercise.

Read:
- README.md
- AGENTS.md
- claims.md
- cases/cyber-group-strategy-transfer-case.md
- artifacts/traceable-learning-artifact.md

Design a 60-90 minute exercise for NWC faculty or students that uses the essay's method.

The exercise must:
1. begin by interrogating the essay itself;
2. then transfer the method to an approved NWC-style artifact;
3. force the learner to identify the frame, assumptions, evidence standard, and AI reliance decisions;
4. include a flawed AI output or flawed frame for critique;
5. end with a traceable learning artifact faculty can inspect.

Return:
- learning objective;
- materials needed;
- step-by-step flow;
- facilitator notes;
- student/faculty outputs;
- assessment criteria;
- likely failure modes.
```

## Create A Flawed AI Assessment

**Best for:** making AI fluency an object of critique rather than a shortcut.

```text
Create a polished, confident, but flawed strategic assessment for students to critique.

Use:
- claims.md
- cases/cyber-group-strategy-transfer-case.md
- artifacts/traceable-learning-artifact.md

The flaw should be at the level of frame, assumptions, evidence standard, reliance, or risk treatment. It should not depend on an obvious factual error.

After the student-facing assessment, provide an instructor-only key:
1. hidden frame;
2. flawed assumptions;
3. missing evidence;
4. risk or tradeoff the answer buries;
5. questions that would expose the flaw in oral defense;
6. what a stronger frame would include;
7. what students should record in the traceable learning artifact.
```

## Run Oral Defense

**Best for:** checking whether the learner owns the frame behind an AI-assisted artifact.

```text
Act as an NWC seminar instructor conducting a short oral defense.

Read:
- AGENTS.md
- claims.md
- artifacts/traceable-learning-artifact.md

Ask one question at a time. Your goal is to determine whether I own the frame behind my AI-assisted work.

Press me on:
- problem frame;
- assumptions;
- evidence standards;
- alternative frames;
- reliance decisions;
- rejected AI outputs;
- risks and costs;
- what would change my conclusion;
- where human judgment must interrupt automation.

After six questions, assess whether I demonstrated ownership of the reasoning and identify what evidence should be added to the traceable learning artifact.
```

## Build The Trace

**Best for:** turning an AI-assisted exercise into evidence faculty can inspect.

```text
Using the critique or exercise we just completed, create a traceable learning artifact.

Read:
- artifacts/traceable-learning-artifact.md
- claims.md

Return a completed artifact with:
1. problem frame;
2. assumptions;
3. evidence standard;
4. AI role and boundaries;
5. accepted AI contributions;
6. rejected or revised AI contributions;
7. reliance decisions;
8. oral-defense questions;
9. final human judgment;
10. faculty review notes.

Keep it practical enough to use in one seminar, not as a compliance packet.
```

