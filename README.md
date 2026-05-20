

Aaran Patel

**1-** Within a GitHub Action that runs whenever code is pushed. Automated tests exist to catch bugs automatically, running them manually defeats part of that purpose since a developer can forget or skip it. A GitHub Action triggers on every push, meaning every team member's code gets tested consistently without relying on anyone to remember. For a team project especially, this acts as a safety net, if someone pushes code that breaks existing functionality, the pipeline catches it immediately before it merges into main.

**2-** No. End-to-end tests are designed to replicate a user's workflow through the UI from start to finish. To check if a function returns the correct output, you would use a unit test instead.

**3-** Navigation mode analyzes the page immediately after it loads, measuring performance metrics like load time and render speed, but cannot evaluate user interactions or dynamic content changes after load. Snapshot mode analyzes the page in its current state at a single moment in time, making it best for catching accessibility issues, but it cannot measure JavaScript performance or DOM changes.

**4-**
- Fix accessibility issues on interactive elements ; the Accessibility score of 90 suggests some elements may be missing ARIA labels or have insufficient color contrast, which affects screen reader users.
- Add a `<meta name="description">` tag; the SEO score of 91 is likely docked partly because the page lacks a description meta tag, which search engines use to index and display the page.
- Ensure all links have descriptive text; sites like this often have anchor tags without meaningful text (e.g. just an image with no alt text inside a link), which hurts both SEO and accessibility simultaneously.