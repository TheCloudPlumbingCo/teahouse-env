# teahouse-env

Local dependencies (MySQL, ToxiProxy, Prometheus, Grafana, Loki, Tempo, MailDev) via `docker compose up`, plus the Makefile for error and latency simulation. The services themselves run from their own repos.

Part of the teahouse demo split across repos in TheCloudPlumbingCo. Research and planning for work on this repo happen in [teahouse-workspace](https://github.com/TheCloudPlumbingCo/teahouse-workspace).

> Split from a single-repo Gradle project. The build has not been verified yet; cross-repo dependencies are resolved from GitHub Packages.
