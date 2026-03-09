---
name: Defect Report
about: Report a defect discovered in the system
title: "Defect: <short description>"
labels: defect
assignees: ""
---

# Bug Report

## Summary
Provide a short description of the problem.

Example:
Order submission API returns HTTP 500 when inventory service is unavailable.

---

## Environment

Where did the problem occur?

- Service: (Order Service / Inventory Service / API Gateway / Other)
- Environment: (Local / Docker / CI Pipeline)
- Branch:
- Commit (if known):

---

## Steps to Reproduce

Provide step-by-step instructions to reproduce the issue.

Example:

1. Start all services
2. Submit an order via POST `/orders`
3. Stop the inventory service
4. Submit another order

---

## Expected Behavior

Describe what the system **should** have done.

Example:
Order request should return a clear error response indicating inventory service is unavailable.

---

## Actual Behavior

Describe what **actually happened**.

Example:
API returns HTTP 500 with no useful error message.

---

## Logs / Error Messages

Include relevant logs or stack traces.
