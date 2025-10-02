# Task 7: Monitor System Resources Using Netdata

## 📌 Objective

The goal of this task is to install **Netdata** and visualize system & application performance metrics in real-time.

---

## 🔧 Tools Used

* **Netdata** (lightweight monitoring tool)
* **Docker**

---

## 🚀 Steps Performed

1. Pulled and ran the Netdata container using Docker:

   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
   ```
2. Accessed the Netdata dashboard at:
   👉 [http://localhost:19999](http://localhost:19999)
3. Monitored real-time metrics like:

   * CPU usage
   * Memory utilization
   * Disk usage
   * Docker containers

---

## 📸 Screenshot

Below is the screenshot of the running Netdata dashboard:

![Netdata Dashboard](Screenshot.png)

---

## 📚 Outcome

* Successfully deployed and used **Netdata** for system monitoring.
* Gained understanding of dashboards, alerts, and performance KPIs.

