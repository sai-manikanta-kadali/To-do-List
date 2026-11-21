# Software Project Collection

This repository currently contains two separate learning/demo artifacts:

1. **Global Path Study Abroad** — a static, responsive single-page website concept built with HTML, CSS, and JavaScript.
2. **SentinelGuard** — an exploratory endpoint-security and browser anti-phishing prototype located in `sentinel-guard/`.

These are independent projects and should be opened from their respective folders.

## Project 1 — Global Path Study Abroad website

A photo-led static website concept for an international education and career counselling service.

### Technology

- HTML5, CSS3, vanilla JavaScript
- Responsive layouts and client-side interactions
- GSAP animations and ScrollTrigger
- Centralized site configuration in `js/config.js`

### Run locally

From the repository root:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

### Important demo-content disclosure

The website contains fictional sample testimonials, counsellor identities, packages, pricing, schedules, and university listings. University names, photos, logos, and trademarks are placeholders and must not be presented as official partnerships or verified current information. Contact forms simulate submission until connected to a real form endpoint.

## Project 2 — SentinelGuard security prototype

See the dedicated [SentinelGuard README](sentinel-guard/README.md) for architecture, setup, browser-extension installation, and local attack-simulation scenarios.

SentinelGuard explores:
- Browser anti-phishing and suspicious-domain warnings.
- Download inspection and quarantine workflows.
- Remote-access-tool and banking-scam context signals.
- Transaction safety prompts.
- A local control dashboard and attack-simulation lab.

It is an experimental prototype. Do not rely on it as a replacement for antivirus, endpoint detection, browser security, or professional security controls.

## Repository structure

```text
.
├── index.html
├── css/
├── js/
├── assets/
└── sentinel-guard/
    ├── agent/
    ├── browser_extension/
    ├── dashboard/
    ├── demo/
    └── tests/
```

## Scope

This repository is a collection of prototypes and demonstrations, not one integrated production application. Review each subproject's README before running or evaluating it.

---

Documented to make the two contained projects and their prototype status clear.