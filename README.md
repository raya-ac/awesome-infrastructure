# Awesome Infrastructure [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of infrastructure, monitoring, and DevOps resources

Inspired by [awesome](https://github.com/sindresorhus/awesome) lists. This is a collection of tools, resources, and learning materials for building and operating infrastructure at scale.

## Contents

- [Monitoring & Observability](#monitoring--observability)
- [Databases](#databases)
- [Networking](#networking)
- [Security](#security)
- [Containers & Orchestration](#containers--orchestration)
- [CI/CD](#cicd)
- [Infrastructure as Code](#infrastructure-as-code)
- [Self-Hosted](#self-hosted)
- [Learning Resources](#learning-resources)
- [Blogs & Newsletters](#blogs--newsletters)

## Monitoring & Observability

### Time-Series Databases
- [Prometheus](https://prometheus.io/) - The gold standard for metrics
- [InfluxDB](https://www.influxdata.com/) - Great for high-cardinality data
- [TimescaleDB](https://www.timescale.com/) - PostgreSQL extension for time-series
- [VictoriaMetrics](https://victoriametrics.com/) - High-performance, cost-effective

### Visualization
- [Grafana](https://grafana.com/) - Best-in-class dashboards
- [SigNoz](https://signoz.io/) - Open-source APM
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Self-hosted status page

### Logging
- [Loki](https://grafana.com/oss/loki/) - Log aggregation by Grafana
- [ELK Stack](https://www.elastic.co/elastic-stack) - Elasticsearch, Logstash, Kibana
- [Vector](https://vector.dev/) - High-performance log router

## Databases

### Relational
- [PostgreSQL](https://www.postgresql.org/) - The only database you need
- [CockroachDB](https://www.cockroachlabs.com/) - Distributed SQL
- [TiDB](https://pingcap.com/) - Cloud-native distributed database

### NoSQL
- [Redis](https://redis.io/) - In-memory data store
- [MongoDB](https://www.mongodb.com/) - Document database
- [ScyllaDB](https://www.scylladb.com/) - Cassandra-compatible, faster

### Search
- [Elasticsearch](https://www.elastic.co/) - Distributed search and analytics
- [Meilisearch](https://www.meilisearch.com/) - Lightning-fast search
- [Typesense](https://typesense.org/) - Open-source alternative to Algolia

## Networking

### VPN/Mesh
- [Tailscale](https://tailscale.com/) - Zero-config VPN
- [Netmaker](https://www.netmaker.io/) - Self-hosted Tailscale alternative
- [Headscale](https://github.com/juanfont/headscale) - Open-source Tailscale control server
- [ZeroTier](https://www.zerotier.com/) - Virtual network everywhere

### DNS
- [CoreDNS](https://coredns.io/) - DNS server with plugins
- [Pi-hole](https://pi-hole.net/) - Network-wide ad blocking
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - Alternative to Pi-hole

### Load Balancing
- [HAProxy](http://www.haproxy.org/) - High-performance TCP/HTTP load balancer
- [Traefik](https://traefik.io/) - Cloud-native edge router
- [Caddy](https://caddyserver.com/) - Easy HTTPS with automatic certs

## Security

### WAF/Protection
- [ModSecurity](https://modsecurity.org/) - Web application firewall
- [CrowdSec](https://www.crowdsec.net/) - Collaborative intrusion prevention
- [Fail2ban](https://www.fail2ban.org/) - Ban IPs with too many failed attempts

### Secrets Management
- [Vault](https://www.vaultproject.io/) - Manage secrets and protect sensitive data
- [SOPS](https://github.com/mozilla/sops) - Secrets encryption
- [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) - Kubernetes secrets

### Certificate Management
- [Certbot](https://certbot.eff.org/) - Let's Encrypt client
- [acme.sh](https://github.com/acmesh-official/acme.sh) - Pure shell ACME client
- [Lego](https://github.com/go-acme/lego) - Let's Encrypt client in Go

## Containers & Orchestration

### Kubernetes
- [k3s](https://k3s.io/) - Lightweight Kubernetes
- [k0s](https://k0sproject.io/) - Zero-friction Kubernetes
- [MicroK8s](https://microk8s.io/) - Small, fast, single-package Kubernetes

### Container Tools
- [Podman](https://podman.io/) - Daemonless container engine
- [Buildah](https://buildah.io/) - Build OCI containers
- [skopeo](https://github.com/containers/skopeo) - Work with remote container registries

### Alternatives to Kubernetes
- [Nomad](https://www.nomadproject.io/) - Simple workload orchestrator
- [Dokku](https://dokku.com/) - Docker-powered PaaS
- [Fly.io](https://fly.io/) - Platform for running full-stack apps

## CI/CD

### Self-Hosted Runners
- [Gitea Actions](https://docs.gitea.com/usage/actions/overview) - CI/CD in Gitea
- [Woodpecker CI](https://woodpecker-ci.org/) - Simple CI engine
- [Drone](https://www.drone.io/) - Container-native CI/CD
- [Concourse](https://concourse-ci.org/) - Pipeline-based CI

### GitOps
- [ArgoCD](https://argo-cd.readthedocs.io/) - Declarative GitOps for Kubernetes
- [Flux](https://fluxcd.io/) - GitOps operator for Kubernetes

## Infrastructure as Code

### Configuration Management
- [Ansible](https://www.ansible.com/) - Simple automation
- [SaltStack](https://saltproject.io/) - Event-driven automation
- [Puppet](https://puppet.com/) - Model-driven configuration

### Provisioning
- [Terraform](https://www.terraform.io/) - Infrastructure as code
- [Pulumi](https://www.pulumi.com/) - Infrastructure as code in real languages
- [OpenTofu](https://opentofu.org/) - Open-source Terraform fork

## Self-Hosted

### Essential Tools
- [Nextcloud](https://nextcloud.com/) - Self-hosted cloud
- [Jellyfin](https://jellyfin.org/) - Media server
- [Immich](https://immich.app/) - Photo and video backup
- [Paperless-ngx](https://docs.paperless-ngx.com/) - Document management

### Monitoring Stack
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Status page
- [Beszel](https://github.com/henrygd/beszel) - Server monitoring
- [Netdata](https://www.netdata.cloud/) - Real-time monitoring

## Learning Resources

### Books
- *Site Reliability Engineering* - Google
- *The Phoenix Project* - Kim, Behr, Spafford
- *Designing Data-Intensive Applications* - Martin Kleppmann
- *Cloud Native DevOps with Kubernetes* - John Arundel

### Courses
- [Google SRE Book](https://sre.google/sre-book/table-of-contents/) (Free)
- [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/) (Free)
- [Linux Foundation Courses](https://www.linuxfoundation.org/training)

### Labs/Practice
- [Killer Shell](https://killercoda.com/) - Hands-on Kubernetes
- [Play with Docker](https://labs.play-with-docker.com/) - Free Docker sandbox
- [Katacoda](https://www.katacoda.com/) - Interactive learning

## Blogs & Newsletters

- [High Scalability](http://highscalability.com/) - Large system architectures
- [Martin Fowler](https://martinfowler.com/) - Software architecture
- [The Morning Paper](https://blog.acolyer.org/) - CS paper summaries
- [Last Week in AWS](https://www.lastweekinaws.com/) - AWS news with commentary
- [Google Cloud Blog](https://cloud.google.com/blog) - GCP updates
- [Cloudflare Blog](https://blog.cloudflare.com/) - Edge networking deep-dives

## Contributing

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[CC0 1.0](LICENSE)