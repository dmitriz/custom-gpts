# GitHub Copilot Instructions & Rules
For full context, see the [project README](https://github.com/dmitriz/custom-gpts/blob/main/README.md).
## Code Review & Change Management Rules

- 🔍 **Minimize diff size** - Make fragment-by-fragment changes, not large paragraph replacements
- 📏 **Use minimal context** – Include only 3–5 lines before/after changes in replace operations
- ✂️ **Avoid large deletions** - Break large changes into smaller, reviewable chunks
- 📋 **Make changes trackable** - Each edit should show clear, specific differences
- 🛠️ **MANDATORY: Fix all markdown warnings** – Required to fix any markdown issues before declaring work complete. No exceptions.

## Documentation & Formatting Rules

- **Always include relevant links** - Add documentation links whenever possible without asking
- **Use clear, descriptive titles** - Titles should explain content purpose immediately
- **Remove numbers from titles** - Never use numbered titles (1., 2., etc.) - use clear descriptive titles instead
- **Add visual elements** – Use icons and emojis to make content more engaging with relevant visuals (e.g., ✅ 🔧 📝)
- **Separate specific vs generic content** - Clearly mark what's use-case specific vs reusable

## Project Structure Rules

- **Prefer flat structure** - Avoid folders for single files
- **Only create folders when too many files** - Start with top-level files, create folders when 10+ files in directory
- **Use clear directory names** - Only lowercase with dashes (e.g., `evaluation-cases`, `gpt-configs`)
- **Generic rules go to appropriate global files** - Not in project-specific documents

## Workflow Rules

- **HIGH-IMPACT, QUICK WINS ONLY** - Everything else goes to [planning](../PLANNING.md)
- **NO implementation without explicit approval**
- **SHORT responses only** - No long explanations
- **NO examples unless approved** - Examples can confuse/bias
- **CRITICAL review only** - Focus on high-impact issues, ignore minor formatting/style items
- **NO completed items in planning** - Planning is for current work and backlog only, not historical records

## Confirmation: Rules I Follow

✅ Make minimal diff changes for easy review  
✅ Include relevant documentation links automatically  
✅ Use clear descriptive titles without numbers  
✅ Use engaging visual elements (icons/emojis)  
✅ Separate specific vs generic content clearly  
✅ Prefer flat project structure  
✅ Only implement with explicit approval

## Global Rules

- **NEVER create duplicate or backup files** - Always update the original file directly. There must only ever be one version of any file in the project. This applies to all files, not just research or documentation. No parallel, backup, or alternate versions allowed.
