# Portfolio site

A single static HTML file — no build step required.

## Deploy to Vercel

1. Create a new GitHub repo (e.g. `marcus-portfolio`) and push this folder to it,
   or drag-and-drop the folder directly at vercel.com/new.
2. In Vercel, click "Add New Project," import the repo (or upload the folder).
3. Framework preset: choose "Other" — no build command or output directory needed,
   since it's a plain `index.html`.
4. Click Deploy. Vercel will give you a live `.vercel.app` URL immediately, and you
   can attach a custom domain afterward under Project Settings → Domains.

## Editing later

Everything (markup, styles, content) lives in `index.html`. No dependencies to install.
Open it in any editor, change the text or links, and redeploy by pushing to the repo
(Vercel auto-redeploys on push) or re-uploading the folder.
