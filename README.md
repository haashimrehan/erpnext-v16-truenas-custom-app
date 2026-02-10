# erpnext-v16-truenas-custom-app

Architecture Overview

- **frontend**  
  NGINX reverse proxy (port 8080 → 30080)

- **backend**  
  ERPNext Python backend

- **queue-short / queue-long**  
  Background workers

- **scheduler**  
  Cron + scheduled tasks

- **websocket**  
  Realtime events (Socket.IO)

- **db**  
  MariaDB 10.6

- **redis-cache / redis-queue**  
  Redis services
