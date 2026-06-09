# Day 9 Submission Checklist

## Code tasks

- Exercise 2 completed: labor-law knowledge entry, statute-of-limitations tool, tool binding, and tool execution handling.
- Exercise 4 completed: privacy agent, privacy routing, aggregation, graph node, and graph edge.
- Runtime LLM factory configured with bounded output tokens via `OPENROUTER_MAX_TOKENS`.
- README Stage 4 path corrected to match `stages/stage_4_milti_agent`.
- Vietnamese Q&A notes added in `exercises/answers.md`.

## Verification

- Syntax check passed for modified Python files.
- `exercises/exercise_2_tools.py` runs and prints a non-empty result.
- `exercises/exercise_4_multiagent.py` runs successfully.
- Stage 1 through Stage 4 were verified locally.
- Stage 5 distributed A2A client was verified locally with all five services running.

## Runtime notes

- Copy `.env.example` to `.env` before running.
- Set `OPENROUTER_API_KEY` in `.env`.
- The local verified config used `OPENROUTER_MODEL=openai/gpt-oss-20b:free` and `OPENROUTER_MAX_TOKENS=128` to avoid paid-credit issues.
- Do not commit `.env`.
