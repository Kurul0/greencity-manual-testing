# Manual Testing: GreenCity Events Page

This repository contains the practical implementation of the manual testing process for the GreenCity web application.

### Project Overview
**Objective:** To perform manual testing of the public-facing features on the About Us and Events pages, and to design structured documentation.

The project focuses on analyzing the following key system aspects:
- Navigation behavior (burger menu) on narrowed desktop viewports.
- System state handling during unauthorized user interaction with restricted features.
- Error handling for invalid data formats (Cyrillic characters in the Email input field).
- Viewport positioning during page loading.
- Button functionality and redirection.

**Test-cases overview:**
- [[GC-001]](test-cases/events-page-tests.md): Verify opening and closing of the burger menu on a narrowed desktop viewport
- [[GC-002]](test-cases/events-page-tests.md): Verify that an unauthorized user cannot react (like) a comment
- [[GC-003]](test-cases/events-page-tests.md): Verify system rejects Cyrillic characters in the Email input field during Sign Up
- [[GC-004]](test-cases/about-us-page-tests.md): Verify that the 'About us' page loads at the top of the viewport
- [[GC-005]](test-cases/about-us-page-tests.md): Verify navigation of the 'Find eco places' button on the 'About us' page
- [[GC-006]](test-cases/about-us-page-tests.md): Verify navigation of the 'Form habit' button on the 'About us' page

**Test Object:** [GreenCity Website](https://www.greencity.cx.ua/#/greenCity)

> **Note:** GC stands for the GreenCity project key, and the following numbers represent the sequential ID for test cases and bug reports.

**Author:** *Kyrylo-Yurii Popailo*
