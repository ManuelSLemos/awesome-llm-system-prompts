# Contributing to Awesome LLM System Prompts

Thank you for your interest in contributing to this repository! Your help is essential to keep this collection updated and useful for the community.

## 🤝 How to Contribute

### 1. Accepted Contribution Types

#### ✅ Welcome
- **Official prompts** with documentation or source links
- **Verified prompts** through reverse engineering with evidence
- **Comparative analysis** between different models
- **Tools** for prompt extraction or analysis
- **Documentation** and structure improvements
- **Translations** to other languages

#### ❌ Not Accepted
- Speculation without evidence
- Made-up or fictional prompts
- Content that violates copyright
- Personal or sensitive information

### 2. Contribution Process

#### Step 1: Fork and Clone
```bash
# Fork the repository on GitHub
git clone https://github.com/your-username/awesome-llm-system-prompts.git
cd awesome-llm-system-prompts
```

#### Step 2: Create Branch
```bash
git checkout -b add-[model-name]-prompt
```

#### Step 3: Add Content
- Place the file in the corresponding folder
- Follow naming conventions
- Include complete metadata
- Add verification evidence

#### Step 4: Commit and Push
```bash
git add .
git commit -m "Add [Model] system prompt from [source]"
git push origin add-[model-name]-prompt
```

#### Step 5: Pull Request
- Open a PR with detailed description
- Include source links
- Explain verification method

## 📋 File Format

### File Structure
```markdown
---
model: "Model Name"
version: "v1.0"
provider: "Company"
source: "official|leaked|reverse-engineered"
date_discovered: "YYYY-MM-DD"
verified: true|false
verification_method: "Method description"
language: "en|es|multi"
context_length: "tokens"
tags: ["tag1", "tag2", "tag3"]
notes: "Additional relevant information"
---

# [Model Name] System Prompt

## Metadata
- **Discovered**: [Date]
- **Source**: [Source type and link if available]
- **Verification**: [How was this verified?]

## System Prompt

```
[Complete prompt here]
```

## Analysis
[Optional prompt analysis]

## Changes from Previous Version
[If applicable, changes from previous versions]

## Evidence
[Links, screenshots, or verification evidence]
```

### Complete Example
```markdown
---
model: "Claude 3 Sonnet"
version: "20240307"
provider: "Anthropic"
source: "reverse-engineered"
date_discovered: "2024-03-15"
verified: true
verification_method: "System message extraction via API"
language: "en"
context_length: "200k"
tags: ["assistant", "helpful", "harmless", "constitutional-ai"]
notes: "Extracted during conversation initialization"
---

# Claude 3 Sonnet System Prompt

## Metadata
- **Discovered**: March 15, 2024
- **Source**: Reverse-engineered via API calls
- **Verification**: Confirmed by multiple users using different methods

## System Prompt

```
The assistant is Claude, made by Anthropic. Claude is helpful, harmless, and honest...
[rest of prompt]
```
```

## 🔍 Verification Methods

### Verification Levels
1. **🟢 Official** - Confirmed by model provider
2. **🟡 Verified** - Confirmed by multiple independent sources
3. **🟠 Probable** - Strong evidence but not fully confirmed
4. **🔴 Unverified** - Requires additional verification

### Extraction Techniques
- **Prompt injection** - Techniques to reveal system instructions
- **Response analysis** - Infer prompts from model behavior
- **Reverse engineering** - Technical analysis of API or interface
- **Official sources** - Documentation, papers, or announcements

## 📊 Folder Structure

```
models/
├── anthropic/
│   └── claude-3-sonnet/
│       ├── claude-3-sonnet_20240307_official.md
│       ├── claude-3-sonnet_20240315_leaked.md
│       └── analysis.md
├── openai/
│   └── gpt-4/
│       ├── gpt-4_20230314_official.md
│       └── variations/
└── analysis/
    ├── comparative-study-march-2024.md
    └── evolution-tracking.md
```

## 🏷️ Tagging Convention

### Main Tags
- `official` - Official prompt
- `assistant` - Conversational assistant model
- `code` - Programming specialized
- `reasoning` - Reasoning focused
- `multimodal` - Multimodal capabilities
- `safety` - Contains safety instructions
- `constitutional-ai` - Uses constitutional AI
- `rlhf` - Trained with RLHF

### Source Tags
- `leaked` - Leaked information
- `reverse-engineered` - Obtained through reverse engineering
- `documented` - Officially documented
- `inferred` - Inferred from behavior

## 🔒 Ethical Considerations

### Principles
- **Transparency**: Promote AI transparency
- **Respect**: Respect intellectual property rights
- **Responsibility**: Responsible use of information
- **Education**: Facilitate research and education

### Boundaries
- Don't publish information that violates terms of service
- Redact personal or sensitive information
- Provide context about potential implications
- Respect takedown requests from providers

## 🛠️ Tools and Scripts

### Validation Scripts
```python
# Example script for format validation
def validate_prompt_file(filepath):
    # Verify metadata
    # Validate markdown format
    # Check structure
    pass
```

### Recommended Tools
- **markdownlint** - Markdown format validation
- **yamllint** - YAML metadata validation
- **pre-commit** - Automatic validation hooks

## 🐛 Reporting Issues

### Before Reporting
- Search existing issues
- Verify it's not a duplicate
- Prepare detailed information

### Information to Include
- **Affected model**
- **Issue type**
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots or evidence**

### Issue Templates
- 🐛 **Bug Report**: For errors or problems
- 💡 **Feature Request**: For new features
- 📝 **Prompt Submission**: For new prompts
- ❓ **Question**: For general questions

## 📞 Contact

- **GitHub Issues**: For technical problems
- **GitHub Discussions**: For general discussion
- **Email**: [maintainer@example.com]
- **Twitter**: [@llm_prompts_repo]

## 🎖️ Recognition

Contributors are recognized in:
- Main README
- Hall of Fame
- Release notes
- Contributor badges

Thank you for helping make this resource better for the entire community! 🚀