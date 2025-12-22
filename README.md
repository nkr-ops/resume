# Naveen Kumar Reddy  
**Distributed Systems & Platform Engineer**  
Bengaluru, India · [LinkedIn](https://www.linkedin.com/in/naveenkumarreddyk/) · [GitHub](https://github.com/nkr-ops)

---

## Summary
Engineer operating at organizational scope across **8+ production systems and 6 domains**.
Known for stabilizing failing platforms, building systems adopted org-wide, and resolving
high-impact failures across the stack — from Linux kernel behavior to cloud architecture.
Delivered **$10M+ revenue protection** and **$1M+ cost impact**.

---

## Experience

### Nielsen — Senior Software Engineer (MTS-3)  
*May 2024 – Present*

- Designed async job orchestration platform supporting **1000+ concurrent jobs** with distributed locking and exactly-once semantics; adopted by **8 teams** as default
- Built **National DQC framework** reconciling data across **7 systems** using graph-based lineage and deviation detection; reduced investigations from days to **<1 hour**
- Architected real-time analytics foundation on **Apache Druid** (petabyte-scale ingestion,async routing, high availability)
- Infrastructure design reviewer for platforms used by **6+ teams**; led **3 systems end-to-end** and shared ownership of others; governed **10+ AWS accounts**
- Reduced critical computation from **O(n⁴) → O(1)** (**2+ hours → ~5 minutes, 97%**)
- Achieved **573,562× lookup speedup** by indexing hot paths and eliminating linear scans
- Traced EKS OOMKills to **cgroups v2 memory accounting** during Kubernetes upgrades
- Diagnosed **martian packet drops** from asymmetric routing, rp_filter behavior, and CIDR overlap
- Resolved **NFS D-state deadlocks** caused by hard-mount loopback configurations
- **Protected $10M+ customer contract** by rebuilding **7 corrupted pipelines** and reprocessing **10TiB+ data** under a 28-day deadline
- Led the company’s first formal **AWS Well-Architected Framework** adoption, establishing tagging standards and cost governance patterns
- Led cross-team security reviews under a Zero Trust model; identified and remediated **45 vulnerabilities** (**8 critical**) across production systems
- Prevented nationwide outage via **ACM certificate renewal + Route53/UDNS remediation**
- Delivered **$560K+ annual savings** through autoscaling fixes, ETL redesign, and governance automation
- Reviewed **100+ MRs**, mentored **30+ engineers**, bar-raiser for **18+ interviews**
- Recipient of **Trailblazer Award** (department-level)

---

### Flexcar — Senior Software Engineer  
*Dec 2022 – May 2024*

- Led zero-downtime **monolith → microservices** migration serving 100% production traffic
- Reduced **P95 latency 850ms → 85ms (10×)** and increased throughput **5×**
- Reduced infrastructure costs by ~$10K/year
- Implemented distributed tracing and circuit breakers across **20+ services**

---

### OYO — Backend Engineer  
*Aug 2021 – Nov 2022*

- Built Kafka-based real-time synchronization (<5s latency, millions of daily events)
- Optimized queries **2000ms → 300ms**, eliminating N+1 patterns

---

## Technical Profile
**Systems:** Distributed systems, platform architecture, failure recovery  
**Debugging:** Linux kernel (cgroups, networking), storage, JVM, cloud infrastructure  
**Languages:** Java, Scala, Python, Go, SQL, Bash  
**Infrastructure:** Kubernetes, Terraform, Helm, EKS, EMR, Docker, GitLab CI/CD  
**Data:** Kafka, Spark, Druid, Airflow, Trino, PostgreSQL, Redis  
**Cloud & Observability:** AWS, Prometheus, Grafana, ELK, Datadog
