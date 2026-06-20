# HRMS QA Test Strategy

## Project Overview

This HRMS application allows job seekers, employers, and company staff to manage recruitment-related activities such as job advertisement posting, CV updates, and employer profile management.

The goal of testing is to ensure that users can successfully perform these critical business operations without data loss, application crashes, or incorrect system behavior.

---

## Critical User Flows

### Flow 1: View Job Advertisements

Path:

/jobadvert

Risk:

Users cannot view available job opportunities.

Priority:

High

---

### Flow 2: Add Job Advertisement

Path:

/jobadvert/add

Risk:

Employers cannot create job postings.

Priority:

Critical

---

### Flow 3: Update Job Seeker CV

Path:

/jobseeker/cv/update

Risk:

Candidates cannot maintain profile information.

Priority:

Critical

---

### Flow 4: Update Employer Information

Path:

/employer/update

Risk:

Employers cannot manage company details.

Priority:

Critical

---

### Flow 5: Update Company Staff Information

Path:

/companystaff/update

Risk:

Administrative users cannot manage profile data.

Priority:

High

---

## Test Types

### Functional Testing

Validate form behavior, navigation, field validation, and page rendering.

### Negative Testing

Validate handling of invalid data such as:

* Empty mandatory fields
* Negative salary values
* Invalid salary ranges
* Invalid dates

### Regression Testing

Verify previously working features continue functioning after future changes.

Focus areas:

* Navigation routes
* Form submissions
* API integrations
* Validation rules

---

## Risks Identified

### High Risk

Broken API integrations resulting in infinite loading screens.

### High Risk

Non-functional dropdown fields preventing form completion.

### Medium Risk

Validation messages may not prevent invalid data from reaching backend services.

---

## What Should Be Automated

* Navigation verification
* Form validation checks
* API response verification
* Loading state verification

---

## What Should Not Be Automated

Visual styling and cosmetic layout checks.

Reason:

UI appearance changes frequently while business functionality remains unchanged.
