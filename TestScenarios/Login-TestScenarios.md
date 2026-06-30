# Login Test Scenarios

## Project
SauceDemo

## Module
Login

## Objective
Validate the Login functionality to ensure users can securely access the application using valid credentials and receive appropriate validation messages for invalid login attempts.

## Scope

### In Scope
- User Login
- Username Validation
- Password Validation
- Error Messages
- Navigation after Login
- Logout
- Session Handling

### Out of Scope
- User Registration
- Forgot Password
- Profile Management

---

## Assumptions

- The SauceDemo application is available.
- Test users are already created.
- The application is accessible through Google Chrome.
- Internet connection is stable.

---

## Test Scenarios

| ID | Test Scenario | Priority |
|----|---------------|----------|
| TS-001 | Verify login with valid credentials | High |
| TS-002 | Verify login with invalid username | High |
| TS-003 | Verify login with invalid password | High |
| TS-004 | Verify login with invalid username and invalid password | High |
| TS-005 | Verify login with empty username | Medium |
| TS-006 | Verify login with empty password | Medium |
| TS-007 | Verify login with empty username and password | Medium |
| TS-008 | Verify locked-out user cannot login | High |
| TS-009 | Verify Username field is displayed | Low |
| TS-010 | Verify Password field is displayed | Low |
| TS-011 | Verify Login button is displayed | Low |
| TS-012 | Verify password field masks entered characters | Medium |
| TS-013 | Verify successful login redirects to Inventory page | High |
| TS-014 | Verify error message is displayed for invalid login | High |
| TS-015 | Verify error message is cleared after successful login | Medium |
| TS-016 | Verify Inventory page cannot be accessed without login | High |
| TS-017 | Verify user session ends after logout |