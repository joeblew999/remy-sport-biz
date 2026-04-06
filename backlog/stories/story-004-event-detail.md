# Story 004 — View event detail page

**Epic:** [epic-002-events](../epics/epic-002-events.md)  
**Status:** Ready  
**Sprint:** [Sprint 02](../../sprints/sprint-02/sprint.md)

---

## User story

As a **user** (any actor, including unauthenticated spectators),  
I want to view the full details of an event,  
so that I know the rules, schedule, registration deadlines, and location before deciding to participate or follow.

---

## Acceptance criteria

- [ ] Detail page is accessible without signing in
- [ ] Page shows: event name, type, dates, location, format, divisions, registration deadline
- [ ] Page shows current registration status (open / closed / full)
- [ ] Page links to bracket, schedule, and results when available
- [ ] Works on mobile and desktop

---

## Notes

- Detail content varies by event type — see [../../domain/event-types.md](../../domain/event-types.md)
- Registration call-to-action should be context-aware (Coach sees "Register team", Player sees "Register as player")
