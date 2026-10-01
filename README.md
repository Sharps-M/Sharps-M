# Milton Maurenzi

**Full Stack Developer** · Argentina · 6+ years building and running production software

I design, build and operate web platforms end to end: data model, backend, front-end, deployment and the documentation that keeps them maintainable. For the last four years I have been the sole hands-on developer across several national government platforms, which means owning every layer and every production incident.

## What I work with

| Area | Technologies |
|------|--------------|
| Backend | PHP (Laravel 10–12, Filament), Node.js (Express), Go |
| Frontend | React, TypeScript, JavaScript, Bootstrap, Tailwind |
| Mobile | React Native |
| Data | MariaDB, MySQL, Redis |
| Infrastructure | Docker, Nginx, Apache, GitHub Actions |
| Testing | PHPUnit, Pest, Vitest |

## Featured projects

### [Modulith — Laravel Modular Monolith Starter](https://github.com/Sharps-M/laravel-modular-monolith-starter)

The generic core extracted from the internal management platforms I maintain. Each domain is a self-contained module with explicit layers (Domain, Application, Infrastructure, UI) loaded by convention.

- Layer boundaries enforced by an architecture test that fails the build
- Role-based access control with guards against privilege escalation
- Hardened authentication, audit trail, light and dark themes
- Docker environment and CI: code style, tests on PHP 8.3/8.4, asset and image builds

`PHP` `Laravel 12` `Docker` `PHPUnit` `GitHub Actions`

### [SafeSocialVoid](https://github.com/Sharps-M/safe-social-void)

A private, local filter that hides specific people from your view in group chats, without leaving the group and without anyone knowing. Cross-browser extension (Manifest V3) built with a hexagonal architecture: a pure domain core, with browser storage and each chat platform behind ports and adapters.

`TypeScript` `WXT` `Hexagonal architecture` `Vitest`

## How I work

- **Architecture first.** Clear module boundaries and documented decisions, so the next change is cheap.
- **Production ownership.** I have built background job pipelines for large exports (50,000+ records with chunking and live progress), and integrations with government identity-verification and banking payment systems.
- **AI-assisted engineering, with rules.** I use AI tools daily under written guidelines: atomic steps, verify against the real system, never invent. The rules are in each repository.

## Contact

Open to full stack and backend roles, remote or hybrid.

- Email: [milton.maurenzi@gmail.com](mailto:milton.maurenzi@gmail.com)
