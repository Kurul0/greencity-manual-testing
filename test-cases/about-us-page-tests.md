## [GC-004] Verify that the 'About us' page loads at the top of the viewport

| Info | Value |
| :--- | :--- |
| **Created** | 2026-04-07 |
| **Last Executed** | 2026-04-07 |
| **Status** | Failed [*(See GC-BUG-001)*](../bug-reports/GC-BUG-001.md) |
| **Environment** | Firefox v.149, Windows 10 |

**Preconditions:**
1. User is not logged in.
2. User is on the GreenCity Home page.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :--: | :--- |
| 1 | Hover over the 'About us' button in the header menu. | - | The cursor changes into a pointer. |
| 2 | Click the 'About us' button. | - | The 'About us' page opens, and the viewport is positioned at the very top of the page. |

---

## [GC-005] Verify navigation of the 'Find eco places' button on the 'About us' page

| Info | Value |
| :--- | :--- |
| **Created** | 2026-04-07 |
| **Last Executed** | 2026-04-07 |
| **Status** | Passed |
| **Environment** | Firefox v.149, Windows 10 |

**Preconditions:**
1. User is not logged in.
2. User is on the GreenCity 'About us' page.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :--: | :--- |
| 1 | Hover over the 'Find eco places' button. | - | The cursor changes into a pointer. |
| 2 | Click the 'Find eco places' button. | - | The user is navigated to the 'Places' (Map) page.<br>The 'Sign in / Sign up' pop-up appears. |

---

## [GC-006] Verify navigation of the 'Form habit' button on the 'About us' page

| Info | Value |
| :--- | :--- |
| **Created** | 2026-04-07 |
| **Last Executed** | 2026-04-07 |
| **Status** | Failed |
| **Environment** | Firefox v.149, Windows 10 |

**Preconditions:**
1. User is not logged in.
2. User is on the GreenCity 'About us' page.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :--: | :--- |
| 1 | Hover over the 'Form habit' button**. | - | The cursor changes into a pointer. |
| 2 | Click the 'Form habit' button. | - | The user is redirected to the GreenCity Home page.<br>The 'Sign in / Sign up' pop-up appears. |
