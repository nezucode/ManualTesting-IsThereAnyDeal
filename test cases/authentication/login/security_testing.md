## SC05 - Security Testing

### A001_SC05_TC19 - Verify account lockout after multiple failed login attempts
**Title**: Verify account lockout after multiple failed login attempts <br>
**Execution Status**: ✅ Passed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Enter a valid email | The system accepts the valid email | ✅ Passed |
| 2 | Enter a valid password | The system accepts the valid password | ✅ Passed |
| 3 | Click the eye icon/visibility toggle button | The password displays in plain text | ✅ Passed |
| 4 | Click the eye icon/visibility toggle button again | The password returns to masked format | ✅ Passed |

---
