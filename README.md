<div align="center">
  <h2>Hello, I'm Enes.</h2>
  <p><b>MLOps & Backend Engineer</b></p>
  <p>Designing scalable, cloud-native inference architectures and robust CI/CD pipelines.</p>
</div>

---

### Engineering Philosophy
I specialize in transforming experimental models into highly available, production-ready microservices. Beyond just making things work, I focus on **how** they work:
* **Architectural Resilience:** Designing systems that fail gracefully, managing data congestion through strategic Redis TTL implementations and event-driven routing via Redpanda.
* **Algorithmic Efficiency:** Prioritizing optimal data structures and algorithmic approaches to ensure low-latency inference at scale.
* **Code Quality & Standards:** Enforcing strict linting (e.g., Ruff) and maintaining clean, traceable version control using Conventional Commits.

---

### Featured Projects

#### 1. End-to-End Fashion AI Recommender (H&M Project)
Architected a decoupled, high-throughput recommendation engine utilizing a vector database and an asynchronous caching layer.
* **The Architecture:** Orchestrated a highly available Kubernetes environment (Helm & ArgoCD). Integrated Qdrant for millisecond-latency semantic search.
* **Performance Engineering:** Slashed inference latency to <2ms and sustained 805 RPS with a 0% error rate. Implemented an asynchronous Redis caching layer with strategic TTL policies to prevent memory congestion under heavy load.
* **Cloud-Native Optimization:** Achieved a ~75% reduction in footprint by provisioning AWS S3 storage via Terraform for dynamic lazy-loading (Boto3) and optimizing deployment via INT8 Dynamic Quantization (ONNX). Reduced image sizes by 54% using multi-stage builds.

#### 2. Cloud-Native Inference Engine (NYC Taxi Project)
Redesigned a monolithic ML deployment into a decoupled, secure, and resource-efficient microservice architecture on AWS.
* **Latency & Resource Optimization:** Migrated to ONNX Runtime and integrated Redis, driving an 85x latency reduction (~281ms to ~3ms). Engineered a resource-efficient Random Forest model (97% size reduction), resolving critical Kubernetes OOM errors.
* **DevSecOps & Reliability:** Established a zero-trust AWS EC2 architecture via custom Security Groups. Enforced automated vulnerability scanning (Trivy) and reduced production Docker image sizes by 68%. Validated system robustness via Locust stress testing under 1000 concurrent connections.

---

### Tech Stack

<div align="left">

**Languages & Code Quality**
<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />

**MLOps, Cloud & Infrastructure**
<br>
<img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argocd&logoColor=white" />
<img src="https://img.shields.io/badge/Helm-0F163F?style=for-the-badge&logo=helm&logoColor=white" />
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />

**Data, Streaming & Databases**
<br>
<img src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-d50000?style=for-the-badge&logo=qdrant&logoColor=white" />
<img src="https://img.shields.io/badge/Postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Apache%20Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/Redpanda-000000?style=for-the-badge&logo=redpanda&logoColor=white" />

</div>

---

### Let's Connect
[LinkedIn](https://www.linkedin.com/in/enes-g%C3%BCler-8ab8a7346)
