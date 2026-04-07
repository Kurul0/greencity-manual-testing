## [GC-BUG-002] 'Form Habit' button fails to trigger redirection on 'About us' page after visiting 'Places' page

| Info | Value |
| :--- | :--- |
| **Created** | 2026-04-07 |
| **Environment** | Firefox v.149, Windows 10 |
| **Severity** | Major |

**Preconditions:**
1. User is not logged in.
2. User is on GreenCity Home page.

**Steps to Reproduce:**
1. Click the 'Places' button in the header menu.
2. Once the 'Places' page loads, click the 'About us' button in the header menu.
3. Click the 'Form Habit' button at the top of the page under 'About Us' chapter.

**Expected Result:** 
1. The user is redirected to the GreenCity Home page.
2. The 'Sign in / Sign up' pop-up appears.

**Actual Result:** The 'Form Habit' button displays a click animation, but the expected redirection to the Home page and the 'Sign in' pop-up are not triggered.

**Attachments:** <img width="1280" height="681" alt="зображення" src="https://github.com/user-attachments/assets/eba2ea48-3798-407e-8333-0a707b099225" />

**Additional Notes** If you reload the website or don't visit 'Places' page the 'Form Habit' button will work, but as soon as you visit the 'Places' page, it fails.
