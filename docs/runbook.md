# On-Call Runbook

This runbook is the first place to look when the handoff-checklist service misbehaves. Keep it updated as you learn more.

## What is this service?

`handoff-checklist` is a small, self-documenting project used to track the checklist for handing the project off from one owner to the next. It is intentionally lightweight: a single repository with a README, this runbook, and any checklists the incoming and outgoing owners maintain.

## How to run it

There is nothing to build or deploy. To work with this project:

1. Clone the repository locally.
2. Read the top-level `README.md` first — it explains the purpose of the project and links to the checklists.
3. Make changes on a short-lived branch and open a pull request into `main`.
4. Keep `main` deployable at all times; every change to `main` should go through a pull request when possible.

## Who to ping

- **Current owner / primary contact:** Hezi Liu (@HeziLiu) — handles questions about the repo layout, open pull requests, and the handover itself.
- **Incoming owner / after handoff:** your teammate takes over at the end of handoff week; update this section once the transfer is complete.
- **If nobody responds:** escalate through your team's normal on-call rotation.

## Useful notes

- The handoff happens at the end of next week. Until then, assume the current owner is the point of contact.
- When in doubt, ask in a pull request comment rather than guessing.
