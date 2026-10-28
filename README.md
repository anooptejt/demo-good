# demo-good

Sample Node web app (an orders dashboard with a small UI) used to demo repository onboarding with ZenseAI AIDLC Centre. This is the **good** app: every release starts and stays healthy.

## Run locally

```bash
npm start        # http://localhost:8080
npm test
```

Endpoints: `/` (UI), `/api/info`, `/healthz`, `/readyz`.

## What is deliberately missing

This repository has no `Dockerfile`, no Kubernetes manifests and no CI workflow. Onboarding through the platform creates and commits those, and the first CI run builds and pushes `quay.io/anoop_thotapalli/demo-good`.

## Releases

- `main` is **v1.0.0**.
- Branch `release/1.1.0` is the next release (a changed banner). Merge it after onboarding to demo a second rollout.
