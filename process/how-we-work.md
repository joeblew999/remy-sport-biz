# How We Work

This document explains how an idea becomes a feature that real users can use. Read this first before anything else in this repo.

---

## The big picture

```
Idea → Story → Backlog → Sprint → Done → Release
```

Here is what each step means:

---

## 1. An idea comes in

Ideas can come from you, from users, from the dev team, or from stakeholders. When an idea comes in, your job as PO is to decide:

- Is this worth building?
- Does it fit the platform's goals?
- How urgent is it compared to everything else?

If yes — write it up as a **Story** (or a **Bug** if something is broken). Use the templates in [templates/](../templates/).

---

## 2. The story goes into the Backlog

Every new story starts with the status **In backlog**. This means it has been captured but is not yet ready for the dev team to pick up. Think of it like a player on the bench — they're on the squad, but not on the court yet.

The backlog is your priority list. The most important stories sit at the top. You are responsible for keeping it ordered.

---

## 3. The story becomes Ready

Before a story can go into a sprint, it needs to be **Ready**. This means:

- The user story is written clearly ("As a Coach, I want to...")
- The acceptance criteria are complete (see [story-lifecycle.md](story-lifecycle.md))
- The dev team has read it and has no blocking questions
- It is small enough to be completed within one sprint

Think of **Ready** as a player who has been briefed on the play — they know exactly what to do when they step on the court.

---

## 4. Sprint planning

At the start of each sprint, you and the dev team agree on which **Ready** stories will be worked on. This is called sprint planning. You pick stories from the top of the backlog. The dev team tells you how many they can realistically complete.

Once stories are committed to a sprint, the dev team gets to work.

---

## 5. The dev team builds it

During the sprint, the dev team builds the stories. Your job during this time is to:

- Answer questions quickly if they arise
- Not add new work to the sprint (save it for the next one)
- Review work as it is completed

---

## 6. You sign off — Done

When the dev team says a story is built, you check it against the acceptance criteria. If every criterion is met, the story is **Done**.

If something is missing or wrong, it stays **In progress** until it is fixed. See [definition-of-done.md](definition-of-done.md) for the full agreement on what Done means.

---

## 7. Release

At the end of a sprint (or when enough features are ready), the dev team deploys the work so real users can access it. You write a brief [release note](../releases/) describing what shipped.

---

## Where things live

| When you need to... | Go to... |
|---|---|
| Capture a new idea | Write a story in [backlog/stories/](../backlog/stories/) using the [template](../templates/story.md) |
| Report something broken | Write a bug in [backlog/bugs/](../backlog/bugs/) using the [template](../templates/bug.md) |
| Plan the next sprint | Pick Ready stories and create a file in [sprints/](../sprints/) |
| Check what's been agreed | [access/matrix.md](../access/matrix.md) and [decisions/](../decisions/) |
| See the big picture | [roadmap/roadmap.md](../roadmap/roadmap.md) |
