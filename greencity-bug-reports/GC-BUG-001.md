## [GC-BUG-001] 'About us' page opens automatically scrolled down instead of at the top

| Info | Value |
| :--- | :--- |
| **Created** | 2026-04-07 |
| **Environment** | Firefox v.149, Windows 10 |
| **Severity** | Minor |

**Preconditions:**
1. User is not logged in.
2. User is on the GreenCity Home page.

**Steps to Reproduce:**
1. Click the 'About us' link in the header menu.

**Expected Result:** The 'About us' page opens, and the viewport is positioned at the very top of the page.

**Actual Result:** The 'About us' page opens, but the viewport is automatically scrolled down to the middle section of the page.

**Attachments:** <img width="1280" height="749" alt="зображення" src="https://github.com/user-attachments/assets/9cdc8f3e-5999-47a8-8911-4e95e7b901e3" />

**Additional Notes:** The position of the viewport upon loading follows a specific pattern depending on the previous page:
* If navigated from the Home page or EcoNews page, the viewport is positioned at the second item: *"Eco products are too expensive"*.
* If navigated from the **Events page**, the viewport is positioned at the first item: *"I don’t have time to look for eco stores"*.
Maybe there is an issue with anchor tags or router scroll memory between page transitions.
