# BUG-003: Employer and Company Staff Update Pages Fail to Load

## Summary

Employer Update and Company Staff Update pages remain stuck on a loading screen because API requests return 404 errors.

## Environment

* Application: HRMS Project
* Browser: Google Chrome

Affected URLs:

* http://localhost:3000/employer/update
* http://localhost:3000/companystaff/update

## Steps to Reproduce

1. Open Employer Update page.
2. Open Company Staff Update page.
3. Wait for page data to load.

## Expected Result

User profile information should load successfully.

## Actual Result

Loading spinner remains indefinitely.

Browser console displays:

* Failed to load resource: 404
* Request failed with status code 404

## Severity

Critical

## Priority

High

## Impact

Employers and company staff cannot manage or update profile information.

## Evidence

Console screenshots stored in screenshots folder.
