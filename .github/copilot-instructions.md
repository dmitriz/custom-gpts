# GitHub Copilot Instructions & Rules

## Code Review & Change Management Rules

- **Minimize diff size** - Make fragment-by-fragment changes, not large paragraph replacements
- **Use minimal context** - Include only 3-5 lines before/after changes in replace operations
- **Avoid large deletions** - Break large changes into smaller, reviewable chunks
- **Make changes trackable** - Each edit should show clear, specific differences

## Documentation & Formatting Rules

- **Always include relevant links** - Add documentation links whenever possible without asking
- **Use clear, descriptive titles** - Titles should explain content purpose immediately
- **Add visual elements** - Use icons/emojis to make content more engaging ✅ 🔧 📝
- **Separate specific vs generic content** - Clearly mark what's use-case specific vs reusable

## Project Structure Rules

- **Prefer flat structure** - Avoid folders for single files
- **Only create folders when too many files** - Start with top-level files, create folders when 10+ files in directory
- **Use clear directory names** - Only lowercase with dashes (e.g., `evaluation-cases`, `gpt-configs`)
- **Generic rules go to appropriate global files** - Not in project-specific documents

## Workflow Rules

- **HIGH-IMPACT, QUICK WINS ONLY** - Everything else goes to planning
- **NO implementation without explicit approval**
- **SHORT responses only** - No long explanations
- **NO examples unless approved** - Examples can confuse/bias
- **CRITICAL review only** - Focus on high-impact issues, ignore minor formatting/style items

## Confirmation: Rules I Follow

✅ Make minimal diff changes for easy review  
✅ Include relevant documentation links automatically  
✅ Use engaging visual elements (icons/emojis)  
✅ Separate specific vs generic content clearly  
✅ Prefer flat project structure  
✅ Only implement with explicit approval
