<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets.datakit.cloud/identity/logo-color-on-blue.svg">
    <img alt="DataKit Logo" src="https://assets.datakit.cloud/identity/logo-color.svg" height="30" />
  </picture>
</p>
<p align="center">Open-source & cloud-agnostic data activation tools.</p>

---

This is DataKit's public .github repository.  A special public repository for GitHub-specific configuration.

## Actions

GitHub Actions for automating common tasks in DataKit repositories.

- [Setup](./setup): An action to setup Task, SOPS, ArgoCD, and other tools for use in GitHub Actions.
- [Setup Monorepo](./setup-monorepo): An action to clone down the DataKit Monorepo and the specified repositories with sparse-checkout.
- [Deploy](./deploy): An action to deploy an app to production using ArgoCD. It also updates the Kustomize patch for the app in the `dtkt-infra` repository.
