markdown# Enterprise Infrastructure Subnet Allocation Matrix

| Device Name | Interface | Assigned IP Address | Subnet Mask | Role / Connection |
| :--- | :--- | :--- | :--- | :--- |
| **DC_FW** | port4 | 10.10.0.1 | 255.255.255.0 | LAN Gateway Edge |
| **DC_SW** | Gi0/0 | 10.10.0.2 | 255.255.255.0 | Core Switching Uplink |
| **DC_WEB** | e0 | 10.10.0.10 | 255.255.255.0 | Production Web Server |
| **DC_APP** | e0 | 10.10.0.11 | 255.255.255.0 | Enterprise Application Tiers |
| **DC_DB** | eth0 | 10.10.0.12 | 255.255.255.0 | Relational Production Database |
| **DC_DNS** | e0 | 10.10.20.10 | 255.255.255.0 | Internal Service DNS Core |
| **PUB_DNS**| e0 | 8.8.8.8 | 255.255.255.252 | Public Infrastructure Resolver |
