# Login Test Cases

## TC-001: Login with Valid Credentials

**Precondition:**
User has a registered account.

**Steps:**
1. Open Login page.
2. Enter valid username.
3. Enter valid password.
4. Click Login.

**Expected Result:**
User is redirected to Dashboard.

---

## TC-002: Login with Invalid Password

**Precondition:**
User has a registered account.

**Steps:**
1. Open Login page.
2. Enter valid username.
3. Enter invalid password.
4. Click Login.

**Expected Result:**
Error message is displayed.
User remains on Login page.

---

## TC-003: Login with Empty Fields

**Steps:**
1. Open Login page.
2. Leave username and password empty.
3. Click Login.

**Expected Result:**
Validation messages are displayed.
