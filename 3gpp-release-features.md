# 3GPP Release Features by Generation

A comprehensive reference of features introduced in each 3GPP release, organized by mobile generation.

---

## 2G / GSM Era

### Phase 1 (1992)

- Basic GSM circuit-switched voice — **3/3** — Deployed by virtually all mobile operators globally from 1992 onward; foundational to mobile telephony with billions of subscribers across 200+ countries, though now being sunset in advanced markets
- SMS (Short Message Service) — **3/3** — Universally deployed on all GSM networks worldwide from the mid-1990s; still active on billions of devices globally despite OTT messaging competition
- TDMA-based air interface — 200 kHz channels, 8 timeslots per carrier
- Full-rate speech codec (13 kbps)
- International roaming framework

### Phase 2 (1995)

- Enhanced Full Rate (EFR) speech codec — improved voice quality — **3/3** — Widely deployed across GSM operators globally from 1997 onward; became the standard voice codec on most GSM networks before being supplemented by AMR
- Half-rate speech codec — doubles voice capacity per carrier — **1/3** — Deployed by many GSM operators as a capacity tool in congested markets, but uptake was uneven and it was largely superseded by UMTS and later technologies
- Supplementary services (call forwarding, call hold, multiparty)
- Emergency call enhancements

### Release 96 (Q1 1997)

- 14.4 kbps circuit-switched data bearers — **1/3** — Deployed by most GSM operators as a software upgrade; saw real commercial use for dial-up data and early WAP, but quickly superseded by GPRS
- Enhanced SMS capabilities
- Advice of Charge enhancements

### Release 97 (Q1 1998)

- **GPRS (General Packet Radio Service)** — first packet data overlay on GSM; theoretical peak ~171.2 kbps — **3/3** — Deployed commercially by operators in 213+ countries; BT Cellnet launched the first commercial GPRS network in 2000 and it became the global standard for 2.5G packet data through the 2000s
- New core network elements: SGSN (Serving GPRS Support Node), GGSN (Gateway GPRS Support Node)
- GTP (GPRS Tunneling Protocol)
- Always-on IP connectivity concept

### Release 98 (Q1 1999)

- **EDGE (Enhanced Data rates for GSM Evolution)** — 8-PSK modulation raises peak to ~384 kbps — **3/3** — Deployed on 604 GSM/EDGE networks in 213 countries as of 2013; widely deployed by operators as a 2.75G upgrade; AT&T/Cingular was an early US deployer in 2003
- AMR (Adaptive Multi-Rate) speech codec — improves voice quality and link robustness
- GPRS support for PCS 1900 band
- CAMEL Phase 2 for operator intelligent-network services

---

## 3G / UMTS Era

### Release 99 / Release 3 (Q1 2000) — "UMTS Launch"

- **WCDMA air interface** — 5 MHz bandwidth; 384 kbps practical, up to 2 Mbps theoretical — **3/3** — Deployed commercially by 150+ licensed operators worldwide; Telenor launched the first commercial WCDMA network in 2001 and it became dominant 3G technology globally through the 2000s-2010s
- New RAN elements: Node B (base station) + RNC (Radio Network Controller)
- Core network split: MSC/VLR (circuit-switched), SGSN/GGSN (packet-switched)
- Soft handover and macro-diversity combining
- Closed-loop and open-loop power control
- RAKE receiver for multipath combining
- Iu (RAN–core), Iub (RNC–Node B), Iur (RNC–RNC) interfaces

### Release 4 (Q2 2001)

