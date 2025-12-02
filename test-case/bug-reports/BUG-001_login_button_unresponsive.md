# BUG-001 — Login button unresponsive intermittently

Environment: Chrome (latest), QA environment v1.2.3

Steps:
1. Open /login
2. Enter valid credentials
3. Click Login (once)

Actual: Sometimes nothing happens on first click; second click succeeds.
Expected: First click should trigger login request.

Severity: Major
Priority: High
Notes: Console sometimes shows `TypeError` — possible JS binding race.
