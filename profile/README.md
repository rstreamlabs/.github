# rstream

rstream is a secure tunneling platform that transforms localhost into globally accessible endpoints.  
It allows developers and operators to expose any TCP/UDP service — HTTP, TLS, DTLS, QUIC, WebSocket, WebTransport — to the internet safely, without opening firewalls or managing NAT.

## Key Features

- Secure by default: TLS 1.3, DTLS, QUIC, optional mTLS, IP allowlists, token auth, SSO.
- Multi-protocol support: HTTP/1.1, HTTP/2, HTTP/3, WebSocket, raw TCP/UDP, DTLS, QUIC.
- Published or private tunnels with automatic reconnection and load balancing.
- Developer-friendly CLI and SDKs for automation and integration.

## SDKs

- **Go / C++ SDKs:** Full tunnel lifecycle management (create, update, close).
- **JavaScript SDK:** Interact with the rstream API (list tunnels, watch events, etc.).

## Learn More

📚 [Documentation](https://rstream.io/docs)  
💻 [Go SDK](https://github.com/rstreamlabs/rstream-go) – [C++ SDK](https://github.com/rstreamlabs/rstream-cpp) – [JS SDK](https://github.com/rstreamlabs/rstream-js)  
🌐 [Website](https://rstream.io)
