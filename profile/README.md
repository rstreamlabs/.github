# rstream

rstream makes a service running on your laptop, server or private network
reachable through a connection opened from that machine. You can share a
web app at a URL or keep access private to authenticated applications.

## Get started

[Create your first HTTP tunnel](https://rstream.io/docs/getting-started/quickstart-guide)
to install the CLI, share a small local server and test its URL. Use the [Kubernetes Operator](https://github.com/rstreamlabs/rstream-operator)
when your platform declares tunnels alongside Kubernetes Services.

## Build with rstream

| SDK | What it brings to your application |
| --- | --- |
| [Go](https://github.com/rstreamlabs/rstream-go) | The reference SDK and CLI, with broad protocol coverage and Go-native networking APIs. |
| [JavaScript and TypeScript](https://github.com/rstreamlabs/rstream-js) | Node.js tunnel runtimes, API clients and browser or React integrations. |
| [C++](https://github.com/rstreamlabs/rstream-cpp) | Native Boost.Asio integration with completion handlers, futures and coroutines. |
| [Python](https://github.com/rstreamlabs/rstream-python) | Async Python integrations and adapters for ASGI and WSGI services. |
| [Java](https://github.com/rstreamlabs/rstream-java) | JVM integrations using JDK streams, futures and framework adapters. |

Check supported protocols when [choosing an SDK](https://rstream.io/sdks).
The [Examples repository](https://github.com/rstreamlabs/rstream-examples)
contains complete applications. The [product documentation](https://rstream.io/docs)
covers tunnels, WebTTY and access policies, and the
[guides](https://rstream.io/guides) show them in use.

## Contribute and report issues

Follow the owning repository’s development guide for contributions and use
its issue tracker for reproducible bugs. Report vulnerabilities privately
through the [security policy](../SECURITY.md).
