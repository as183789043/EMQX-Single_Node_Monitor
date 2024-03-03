# EMQX-Single_Node_Monitor (Liunx System)

Use docker-compose to quickly deploy single-node EMQX and monitoring systems Prometheus and Grafana

Quick start step by step

* Setting Environment
  ```bash
  git clone [https://github.com/as183789043/Emqx-Single_Node_Monitor.git](https://github.com/as183789043/EMQX-Single_Node_Monitor.git)
  cd EMQX-Single_Node_Monitor
  docker compose up -d
  ```

* Default Username and Password
  ```
  EMQX (port 18083):
    username : admin
    password : public
  
  Grafana (port 3000):
    username : admin
    password : admin
  ```

* Setting EMQX monitor -> Pushgateway
  ```
  http://pushgateway:9091
  ```

* Setting Grafana Datasource -> Prometheus 
  ```
  http://prometheus:9090
  ```

* Import Dashboard
  ```
  Upload the dashboard.json file which in emqx directory 
  ```

![192 168 102 128_3000_d_uAUUbySVze_emqx_orgId=1 refresh=5s from=now-30m to=now](https://github.com/as183789043/Emqx-Single_Node_Monitor/assets/56618553/95132dbb-5b86-4656-9027-b609dda0bca5)
![192 168 102 128_3000_d_uAUUbySVze_emqx_orgId=1 refresh=5s from=now-30m to=now (3)](https://github.com/as183789043/Emqx-Single_Node_Monitor/assets/56618553/b5e3029a-090c-48d8-9646-b0f7dfc384a7)

