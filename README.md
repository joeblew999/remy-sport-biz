# Remy Sport — Business Docs

This is where you, as the Product Owner (PO), manage everything the dev team needs to build the platform. Think of it as your coaching playbook — the dev team are your players, and these documents are how you communicate the game plan to them.

You don't need to know how to code. Your job is to describe **what** needs to be built and **why**. The dev team figures out the **how**.

---

## Domain

**What it's for:** These are your foundational definitions — the things that never really change. Before the dev team builds anything, they need to understand who uses the platform and what kinds of events it supports. You wrote this knowledge already as a basketball coach. This is just the formal version of it.

| Document | What it answers |
|---|---|
| [domain/actors.md](domain/actors.md) | Who the six user types are and what their goals are |
| [domain/event-types.md](domain/event-types.md) | What Tournaments, Leagues, Camps, and Showcases are |

---

## Access

**What it's for:** A single table that answers "who can do what?" for every feature. When a dev asks "should a Coach be able to edit scores?" — this is where you look. You own this table and keep it up to date as the platform grows.

| Document | What it answers |
|---|---|
| [access/matrix.md](access/matrix.md) | Who can do what, and which features apply to which event types |

---

## Roadmap

**What it's for:** Your high-level plan. Think of it like a season schedule — what's already been played (Now), what's coming up next (Next), and what's on the horizon but not yet locked in (Future Ideas). Stakeholders and coaches use this to see the big picture without getting into the details.

| Document | What it answers |
|---|---|
| [roadmap/roadmap.md](roadmap/roadmap.md) | What's built, what's coming, and what's planned (Now / Next / Later) |

---

## Backlog

**What it's for:** This is your full list of work waiting to be done — like a training drill list before the season starts. You organise it into **Epics** (big themes of work) and **Stories** (individual tasks inside each theme). The dev team pulls work from here sprint by sprint.

- An **Epic** is a large feature area, like "Scores & Results" or "Brackets". It groups related stories together.
- A **Story** is a single, specific thing to build, written from the user's point of view. It includes the exact conditions the dev team must meet before you'll sign it off (called acceptance criteria).

| Folder | What it contains |
|---|---|
| [backlog/epics/](backlog/epics/) | Big themes of work, one file per epic |
| [backlog/stories/](backlog/stories/) | Individual tasks, written as user stories with sign-off conditions |

### Epics

| Epic | Title | Status |
|---|---|---|
| [epic-001](backlog/epics/epic-001-auth.md) | Auth | Done |
| [epic-002](backlog/epics/epic-002-events.md) | Events | Next up |
| [epic-003](backlog/epics/epic-003-teams-players.md) | Teams & Players | In backlog |
| [epic-004](backlog/epics/epic-004-schedules-brackets.md) | Schedules & Brackets | In backlog |
| [epic-005](backlog/epics/epic-005-scores-results.md) | Scores & Results | In backlog |
| [epic-006](backlog/epics/epic-006-rankings-standings.md) | Rankings & Standings | In backlog |
| [epic-007](backlog/epics/epic-007-live-realtime.md) | Live & Real-time | In backlog |
| [epic-008](backlog/epics/epic-008-ai-assistant.md) | AI Assistant | In backlog |

---

## Sprints

**What it's for:** A sprint is a fixed block of time (usually two weeks) where the dev team focuses on a specific set of stories. Think of it like a training block — a defined period with a clear goal. At the end, the team reviews what got done and you sign off on it. You decide what goes into each sprint based on priority.

| Sprint | Goal | Status |
|---|---|---|
| [sprint-01](sprints/sprint-01/sprint.md) | Auth | Done |
| [sprint-02](sprints/sprint-02/sprint.md) | Events | Upcoming |

---

## Releases

**What it's for:** A record of what has actually shipped to users and when. Different from sprints — a sprint is internal delivery, a release is when real users get access to the features. Use this to communicate to stakeholders what's live.

| Release | What shipped | Status |
|---|---|---|
| [release-001](releases/release-001.md) | Auth | Released |

---

## Decisions

**What it's for:** A log of the important product decisions made along the way, and why. When someone asks "why did we do it this way?" six months from now, this is where the answer lives. You don't need to document every small choice — just the ones with real trade-offs or that affected scope, cost, or direction.

| Decision | Title | Status |
|---|---|---|
| [decision-001](decisions/decision-001-auth-provider.md) | Auth provider: Better Auth | Accepted |

---

## Bugs

**What it's for:** When something is built but isn't working correctly, it goes here as a bug report. Bugs are separate from stories — a story is new work, a bug is broken existing work. You triage bugs (decide how urgent they are) and assign them to sprints when needed.

| Folder | What it contains |
|---|---|
| [backlog/bugs/](backlog/bugs/) | Bug reports, triaged and prioritised separately from stories |

---

## Templates

**What it's for:** Blank starting points for every type of document you'll create. When you need to write a new story, epic, sprint, bug report, or decision — copy the right template, fill it in, and save it in the correct folder. This keeps everything consistent so the dev team always knows what to expect.

| Template | Use for |
|---|---|
| [templates/epic.md](templates/epic.md) | New epic |
| [templates/story.md](templates/story.md) | New user story |
| [templates/sprint.md](templates/sprint.md) | New sprint |
| [templates/bug.md](templates/bug.md) | New bug report |
| [templates/decision.md](templates/decision.md) | New product decision |
