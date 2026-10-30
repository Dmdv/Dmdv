## Dmitry Dyachkov — low-latency systems & trading infrastructure

Hong Kong · C++ · Rust · Zig · Go

I build trading and exchange infrastructure: matching engines, market data pipelines and post-trade messaging, including at a leading crypto exchange in Hong Kong. Outside work I build things to see how fast they can really go, and measure them honestly.

### What I'm working on now
- **[market-maker-proto](https://github.com/Dmdv/market-maker-proto)**: a C++20 mock exchange plus a Python market-making client over WebSocket, with a latency lab built in. It uses coordinated-omission-aware benchmarks, exact-rank percentiles and peer-audited runs.
- **[hft-asm-l2-conflator](https://github.com/Dmdv/hft-asm-l2-conflator)**: an L2 order-book conflator written in AArch64 assembly, with an exclusive-shard pipeline, NEON VWAP and SPSC rings.
- **[nanosecond-stream-benchmark](https://github.com/Dmdv/nanosecond-stream-benchmark)**: zero-copy packet streaming and parsing, the same task in C++23, Rust, Zig 0.16 and OCaml 5, benchmarked head to head.
- **[async-worker-pool_zig](https://github.com/Dmdv/async-worker-pool_zig)**: a lock-free async worker pool in Zig 0.16, with a zero-CAS SPSC ring (65M ops/s), comptime arenas and SIMD. There's also a **[C11 + Rust FFI version](https://github.com/Dmdv/async-worker-pool)** with zero-copy claim/commit and sub-microsecond latency.
- **[cpp26-systems-stack](https://github.com/Dmdv/cpp26-systems-stack)**: a C++26 systems playground covering async I/O, parallelism, JSON and RPC (Asio, Beast, stdexec, TBB, simdjson, gRPC).
- **[review-gate](https://github.com/Dmdv/review-gate)**: a GitHub Action that enforces strict PR review. It requires a quorum of review bots, resolved threads and green CI, with no bypass.

### Background
- I've spent 23 years in backend engineering, the last decade in fintech and trading, and 5 years in blockchain.
- I've built exchange components (a proprietary matching engine, FIX/ITCH/OUCH connectivity) and post-trade messaging for a large crypto exchange.
- In blockchain I've built Ethereum, Solana and Cosmos indexers, CosmWasm and Solidity contracts, and trading bots.
- My infrastructure stack is Kubernetes, Terraform and Docker. I wrote C# for 15 years and Python is still everyday glue.

### Currently curious about
MEV, Solana and Drift Protocol, Halo2 zero-knowledge proofs, and how far Zig can be pushed in hot paths.

[LinkedIn](https://www.linkedin.com/in/ddyachkov)
