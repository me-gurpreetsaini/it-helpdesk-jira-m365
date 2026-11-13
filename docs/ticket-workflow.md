# Ticket Workflow and SLA Policy

## Priorities

| Priority | Jira name | Meaning | Example |
|---|---|---|---|
| P1 | Highest | Many users cannot work | Email down for a department |
| P2 | High | One user cannot work | Locked out of account |
| P3 | Medium | Inconvenience, user can still work | Printer offline, another printer available |
| P4 | Low | Standard request | New software install |

## First response targets

| Priority | Target | Calendar |
|---|---|---|
| P1 | 30 minutes | 24/7 |
| P2 | 2 hours | Business hours (Mon-Fri, 9-5 ET) |
| P3 | 8 business hours (1 business day) | Business hours |
| P4 | 16 business hours (2 business days) | Business hours |

## Resolution targets

| Priority | Target | Calendar |
|---|---|---|
| P1 | 4 hours | 24/7 |
| P2 | 8 business hours (1 business day) | Business hours |
| P3 | 24 business hours (3 business days) | Business hours |
| P4 | 40 business hours (5 business days) | Business hours |

Resolution means the issue is fixed and the ticket reaches Resolved. The clock pauses while waiting for the customer.

First response means a person replied to the customer. It is not the same as resolution. 

## SLA clock rules

- Starts when the ticket is created.
- Pauses while the status is Waiting for customer.
- Stops at the first public reply from an agent.

## Ticket workflow

1. Triage: read the ticket, set the priority, assign it.
2. Acknowledge: send the acknowledgement reply (pls see `templates/`).
3. Work: gather details, troubleshoot, document each step.
4. Resolve: fix the issue and send the resolution reply.
5. Close: confirm with the user, then close.

## Ticket note format

Summary, Steps taken, Resolution, Root cause, Follow up.

## Escalation

- Escalate to a senior technician when the issue is outside my access or permissions, affects multiple users, or is still unresolved after the troubleshooting steps in the KB article.
- P1 tickets are escalated immediately.
- When escalating, include what was tried so the next person does not repeat it.
