# Pharmacy Tech Exam Prep support and legal site

Static English and Spanish support/legal pages for the iOS app. English is authoritative. No build step, JavaScript, external font, analytics, or form is required.

## Pages

The root `index.html` is the English landing page; `index-es.html` is Spanish. Each policy and support page has an English page and a matching `-es.html` page. `404.html` is the fallback. `.nojekyll` keeps GitHub Pages from running Jekyll.

## Preview locally

From this directory, run `python3 -m http.server 8000` and open `http://localhost:8000/`. Links are relative so the site also works at a GitHub Pages project path.

## Publication

This dedicated repository publishes from the `main` branch root through GitHub Pages at https://mcleung-888.github.io/pharmacy-tech-exam-prep-support/. The copy-ready English and Spanish URLs are in `APP_STORE_URLS.md`. Verify the public pages and email links before entering URLs in App Store Connect.

## Release review

The wording reflects the inspected PTCE Flutter entry point in `APP_BASE/rbt_exam_prep/lib/ptep/` as of 7 October 2026. Recheck the shipping binary, dependency graph, StoreKit product configuration, data behavior, and legal text before publication and whenever the app changes. This site does not substitute for product owner or legal review.
