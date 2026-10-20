# Help Desk Ticketing & Incident Simulation Portfolio

A practical service desk portfolio demonstrating ticket intake, prioritisation, user communication, evidence-based troubleshooting, escalation, verification, and closure.


## Ticket catalogue

| ID | Scenario | Skills demonstrated |
|---|---|---|
| HD-001 | One user's network printer jobs fail | Scope, queue, printer selection, safe diagnostics |
| HD-002 | Remote user cannot access mapped drive | VPN triage, network path, file access |
| HD-003 | Windows computer suddenly slow | Task Manager, symptoms, performance investigation |
| HD-004 | Business application closes on launch | Error capture, logs, safe escalation |
| HD-005 | Access Denied on a team folder | Identity, group membership, share/NTFS permissions |
| HD-006 | New starter needs access | Approval, least privilege, validation |
| HD-007 | Unexpected sign-in approval prompt | Security response, evidence preservation, escalation |
| HD-008 | Multiple users report the same outage | Incident coordination, impact, communications |

## Ticket lifecycle

1. Capture the user's symptom and exact error.
2. Establish scope and business impact.
3. Set priority using the organisation's impact/urgency matrix and SLA.
4. Ask targeted questions and select checks that answer them.
5. Record observations separately from assumptions.
6. Make only authorised, evidence-supported changes.
7. Verify the user can complete the affected task.
8. Record resolution or escalation, user update, and closure notes.

## Repository layout

```text
help-desk-ticketing-portfolio/
├── README.md
├── ticket-register.csv
├── templates/ticket-template.md
├── procedures/ticket-handling-runbook.md
└── tickets/ (eight individual ticket records)
```

## Lab boundaries

The existing Windows lab uses `triiumph.com`. Do not assume simulated employees, printers, shares, or applications exist in that lab. Practise a scenario in the lab only when it can be reproduced safely and meaningfully. Remove sensitive details from published evidence.

## Practice record

For each case actually practised, record the date, environment, checks performed, actual observations, actions taken, verification result, and what you would escalate. Mark a case verified only after completing and documenting those steps.
