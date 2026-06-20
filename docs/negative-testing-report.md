# Negative Testing Report

## Objective

Verify how the HRMS application behaves when invalid, incomplete, or unexpected input is provided.

---

## Test Case 1: Empty Required Fields

### Steps

1. Open Add Job Advert page.
2. Leave all required fields empty.
3. Attempt submission.

### Expected Result

Validation messages should appear.

### Actual Result

Validation messages appeared for required fields such as:

* Job Position
* City
* Working Type
* Working Time

### Status

PASS

---

## Test Case 2: Negative Minimum Salary

### Steps

1. Enter -1 in Minimum Salary.
2. Attempt submission.

### Expected Result

System should reject negative salary values.

### Actual Result

Validation message displayed:

"Min salary must be greater than 0"

### Status

PASS

---

## Test Case 3: Maximum Salary Less Than Minimum Salary

### Steps

1. Enter 10000 as Minimum Salary.
2. Enter 5000 as Maximum Salary.

### Expected Result

System should reject invalid salary range.

### Actual Result

Validation message requested a salary value greater than the minimum salary.

### Status

PASS

---

## Test Case 4: Missing Dropdown Selections

### Steps

1. Leave dropdown fields unselected.
2. Attempt submission.

### Expected Result

User should receive validation messages.

### Actual Result

Validation messages appeared.

However, dropdown controls themselves were not functional.

### Status

FAIL

Related Bug:

BUG-001

---

## Test Case 5: Long Description Text

### Steps

1. Enter a large block of text into Description field.

### Expected Result

System should handle input without crashing.

### Actual Result

Field accepted input successfully.

### Status

PASS

---

## Summary

The application performs basic validation for required fields and salary values. However, critical functionality is affected by non-working dropdown controls and API failures that prevent several major workflows from operating correctly.
