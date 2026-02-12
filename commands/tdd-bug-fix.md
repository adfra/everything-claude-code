---
description: Analyse a given error or bug report and apply a TDD approach to fix the issue.
---

# TDD Bug Fix Command

This command invokes the **tdd-guide** agent to generate, maintain, and execute a full set of tests to firstly mimic the bug with a failed (set of) test(s) and then provide a fix to confirm with a passing (set of) test(s).

## What This Command Does

1. **Analyse** - Understand the bug report, root cause and determine a fix
2. **Apply TDD** - Leverage the tdd-guide agent to generate tests to mimic the bug and confirm the fix
3. **Confirm Fix** - Run tests to confirm the fix

## When to Use

Use `/tdd-bug-fix` when:
- Encountering errors and bugs in the code base.

## Example Usage

```
User: /tdd-bug-fix <some bug report or error message>

Agent: <Follows the tdd-guide instruction set to generate, maintain, and execute a full set of tests to firstly mimic the bug with a failed (set of) test(s) and then provide a fix to confirm with a passing (set of) test(s).>

## Related Agents

This command invokes the `tdd-guide` agent located at:
`~/.claude/agents/tdd-guide.md`