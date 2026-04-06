# Story Lifecycle

Every story moves through a set of statuses from the moment it is created to the moment it ships. This document explains what each status means, who is responsible at each stage, and what needs to happen before a story can move forward.

---

## Statuses

### In backlog
The story has been written and captured but is not yet ready for the dev team. It may still be rough, missing detail, or not yet prioritised.

**Who acts:** You (PO). Refine the story, add or improve acceptance criteria, and move it up the priority order when it becomes important.

---

### Ready
The story is fully written, the acceptance criteria are clear, and the dev team has no blocking questions. It is ready to be picked up in the next sprint.

**Checklist before marking Ready:**
- [ ] User story is written ("As a [actor], I want to..., so that...")
- [ ] All acceptance criteria are listed and unambiguous
- [ ] The dev team has read it and agrees it is clear
- [ ] It is small enough to complete in one sprint

**Who acts:** You (PO) mark it Ready after confirming with the dev team.

---

### In progress
The dev team has picked up the story and is actively building it. It is part of the current sprint.

**Who acts:** Dev team. You stay available to answer questions quickly — a question left unanswered for a day can block the whole sprint.

---

### Done
The story has been built, tested, and signed off by you (the PO). Every acceptance criterion has been met. See [definition-of-done.md](definition-of-done.md) for the full checklist.

**Who acts:** You (PO) sign it off after reviewing it.

---

## What is an acceptance criterion?

An acceptance criterion is a specific, testable condition that must be true for a story to be Done. Think of it like the criteria a referee uses to make a call — it is either met or it isn't. There is no grey area.

**Bad acceptance criterion** (too vague):
> The registration form should work well.

**Good acceptance criterion** (specific and testable):
> A coach can register their team for a tournament and receive a confirmation message on screen.

When you write a story, ask yourself: "How will I know, without any doubt, that this has been built correctly?" Each answer is an acceptance criterion.

---

## Story lifecycle at a glance

```
In backlog → Ready → In progress → Done
```

| Status | Who acts | What happens |
|---|---|---|
| In backlog | PO | Write and refine the story |
| Ready | PO + Dev team | Confirm it is clear and sized correctly |
| In progress | Dev team | Story is being built in the current sprint |
| Done | PO | PO signs it off against acceptance criteria |
