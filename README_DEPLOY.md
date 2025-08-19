# Deploy su Vercel

1) Crea un repo (facoltativo) e pusha questi file, oppure importa direttamente la cartella in Vercel.
2) In Vercel, scegli **Framework: Other** (static).
3) Deploy. Il file `vercel.json` imposta il fallback SPA su `index.html`.
4) Collega il dominio da **Settings → Domains** (vedi istruzioni DNS sotto).

DNS Aruba (dominio radice e www):
- CNAME `www` → `cname.vercel-dns.com.`
- A/AAAA per root: usa l'opzione **Vercel → Add apex domain** e segui gli IP suggeriti (A/AAAA) oppure imposta un redirect 301 da `@` a `www`.

