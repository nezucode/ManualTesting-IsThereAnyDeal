## SC05 - Security Testing

### A001_SC05_TC19 - Verify account lockout after multiple failed login attempts
**Title**: Verify account lockout after multiple failed login attempts <br>
**Execution Status**: ⛔ Failed <br>
**Preconditions**: 
- User opens the website (https://isthereanydeal.com/)
- User clicks the "User" button then clicks the "Sign in / join" button
- User is currently on the "Sign in" page
- User has a valid registered account (e.g., fkdnd@tiffincrane.com / Qwerty12)

| Steps | Action | Expected Result | Status |
| :--- | :--- | :--- |:--- |
| 1 | Enter a valid email and incorrect password, then click "Sign In" button (1st attempt) | The systems displays an error message (e.g., "The email and password combination is incorrect.") | ✅ Passed |
| 2 | Enter a valid email and incorrect password, then click "Sign In" button (2nd attempt) | The systems displays an error message (e.g., "The email and password combination is incorrect.") | ✅ Passed |
| 3 | Enter a valid email and incorrect password, then click "Sign In" button (3rd attempt) | The systems displays an error message (e.g., "The email and password combination is incorrect.") | ✅ Passed |
| 4 | Enter a valid email and incorrect password, then click "Sign In" button (4th attempt) | The systems shows CAPTCHA challenge (e.g., reCAPTCHA checkbox or image puzzle) | ⛔ Failed |

**Notes:** *No CAPTCHA or account lockout after multiple failed login attempts. Increases risk of brute-force attacks. Recommend adding CAPTCHA after 3–5 failed attempts. See attached [screenshot](https://github.com/nezucode/ManualTesting-IsThereAnyDeal/blob/main/screenshots/D002_A001_TC19_LoginFailedAttempt.png).*

---
