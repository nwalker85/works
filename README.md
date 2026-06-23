# Works — a dated index of things I've built

Nate Walker · [nwalker.cc](https://nwalker.cc) · [@nwalker85](https://github.com/nwalker85)

A public index of the software, platforms, hardware, and written work I've designed and built. Each entry lists an approximate **first-developed** date (for code, the version-control first-commit date where known). Links are provided where a project is public; many remain private source, in which case the dated entry stands as the public record. Some security- and privacy-sensitive projects are listed under **generic titles** by design.

> Dates are approximate years of conception/first development unless a specific date is given. This index is maintained as a living record.

---

## AI Agent Platform (RavenmaskOS)

- **RavenmaskOS** — *2024–2026* — AI-agent operating platform: orchestration, governance, deployment, full action traceability with human-in-the-loop. *(private)*
- **Norns** — *2024–2026* — conversational AI agent (LangGraph); multi-channel; runs on a 3-node HA cluster, with an admin UI and a SwiftUI client. *(private)*
- **Bifrost** — *2024–2026* — MCP tool gateway / execution gateway: tool registry, executor router, channel gateway, contract verification. *(private)*
- **Freyr** — *2025–2026* — agent runtime & execution control plane (FastAPI); lifecycle, threads, checkpointing, distributed workers, bandit-learning. *(private)*
- **Forge** — *2025–2026* — agent compilation platform: compiles agent manifests into deployable LangGraph state graphs. *(private)*
- **Muninn** — *2025–2026* — long-term agent memory service (record/score/retrieve/decay/promote). *(private)*
- **Huginn** *(runtime-state)* — *2025–2026* — cross-channel conversation-state service (single thread across web/voice/chat). *(private)*
- **Ravenhelm Agent Studio** — *2025–2026* — multi-tenant agentic-systems platform (Domain Intelligence as first app). *(private)*
- **Loki** — *2025–2026* — server-driven-UI framework + design system (Flutter/Dart). *(private)*
- **token-forge** — *2025–2026* — design-token toolchain (YAML → CSS/Tailwind/Dart) + token server. → [token-forge](https://github.com/nwalker85/token-forge) · [token-forge-server](https://github.com/nwalker85/token-forge-server)
- **Ymir** — *2026* — AI quality platform: test aggregation + agent-quality scoring (task completion, hallucination, faithfulness, latency). *(private)*
- **PMO Agent** — *2025–2026* — project-management agent (Linear integration, build orchestration, HITL). *(private)*

## Knowledge Graph & Data

- **Mímir** — *2025–2026* — schema-driven knowledge graph / domain CMDB (typed entities, FK-driven edges, blast-radius queries); a multi-repo family. *(private)*

## Governance, Identity & Accountability

- **Runestack / Accountable.ai** — *2025–2026* — AI-agent accountability platform: externally verifiable agent authority, action, approval, outcome. *(private)*
- **Rig** — *2025–2026* — canonical user identity & voice-ID service (multi-tenant; voice-ID + SMS MFA, zero biometrics). *(private)*
- **Forseti** — *2025–2026* — permission-checking & authorization/audit service (OpenFGA + LDAP). *(private)*
- **Vor** — *2025–2026* — agent identity enrollment & contract issuance (birth-cert / wallet / contract tiers). *(private)*
- **Artimetrics™** — *2025–2026* — "biometrics for AI agents": static + behavioral identity profiles, drift verification. *(private)*
- **Várar** — *2025–2026* — binding authority/execution contract primitive. *(private)*
- **Kvasir** — *2025–2026* — identity-onboarding automation CLI (FreeIPA + OIDC + FIDO2). → [github.com/nwalker85/kvasir](https://github.com/nwalker85/kvasir)
- **Ravenhelm Doctrine / Codex** — *2025–2026* — machine-readable governance-as-code (JSON-Schema policies + OPA/Cedar). *(private)*
- **ANP — Agent Network Protocol** — *2026* — cryptographic delegation/identity protocol specification. *(private)*
- **Langmail** — *2025–2026* — zero-trust agent task-mailbox with a pluggable ledger gate. *(private)*
- **Agent Accountability Ledger** — *2026* — anchored private ledger (hash-chain → Merkle → public-chain anchoring → verification). *(private)*
- **Týr** *(design)* — *2025–2026* — governance & audit "constitutional" service (detective control). *(design)*
- **Yggdrasill** *(concept)* — *2026* — agent-first identity provider / "tree of trust." *(concept)*

## SDKs, LLM Infrastructure & Libraries

- **Ravenhelm LLM Inference Bus** — *2026* — command+query inference API over NATS JetStream + shared types lib + generated SDK. *(private)*
- **fenrir-worker** — *2026* — GPU inference worker (NATS consumer driving a local llama server). *(private)*
- **llm-jwt-auth** — *2026* — forward-auth microservice (JWT) for an LLM endpoint. *(private)*
- **ravenhelm-sdk-ts / ravenhelm-contracts** — *2025–2026* — TypeScript client SDK + shared contract/schema library. *(private)*

## Observability & Operations

- **Heimdall** — *2025–2026* — network monitoring & DNS-intelligence platform (ingest → ClickHouse → web UI; detection engine, ATT&CK mapping). *(private)*
- **heimdall-mcp** — *2026* — MCP server exposing the monitoring API to agents. *(private)*
- **Vidar** — *2025–2026* — AIOps / incident-management (alert ingest, ITIL lifecycle, CMDB auto-discovery). *(private)*
- **hostname-intel** — *2026* — hostname intelligence service (10+ intel sources → 0–100 risk score). *(private)*
- **change-mgmt** — *2026* — change-request system of record (RFCs, freeze windows, PIRs) gating tool use/CI. *(private)*
- **office-scorecard** — *2026* — OKR operating dashboard (exporter → Grafana kiosk). *(private)*
- **resource-monitor** — *2026* — Ansible-driven fleet observability (exporters + dashboards + alerting). *(private)*

## Voice & Telephony

- **Voice Gateway** — *first commit 2025-12-17* — browser real-time voice: agent worker + token API, delegating turns to my AI agent. *(private)*
- **Telephony Gateway** — *first commit 2026-01-03* — phone-call service (Programmable-Voice webhooks + media streams; inbound + outbound). *(private)*
- **Voice→agent streaming bridge** — *2025–2026* — adapter turning my LangGraph agent into a streaming voice backend (token streaming, barge-in, tool-calling), vendor-independent. *(private)*
- **Jarvis / Alfred** — *2026* — in-vehicle full-duplex voice assistant orchestration. *(private)*
- **myjarvis** — *created 2025-11-28* — earlier AI agent for local file/tool interactions. *(private)*
- **isip** — *created 2025-12-04* — macOS SIP automation toolkit + MCP server for testing voice-AI systems (MIT). → [github.com/nwalker85/isip](https://github.com/nwalker85/isip)
- **io-bakeoff** — *created 2026-04-02* — voice-IO multi-model bake-off / evaluation harness. *(private)*
- **Multi-Channel Session architecture** — *2025–2026* — design unifying browser, phone, and chat into one continuous agent session. *(design)*

## Situational-Awareness & Sensing *(generic titles by design; private source)*

- **Mobile situational-awareness platform** — *2025–2026* — full-spectrum sensing/awareness platform for a mobile environment (event spine → tactical display). *(private)*
- **RF/SDR sensing node** — *2025–2026* — software-defined-radio sensing node (wideband sweep, sub-GHz decode, signal fingerprinting, multilateration). *(private)*
- **Distributed RF sensor platform** — *2025–2026* — field nodes + event-fabric aggregator + SDKs. *(private)*
- **WiFi presence-sensing mesh** — *2025–2026* — microcontroller sensor mesh → aggregator (vendor enrichment, RSSI trilateration). *(private)*
- **Sensing operations dashboard** — *2026* — operator common-operating-picture UI. *(private)*
- **SDR control MCP server** — *2026* — MCP wrapper over an SDR REST API for agent control. *(private)*
- **Edge broker/aggregator stack** — *2026* — broker + aggregators deployment for the sensing spine. *(private)*
- **ESP32 edge media-collection chain** — *2026* — microcontroller camera/audio firmware + streaming ingest/viewer. *(private)*
- **Camera-roster aggregator** — *2026* — camera roster + caption bridge service. *(private)*
- **Communications-security posture tool** — *2026* — COMSEC posture management. *(private)*
- **Sensing subsystem designs** — *2025–2026* — visual / measurement / device / aerial sensing-subsystem architectures. *(design)*
- **Infrared illuminator hardware** — *2026* — custom IR floodlight (schematic, simulation, enclosure, prototype). *(private)*

## Mobile-Device Analysis *(generic titles by design; private source)*

- **Mobile-device activity dashboard** — *2026* — hosted analysis dashboard over device diagnostic logs (ClickHouse-backed). *(private)*
- **Device power-log timeline tool** — *2026* — parser/interpreter + timeline UI for device power logs. *(private)*
- **Device log-corpus & behavioral toolkit** — *2026* — corpus catalog, session parser, event-semantics dictionary, pattern engine. *(private)*
- **Device messaging-activity capture tool** — *2026* — live-log watcher + capture tooling. *(private)*
- **Device-log ingestion/analysis pipeline** — *2026* — unified-log ingestion into a columnar store + timeline reconstruction. *(private)*
- **CoreDevice SDK** — *2026* — generic SDK for Apple CoreDevice/`devicectl` workflows. *(private)*
- **Audio archive + speaker-ID tool** — *2026* — audio archive with transcription/diarization + cross-recording speaker identity. *(private)*
- **iOS syslog rules daemon** — *2026* — Go daemon evaluating declarative rules over live device syslog. *(private)*

## Apps & Products

- **The Viking** — *2025–2026* — smart-RV product platform (situational awareness + smart-home + voice). *(private)*
- **Frith** — *2026* — macOS/SwiftUI presence-based file-sealing vault (seal files to a physical hardware key). *(private)*
- **Aesir** — *2026* — macOS/SwiftUI agent-orchestration cockpit (terminal, git/worktree managers). *(parked)*
- **Njörðr** — *2026* — journey-mapping platform + declarative-UI (event-sourced) proof-of-concept (Flutter). *(private)*
- **Ultradex** — *2026* — AI networking-relationship assistant (surfaces neglected contacts + outreach). *(private)*
- **cc-monitor** — *2026* — tool to monitor local Claude Code instances (process/memory/token usage); CLI + menubar (MIT). → [github.com/nwalker85/cc-monitor](https://github.com/nwalker85/cc-monitor)
- **Fulla** — *2026* — agent-driven operating-reports platform (scheduled report agents → docs + kiosk). *(PRD)*
- **Fenrir** — *2025–2026* — dedicated GPU LLM inference node (local serving + auth). *(private)*

## Developer Tooling

- **dex-mcp** — *2026* — MCP server for the Dex personal CRM. → [github.com/nwalker85/dex-mcp](https://github.com/nwalker85/dex-mcp)
- **MCPManager / MyMCP** — *2026* — tools to register/launch/monitor local MCP servers; MCP-server scaffold. *(private)*
- **agentfoundry** — *2025–2026* — agent tooling. → [github.com/nwalker85/agentfoundry](https://github.com/nwalker85/agentfoundry)

## Specifications & Declarative Frameworks

- **Domain Intelligence System (DIS)** — *2025–2026* — "Terraform for Agentic AI": a declarative grammar for modeling/deploying agentic AI systems (schema family v1.6, Apache-2.0). → [domainintelligenceschema.org](https://domainintelligenceschema.org) · [github.com/nwalker85/domainintelligenceschema](https://github.com/nwalker85/domainintelligenceschema)
- **EPAS — Enterprise Platform Architecture Scaffold (v2.0)** — *2025–2026* — vendor-neutral enterprise-architecture spec (SDK-first, contract-based trust, five-plane, agentic governance), Apache-2.0, with a reference implementation. → [github.com/epas-platform/spec](https://github.com/epas-platform/spec) · [starter](https://github.com/epas-platform/starter)
- **RLOM — Ravenhelm Linear Operating Model** — *2026* — tiered operating model for running a software team on Linear. *(private — pending publish)*

## Written Works (theses, research, frameworks)

- **The Stigmergic Enterprise** *(DIS whitepaper)* — *Aug 2025* — how AI agents should coordinate via environmental signals ("digital pheromones") rather than central planning.
- **Decision Accountability Framework** — *2026* — Permission → Context → Decision → Consequence "accountability envelope," cryptographically attested.
- **Neural LLM — Optimizable Agent Orchestration** — *2025–2026* — agent-orchestration graphs as trainable neural networks (learned routing, prompt optimization).
- **The Sovereign Agent** — *2026* — crypto identity + provable decisions + self-optimization + stigmergic coordination + economic risk-bearing.
- **Digital Personhood** — *2026* — personhood as functional architecture; "civil infrastructure for digital persons."
- **Entropy and the Architecture of Life** — *2026* — unifying thesis: entropy management as a substrate-independent definition of life.
- **The Nexus Arbitrage Agent** — *2026* — consequence mechanics for sovereign AI.
- **Agent Identity Ontology** — *2026* — DIDs, lineage/birth certificates, agent taxonomy, registration & probate semantics.
- **Bittensor / EigenLayer — Internal Research** — *2026* — analyses mapping crypto-incentive and restaking mechanisms to agent systems.
- **The AI-Augmented Authority** — *2026* — methodology for producing white papers via AI-augmented workflows.
- **Operation Empire** — *2026* — multi-entity corporate/legal/tax operating-model charter.
- **Ravenhelm: The Agentic Enterprise Operating System** — *2026* — strategic operating model (CORE framework mapped to NIST AI RMF; org topology; lifecycle; metrics).
- **Additional frameworks** — *2025–2026* — Agentropy / The λ Maxim, The Cube Protocol, The Rosetta Stone, Branding Strategy, Hrafngrima Manifesto.

---

*Index compiled 2026-06. Public links added as projects are open-sourced. © Nate Walker / Ravenhelm — all rights reserved except where a repository states an open-source license.*
