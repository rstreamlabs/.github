# rstream

rstream is a developer-first platform for zero-trust networking.

It combines an edge network with lightweight agents to publish local and private services through outbound-only tunnels, with identity, access policy, and observability handled at the edge. The same model covers browser-facing services, internal access paths, remote devices, and embedded systems without requiring inbound exposure or a VPN.

HTTP and non-HTTP workloads share the same connectivity model, including HTTP, TCP, TLS, DTLS, QUIC, WebSocket, and WebTransport. rstream can also provide managed STUN/TURN for WebRTC connectivity when browser peers need relay support.

## What rstream provides

- Outbound-only tunnels with encryption by default.
- Edge authentication and access policy, including rstream Auth, tokens, mutual TLS, IP restrictions, and GeoIP rules depending on deployment and plan.
- Published and private tunnels for browser-facing services, internal access, and client-only connectivity.
- CLI, SDKs, and a Kubernetes operator for operational workflows, backend integration, and device-side software.
- Built-in observability for connection logs, metrics, and operational tooling.
- Browser-based operator flows such as WebTTY for identity-aware terminal access.
- Sandbox-oriented connectivity patterns for isolated code execution and runner orchestration.

## Common use cases

- Local development, demos, QA, and temporary endpoint exposure.
- Zero-trust access to SSH, dashboards, APIs, and other private services.
- Fleet operations, remote administration, and browser-based terminal access with WebTTY.
- Kubernetes-native tunnel management for Services that should be exposed through rstream.
- Real-time systems that need low-latency signaling, datagram transports, or STUN/TURN-assisted connectivity.
- AI and agent workflows that need isolated execution environments and controlled network reachability.

## SDKs, operator, and examples

- Go SDK and CLI: https://github.com/rstreamlabs/rstream-go
- C++ SDK: https://github.com/rstreamlabs/rstream-cpp
- JavaScript SDK: https://github.com/rstreamlabs/rstream-js
- Kubernetes operator: https://github.com/rstreamlabs/rstream-operator
- Examples: https://github.com/rstreamlabs/rstream-examples

## Learn more

- Documentation: https://rstream.io/docs
- Guides: https://rstream.io/guides
- Website: https://rstream.io
- GitHub organization: https://github.com/rstreamlabs
