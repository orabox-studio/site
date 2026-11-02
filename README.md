# OraBox site

Public tree for **https://orabox.app** (Plesk `www`).

Lives beside `studio/` and `apps/` under local `EDWM Project/orabox/`.

```
public/
  index.html                 → /
  apps/<slug>/index.html     → /apps/<slug>/
  privacy/<slug>/index.html  → /privacy/<slug>/
```

```bash
cd ../studio
./scripts/deploy-site-tree.sh
```

Playbook: [studio docs/SITE-AND-DEPLOY.md](https://github.com/orabox-studio/studio/blob/main/docs/SITE-AND-DEPLOY.md).
