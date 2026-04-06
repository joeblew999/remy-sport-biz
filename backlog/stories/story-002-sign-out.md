# Story 002 — Sign out

**Epic:** [epic-001-auth](../epics/epic-001-auth.md)  
**Status:** Done  
**Sprint:** [Sprint 01](../../sprints/sprint-01/sprint.md)

---

## User story

As a **user** (any actor),  
I want to sign out of my account,  
so that my session is ended and my account is secure on shared devices.

---

## Acceptance criteria

- [ ] Sign out option is accessible from any screen (e.g. nav menu)
- [ ] Signing out clears the session and redirects to the public home or sign-in page
- [ ] Signed-out users cannot access authenticated routes
- [ ] Works on mobile and desktop

---

## Notes

- Session tokens must be invalidated server-side on sign out
