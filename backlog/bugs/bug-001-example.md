# Bug 001 — Example: Session not persisting on mobile Safari

**Status:** New  
**Severity:** High  
**Reported by:** QA  
**Reported date:** 2026-03-15  
**Sprint:** _(unassigned)_

---

## Summary

After signing in on mobile Safari, the session is lost when the browser is backgrounded and reopened.

---

## Steps to reproduce

1. Open the app in mobile Safari on iOS
2. Sign in with valid credentials
3. Background the browser for 30+ seconds
4. Return to the app

---

## Expected behaviour

User remains signed in and is taken back to their last screen.

---

## Actual behaviour

User is redirected to the sign-in page as if they have no active session.

---

## Notes

- Reproduced on iOS 17, Safari
- Does not occur on Chrome for iOS or desktop browsers
- Related to story-001 (sign in)
