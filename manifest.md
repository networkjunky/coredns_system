Manifest for this project:

coredns version 1.7.0 via Docker 18.06.02 (Photon) and Docker 19.03.12 (Ubuntu 20.04.01 LTS)
Containers will run on a combination of photon OS and Ubuntu.  
-Photon for it's lightweight and preconfigured security aspects.  
-Ubuntu for the monitoring stack including prometheus, reddis, and grafana
Containers:
- codedns/coredns
- grafana/grafana
- redis
- gcr.io/google-containers/cadvisor
- Prometheus is on Ubuntu, could sample as container as well.
Linux Images:
-Ubuntu 20.04.01 LTS
-photon-hw11-3.0-0a85037c - OVA
Environment Overview:
-Linux varients on top of VSphere 6.7
-pfSense-CE-2.4.5-RELEASE-p1-amd64 on VSphere 6.7 as gateway.