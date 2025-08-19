# Awesome LLM System Prompts 🤖

A curated collection of system prompts from various Large Language Models (LLMs), including official releases and community discoveries.

## 📋 Table of Contents

- [About](#about)
- [Repository Structure](#repository-structure)
- [Models Covered](#models-covered)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)
- [License](#license)

## About

This repository aims to document and preserve system prompts from various LLMs to:
- Foster transparency in AI systems
- Enable research and analysis
- Help developers understand prompt engineering techniques
- Create a historical record of prompt evolution

## Repository Structure

```
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── example-prompt-file.md
├── models/
│   ├── anthropic/
│   │   ├── claude-3-opus/
│   │   ├── claude-3-sonnet/
│   │   ├── claude-3-haiku/
│   │   └── claude-4-sonnet/
│   ├── openai/
│   │   ├── gpt-3.5-turbo/
│   │   ├── gpt-4/
│   │   ├── gpt-4-turbo/
│   │   └── o1-preview/
│   ├── google/
│   │   ├── gemini-pro/
│   │   ├── gemini-ultra/
│   │   └── bard/
│   ├── meta/
│   │   ├── llama-2/
│   │   └── llama-3/
│   ├── microsoft/
│   │   └── copilot/
│   └── other/
├── analysis/
│   ├── prompt-patterns.md
│   ├── evolution-timeline.md
│   └── comparative-analysis.md
└── tools/
    ├── prompt-extractor.py
    └── analysis-scripts/
```

## Models Covered

### 🔵 Anthropic
- **Claude 4 Sonnet** - Latest version (August 2025)
- **Claude 3 Opus** - Most capable model
- **Claude 3 Sonnet** - Balanced performance
- **Claude 3 Haiku** - Fast and efficient

### 🟢 OpenAI
- **GPT-4 Turbo** - Enhanced version
- **GPT-4** - Original flagship model
- **GPT-3.5 Turbo** - Widely used variant
- **O1-Preview** - Reasoning-focused model

### 🔴 Google
- **Gemini Ultra** - Most capable
- **Gemini Pro** - General purpose
- **Bard** - Conversational AI

### 🔵 Meta
- **Llama 3** - Latest open model
- **Llama 2** - Previous generation

### 🟡 Microsoft
- **Copilot** - Integrated assistant

### Others
- Mistral AI models
- Cohere models
- Perplexity AI
- Community fine-tunes

## File Naming Convention

Each prompt file follows this naming pattern:
```
[model-name]_[version]_[date]_[source].md
```

Examples:
- `claude-4-sonnet_20250819_official.md`
- `gpt-4-turbo_20240315_leaked.md`
- `gemini-pro_20240201_reverse-engineered.md`

## Metadata Format

Each prompt file includes this metadata header:

```yaml
---
model: "Claude 4 Sonnet"
version: "20250819"
source: "official"
date_discovered: "2025-08-19"
verified: true
language: "en"
context_length: "200k"
tags: ["assistant", "helpful", "harmless", "honest"]
---
```

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### How to Contribute
1. **Fork** the repository
2. **Create** a new branch for your contribution
3. **Add** the system prompt with proper metadata
4. **Verify** the prompt's authenticity when possible
5. **Submit** a pull request

### Contribution Types
- ✅ Official prompts from model providers
- ✅ Reverse-engineered prompts with evidence
- ✅ Leaked prompts with verification
- ✅ Analysis and comparative studies
- ❌ Speculation without evidence
- ❌ Proprietary content without permission

## Verification Levels

- 🟢 **Verified Official** - Confirmed by model provider
- 🟡 **Community Verified** - Multiple independent confirmations
- 🟠 **Probable** - Strong evidence but not fully confirmed
- 🔴 **Unverified** - Requires additional verification

## Analysis Tools

The repository includes tools for:
- Prompt extraction and parsing
- Similarity analysis between models
- Evolution tracking over time
- Pattern identification
- Statistical analysis

## Research Applications

This collection enables research in:
- **Prompt Engineering** - Understanding effective techniques
- **AI Safety** - Analyzing safety instructions and constraints
- **Model Behavior** - Correlating prompts with outputs
- **Evolution Studies** - Tracking changes over time
- **Comparative Analysis** - Understanding different approaches

## Ethical Considerations

- All prompts are collected for educational and research purposes
- We respect intellectual property rights
- Sources are properly attributed
- Sensitive information is redacted when necessary

## Disclaimer

This repository is for educational and research purposes only. System prompts may be:
- Incomplete or outdated
- Subject to change by model providers
- Protected by intellectual property rights
- Not representative of current model behavior

Always verify information independently and respect terms of service.

## License

This project is licensed under MIT License - see [LICENSE](LICENSE) file for details.

## Contact

- **Issues**: Use GitHub issues for questions or problems
- **Discussions**: Use GitHub discussions for general conversation
- **Email**: [your-email@example.com]

---

⭐ **Star this repository** if you find it useful for your research or development work!

## Recent Updates

- **2025-08-19**: Added Claude 4 Sonnet system prompt
- **2025-08-15**: Improved verification methodology
- **2025-08-10**: Added comparative analysis tools
- **2025-08-05**: Repository restructure for better organization

## Statistics

- **Total Models**: 25+
- **Total Prompts**: 150+
- **Contributors**: 50+
- **Last Updated**: August 2025