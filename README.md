# JAILBREAK-AI

<p align="center">
  <img src="https://img.shields.io/badge/Status-Research%20%26%20Security-blue" alt="Status" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
  <img src="https://img.shields.io/badge/Language-English%20%2F%20French-orange" alt="Language" />
  <img src="https://img.shields.io/badge/Focus-AI%20Security%20%26%20Robustness-red" alt="Focus" />
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#project-goals">Project goals</a> ·
  <a href="#models-directory">Models directory</a> ·
  <a href="#security-and-responsibility">Security</a> ·
  <a href="#contributing">Contributing</a>
</p>

This repo is a personal collection of notes, prompts, and experiments around AI behavior, prompt robustness, and model evaluation.

I put it together to compare how different models react to edge cases, adversarial inputs, and prompt design choices.

## Overview

The goal here is mostly to document patterns, test limits, and keep notes in one place. It is focused on model behavior, prompt injection, and defensive evaluation in controlled and authorized settings.

This is not meant for bypassing protections, exploiting systems without permission, or doing anything unsafe. The point is to study weaknesses, understand failure modes, and look at safer ways to evaluate models.

## Project goals

- Compare behavior across model families
- Keep prompts, findings, and notes together
- Test robustness and edge cases
- Document model limitations in a structured way
- Support responsible AI research and evaluation

## Models directory

The project is organized by model family to make comparisons easier.

| Model family | Directory | Notes |
| --- | --- | --- |
| ChatGPT / GPT / OpenAI | `chatgpt/` | Notes, prompts, and experiments around ChatGPT and related models |
| Claude / Haiku | `claude/` | Claude-related resources and notes |
| Gemini / Gemma | `gemini/` | Gemini and Gemma resources |
| DeepSeek | `deepseek/` | DeepSeek-related resources |
| Devin | `devin/` | Devin-related resources |
| Grok | `grok/` | Grok-related resources |
| Qwen | `qwen/` | Qwen-related resources |

## Repository structure

```text
JAILBREAK-AI/
├── README.md
├── LICENSE
├── chatgpt/
├── claude/
├── gemini/
├── deepseek/
├── devin/
├── grok/
├── qwen/
├── docs/
│   ├── research-notes.md
│   ├── prompt-robustness.md
│   └── defensive-guidance.md
├── examples/
│   ├── evaluation/
│   └── prompts/
├── scripts/
│   └── utilities/
├── tests/
│   └── validation/
├── requirements.txt
├── .gitignore
└── .github/
```

## Project roadmap

### Phase 1 — Foundation
- Set up the repository structure
- Organize model families and folders
- Add the main documentation

### Phase 2 — Research indexing
- Gather model-specific notes and resources
- Add prompt and evaluation observations
- Improve comparison across models

### Phase 3 — Defensive analysis
- Track adversarial cases and patterns
- Document mitigation ideas and safety checks
- Build a reusable research base

### Phase 4 — Expansion
- Add more examples and references
- Improve documentation quality
- Keep the repo useful for future experiments

## Security and responsibility

This repository is intended for research, testing, and educational purposes under controlled and authorized conditions.

It is not meant for:
- bypassing platform protections,
- unauthorized access,
- policy violations,
- malicious or illegal activity,
- unsafe exploitation of systems without permission.

All content should be used responsibly and in compliant environments.

## Contributing

Contributions are welcome when they are relevant, clear, and aligned with the project’s goals.

A simple workflow:
1. Fork the repository
2. Create a branch for your work
3. Add or improve research content
4. Open a pull request with a clear description

## License

This project is distributed under the MIT License. See `LICENSE` for details.

---

<p align="center">
  <sub>Built for responsible AI research and model evaluation.</sub>
</p>
