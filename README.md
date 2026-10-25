# Hallo — support, issues and ideas

Public support site and issue tracker for **Hallo**, a fully unlocked SwiftUI study
reconstruction of the Halo iOS app. The app source lives in a private repository; this
repository holds the support page and the public issue tracker.

- **Support page:** <https://jphermans.github.io/hallo-support/>
- **Report a bug:** [new bug report](https://github.com/jphermans/hallo-support/issues/new?template=bug_report.yml)
- **Request an improvement:** [new idea](https://github.com/jphermans/hallo-support/issues/new?template=feature_request.yml)
- **Email:** support@jphsystems.io · JPHsystems, Belgium

## What is in here

| Path | Purpose |
| --- | --- |
| `index.html` | The support page (GitHub Pages, single file, no JavaScript, no analytics) |
| `screenshots/` | Images used by the page, downscaled to 900 px |
| `.github/ISSUE_TEMPLATE/` | Bug report and improvement forms, plus contact links |

## Filing a good report

Include the app version and build (Settings → About, e.g. `0.1.0 (8)`), your device and
iOS version, then the steps that lead to the problem, what you expected and what happened
instead. Never paste API keys or mail passwords into an issue.

## Deployment

Pages serves `main` at the repository root. To update: edit `index.html`, commit, push —
the site rebuilds automatically in under a minute.
