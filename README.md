<p align="center">
<img alt="businessBot logo" src="https://i.imgur.com/P9NI00w.png" height="160" />

<h3 align="center">businessBot</h3>
</p>

---

[![GoDoc](https://godoc.org/github.com/target/businessBot?status.svg)](https://godoc.org/github.com/target/businessBot)
[![Build Status](https://github.com/target/businessBot/workflows/release/badge.svg)](https://github.com/target/businessBot/workflows/release)
[![GitHub release](https://img.shields.io/github/release/target/businessBot.svg)](https://github.com/target/businessBot/releases/latest)
[![Coverage Status](https://coveralls.io/repos/target/businessBot/badge.svg)](https://coveralls.io/r/target/businessBot)
[![Go Report Card](https://goreportcard.com/badge/github.com/target/businessBot)](https://goreportcard.com/report/github.com/target/businessBot)

businessBot is a chatbot framework written in Go. But there's a catch, you don't need to know a lick of Go! Configure your bot via YAML files, extend functionality by writing scripts in your favorite language.

The philosophy behind businessBot is to create very simple, lightweight, "dumb" bots that interact with APIs and scripts which house a bot's business logic. The word **flott** comes from the German word meaning _quick_/_speedy_.



## Installation

### Using go

```sh
go get -u github.com/target/businessBot/cmd/businessBot
```

### Binaries

Binaries for Linux, macOS, and Windows are available as [Github Releases](https://github.com/target/businessBot/releases/latest).

## Helm Chart

To install using the [Helm](https://helm.sh/) chart located in this repo, clone this repo, create [Kubernetes secrets](https://kubernetes.io/docs/concepts/configuration/secret/) for your Slack Token and Slack App Token in your namespace & install the chart:

```sh
helm install helm/businessBot/
```


✔ = Done 🚧 = in progress (functional but some features may not work)


