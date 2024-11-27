# Changelog

## 0.0.0-8.7.0-alpha2 (2024-11-27)


### ⚠ BREAKING CHANGES

* remove separated ingress functionality and only keep the global combined ingress
* Zeebe, Zeebe Gateway, Operate, and Tasklist have been replaced with Orchestration Core. Also, the Connectors configuration syntax was updated.

### Features

* adding application override to console ([#2594](https://github.com/camunda/camunda-platform-helm/issues/2594)) ([e9d0c48](https://github.com/camunda/camunda-platform-helm/commit/e9d0c4827d5e10a666abacce5d00d94b443418aa))


### Bug Fixes

* adding http/https options to readinessProbes for console ([#2529](https://github.com/camunda/camunda-platform-helm/issues/2529)) ([64a37f6](https://github.com/camunda/camunda-platform-helm/commit/64a37f66227ceb32b67c4f58b729206f6a5c5392))
* assign Zeebe role to demo user ([#2510](https://github.com/camunda/camunda-platform-helm/issues/2510)) ([cd419a3](https://github.com/camunda/camunda-platform-helm/commit/cd419a3da7d3e1859bdbbf742bda554b4fd42eaa))
* **core:** disable core client secret if identity is disabled ([#2584](https://github.com/camunda/camunda-platform-helm/issues/2584)) ([89a1333](https://github.com/camunda/camunda-platform-helm/commit/89a13330b2f71cfe30e3932c7e738d22b9d9711b))
* **deps:** update module github.com/stretchr/testify to v1.10.0 ([#2609](https://github.com/camunda/camunda-platform-helm/issues/2609)) ([90097de](https://github.com/camunda/camunda-platform-helm/commit/90097dea2a6bfa678d405f2aa9ee6165c2cb57c3))


### Refactors

* **core:** add identity admin client ([#2602](https://github.com/camunda/camunda-platform-helm/issues/2602)) ([9acebbe](https://github.com/camunda/camunda-platform-helm/commit/9acebbeb81642664f0dc8b44df30fb009ca72890))
* **core:** rename core statefulset to avoid upgrade downtime ([#2581](https://github.com/camunda/camunda-platform-helm/issues/2581)) ([061b06d](https://github.com/camunda/camunda-platform-helm/commit/061b06d35936bf8995f03a1ea4bec276ecb6a94f))
* remove separated ingress functionality ([#2586](https://github.com/camunda/camunda-platform-helm/issues/2586)) ([3d12988](https://github.com/camunda/camunda-platform-helm/commit/3d12988720594bb6cc160bf246999cba89fecdea))
* remove support for global.multiregion.installationType ([#2588](https://github.com/camunda/camunda-platform-helm/issues/2588)) ([a04f88a](https://github.com/camunda/camunda-platform-helm/commit/a04f88a4073a130f715094d6bca9d5d4b4c419b0))
* replace zeebe and web-apps with camunda orchestration core ([28d7927](https://github.com/camunda/camunda-platform-helm/commit/28d79278105b365a61b51974ce5efb0400d160e0))
