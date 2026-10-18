# 🛡️ Manifiesto — Labs & Drops

> **Identidad:** `Labs [icono] Drops` — sin ampersand, sin "mrclo" en nombres de usuario/dominio.

## Identidad de marca

| Elemento | Valor |
|---|---|
| Dominio | `labsndrops.dev` |
| Lockup visual | `Labs <img class="brand-lockup-emblem"> Drops` |
| GitHub org | `labsndrops` |
| Instagram / X / GitHub | `@labsndrops` |
| TikTok | `@labs_drops` (pendiente: `@labsndrops`) |
| LinkedIn | `linkedin.com/in/lmrclo/` |
| Email destino | `labs.drops@gmail.com` |

## Reglas de código

1. **Nunca** usar `mrclo.dev`, `mrclo-devops` o `&` en URLs, nombres de usuario, repos o lockups visuales.
2. **CSS lockup**: siempre `.brand-lockup` + `.brand-lockup-emblem` (definido en `portal.css` o inline).
3. **Referencias al sitio**: solo `labsndrops.dev`.
4. **Hashtag**: `#labsndrops` (nunca `#mrclodev`).

## Reglas de repos

1. **Un código, un repo.** No duplicar.
2. **Fuente única del sitio**: `labsndrops-pages` (Cloudflare Pages, repo privado).
3. **Fuente única de Heartbeats**: `heartbeats-memories/`.
4. **NO recrear** `mrclo-devops.github.io` (eliminado 2026-10-17).
5. **NO usar GitHub Pages** (exige repo público; el sitio debe ser privado).
6. **Deploy**: `git push origin main` → Cloudflare Pages → `labsndrops.dev`.

## Deploy

```bash
# Desde cualquier clon de labsndrops-pages:
git push origin main   # Cloudflare Pages despliega automáticamente
```

## Archivos de referencia

- Lockup CSS: `assets/css/portal.css` → `.brand-lockup`, `.brand-lockup-emblem`
- Perfil de marca: `labsndrops/labsndrops` (GitHub README)
- Plan migración: `.IA Talks/temas/05_infraestructura_devops_y_herdr/PLAN_MIGRACION_MRCLO_DEV_A_LABSNROPS_DEV.md`
