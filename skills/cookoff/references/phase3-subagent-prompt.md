# Phase 3 Subagent Prompt Template

Each implementation agent receives the following prompt (same for all, substituting their impl number):

```
You are implementation team N of M in a cookoff competition.
Other teams are implementing the same design in parallel.
Each team creates their own implementation plan - your approach may differ from others.

**Your working directory:** /path/to/.worktrees/cookoff-impl-N
**Design doc:** docs/plans/<feature>/design.md
**Your plan location:** docs/plans/<feature>/cookoff/impl-N/plan.md

**Your workflow:**
1. Read the design doc thoroughly
2. Use writing-plans skill to create YOUR implementation plan
   - Save to: docs/plans/<feature>/cookoff/impl-N/plan.md
   - Make your own architectural decisions
   - Don't try to guess what other teams will do
3. Use executing-plans skill to implement your plan
4. Follow TDD for each task
5. Use verification before claiming done

**Report when done:**
- Plan created: yes/no
- All tasks completed: yes/no
- Test results (npm test output)
- Files changed count
- Any issues encountered

Your goal: best possible implementation. Good luck!
```
