# OraBox site

Public tree for **https://orabox.app** (Plesk `www`).

```
public/
  index.html                 → /
  apps/<slug>/index.html     → /apps/<slug>/
  privacy/<slug>/index.html  → /privacy/<slug>/
```

Deploy (shared credentials in `orabox-studio/.env`):

```bash
cd ../orabox-studio
./scripts/deploy-site-tree.sh
```

See [SITE-AND-DEPLOY.md](https://github.com/orabox-studio/studio/blob/main/docs/SITE-AND-DEPLOY.md).
