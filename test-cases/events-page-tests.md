## [GC-001]: Verify opening, closing, and hover states of the burger menu on a narrowed desktop browser

| Info | Value |
| :--- | :--- |
| **Created** | 2026-03-29 |
| **Last Executed** | 2026-03-29 |
| **Status** | Passed |
| **Environment** | Firefox v.149, Windows 10 |

**Preconditions:**
1. User is on the GreenCity Events page.
2. The browser window is narrowed until the main header navigation collapses and the burger menu icon appears.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :---: | :--- |
| 1 | Hover over the burger menu icon. | - | The cursor changes into a pointer. |
| 2 | Click the burger menu icon. | - | Menu pop-up with navigation links opens. <br>The burger menu icon animates and changes into a 'cross' (close) icon. |
| 3 | Hover over the 'cross' (close) icon. | - | The cursor changes into a pointer. |
| 4 | Click the 'cross' (close) icon. | - | Menu pop-up closes. <br>The 'cross' icon animates back into a burger menu icon. |


## [GC-002]: Verify that an unauthorized user cannot react (like) a comment

| Info | Value |
| :--- | :--- |
| **Created** | 2026-03-29 |
| **Last Executed** | 2026-03-29 |
| **Status** | Passed |
| **Environment** | Firefox v.149, Windows 10 |

**Preconditions:**
1. User is not logged in.
2. User is on an Event Details page that contains at least one comment.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :---: | :--- |
| 1 | Hover over the 'Like' button on any comment. | - | The cursor changes into a pointer. |
| 2 | Click the 'Like' button. | - | A 'Log In' / 'Sign In' pop-up window appears. <br>The reaction count on the comment does not increase. |


## [GC-003]: Verify system rejects Cyrillic characters in the Email input field during Sign Up

| Info | Value |
| :--- | :--- |
| **Created** | 2026-03-29 |
| **Last Executed** | 2026-03-29 |
| **Status** | Passed |
| **Environment** | Firefox v.149, Windows 10 |

**Preconditions:**
1. User is not logged in.
2. User has opened the 'Sign Up' pop-up window.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :---: | :--- |
| 1 | Click on the Email input field and enter an email address containing Cyrillic characters. | `пошта@gmail.com` | The input is accepted in the field. |
| 2 | Click anywhere outside the Email field (remove focus). | - | An error message 'Please check that your e-mail address is indicated correctly' appears under the field.<br>The 'Sign Up' submit button becomes disabled. |
