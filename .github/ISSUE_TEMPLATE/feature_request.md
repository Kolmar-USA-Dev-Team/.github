---
name: Feature Request
about: Request or track development of a new feature
title: "[Feature]: "
labels: feature
---

## Summary

Briefly describe the feature.

Example:
> Implement worker lookup endpoint to validate scanned worker badges.

---

## Problem / Motivation

Why is this feature needed?

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
