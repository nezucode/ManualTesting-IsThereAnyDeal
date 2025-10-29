## SC01 - Login With Valid Credentials

### A001_SC01_TC01 - Verify login with a valid email and password
**Title**: Verify login with a valid email and password <br>
**Execution Status**: ✅ Passed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Enter a valid email (e.g., fkdnd@tiffincrane.com) | The system accepts the valid email | ✅ Passed |
| 2 | Enter a valid password (e.g., Qwerty12) | The system accepts the valid email | ✅ Passed |
| 3 | Click the "Sign In" button | The user is successfully logged in and redirected to the homepage | ✅ Passed |

---

## SC02 - Login With Invalid Credentials

### A001_SC02_TC02 - Verify login with empty email and password fields
**Title**: Verify login with empty email and password fields <br>
**Execution Status**: ✅ Passed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Leave the email and password fields empty | Both fields remain blank  | ✅ Passed |
| 2 | Click the "Sign in" button | The system displays an error message for the email and password fields (e.g., "Please fill in this field.") | ✅ Passed |

---

### A001_SC02_TC03 - Verify login with an empty email and a valid password
**Title**: Verify login with an empty email and a valid password <br>
**Execution Status**: ✅ Passed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Leave the email field empty | The email field remain blank  | ✅ Passed |
| 2 | Enter a valid password | The system accepts the valid password | ✅ Passed |
| 3 | Click the "Sign in" button | The system displays an error message for the email field (e.g., "Please fill in this field.") | ✅ Passed |


