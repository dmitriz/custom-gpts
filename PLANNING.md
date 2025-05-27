# Custom GPT Testing Project - Planning & Ideas

## Project Goal

Testing OpenAI Custom GPTs for professional-level AI assistance. 

**Important:** This refers specifically to OpenAI's "GPTs" feature in ChatGPT Plus/Enterprise (see [OpenAI GPTs documentation](https://openai.com/index/introducing-gpts/)), NOT third-party services using similar names. Focus on quality evaluation and best practices for OpenAI's platform only.

## Workflow Rules (Strict Adherence Required)

- **NO implementation without explicit approval**
- **HIGH-IMPACT, QUICK WINS ONLY** - everything else goes to planning
- **SHORT responses only** - no long explanations
- **NO examples unless approved** - examples can confuse/bias
- **CRITICAL review only** - discard minor items

## 🎯 Project Intent

**Main Goal:** Evaluate Custom GPTs created on OpenAI platform to see if they actually follow their custom instructions.

**Specific Use Case:** Compare responses between:

- Your Custom GPT (with specific instructions)
- Regular ChatGPT (no custom instructions)

**Key Question:** Does the Custom GPT perform differently/better than regular ChatGPT according to its instructions?

## ⚡ Current Simple Focus

- Create minimal evaluation method
- Test one Custom GPT vs regular ChatGPT
- Document clear differences (or lack thereof)

## 🔄 Advanced Features (Future Work)

All complex features moved to `advanced/` folder:

- Multi-criteria scoring systems
- Detailed evaluation rubrics
- Complex test scenarios

## 📝 Complete Chat History - Items Discussed

### ✅ Completed Items

- Fixed scoring system definitions (1-5 scale)
- Created GitHub Copilot instructions with strict markdown rules
- Renamed `tests/` to `evaluations/` for clarity
- Created simplified evaluation method
- Moved complex files to `advanced/` folder
- Updated project structure to flat hierarchy
- Added visual elements (emojis/icons) to documentation
- Created minimal Custom GPT vs regular ChatGPT comparison method
- Stripped README of "work in progress" language
- Removed confusing elements from evaluation forms

### 🎯 Current Focus Items

- Minimal evaluation method testing
- Simple Custom GPT instruction-following evaluation
- Flat project structure maintenance

### 📋 Backlog Items

- Expand test coverage to different technical topics (software architecture, security, performance)
- Add edge case testing for GPT responses (ambiguous inputs, conflicting requirements, incomplete information)
- Research additional MCP servers:
  - Context7 (mentioned but not available)
  - GitHub MCP (connection issues, needs configuration)
  - Database MCP for data persistence
  - Testing MCP for automated testing
- Best practices documentation for Custom GPT creation and evaluation
- Sustainable project structure for scaling test cases
- Professional-level AI assistance evaluation framework
- Multiple test scenarios beyond API design
- Advanced scoring rubrics with multiple criteria
- Automated testing capabilities exploration

### 🔧 MCP Server Status

**Available:**

- `promptBoost` - Enhance prompt quality
- `f51_resolve-library-id` & `f51_get-library-docs` - Library documentation
- `fetch_webpage` - Web research

**Issues:**

- `github_repo` - Connection problems, authentication needed
- Context7 - Not currently available, requires installation

### 📊 Evaluation Methods Discussed

- Simple Yes/Maybe/No scoring (current)
- 1-5 scale detailed scoring (moved to advanced)
- Multi-criteria evaluation (backlog)
- Evidence-based reasoning requirements (advanced)
- Rule adherence checking (advanced)

## Future Ideas (Capture Only - No Implementation)

- Expand test coverage to different technical topics (software architecture, security, performance)
- Add edge case testing for GPT responses (ambiguous inputs, conflicting requirements, incomplete information)
- Research additional MCP servers for enhanced capabilities
- Best practices documentation for Custom GPT creation and evaluation
- Sustainable project structure for scaling test cases

## Notes

- Focus on most urgent items only
- Using online pull request reviewers for feedback
- Concern about examples causing confusion/bias in evaluation
