# StudySpark Hub

A responsive study website with subject folders, revision notes, practice tests, mock tests, daily tracking, analytics and a local profile experience.

## Website-wide update — 4 November 2026

- One consistent neon-purple / midnight-blue design language across home, subjects, notes, test series, mock test centre, tracker, analytics and profile.
- Responsive sidebar and search/header navigation, with a collapsible menu on tablet and phone.
- Mobile-first card grids and overflow-safe subject, test, notes, mock-test, tracker, analytics and profile layouts; compact readers and exam controls for phone widths.
- Adaptive card grids, modal readers, chapter navigation and timed test runner layouts.
- Existing study notes, question banks, Polity, English and other subject sections are retained.

## Algebra revision

Path: `Maths → Algebra → Algebra Revision → Algebra Revision Workspace`

The single Algebra Revision workspace has nine switchable concept tabs:

1. Square identities, sum/difference relations and derived forms.
2. Cube identities and factorisation.
3. Perfect squares, completing the square and sums of real squares.
4. Reciprocal expressions, special cases and higher-power recurrence.
5. Three-variable square/cube identities and equality conditions.
6. Value putting, symmetric/cyclic expressions and Componendo–Dividendo.
7. General powers, odd-power sums and telescoping factor chains.
8. Zero-sum squares and quadratic forms.
9. Quartic patterns and polynomial simplification.

### Algebra tests

- Original Algebra Revision Fast Test: 28 questions, 12 minutes. Preserved.
- Existing Algebra Complete Revision Test: 52 questions, 35 minutes. Preserved.
- Algebra PDF 02 + 03 Coverage Practice: 60 newly authored questions, 45 minutes. This maps one original practice variant to each of the 51 Algebra question slides in PDF 02 and 9 Algebra question slides in the first Algebra section of PDF 03.

The 60 Algebra and 17 Mensuration questions are newly authored variants aligned to each question slide in PDF 02 and PDF 03. They preserve the mathematical skill, question style and difficulty pattern without copying the commercial slide wording. Existing 28- and 52-question banks remain separate and unchanged. Total retained + new Algebra-related practice: 28 + 52 + 60 Algebra questions, plus 17 Mensuration 3D questions.

## 3D Mensuration

Path: `Maths → Mensuration 3D`

- Illustrated 3D formula guide: prisms, pyramids, cuboids, cubes, cylinders, cones, spheres, hemispheres, hollow solids and recasting.
- Mensuration 3D PDF 03 Coverage Practice: 17 newly authored question variants matching the 17 question slides in the Mensuration section of PDF 03, 20 minutes.
- Includes an original vector diagram asset, `mensuration-shapes.svg`.

## Source scope and limitations

PDF 02 contains 51 question slides. PDF 03 contains 9 Algebra question slides and 17 Mensuration 3D question slides. Practice questions are original variants, not verbatim reproductions of the supplied commercial PDFs. The concept guides summarise formulas and methods. Where a source slide is unreadable or ambiguous, the website does not guess its exact wording.

## Existing study areas retained

- Maths Simplification and other topic folders.
- English grammar, summaries and 120 Rules test parts.
- General Knowledge / Polity, articles, amendments and lecture notes.
- Reasoning, mock test centre, test series and sectional tests.
- Daily checklist, study-time analytics, answer review and profile.

## Data note

Study time and checklist progress are stored in browser local storage. They stay on that browser/device and are not synchronised across devices. Shared profile syncing requires a secure backend and database.

## Deploy to GitHub Pages

1. Back up the current repository.
2. Extract this ZIP.
3. Upload the contents of the `studyspark_final` folder to the repository root, replacing files with the same names.
4. Keep all image assets (`hero-character.png`, `sidebar-mascot.png` and `mensuration-shapes.svg`) beside `index.html`.
5. Commit and push the changes.
