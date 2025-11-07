# Prometheus & Grafana Monitoring Project

This project demonstrates a **monitoring setup** using **Prometheus** and **Grafana**, where an Ubuntu VM is monitored with **Node Exporter** and visualized through Prometheus and Grafana installed on a RedHat VM.

---

## **Project Overview**

- **Prometheus**: Monitors metrics from Node Exporter.
- **Grafana**: Visualizes system metrics.
- **Node Exporter**: Runs on Ubuntu VM to collect CPU, memory, disk, and network metrics.
- **Ubuntu VM**: Target machine being monitored.
- **RedHat VM**: Hosts Prometheus and Grafana.

---

## **What I Did**

1. **Installed Node Exporter on Ubuntu VM**
   - Downloaded and extracted Node Exporter.
   - Created a dedicated user for Node Exporter.
   - Configured Node Exporter as a systemd service.
   - Started and enabled the service.

2. **Installed Prometheus on RedHat VM**
   - Created Prometheus user and directories.
   - Copied Prometheus binaries and configuration.
   - Created a systemd service for Prometheus.
   - Started and enabled the service.

3. **Configured Grafana on RedHat VM**
   - Installed Grafana.
   - Added Prometheus as a data source.
   - Verified metrics from Ubuntu VM using Node Exporter.

4. **Verified Monitoring**
   - Accessed Grafana dashboard via browser.
   - Observed metrics like CPU, memory, and disk usage from Ubuntu VM.

---

## **Technologies Used**

- Linux (Ubuntu & RedHat)
- Prometheus
- Grafana
- Node Exporter
- Systemd
- Git & GitHub

---

## **Work Flow**

![monitoring](https://github.com/user-attachments/assets/6be7d252-0393-4e80-adc2-32c854ea62e9)

---
![awsvms](https://github.com/user-attachments/assets/42452e29-ff74-4a5c-a99e-3d1cf1122ac3)

---
![grafana2](https://github.com/user-attachments/assets/e460eab1-2869-4a8b-9462-6f82719b7b09)

---
![prometheus](https://github.com/user-attachments/assets/2e8f4c21-8f5d-4e62-9985-8a80d3f7031d)

![node_exporter](https://github.com/user-attachments/assets/3f6f5553-163e-400b-8e7f-946b66990692)

---
