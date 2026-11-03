# StudySpark Hub — dashboard and subject workspace refresh

This update gives the Home screen a richer dark dashboard style while preserving the existing study library and exam workflows.

## What changed

- Refreshed the Home hero, progress panel, study-time overview and quick-action cards.
- Added live Today / This Week / This Month study-time totals to the dashboard. The existing profile view still contains the detailed history.
- Improved subject-card spacing, colours, hover states and responsive layout.
- Added chapter/section counts to subject cards using the actual subject structure in the project.
- Clarified the subject descriptions and the Notes / Practice Tests / Formula & Revision navigation.
- Removed third-party coaching/platform names and branded source attributions from visible study copy. Existing educational content and question banks remain in the project.
- Renamed the old “Mock Matrix” wording to “Mock Test Centre”.

## Existing study content retained

- Maths notes and the 80-question Simplification challenge.
- English grammar notes, summaries and four 450-question practice parts.
- General Knowledge folders, including Indian Polity, History, Geography, Science, Economy, Current Affairs and Criminal Law.
- Constitution article and amendment summaries and their practice sets.
- Bank Exams, Computer Knowledge and Reasoning study sections.
- Daily checklist, Mock Test Centre, Test Series, answer review and local study-time tracking.

## Important data note

Study time and checklist progress are stored in the browser's local storage. They remain on that browser/device and are not synchronised across devices. A real shared profile requires a secure backend and database.

## Deploy

1. Back up the current repository.
2. Extract this ZIP on your computer.
3. Replace `index.html`, `app.js`, and `style.css` in the repository root with the extracted files.
4. Keep any unrelated image/assets folders already in your repository.
5. Commit and push the changes to GitHub.

The JavaScript syntax check passed with `node --check app.js`. A full interactive browser regression test was not completed for this update.
