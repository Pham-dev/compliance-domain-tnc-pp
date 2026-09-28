# SMS Opt-In Compliance Pages

A small GitHub Pages site hosting the SMS opt-in consent flow and its supporting
policy documents for A2P 10DLC campaign registration.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | SMS opt-in confirmation page (consent capture UI) |
| `privacy-policy.md` | Privacy policy, including the SMS opt-in data exemption |
| `terms-of-service.md` | Terms of service, including the SMS opt-in data exemption |
| `_config.yml` | Jekyll config (Cayman theme for the Markdown pages) |

## Published site

Once GitHub Pages is enabled (**Settings → Pages → Deploy from a branch → `main` / root**),
the pages are available at:

- `/` — SMS opt-in confirmation
- `/privacy-policy` — Privacy Policy
- `/terms-of-service` — Terms of Service

## Local preview

```bash
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Notes

- Placeholder contact addresses (`privacy@example.com`, `legal@example.com`) should
  be replaced with real contacts before the site is used for a live registration.
- The opt-in form in `index.html` is front-end only; it does not transmit or store
  any submitted data.
