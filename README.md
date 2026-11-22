# Engineers Co

A job platform where engineers find work and employers find engineers. It covers civil, electrical, mechanical, software and related disciplines, and is built for Kenya and the wider African market.

Engineers build a profile with their discipline, registration number, certifications and software skills, then search and apply for roles. Employers are verified before they can post, then manage applicants in one place.

## Tech stack

### Frontend

| Layer | Choice |
|---|---|
| Rendering | Jinja2 templates (server-rendered) |
| Interactivity | HTMX and Alpine.js |
| Styling | Tailwind CSS |
| Forms | Flask-WTF |
| Assets | Self-hosted fonts, inline SVG icons, WebP/AVIF images |
| Testing | Playwright, axe, Lighthouse CI |

### Backend

| Layer | Choice |
|---|---|
| Language | Python 3.12 |
| Framework | Flask 3 with Blueprints (modular monolith) |
| Database | PostgreSQL 16, with SQLAlchemy 2 and Alembic |
| Cache and queues | Redis |
| Background jobs | Celery and Celery Beat |
| Search | PostgreSQL full-text search and pg_trgm (OpenSearch later) |
| File storage | S3-compatible object storage |
| Auth | Flask-Login, JWT for the API, Google and LinkedIn OAuth2 |
| Payments | M-Pesa (Daraja) and Stripe |
| Email, SMS | Brevo, SES or SendGrid; Africa's Talking |
| Serving | Gunicorn behind Nginx, Cloudflare in front |
| Infrastructure | Docker, GitHub Actions |
| Monitoring | Sentry, Prometheus and Grafana |

## Documentation

- [Frontend Tech Stack](Frontend%20Tech%20Stack%20-%20Engineers%20Job%20Platform.docx)
- [Backend Tech Stack](Backend%20Tech%20Stack%20-%20Engineers%20Job%20Platform.docx)

## Status

Planning and design. No application code yet.
