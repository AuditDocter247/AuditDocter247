# 🛡️ AuditDocter247 — Smart Contract Security Auditor

**UK 🇬🇧 | Independent Solidity Auditor | Building in Public**

---

## 👋 About

I'm a UK-based independent smart contract security auditor. I do careful, manual, line-by-line reviews of Solidity contracts — finding the access-control flaws, reentrancy paths, oracle-manipulation vectors, and accounting bugs that automated scanners miss.

Every finding in my portfolio below was reasoned through by hand and written up in full, with proof-of-concept walkthroughs and concrete fixes. I document my work publicly so you can judge the quality before you ever contact me.

**My mission:** help Web3 projects catch vulnerabilities before they become exploits — at a price that makes sense for small and early-stage teams.

---

## 📋 Portfolio

### Findings

**Finding #004 — Oracle Manipulation via Spot Price**
*LendingPool.sol · Critical · 09 July 2026*
Collateral over-valuation via a manipulable single-pool spot price, enabling flash-loan-funded over-borrowing.
[View report →](https://auditdocter247.github.io/Audit-Portfolio/finding-004-lendingpool-oracle-manipulation.html)

**Finding #003 — Unprotected Initialiser Front-Running**
*DeFiTreasury.sol · Critical · 05 July 2026*
Ownership hijack via a race condition on an unguarded `initialise()` in a proxy pattern.
[View report →](https://auditdocter247.github.io/Audit-Portfolio/finding-003-defitreasury-initialise.html)

**Finding #002 — Unrestricted Ownership Takeover**
*AdminVault.sol · Critical · 29 June 2026*
Missing access control on `setOwner()` allowing complete contract takeover.
[View report →](https://auditdocter247.github.io/Audit-Portfolio/finding-002-access-control.html)

**Finding #001 — Reentrancy Vulnerability**
*EtherStore.sol · Critical · 27 June 2026*
External call before state update enabling recursive withdrawal.
[View report →](https://auditdocter247.github.io/Audit-Portfolio/finding-001-etherstore.html)

### Independent Reviews

**Anisian (ANI) — Clean Review**
*Live contract on Base · 11 July 2026*
Verified all four publicly-claimed security properties (no mint, no admin, no pause, no upgrade) against deployed source — all confirmed accurate. A clean review is as much a professional skill as finding a bug.
[View report →](https://auditdocter247.github.io/Audit-Portfolio/review-anisian-clean-report.html)

**Full portfolio:** [auditdocter247.github.io/Audit-Portfolio](https://auditdocter247.github.io/Audit-Portfolio/)

---

## 🎯 Services

- **Smart Contract Security Reviews** — Solidity & EVM-compatible chains
- **Pre-Mainnet Vulnerability Reviews** — catch bugs before launch
- **Clear, Actionable Reports** — severity-rated findings, PoC walkthroughs, plain-English fixes

Current focus: single-contract reviews (standard token, vault, staking, and access-control patterns). Founder-rate pricing while I build my client track record — [get in touch](#-contact) to discuss scope.

---

## 🔧 How I Work

Manual review is the core of every audit — no tool replaces reading the code and reasoning through the logic. I supplement that with static analysis (Slither) and use AI assistants to accelerate research and report drafting. The judgement, the findings, and the sign-off are mine.

---

## 📚 Background & Ongoing Study

- Solidity fundamentals, EVM mechanics, and common vulnerability classes (SWC Registry)
- Deep-dives on historical DeFi exploits and their root causes
- Tooling: Slither, Mythril, Foundry, Hardhat
- Active on CodeHawks, Sherlock, and Immunefi

---

## 🤝 Contact

- **📧 Email:** AuditDocter247@proton.me
- **🐦 X / Twitter:** @AuditDocter247

**Open to:** audit enquiries, pre-launch security reviews for Web3 founders, and collaboration with other auditors.

---

*⚡ Building in public since June 2026 ⚡*
