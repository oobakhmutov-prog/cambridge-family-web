# TESTING_CHECKLIST.md

## Goal

Protect critical product, UX, and lead-generation flows.

## Core manual QA checklist

### General
- pages load correctly
- no broken links
- no obvious layout breaks
- no console-critical issues
- favicon and metadata render correctly

### Responsive
- desktop layout works
- tablet layout works
- mobile layout works
- spacing remains consistent
- no clipped content
- no broken cards or buttons

### Navigation
- header navigation works
- route pages open correctly
- CTA buttons link correctly
- footer links work
- language switching works if implemented

### Forms
- required fields validate correctly
- invalid inputs show useful errors
- successful submission is clear
- failed submission is handled clearly
- no duplicate-submit issues
- spam protection works as expected

### Content
- headings are correct
- text hierarchy is clear
- no placeholder content remains
- no duplicated blocks accidentally appear

### SEO basics
- titles render correctly
- meta descriptions exist
- headings are structured properly
- pages are indexable as intended
- sitemap and robots are available

### Performance
- images load correctly
- images are responsive
- lazy loading works where expected
- no major layout shift during load
- page feels fast on mobile

### Accessibility
- keyboard focus is visible
- buttons and links are accessible
- forms have labels
- images have alt text where needed
- contrast remains acceptable

### Analytics
- CTA clicks are tracked
- form submissions are tracked
- route selection interactions are tracked
- contact clicks are tracked

## Recommended automated coverage

At minimum:
- homepage renders
- route pages render
- main CTA exists and works
- form validation works
- successful form submit flow works
- no critical navigation regression

## Pre-release rule

No production release without:
- responsive QA
- form QA
- SEO sanity check
- analytics sanity check
