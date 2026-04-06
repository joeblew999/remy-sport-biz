# Decision 001 — Auth provider: Better Auth

**Date:** 2026-03-01  
**Status:** Accepted  
**Decided by:** PO + Tech Lead  
**Stakeholders:** Dev team

---

## Context

The platform needs secure user authentication with support for multiple roles (Organizer, Coach, Player, Spectator, Referee, Admin). We needed to choose between building auth from scratch, using a hosted service, or using an open-source library.

---

## Options considered

| Option | Pros | Cons |
|---|---|---|
| Build from scratch | Full control | High effort, security risk |
| Hosted service (Auth0, Clerk) | Fast, managed | Cost at scale, vendor lock-in |
| Better Auth (open-source) | Free, self-hosted, role/org plugins | Requires self-hosting |

---

## Decision

Use **Better Auth** with its organization and role plugins to manage multi-role accounts.

---

## Consequences

- Role assignment is handled through Better Auth's org and role plugins
- A Coach can also be a Player on a single account
- Social login and 2FA are possible in future via Better Auth extensions
