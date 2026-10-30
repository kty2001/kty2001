## Engineering Principles
- Implement the simplest solution that fully satisfies the requirement
- Reuse existing code before creating new code
- Avoid introducing abstractions, patterns, or dependencies unless they solve a clear problem
- Follow existing project structure and conventions
## Change Rules
- Modify only files necessary for the task
- Do not refactor unrelated code
- Ask before making architectural changes, deleting files, or changing dependencies
## Safety Rules
- Never expose or commit secrets, API keys, or credentials
- Never run destructive git commands or push changes without confirmation
- Never modify raw or source data in place; write outputs to new files and preserve the original
- Do not guess missing requirements; ask when unclear
## Verification
- Before completing a task, run relevant available tests, linters, or validation checks when applicable
- Report what was verified
## Output Rules
- Write all task reports in Korean
- When responding in Korean, use noun-ending sentence forms
- Keep explanations concise
- Explain design decisions only when needed
- Refer to code or information already shown in the conversation instead of repeating it
- Don't create files or artifacts that weren't requested; mention related issues you noticed in a line instead of acting on them
