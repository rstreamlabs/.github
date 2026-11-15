# rstream

Connect services across private networks through outbound tunnels. rstream combines an edge network with a CLI, application SDKs and browser tools: the agent maintains the connection, and the edge routes traffic and applies access policy.

Published tunnels provide an address for ordinary clients. Private tunnels are reached through an authenticated rstream client. The same model supports local development, backend integrations, device fleets and remote operations.

## Choose an integration

| Component | Best starting point |
| --- | --- |
| [Go SDK and CLI](https://github.com/rstreamlabs/rstream-go) | The reference implementation, broad protocol coverage and command-line workflows. |
| [C++ SDK](https://github.com/rstreamlabs/rstream-cpp) | Native applications that own their Boost.Asio event loop and use callbacks, futures or coroutines. |
| [JavaScript and TypeScript SDKs](https://github.com/rstreamlabs/rstream-js) | Node.js tunnel runtimes, API clients and browser/React integrations. |
| [Python SDK](https://github.com/rstreamlabs/rstream-python) | Async Python services, ASGI/WSGI applications and webhook receivers. |
| [Java SDK](https://github.com/rstreamlabs/rstream-java) | JVM services using JDK streams, futures and framework adapters. |
| [Kubernetes operator](https://github.com/rstreamlabs/rstream-operator) | Declarative tunnels for Kubernetes Services. |
| [Examples](https://github.com/rstreamlabs/rstream-examples) | Complete applications combining rstream with other components. |

SDKs share the connectivity model and configuration conventions, with different protocol and runtime capabilities. Each repository explains its supported surface and provides a first example.

## Learn and contribute

Start with the [product documentation](https://rstream.io/docs) for concepts and setup, then use the [guides](https://rstream.io/guides) for complete workflows. For contributions, follow the owning repository’s development guide. Questions and reproducible bugs belong in that repository’s issues; report vulnerabilities through the [security policy](../SECURITY.md).
