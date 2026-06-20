# HRMS Test Cases

## TC-001 Verify Home Page Loads

**Precondition:** Application is running

**Steps:**

1. Open browser
2. Navigate to http://localhost:3000

**Expected Result:**
Home page should load successfully.

**Priority:** High

---

## TC-002 Verify Find Job Navigation

**Steps:**

1. Open Home Page
2. Click "Find a Job"

**Expected Result:**
User should be redirected to job listings page.

**Priority:** High

---

## TC-003 Verify Post Job Navigation

**Steps:**

1. Open Home Page
2. Click "Post a Job"

**Expected Result:**
Post Job page should open.

**Priority:** High

---

## TC-004 Verify Job Search Field Accepts Input

**Steps:**

1. Navigate to Job Listings
2. Enter "QA Engineer" in search field

**Expected Result:**
Input should be accepted.

**Priority:** Medium

---

## TC-005 Verify Job Position Dropdown

**Steps:**

1. Navigate to Add Job Advert
2. Click Job Position dropdown

**Expected Result:**
Dropdown options should appear.

**Actual Observation:**
Failed (BUG-001)

**Priority:** Critical

---

## TC-006 Verify City Dropdown

**Steps:**

1. Navigate to Add Job Advert
2. Click City dropdown

**Expected Result:**
City list should appear.

**Actual Observation:**
Failed (BUG-001)

**Priority:** Critical

---

## TC-007 Verify Min Salary Validation

**Steps:**

1. Enter negative salary value

**Expected Result:**
Validation message should appear.

**Priority:** High

---

## TC-008 Verify Jobseeker Profile Update Page

**Steps:**

1. Navigate to /jobseeker/cv/update

**Expected Result:**
Profile form should load.

**Actual Observation:**
Infinite loading screen (BUG-002)

**Priority:** Critical

---

## TC-009 Verify Employer Update Page

**Steps:**

1. Navigate to /employer/update

**Expected Result:**
Employer form should load.

**Actual Observation:**
Infinite loading screen (BUG-003)

**Priority:** Critical

---

## TC-010 Verify Responsive Navigation

**Steps:**

1. Resize browser window
2. Navigate through menu

**Expected Result:**
Navigation remains accessible.

**Priority:** Medium
