Prometheus IPMI Exporter
===


Requirements
---

1. Python (tested with 2.7)
2. Python [prometheus_client](https://github.com/prometheus/client_python) module
4. `freeipmi` packet


As a command
---

```
export TARGET_IPS=192.168.0.1,192.168.0.2
export IPMI_USER='...'
export IPMI_PASSWD='...'
python ipmi_exporter.py
```