- **All-IP Core Network** — CS domain transported over IP (bearer-independent CS core) — **1/3** — Partially deployed; the MSC server / Media Gateway split was adopted by some operators as an evolution path, but full bearer-independent CS core did not achieve universal deployment as operators migrated directly to EPC
- **TD-SCDMA** added as TDD air interface (China's contribution; 1.28 Mcps chip rate) — **0/3** — Deployed exclusively by China Mobile under a 2009 license; subscribers peaked around 50 million but China Mobile quickly pivoted to TD-LTE, and the TD-SCDMA network was effectively abandoned by 2014
- Low-chip-rate TDD (1.28 Mcps)
- MMS (Multimedia Messaging Service) — **1/3** — Commercially deployed by most operators globally through the 2000s-2010s; usage peaked but has declined with operators like Vodafone Germany, Swisscom, and Singtel discontinuing MMS since 2021, while US operators (AT&T, Verizon, T-Mobile) and others still support it
- MSC server / Media Gateway split for VoIP core transport

### Release 5 (Q1 2002)

- **HSDPA (High Speed Downlink Packet Access)** — shared HS-DSCH channel, 2 ms TTI, adaptive modulation and coding (up to 16-QAM), HARQ; theoretical peak 14.4 Mbps — **3/3** — Deployed on 207+ commercial HSDPA networks in 89 countries by 2008, growing to 601 commercial HSPA networks in 221 countries by 2016; ubiquitous on all major WCDMA operators globally
- **IMS (IP Multimedia Subsystem)** — SIP-based session control architecture for VoIP and multimedia; P/S/I-CSCF functions — **3/3** — Deployed by 375 operators in 156 countries for VoLTE as of 2025; IMS is the foundational platform for VoLTE/VoNR worldwide with a USD 3.46 billion market in 2025
- UTRAN over IP (Iub/Iur over IP)

### Release 6 (Q4 2004)

- **HSUPA (High Speed Uplink Packet Access)** — E-DCH with 10 ms/2 ms TTI, HARQ, up to 5.76 Mbps; HSPA = HSDPA + HSUPA combined — **3/3** — Deployed universally alongside HSDPA across 600+ HSPA networks in 218 countries; became the standard UMTS data technology globally through the 2000s-2010s
- **MBMS (Multimedia Broadcast/Multicast Service)** — efficient one-to-many content delivery — **0/3** — Standardized in Release 6 but never achieved significant commercial deployment on 3G networks; competing technologies (MediaFLO, DVB-H) also failed, and operators skipped directly to eMBMS on LTE
- WLAN–3GPP interworking (I-WLAN)
- IMS enhancements including Push-to-Talk over Cellular (PoC)
- GAN (Generic Access Network) — voice/data over WLAN using GSM/GPRS protocols

### Release 7 (Q4 2007)

- **HSPA+** — 64-QAM DL (21.1 Mbps), 16-QAM UL (11.5 Mbps) — **3/3** — Deployed by 415+ commercial HSPA+ networks in 173 countries as of 2015; Telstra launched the world's first HSPA+ network in February 2009 and it became mainstream on all major WCDMA operators
- **2×2 MIMO for HSDPA** — combined with 64-QAM reaches 28.8 Mbps DL — **1/3** — Deployed by a subset of HSPA+ operators, primarily in advanced markets; MIMO adoption was limited compared to basic HSPA+ due to device and infrastructure cost, with DC-HSPA being more commonly prioritised
- Continuous Packet Connectivity (CPC) — DTX/DRX to reduce overhead for always-on services — **1/3** — Deployed by operators supporting HSPA+ as a software feature on compatible equipment (e.g., Nokia Siemens Networks, ZTE), improving battery life; not universally activated but commercially available on most HSPA+ networks
- EDGE Evolution (EGPRS-2) — higher modulation, improved PHY
- VoIP over HSPA enhancements
- NFC integration specifications

---

## 4G / LTE Era

### Release 8 (Q4 2008) — "LTE Introduction"

- **LTE air interface** — OFDMA downlink, SC-FDMA uplink; up to 300 Mbps DL / 75 Mbps UL — **3/3** — Deployed by 835 operators in 243 countries/territories as of May 2025 with 6.6 billion subscriptions; the dominant global mobile broadband technology
- Scalable bandwidth: 1.4, 3, 5, 10, 15, 20 MHz; FDD and TDD duplex modes
- **Flat RAN architecture** — eNB connects directly to EPC; no RNC
- **EPC (Evolved Packet Core)** — all-IP; MME (mobility), S-GW (user plane anchor), P-GW (internet gateway), HSS (subscriber data), PCRF (policy) — **3/3** — Deployed by all 835+ commercial LTE operators worldwide; the EPC is the universal 4G core network deployed globally
- MIMO: up to 4×4 DL spatial multiplexing; up to 4 transmit antennas
- Turbo coding, HARQ with soft combining, adaptive modulation and coding
- S1 (eNB–EPC) and X2 (eNB–eNB) interfaces
- QoS: QCI-based bearer model, default + dedicated bearers
- **SAE (System Architecture Evolution)** — TS 23.401, TS 23.402

### Release 9 (Q4 2009)

- **eMBMS (evolved MBMS)** — LTE broadcast with MBSFN subframes — **1/3** — Deployed commercially by a limited number of operators including KT (Korea, first commercial launch 2014), Telstra (Australia), and China Mobile (100-city deployment); uptake has been constrained but market is valued at USD 1.04 billion in 2025
- Dual-cell HSDPA (DC-HSDPA) on UMTS — aggregates two 5 MHz carriers
- IMS emergency calls over LTE (TS 23.167)
- Self-Organizing Networks (SON) Phase 1 — ANR, coverage/capacity optimization — **3/3** — Universally deployed across LTE networks globally; SON became a baseline operational requirement for all major operators including AT&T (adopting Ericsson SMO/Non-RT RIC) and Rakuten Mobile
- Home eNodeB (HeNB / femtocell) architecture and security enhancements — **1/3** — Deployed commercially by operators including AT&T, Verizon, T-Mobile US, Sprint, Orange, Vodafone, and EE; T-Mobile deployed LTE femtocells from Alcatel-Lucent in 2015, with a global market reaching USD 6.5 billion in 2024
- Location services (LCS) improvements — OTDOA positioning

### Release 10 (Q1 2011) — "LTE-Advanced" (meets IMT-Advanced)

- **Carrier Aggregation (CA)** — up to 5 component carriers × 20 MHz = 100 MHz; theoretical DL ~3 Gbps — **3/3** — Deployed by 346 LTE-Advanced networks in 155 countries as of 2025; universally supported by all major LTE-A operators globally with a market of USD 5.68 billion in 2025
- **Enhanced MIMO** — up to 8×8 DL, 4×4 UL spatial multiplexing — **1/3** — Deployed by advanced operators (Vodafone Australia with Huawei, Verizon, Telstra) for high-capacity urban sites; 8×8 DL specifically has limited deployment due to cost and device constraints relative to practical 4×4 deployments
- **Relay Nodes (RN)** — in-band and out-band Type 1 relay for coverage extension without backhaul fiber — **0/3** — Standardized in Rel-10 but saw minimal commercial deployment; operators generally preferred small cells, distributed antenna systems, or wireless backhaul over relay nodes, and the feature was largely bypassed in favor of IAB in 5G
- **eICIC (enhanced Inter-Cell Interference Coordination)** — Almost Blank Subframes (ABS) for HetNet interference management — **1/3** — Deployed by operators running HetNet deployments (picocells within macrocells); implemented in commercial LTE-A networks across major operators in dense urban environments, though deployment was selective rather than universal
- SON Phase 2 — load balancing, handover optimization
- Uplink CoMP study item

### Release 11 (Q3 2012)

- **CoMP (Coordinated Multi-Point)** — joint transmission and coordinated scheduling/beamforming across eNBs — **0/3** — Standardized in Rel-11 but saw very limited commercial deployment due to stringent low-latency backhaul requirements; vendors (Ericsson, Huawei, Samsung) supported it but widespread operator uptake did not materialise
- **FeICIC (Further enhanced ICIC)** — receiver interference cancellation for HetNets
- Carrier aggregation enhancements: inter-band TDD CA, TDD–FDD joint operation
- Advanced MIMO codebook for 4Tx DL transmission
- SON Phase 2 enhancements (self-optimization)
- Machine-type communications (MTC) preliminary studies (PSM, extended DRX)

### Release 12 (March 2015)

- **D2D / ProSe (Device-to-Device / Proximity Services)** — direct UE–UE communication over PC5 interface; public safety and commercial use cases — **0/3** — Commercially deployed primarily in US public safety networks (FirstNet) and some first-responder deployments; broad commercial use cases (advertising, social) remain largely unrealised by mainstream operators
- **Dual Connectivity (DC)** — UE simultaneously connected to Master eNB (MeNB) + Secondary eNB (SeNB) for throughput aggregation — **3/3** — Widely deployed across LTE-Advanced operators globally and became the foundational architecture for 5G NSA (EN-DC); universally adopted by operators deploying LTE-A and 5G NSA
- **256-QAM DL** — higher spectral efficiency in good radio conditions — **3/3** — Deployed by LTE-Advanced operators globally as part of gigabit LTE; Telstra deployed 256-QAM with carrier aggregation and 4×4 MIMO to achieve 2 Gbps; Sprint, T-Mobile, and most major LTE-A operators deployed it
- Small Cell Enhancements (SCE) — discovery, dual connectivity, offloading
- MTC enhancements: low-cost UE category (Cat-0), Power Saving Mode (PSM), extended DRX
- SON Phase 3 enhancements

### Release 13 (Q1 2016) — "LTE-Advanced Pro"

- **NB-IoT (Narrowband IoT)** — 180 kHz in-band/guard-band/standalone; deep coverage (+20 dB MCL), long battery life for IoT — **3/3** — Deployed by 177 operators in 69 countries as of 2025 with 140 commercial NB-IoT networks; a global mainstream IoT technology with billions of projected connections
- **LTE-M (Cat-M1 / eMTC)** — 1.4 MHz bandwidth IoT with VoLTE support and mobility — **3/3** — Deployed by 129 LTE-M networks in 53 countries as of 2025; mainstream cellular IoT technology especially in North America and Europe
- **LAA (Licensed Assisted Access)** — LTE in 5 GHz unlicensed spectrum (DL); LBT (Listen Before Talk) mechanism — **1/3** — Deployed commercially by Telstra (first gigabit LTE with LAA), T-Mobile US, and 37 operators across 21 countries as of 2019; real commercial deployments but not universal due to Wi-Fi coexistence complexity and 5G transition
- **LWA (LTE-WLAN Aggregation)** — seamless aggregation of LTE and Wi-Fi traffic at PDCP layer — **0/3** — Only Chunghwa Telecom (Taiwan) launched a commercial LWA service; Korean operators trialled but did not commercialise it due to high cost and equipment replacement requirements; largely superseded by other offload approaches
- Carrier aggregation scaled to 32 component carriers (theoretical)
- **FD-MIMO (Full-Dimension MIMO)** — up to 16 antenna ports, active antenna systems (AAS), 3D beamforming — **3/3** — Widely deployed commercially by operators (Vodafone Australia, Verizon, Telstra with Huawei/Ericsson/Samsung equipment) as a stepping stone to 5G massive MIMO; active antenna systems (AAS) became mainstream in 4G densification and 5G NR
- Latency reduction study — shortened TTI groundwork
- Single-cell point-to-multipoint (SC-PTM) for broadcast

### Release 14 (Mid 2017) — "Road to 5G"

- **C-V2X (Cellular Vehicle-to-Everything)** — PC5 interface (Mode 3: network-scheduled; Mode 4: UE-autonomous); basis for connected automotive — **1/3** — Commercially deployed in China (25+ OEMs in production, 1M+ vehicles by 2023) and early US deployments (Fort Bend County, Texas 2025); real commercial use but not yet widespread globally, with Europe still deciding between ITS-G5 and C-V2X
- **eLAA (Enhanced LAA)** — uplink transmission in unlicensed spectrum — **0/3** — Standardized in Rel-14 but saw minimal commercial deployment; most operators with LAA only deployed downlink LAA and the small number who invested were deterred by 5G transition before eLAA-capable devices matured
- NB-IoT and eMTC enhancements: multicast, positioning, roaming, mobility
- Shortened TTI (sTTI) and faster HARQ processing — latency reduction normative work — **0/3** — Standardized in Rel-14 but not commercially deployed in LTE networks; analysis showed that practical LTE deployment demand was weak and the industry moved to 5G NR mini-slots for low-latency use cases instead
- LTE-based 5G study items initiated
- Aerial vehicle (drone) studies
- **LWIP (LTE/WLAN Integration with IPsec)** — tighter WLAN integration at IP layer

---

## 5G / NR Era

### Release 15 (Late 2018) — "5G Phase 1"

**Delivery in three drops:**

1. **Early drop (Dec 2017):** NSA NR (Option 3/3a/3x — LTE anchor + NR secondary over EPC)
2. **Main drop (Jun 2018):** SA NR (Option 2 — standalone NR gNB + 5GC)
3. **Late drop (Mar 2019):** Migration architectures (Options 4, 5, 7)

**NR Air Interface (TS 38 series):**

- Flexible numerology — subcarrier spacing 15 / 30 / 60 / 120 / 240 kHz (µ = 0–4)
- Frequency ranges: FR1 (410 MHz – 7.125 GHz), FR2 / mmWave (24.25 – 52.6 GHz)
- Channel coding: LDPC for data channels; Polar codes for control channels (replaces Turbo + TBCC)
- Massive MIMO and beam management (P1 beam sweeping, P2 beam refinement, P3 beam tracking) — **3/3** — Universally deployed across 5G NR networks globally; 64T64R massive MIMO dominated the market at USD 4.4 billion in 2025 with macro cells making up 62.8% of deployments; foundational to mid-band 5G performance
- Bandwidth Parts (BWP) — flexible UE bandwidth configuration within a carrier — **3/3** — Implemented in all commercial 5G NR deployments as a mandatory feature of the NR specification; universally present wherever 5G NR is deployed
- Mini-slots (2, 4, or 7 OFDM symbols) for low-latency URLLC scheduling
- SSB (SS/PBCH Block) with beam sweeping — replaces LTE's always-on CRS
- CORESET and flexible search spaces for PDCCH
- **New SDAP layer** — QoS flow-to-DRB mapping; no LTE equivalent
- **RRC INACTIVE state** — three-state machine (IDLE / INACTIVE / CONNECTED); reduces signaling for IoT/sporadic traffic
- Supplementary Uplink (SUL) — low-band UL paired with mid/high-band DL for coverage
- CSI framework: Type I (single-panel) and Type II (multi-panel, high-resolution) codebooks
- Initial NR positioning reference signals (PRS)

**NR NSA (Option 3/EN-DC):** — **3/3** — The overwhelmingly dominant initial 5G deployment mode; the vast majority of early commercial 5G launches worldwide used NSA, providing 5G data speeds while reusing 4G core infrastructure

**NR SA (Option 2):** — **1/3** — Growing rapidly with 85+ operators in 47 countries having launched live 5G SA services as of late 2025, up from early launches in China and North America; now commercially deployed but still represents a minority of global 5G networks

**5G Core (5GC — TS 23.5xx series):**

- **Service-Based Architecture (SBA)** — all NFs communicate via HTTP/2 + JSON RESTful APIs (replaces point-to-point reference points of EPC) — **1/3** — Deployed by 89 operators in 48 markets with commercial 5G SA as of late 2025; growing but still a fraction of global mobile operators; foundational to all 5G SA networks
- Network Functions: AMF (access & mobility), SMF (session management), UPF (user plane), PCF (policy), UDM (subscriber data), AUSF (authentication), NRF (NF registry/discovery), NSSF (slice selection), NEF (capability exposure), AF (application function)
- **Network Slicing** — S-NSSAI = SST (Slice/Service Type) + SD (Slice Differentiator); end-to-end logical network isolation — **1/3** — 65 network slicing-based services worldwide transitioned to commercial offerings as of late 2025 with 55% generating revenue; real commercial deployments by T-Mobile US, China Mobile, Deutsche Telekom, Reliance Jio, but mass-market adoption is still emerging
- **CUPS (Control/User Plane Separation)** — SMF controls UPF via N4/PFCP
- Session and Service Continuity (SSC) modes 1 / 2 / 3 for IP session mobility
- UDM replaces HSS; AUSF centralizes authentication
- NRF provides dynamic NF discovery and registration

### Release 16 (July 2020) — "5G Phase 2"

- **NR V2X (Sidelink)** — PC5 interface for advanced automotive/platooning/remote driving use cases; Mode 1 (gNB-scheduled) and Mode 2 (UE-autonomous resource selection) — **0/3** — Standardized in Rel-16 but not yet commercially deployed; trials ongoing and OEM integration is nascent; ongoing EU and US deployments focus on LTE-V2X (Rel-14) rather than NR V2X
- **IIoT / URLLC enhancements** — TSN (Time-Sensitive Networking) integration, configured grants Type 1/2, intra-UE prioritization, enhanced PDCP duplication for reliability — **0/3** — Standardized but commercially deployed only in isolated pilots (e.g., T-Mobile's Halo autonomous vehicles); industrial URLLC at scale remains pre-commercial with most 5G SA networks not yet offering guaranteed URLLC SLAs
- **IAB (Integrated Access and Backhaul)** — NR-based wireless backhaul for small cells; same spectrum for access and backhaul — **0/3** — Standardized in Rel-16 and enhanced in Rel-18; commercial deployments are emerging but limited, with Samsung supporting IAB commercially but widespread operator deployment not yet achieved as of 2026
- **NR Positioning** — DL-TDOA, UL-TDOA, DL-AoD, UL-AoA, multi-RTT using PRS/SRS; targets sub-3 m accuracy — **1/3** — Commercially deployed in 5G networks with positioning features enabled; operators and enterprises are offering 5G positioning services, though sub-meter accuracy use cases remain niche; growing demand from IIoT and logistics verticals
- **NR-U (NR Unlicensed)** — LBT (Listen Before Talk) mechanism; operation in 5/6 GHz unlicensed bands — **0/3** — Standardized in Rel-16 but commercial operator deployments are limited; primarily used in private network scenarios; public operator adoption has been minimal compared to Wi-Fi 6E competition in unlicensed bands
- **DSS (Dynamic Spectrum Sharing)** — LTE and NR share the same carrier simultaneously via rate matching — **1/3** — Deployed commercially by AT&T (850 MHz, 2020) and European operators as a 5G launch tool; however AT&T later shuttered most DSS deployment after finding performance limitations, and T-Mobile never used it; had real commercial deployment but is now largely in decline
- **MIMO enhancements** — multi-TRP (Transmission-Reception Point) for reliability/capacity; enhanced Type II codebook
- **UE power saving** — UE assistance information, cross-slot scheduling, PDCCH skipping, extended DRX
- **2-step RACH** — MsgA + MsgB (combines Msg1+Msg3 / Msg2+Msg4 of 4-step RACH) for lower latency/overhead
- **Non-Public Networks (NPN)** — SNPN (Standalone NPN) and PNI-NPN (Public Network Integrated NPN) for private 5G — **3/3** — Commercially deployed with 6,500 private LTE/5G networks worldwide at end of 2025; private 5G (predominantly NPN) is growing at 22%+ CAGR driven by manufacturing, ports, and industrial use cases
- Ethernet header compression in 5GS for industrial OT traffic
- SON and MDT (Minimization of Drive Test) for NR

### Release 17 (March 2022)

- **NTN (Non-Terrestrial Networks)** — LEO and GEO satellite integration into NR (TS 38.821); propagation delay / Doppler compensation; store-and-forward for IoT-NTN — **1/3** — Early commercial deployments emerging in 2025: Myriota launched first commercial 5G NTN IoT service in December 2025; Eutelsat completed the first trial over OneWeb satellite in February 2025; 90+ operators formed satellite partnerships but full NR-NTN deployment is nascent
- **RedCap (Reduced Capability NR)** — simplified 5G NR for IoT, wearables, and industrial sensors: 20 MHz bandwidth (FR1) / 100 MHz (FR2), 1–2 Rx antennas, relaxed processing timeline — **1/3** — Commercially launched by China Mobile, China Telecom, China Unicom, T-Mobile US, STC (Kuwait), and Dito (Philippines) as of April 2025; 30 operators across 21 countries investing; ecosystem is maturing with GCF-certified modules emerging
- **NR Multicast/Broadcast (MBS)** — point-to-multipoint sessions in NR for broadcast services and group communications — **0/3** — Standardized in Rel-17 (frozen 2022) with field tests conducted; no widespread commercial operator deployments yet as of 2026; China Mobile is piloting FeMBMS but commercial mass-market launches have not been announced
- **Small Data Transmission (SDT)** — data transfer while UE remains in RRC INACTIVE via RACH or configured grant; reduces wake-up signaling for IoT — **0/3** — Standardized in Rel-17 with test tools available (e.g., Amarisoft); no reported commercial operator deployments yet as of 2026; adoption is dependent on IoT device ecosystem maturity
- **Sidelink enhancements** — UE-to-network relay, UE-to-UE relay, power saving, improved resource allocation
- **MIMO Phase 2** — multi-TRP enhancements, SRS (Sounding Reference Signal) enhancements, Unified TCI (Transmission Configuration Indicator) framework
- **Positioning enhancements** — cm-level accuracy targets for IIoT; DL PRS enhancements; carrier phase measurement
- **NR coverage enhancements** — PUSCH/PUCCH repetition, Msg3/MsgA coverage improvements for cell-edge UEs
- **UE power saving Phase 2** — paging early indication, relaxed measurements for stationary UEs
- **QoE (Quality of Experience)** measurement collection and reporting
- **NWDAF enhancements Phase 2 (eNA)** — expanded AI/ML analytics functions in 5GC
- **Edge Computing enhancements** — improved support for edge application servers (EAS) and LADN (Local Area Data Network)
- FR2-2 study — spectrum exploration for 52.6–71 GHz
- AI/ML for NR study (TR 38.843) — foundational study item feeding Rel-18 normative work
- XR (Extended Reality) study — lays groundwork for Rel-18 XR features

---

## 5G-Advanced

### Release 18 (Frozen ~Dec 2024) — "5G-Advanced Phase 1"

- **AI/ML for NR air interface (normative)** — AI/ML-based CSI feedback compression and prediction, beam management prediction, positioning enhancement; lifecycle management (training, inference, monitoring, fallback); TS 38.843 — **0/3** — Frozen in Rel-18 (Dec 2024) with normative specifications complete; no commercial operator deployments reported as of April 2026; early vendor trials underway but pre-commercial
- **MIMO evolution** — 8 Tx UE codebook; completed Unified TCI framework; Coherent Joint Transmission (CJT) for multi-TRP; enhanced CSI (Type II, CRI-based); SRS enhancements for 8 Tx UE
- **XR (Extended Reality) support** — capacity enhancements for XR traffic patterns (periodic + jitter), UE power saving for XR, awareness-based scheduling — **0/3** — Standardized in Rel-18 (Dec 2024) with 3GPP XR framework defined; no commercial operator deployments of XR-specific 5G features as of April 2026; pre-commercial stage dependent on XR device ecosystem
- **Energy efficiency / Network Energy Savings** — gNB cell DTX, spatial element/SCS/bandwidth adaptation, SSB-less operation; UE relaxed measurements and PDCCH monitoring reduction — **0/3** — Standardized in Rel-18 with framework defined; operators are actively implementing energy-saving techniques but the specific Rel-18 normative features are pre-commercial as of April 2026; proprietary energy-saving features are deployed but Rel-18 specific standards are not yet commercially active
- **NTN enhancements Phase 2** — NR-NTN store-and-forward, handheld UE coverage improvements; IoT-NTN (eMTC/NB-IoT over satellite); discontinuous coverage handling
- **eRedCap (Enhanced RedCap)** — further bandwidth reduction to 5 MHz FR1; simplified peak rate requirements; targeting sensors adjacent to ambient IoT — **0/3** — Standardized in Rel-18 (June 2024); eRedCap modules are sampling as of early 2026 but commercial network deployments have not launched; ecosystem expected to mature through 2026-2027
- **Sidelink enhancements Phase 2** — carrier aggregation for sidelink, sidelink power saving, sidelink positioning, UE-to-UE relay improvements
- **Ambient IoT (study → early normative)** — ultra-low-power / zero-energy device concepts; backscatter and energy harvesting; inventory, command, positioning use cases — **0/3** — In study/early normative phase in Rel-18; no commercial deployments exist as of April 2026; technology is pre-commercial with ecosystem development just beginning
- **Positioning Phase 2** — low-power high-accuracy positioning, sidelink-based positioning, carrier phase positioning for cm-level accuracy
- **MBS enhancements** — MBS reception in RRC INACTIVE, inter-cell coordination for multicast
- **L1/L2-based mobility** — Lower Layer Triggered Mobility (LTM); Conditional Handover (CHO) enhancements; faster mobility at reduced signaling cost — **0/3** — Standardized in Rel-18 (Dec 2024); no commercial operator deployments reported as of April 2026; pre-commercial feature undergoing vendor validation
- **Duplex evolution studies** — Subband Full Duplex (SBFD), Cross-Division Duplex (XDD)

### Release 19 (Target freeze ~Late 2025 / Early 2026) — "5G-Advanced Phase 2"

- **AI/ML Phase 2** — AI/ML for mobility optimization and SON; enhanced lifecycle management (model transfer, federated learning concepts) — **0/3** — Release 19 specifications not yet frozen as of April 2026; pre-commercial study/normative work with no commercial deployments
- **Further MIMO** — beyond 8 Tx UE; advanced multi-TRP; distributed MIMO concepts
- **Network Sensing** — radar-like object detection, tracking, and environment monitoring integrated with communication functions (ISAC precursor) — **0/3** — Normative work in Rel-19 still in progress as of April 2026; no commercial deployments; ISAC remains a research and pre-standardization concept
- **XR evolution** — higher capacity, lower latency for immersive services; multi-modal XR support
- **NTN Phase 3** — direct satellite-to-device improvements; multi-connectivity (terrestrial + NTN); inter-satellite links study
- **Core network evolution** — NWDAF Phase 3 (AI/ML model sharing, federated analytics); NEF/CAPIF evolution; Network Slicing enhancements; enterprise-grade private/public network integration

---

## 6G Horizon

### Release 20 (Expected ~2027) — "6G Studies"

- First 6G study items on requirements, architecture, security, and radio evolution (TR 22.870 — 6G use cases; TR 38.914 — 6G scenarios and requirements) — **0/3** — Study phase only as of April 2026; no normative specifications or commercial deployments; 6G target commercial deployment is approximately 2030
- Sub-THz spectrum exploration (100–300 GHz)
- AI-native network design — AI embedded at every layer, not bolted on
- Integrated Sensing and Communication (ISAC)
- Extreme positioning accuracy (cm-to-mm targets)
- Sustainable and energy-efficient RAN and core design
- Digital twin networks
- Continuation of ambitious 5G-Advanced feature streams

### Release 21 (Expected ~2028–2029) — "First 6G Normative"

- First normative 6G air interface and core specifications — **0/3** — Expected normative work beginning ~2028-2029; no specifications exist as of April 2026; purely in study/pre-normative phase targeting 2030 commercial deployment
- Target commercial 6G deployment: ~2030
- New 6G air interface candidates (sub-THz, AI-native waveforms)
- Next-generation core architecture (AI-native SBA evolution)
- AI as a native first-class network element (not a feature overlay)
- Holographic communication and digital twin support
- Tbps-class peak data rates
- Sub-millisecond latency targets
- Massive connectivity: up to 10⁷ devices/km²

---

## Quick Reference: Generation Summary

| Generation | Key Releases | Peak Data Rate | Core Architecture | Key Innovation |
|---|---|---|---|---|
| 2G GSM | Ph1–Rel 98 | ~384 kbps (EDGE) | Circuit-switched + GPRS overlay | Mobile voice + basic packet data |
| 3G UMTS | Rel 99 – Rel 7 | ~28 Mbps (HSPA+) | CS + PS core, RNC-based RAN | Wideband data, IMS, HSPA |
| 4G LTE | Rel 8 – Rel 14 | ~3 Gbps (LTE-A CA) | All-IP EPC, flat eNB RAN | OFDMA, carrier aggregation, VoLTE |
| 5G NR | Rel 15 – Rel 17 | ~20 Gbps (mmWave) | 5GC SBA, gNB/CU-DU split | Massive MIMO, network slicing, URLLC, NTN |
| 5G-Advanced | Rel 18 – Rel 19 | Enhanced 5G | 5GC + AI/ML functions | AI/ML air interface, XR, ambient IoT |
| 6G | Rel 20 – Rel 21 | Tbps class | AI-native architecture | Sub-THz, ISAC, digital twins |

---

## Commercial Success Summary by Release

| Release | Total Features | Sum of Scores | Max Possible | % Success |
|---|---|---|---|---|
| GSM Phase 1 | 2 | 6 | 6 | 100% |
| GSM Phase 2 | 2 | 4 | 6 | 67% |
| GSM Release 96 | 1 | 1 | 3 | 33% |
| GSM Release 97 | 1 | 3 | 3 | 100% |
| GSM Release 98 | 1 | 3 | 3 | 100% |
| UMTS Release 99 | 1 | 3 | 3 | 100% |
| UMTS Release 4 | 3 | 2 | 9 | 22% |
| UMTS Release 5 | 2 | 6 | 6 | 100% |
| UMTS Release 6 | 2 | 3 | 6 | 50% |
| UMTS Release 7 | 3 | 5 | 9 | 56% |
| LTE Release 8 | 2 | 6 | 6 | 100% |
| LTE Release 9 | 3 | 5 | 9 | 56% |
| LTE Release 10 | 4 | 5 | 12 | 42% |
| LTE Release 11 | 1 | 0 | 3 | 0% |
| LTE Release 12 | 3 | 6 | 9 | 67% |
| LTE Release 13 | 5 | 10 | 15 | 67% |
| LTE Release 14 | 3 | 1 | 9 | 11% |
| NR Release 15 | 6 | 12 | 18 | 67% |
| NR Release 16 | 7 | 5 | 21 | 24% |
| NR Release 17 | 4 | 2 | 12 | 17% |
| 5G-Advanced Release 18 | 6 | 0 | 18 | 0% |
| 5G-Advanced Release 19 | 2 | 0 | 6 | 0% |
| 6G Release 20–21 | 2 | 0 | 6 | 0% |
| **TOTAL** | **66** | **88** | **198** | **44%** |

---

## Conclusions

### Overall Commercial Success Rate: 44%

Across 66 scored features spanning 30+ years of 3GPP standardisation, the industry converted less than half of standardised features into genuine commercial deployments (88 out of 198 possible points). More than half the features were either abandoned, deployed too narrowly to count, or have not yet had time to reach the market.

### Success by Tier

**Universal successes (3/3) — 23 features**
The clearest pattern is that features solving a broadly-felt problem with low coordination overhead almost always succeed. GSM voice/SMS, GPRS, EDGE, WCDMA, HSDPA/HSUPA, HSPA+, LTE, EPC, Carrier Aggregation, NB-IoT, LTE-M, FD-MIMO/AAS, Massive MIMO, Bandwidth Parts, NR NSA, IMS/VoLTE, and NPN (private 5G) all reached universal deployment. These features shared a common trait: a single operator could deploy unilaterally and immediately capture value, without needing coordinated action from device makers, regulators, or other operators.

**Partial deployments (1/3) — 19 features**
Features in this tier typically succeeded in advanced markets or specific verticals but never achieved the global ubiquity of tier-3 technologies. MMS peaked and is now in decline. Half-rate codecs were a capacity tool deployed in congested markets. eICIC/HetNet was widely deployed but the small-cell density needed to fully exploit it never materialised at scale. NR SA and Network Slicing are real deployments but remain a minority of 5G traffic. RedCap is commercially launching but still early. C-V2X PC5 is deployed in China and some US corridors but not globally.

**Not commercially deployed (0/3) — 24 features**
Three distinct failure modes appear here:

1. **Ecosystem coordination failures**: C-V2X/NR V2X sidelink, D2D/ProSe, and NR-U all required simultaneous deployment by operators, device makers, and (in V2X's case) automakers and road authorities. Without a common forcing function, adoption stalled.

2. **Technology superseded before maturing**: TD-SCDMA (single-country experiment abandoned within five years), 3G MBMS (bypassed directly by LTE eMBMS), Relay Nodes Rel-10 (overtaken by IAB and small cells with fibre), and Shortened TTI (absorbed into NR's native mini-slot design) were all standardised and then leapfrogged.

3. **Too early for the market**: CoMP, IAB, Small Data Transmission, and all Rel-18/19 5G-Advanced features have not had time to mature commercially. AI/ML for the air interface, XR enhancements, Ambient IoT, and eRedCap are standardised but pre-commercial as of April 2026.

### Generational Patterns

| Generation | % Success | Interpretation |
|---|---|---|
| 2G GSM (Ph1–Rel 98) | ~81% | Core voice/data features; strong commercial conversion |
| 3G UMTS (Rel 99–7) | ~58% | Strong base; MBMS and TD-SCDMA drag the average |
| 4G LTE (Rel 8–14) | ~52% | Carrier aggregation and IoT succeed; HetNet tools and V2X underperform |
| 5G NR (Rel 15–17) | ~37% | NSA/SA and Massive MIMO anchor success; sidelink, IAB, NTN still emerging |
| 5G-Advanced (Rel 18–19) | 0% | Pre-commercial; no Rel-18 features commercially deployed at scale yet |
| 6G (Rel 20–21) | 0% | Study phase only; target deployment ~2030 |

Success rates naturally decline with recency — newer features have had less time to deploy. The 37% figure for 5G NR Rel-15–17 will likely improve as SA deployments grow, network slicing matures, and RedCap/NTN devices reach the market in volume.

### Structural Insight

The data suggests 3GPP standardisation is most commercially effective when:

- The feature solves a capacity or coverage problem that operators face immediately
- A single operator can deploy and benefit without waiting for ecosystem coordination
- Device chipset support arrives quickly (within 1–2 years of spec freeze)

Conversely, features requiring multi-stakeholder ecosystems (automotive, broadcast, industrial IoT) consistently underperform their standardisation ambition, even when technically sound. This is a market coordination problem, not a standards quality problem.

---

*Based on 3GPP specifications. Release freeze dates are approximate. Feature details reference TS/TR documents from the relevant release series.*
