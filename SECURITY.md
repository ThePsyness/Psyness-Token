# Psyness Token (PSS) — Security Notes

This document outlines the security architecture, verification strategy, and known limitations of the PsynessToken smart contract.

---

## ✅ Standards Used

- Built on [OpenZeppelin Contracts v4.9.3](https://github.com/OpenZeppelin/openzeppelin-contracts)
- Inherits from:
  - `ERC20`
  - `Ownable`
- SPDX License: MIT

---

## 🔐 Ownership Model

- Contract is `Ownable`  
- No minting, burning, or pausing functions  
- No proxy or upgradeable patterns used  
- No renounceOwnership call executed

---

## 🔎 Verification Strategy

- Flattened using Remix and manually cleaned for unused imports  
- Verified on BscScan with exact bytecode match  
- ABI exposed and constructor parameters confirmed  
- Final verified contract: [`0x3571494ec9219331992b79a45431d95483330420`](https://bscscan.com/address/0x3571494ec9219331992b79a45431d95483330420)

---

## ⚠️ Known Limitations

- No reentrancy guards (not needed for pure ERC20)  
- No custom logic beyond standard ERC20  
- Contract is not upgradeable — future changes require redeployment

---

## 📬 Contact

For security disclosures or technical questions:  
📧 `vibes@psyness.com`
