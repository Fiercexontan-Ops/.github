# Maintainers

This document defines the maintainers, responsibilities, and escalation paths
for the Fiercexontan organization repositories.

Our goal is to ensure security, transparency, and timely responses to issues,
especially those related to cryptographic assets, wallets, and blockchain systems.

---

## 🧩 Roles & Responsibilities

### 🔐 Security Team
**Scope**
- Security vulnerabilities
- Wallet compromise reports
- Seed phrase / private key exposure
- Malicious dApp or phishing incidents
- Signature or smart-contract exploits

**Responsibilities**
- Review all security-labeled issues
- Ensure sensitive data is not disclosed publicly
- Coordinate responsible disclosure
- Escalate critical incidents immediately

**Team**
- @samchodd (Lead Security Reviewer)

---

### ⛓️ Transaction & Network Team
**Scope**
- Failed or stuck transactions
- Gas, nonce, or mempool issues
- Network congestion or RPC errors

**Responsibilities**
- Analyze transaction-level failures
- Request necessary technical details (TX hash, chain, time)
- Guide users on safe remediation steps

**Team**
- @maestro-lab9

---

### 👛 Wallet & Access Team
**Scope**
- Wallet restore issues
- Balance discrepancies
- Login or decryption problems
- Hardware and software wallet integrations

**Responsibilities**
- Assist with wallet diagnostics
- Identify user-side vs protocol-side issues
- Provide safe recovery guidance

**Team**
- @tommy88734

---

### 📊 DeFi & Smart Contract Team
**Scope**
- Token swaps
- Liquidity pools
- Bridges and cross-chain activity
- Smart contract approvals or failures

**Responsibilities**
- Review DeFi interaction issues
- Validate contract behavior
- Identify protocol risks or misuse

**Team**
- @maestro-lab9  
- @tommy88734

---

## 🚨 Severity & Escalation

### Security Severity Levels

| Level | Description |
|------|------------|
| **High** | Active exploit, fund loss, credential exposure |
| **Medium** | Potential vulnerability, suspicious behavior |
| **Low** | Best-practice concern or non-exploitable issue |

**High severity issues**
- Are labeled `priority: critical`
- Trigger immediate Security Team attention
- May be moved to private discussion channels

---

## 🔁 Assignment & Rotation

Issue assignment is automated via the organization’s GitHub App (Probot),
based on detected category and rotation rules.

Maintainers may reassign issues if additional expertise is required.

---

## 📬 Contact & Coordination

For sensitive matters:
- Do **NOT** post private keys, seed phrases, or passwords
- Please adhere to the provided contact's instructions.

General support:
- Issues should be opened using the appropriate issue template
- Provide only non-sensitive technical details

---

## 🔒 Final Notes

Maintainers are expected to:
- Act professionally and respectfully
- Protect user privacy at all times
- Follow responsible disclosure practices
- Maintain the integrity and trust of the organization

This document may be updated as the organization evolves.
