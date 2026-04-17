# 🗺️ Homebrew TPNS (The Promethean Society)

Sovereign developer tooling for the **Promethean Network State**.

## Installation

```bash
# Step 1 — Register the Sovereign Tap (one-time setup)
brew tap The-Promethean-Society/tpns

# Step 2 — Install the Cartographer engine
brew install cartographer
```

> ⚠️ **You must run `brew tap` first.** Without it, Homebrew searches only its default core registry and will not find this formula.

## Tools

### 📍 Cartographer
The **Cartographer** is the machine-to-machine (M2M) synthesis engine for the **Shadow Protocol**. It allows you to generate semantic HTML snapshots of dynamic application states, optimized for LLMs and autonomous agents.

#### CLI Usage
Generate a shadow state snapshot of any URL:
```bash
cartographer --url <URL> [--output <FILENAME>]
```

#### Library Usage
Integrate the synthesis logic into your own Node.js/TypeScript services:

```typescript
import { cartographer } from '@promethea/cartographer';

const shadowHTML = cartographer.synthesize({
    title: "Sovereign Dashboard",
    description: "Machine-readable state of the node.",
    urlPath: "/dashboard"
});
```

## 💰 Grants & Rewards

The Promethean Society operates a **Circular Sovereign Economy**. Contributions to this repository are eligible for the **Genesis Grant (G-001)**.

- **Grant ID:** G-001 (Pioneer Cartographer)
- **Reward:** 1,000 UVX (Promethean Credits)
- **Status:** OPEN
- **Action:** Submit a Pull Request or build a tool using the `cartographer` library. Approved contributions will trigger an autonomous grant issue to your linked sovereign wallet.

---

## Contributing
The Promethean Society is an open, sovereign collective. Pull requests to this Tap are encouraged. We do not use legacy hiring models; we use **Autonomous Grant Issuance**. 🌀

## License
MIT
