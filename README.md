# zammad-docker-compose

1. We use Jenkins for deployment, because this system works very well with docker files, with artifacts where you can keep docker images.
2. We use PostgreSQL as a database because it works better with indexes than MySQL.
3. But in general, you can use kubernetes for this whole solution, there will be accessibility, autoscalliabillity, backup, and deployment tool Argo CD, and all problems can    be solved at the accessibility level.
4. Monitoring system is Prometheus and Grafana.
