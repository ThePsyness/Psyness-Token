# PsynessToken Deployment Audit Trail

This document records every contract creation attempt from wallet `0x5eC1Ef0a004728F7649670f945DD81E0BD43c489`, leading to the final verified PsynessToken (PSS) on BNB Chain.

---

## ✅ Final Verified Contract

| Token         | Contract Address                                                                 | Status          | Notes                                                                 |
|---------------|-----------------------------------------------------------------------------------|------------------|-----------------------------------------------------------------------|
| Psyness (PSS) | [0x3571494ec9219331992b79a45431d95483330420](https://bscscan.com/address/0x3571494ec9219331992b79a45431d95483330420) | ✅ Verified       | Final deployment with verified source, ABI exposed, token tracker active |

---

## ❌ Previous Attempts

| Token         | Contract Address                                                                 | Status          | Notes                                                                 |
|---------------|-----------------------------------------------------------------------------------|------------------|-----------------------------------------------------------------------|
| PsynessToken  | [0x538c8d44a9c654c86152b147a6cde177af175ef51488ff07c4b38b62745dceae](https://bscscan.com/address/0x538c8d44a9c654c86152b147a6cde177af175ef51488ff07c4b38b62745dceae) | ❌ Oversized      | 20× gas of final version, failed verification due to bloated bytecode |
| —             | [0x6ee32c8e8ad2221e0c3d57f12b12d85533e68cc5e2bf9797574d555e4ecf8dbd](https://bscscan.com/address/0x6ee32c8e8ad2221e0c3d57f12b12d85533e68cc5e2bf9797574d555e4ecf8dbd) | ❌ Stub            | Minimal gas, likely placeholder or failed deployment                  |
| Context       | [0x2ffcce491c576d39d8c7c837a71f21eb0bf662d0904d2ea1d895b88a89bb762e](https://bscscan.com/address/0x2ffcce491c576d39d8c7c837a71f21eb0bf662d0904d2ea1d895b88a89bb762e) | ❌ Wrong contract | Remix defaulted to OpenZeppelin’s `Context` base class                |
| Context       | [0xc0ab758386d7d9d84ea5956018869fc6f8a6088b6409e80e6e18d1851a01ce6d](https://bscscan.com/address/0xc0ab758386d7d9d84ea5956018869fc6f8a6088b6409e80e6e18d1851a01ce6d) | ❌ Duplicate       | Another `Context` deployment due to Remix artifact confusion          |
| PsynessToken  | [0x73d6d01b070f6994d17a711910f9c0c37c5838602d37a59d809901e93dd6836c](https://bscscan.com/address/0x73d6d01b070f6994d17a711910f9c0c37c5838602d37a59d809901e93dd6836c) | ❌ Bytecode mismatch | Correct name, failed verification due to artifact mismatch            |
| —             | [0x41d52ed376b5000063e4cc6b80e1938b0261ba66d43004e66e6e4252b39f6cc4](https://bscscan.com/address/0x41d52ed376b5000063e4cc6b80e1938b0261ba66d43004e66e6e4252b39f6cc4) | ❌ Not verified    | No ABI, no ERC20 interface                                            |
| —             | [0xcc9398260ea40f27026f008883dd27d4777adb0e954af46dd75d0135f6e8a091](https://bscscan.com/address/0xcc9398260ea40f27026f008883dd27d4777adb0e954af46dd75d0135f6e8a091) | ❌ Not verified    | No ERC20 metadata                                                     |
| —             | [0x0fe515f5b55aa648c734d274af7d87663ce90dfa90b6c62d70d7a093c6668e9c](https://bscscan.com/address/0x0fe515f5b55aa648c734d274af7d87663ce90dfa90b6c62d70d7a093c6668e9c) | ❌ No token logic  | Likely test or miscompiled contract                                   |
| —             | [0x7a90feeba8873c412234916ef12e39b6146aa85d05be4d6181b052c649cd53c4](https://bscscan.com/address/0x7a90feeba8873c412234916ef12e39b6146aa85d05be4d6181b052c649cd53c4) | ❌ No token logic  | No ABI, no ERC20 interface                                            |
| —             | [0x9566e349bda67de39bc931135b55ec0e5241f44e](https://bscscan.com/address/0x9566e349bda67de39bc931135b55ec0e5241f44e) | ❌ No token tracker | Unverified contract, no ERC20 metadata or activity                    |

---

## 🧠 Notes

- All deployments were made from the same wallet: `0x5eC1Ef0a004728F7649670f945DD81E0BD43c489`
- Final verified contract uses minimal gas and matches flattened source exactly
- Audit trail reflects every attempt, including failed verifications and base-class artifacts

---

## 📬 Contact

For questions or verification requests:  
📧 `vibes@psyness.com`


---

## 🔗 Related Resources

- [Psyness Manifesto](https://www.psyness.com/the-psyness-pss-manifesto-awakening-the-psyche-in-a-cyber-cosmic-age/#token-audit-trail)  
- [Homepage](https://psyness.com)  
- [GitHub Repository](https://github.com/ThePsyness/Psyness-Token)

---

For questions or verification, contact: `vibes@psyness.com`
