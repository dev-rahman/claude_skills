# Your profile & assets

This folder is how the skill **remembers you** across chats in the Claude app.
Whatever lives here travels inside the skill package, so every new conversation
that uses the skill already has your CV and details — no re-upload.

## What to put here

- **`base_cv.pdf`** or **`base_cv.docx`** — your current CV / Lebenslauf. This is
  the source document every tailored CV is built from.
- **`sample_cover_letter.pdf`/`.docx`/`.txt`** — optional. One real cover letter
  you've written, so the skill learns *your* voice instead of sounding like AI.
- **`profile.md`** — auto-generated structured summary of you (parsed from the CV).
  Edit it anytime to correct or update details.
- **`style_notes.md`** — auto-generated notes on your writing voice.

## Two ways to use it in the Claude app

1. **Bundle your CV (recommended — persists everywhere):** put `base_cv.*` in this
   folder, re-zip the `job-skill-germany` folder, and re-upload the skill in
   claude.ai → Settings → Capabilities → Skills. Now every chat has your CV built
   in.
2. **Upload per conversation:** skip bundling and just attach your CV to the chat
   (or the Project) when you start. The skill reads the uploaded file. You'll
   re-attach it in each new chat.

A claude.ai Space/Project file can't be reached from a local tool session, but in
the Claude app itself the skill can read what you upload to the conversation —
either approach above works there.
