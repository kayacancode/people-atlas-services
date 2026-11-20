# People Atlas services

Hosted People Graph and reconnect services, separated from the Obsidian plugin so each runtime has its own checks. Public source extracted from kayacancode/obsidian-gmail-crm commit fd12efe1b6f026b0cdfb737894046f47311cc719. No deployment changed during extraction.

The Obsidian plugin lives at https://github.com/kayacancode/obsidian-gmail-crm.

Run `npm ci`, `npm run typecheck`, and `npm test` in `apps/people-graph`. The reconnect service uses its own `npm ci` and `npm run typecheck` in `apps/reconnect-web`.
