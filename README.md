# ABA Lab — Task Queue

Auto-maintained, read-only lab view of the ABA Lab task queue.
**Do not edit by hand** — updates are pushed automatically whenever a task is
approved, rejected, or revised (and on an hourly refresh).

- **Board:** `index.html` + `data.json` (live data)
- **System of record:** Supabase `task_queue` table
- **Approvals happen in** the lab's internal WebUI tab (ABA Task Queue)

## Site

Served by GitHub Pages at `https://GabbinTheGreat.github.io/aba-lab/`.

## One-time activation (Gabe)

1. Make the repo **Public** — Settings → *Danger zone* → *Change visibility*
   → Public. (GitHub Pages on a free account only serves public repos.)
2. Settings → **Pages** → Source: **Deploy from a branch** → branch `main`,
   folder `/(root)` → Save.
3. Site is live at the URL above within ~2 minutes.
