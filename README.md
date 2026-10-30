## Dmitry Dyachkov — low-latency systems & trading infrastructure

Hong Kong · C++ · Rust · Zig · Go

I build trading and exchange infrastructure: matching engines, market data pipelines and post-trade messaging, including at a leading crypto exchange in Hong Kong. Outside work I build things to see how fast they can really go, and measure them honestly.

### What I'm working on now
- A C++20 mock exchange plus a Python market-making client over WebSocket, with a latency lab built in. It uses coordinated-omission-aware benchmarks, exact-rank percentiles and peer-audited runs.
- An L2 order-book conflator written in AArch64 assembly, with an exclusive-shard pipeline, NEON VWAP and SPSC rings.
- Zero-copy packet streaming and parsing, the same task in C++23, Rust, Zig 0.16 and OCaml 5, benchmarked head to head.
- A lock-free async worker pool in Zig 0.16, with a zero-CAS SPSC ring (65M ops/s), comptime arenas and SIMD. There's also a C11 + Rust FFI version with zero-copy claim/commit and sub-microsecond latency.
- A C++26 systems playground covering async I/O, parallelism, JSON and RPC (Asio, Beast, stdexec, TBB, simdjson, gRPC).
- A GitHub Action that enforces strict PR review. It requires a quorum of review bots, resolved threads and green CI, with no bypass.

### Background
- I've spent 23 years in backend engineering, the last decade in fintech and trading, and 5 years in blockchain.
- I've built exchange components (a proprietary matching engine, FIX/ITCH/OUCH connectivity) and post-trade messaging for a large crypto exchange.
- In blockchain I've built Ethereum, Solana and Cosmos indexers, CosmWasm and Solidity contracts, and trading bots.
- My infrastructure stack is Kubernetes, Terraform and Docker. I wrote C# for 15 years and Python is still everyday glue.

### Currently curious about
MEV, Solana and Drift Protocol, Halo2 zero-knowledge proofs, and how far Zig can be pushed in hot paths.

[LinkedIn](https://www.linkedin.com/in/ddyachkov)
