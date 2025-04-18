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
