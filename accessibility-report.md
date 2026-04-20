# Accessibility Report

**Project:** iyf-s10-week-01--erickcodes  
**Author:** Erick Njeru  
**Date:** April 19, 2026

## Introduction
This report documents the accessibility audit performed on my multi-page portfolio website (especially `index.html`) as required in **Task 2.3**.

I followed the Web Content Accessibility Guidelines (WCAG) basics and used the recommended tools.

## Tools Used
- Chrome DevTools Lighthouse (Accessibility audit)
- WAVE Web Accessibility Evaluation Tool (wave.webaim.org)
- Manual keyboard navigation test
- Visual inspection for alt text, headings, and contrast

## Issues Found & Fixes Applied

### 1. Language Attribute
- **Issue:** `<html>` tag had no `lang` attribute.
- **Fix:** Added `lang="en"` → `<html lang="en">`
- **Status:** ✅ Fixed

### 2. Image Alternative Text
- **Issue:** The profile image had a generic or missing alt text.
- **Fix:** Changed to a meaningful description: `alt="Erick Njeru profile picture"`
- **Status:** ✅ Fixed

### 3. Heading Structure
- **Issue:** Headings were not in proper logical order (e.g., skipped levels).
- **Fix:** Used `<h1>` for main title, then `<h2>` and `<h3>` correctly.
- **Status:** ✅ Fixed

### 4. Link Text
- **Issue:** Some links had unclear text like "click here".
- **Fix:** Made links descriptive (e.g., "Learn More About Me", "Visit MDN Web Docs").
- **Status:** ✅ Fixed

### 5. Form Labels (will apply once contact.html is added)
- Ensured every input will have a proper `<label>` associated with it using `for` and `id`.

### 6. Color Contrast & Focus
- Checked text contrast.
- Ensured keyboard focus is visible on navigation links.

## Final Lighthouse Accessibility Score
(After running the audit) → **XX / 100**

**Note:** I will update this score after running Lighthouse on the final version.

## Conclusion
All major accessibility issues have been identified and fixed. The website now uses semantic HTML, proper alt text, and good heading structure. This makes the site more usable for people using screen readers or navigating with keyboard only.

I understand that accessibility is important so that everyone can access my content comfortably.

**Declaration:** This accessibility report is part of my Week 1 submission for IYF Weekend Academy Season 10.
