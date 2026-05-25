# Ovii Care

A women's health companion — cycle tracking, mood & symptom logs, partner sharing, gamified points, and a curated shop.

🌐 [oviicare.com](https://oviicare.com) · 🌍 EN / AR

---

## Repos

- **[mobile-application](https://github.com/Ovii-Care/mobile-application)** — Flutter app (iOS + Android). Dart, BLoC, Dio, Firebase. FVM-pinned to 3.44.
- **[backend](https://github.com/Ovii-Care/backend)** — Laravel 10 API + AdminLTE panel + marketing site. PHP 8.2, MySQL 8, Redis 7, OAuth2 (Passport).
- **[infra](https://github.com/Ovii-Care/infra)** — Terraform on AWS (EC2 / RDS / S3), Docker Compose for staging & prod, operator runbooks.

Each repo has its own README with full setup. New laptop? Start with the [Mac setup guide](https://github.com/Ovii-Care/<device-setup-repo>).

---

## Conventions

- `just` everywhere — `just --list` in any repo.
- Docs ship with the change, not after. From `infra/README.md`: *"once the docs lag, they stop being trustworthy."*
- Secrets in Bitwarden under `oviicare-*`. Nothing sensitive in git.
- Production mirror in staging — same compose file, same image, different env.
