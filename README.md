# IFTS - International Forum on Transport Standards

Fictional website for the EB-1B training case (contribution-led version). Static HTML + CSS, GitHub Pages.

- Repo: fanshiyu35/ifts-forum
- Live URL: https://fanshiyu35.github.io/ifts-forum/
- Final domain (CNAME committed, DNS to be configured by the controller): **ifts-forum.org**

## Pages

| Path | Content |
|---|---|
| / | Home - forum intro, organiser, Edition 2025 highlight |
| /history/ | History & scale - founding 2012, editions/attendance table 2013-2025, topic evolution, working groups |
| /2025/ | Edition 2025 - 17-19 June 2025, Prague; theme "Scenario Ranking and Reporting Standards"; keynote Dr. Yanxi Liu (invited by Forum Chair) |
| /archive/ | Edition archive 2013-2025 with venues, themes, keynotes, outcomes |
| /speakers/ | Keynote speaker roster 2013-2025 (12 fictional multi-country speakers + Dr. Yanxi Liu 2025) |
| /contact/ | Secretariat contact (fictional P.O. Box Prague, @ifts-forum.org addresses) |

## Key facts (locked)

- Founded: 2012, Prague. 13 editions 2013-2025. 2025 = 13th edition, 336 delegates, 41 countries.
- Forum Chair (signs the G-3 2025 invitation): **Vilém Skočdopole** (see NAME_CHECK.md).
- Secretary General: Bianca Marinello. Venue 2025: Tessera Congress Centre, Prague.
- 2025 keynote: Dr. Yanxi Liu, "Stability Testing for Transport Performance Rankings: A Multivariate Approach to Scenario Reporting" - delivered by personal invitation of the Forum Chair.
- No reference to ISO/ANSI/CEN or any real standardisation body anywhere. IFTS "does not issue standards and is not a standardisation body".

## Crawling controls

- robots.txt: full-site block (`User-agent: * / Disallow: /`)
- Every page carries `<meta name="robots" content="noindex, nofollow">`
- Footer marker: "Training specimen" (single occurrence per page)

## DNS records required from the controller (for ifts-forum.org)

- CNAME: `ifts-forum.org` -> `fanshiyu35.github.io` (apex or `www` + apex ALIAS/ANAME as the registrar supports)
- Recommended: CNAME `www.ifts-forum.org` -> `fanshiyu35.github.io`; apex via ALIAS/ANAME (Namecheap: "URL Redirect" won't serve Pages; use ALIAS)
- GitHub Pages custom-domain check will stay pending until DNS resolves; the github.io URL works regardless.

## Name checks

All name/domain/venue collision checks are recorded in NAME_CHECK.md (chair, secretary general, 12 speakers, 12 fictional affiliations, venue, forum name, domain availability).
