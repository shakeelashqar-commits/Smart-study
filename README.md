# Smart Study — starter website

This is a responsive static website starter for a free CBSE learning platform for Classes 8–12, in Tamil and English.

## Run locally
Open `index.html` in a modern browser. No build tools are needed.

## Included in this starter
- Responsive homepage and class selector (8–12)
- Subject cards and sample chapter navigation
- Tamil/English UI toggle
- Sample quiz with instant feedback
- Demo progress saved in the current browser's local storage
- Demo login modal (NOT secure authentication)
- Sample downloadable revision sheet (currently a text file template)

## Important limitations
This is a starter/demo, not yet a complete public learning platform:
- Login is only a front-end demo. Do not use real passwords or sensitive student data.
- Progress is stored only in the same browser/device.
- Real video lessons are not connected yet.
- Full chapter-wise PDFs, PYQs, answers and quizzes have not been populated.
- The sample download is a template, not a complete CBSE chapter PDF.

## Publish for free (example: GitHub Pages)
1. Create a GitHub account if you don't have one.
2. Create a new public repository named `smart-study`.
3. Upload `index.html` and `README.md`.
4. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
5. GitHub will show the published URL, usually `https://YOUR-USERNAME.github.io/smart-study/`.

A free subdomain is available through the hosting provider. A custom `.com` domain usually costs money. Availability and provider limits can change.

## To make it production-ready
1. Connect Supabase Auth for secure login and a database for student profiles/progress.
2. Store only necessary student data; add privacy policy and guardian/school review as appropriate.
3. Add videos from sources that allow embedding and are legally shareable.
4. Add original or openly licensed PDFs and verified question banks. Respect copyright.
5. Add accessibility, backups, abuse protection and a moderation process.
