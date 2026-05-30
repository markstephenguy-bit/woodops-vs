# Copilot Instructions

## Project Guidelines
- Preferred terminal shell: powershell.exe; IDE: Visual Studio Community 2026; workspace root: C:\Users\mguy\source\repos\woodops-vs\woodops-vs\

## Memory & Artifact Management
- Keep repository context minimal and canonical; prefer a single canonical file at Artifacts/Canonical/SOLUTION_CONTEXT.md to capture solution context and avoid duplicating external Drive files.
- Create and maintain a canonical in-repo memory at Artifacts/Canonical (include SOLUTION_CONTEXT.md) and treat that file as the single source of truth; update only via pull request and only after explicit user approval.
- Interface exclusively via chat for managing context; act as an administrative worker to draft and prepare updates but do not commit changes without explicit user approval.
- Use in-repo metadata and reference pointers for agent artifacts so the solution has a canonical memory repository without duplicating external content.
- Store minimal metadata and reference pointers in-repo (identifiers, original location, access method); reference external sources rather than embedding their contents.

## Instruction Update Process
- Draft updates and proposed merges in chat; require explicit user approval before committing changes or opening pull requests.
- When merging new instructions, check for existing instructions with the same semantic meaning and enhance the existing instruction rather than adding a duplicate.
- If a new instruction is more specific or comprehensive, replace the older instruction; if they complement each other, merge into a single cohesive instruction.
- Group semantically related instructions together and place general instructions before specific ones; create a new section only when the instruction does not fit existing categories.

## Instruction Merge & Formatting Rules
- Use clear, concise, actionable language in imperative mood.
- Use headings (##, ###) to organize related instructions and bullet points (-) for lists; maintain consistent indentation and spacing.
- Preserve existing formatting conventions (paths, code blocks, emphasis, links) unless a merge requires an edit.
- Avoid redundant phrases and keep instructions short and focused.
- When producing merged instruction content for responses or commits, return only the complete merged Markdown content; do not wrap output in code fences; do not add meta-commentary; preserve all existing content unless merging or deduplicating.- When producing merged instruction content for responses or commits, return only the complete merged Markdown content; do not wrap output in code fences; do not add meta-commentary; preserve all existing content unless merging or deduplicating.