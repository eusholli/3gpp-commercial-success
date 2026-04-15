# 3GPP Commercial Success

A comprehensive knowledge base and reference tool for understanding 3GPP telecommunications standards from both technical and commercial deployment perspectives.

## Overview

This repository documents the evolution of 3GPP mobile network standards (from 2G through 6G), tracking not just the technical features introduced in each release, but also their real-world commercial deployment across generations. It combines:

- **Standards expertise** — detailed coverage of all 3GPP releases (99 through 21), generations (2G, 3G, 4G, 5G, 6G), and technical specifications
- **Commercial metrics** — real deployment data showing which features achieved global adoption and which remained niche
- **Practical knowledge** — guidance on network planning, spectrum strategy, migration paths, troubleshooting, and O-RAN architectures

## Contents

### 📋 Core Documentation

- **`3gpp-release-features.md`** — The flagship reference document covering every 3GPP release in detail:
  - Complete feature breakdown for each release/generation
  - Commercial deployment metrics (shows adoption scope: fully deployed, partially deployed, or not deployed)
  - Global deployment statistics and operator counts
  - Links to relevant 3GPP Technical Specifications
  - Over 200 major features tracked across 2G, 3G, 4G, 5G, and early 6G study items

- **`3gpp-expert.skill`** — A Claude Code skill that augments Claude with 3GPP expertise:
  - Enables Claude to serve as a senior 3GPP telecommunications consultant
  - Automatically triggers on 3GPP-related queries (standards, protocols, deployments, network architecture)
  - References local knowledge base for accurate, up-to-date information

### 📚 Skill Knowledge Base

The `.claude/skills/3gpp-skill/` directory contains detailed reference materials:

- **`SKILL.md`** — Complete skill documentation covering:
  - Standards & releases (release cycles, spec organization, staging methodology)
  - Radio Access Technologies (PHY layer details, protocol stacks, generation-specific differences)
  - RAN Working Group structure and responsibilities
  - Core network architecture (5GC, SBA, evolution from EPC)
  - Key 5G/6G features (network slicing, MIMO, beamforming, URLLC, NTN, sidelink, positioning)
  - Practical deployment knowledge (network planning, spectrum strategy, migration, interoperability)
  - Future evolution (5G-Advanced, 6G timeline and themes)

- **`references/releases.md`** — Detailed release-by-release breakdown
- **`references/phy-layer.md`** — Physical layer specifications and signal details
- **`references/working-groups.md`** — 3GPP RAN and SA working group mappings

### 📊 Visual Resources

- **`3gpp-commercial-success-charts.html`** — Interactive charts visualizing:
  - Feature adoption timelines across generations
  - Commercial deployment metrics
  - Technology evolution curves
  - Standards release history and feature introduction

### 🎨 Assets

- **`3gpp_logo.svg`** — Official 3GPP logo (vector)
- **`3killpp.jpeg`** — Alternative project logo variant

## How to Use This Repository

### For Claude Code Users

1. **Use the 3GPP Skill** — This repository includes a custom Claude Code skill that automatically enhances Claude with 3GPP expertise:
   ```
   Ask about any 3GPP topic:
   - Standards and releases: "What's new in Release 18?"
   - Protocols: "How does the RRC connection establishment work?"
   - Deployment: "Compare NSA vs SA 5G deployment"
   - Troubleshooting: "Why would a handover fail in LTE?"
   ```

   The skill automatically:
   - Grounds answers in specific 3GPP Technical Specifications
   - References the release features database
   - Adapts depth to the question (high-level overview vs. protocol-level detail)
   - Uses correct terminology (UE, gNB, handover, etc.)

2. **Explore the Feature Database** — `3gpp-release-features.md` is the primary reference:
   - Find what feature you're interested in
   - See which release introduced it
   - Understand the commercial adoption (was it widely deployed?)
   - Get the relevant 3GPP spec number

3. **Reference the Charts** — Open `3gpp-commercial-success-charts.html` to visualize:
   - Feature timelines across generations
   - Adoption trends
   - Technology evolution curves

### For Technical Research

The repository provides authoritative references for:

- **Which spec covers what?** — See working group mappings in `references/working-groups.md`
- **Generation-specific details** — Physical layer facts, protocol stack differences, key terminology
- **Deployment strategies** — Network planning, spectrum allocation, migration paths, O-RAN
- **Future roadmap** — What's coming in 5G-Advanced and 6G study items

### For Project Teams

Use this as a knowledge base for:
- **Onboarding** — New team members learning 3GPP standards
- **Architecture decisions** — Understanding trade-offs between NSA/SA, LTE/NR, etc.
- **Feature prioritization** — Which features matter commercially
- **Vendor evaluation** — Checking which features vendors should support

## Key Facts at a Glance

