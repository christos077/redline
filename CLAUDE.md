# Redline

A web app. Someone uploads a contract, lease, freelance agreement or terms of service and learns what they are actually signing.

## Build exactly these capabilities
- A plain-English summary of the document.
- The clauses that could hurt the user, ranked by severity, each showing its exact source sentence.
- A drafted counter-offer for each flagged clause.
- A question box that answers only from the document.
- An editable list of the user's own red lines, which drives the analysis.
- A saved library of the user's past documents.

Anything not on this list needs my approval first, even when it looks like the obvious next step.
Excluded on purpose: payments and billing, OCR for scanned documents, and sharing a document between users.
This version exists to prove the analysis can be trusted, and none of these make it more trustworthy.
OCR would actively undermine it: a citation is worthless when the text it points at was misread.

## Settled decisions (not open for reinterpretation)
- Next.js, Supabase for auth and database, deployed on Vercel.
- The uploaded file is parsed in the browser. Store only the extracted text; never upload or store the original file.
- The model is called through OpenRouter only. Read the model name from `OPENROUTER_MODEL` in `.env.local`; never hard-code it.
- Every risk flag cites the exact sentence it came from. A flag whose source cannot be shown is a bug.
- Before showing a citation, check that it appears word for word in the stored text. Models reword quotes. If the check fails, do not show the flag.

## Standing rules
- Keep credentials in `.env.local`, which is gitignored. Never commit a secret: a key is public the moment it is pushed and has to be rotated. This repo is public.
- The OpenRouter key and the Supabase service-role key are server-only. Never put them in a `NEXT_PUBLIC_` variable or in client code.
- State only what the document says. Where the text does not support a claim, the product does not make it.
- When the document does not answer a question, the question box says so. It never fills the gap from general knowledge.
- Ask me before adding a dependency.

## Working while I am away
- Commit locally as you go. Ask me before any `git push` or Vercel deploy.
- When you need my answer, for example a new dependency or anything outside the list above, add the question to `QUESTIONS.md`.
  Then skip that piece and keep working on other in-scope parts. Do not guess.

## Read when relevant
- `research/summary.md` holds the user research. Read it before deciding what the product should do.
- `PRD.md` will hold the brief once it exists. Read it before building. If it does not exist yet, ask me before starting a build.

## Agent skills

### Issue tracker
GitHub Issues on christos077/redline (public), via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels
The five default labels: needs-triage, needs-info, ready-for-agent, ready-for-human, wontfix. See `docs/agents/triage-labels.md`.

### Domain docs
Single-context: `GLOSSARY.md` and `docs/adr/` at the repo root. See `docs/agents/domain.md`.
