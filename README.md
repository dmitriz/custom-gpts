# Custom GPTs Testing Repository

Testing and evaluation framework for OpenAI Custom GPTs. This repository contains tools for evaluating AI response quality using structured rulebooks and test cases.

**Important:** This project focuses on OpenAI's "GPTs" feature (ChatGPT Plus/Enterprise), not third-party services.

## Current Repository Structure

### Implemented Components

- **`rulebooks/rules.md`** - Evaluation criteria with 5-point scoring system
- **`prompts/evaluator-gpt-instructions.md`** - Complete GPT configuration with defined scoring scales  
- **`tests/test-case-1.md`** - Sample API design evaluation test case
- **`PLANNING.md`** - Future roadmap and workflow rules

### Workflow Rules

- HIGH-IMPACT changes only
- NO implementation without approval
- SHORT responses preferred
- NO examples without approval (bias concern)

## Current Status

- ✅ Scoring system complete (1-5 scale defined)
- ✅ Basic test case available  
- ⏳ Additional test topics needed
- ⏳ Edge case testing planned
