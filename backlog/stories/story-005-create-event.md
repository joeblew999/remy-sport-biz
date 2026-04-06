# Story 005 — Create an event

**Epic:** [epic-002-events](../epics/epic-002-events.md)  
**Status:** Ready  
**Sprint:** [Sprint 02](../../sprints/sprint-02/sprint.md)

---

## User story

As an **Organizer** or **Admin**,  
I want to create a new event,  
so that teams and players can register and participate.

---

## Acceptance criteria

- [ ] Organizer can select event type: Tournament, League, Camp/Clinic, Showcase
- [ ] Required fields: name, event type, start date, end date, location
- [ ] Optional fields: description, format, registration deadline, max teams/players
- [ ] Event is saved in draft state and not publicly visible until published
- [ ] Organizer can publish the event to make it visible in browse
- [ ] Admin can create events on behalf of any organizer
- [ ] Works on mobile and desktop

---

## Notes

- Format options vary by event type (e.g. bracket format only for Tournament/Showcase)
- Divisions (age/gender) are configured in a follow-on story (story-006)
