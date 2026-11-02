# JAILBREAK-AI

<p align="center">
  <img src="https://img.shields.io/badge/Status-Research%20%26%20Security-blue" alt="Status" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
  <img src="https://img.shields.io/badge/Language-English%20%2F%20French-orange" alt="Language" />
  <img src="https://img.shields.io/badge/Focus-AI%20Security%20%26%20Robustness-red" alt="Focus" />
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#project-roadmap">Roadmap</a> ·
  <a href="#models-directory">Models directory</a> ·
  <a href="#security-and-responsibility">Security</a> ·
  <a href="#contributing">Contributing</a>
</p>

A curated research repository focused on AI security, prompt robustness, adversarial testing, and responsible evaluation of large language models.

## Overview

This repository is designed for structured research, defensive testing, and model analysis in controlled, ethical, and authorized environments. It brings together notes, prompts, and observations around how AI systems behave under adversarial conditions and how they can be evaluated more responsibly.

The goal is not to bypass protections or violate platform policies, but to better understand model weaknesses, prompt injection behavior, robustness limits, and defensive evaluation methods.

## Project goals

- Study prompt robustness and model limitations
- Document adversarial behavior and edge cases
- Compare model families and evaluation patterns
- Organize research files by model family
- Promote safe, transparent, and responsible AI analysis

## Models directory

The project is organized by model family for easier navigation and comparison.

| Model family | Directory | Notes |
| --- | --- | --- |
| ChatGPT / GPT / OpenAI | `chatgpt/` | Includes ChatGPT, GPT, and OpenAI-related resources |
| Claude / Haiku | `claude/` | Includes Claude and Anthropic-related resources |
| Gemini / Gemma | `gemini/` | Includes Gemini and Gemma-related resources |
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
- Define structure and model family organization
- Establish repository conventions
- Add central documentation and navigation

### Phase 2 — Research indexing
- Consolidate model-specific resources
- Add prompt and evaluation notes
- Improve comparative analysis across model families

### Phase 3 — Defensive analysis
- Track adversarial cases and behaviors
- Document mitigation patterns and safety heuristics
- Build a reusable research knowledge base

### Phase 4 — Expansion
- Add more analysis resources and examples
- Improve reproducibility and documentation quality
- Support broader collaborative research workflows

## Security and responsibility

This repository is intended strictly for educational, research, and defensive security purposes.

It does not support or encourage:
- bypassing platform protections,
- unauthorized access,
- policy violations,
- malicious or illegal activity,
- unsafe exploitation of systems without authorization.

All content should be used only in controlled, authorized, and legally compliant environments.

## Contributing

Contributions are welcome when they are relevant, documented, and aligned with the project’s research and ethical goals.

Recommended flow:
1. Fork the repository
2. Create a dedicated branch
3. Add or refine research content
4. Open a pull request with a clear description

## License

This project is distributed under the MIT License. See `LICENSE` for details.

---

<p align="center">
  <sub>Built for responsible AI research and model evaluation.</sub>
</p>
