# Upstream source

The application code in `src/` comes from Google's Bank of Anthos sample:

- Repository: https://github.com/GoogleCloudPlatform/bank-of-anthos
- Commit: `db35fea9fd090150e2398106aadb475576f80d94` (2026-09-18)
- License: Apache 2.0 (see `LICENSE`)

## What was imported

Copied unchanged: `src/` (services, Dockerfiles, tests, DB init scripts), root `pom.xml`, Maven wrapper (`mvnw`, `.mvn/`), `.pylintrc`, `LICENSE`.

Left out on purpose. These are upstream deployment assets, which the capstone brief counts as reference material only:

- `kubernetes-manifests/`, `iac/`, `extras/`, `.github/`
- every `k8s/` and `components/` folder, plus `skaffold*.yaml` and `cloudbuild.yaml`
- `src/ledgermonolith/`, a single-service variant we don't deploy

## Changes from upstream

Each change is made in its own reviewed PR and listed here.

| Change | Files | Reason |
|---|---|---|
| _(none yet)_ | | |
