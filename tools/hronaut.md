---
slug: "hronaut"
name: "Hronaut"
description: "Visible local browser workspaces for coding agents over MCP"
category: "web-browser-interaction-tools"
tags:
  - "browser"
  - "mcp"
  - "local-first"
  - "persistent-session"
  - "human-in-the-loop"
  - "coding-agents"
websiteUrl: "https://hronaut.dev"
githubUrl: "https://github.com/hronaut/hronaut"
logoUrl: "https://www.google.com/s2/favicons?sz=64&domain_url=https://hronaut.dev"
ogImageUrl: "https://hronaut.dev/hronaut-social-card-v1-11-56.png"
pricing: "paid"
classification: "agent-enabling"
entityType: "software-application"
developerName: "Hronom"
docsUrl: "https://hronaut.dev/setup"
pricingUrl: "https://hronaut.dev/#pricing"
licenseUrl: "https://github.com/hronaut/hronaut/blob/main/LICENSE"
interfaces:
  - "Streamable HTTP MCP"
  - "Electron desktop application"
deploymentModes:
  - "local"
evidenceSources:
  - title: "Hronaut official website"
    url: "https://hronaut.dev/"
    claim: "Hronaut describes a local visible browser workspace for coding agents, with a 10-day trial followed by paid named-user plans and no automatic conversion from the trial."
    accessedAt: "2026-09-14"
    sourceType: "official-product-page"
  - title: "Hronaut public repository — browser and MCP boundaries"
    url: "https://github.com/hronaut/hronaut"
    claim: "The public repository documents a visible persistent Electron browser, durable agent workspaces over MCP, named local browser context, human takeover, and authoritative postcondition read-back."
    accessedAt: "2026-09-14"
    sourceType: "official-repository"
  - title: "Hronaut v2.4.1 release"
    url: "https://github.com/hronaut/hronaut/releases/tag/v2.4.1"
    claim: "The current public release notes document authority-generation visibility in consequential action reviews, consolidated workspace and access controls, delayed-favicon recovery, and stale credential-fill rejection."
    accessedAt: "2026-09-14"
    sourceType: "official-release-notes"
  - title: "Hronaut subscription and trial license"
    url: "https://github.com/hronaut/hronaut/blob/main/LICENSE"
    claim: "The public license describes source visibility, a single 10-day evaluation per named user, and paid ongoing use after the trial."
    accessedAt: "2026-09-14"
    sourceType: "official-license"
verificationLevel: "documentation-reviewed"
classificationRationaleMd: "Hronaut materially empowers an external coding agent by supplying a persistent local visible browser workspace, MCP execution boundary, scoped browser context, and human takeover controls; it is not itself the planning agent."
inclusionRationaleMd: "The agent-facing value is substantive: an agent can operate a named browser workspace through MCP and resume after a session boundary while a person retains visible control of consequential steps."
bestForMd: "Coding agents that need a named visible local browser workspace, persistent tabs between sessions, human takeover during sign-in, 2FA, or consequential writes, and authoritative read-back after browser actions."
notBestForMd: "Teams seeking a hosted browser fleet, stealth or CAPTCHA-solving service, unattended cloud execution or a general-purpose agent memory layer."
limitationsMd: "Hronaut is a local desktop execution layer, not a hosted browser service or orchestration platform; compatibility depends on the calling MCP client and site. The product is source-available and requires a subscription after its limited trial."
unknownsMd: "Compatibility with a specific coding-agent client depends on that client's local Streamable HTTP MCP support and the active Hronaut profile configuration."
isIndexable: true
---

Hronaut is a visible, persistent Electron browser that exposes durable local agent workspaces through MCP. Each workspace keeps its own browser profile and site data, while people can watch, pause, approve, or take over a task when a manual step is required.

## So agents can...

- Navigate and interact with websites through a visible local browser workspace
- Reuse named browser context and tabs across compatible agent sessions
- Pause for human sign-in, 2FA, CAPTCHA, payment, or other consequential steps
- Continue only after a caller verifies the authoritative external result
