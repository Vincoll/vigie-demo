# Public demonstration of Vigie

This public demonstration aims to show the functionalities of Vigie in real use.

## What's Vigie ?

**Vigie is in alpha stage, still under heavy development.**

Vigie is a cross platform application service monitoring tool based on assertions. You will be able to monitor many types of services and to confront them with an expected result. If one of your assertion returns an error, an alert system will warn you.

Vigie is written in Go and design to be lightweight and with simplicity of use in mind. The application aims to respect the [Twelve-Factors App](https://12factor.net/) standard.

This tool can be use as standalone or can rely on components that enhance its monitoring capability with metrics, state history, dashboards and advanced alertings mechanisms.

**Vigie is in alpha stage, still under heavy development.**

# Vigie Demo

**This Demo showcase a full deployement of Vigie.**

* Vigie Instance
* Metrics: [Prometheus (Time Series Database)](https://prometheus.io/)
* Dashboard: [Grafana](https://grafana.com/)
* Alerting: No demo yet

## Conditions of the Demo

* This public demonstration aims to show the functionalities of Vigie in real use.
  * As the application evolve more application services will be added.
* Vigie Configuration and Tests are in this git repo.
* For the purpose of the demo every endpoints of the app is exposed.
* Read Only

## Exposed Services

**Vigie Instance**

* ☑ Web API (Alpha)
* ☑ Prometheus Exporter (Beta)

**Vigie's Probes - Application Services**

* ☑ Debug Probe
* ☐ HTTP
* ☐ DNS
* ☐ Hash
* ☐ Ping
* ...

**Grafana**

* ☑ Vigie Front dashboard (Stable)

## Exposed URLS

* **Vigie Instance - WebAPI:** Details results of ours Tests.
  * [Vigie Webapi](https://webapi.vigie.vincoll.io/testsuites)
* **Vigie Instance - Prometheus Exporter:** Presents test metrics pull by Prometheus
  * [Vigie Prometheus Exporter](https://promexporter.vigie.vincoll.io/metrics)
* **Prometheus:** Prometheus pull and store the metrics inside his Time Series Database.
  * [Vigie Prometheus](https://prometheus.vigie.vincoll.io)
* **Grafana:** Displays dashboards aggregating the prometheus metrics for humans.
  * [Vigie Grafana Dashboard](https://grafana.vigie.vincoll.io)
  * _User/Pass:_ demo:demo

# About Vigie (ﾉ◕ヮ◕)ﾉ*:・ﾟ✧

Vigie is written in Go by [Vincent Collard](https://vincoll.io) as a side project.

Vigie source code will be available when ready: [https://github.com/Vincoll/vigie](https://github.com/Vincoll/vigie)
