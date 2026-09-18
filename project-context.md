# KOR-0320 marketing site context

- Service: 투자자산운용사 전 과목 500제
- Service ID: KOR-0320
- Android package / iOS bundle: `app.mcyj.examprep.kor0320`
- Scope: currently released app marketing site for GitHub Pages
- Locales: Korean primary, English support
- Design: navy and electric-mint portfolio research terminal
- Typography: preserve Korean word units with global `word-break: keep-all`
- Store badges: App Store and Google Play controls use identical 194 × 75 frames
- Public store links: exact Google Play package and App Store ID `6797954250`
- Official source: Korea Financial Investment Association qualification center, code `FWM006`
- Source app is read-only; website work is isolated in this repository.

## Verification log

- 2026-09-19: Initialized the isolated marketing-site project after confirming no local or remote repository collision.
- 2026-09-19: Revalidated live KOFIA `FWM006` data: 3 subjects, 20/30/50 question allocation, 100 questions in 120 minutes, 40% per-subject floor, and 70% overall standard.
- 2026-09-19: Built 34 indexable routes and 36 HTML files across Korean and English.
- 2026-09-19: `npm test` verified metadata, internal links, official exam structure, both released Store identities, global `word-break: keep-all`, and equal 194 × 75 marketplace badge frames.
- 2026-09-19: Local and production HTTP QA passed for all 34 sitemap routes, representative static assets, and the custom 404 page.
- 2026-09-19: Created public repository `MCYJ/500-kor-0320-web`, enabled workflow-based GitHub Pages, and completed deployment run `35376911612`.
- 2026-09-19: Production identity verification passed for App Store ID `6797954250` and Google Play package `app.mcyj.examprep.kor0320`.
- Production: https://mcyj.github.io/500-kor-0320-web/ko/
