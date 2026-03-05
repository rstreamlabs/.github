# rstream

rstream is a secure connectivity platform that turns local and private services into globally reachable endpoints. It exposes TCP and UDP workloads — HTTP, TLS, DTLS, QUIC, WebSocket, and WebTransport — without opening inbound ports or changing NAT.

## Key features

- Outbound-only connectivity with encryption by default (TLS 1.3 transport), with support for modern tunnel protocols and transports.
- Edge enforcement for authentication and access policy, including token-based access, mutual TLS, and IP or GeoIP restrictions (availability depends on deployment and plan).
- Published and private tunnels for both public endpoints and client-only connectivity.
- CLI and SDKs for operator workflows, automation, and product integration.

## SDKs

- **Go SDK**: Reference implementation with the broadest rstream API surface (and includes the CLI codebase).
- **C++ SDK**: Native integration for performance-critical environments and asynchronous C++ codebases.
- **JavaScript SDK**: Control-plane and integration workflows (listing tunnels, watching events, automation).

## Core repositories

- **Engine server**: https://github.com/rstreamlabs/rstream-engine  
- **Next.js integration**: https://github.com/rstreamlabs/rstream-nextjs  

## Learn more

📚 Documentation: https://rstream.io/docs  
💻 SDKs: https://github.com/rstreamlabs/rstream-go · https://github.com/rstreamlabs/rstream-cpp · https://github.com/rstreamlabs/rstream-js  
🌐 Website: https://rstream.io
