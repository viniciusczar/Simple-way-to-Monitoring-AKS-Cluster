Hi!

That's a simple way to build you Grafana+Prometheus+Loki+Promptail. I'm not here to explain one by one, however, follow the numbers to do your Monitore System with them in Kubernetes Cluster.

OBS: 
    - I supposed you're using a AKS cluster from Azure with Storage Account and Share Files created before.
    - I'm using a namespace name "monitoring".
    - Whether you change some parameter, guarantee you change where they are filled.
    - That're a bunch of ways to do your Grafana with tools (prometheus, loki, etc), but, this is a simple way what i used to contribute for community.