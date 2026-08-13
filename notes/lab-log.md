## 2026-08-14 — Windows Authentication Detection

### Objective
Detect failed Windows authentication attempts using Wazuh.

### Environment
- Wazuh Server: Ubuntu
- Endpoint: Windows 10
- Agent: Windows10-Lab

### Activity
Generated five incorrect password attempts against the
Windows test account.

### Result
Windows generated Event ID 4625.
Wazuh detected the events as authentication failures.

### Evidence
- evidence/04-authentication-failure.png
- evidence/05-authentication-event-details.png

### Status
Completed
