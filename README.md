The public collaboration page is [Sudden cardiac death](https://zobermeyer.github.io/scd-replication/).

Edit `scd-replication/index.html` and `scd-replication/styles.css`. The HTML file owns the published text.

The page reproduces the existing collaboration protocol. Its access form link uses the user reviewed agreement version 1.3. The linked US and Sweden protocol drafts keep their existing Google Drive permissions.

Only public materials belong in this repository. Store completed forms, email assent, identities, approvals, and access reports in the separate private administration repository. Keep model files in their separate private repository. This site collects no submissions.

GitHub Pages publishes the repository root from the `master` branch. The root page redirects to `/scd-replication/`.

Run `python3 scripts/check_site.py` before publication. The check uses only Python's standard library. It checks the public file list and local links.
