# xflops

XFLOPS is an open source community dedicated to helping enterprises build AI applications. We provide tools, frameworks, and best practices—including [Flame](https://github.com/xflops/flame), a distributed engine delivering secure, cost-effective, and high-performance infrastructure for AI workloads.

## Key Features

- **Elastic** — Scale workloads dynamically based on demand with auto-scaling capabilities and resource optimization.
- **Security** — Session-based authentication and authorization for secure access to elastic workloads running in microVMs.
- **Cost Effective** — Advanced scheduling algorithms that optimize resource utilization and workload distribution.
- **Heterogeneous** — Support for various hardware configurations including GPUs, TPUs, and specialized accelerators.
- **High Performance** — Optimized for maximum throughput, ensuring elastic workloads run at peak efficiency.
- **Cloud Native** — Designed with Cloud Native architecture, deployable on any cloud platform or on-premise.

## Flame

Flame is our flagship distributed engine for elastic workloads, providing a comprehensive suite of mechanisms commonly required by various classes of elastic workloads, including AI/ML, HPC, Big Data, and more.

### Capabilities

- **Scale** — Workloads scale across multiple nodes to maximize performance while ensuring fair resource sharing across tenants and sessions.
- **Performance** — Cutting-edge features improve roundtrip times and throughput in large-scale environments, with intelligent runtime sharing to minimize startup time.
- **Security** — MicroVM runtime with session-dedicated executors prevents data leakage; all components communicate using mTLS.
- **Flexibility** — General APIs support multiple scenarios across Rust, Go, and Python via gRPC.

