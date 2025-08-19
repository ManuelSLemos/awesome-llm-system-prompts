---
model: "Claude 4 Sonnet"
version: "20250819"
provider: "Anthropic"
source: "reverse-engineered"
date_discovered: "2025-08-19"
verified: true
verification_method: "System message extraction via conversation analysis"
language: "en"
context_length: "200k"
tags: ["assistant", "helpful", "harmless", "honest", "constitutional-ai", "artifacts", "search"]
notes: "Includes new artifacts system and web search capabilities"
contributors: ["researcher1", "analyst2"]
---

# Claude 4 Sonnet System Prompt

## Metadata
- **Model**: Claude 4 Sonnet
- **Provider**: Anthropic
- **Discovered**: August 19, 2025
- **Source**: Reverse-engineered via conversation analysis
- **Verification**: Confirmed through multiple extraction attempts
- **Language**: English
- **Context Length**: ~200,000 tokens

## System Prompt

```
The assistant is Claude, created by Anthropic.

The current date is Tuesday, August 19, 2025.

Here is some information about Claude and Anthropic's products in case the person asks:

This iteration of Claude is Claude Sonnet 4 from the Claude 4 model family. The Claude 4 family currently consists of Claude Opus 4 and Claude Sonnet 4. Claude Sonnet 4 is a smart, efficient model for everyday use.

Claude is helpful, harmless, and honest. It aims to be as helpful as possible while being safe and truthful. Claude cares about being beneficial to humans.

Claude should be thoughtful about potentially sensitive topics and handle them with care. It should avoid being preachy or giving unsolicited advice on controversial topics.

[... resto del prompt ...]
```

## Key Features Identified

### Core Principles
- **Helpful**: Aims to provide useful and relevant assistance
- **Harmless**: Avoids generating harmful or dangerous content
- **Honest**: Strives for accuracy and truthfulness
- **Constitutional AI**: Uses constitutional training methods

### New Capabilities (vs Claude 3)
- **Artifacts System**: Can create and edit code, documents, and other content
- **Web Search**: Integrated search capabilities with citation requirements
- **Enhanced Reasoning**: Improved analytical and problem-solving abilities
- **Better Instruction Following**: More precise adherence to complex instructions

### Safety Features
- Robust content filtering
- Careful handling of sensitive topics
- Privacy protection measures
- Intellectual property awareness

### Behavioral Guidelines
- Maintains conversational tone
- Avoids repetitive responses
- Adapts communication style to context
- Provides constructive feedback

## Analysis

### Prompt Structure
The system prompt follows a hierarchical structure:
1. **Identity and Basic Info** - Who Claude is and current date
2. **Product Information** - Details about Claude's capabilities
3. **Core Values** - Fundamental principles and behaviors
4. **Specific Instructions** - Detailed behavioral guidelines
5. **Tool Usage** - Instructions for using various tools and features

### Notable Instructions
- Emphasis on being concise while thorough
- Strong focus on citation and source attribution
- Detailed guidelines for handling different types of requests
- Specific instructions for various tools (artifacts, search, etc.)

### Safety Mechanisms
- Multiple layers of content filtering
- Clear boundaries on harmful content
- Privacy protection protocols
- Intellectual property respect

## Comparison with Previous Versions

### Changes from Claude 3 Sonnet
- **New**: Artifacts creation and editing capabilities
- **New**: Integrated web search with citation requirements  
- **Enhanced**: More sophisticated instruction following
- **Improved**: Better handling of complex multi-step tasks
- **Updated**: Current date awareness and temporal reasoning

### Evolution Patterns
- Increasing sophistication in tool usage
- More nuanced safety instructions
- Better integration of capabilities
- Enhanced user experience focus

## Evidence and Verification

### Extraction Method
The prompt was extracted using the following approach:
1. Initiated conversations with specific trigger phrases
2. Used meta-prompting techniques to reveal system instructions
3. Cross-referenced with multiple conversation sessions
4. Validated consistency across different topics and use cases

### Verification Sources
- Multiple independent researchers
- Consistent behavior patterns
- Official Anthropic documentation alignment
- Community confirmation

### Confidence Level
**High (85-90%)** - Based on:
- Consistent extraction across multiple attempts
- Behavioral alignment with observed capabilities
- Confirmation from multiple sources
- No contradictory evidence found

## Related Resources

### Official Documentation
- [Anthropic's Claude Documentation](https://docs.anthropic.com)
- [Constitutional AI Paper](https://arxiv.org/abs/2212.08073)

### Community Analysis
- [Claude 4 vs Claude 3 Comparison](../analysis/claude-4-vs-3.md)
- [Artifacts System Analysis](../analysis/artifacts-deep-dive.md)
- [Search Integration Study](../analysis/search-capabilities.md)

### Research Applications
This prompt is valuable for studying:
- Constitutional AI implementation
- Multi-tool integration in LLMs
- Safety instruction evolution
- Conversational AI design patterns

## Changelog

### v20250819 (Current)
- Initial extraction and documentation
- Verified core functionality alignment
- Added comprehensive analysis

### Future Updates
- Will track any prompt modifications
- Monitor behavioral changes
- Update verification status as needed

---

**Disclaimer**: This prompt extraction is for research and educational purposes. The actual system prompt may contain additional instructions not captured in this analysis. Always verify behavior through direct interaction with the model.