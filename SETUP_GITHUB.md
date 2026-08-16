# GitHub setup checklist

## 1. Create a public repository

Suggested name:

`roombook-ai-challenge`

Push all files from this bundle to `main`.

## 2. Enable GitHub Pages

`Settings → Pages`

Choose:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/docs`

## 3. Enable Discussions

`Settings → General → Features → Discussions`

Enable Discussions.

## 4. Create one Discussion

Use:

- title: `community/DISCUSSION_TITLE.txt`
- body: `community/DISCUSSION_BODY.md`

Pin it.

## 5. Patch the Discussion link

Replace `DISCUSSION_URL_PLACEHOLDER` in `docs/index.html` with the URL of the pinned Discussion.

## 6. Downloads

Current Participant and Self Evaluator ZIPs are already in `/downloads`.

For v1 this is enough. Later they can be moved to GitHub Releases if desired.

## 7. Suggested repository description

A self-contained experiment in structured AI-assisted software development. Build RoomBook, self-evaluate it, and optionally share your repository.

## 8. Suggested topics

`ai`, `software-development`, `challenge`, `codex`, `claude`, `nextjs`, `supabase`, `ai-agents`
