# **Mats Heming Julner (@recurmj)**  
Creator of the **permissioned-pull architecture**, discoverer of **κ₍c₎ (the consent invariant)**, and founder of **Recur Labs**.

My work focuses on **authorization primitives**, programmable intent, and the formal structures that connect **human intention → authorization → execution → state → consensus** across distributed systems.

I author **RIP-001 through RIP-010**, defining the open standard for consent-based digital value flow.

---

## 📚 **Canonical Work**

### **Recur Standard (RIP-001 → RIP-010)**  
The open, non-custodial flow architecture built on portable authorization.

👉 **GitHub — Recur Standard**  
https://github.com/recurmj/recur-standard

👉 **Recur Canon (primary archive)**  
https://recurlabs.org/canon


## 🧵 **Ethereum Magicians Discussions (RIPs)**  
Primary public threads establishing the standard and formal discussions with the Ethereum research community.

👉 **RIP-001 · Permissioned-Pull Objects (ERC Draft Discussion)**  
https://ethereum-magicians.org/t/draft-erc-rip-001-permissioned-pull-standard-consented-flow-layer-for-digital-value/25931

👉 **RIP-009 · Cross-Network Consent Verification Standard (ERC Draft Discussion)**  
https://ethereum-magicians.org/t/draft-erc-rip-009-cross-network-consent-verification-standard/26637/2

(These threads document the early review, technical debate, and standardization pathway for the core permissioned-pull primitives and the consent invariant κ₍c₎.)

---

## 🔷 **Recur Improvement Proposals (RIPs)**  
_Descriptions as published on recurlabs.org:_

### **RIP-001 · Permissioned-Pull Objects**  
Signed, revocable pull rights.  
A wallet can authorize _“you may pull up to X under these limits.”_  
This is the core primitive.

### **RIP-002 · Consent Registry**  
A shared on-chain index of active consents, revocations, and cumulative pulls.  
Wallets and auditors can verify _“is this still allowed?”_ without trusting an app.

### **RIP-003 · Cross-Network Flow Intent**  
A signed instruction describing where liquidity should move across domains  
(which chain is over-funded, which is under-funded, how much may move, by whom, and until when).

### **RIP-004 · Non-Custodial Rebalancing**  
Execution logic for RIP-003.  
Liquidity moves from surplus → deficit domains using permissioned pull,  
without bridges, wraps, or pooled custody.

### **RIP-005 · Flow Channels**  
Continuous, rate-limited pull between a grantor and grantee.  
Enables streaming payouts, automated treasury draining, and recurring settlement — all under pause and revoke.

### **RIP-006 · Universal Clock & Adaptive Routing**  
A shared timing model and router logic.  
Channels across chains stay synchronized on rate limits and allocation targets  
so no venue becomes over-drawn.

### **RIP-007 · Programmatic Policy Objects**  
Programmatic policy on top of consent: spend ceilings, jurisdiction limits, KYC rules, allowed destinations, rate guards, emergency stops — the compliance surface institutions require.

### **RIP-008 · Settlement Mesh**  
Network-wide equilibrium.  
Liquidity allocates itself toward target weights across chains, custodians, and venues using only revocable consent — no custody.

### **RIP-009 · Cross-Network Consent Verification Standard**  
Formalization of **κ₍c₎**.  
Defines how independent systems reconstruct the same domain separator and struct hash  
and reach the same verdict on a signature — enabling consent continuity across networks without shared state.

### **RIP-010 · Consent State Machine Standard**  
Lifecycle of a Permissioned-Pull Object:  
grant → activation → use → revocation → expiry.  
Describes how consent state is propagated and synchronized across independent execution environments.

---

## 🔶 **The Consent Invariant — κ₍c₎**

κ₍c₎ is the first identified **cross-system invariant** governing the meaning and validity of a signed authorization _independent of network state or consensus_.

It formalizes:

- portable intent  
- identity above networks  
- authorization-based continuity  
- pull-based value flow  

👉 **Formal Definition (v1.0)**  
https://github.com/recurmj/recur-standard/blob/main/docs/formal-kc-definition.md

---

## 🧩 **Architectural Focus Areas**

- Consent as a first-class primitive  
- Portable authorization identity (PPOs)  
- Cross-network intent (FlowIntent)  
- Pull-based execution (PullSafe)  
- Consent invariance (κ₍c₎)  
- Network-agnostic continuity  
- Domain separation & struct hashing  
- Rebalancing & routing without custody  
- Formal hierarchy:  
  **Intent → Authorization → Execution → State → Consensus → Network**

---

## 🛠 **Reference Implementations**

Included in the Recur Standard repository:

- **RecurPullSafeV2**  
- **RecurConsentRegistry**  
- **FlowIntentRegistry**  
- **Universal Clock / Adaptive Router**  
- **Settlement Mesh**  
- **Consent State Machine**  
- **Cross-network test vectors & Foundry scripts**

👉 https://github.com/recurmj/recur-standard

---

## 🔬 **Technical Papers & Canon**

- **The Discovery of the Consent Constant (κ₍c₎)**  
- **The Geometry of Consent**  
- **Recur Whitepaper / Flow Layer Specification**

Available via:  
👉 https://recurlabs.org

---

## 📨 **Contact**

- **Canonical Website:** https://recurlabs.org  
- **Twitter:** https://twitter.com/matsjulner  
- **Email:** contact@recurlabs.org  

---

## 🧭 **Mission**

To define the missing layer of digital value flow by establishing **consent as the governing primitive**, replacing push-based financial architecture with **pull-based, authorization-driven systems** grounded in κ₍c₎.

---
