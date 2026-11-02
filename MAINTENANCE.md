# Keeping the profile current

This repo (the landing page) and `ticohannan/ticohannan` (the GitHub profile README) are reviewed
on a schedule. A review proposes changes as a pull request; nothing is merged without Tico's approval.

## Where updates come from

1. **INBOX.md in this repo.** The fastest way to get something onto the site: add a line there
   (a talk, paper, poster, award, internship, course project, conference attended). Each review
   folds the inbox into the page and clears the items it used.
2. **Public GitHub repositories** under `ticohannan`: new public repos, new releases or version
   bumps, new or renamed Pages sites, and README changes that alter what a project does.
3. **YouTube, @TicoHannanSTEM**: new videos, and new playlists once they exist.

## What belongs on the page

- Finished or clearly working public projects, each with a one-paragraph plain description,
  2–3 real facts (numbers from the project's own README), and links to the demo, source and video.
- Professional items listed in INBOX.md, worded factually.
- The three most recent videos.

## What never goes on the page

- Private repositories, or anything learned from them, unless INBOX.md says to add it.
- Email, phone, home location, school or employer, unless INBOX.md says to add it.
- Claims not backed by a public source or by INBOX.md (no inferred degrees, titles or results).
- Third-party images, except YouTube thumbnails of Tico's own videos.

## How a review runs

1. Read INBOX.md and check the three sources above for anything new since the last review
   (the date at the bottom of this file).
2. If nothing changed, stop: no pull request.
3. Otherwise, on a branch `update/YYYY-MM`, edit `index.html` (and the profile README in
   `ticohannan/ticohannan` when the project list changes), keep the existing design and tokens,
   clear the used INBOX.md lines, update the date below, and open one pull request per repo
   with a short list of what changed and where each fact came from.
4. Check `index.html` still renders at phone width and has no broken links.

Last reviewed: 2026-11-01
