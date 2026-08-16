# GitHub setup checklist

## Stato attuale

Repository pubblica:

`diecieventi/roombook-ai-challenge`

README, sito Pages e materiali community sono già caricati su `main`.

## 1. Crea la GitHub Release v1.4

Vai in:

`Releases → Draft a new release`

Imposta:

- Tag: `v1.4`
- Release title: `RoomBook Challenge v1.4`

Allega esattamente questi due file:

- `RoomBook-Challenge-PARTICIPANT-v1.4.zip`
- `RoomBook-Challenge-SELF-EVALUATOR-v1.4.zip`

Poi pubblica la Release.

I link del sito Pages sono già configurati per questi nomi e per il tag `v1.4`.

### SHA-256 attesi

Participant Kit:

`ef651af48ceba33e1774273458196a143aca94388de32fbbeb15c8ecfbafce86`

Self Evaluator:

`cd226f7ceff495aa8b46771e1a51645b1715e29a9abec593597cbe64cc2de37a`

## 2. Attiva GitHub Pages

`Settings → Pages`

Scegli:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/docs`

## 3. Attiva Discussions

`Settings → General → Features → Discussions`

Attiva Discussions.

## 4. Crea una sola Discussion

Usa:

- titolo: `community/DISCUSSION_TITLE.txt`
- testo: `community/DISCUSSION_BODY.md`

Poi fissala/pinnala in alto.

## 5. Collega la Discussion al sito

Dopo aver creato la Discussion, copia il suo URL e sostituisci in `docs/index.html`:

`DISCUSSION_URL_PLACEHOLDER`

con l'URL reale.

## 6. Descrizione repository suggerita

`A self-contained experiment in structured AI-assisted software development. Build RoomBook, self-evaluate it, and optionally share your repository.`

## 7. Topic suggeriti

`ai`, `software-development`, `challenge`, `codex`, `claude`, `nextjs`, `supabase`, `ai-agents`
