 Monitor System Resources Using Netdata

## What I Did
- Installed Docker and ran **Netdata** in a container:
  ```bash
  docker run -d --name=netdata -p 19999:19999 --restart unless-stopped netdata/netdata
Opened the dashboard at http://<public-ip>:19999.

Monitored CPU, Memory, Disk I/O, Network, and Docker container metrics.

Checked the Alerts/Alarms panel.

Captured screenshots as proof.

Nodes:
<img width="1910" height="1021" alt="Screenshot 2025-08-14 170454" src="https://github.com/user-attachments/assets/1eafc434-c292-4e84-8c57-b9b201cf0ae1" />


Dashboard:
<img width="1912" height="963" alt="Screenshot 2025-08-14 170912" src="https://github.com/user-attachments/assets/7ae4b113-00c2-4635-83b4-4c8d06bce5b7" />


Commands:
<img width="1913" height="986" alt="Screenshot 2025-08-14 171316" src="https://github.com/user-attachments/assets/861a4f70-b428-4a9f-9179-d383ec14f5e2" />


CPU:
<img width="1919" height="1030" alt="Screenshot 2025-08-14 171340" src="https://github.com/user-attachments/assets/91e99c3f-086e-4c0c-9032-491adb62f053" />


MEMORY:
<img width="1919" height="1026" alt="Screenshot 2025-08-14 171415" src="https://github.com/user-attachments/assets/61e33851-e3d9-430f-8911-ecb4062ad6c0" />


DISK:
<img width="1919" height="1028" alt="Screenshot 2025-08-14 171431" src="https://github.com/user-attachments/assets/5d8e2985-a975-4f64-a4e0-f838d3f827ad" />


UPTIME:
<img width="1919" height="1026" alt="Screenshot 2025-08-14 171509" src="https://github.com/user-attachments/assets/a58d1fb7-65c8-4eaa-8777-717fa3ec91e8" />


TRAFFIC:
<img width="1919" height="1023" alt="Screenshot 2025-08-14 171548" src="https://github.com/user-attachments/assets/0a752ea1-7803-4ca8-80ed-98b1e64767f0" />


METRICS MEMORY:
<img width="1919" height="1027" alt="Screenshot 2025-08-14 171702" src="https://github.com/user-attachments/assets/5e7c7bad-dbba-4264-b737-37822dcd7f40" />

