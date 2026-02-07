**# Linux**
*Linux Interview Questions*
Linux Interview Questions.pdf

```bash
sudo apt update
sudo apt install prometheus
```
`prometheus.yml`

### Bullet list
```md
- Prometheus
- Grafana
- Node Exporter


[Prometheus Docs](https://prometheus.io)

![Architecture Diagram](images/architecture.png)


<details>
<summary>Click to expand</summary>

```bash
systemctl status prometheus


| Component | Port | Purpose |
|--------|------|--------|
| Prometheus | 9090 | Metrics |
| Grafana | 3000 | Dashboards |


## 📋 Lists


# Grafana + Prometheus Monitoring Lab

## 📌 Overview
This lab demonstrates how to monitor a Linux server using Prometheus and Grafana.

## 🏗 Architecture
- Prometheus
- Grafana
- Node Exporter

## 🔧 Prerequisites
- Ubuntu 22.04
- Internet access

## 🚀 Installation Steps

### 1️⃣ Install Node Exporter
```bash
wget https://github.com/prometheus/node_exporter/releases/latest/download/node_exporter-linux-amd64.tar.gz

