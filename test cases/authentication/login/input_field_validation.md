## SC03 - Input Field Validation

### A001_SC03_TC08 - Verify login with leading/trailing spaces in the email field
**Title**: Verify login with leading/trailing spaces in the email field <br>
**Execution Status**: ✅ Passed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Enter a valid email with leading/trailing spaces (e.g., "fkdnd@tiffincrane.com ") | The system accepts the valid email with leading/trailing spaces  | ✅ Passed |
| 2 | Enter a valid password | The system accepts the valid password | ✅ Passed |
| 3 | Click the "Sign in" button | The system automatically trims whitespace from the email input, the user is allowed to log in and redirected to the homepage | ✅ Passed |

---

### A001_SC03_TC09 - Verify login with leading/trailing spaces in the password field
**Title**: Verify login with leading/trailing spaces in the password fieldd <br>
**Execution Status**: ⛔ Failed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Enter a valid email | The system accepts the valid email | ✅ Passed |
| 2 | Enter a valid password with leading/trailing spaces (e.g., "Qwerty12 ") | The system accepts the valid password with leading/trailing spaces | ✅ Passed |
| 3 | Click the "Sign in" button | Log in should fail if the entered password contains leading/trailing spaces. The system displays an error message (e.g., "The email and password combination is incorrect"). | ⛔ Failed |

**Notes:** *The user is succeed to login with password containing leading/trailing spaces (e.g., "Qwerty12 "). See attached [screenshot](https://github.com/nezucode/ManualTesting-IsThereAnyDeals-LoginTestCases/blob/main/screenshots/ISTAD_A001_TC09_PasswordWithLeadingTrailingSpaces.png)*
