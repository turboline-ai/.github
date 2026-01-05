![Top Banner](https://turbocdn.blob.core.windows.net/blog-images/naga.png)

<p align="center">
  <strong>Welcome to Turboline!</strong><br>
  <em>Realtime data infrastructure for AI bound streams</em>
</p>

<p align="center">
  <a href="https://turboline.ai">Website</a> | 
  <a href="https://github.com/turboline-ai/turbostream">Open Source</a>
</p>

---

## Our Focus: Turbostream

We are committed to building Turbostream, an open-source platform that enables developers consume and analyze chaotic, high-frequency data feeds with the power of Artificial Intelligence.

Turbostream is designed for high throughput, low latency environments like financial services, network monitoring, and industrial IoT. Our goal is to transform millions of raw data points into concise format that can be ingestable by LLM and AI models for actionable intelligence in real time.

[![Watch the video](https://img.youtube.com/vi/wi7u57JCQ_E/maxresdefault.jpg)](https://youtu.be/wi7u57JCQ_E)

### [Watch this video on YouTube](https://youtu.be/wi7u57JCQ_E)

---
## Components

Turbostream is developed as two separate, highly focused open-source components, licensed under the Mozilla Public License 2.0 (MPL-2.0).

**1. Turbostream Core Backend**

The heart of the system, written in Go, focused exclusively on performance and security.                                  

| Feature Summary    | Description |
| -------- | ------- |
| High-Speed Ingestion  | Uses Goroutines and Channels for non-blocking consumption of data via WebSockets and HTTP polling. |
| Secure Configuration | Retrieves sensitive feed configuration from a secure MongoDB vault at startup. |
| LLM-Agnostic Processing    | Implements the core batching, throttling, and state management required to feed real-time data to any LLM API for contextual analysis.   |
| TSLN Implementation    | Implements [Time Series Lean Notation (TSLN)](https://github.com/turboline-ai/tsln) for efficient token consumption. |

[Backend Repository Link](https://github.com/turboline-ai/turbostream/tree/main/go-backend)

**2. Turbostream Terminal UI (TUI)**

A feature-rich, interactive client built with Go, providing a powerful, desktop-grade dashboard right in your terminal.


| Feature Summary    | Description |
| -------- | ------- |
| Real-Time Observability  | Displays live metrics on queue depth, throughput, and consumer latency, ensuring performance transparency. |
| Analysis Section | Renders the LLM's natural-language output and contextual analysis in a dedicated panel. |
| Configuration Interface   | Allows secure viewing and interaction with current feed configurations and system health status.   |

[TUI Repository Link](https://github.com/turboline-ai/turbostream/tree/main/go-tui)

---

## Community and Contribution

Turbostream is a project built with and for the community. We welcome contributions, feedback, and discussion from developers specializing in high-performance Go, real-time data streaming, and applied AI/LLM engineering.

Join our Github discussions for regular updates and announcements. 

---

## License

All core components of Turbostream are released under the **Mozilla Public License 2.0 (MPL-2.0)**.

---

## Other Relevant Projects

### Time Series Lean Notation

TSLN (Time-Series Lean Notation) is a specialized data serialization format designed to maximize token efficiency when transmitting time-series data to Large Language Models (LLMs) for analysis. Through innovative encoding strategies including relative timestamps, differential encoding, and repeat markers, TSLN achieves approximately 74% token reduction compared to JSON and 40% reduction compared to existing optimized formats like TOON (Token-Optimized Object Notation).

[Read our white paper](https://github.com/turboline-ai/tsln)

| Package Name                             | Description                                   | Download Link                                                                                        |
|------------------------------------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------|
| **TSLN Go Lang**              | Go Implementation for TSLN. | [Repo](https://github.com/turboline-ai/tsln-golang)                                      |
| **TSLN Node.JS**              | Node.js Implementation for TSLN.            | [Repo](https://github.com/turboline-ai/tsln-node)                                      |

---

### Future Packages

We are continuously expanding our library of packages. Stay tuned for new releases in other programming languages and frameworks.

---

<p align="center">
  Thank you for visiting the Turboline GitHub repository. We look forward to collaborating and building the future of AI together.
</p>

![Bottom Banner](https://turbocdn.blob.core.windows.net/cdn/images/Turboline-banner.png)
