In DevOps, various protocols and ports play a critical role in networking, automation, CI/CD, monitoring, and security.

Networking & Communication:
SSH (port 22) is essential for remote server access and automation, commonly used with tools like
Ansible and Git for CI/CD pipelines. HTTP (port 80) and HTTPS (port 443) handle web communication 
and API interactions, while DNS (port 53) resolves domain names. For file transfers, FTP (port 21)
is sometimes used, but SFTP (port 22) is preferred for security.

CI/CD & Version Control:
Git repositories can be accessed over SSH (port 22) or HTTPS (port 443). Jenkins, a widely used 
CI/CD tool, typically runs on port 8080. Docker registries use port 5000 for storing and retrieving
container images.

Configuration Management & Automation:
Ansible operates over SSH (port 22) since it is agentless. SaltStack uses ports 4505 and 4506 
for master-to-minion communication. Puppet agents connect to their master via port 8140, while Chef
Server uses port 443 for secure API interactions.

Containerization & Orchestration:
Docker Daemon API listens on port 2375 for unsecure connections and 2376 for secure ones. 
Kubernetes API Server runs on port 6443 to manage the cluster, while Kubelet API uses port 10250
for node communication. etcd, the key-value store for Kubernetes, operates on ports 2379 and 2380.
Kubernetes Dashboard, when exposed via NodePort, typically runs on ports ranging from 30000 to 32767.

Monitoring & Logging:
Prometheus, a popular monitoring tool, collects metrics on port 9090. Grafana, used for
data visualization, operates on port 3000. The ELK stack (Elasticsearch, Logstash, and Kibana)
involves Elasticsearch on port 9200 and Kibana on port 5601. Fluentd, for log aggregation, runs on port 24224.

Cloud & API Services:
AWS, Google Cloud, and Azure APIs primarily communicate over port 443. This ensures secure interactions
between DevOps tools and cloud services.

Security & Authentication:
LDAP (port 389) is used for directory services authentication, while LDAPS (port 636) provides a 
secure alternative. Kerberos authentication relies on port 88, and OpenVPN runs on port 1194 for secure remote access.
