# QA Testing Plan - Expense Tracker

## 1. Unit & Functional Testing Scope
This document outlines the high-level manual testing procedures to verify system reliability without code integration.

## 2. Test Cases

| Test Case ID | Feature | Description | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| TC-01 | Auth | Log in with registered, valid credentials. | User is redirected to Dashboard page. | Passed |
| TC-02 | Auth | Log in with an incorrect password. | Error message "Invalid Credentials" displays. | Passed |
| TC-03 | Tracker | Add a valid expense (e.g., $15 for Food). | Transaction list updates; balance reduces. | Passed |
| TC-04 | Tracker | Try to save an expense with a negative value. | Form validation blocks submission. | Passed |
