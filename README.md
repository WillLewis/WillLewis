# Will Lewis

AI/ML Product Manager — agentic systems, evals, and ML decisioning in regulated environments.

8+ years shipping 0-1 AI products. Most recently led a neurosymbolic multi-agent review system at Capital One that cut high-volume fraud/ops review time from \~20 minutes to \~2 minutes across 1M monthly cases. Before that: enterprise RAG at HPE (support tickets reduced 30%), ML content tagging at Stanford Medicine (\~$400K annual savings), and computer-vision fraud detection at a C2B marketplace.

The thesis that runs through everything here: **agents propose, code decides.** Models are good at compressing the messy middle of a workflow. The harness — policy layer, held-out evals, deterministic gates — is what makes them shippable. So that's what I build.

## Selected work

**[atlas-agentic-fraud-lab](https://github.com/WillLewis/atlas-agentic-fraud-lab)** — Red-team agents attack a mock fraud scorer, defense agents propose fixes, a deterministic judge decides. Recall at capped customer friction went 27% → 97% across three rounds — and the judge rejected the Round 1 fix that looked good on found examples but failed the locked holdout. That rejection is the point.

**[agent-harness-environment](https://github.com/WillLewis/agent-harness-environment)** — Coding agents pass the tests they can see. A held-out battery they never see shows a 2.5x quality spread across model tiers that the visible pass rate (100% everywhere) is blind to. Goodhart's law, instrumented.

**[regulated-agent-launch-kit](https://github.com/WillLewis/regulated-agent-launch-kit)** — Turns traces, evals, regression seeds, and approval gates into a launch/no-launch recommendation. Current verdict on its own synthetic case study: **NO-GO** — a semantic gate caught 14 overpromises a lexical grader cleared. A launch kit that can't say no isn't one.

**[voice-agent-prompt-lab](https://github.com/WillLewis/voice-agent-prompt-lab)** — Local-first prompt and eval lab for an insurance FNOL voice agent. 114/114 eval gate, 5 real regressions caught during prompt iteration.

Live demos and full case studies: **[wxl3.com](https://wxl3.com)**

## Background

Wharton MBA · Penn Economics · UC Berkeley graduate coursework in data science. PM since 2018, ML focus since 2017. Particular interest in adversarial systems, agentic automation, and football.

Open to Senior PM and Group PM roles · NYC / SF / Remote · Available June 2026
📫 [willxemail@gmail.com](mailto:willxemail@gmail.com) · [LinkedIn](https://www.linkedin.com/in/willlinkedin/)
