# Accessibility Audit — CampusConnect

## Scope and method
This is a preliminary source-code review of the supplied HTML and CSS. An automated Lighthouse or WAVE browser audit has **not** been run in this environment. Do not report an automated score until you run one in a browser.

## Checks completed by source review

| Check | Result | Evidence / note |
|---|---|---|
| Document language | Pass | `<html lang="en">` is present. |
| Page title and metadata | Pass | Descriptive title, UTF-8, viewport and description metadata are present. |
| Semantic landmarks | Pass | Header, labelled navigation, main, sections, article, aside and footer are used. |
| Heading hierarchy | Pass | One h1, followed by section h2 headings and card/panel h3 headings. |
| Skip navigation | Pass | Keyboard-visible skip link targets the main content. |
| Form labels | Pass | Every input, select and textarea has an associated label. |
| Grouped controls | Pass | Related controls use fieldset and legend. |
| Required fields | Pass | Required attributes and a visible required-field note are present. |
| Keyboard focus | Pass | Native controls plus `:focus-visible` outlines are styled. |
| Responsive layout | Pass | CSS grid changes to a single column on smaller screens. |
| Reduced motion | Pass | Reduced-motion preference disables smooth scrolling and limits transitions. |
| Form data storage | Not implemented | Demo form must be connected to a secure backend before real use. |

## Run an automated audit

1. Open `index.html` in Google Chrome or deploy the page to a test host.
2. Open Developer Tools → **Lighthouse**.
3. Select **Accessibility** (optionally also Best Practices and SEO), choose the mobile or desktop mode, and select **Analyze page load**.
4. Save the generated report or record the score, date, browser version and any flagged issues here.
5. Alternatively, open the page in the WAVE browser extension and review errors, contrast alerts and structural indicators.
6. Fix every genuine issue, rerun the audit, and attach the final report to the submission.

## Manual testing still recommended
- Navigate the entire page using Tab, Shift+Tab, Enter and Space.
- Confirm the skip link appears when focused and moves focus to the main content.
- Test labels and form validation with a keyboard and screen reader.
- Check text/background contrast with WAVE or a contrast analyser, especially after changing colours.
- Test at 200% zoom and on a narrow mobile viewport.

## Audit record
- Automated tool: Not yet run
- Date: Pending
- Accessibility score: Pending
- Outstanding findings: Run Lighthouse or WAVE and record results before final submission.
