# Turboline

![Top Banner](https://turbocdn.blob.core.windows.net/blog-images/Turbostream.png)

<p align="center">
  <strong>Welcome to Turboline!</strong><br>
  <em>Realtime data infrastructure for AI Agents</em>
</p>

<p align="center">
  <a href="https://turboline.ai">Website</a> | 
  <a href="https://github.com/turboline-ai/turbostream">Open Source</a> | 
</p>

---

## 🚀 Our Focus: Turbostream

We are committed to building Turbostream, an open-source platform that enables developers and data engineers to consume, analyze, and visualize chaotic, high-frequency data feeds with the power of Artificial Intelligence.

Turbostream is designed for high throughput, low latency environments like financial services, network monitoring, and industrial IoT. Our goal is to transform millions of raw data points into concise, natural-language, and actionable intelligence in real time.

---
## 🛠️ Components

TurboStream is developed as two separate, highly focused open-source components, licensed under the Mozilla Public License 2.0 (MPL-2.0).

**1. TurboStream Core Backend**

The heart of the system, written in Go, focused exclusively on performance and security.                                  
Feature Summary

| Feature Summary    | Description |
| -------- | ------- |
| High-Speed Ingestion  | Uses Goroutines and Channels for non-blocking consumption of data via WebSockets and HTTP polling. |
| Secure Configuration | Retrieves sensitive feed configuration from a secure MongoDB vault at startup. |
| LLM-Agnostic Processing    | Implements the core batching, throttling, and state management required to feed real-time data to any LLM API for contextual analysis.   |

[Backend Repository Link](https://github.com/turboline-ai/turbostream/tree/main/go-backend)

**2. TurboStream Terminal UI (TUI)**

A feature-rich, interactive client built with Go, providing a powerful, desktop-grade dashboard right in your terminal.


| Feature Summary    | Description |
| -------- | ------- |
| Real-Time Observability  | Displays live metrics on queue depth, throughput, and consumer latency, ensuring performance transparency. |
| Analysis Section | Renders the LLM's natural-language output and contextual analysis in a dedicated panel. |
| Configuration Interface   | Allows secure viewing and interaction with current feed configurations and system health status.   |

[TUI Repository Link](https://github.com/turboline-ai/turbostream/tree/main/go-tui)

---

## 🤝 Community and Contribution

TurboStream is a project built with and for the community. We welcome contributions, feedback, and discussion from developers specializing in high-performance Go, real-time data streaming, and applied AI/LLM engineering.

Join our Github discussions for regular updates and announcements. 

---

## 📜 License

All core components of TurboStream are released under the **Mozilla Public License 2.0 (MPL-2.0)**.

---

## 📦 Other Relevant Projects

### .NET Packages on NuGet

<p align="left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/ee/.NET_Core_Logo.svg" alt=".NET Logo" width="100" height="100">
</p>

| Package Name                             | Description                                   | Download Link                                                                                        |
|------------------------------------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------|
| **Turboline.AI.API.Client**              | API Client for interacting with Turboline AI. | [NuGet](https://www.nuget.org/packages/Turboline.AI.API.Client)                                      |
| **Turboline.NLQ2SQL.MSSQL**              | Natural Language to SQL for MSSQL.            | [NuGet](https://www.nuget.org/packages/Turboline.NLQ2SQL.MSSQL)                                      |
| **Turboline.NLQ2SQL.PostgresSQL**        | Natural Language to SQL for PostgreSQL.       | [NuGet](https://www.nuget.org/packages/Turboline.NLQ2SQL.PostgresSQL)                                |
| **Turboline.NLQ2SQL.MySQL**              | Natural Language to SQL for MySQL.            | [NuGet](https://www.nuget.org/packages/Turboline.NLQ2SQL.MySQL)                                      |
| **Turboline.NLQ2SQL.MSSQL.WebForms**     | NLQ to SQL for MSSQL in WebForms.             | [NuGet](https://www.nuget.org/packages/Turboline.NLQ2SQL.MSSQL.WebForms)                             |

---

### Future Packages

We are continuously expanding our library of packages. Stay tuned for new releases in other programming languages and frameworks.

---

<p align="center">
  Thank you for visiting the Turboline GitHub repository. We look forward to collaborating and building the future of AI together.
</p>

![Bottom Banner](https://turbocdn.blob.core.windows.net/cdn/images/Turboline-banner.png)
