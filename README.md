# Assuring Learning After Automation: Agent Mode

This repo is the companion source kit for **Assuring Learning After Automation**, a long-form essay and faculty-facing prototype about assurance of learning, frame literacy, and AI-enabled judgment at the National War College.

Use it with Codex, Claude Code, OpenClaw, or another coding agent to turn the essay into a working session. The essay argues that once AI can produce polished artifacts, the evidence of learning must move upstream: students and leaders need to own the frame, calibrate reliance, contest outputs, preserve developmental friction, and defend judgment under questioning.

## Connect Your Agent

Paste this into your coding agent:

```text
You are helping me read and use the essay "Assuring Learning After Automation."
https://nwc-learning-companion.web.app

Use this companion GitHub repo as your source of truth:
https://github.com/jackcshaw/nwc-learning-companion

If you can access GitHub or run shell commands, clone or open that repo first. Start with only these files:
- README.md
- AGENTS.md
- claims.md
- prompts/starter-prompts.md
- prompts/objections-and-responses.md
- sources/source-spine.md
- cases/cyber-group-strategy-transfer-case.md
- artifacts/traceable-learning-artifact.md

Do not answer from the essay alone. Use the repo to help me do one useful thing with the argument.

Start by giving me:
1. the cleanest version of the core claim;
2. the part of the argument most relevant to an NWC instructor or curriculum leader;
3. the most useful starter prompt from the repo for my next step.

If I ask to inspect evidence, read `claims.md` and `sources/source-spine.md`. If I ask to design an exercise, read `cases/cyber-group-strategy-transfer-case.md` and `artifacts/traceable-learning-artifact.md`. If I ask to argue with the essay, read `prompts/objections-and-responses.md`.

If you cannot access GitHub directly, tell me the smallest set of repo files you need me to paste before you continue.
```

## Start Here

| I want to... | Use this |
| :-- | :-- |
| Give my agent operating instructions | [`AGENTS.md`](AGENTS.md) |
| Copy starter prompts | [`prompts/starter-prompts.md`](prompts/starter-prompts.md) |
| Work through objections | [`prompts/objections-and-responses.md`](prompts/objections-and-responses.md) |
| Inspect the core claims | [`claims.md`](claims.md) |
| See the source spine | [`sources/source-spine.md`](sources/source-spine.md) |
| Build the NWC transfer exercise | [`cases/cyber-group-strategy-transfer-case.md`](cases/cyber-group-strategy-transfer-case.md) |
| Create the learning trace | [`artifacts/traceable-learning-artifact.md`](artifacts/traceable-learning-artifact.md) |

## What This Repo Is For

This repo answers four practical questions:

- **What is the argument?** AI weakens the artifact as evidence of learning. NWC can respond by teaching and assessing frame ownership.
- **What should faculty inspect?** The claim map and source spine separate the essay's argument from the evidence and open questions behind it.
- **What should students practice?** The prompts turn the essay into activities around framing, assumptions, reliance, flawed outputs, oral defense, and reusable artifacts.
- **What should the institution save?** The traceable learning artifact records frame choices, reliance decisions, rejected outputs, and faculty review notes so learning can compound.

## Public-Safe Boundary

This repo is intended to be public and unclassified. It includes the essay, prompts, claim maps, and links to public sources. It does not include local course artifacts or private NWC materials. The Cyber Group Strategy transfer case is described as a practice pattern; instructors should attach only artifacts they are authorized to use.

