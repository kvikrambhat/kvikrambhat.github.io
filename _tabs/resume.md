---
title: Resume
icon: fas fa-file-lines
order: 0
---

Solution architect and engineering leader, 13 years across energy storage, renewables,
and connectivity certification. I took on management early at a fast-growing startup,
then moved deliberately back into hands-on architecture to deepen technical judgment.
Both modes are below - same track record, different emphasis.

Currently in Bangalore. Open to remote.

[GitHub](https://github.com/kvikrambhat) ·
[LinkedIn](https://www.linkedin.com/in/kvikrambhat/)

---

## As an Architect

I design distributed, real-time systems at the IT/OT convergence layer - SCADA/HMI
platforms, event-driven IIoT pipelines, and cloud-native modernization. At Fluence I
architect the real-time platform streaming over a million data points across 100,000+
MQTT topics under 99%+ availability SLAs, at utility-scale installations from 100 MW
to 4 GW.

**What that looks like in practice**

- Cut UI update latency from 5 seconds to under 200 ms and halved MQTT broker resource
  usage by redesigning the real-time pipeline from polling to demand-driven Redis
  pub/sub. The UI declares only the metric IDs it needs; a dedicated subscription
  service subscribes to just those topics and scales horizontally on its own. A
  TimescaleDB/Hasura prefetch layer hydrates recent history on load.
- Architected the React-based SCADA/HMI framework visualizing up to a million
  real-time data points - WebSocket streaming patterns, a micro-frontend structure,
  and a reusable charting and diagramming component set on AG Grid, AG Charts, and GoJS.
- Designed the site control authority architecture, guaranteeing a single active
  control source with automatic failover in under a minute across Fluence SCADA, RTU,
  third-party SCADA, and customer integrations.
- Automated a large part of site commissioning by building and owning the site
  configuration toolkit end to end - template model through generation engine to
  production code - expanding device templates and a site layout definition into the
  complete configuration set for every device and service on a site.
- Rebuilt the Device Catalog from a wizard-based UI into a JSON schema-driven
  architecture with an Excel-like grid interface, cutting data entry from one to two
  days to a few hours per site and removing frontend code changes entirely when
  onboarding new hardware product lines.
- Created a shared React component library adopted across four internal applications,
  so updates land once and propagate everywhere.

---

## As an Engineering Leader

Four years leading an 18-engineer organization at Granite River Labs across multiple
global product streams, plus platform and cloud teams at Prescinto. I hire, grow
people into leadership, and set the architectural standards a team is measured against.

**What that looks like in practice**

- Built and led a team of 18 engineers, personally interviewing and hiring 10–12 for
  the Wi-Fi certification workstream and establishing hiring and onboarding standards.
- Grew two direct reports into team lead roles. Several engineers earned Connectivity
  Standards Alliance recognition for contributions to Matter test plan updates and
  certification tooling.
- Co-facilitate Architecture Review Board sessions alongside the Enterprise Architect,
  steering cross-team alignment on change proposals and producing Architecture
  Decision Records within a SAFe Agile model.
- Presented platform scalability roadmap and cloud adoption strategy directly to
  C-level leadership, informing infrastructure investment decisions.
- Represented GRL in cross-company certification working groups of 50–100 engineers
  drawn from Apple, Google, Intel, and other participating companies.
- Mentored graduate engineers onto the data platform team through regular code
  reviews, pair programming, and architectural walkthroughs.

---

## Experience

**UI Architect - Solution Architecture, IIoT/SCADA Platform**
*Fluence, Bangalore · Feb 2024 – Present*

Fluence (NASDAQ: FLNC) is a global energy storage provider whose digital products
manage 22.8 GW of renewable and storage assets. I architect across UI, Configuration,
DevOps, and Platform teams, designing applications and the interfaces between them for
mission-critical SCADA/HMI and energy management systems.

Alongside the platform work above: standardized developer environments using Docker
with VS Code Remote so every engineer gets an identical setup on first run, added
automated PR checks so feedback arrives before review, and designed a release manifest
system that validates component versions and artifact availability before a release
proceeds.

**Technical Manager**
*Prescinto Technologies, Bangalore · Aug 2023 – Feb 2024*

Real-time monitoring and analytics for utility-scale renewable plants, 50–200 MW. Led
four engineers across cloud and application development, owning architecture decisions
for scalability and reliability.

- Migrated real-time data ingestion from self-hosted VerneMQ to Azure Event Grid,
  moving the pipeline to a managed event-driven model with native Logic Apps integration.
- Re-architected SFTP-based ingestion into a cloud-native, fault-tolerant model,
  improving delivery reliability from 85% to 99.9% and eliminating manual recovery.
- Directed modernization of on-premises data processing to a horizontally scalable
  cloud architecture, establishing monitoring, alerting, and performance baselines.

**Software Development Manager**
*Granite River Labs, Bangalore · Apr 2019 – Jul 2023*

GRL is a global connectivity testing and certification company operating 10+ labs
across three continents, serving 500+ semiconductor and consumer electronics companies.

- Modernized the Wi-Fi certification platform with end-to-end automation, reducing
  vendor certification timelines from weeks to days.
- Led development of the Matter Protocol certification framework, the official
  compliance tooling used across the CSA member ecosystem.

**Technical Lead / Senior Software Engineer**
*Granite River Labs, Bangalore · Oct 2013 – Apr 2019*

- Automated IoT certification testbed setup - auto-detecting devices over USB, applying
  topology configuration, and booting in the correct order. Test topologies form in
  seconds rather than an hour of manual setup per run.
- Replaced a fixed-interval polling loop in the firmware data path with a
  readiness-driven read, removing multi-second lag in real-time diagnostics and
  eliminating UI crashes caused by streaming full-rate data.
- Led the cross-platform port of the product line to .NET Core, extending tooling from
  Windows-only to Linux and macOS.
- Led the team that built the official open-source Thread Test Harness used by all
  authorized test labs worldwide, resolving chipset-specific interoperability failures
  across Qualcomm, Silicon Labs, and Nordic Semiconductor.

---

## Skills

**Languages & Frameworks**
.NET Core (C#), Python, JavaScript, TypeScript, Node.js, React, Next.js, Angular

**Architecture & Protocols**
Microservices, Event-Driven Architecture, REST, gRPC, MQTT / SparkplugB, Redis Pub/Sub,
WebSockets, Micro-Frontends, mTLS

**Cloud & DevOps**
Azure (Event Grid, Logic Apps, Cache for Redis, Blob Storage), Docker, Kubernetes,
Jenkins, GitHub Actions, CI/CD

**Data**
TimescaleDB, PostgreSQL, time-series pipelines, Hasura

**Practice**
System Design, Architecture Decision Records, SAFe Agile, Architecture Review Board,
Playwright, TestRail, Git

**Leadership**
Hiring and team building, mentoring and onboarding, technical roadmapping,
architecture governance, executive communication

---

## Recognition

- Certificate of Recognition, Connectivity Standards Alliance, for contributions to
  Matter Protocol certification tooling (2020)
- Acknowledged by the Thread Group for contributions to the Thread Test Harness
  certification suite (2017)

## Education

Bachelor of Engineering, Computer Science - Sambhram Institute of Technology (VTU),
Bangalore, 2013

## Certifications

- Microsoft Certified: Azure Fundamentals (AZ-900), 2026
- Hugging Face - Agents, MCP, Foundations of Agents (2025)
- Multi AI Agent Systems with crewAI, DeepLearning.AI (2025)