### Generations & Timelines
- **2G (1992–2003)**: GSM, GPRS, EDGE — circuit and early packet switching
- **3G (2000–2020)**: WCDMA/HSPA — packet-optimized with IMS foundation
- **4G (2008–present)**: LTE — flat architecture, all-IP, dominant since 2012
- **5G (2019–present)**: NR with 5GC — service-based architecture, network slicing, massive MIMO
- **5G-Advanced (2023+)**: Rel-18/19/20 — AI/ML, energy efficiency, XR, advanced NTN
- **6G (2027+)**: Rel-21+ — sub-THz spectrum, integrated sensing and communication, digital twins

### Deployment Leaders
- **LTE**: 835 operators in 243 countries (6.6 billion subscriptions as of May 2025)
- **5G NR**: 200+ operators in 70+ countries (1.3+ billion subscriptions)
- **IMS**: 375 operators in 156 countries (foundational for VoLTE/VoNR)

### Critical Technical Facts
- **3GPP Spec Organization**: 21-series (requirements), 23-series (architecture), 24-series (NAS), 29-series (core protocols), 36-series (LTE), 38-series (NR)
- **LTE** uses Turbo coding + TBCC; **NR** uses LDPC + Polar
- **NR** adds SDAP layer (QoS flow mapping), flexible numerology (15–240 kHz), bandwidth parts, beam-based operations
- **5GC** replaces EPC with Service-Based Architecture (HTTP/2, JSON REST APIs)

## Project Structure

```
3gpp-commercial-success/
├── README.md                              # This file
├── LICENSE                                # MIT License
├── 3gpp-release-features.md              # Main feature reference (200+ features tracked)
├── 3gpp-expert.skill                     # Claude Code skill definition
├── 3gpp-commercial-success-charts.html   # Interactive visualization
├── 3gpp_logo.svg                         # Official logo
├── 3killpp.jpeg                          # Alternative logo
├── .github/
│   └── FUNDING.yml                       # GitHub sponsorship config
├── .claude/
│   ├── settings.local.json               # Claude Code settings
│   └── skills/
│       └── 3gpp-skill/                   # Skill knowledge base
│           ├── SKILL.md                  # Skill documentation
│           └── references/
│               ├── releases.md           # Release history
│               ├── phy-layer.md          # Physical layer specs
│               └── working-groups.md     # Working group mappings
└── .gitignore
```

## Getting Started

### 1. Explore the Feature Database
Start with `3gpp-release-features.md` to get a sense of:
- How many operators deployed feature X?
- When was feature Y introduced?
- Which releases matter most for your use case?

### 2. Understand Your Generation
Jump to the section for your area of interest:
- **2G?** See "2G / GSM Era"
- **3G?** See "3G / UMTS Era"
- **4G?** See "4G / LTE Era"
- **5G?** See "5G / NR Era"
- **6G?** See "6G Study Items & Vision"

### 3. Dive into Technical Details
Use the `.claude/skills/3gpp-skill/references/` files to find:
- **Protocol specifics** → `phy-layer.md`
- **Working group ownership** → `working-groups.md`
- **Release evolution** → `releases.md`

### 4. Ask the 3GPP Expert
If you have Claude Code installed, ask directly:
```
"Tell me about Release 18"
"What's the difference between RRC and NAS?"
"How do network slices work in 5GC?"
"What does O-RAN add to 3GPP?"
```

## Key Questions This Repository Answers

**Technical:**
- How does the RRC connection establishment procedure work? (Step-by-step with spec references)
- What's the difference between LTE PSS and NR PSS? (Different sequences: ZC vs m-sequence)
- How does 5GC differ from EPC? (Service-based architecture, network functions, interfaces)
- What is a bandwidth part (BWP)? (Why NR needs them, how they're configured)

**Deployment:**
- Which 5G features have the highest commercial adoption?
- What's the best migration path from EPC to 5GC?
- How do NSA and SA deployments compare? (Pros/cons, when to use each)
- What spectrum bands should I prioritize for network planning?

**Strategic:**
- What should we focus on for Release 18/19?
- How does RedCap fit into our 5G strategy?
- When will 6G be commercially relevant?
- What's the timeline for 5G-Advanced features?

## License

MIT License — See `LICENSE` file for details.

## Contributing

This repository is maintained as a knowledge base. For updates, corrections, or suggestions regarding 3GPP features, deployments, or technical details, please refer to the main repository.

## Related Resources

- **3GPP Official** — https://www.3gpp.org (Technical Specifications, work item status)
- **O-RAN Alliance** — https://www.o-ran.org (RAN architecture specifications)
- **GSM Association (GSMA)** — https://www.gsma.com (Market data, deployment statistics)
- **Claude Code** — https://claude.com/claude-code (Where the 3GPP skill runs)

## Author

Created by **lugasia** — a 3GPP standards and deployment specialist.

---

**Last Updated**: 2026 | Version: 1.0
