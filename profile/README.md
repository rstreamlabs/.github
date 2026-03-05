# rstream

rstream is a secure tunneling platform that turns local and private services into globally reachable endpoints. It exposes TCP and UDP workloads — HTTP, TLS, DTLS, QUIC, WebSocket, and WebTransport — without opening inbound ports or changing NAT.

## Key features

- Outbound-only connectivity with encryption by default (TLS 1.3 transport), with support for modern tunnel protocols and transports.
- Edge enforcement for authentication and access policy, including options such as token-based access, mutual TLS, and IP or GeoIP restrictions (availability depends on deployment and plan).
- Published and private tunnels for both public endpoints and client-only connectivity.
- CLI and SDKs for operator workflows, automation, and product integration.

## SDKs

- **Go and C++ SDKs:** Full tunnel lifecycle management (create, update, close) and runtime connectivity.
- **JavaScript SDK:** API integration patterns such as listing tunnels and watching events.

## Learn more

📚 [Documentation](https://rstream.io/docs)  
💻 [Go SDK](https://github.com/rstreamlabs/rstream-go) · [C++ SDK](https://github.com/rstreamlabs/rstream-cpp) · [JS SDK](https://github.com/rstreamlabs/rstream-js)  
🌐 [Website](https://rstream.io)
