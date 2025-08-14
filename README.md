 Monitor System Resources Using Netdata

## What I Did
- Installed Docker and ran **Netdata** in a container:
  ```bash
  docker run -d --name=netdata -p 19999:19999 --restart unless-stopped netdata/netdata
Opened the dashboard at http://<public-ip>:19999.

Monitored CPU, Memory, Disk I/O, Network, and Docker container metrics.

Checked the Alerts/Alarms panel.

Captured screenshots as proof.
