# Story 001 — Sign in with email and password

**Epic:** [epic-001-auth](../epics/epic-001-auth.md)  
**Status:** Done  
**Sprint:** [Sprint 01](../../sprints/sprint-01/sprint.md)

---

## User story

As a **user** (any actor),  
I want to sign in with my email and password,  
so that I can access my account and the features available to my role.

---

## Acceptance criteria

- [ ] User can enter email and password on a sign-in form
- [ ] Valid credentials grant access and redirect to the home screen
- [ ] Invalid credentials show a clear error message (do not reveal which field is wrong)
- [ ] Session is persisted across page reloads
- [ ] Session expires after a defined inactivity period
- [ ] Works on mobile and desktop

---

## Notes

- Auth handled via Better Auth
- No social login in this story (future epic)
