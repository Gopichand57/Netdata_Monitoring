![Screenshot 2025-04-18 220822](https://github.com/user-attachments/assets/d2b7e352-733b-4498-a6d4-ffe019dc0a47)
# TASK 7: Monitor System Resources Using Netdata

# Objective
Install Netdata and visualize system and app performance metrics in real time.

# Tools Used
- Netdata (Docker image)
- Docker
- AWS EC2 (Ubuntu)

# Steps Performed

1. Launched an EC2 Ubuntu instance.
2. Installed Docker and pulled Netdata image:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
