# Ansible-Prometheus
Use Ansible to set up system monitoring with Prometheus

## Notes
- Check location of execstart and config file
- config file is YML file from the Prometheus unzipped folder

> First way to run the service: Add the service file in `cd /etc/systemd/system/prometheus.service` 
```sh
sudo service prometheus status
sudo service prometheus start
sudo service prometheus status
sudo service prometheus stop
```

> Second way to run the service: Navigate to the Folder and run `./prometheus`

> Loading Prometheus online: <public-ip>:9090
