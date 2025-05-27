# Custom GPTs Testing Repository

Testing and evaluation framework for OpenAI Custom GPTs. This repository contains tools for evaluating AI response quality using structured rulebooks and test cases.

**Important:** This project focuses on OpenAI's "GPTs" feature (ChatGPT Plus/Enterprise), not third-party services.

## Current Repository Structure

## 📁 Current Repository Structure

### ✅ Implemented Components

- **📜 `rulebooks/rules.md`** - Evaluation criteria and scoring framework ([see evaluation rules](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_format_inputs_to_ChatGPT_models.md))
- **🎯 `gpt-evaluator-simple.md`** - Simplified GPT configuration for initial testing  
- **📊 `evaluations/test-case-1.md`** - Sample API design evaluation scenario
- **📋 `PLANNING.md`** - Future roadmap and workflow rules

### 📂 Directory Details

- **`rulebooks/`** - Structured evaluation criteria and scoring rubrics for AI response quality
- **`evaluations/`** - Test scenarios and evaluation cases (not software tests - AI response evaluations)  
- **`prompts/`** - Complex GPT instructions (moved to backlog - too advanced for initial testing)
- **`.github/`** - Project workflow rules and Copilot instructions

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
