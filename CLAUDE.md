# CodeScope – Project Context for Claude Code

## Goal
Build a personal LangChain tool that analyzes a local codebase or GitHub repo and produces structured reports (complexity, dependencies, architecture notes, change explanations).

## Constraints
- Personal project only (solely owned by the author).
- Use LangChain for chaining analysis steps and structured output.
- Prefer clear, modular code.
- Output should be structured (Pydantic models / JSON).

## Current status
- Scaffold only. Main entry point is `src/main.py`.
- No full analysis pipeline yet.

## Suggested next steps
1. Add LangChain chain for basic file listing + summary.
2. Add dependency extraction (requirements.txt / package.json).
3. Add structured output models.
4. Add simple CLI improvements and tests.
