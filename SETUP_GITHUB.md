# GitHub setup checklist

## 1. Repository

Repository pubblica:

`diecieventi/roombook-ai-challenge`

I file principali sono già caricati su `main`.

## 2. Enable GitHub Pages

`Settings → Pages`

Choose:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/docs`

I due ZIP pubblici sono già copiati anche in `docs/downloads/`, quindi i pulsanti del sito Pages funzionano senza GitHub Releases.

## 3. Enable Discussions

`Settings → General → Features → Discussions`

Enable Discussions.

## 4. Create one Discussion

Use:

- title: `community/DISCUSSION_TITLE.txt`
- body: `community/DISCUSSION_BODY.md`

Poi fissala/pinnala in alto.

## 5. Patch the Discussion link

Dopo aver creato la Discussion, copia il suo URL.

Replace `DISCUSSION_URL_PLACEHOLDER` in `docs/index.html` with that URL.

## 6. Downloads

Le copie usate dal sito Pages sono:

- `docs/downloads/RoomBook-Challenge-PARTICIPANT-v1.4.zip`
- `docs/downloads/RoomBook-Challenge-SELF-EVALUATOR-v1.4.zip`

Esistono anche copie in `/downloads` come archivio della repository.

## 7. Suggested repository description

A self-contained experiment in structured AI-assisted software development. Build RoomBook, self-evaluate it, and optionally share your repository.

## 8. Suggested topics

`ai`, `software-development`, `challenge`, `codex`, `claude`, `nextjs`, `supabase`, `ai-agents`
