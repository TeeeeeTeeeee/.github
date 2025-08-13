# TeeTee

**Private, affordable, high-performance LLMs via verifiable TEE sharding.**

## What we do
- **Shard & run** large models across multiple TEEs (Phala) with on-chain attestation of code + model hash.
- **Two ways to use:**
  - **Host a shard** → profit share + direct usage.
  - **Buy tokens** with ETH on **Base** → pay-per-query in chat.
- **Smart contracts** automate payments, usage metering, and revenue split.

## Why it matters
**Data stays private · Costs are pooled · No single-GPU/TEE limits · Decentralized & fault-tolerant.**

## Status (PoC)
TinyLlama split into **2 shards**; single `/generate` endpoint; both TEEs post attestation reports.

## Roadmap
- **Vertical:** more shards → bigger models.
- **Horizontal:** P2P mesh → failover & scale.

## Links (From our old prototype)
- **Demo:** https://tee-tee.vercel.app/
- **Setup:** https://github.com/derek2403/TeeTee/blob/main/TeeDockerFiles/README.md
- **Contract (Base Sepolia):** [`0x396061f4eba244416ca7020fa341f8f6a990d991`](https://sepolia.basescan.org/address/0x396061f4eba244416ca7020fa341f8f6a990d991)

## Team
Liew Qi Jian · Phen Jing Yuan · Edwina Hon Kai Xin · Cedric Chung Theng Fung · Tan Zhi Wei · Marcus Tan
