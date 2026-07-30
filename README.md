# 🚀 Prometheus + Grafana Monitoring Project

## 📌 Project Overview

This project demonstrates real-time infrastructure monitoring using Prometheus, Grafana, and Node Exporter on AWS EC2 instances.

Prometheus collects system metrics from Node Exporter, while Grafana visualizes those metrics through interactive dashboards. A stress test script is used to generate CPU load and verify that the monitoring setup works correctly.

---

## 🛠️ Tools & Technologies

- AWS EC2
- Ubuntu Linux
- Prometheus
- Grafana
- Node Exporter
- Git & GitHub
- Bash Shell Script

---

## 📂 Project Structure

```
prometheus-grafana-monitoring-project/
│── README.md
│── LICENSE
│
├── screenshots/
├── scripts/
│   ├── install_node_exporter.sh
│   ├── cpu_stress.sh
│
├── configs/
│   └── prometheus.yml
│
├── docs/
│   ├── architecture.png
│   └── setup-steps.md
│
└── dashboard/
    ├── dashboard-1860.json
    └── dashboard-3662.json
```

---

## ⚙️ Project Workflow

1. Launch AWS EC2 Instance.
2. Install Prometheus.
3. Install Node Exporter.
4. Configure `prometheus.yml`.
5. Verify Prometheus Targets.
6. Install Grafana.
7. Add Prometheus as Data Source.
8. Import Node Exporter Dashboard.
9. Monitor CPU, Memory, Disk, and Network usage.
10. Run `cpu_stress.sh` to generate CPU load.
11. Observe live metrics in Grafana Dashboard.

---

## 📊 Metrics Monitored

- CPU Usage
- Memory Usage
- Disk Usage
- Network Traffic
- System Load
- Uptime

---

## 📸 Screenshots

- EC2 Instance
- Prometheus Targets
- Prometheus UI
- Grafana Login
- Grafana Data Source
- Node Exporter Dashboard
- Stress Test Dashboard

---

## 📈 Result

Successfully configured a complete monitoring solution using Prometheus and Grafana. The dashboard displayed real-time metrics, and CPU stress testing confirmed that monitoring was functioning correctly.

---

## 👩‍💻 Author

**Nayan Kshirsagar**
