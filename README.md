# GEKON — GitHub Pages

Статическая обзорная страница meta-репозитория VPN-gekon.

## Локально

```bash
open docs/index.html
# или
python3 -m http.server -d docs 8080
```

## GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` → Folder: **/docs**.

URL: `https://<user>.github.io/<repo>/`

## Forgejo Pages

Если Pages включены на Forgejo — укажите root `docs/` (или скопируйте `docs/index.html` в ветку `pages` по политике инстанса).

## Состав

| Файл | Назначение |
|------|------------|
| `index.html` | Лендинг: продукт, стек, infra, репозитории, tier-карта |
| `assets/gekon-logo.svg` | Марка G |
| `assets/gekon-hero-logo.svg` | Wordmark для hero |
| `assets/favicon.svg` | Favicon |

Бренд и палитра синхронизированы с [gekon.tech](https://gekon.tech) (тёмный фон, mint/cyan).
