# Testing for accessibility

Knowing the basics is not enough; you have to check whether your site actually meets them. Accessibility testing combines automated tools that catch some issues cheaply, manual checks that catch what tools cannot, and, where possible, feedback from people who actually use assistive technology. No single method finds everything, which is why a layered approach is the standard.

## Automated tools catch some of it

Automated accessibility checkers scan a page and report problems like missing alt text, insufficient contrast, missing form labels, and certain structural issues. They are fast, free, and worth running, and they catch a meaningful share of common problems. Their limit is that they can only check what is machine-detectable, which is a minority of all accessibility issues. A tool can tell you an image has no alt text, but it cannot tell you whether the alt text you wrote actually describes the image well. It can flag low contrast but cannot judge whether your focus order makes sense. Treat automated tools as a first pass that catches the obvious mechanical failures, not as proof of accessibility.

## The keyboard test, done by you

The single most valuable manual check, as the keyboard page covered, is to use your site with the keyboard only. Tab through every page, confirm you can reach and operate everything, that focus is always visible, that the order makes sense, and that nothing traps you. This costs nothing and finds operability problems that automated tools miss entirely, because whether a page is genuinely usable by keyboard is a judgment a tool cannot fully make. Doing this honestly on the main tasks of your site, signing up, buying, navigating, surfaces a large share of real barriers.

## Testing with a screen reader

The next step up is to try your site with a screen reader, the software that reads the page aloud for blind and low-vision users. Major operating systems include one built in, so you can try it without extra cost. Navigating your own site by listening rather than looking reveals whether your headings, landmarks, alt text, and labels actually produce a sensible experience, or whether a screen reader user would be lost. It takes some practice to use a screen reader even roughly, but even a clumsy attempt surfaces problems, like an unlabelled button announced as just button, that you would never notice visually. This is the manual check that most directly tests the screen reader experience the earlier pages aimed at.

## Real users are the strongest test

The most reliable way to know whether your site is accessible is feedback from people who actually use assistive technology daily, because they navigate it fluently and notice problems no checklist captures. This is not always practical for a small operator, but where you can get it, through accessibility user testing or feedback from disabled users, it is the strongest signal. Lived experience finds the issues that automated tools, your own keyboard test, and your fumbling screen reader attempt all miss, because real users know how the tools are meant to work and feel the friction immediately. When formal testing is out of reach, simply inviting and acting on accessibility feedback from your actual users is a meaningful step.

## Build it into the routine

Accessibility, like security and performance, degrades as a site changes, so testing belongs in the regular routine rather than being done once. A new feature can introduce an unlabelled control, a redesign can remove focus indicators, new content can ship without alt text. Running the automated checker and the keyboard test after meaningful changes, and revisiting the basics periodically, keeps accessibility from quietly eroding. The pattern matches the rest of this portfolio's baselines: it is maintained, not completed. A site that was accessible at launch stays accessible only if each change is checked against the same basics that made it accessible in the first place.
