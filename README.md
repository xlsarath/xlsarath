### Sarath Makkena

Staff Software Engineer at [Personalis](https://www.personalis.com) (cancer genomics). I build ML platforms and LLM infrastructure, and the distributed systems they run on. *Learn deeply, build with care.*

**Recent impact**

- **Document AI:** LoRA fine-tuning of a vision-language model inside a private VPC lifted held-out field accuracy from 86% to 94% with fewer invented values. Insurance cards, order forms and pathology reports parse end to end in ~37 s, with page evidence for every field.
- **LLM platform:** PHI-safe vLLM serving on Kubernetes GPUs behind an OpenAI-compatible gateway, with encrypted weights, audit trails, scale-to-zero GPUs, an adapter registry with lineage and ~35 s rollback with zero failed requests.
- **Platform at scale:** technical lead for a clinical ordering, billing and reporting platform through 3× order growth in a year; top contributor to its core services (~3,300 commits across 20 repositories).
- **Distributed systems:** Kafka / Amazon MSK pipelines, change data capture, transactional outboxes, idempotent consumers with dead-letter replay, and a versioned state machine for clinical report release.
- **Observability:** Prometheus, Grafana, Loki, PromQL/LogQL alerting and Kafka consumer-lag monitoring.
- **Healthcare interoperability:** HL7 v2, FHIR, health-information exchange, OAuth 2.0 / OIDC, audit trails.

**Stack:** Java 25 · Spring Boot · Python · React · Kafka · PostgreSQL · OpenSearch · vLLM · LiteLLM · PyTorch / PEFT · AWS (EKS GPU, S3, KMS) · Kubernetes

Most of my production work lives in private, regulated codebases. The public repos below are smaller projects that show the same ideas.

| Project | What it shows |
|---|---|
| [lightweight-fine-tuning](https://github.com/xlsarath/lightweight-fine-tuning) | LoRA/QLoRA on GPT-2 for news classification: 62.5% zero-shot → 89.4% accuracy while training 0.24% of the weights |
| [STEDI-Application-kafka-spark-Redis-](https://github.com/xlsarath/STEDI-Application-kafka-spark-Redis-) | Real-time analytics pipeline: Kafka, Spark Structured Streaming and Redis |
| [ChicagoTransitAuthority-Kafka](https://github.com/xlsarath/ChicagoTransitAuthority-Kafka) | Transit-event streaming with Kafka producers, Kafka Connect, REST Proxy, KSQL and Faust |

**Publications:** [Enhanced Predictive Modeling of Cricket Game Duration Using Multiple Machine Learning Algorithms](https://ieeexplore.ieee.org/document/9310081), IEEE ICDSE 2020

[LinkedIn](https://www.linkedin.com/in/sarathmakkena/) · xlsarathchandra@gmail.com
