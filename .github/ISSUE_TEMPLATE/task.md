---
name: Task
about: Implement a task for a feature
title: "[Task]: "
labels: task
---

## Summary

Briefly describe the task.

Example:
> Implement worker lookup endpoint to validate scanned worker badges.

---

## Problem / Motivation

Why is this task necessary to implement the parent feature?

Example:
> The frontend needs a way to validate worker badges when scanned so the supervisor can confirm the correct worker is being logged.

---

## Proposed Solution

Describe the technical approach.
Example:

```
GET /api/workers/{workerBarcode}
```

Returns worker information associated with the scanned barcode

---

## Expected Behavior

Example response:

```json
{
    "id": "12345678",
    "name": "John Smith"s
}
```

---

## Acceptance Criteria

* [ ] Endpoint implemented
* [ ] Returns correct worker data
* [ ] Returns `404` when worker is not found
* [ ] Swagger documentation added
* [ ] Unit tests added

---

## Notes

Add any additional context or implementation notes here.
