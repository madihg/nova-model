# nova-model

Course chat demo ("Hi, I'm Nova.") on the Vercel shooketh fine-tuning template, serving `ft:gpt-3.5-turbo-0125:personal:nova-model:B7o56WuQ` from `app/api/chat/route.ts`.

## Session State (2026-10-21)

- Rebuilt here after github.com/madihg/nova-model was deleted: cloned madihg/futurev-meta (same template), swapped model id, system prompt (from `scripts/data.jsonl`), heading, example prompts; copy taken from the last production deployment via `vercel curl / --deployment dpl_Hw93hKRML9Ly1XPn25yddrmvxJ9Y`.
- Deployed to production: https://nova-model-three.vercel.app (Vercel project nova-model, linked via .vercel/). Deploy from a copy without `.git`, otherwise Vercel blocks the CLI deployment (TEAM_ACCESS_REQUIRED).
- Source: github.com/madihg/nova-model (public, recreated 2026-10-21); the Vercel project is git-linked to it again, so pushes to main deploy production.
- Chat untested end to end: the OpenAI account had zero API credits on 2026-10-21.
