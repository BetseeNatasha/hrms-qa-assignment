# BUG-002: Job Seeker CV Update Page Stuck on Loading Screen

## Summary

The Job Seeker CV Update page never finishes loading and remains on a spinner indefinitely.

## Environment

* Application: HRMS Project
* Browser: Google Chrome
* URL: http://localhost:3000/jobseeker/cv/update

## Steps to Reproduce

1. Open the Job Seeker CV Update page.
2. Wait for page data to load.

## Expected Result

CV information should be displayed and editable.

## Actual Result

The page remains on a loading spinner indefinitely.

Browser console shows:

* Request failed with status code 404
* Failed to load resource

## Severity

Critical

## Priority

High

## Impact

Job seekers cannot update or maintain their CV information.

## Evidence

Console screenshot stored in screenshots folder.
